---
Autor: Ronne Scherhelton
URL: https://web.dio.me/project/otimizando-o-sistema-bancario-com-funcoes-python
---
# Trilha Python DIO - LuizaLabs
## Desafio: Criando um sistema bancário
Neste desafio, tive a oportunidade de otimizar o Sistema Bancário previamente desenvolvido com o uso de funções Python. O objetivo era aprimorar a estrutura e a eficiência do sistema, implementando as operações de depósito, saque e extrato em funções específicas. Tive a chance de refatorar o código existente, dividindo-o em funções reutilizáveis, facilitando a manutenção e o entendimento do sistema como um todo. Preparando-se para aplicar conceitos avançados de programação e demonstrar sua habilidade em criar soluções mais elegantes e eficientes utilizando Python.
### Objetivo Geral
Deixar o código mais modularizado, criando funções para operações existentes:
- Saque (Sacar)
- Depósito (Depositar)
- Extrato (Visualizar histórico)

Além das novas funções para próxima versão do sistema:
- Cadastrar usuário (cliente)
- Cadastrar conta bancária

Funções opcionais:
- listar contas

#### Saque
Deve receber os argumentos apenas por nome (*keyword only*).
Sugestão de argumentos:
- saldo
- valor
- extrato
- limite
- numero_saques
- limite_saques

Sugestão de retorno:
- saldo
- extrato

#### Extrato
Deve receber os argumentos por posição e nome (*positional only* e *keyword only*).
Argumentos posicionais:
- saldo

Argumentos nomeados:
- extrato

#### Criar usuário (cliente)
A aplocação deve armazenar os usuários em uma lista, sendo o usuário composto por:
- nome
- data de nascimento
- CPF
- endereço
  - logradouro
  - número
  - bairro
  - cidade
  - sigla estado

Deve ser armazenado somente os números do CPF, não podendo haver duplicidade.
#### Criar conta corrente
A aplicação deve amarzenar em lista, sendo composta da seguinte forma:
- conta
  - agência
  - número da conta
  - usuário

O número da conta é sequencial, iniciando em 1.
O número da agência é fixo: `0001`.
O usuário pode ter mais de uma conta, mas uma conta pertence somente a um usuário.
>[!NOTE]Dica
> Para vincular um usuário a uma conta, filtre a lista de usuários buscando o CPF informado para cada usuário da lista.
