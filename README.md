# Data_Science_Projects 
Projetos de ciência de dados desenvolvidos por mim

<div display='inline'>
<img src="https://img.shields.io/pypi/status/V1"/>
<img src="https://img.shields.io/npm/l/react"/>
<img src="https://img.shields.io/github/stars/savioricardog?style=social"/>
</div>

<html>
<h1 align="center"> Projeto de análise dos microdados do ENEM 2021 V1.0</h1>
Neste projeto de análise de dados, o dataset usado foi retirado do site do enem: https://www.gov.br/inep/pt-br/acesso-a-informacao/dados-abertos/microdados/enem.<br>
Analisei de maneira generalizada os dados disponibilizados pelo INEP, com enfoque na geração de insights. Comecei obtendo os dados e limpando-os com uso de pandas e numpy. Após a limpeza gerei um overview e fiz uma análise explotória para entender a distribuição estatística dos meus dados e também iniciar a geração das hipóteses a serem respondidads. Após as hipótes geradas, iniciei com as análises necessárias. Sendo elas:

<body>
<ul>
<li> Calculo das notas médias que os alunos obtem na prova, que mostrou que as médias ainda hoje são muito baixas, algo em torno de 536,39.</li>
 
 ![Captura de tela 2023-05-04 230444](https://user-images.githubusercontent.com/102491585/236364190-8602cc4e-e0b8-4ccb-a1ca-58943445bca4.png)
 
<li>Em seguida parti para o comparativo entre os resultados obtidos por pessoas do sexo Masculino x Feminino que mostrou uma baixa diferença entre Homens e Mulheres, onde a maior diferença foi em prol das mulheres, que tiram melhores notas na redação, mas que no geral se saem abaixo dos homens. 
 
 ![MxF](https://user-images.githubusercontent.com/102491585/236349942-18ab5101-10e1-465a-a476-ece705cf0713.png)</li>
  
<li>Comparei também a relação entre as notas dos estados e regiões do país, onde podemos ver que de fato o ensino é infeior nas regiões Norte e Nordeste, se comparados ao restante do pais. </li>
  
 ![Captura de tela 2023-05-04 212953](https://user-images.githubusercontent.com/102491585/236356807-9f37342f-c37c-4f1a-90e0-010d58d8c4de.png)
  
<li>Calculei o percentual de evasão das provas por Faixa etária dos alunos:<br>
 
Por Perfil Socieconomico: <br> 

 ![Captura de tela 2023-05-04 230315](https://user-images.githubusercontent.com/102491585/236364063-6a5fe9df-cfab-4093-b8a6-c47d9e26cd71.png)

Por Sexo: <br>
 
 ![Captura de tela 2023-05-04 222953](https://user-images.githubusercontent.com/102491585/236361247-8d776a4d-e6f6-43a1-9216-7d4b0700cbf5.png)
 
Por Estado de moradia: <br>
 
 ![Captura de tela 2023-05-04 230201](https://user-images.githubusercontent.com/102491585/236363938-d2aca4f1-5b4f-4e3b-b1d6-90a268fc0847.png)
 
Onde o podemos inferir que perfil do faltante do ENEM é: Residente no Norte, Mulher, em média com 18 anos, e com renda familiar abaixo dos R$ 1.100,00 mensais. </li>
 
<li>Calculei a média socioeconomica das pessoas que prestaram a prova, que é o grupo com renda de até R$ 1.100,00, que também é grupo com maior evasão, por ser o que mais se inscreve. </li>
  
 ![Captura de tela 2023-05-04 215140](https://user-images.githubusercontent.com/102491585/236358394-47986060-5c13-435d-9de6-609742614839.png)

<li>Análisei comparativamente as notas dos alunos que fazem para valer x aluno treineiros, e pude perceber que a diferença entre os dois grupos é baixa, cerca de 2% a diferença média entre os grupos.</li>
 
 ![Captura de tela 2023-05-04 215407](https://user-images.githubusercontent.com/102491585/236358588-9e9b93b3-6cfc-4878-a5d3-4738ac8d6f1c.png)

<li>Verifiquei qual o grupo etário mais presente nas provas e o resultado foi o de faixa etária de 18 anos. </li>
  
 ![Captura de tela 2023-05-04 220127](https://user-images.githubusercontent.com/102491585/236360148-ae5a23d4-e508-4e3d-be12-97425c2f951e.png)

<li>Calculei as notas por grupo etário, que mostrou que o grupo de 22 anos, é o que obtem melhores resultados no prestar da prova.</li>
  
 ![Captura de tela 2023-05-04 221805](https://user-images.githubusercontent.com/102491585/236360369-976e1836-c490-4478-925b-e43d5fde8799.png)
  
<li>Por fim, fiz um comparativo entre alunos de escola pública x privada, para validar a hipótese de que alunos de escola privada se saem melhor, e de fato se saem, a diferença média entre os grupo foi de 21,83% em prol dos alunos de escola privada.</li>
  
 ![Captura de tela 2023-05-04 221545](https://user-images.githubusercontent.com/102491585/236360198-30b70c6c-84da-413f-98fe-4be0d0e78f5c.png)
 
<li> Em seguida comparei as hipóteses pré resolução, com os resultados obtidos e listei alguns outros insights que tive durante a análise e exploração dos dados, que foram: </li>
 Os alunos possuem menor conhecimento na materia de Ciências da Natureza, seguido de Linguagens e Códigos, Ciências Humanas, Matemática e por fim Redação. E mesmo a nota média da materia de Linguagens e codigos ter sido a 2° menor, isso não afetou na redação que teve a maior media de notas entre todas as matérias.<br>
 A média total se somadas todas as matérias é de 536.39, o que mostra um baixo percentual de aprendizagem das matérias basicas.<br>
 Conforme calculado, na maioria das notas, as pessoas do sexo feminimo se saem abaixo das pessoas do sexo masculino, principalmente nas matérias de exatas. Somente na matéria de "Redação" que a medía de pontos do sexo Feminimo foi superior.<br>
 Em geral alunos da região norte, obtém menores notas.<br>
 Em contra partida, o Sudeste tem as maiores notas, seguido de perto pela região Sul.<br>
 Alunos que fizeram para valer tiram maiores notas em todas as matérias do Enem.<br>
 Podemos concluir que mais de 66% dos candidatos que relizam a prova, estão entre os 17 e 19 anos de idade.<br>
 Pela comparação de médias entre escola pública e privada, podemos concluir que as notas de alunos de escola do tipo privada, são em média 21.83% maiores.<br>
 Em geral mulheres faltam mais que os homens na prova do Enem.<br>
 Por ser a faixa etária mais presente nas inscrições, os alunos de 18 anos também são os que mais faltam.<br>
 Os alunos que mais faltam, estão classificados na faixa de renda de até 1100.00 e os que menos faltam estao classificados na faixa de renda de 11.000,01 at 13.200,00.<br>
 A faixa de renda com mais participantes é a de até 1100.<br>
 Apesar de nada muito expresivo, a mediana de notas dos alunos que fazem para valer é cerca de 2.03% superior aos treineiros.<br>
 A faixa etária tipo 3 (18 anos) é a que mais comparece.<br>
 A faixa etária com a maior média é a dos alunos com 22 anos.

</ul>
</body>
</html>
