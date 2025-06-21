📘 Sistemas Fuzzy em Scilab com sciFLTEditor
Este projeto contém a implementação de dois sistemas baseados em lógica fuzzy utilizando o Scilab com o editor gráfico sciFLTEditor. Cada sistema trata de um problema distinto, com foco na construção de variáveis linguísticas, regras de inferência e defuzzificação.

🧠 Questão #1 – Controle de Vagas em Estacionamento Escolar
🎯 Enunciado:
Projete um sistema de controle inteligente para estimar o estado de ocupação de um estacionamento escolar, com base na quantidade de veículos que entram e saem. A saída é uma estimativa do estado atual das vagas.

✅ Requisitos:
Variáveis de Entrada:
Veículos Entrando (intervalo: 0 a 100)
Veículos Saindo (intervalo: 0 a 100)

Variável de Saída:
Estado das Vagas (intervalo: 0 a 100), representando a porcentagem de ocupação

Fuzzificação:
Veículos Entrando e Saindo: Poucos, Médios, Muitos
Estado das Vagas: Livres, Parcialmente Ocupadas, Cheias

Regras Fuzzy:
Exemplo:
Se Muitos Entrando e Poucos Saindo, então Vagas Cheias
Se Poucos Entrando e Muitos Saindo, então Vagas Livres

Defuzzificação:
Método do centroide (centroid)

Teste:
Simule diferentes fluxos de entrada/saída e observe o grau de ocupação estimado pelo sistema fuzzy.

🧠 Questão #2 – Estimativa de Tempo de Correção de Provas
🎯 Enunciado:
Desenvolva um sistema fuzzy para estimar o tempo necessário para corrigir manualmente uma prova, com base em:
Número de Questões da prova
Dificuldade Média das questões
A saída será o Tempo Estimado de Correção em uma escala fuzzy.

✅ Requisitos:
Variáveis de Entrada:
Número de Questões (intervalo: 0 a 20)
Dificuldade Média (intervalo: 0 a 20)

Variável de Saída:
Tempo Estimado de Correção (intervalo: 0 a 20)

Fuzzificação:
Número de Questões: Poucas, Médias, Muitas
Dificuldade Média: Fácil, Média, Difícil
Tempo Estimado: Curto, Médio, Longo

Regras Fuzzy:
Exemplo:
Se Muitas Questões e Dificuldade Difícil, então Tempo Longo
Se Poucas Questões e Dificuldade Fácil, então Tempo Curto

Defuzzificação:
Método do centroide (centroid)

Teste:
Simule valores variados de questões e dificuldade e observe o tempo estimado gerado pelo sistema fuzzy.

🛠️ Ferramentas Utilizadas
 Scilab (versão recomendada ≥ 6.1)

 sciFLTEditor – Editor gráfico da Fuzzy Logic Toolbox (FLT
