# Curso NTT Data - Engenharia de Dados com Python

Bem-vindo ao repositório do projeto desenvolvido para o curso **NTT Data - Engenharia de Dados com Python**, oferecido pela DIO. Este projeto foi criado com o objetivo de melhorar a experiência do usuário ao visualizar relatórios, reorganizando informações de maneira intuitiva e visualmente atraente, utilizando técnicas avançadas de construção de gráficos e boas práticas de design.

## Descrição

O projeto consiste na elaboração de um relatório interativo em **Power BI**, integrando diversos tipos de gráficos, linguagem DAX para cálculos avançados, botões de navegação e a aplicação da proporção áurea para otimizar a compreensão visual e a estética do layout.

## Ferramentas Utilizadas
- **Power BI**: Plataforma principal para criação de gráficos, medidas DAX e desenvolvimento do relatório interativo.

## Estrutura do Relatório
O relatório foi projetado com um padrão consistente de cores no fundo e inclui botões de navegação para facilitar a interação do usuário: avançar para a próxima página, retornar à página anterior ou voltar à página inicial por meio de um botão no formato de uma casa. As páginas do relatório são organizadas da seguinte forma:

- **Home Page**: Apresenta o título do relatório (página pré-construída).

- **Principal**: Exibe o conteúdo gráfico principal (página pré-construída).

- **Detalhes**: Inclui um histograma e botões para alternar entre dois gráficos no mesmo espaço da página.

- **TOPN & Outliers**: Utiliza DAX para destacar os 3 produtos mais vendidos e apresenta um gráfico de dispersão com funcionalidade Play Axis.

- **Data Analytics**: Exibe um gráfico de dispersão com linha de tendência e usa DAX para identificar os 5 meses com maior volume de vendas, representados graficamente.

- **Categorias**: Aplica técnicas de clusterização e agrupamento de dados para visualizações específicas.

### Arquivo do Projeto
Nome: <span style="color: orange;">sales_report_desafio_projeto.pbix</span>


Localização: Disponível para download em https://github.com/OCORUJA/power_bi_analyst

### Pré-requisitos
- **Power BI Desktop**: Necessário para abrir, visualizar e editar o arquivo <span style="color: orange;">.pbix</span>

Instalação
Siga os passos abaixo para acessar o projeto:
Clone o repositório:
```bash 
git clone https://github.com/OCORUJA/power_bi_analyst.git
 ```

Navegue até o diretório do projeto:
```bash 
cd power_bi_analyst/Módulo 5/Desafio 2 - Relatório com Data Analytics/Community
 ```

Abra o arquivo `sales_report_desafio_projeto.pbix` no Power BI Desktop.

### Como Contribuir
Contribuições são muito bem-vindas! Para colaborar, siga estas etapas:
Faça um fork deste repositório.

Crie uma branch para sua alteração:
```bash 
git checkout -b melhoria/nova-funcionalidade
```

Realize suas modificações e faça o commit:
```bash 
git commit -m "Adiciona melhoria no modelo"
```

Envie um pull request com uma descrição detalhada das mudanças propostas.

Sinta-se à vontade para sugerir melhorias, novas funcionalidades ou ajustes no projeto!

### Licenças

Este projeto foi desenvolvido exclusivamente para fins educacionais e está alinhado às diretrizes do curso **NTT Data - Engenharia de Dados com Python**, oferecido pela DIO.

