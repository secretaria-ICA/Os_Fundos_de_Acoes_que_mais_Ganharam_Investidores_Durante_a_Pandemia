# Os_Fundos_de_Ações_que_mais_Ganharam_Investidores_Durante_a_Pandemia_Relatório_de_Acompanhamento

#### Aluna: [Priscila Barbosa dos Santos](https://github.com/PrisBarbosa)

#### Orientadora: [Manoela Kohler](https://github.com/manoelakohler)

---

Trabalho apresentado ao curso [BI MASTER](https://ica.puc-rio.ai/bi-master) como pré-requisito para conclusão e obtenção de crédito na disciplina "Projetos de Sistemas Inteligentes de Apoio à Decisão".

https://github.com/PrisBarbosa/fundos_acoes_pandemia

---

### Resumo

Foi publicada uma matéria na ["exame.invest"](https://invest.exame.com/me/os-fundos-de-acoes-que-mais-ganharam-investidores-durante-a-pandemia) que falava sobre a evolução da quantidade de cotistas nos fundos de investimento em ações durante a pandemia. A solicitação da análise descritiva multivariada desses fundos de investimento veio pelo diretor da Diretoria Comercial e de Produtos da BB DTVM. 

### Abstract

An article was published in "exame.invest" (https://invest.exame.com/me/os-fundos-de-acoes-que-mais-ganharam-investidores-durante-a-pandemia) that talked about the evolution number of shareholders in equity investment funds during the pandemic. The request for the multivariate descriptive analysis of these investment funds came by the director of the Commercial and Product Board of BB DTVM.

### 1. Introdução

A partir da Definição da Pergunta de Negócio (Como foi essa entrada de cotistas ao longo do período?) e da leitura da matéria, foram avaliadas todas as demais etapas do processo de BI, desde a Definição de Requisitos até o Storytelling com feedback do cliente, pois trabalhamos com a Metodologia Ágil Scrum.

### 2. Modelagem

Com o mapeamento dos dados necessários e análise das fontes confiáveis, a fonte escolhida foi a CVM - Comissão de Valores Mobiliários. Os dados mapeados são disponibilizados diariamente na URL http://dados.cvm.gov.br/dados/FI/DOC/INF_DIARIO/DADOS/ e, por isso, possibilitou a utilização de web scraping como forma de extração.

<img align="center" height="250" width="800" src="https://user-images.githubusercontent.com/95291494/144506778-a5da2868-8a54-48a9-aa50-8c0c9a2250f6.png" />

Todo processo de ETL foi realizado no PDI - Pentaho Data Integration que é o componente da suíte Pentaho usado para criar processos de extração, transformação e carga (do inglês Extraction, Transformation and Loading, ETL).

<img align="center" height="400" width="800" src="https://user-images.githubusercontent.com/95291494/144770143-ccaf2dca-e2fc-4503-9911-4f7d95c4af7e.png" />

<img align="center" height="400" width="800" src="https://user-images.githubusercontent.com/95291494/144770122-9014cb92-7d0a-47b7-a0e1-4c9ccf682f93.png" />

<img align="center" height="400" width="800" src="https://user-images.githubusercontent.com/95291494/144770134-d80b76bb-a8b3-4667-8f75-bdb00f21e306.png" />

Para o Dashboad, foi utilizado o framework abaixo, disponibilizado pelo professor Pedro Venturini (https://www.linkedin.com/in/pedrovento) na aula de Dataviz do Programa Radar do Cappra Institute (https://cappralab.com/radar), o qual sou membro desde 2020.

<img align="center" height="250" width="500" src="https://user-images.githubusercontent.com/95291494/144491119-3a0a9f2c-5798-42eb-9904-2dff02f09bcb.png" />

*A utilização da imagem foi autorizada por Pedro Venturini.

Assim, o Power BI foi escolhido pra entrega do Relatório ao Cliente.

<img align="center" height="400" width="800" src="https://user-images.githubusercontent.com/95291494/145581437-ec112697-e5d5-40f3-8356-ce142f764998.png" />

<img align="center" height="400" width="800" src="https://user-images.githubusercontent.com/95291494/145495040-84ed8728-5f61-4a21-b619-1d9e33be5fe0.png" />

<img align="center" height="400" width="800" src="https://user-images.githubusercontent.com/95291494/145495051-cc6e8414-6908-4fea-b367-6b4ab5619a6d.png" />

<img align="center" height="400" width="800" src="https://user-images.githubusercontent.com/95291494/145495081-c3b27082-a0fb-40c9-beb7-8d5de3c8ff9d.png" />

<img align="center" height="400" width="800" src="https://user-images.githubusercontent.com/95291494/145495101-d12c9878-cbe2-4067-a5d7-2ffded73cedd.png" />

<img align="center" height="400" width="800" src="https://user-images.githubusercontent.com/95291494/145495139-22f917d1-64c9-49c5-ad37-e28ee021e056.png" />

<img align="center" height="400" width="800" src="https://user-images.githubusercontent.com/95291494/145495197-d3554ead-f1cf-48e9-a245-76f0ed0d99e8.png" />

### 3. Resultados

Com os dados disponibilizados no dashboard puderam ser apurados vários insights dependendo da variável avaliada já que trata-se de uma análise multi. Mas apenas com esses dados quantitativos não há como concluir que tipo de indutor foi responsável por cada movimento em cada variável, quantidade de cotista, captação líquida e etc. Demonstrou-se com números os momentos de maior movimento mas não os motivos. Motivos estes a serem apurados com as informações qualitativas as quais não temos acesso. 

### 4. Conclusões

Após apresentação do storytelling, o cliente analisou os dados quantitativos e prontamente solicitou à Diretoria de Clientes os dados qualitativos para agregar valor ao relatório de acompanhamento. Este dashboard passará a ser utilizado como ferramenta de gestão de medição de um dos KPIs da empresa, aumentar em percentual a quantidade de cotistas. Além disso, também foi mencionado pelo cliente que os insights resultantes das análises serão aproveitados para ações da diretoria como, por exemplo, revisão de portfólio. Considerou-se então que o projeto foi aceito pelo cliente e a pergunta de negócio respondida.

---

Matrícula: 183.477.011

Pontifícia Universidade Católica do Rio de Janeiro

Curso de Pós Graduação *Business Intelligence Master*
