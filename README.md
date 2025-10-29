### 🧾 Sistema de Cotações e Lista de Compras

Este projeto é um **sistema simples e completo** desenvolvido em **HTML, CSS e JavaScript**, utilizando bibliotecas externas robustas para processamento de dados e visualização. Seu objetivo principal é **automatizar a comparação de preços de fornecedores para otimizar a geração da lista de compras final**, garantindo a escolha sempre do menor preço.

#### ⚙️ Funcionalidades Principais:

* **Entrada de Itens:** Permite a inserção manual de itens em falta ou a importação rápida através de um arquivo Excel (XLSX).
* **Processamento de Cotações:** Recebe e processa arquivos de cotação de até **6 fornecedores** diferentes.
* **Leitura Inteligente de Excel:** Implementado para **ler e extrair dados reais (código e preço)** de planilhas Excel (XLSX/XLS) enviadas pelos fornecedores, substituindo a simulação por dados concretos.
* **Análise Automática de Preços:** Realiza o cruzamento da lista de itens em falta com os dados de cotação para identificar e selecionar automaticamente o menor preço item por item, garantindo a **redução de custos**.
* **Geração da Lista de Compras Aprovada:** Cria a lista final consolidada, indicando o item, o fornecedor escolhido e o valor total da compra.
* **Relatórios e Visualização:** Exibição detalhada da análise de preços, com gráficos (Chart.js) que mostram a performance de cada fornecedor (itens ganhos e valor total aprovado).
* **Exportação e Compartilhamento:** Funcionalidades de exportação da lista final em **PDF e Excel**, além de opções diretas de compartilhamento via **WhatsApp e E-mail**.
* **Interface:** Design moderno e limpo, com cores suaves e agradáveis, pensado para uma melhor experiência visual e usabilidade em 3 etapas claras.

#### 🛠️ Tecnologias Utilizadas:

* **Frontend:** HTML5, CSS3, JavaScript (ES6+)
* **Processamento de Dados:** [SheetJS / XLSX](https://sheetjs.com/) (para leitura e escrita de Excel)
* **Visualização:** [Chart.js](https://www.chartjs.org/) (para gráficos de análise)
* **Exportação:** [jsPDF](https://raw.githack.com/MrRio/jsPDF/master/docs/) (para exportação em PDF)

#### 🧍‍♂️ Desenvolvido por

**Glailton Nascimento**
📅 Versão otimizada – Outubro de 2025
