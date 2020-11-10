# Repositório para revisão

Primeiro, criar uma pasta na nossa máquina para colocar os arquivos do projeto.

Inicializar a pasta com o git

```
 git init
```

Cria um repositório no github e assicia a pasta do projeto local como o repositório do github.
Inicializar a pasta com o git

```
 git remote add origin https://github.com/caixetovisk/revisao-gith-github.git
```

Altera o nome da branch de master para main

```
 git branch -M main
```

Adiciona arquivo para serem enviados para o github

```
 git add .
```

Colocamos uma mensagem do que foi feito

```
 git commit -m "Iniciando o repositório"
```

Enviamos as alterações para o github

```
 git push -u origin main
```
