# Computabilidade-e-Complexidade-de-Algoritmos
Repositório referente a matéria de Computabilidade e Complexidade de Algoritmos do curso de Ciência da Computação

>> Computabilidade:
O termo “computável” foi proposto por Alan Turing para designar a totalidade
de números reais cuja expansão decimal pode ser calculada em tempo finito,
através de recursos finitos. No mesmo artigo, Turing argumenta que este conjunto
corresponde ao conjunto de funções ou predicados computáveis. A proposta de
Turing consistia em identificar os possíveis processos envolvidos no ato de
“computar um número”. Para tanto, Turing definiu um artefato teórico, que
chamou de “máquina de computar”, de maneira que, todo número cuja expansão
decimal pudesse ser obtida a partir de operações da máquina seria chamado de
“número computado pela máquina”.
Ao identificar os processos necessários para computar um número, Turing
estaria indiretamente, identificando o conjunto de números (funções, predicados,
etc) computáveis e, consequentemente, respondendo a seguinte pergunta: O que
pode ser efetuado pela máquina de computar?
Na tentativa de definir o “computável”, Turing se deparou com o seguinte
problema: os números computados pela máquina realmente formam aquele
conjunto que, intuitivamente, consideramos “computável”? Para responder a tal
questão com precisão, Turing precisaria provar matematicamente que (→) todos os
números que consideramos “computáveis” podem ser obtidos pela máquina. Desta
maneira, a máquina computaria necessariamente todos os “números
computáveis”. Por outro lado seria também necessária a prova matemática de que
(←) todos os números que a máquina computa são considerados por nós “números
computáveis”. Estaria então provado que a máquina não computaria nada além do
que “números computáveis”. (artigo de 1936).
Ref.: http://www.ic.uff.br/isabel/pdf/Computabilidade,%20Hist%C3%B3ria%20e%20Matem%C3%A1tica.pdf
>> Objetivos:
➢ Investigar a possibilidade de existir ou não algoritmos que solucionem
determinada classe de problemas.
➢ Verificar os limites da computação e, também, o que pode realmente ser
implementado e solucionado por meio de um computador.
➢ O objetivo está centrado na possibilidade de construção desses algoritmos.
?? Questão:
>> O computador pode resolver quais problemas ?
▪ Como verificar essa questão ?
Entendendo “computabilidade” como conceituação de tudo que pode ser
realizado por computador a discussão a respeito deste tema é fundamental
aos estudantes de Ciência da Computação. A Computabilidade vem mostrar
ao profissional em formação dois importantes resultados (negativos) com
relação ao computador. O primeiro resultado é consequência do trabalho de
Gödel (filósofo e matemático), e consiste na constatação de que nem tudo se
pode resolver através do computador. O segundo resultado negativo,
abordado por Turing, aponta a impossibilidade de caracterizar a classe de
problemas computáveis. Informalmente, poderíamos dizer que sabemos que
existem problemas não resolvíveis através de computadores, mas não
sabemos exatamente quais são. É através do estudo da Computabilidade que
o profissional da área de computação adquire pleno conhecimento da real
capacidade dos computadores, e passa a lidar com seu instrumento de
trabalho de maneira realística, sem mitos.
Ref.: http://www.ic.uff.br/isabel/pdf/Computabilidade,%20Hist%C3%B3ria%20e%20Matem%C3%A1tica.pdf
>> Abordagem:
“Focada nos problemas com respostas do tipo Sim/Não (ou Problemas de
decisão). A vantagem de tal abordagem é que a verificação da solubilidade de um
problema pode ser associada às condições de aceitação/rejeição de uma Máquina
Universal às respostas Sim/Não, respectivamente.”
Ref.: http://usuarios.upf.br/~mcpinto/teoria/teoria-computabilidade.pdf
>> Classes de Solucionabilidade de Problemas
Ref.: http://www2.fct.unesp.br/docentes/dmec/olivete/tc/arquivos/Aula9.pdf
➢ Um problema é denominado Solucionável se existe um algoritmo (Máquina
Universal) que solucione o problema e sempre para (aceitação – Sim ou
rejeição – Não) com qualquer entrada.
➢ Um problema é denominado Não-Solucionável se não existe um algoritmo
(Máquina Universal) que solucione o problema e sempre para com qualquer
entrada.
➢ Um problema é denominado Parcialmente Solucionável ou Computável se
existe um algoritmo (Máquina Universal) que sempre para se a resposta for
afirmativa (aceitação – Sim), porém, se a resposta esperada for negativa, o
algoritmo pode parar (rejeição – Não) ou permanecer processando
indefinidamente (loop infinito).
➢ Um problema é denominado Completamente Insolúvel ou Não-Computável se
não existe um algoritmo (Máquina Universal) que solucione o problema tal que
sempre para quando a resposta é afirmativa (aceitação – Sim).
