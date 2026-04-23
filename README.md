# Análise de Dados HPLC Otimizada

Uma aplicação web de página única (SPA) concebida para simplificar o processamento, análise e visualização de dados resultantes de Cromatografia Líquida de Alta Eficiência (HPLC).

## 🚀 Funcionalidades Principais

* **Gestão de Moléculas:** Registo de moléculas com parâmetros personalizáveis (tempo de referência, variância máxima, fatores de conversão, diluição e correção).
* **Processamento de Amostras:** Importação em massa de dados brutos de HPLC por texto (copiar e colar). Agrupamento fácil de replicatas para formar amostras consolidadas.
* **Análise Estatística:** Cálculo automático de médias e desvios padrão para as amostras processadas, lidando autonomamente com valores não detectados.
* **Visualização de Dados:** Geração de gráficos interativos (barras ou linhas) utilizando o Chart.js, permitindo a comparação de múltiplas métricas e conjuntos de dados no mesmo plano.
* **Exportação Simples:** Cópia dos resultados processados diretamente para o formato CSV (compatível com Excel, Google Sheets, etc.) através da área de transferência.
* **Sincronização e Cópia de Segurança:** O estado da aplicação é guardado automaticamente no seu navegador (`localStorage`). Inclui opções para exportar/importar os dados via formato JSON para sincronização entre diferentes computadores ou dispositivos.

## 🛠️ Tecnologias Utilizadas

* **HTML5 / CSS3 / JavaScript (Vanilla):** 
* **[Tailwind CSS](https://tailwindcss.com/):** Para uma interface de usuário limpa, moderna e responsiva.
* **[Chart.js](https://www.chartjs.org/):** Para a renderização flexível dos gráficos.
* **[Phosphor Icons](https://phosphoricons.com/):** Para uma iconografia consistente.

## 📖 Como Utilizar

1. **Aba Parâmetros:** Adicione as moléculas que pretende analisar. Defina o tempo de retenção esperado (Tempo de Referência) e a margem de erro aceitável (Variância Máxima).
2. **Aba Amostras:** Cole os dados brutos da corrida de HPLC na área de texto dedicada. Defina um nome para a sua amostra (ex: `Cultura_24h`) e selecione as replicatas correspondentes que o sistema identificou. Pressione "Processar...".
3. **Aba Resultados:** Consulte a tabela gerada com as médias e desvios padrão. Utilize os botões de ação em lote para apagar ou copiar os resultados para exportação.
4. **Aba Gráfico:** Construa as suas comparações visuais selecionando o tipo de gráfico, o conjunto de amostras e as métricas que pretende comparar (Média ou Desvio Padrão).


`O arquivo 'data.json' contem dados de exemplo para testar a ferramenta.`
