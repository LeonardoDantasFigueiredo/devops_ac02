### Leonardo Dantas Figueiredo - RA 1903702

### Exemplo comando Clone:
1. Criando um repositório via interface web (print_01)
2. ls (print_02 mostrando diretório vazio)
3. git clone https://github.com/LeonardoDantasFigueiredo/devops_ac02
4. cd devops_ac02
5. ls (print_03 mostrando diretório do projeto e README nele contido)

### Exemplo comando Add:

1. git add --all (print_04 adiciona arquivos ao repositório local e faz stage para commit)
2. ls (print_05 mostrando novos arquivos no repositório local)
3. git status (print_06 arquivos em stage prontos para commit )

### Exemplo comando Commit:

1. git commit (print_07 commitando as modificações e deixando pronto para dar push pro repositório remoto)
2. git status (print_08 informando que nosso repositório local tem modificações a frente do repositório remoto)

### Exemplo comando Push:

1. git push (print_09 realiza o push das modificações feitas no repositório local para o remoto indicado)
2. git status (print_10 informando que os repositórios estão atualizados)

### Exemplo comando Fetch:
1. git status (print_11 informando que o repositório remoto tem modificações a frente do repositório local)
2. git fetch (baixa os arquivos do repositório remoto mas não os grava no repositório local)
3. git merge (print_12 grava os arquivos do repositório remoto no repositório local)

### Exemplo comando Pull:

1. git status (print_13 confirmando se existem mudanças nos repositórios)
2. git pull (print_14 buscar e baixar arquivos dos repositórios remotos e fazer a atualização imediata ao repositório local para que os conteúdos sejam iguais)

### Exemplo comando Checkout:

1. git branch (print_15 criando uma nova branch)
2. git checkout (print_15 mudando para a nova branch)
3. git status (print_15 informando que existem mudanças sem stage)

- git log (print_16)