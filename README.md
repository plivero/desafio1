# desafio1

Se trata de um desafio solicitado por henriquelh1.
1. Criar um novo repositório com README file

2. Clonar repositório

3. Fazer Configuracao para commit assinado (pesquisar como fazer com chatgpt, "commits verified on github using windows"), dicas:
a. tem que instalar uma paradinha antes
b. Tu vai gerar uma chave que tem que ser adicionada manualmente no github
c. no hora de configurar, o email tem que ser o mesmo da conta GitHub
d. no meio da configuração vai pedir pra tu criar uma senha, cria uma senha curta e facil que tu nao ESQUECA
e. depois da configuracao se o commit ainda não tiver assinado verifica tuas variaveis globais de configuração, o email global tem que ser o mesmo que tu configurou no processo, ou seja o mesmo do GitHub
f. Talvez a tua chave ja esteja configurada, e aplicacao da assinatura so venham nos futuros commits. Mas voce tem ver que todos os commits verificados, inclusive os antigos. Verificar como fazer isso com “git commit. —amend”

4. Uma vez que a chave foi criada e adicionada no github, crie regras para a branch PRINCIPAL para o novo repositório no github:
a. necessario commit assinado
b. necessario ao menos um aprovador
c. necessario conversation resolution
d. necessario most recent push reviewed

5. Adicionar henriquehl1 como colaborador do repositorio

6. Apos de configurado assinatura e de criar as regras da branch, volte ao repo local, crie uma branch com alguma mudanca e faca um Pull Request e coloque henriquehl1 como reviewer