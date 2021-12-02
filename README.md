# Os fundos de ações que mais ganharam investidores durante a pandemia - Relatório de Acompanhamento



#### Aluno: Priscila Barbosa dos Santos (https://github.com/PrisBarbosa)

#### Orientador: Guilherme Cesário Strachan (https://github.com/link_do_github)



---



Trabalho apresentado ao curso [BI MASTER](https://ica.puc-rio.ai/bi-master) como pré-requisito para conclusão de curso e obtenção de crédito na disciplina "Projetos de Sistemas Inteligentes de Apoio à Decisão".

https://github.com/PrisBarbosa/fundos_acoes_pandemia

---

### Resumo



Foi publicada uma matéria na "exame.invest"(https://invest.exame.com/me/os-fundos-de-acoes-que-mais-ganharam-investidores-durante-a-pandemia) que falava sobre a evolução da quantidade de cotistas nos fundos de investimento em ações durante a pandemia. A solicitação da análise descritiva multivariada desses fundos de investimento veio pelo Diretor da Diretoria Comercial e de Produtos. 

A partir da Definição da Pergunta de Negócio (Como foi essa entrada de cotistas ao longo do período?) e da leitura da matéria, foram avaliadas todas as etapas do processo de BI, desde a Definição de Requisitos até o Storytelling com feedback do cliente pois trabalho com a Metodologia Ágil Scrum.

Após mapeamento dos dados necessários e análise das fontes confiáveis, a fonte escolhida foi a CVM - Comissão de Valores Mobiliários. Os dados necessários são disponibilizados diariamente na URL http://dados.cvm.gov.br/dados/FI/DOC/INF_DIARIO/DADOS/diariamente e, por isso, possibilitou a utilização de web scraping como forma de extração.


![image](https://user-images.githubusercontent.com/95291494/144506778-a5da2868-8a54-48a9-aa50-8c0c9a2250f6.png)


Todo processo de ETL foi realizado no PDI - Pentaho Data Integration, uma das ferramentas utilizadas pela BB DTVM, que é o componente da suíte Pentaho usado para criar processos de extração, transformação e carga (do inglês Extraction, Transformation and Loading, ETL).


![image](https://user-images.githubusercontent.com/95291494/144507420-a0252cf5-6a04-4fdd-bed8-6adf7984a10c.png)

![image](https://user-images.githubusercontent.com/95291494/144508458-f5a155df-62e8-4216-a3c4-1bd7f4b7c756.png)

![image](https://user-images.githubusercontent.com/95291494/144508610-9baa4b75-23c7-4a86-b7d9-b01f5bf5a619.png)


Para o Dashboad, geralmente utilizo o framework abaixo, disponibilizado pelo professor Pedro Venturini na aula de Dashboard do Programa Radar do Cappra Institute (https://cappralab.com/radar), o qual sou membro desde 2020.


![image](https://user-images.githubusercontent.com/95291494/144491119-3a0a9f2c-5798-42eb-9904-2dff02f09bcb.png)


Assim o Power BI foi escolhido pra entrega do Relatório ao Cliente.


![image](https://user-images.githubusercontent.com/95291494/144509193-9fadbddb-0090-43b9-b41d-6c54e252e0ae.png)

![image](https://user-images.githubusercontent.com/95291494/144509260-1562a6d4-b58a-42bc-bebe-a677e0777c5b.png)

![image](https://user-images.githubusercontent.com/95291494/144509459-b4fda4a7-af17-4078-92bc-aaf674e95e73.png)

![image](https://user-images.githubusercontent.com/95291494/144509533-43a03c58-347a-46e9-8a44-0834a6f21a6d.png)







---



Matrícula: 183.477.011



Pontifícia Universidade Católica do Rio de Janeiro



Curso de Pós Graduação *Business Intelligence Master*
