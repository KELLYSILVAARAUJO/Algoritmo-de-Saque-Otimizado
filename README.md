# Simulador de Saque em Caixa Eletrônico
Este repositório contém o código-fonte de um algoritmo simples que simula o saque de dinheiro em um caixa eletrônico, calculando a distribuição das notas necessárias para compor o valor solicitado.💡 Sobre o ProjetoO algoritmo foi desenvolvido em Flowgorithm e tem como objetivo principal determinar a quantidade mínima de notas de diferentes valores para um determinado valor de saque, seguindo a lógica de priorizar as notas de maior valor. 
# Funcionalidades
O programa executa as seguintes tarefas:
Solicita ao usuário o valor que deseja sacar (em Reais).
Entrada: O valor do saque é armazenado na variável valorsaque. Calcula a distribuição de notas, priorizando as maiores denominações. As notas consideradas são: R$100,00, R$50,00, R$20,00, R$10,00, R$2,00 e R$1,00. Exibe a quantidade de cada nota necessária para completar o saque. O resultado mostra quantas notas de cada valor (notas100, notas50, etc.) serão entregues. 
# Lógica do Algoritmo
O cálculo da distribuição de notas é realizado utilizando os operadores de divisão inteira (/) e módulo (%) de forma sequencial, do maior para o menor valor de nota. 
# Cálculo da Quantidade de Notas: 
A divisão inteira do valor atual pelo valor da nota (valorsaque / valor_nota) retorna o número máximo de notas daquela denominação. 
# Atualização do Saldo:
O operador módulo (valorsaque % valor_nota) atualiza a variável valorsaque com o resto que ainda precisa ser distribuído nas notas de valor menor. Por exemplo, para notas de R$100,00:* notas100 = valorsaque / 100 (Calcula quantas notas de R$100 cabem no saque).Atualiza o `valorsaque` com o que sobrou após a distribuição das notas de R$100.
# Como Executar Este algoritmo 
Está formatado como um arquivo .fprg (Flowgorithm). Para visualizá-lo ou executá-lo, você precisará do software Flowgorithm. Baixe e instale o Flowgorithm em seu computador. Abra o arquivo CAIXAELETRONICO.fprg usando o programa. Execute a função Main para iniciar a simulação.
