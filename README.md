1118454_Camila Campos

1116251_Mathias Stadtlober

Transformação da Coluna “Com que frequência você aposta?” para Valores Numéricos

Neste exemplo, escolhemos trabalhar com a coluna “Com que frequência você aposta?”.

Pois ela contém respostas textuais que descrevem a regularidade com que cada participante aposta.

Para realizar análises estatísticas, é importante transformar essas categorias qualitativas em valores numéricos que representem, de forma aproximada, a frequência mensal de apostas.


Lógica da Função Desenvolvida

Foi criada uma função em Python que recebe a resposta textual da frequência e retorna um número inteiro estimado de apostas por mês.

O mapeamento definido foi:

"Diariamente" → 30

"Uma ou duas vezes por semana" → 6

"Mensalmente" → 1

"Apostei poucas vezes na vida" → 0

(Outros valores podem ser adaptados conforme a necessidade da análise.)

Essa lógica permite transformar informações subjetivas em dados quantitativos. 

A função identifica os padrões principais presentes no texto e converte cada um deles em uma estimativa coerente.


Justificativa da Transformação

Converter textos em números é uma etapa essencial na preparação de dados, especialmente para quem está iniciando na área.

Esse processo é importante porque:

Possibilita calcular médias relacionadas à frequência de apostas;

Permite comparar o comportamento dos participantes;

Facilita a visualização de tendências e padrões;

Padroniza a base de dados para análises estatísticas, reduzindo ambiguidades das respostas textuais.


Impacto Prático da Transformação

Com a criação dessa nova coluna numérica, torna-se possível:

Calcular a média de apostas mensais por faixa etária, gênero ou renda;

Identificar grupos que apresentam maior frequência de apostas;

Elaborar gráficos comparativos para observar como diferentes fatores influenciam o comportamento de aposta.

Com a criação dessa nova coluna numérica, torna-se possível:

calcular a média de apostas mensais por faixa etária, gênero ou renda;

Identificar grupos que apresentam maior frequência de apostas;

Elaborar gráficos comparativos para observar como diferentes fatores influenciam o comportamento de aposta.


A transformação das respostas textuais em valores numéricos facilita a análise dos dados e torna as comparações mais claras. 

Esse processo é essencial, pois mostra como preparar a base para estudos estatísticos e visualizações de forma simples e eficiente.
