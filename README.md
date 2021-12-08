# Os fundos de ações que mais ganharam investidores durante a pandemia - Relatório de Acompanhamento



#### Aluna: Priscila Barbosa dos Santos (https://github.com/PrisBarbosa)

#### Orientador: Professor Orientador (https://github.com/link_do_github)



---



Trabalho apresentado ao curso [BI MASTER](https://ica.puc-rio.ai/bi-master) como pré-requisito para conclusão e obtenção de crédito na disciplina "Projetos de Sistemas Inteligentes de Apoio à Decisão".

https://github.com/PrisBarbosa/fundos_acoes_pandemia

---

### Resumo



Foi publicada uma matéria na "exame.invest"(https://invest.exame.com/me/os-fundos-de-acoes-que-mais-ganharam-investidores-durante-a-pandemia) que falava sobre a evolução da quantidade de cotistas nos fundos de investimento em ações durante a pandemia. A solicitação da análise descritiva multivariada desses fundos de investimento veio pelo Diretor da Diretoria Comercial e de Produtos. 

A partir da Definição da Pergunta de Negócio (Como foi essa entrada de cotistas ao longo do período?) e da leitura da matéria, foram avaliadas todas as etapas do processo de BI, desde a Definição de Requisitos até o Storytelling com feedback do cliente, em conjunto com a Metodologia Ágil Scrum.

Após mapeamento dos dados necessários e análise das fontes confiáveis, a fonte escolhida foi a CVM - Comissão de Valores Mobiliários. Os dados necessários são disponibilizados diariamente na URL http://dados.cvm.gov.br/dados/FI/DOC/INF_DIARIO/DADOS/diariamente e, por isso, possibilitou a utilização de web scraping como forma de extração.


![image](https://user-images.githubusercontent.com/95291494/144506778-a5da2868-8a54-48a9-aa50-8c0c9a2250f6.png)


Todo processo de ETL foi realizado no PDI - Pentaho Data Integration que é o componente da suíte Pentaho usado para criar processos de extração, transformação e carga (do inglês Extraction, Transformation and Loading, ETL).

![image](https://user-images.githubusercontent.com/95291494/144770143-ccaf2dca-e2fc-4503-9911-4f7d95c4af7e.png)

![image](https://user-images.githubusercontent.com/95291494/144770122-9014cb92-7d0a-47b7-a0e1-4c9ccf682f93.png)

![image](https://user-images.githubusercontent.com/95291494/144770134-d80b76bb-a8b3-4667-8f75-bdb00f21e306.png)


Para o Dashboad, geralmente utilizo o framework abaixo, disponibilizado pelo professor Pedro Venturini (https://www.linkedin.com/in/pedrovento) na aula de Dashboard do Programa Radar do Cappra Institute (https://cappralab.com/radar), o qual sou membro desde 2020.


![image](https://user-images.githubusercontent.com/95291494/144491119-3a0a9f2c-5798-42eb-9904-2dff02f09bcb.png)


*A utilização da imagem foi autorizada por Pedro Venturini.


Assim o Power BI foi escolhido pra entrega do Relatório ao Cliente.


![image](https://user-images.githubusercontent.com/95291494/145088574-4d02ca70-9468-40a9-8fff-1c9d4a3a212e.png)

![image](https://user-images.githubusercontent.com/95291494/144908897-d1c236f4-fb62-4f4a-8ec2-a54de3be5f95.png)

![image](https://user-images.githubusercontent.com/95291494/144908938-b0d520b8-3c37-436b-be9a-23b156b7efbb.png)

![image](https://user-images.githubusercontent.com/95291494/144908961-7b9b1a5e-90fb-4133-b8fe-2f85cca66d4e.png)

Conclusão...



---



Matrícula: 183.477.011



Pontifícia Universidade Católica do Rio de Janeiro



Curso de Pós Graduação *Business Intelligence Master*
