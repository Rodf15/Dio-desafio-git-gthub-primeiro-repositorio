# Manual básico Git/Github



### criando primeiro repositório  

Primeiramente acesse o site [Github](www.github.com) e crie sua conta, o processo é bem simples como podemos ver abaixo:

https://drive.google.com/file/d/1mkUFMMwn9jzyCrFKwUlS-J70VVmQszT6/view?usp=sharing

Depois de sua conta criada clique em New Repository, no canto superior direito, como na imagem abaixo:

https://drive.google.com/file/d/12SX2OICnKWCYqwuXdsrRsFlNzL4Pnp1H/view?usp=sharing

Defina o nome ,descrição e tipo de projeto:

https://drive.google.com/file/d/12SX2OICnKWCYqwuXdsrRsFlNzL4Pnp1H/view?usp=sharing

Agora, assumindo que você já tem o git instalado na sua maquina, vamos adicionar o seu projeto local ao seu Repositório no Github, clique com o botão direito do seu mouse, depois clique em 'Git Bash Here' dentro da pasta onde esta seu repositório.

https://drive.google.com/file/d/1nUsDe3f1vSG3-szkdiKcFV1JftGza7XW/view?usp=sharing

Digite o comando 'git init' em seu terminal

https://drive.google.com/file/d/1h0Hltzlj2lHNtOep6tfzKt0DMCSs4W2c/view?usp=sharing

Se for a primeira vez que você estiver usando o Git é importante que você configure seu email e nome para que sempre que criar um commit ele tenha um autor, useremos os seguintes com os seguintes comandos:

git config --global user.email "seu email"

git config --global user.name "seu nome" 



#### É interessante que seu nome e email sejam o mesmo cadastrados no Github para que ele identifique você como autor(a). 

Caso deseje reescrever essas configurações vc pode resetar e inseri-las novamente.

Para "resetar" essas configurações utilize os comandos:

git confg --global --unset user.email 

git confg --global --unset user.name

Para verificar as configurações do seu Git utilize o comando:

git config --list



#### Feito isso crie seu arquivo, pode ser TXT (.txt) ou Markdown (.md)

Agora vamos adicionar os arquivos, "commitar" e "pushar", com os seguintes comandos:

git remote add origin "link do seu repositório sem aspas"

git add .

git commit -m "meu primeiro commit"

git push origin master

### Criando um clone

Abra o "git bash" no diretorio onde quer que o arquivo fique, no [Github](www.github.com) navegue até o repositório a ser clonado, clique no botão verde "Code" e copie o link do repositório:



https://drive.google.com/file/d/1s-av4dyzYxBxgmm0HQsl-CaIahM5vlEh/view?usp=sharing

No seu terminal use o seguinte comando:

git clone "link copiado sem aspas"

#### pronto!... O repositório já estará copiado em sua maquina.

Para reenviar os arquivos clonados após modificações, utilize os comandos:

- Para adicionar:

  git add . 

- Para "commitar"

  git commit -m "nome dado a commit"

- Para enviar('Pushar') ao Github

  git push origin main



Fiz o manual de forma simples e básica, contribuam com ele  lá no [Github](https://github.com/Rodf15/Dio-desafio-git-gthub-primeiro-repositorio.git), qualquer critica construtiva estamos ai!... abraços!!! 

P.S.  As definições do que é Git e Github estão em outra pasta deste repositório.







