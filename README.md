# Análise de Dados HPLC Otimizada

Uma aplicação web de página única (SPA) concebida para simplificar o processamento, análise e visualização de dados resultantes de Cromatografia Líquida de Alta Eficiência (HPLC).

## 🚀 Funcionalidades Principais

* **Gestão de Moléculas:** Registo de moléculas com parâmetros personalizáveis (tempo de referência, variância máxima, fatores de conversão, diluição e correção).
* **Processamento de Amostras:** Importação em massa de dados brutos de HPLC por texto (copiar e colar). Agrupamento fácil de replicatas para formar amostras consolidadas.
* **Análise Estatística:** Cálculo automático de médias e desvios padrão para as amostras processadas, lidando autonomamente com valores não detetados.
* **Visualização de Dados:** Geração de gráficos interativos (barras ou linhas) utilizando o Chart.js, permitindo a comparação de múltiplas métricas e conjuntos de dados no mesmo plano.
* **Exportação Simples:** Cópia dos resultados processados diretamente para o formato CSV (compatível com Excel, Google Sheets, etc.) através da área de transferência.
* **Sincronização e Cópia de Segurança:** O estado da aplicação é guardado automaticamente no seu navegador (`localStorage`). Inclui opções para exportar/importar os dados via formato JSON para sincronização entre diferentes computadores ou dispositivos.

## 🛠️ Tecnologias Utilizadas

* **HTML5 / CSS3 / JavaScript (Vanilla):** Sem necessidade de frameworks complexas ou *build steps*.
* **[Tailwind CSS](https://tailwindcss.com/):** Utilizado via CDN para uma interface de utilizador limpa, moderna e responsiva.
* **[Chart.js](https://www.chartjs.org/):** Para a renderização flexível dos gráficos.
* **[Phosphor Icons](https://phosphoricons.com/):** Para uma iconografia consistente.

## 📖 Como Utilizar

Como se trata de uma aplicação web estática baseada no lado do cliente (sem backend), a instalação é imediata:

1. **Descarregue ou clone** os ficheiros para a sua máquina local.
2. Certifique-se de que os recursos visuais (como o `logohplc.png` na pasta `assets`) estão no local correto, se aplicável.
3. Dê um duplo clique no ficheiro `index.html` para abri-lo no seu navegador web preferido (Chrome, Firefox, Edge, Safari).

### Fluxo de Trabalho (Guia Rápido)

1. **Aba Parâmetros:** Adicione as moléculas que pretende analisar. Defina o tempo de retenção esperado (Tempo de Referência) e a margem de erro aceite (Variância Máxima).
2. **Aba Amostras:** Cole os dados brutos da corrida de HPLC na área de texto dedicada. Defina um nome para a sua amostra (ex: `Cultura_24h`) e selecione as replicatas correspondentes que o sistema identificou. Prima "Processar".
3. **Aba Resultados:** Consulte a tabela gerada com as médias e desvios padrão. Utilize os botões de ação em lote para apagar ou copiar os resultados para exportação.
4. **Aba Gráfico:** Construa as suas comparações visuais selecionando o tipo de gráfico, o conjunto de amostras e as métricas que pretende comparar (Média ou Desvio Padrão).

## 👨‍💻 Sobre o Projeto e o Criador

Esta ferramenta foi desenvolvida com dedicação pelo **Ítalo**, estudante de biologia e entusiasta de ciência e programação. O objetivo primordial do projeto é aliviar o trabalho moroso de investigadores e estudantes na triagem de ficheiros de texto oriundos de equipamento HPLC.

Se esta ferramenta lhe ajudou a otimizar o seu fluxo de trabalho analítico, considere apoiar a manutenção do projeto pagando um café ao programador através da chave **PIX**: `italo.faria0@gmail.com`. O seu apoio faz toda a diferença!
