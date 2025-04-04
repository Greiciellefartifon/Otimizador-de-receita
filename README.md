Sistema de Otimização de Receitas - Engenharia de Alimentos
Descrição
Este projeto é um sistema web para otimização de receitas na área de Engenharia de Alimentos, com foco no equilíbrio entre custo, valor nutricional e qualidade. A aplicação permite:

Cadastro e gerenciamento de receitas

Cálculo automático de informações nutricionais

Otimização de formulações com diferentes objetivos

Análise de sensibilidade dos parâmetros

Cálculo de preço de venda

Funcionalidades
1. Cadastro de Receitas
Adição de ingredientes com quantidade e preço

Cálculo automático de valores nutricionais

Busca de dados nutricionais (simulação de API)

Armazenamento local das receitas

2. Otimização de Formulações
Três objetivos de otimização:

Minimizar custo

Maximizar valor nutricional

Equilíbrio custo-nutrição

Definição de restrições nutricionais e de custo

Comparação entre receita original e otimizada

Exportação de resultados para PDF e Excel

3. Análise de Sensibilidade
Avaliação do impacto de mudanças nos parâmetros

Geração de gráficos e tabelas comparativas

Exportação de dados para Excel

4. Cálculo de Preço de Venda
Considera custos de produção, embalagem e impostos

Cálculo de margem de lucro em diferentes cenários

Visualização gráfica da relação preço-lucro

Tecnologias Utilizadas
HTML5, CSS3 e JavaScript puro

Chart.js para visualização de gráficos

Papa Parse para manipulação de dados

jsPDF para geração de PDFs

SheetJS (xlsx) para exportação em Excel

Armazenamento local (localStorage) para persistência de dados

Como Utilizar
Abra o arquivo HTML em qualquer navegador moderno

Navegue pelas abas para acessar as diferentes funcionalidades

Na aba "Nova Receita", cadastre os ingredientes e informações básicas

Use a aba "Otimização" para melhorar sua receita conforme seus objetivos

Na aba "Análise", explore como diferentes parâmetros afetam seus resultados

Calcule o preço de venda ideal na aba correspondente

Banco de Dados Nutricional
O sistema inclui um banco de dados simplificado com informações nutricionais de ingredientes comuns. Para ingredientes não listados, é possível:

Buscar dados nutricionais (simulação de API)

Inserir valores manualmente

Personalização
O código pode ser facilmente adaptado para:

Adicionar novos ingredientes ao banco de dados nutricional

Modificar as regras de otimização

Incluir novos parâmetros de análise

Integrar com APIs reais de dados nutricionais

Limitações
Banco de dados nutricional limitado (pode ser expandido)

Simulação de API (idealmente substituir por serviço real)

Armazenamento local (sem sincronização em nuvem)
