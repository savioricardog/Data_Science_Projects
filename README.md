# Data_Science_Projects 
Projetos de ciência de dados desenvolvidos por mim

<div display='inline'>
<img src="https://img.shields.io/pypi/status/V1"/>
<img src="https://img.shields.io/npm/l/react"/>
<img src="https://img.shields.io/github/stars/savioricardog?style=social"/>
</div>


<h1 align="center">1 - Projeto de análise dos microdados do ENEM 2021 V1.0</h1>
Nesta primeira versão do projeto dos dados do ENEM, retirados do site do enem: https://www.gov.br/inep/pt-br/acesso-a-informacao/dados-abertos/microdados/enem.
Analisei de maneira generalizada os dados disponibilizados pelo INEP, com enfoque na geração de insights. Comecei obtendo os dados e limpando-os com uso de pandas e numpy. Após a limpeza gerei um overview e fiz uma análise explotória para entender a distribuição estatística dos meus dados e também iniciar a geração das hipóteses a serem respondidads. Após as hipótes geradas, iniciei com as análises necessárias. Começando com:
calculo das notas médias que os alunos obtem na prova, que mostrou que as médias ainda hoje são muito baixas, algo em torno de 536,39. 
Em seguida parti para o comparativo entre os resultados obtidos por pessoas do sexo Masculino x Feminino que mostrou uma baixa diferença entre Homens e Mulheres, onde a maior diferença foi em prol das mulheres, que tiram melhores notas na redação, mas que no geral se saem abaixo dos homens. 
Comparei também a relação entre as notas dos estados e regiões do país, onde podemos ver que de fato o ensino é infeior nas regiões Norte e Nordeste, se comparados ao restante do pais. 
Calculei o percentual de evasão das provas por Faixa etária dos alunos, por Perfil Socieconomico, por Sexo e por Estado de moradia, onde o perfil do faltante do ENEM é: Residente da Norte, Mulher, em média com 18 anos, e com renda familiar abaixo dos R$ 1.100,00 mensais. 
Calculei a média socioeconomica das pessoas que prestaram a prova, que é o grupo com renda de até R$ 1.100,00, que também é grupo com maior evasão, por ser o que mais se inscreve. Análisei comparativamente as notas do alunos que fazem para valer x aluno treineiros, e pude perceber que a diferença entre os dois grupos é baixa, cerca de 2% a diferença média entre os grupos. 
Verifiquei qual o grupo etário mais presente nas provas e o resultado foi o de faixa etária de 18 anos. 
Calculei as notas por grupo etário, que mostrou que o grupo de 22 anos, é o que obtem melhores resultados no prestar da prova. 
Por fim, fiz um comparativo entre alunos de escola pública x privada, para validar a hipótese de que alunos de escola privada se saem melhor, e de fato se saem, a diferença média entre os grupo foi de 21,83% em prol dos alunos de escola privada. Em seguida comparei as hipóteses pré resolução, com os resultados obtidos e listei alguns outros insights que tive durante a análise e exploração dos dados.
