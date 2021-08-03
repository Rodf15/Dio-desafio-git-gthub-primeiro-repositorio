# Criando um Repositório

Primeiramente acesse o site [Github](www.github.com) e crie sua conta, o processo é bem simples como podemos ver abaixo:

![](C:\Users\Rodrigo Furtado\Desktop\imagem\Capturar1.PNG)

Depois de sua conta criada clique em New Repository, no canto superior direito, como na imagem abaixo:

![](C:\Users\Rodrigo Furtado\Desktop\imagem\1_WkZqiJ8JXvDLe0rdl6d_AQ.png)

Defina o nome ,descrição e tipo de projeto:

![](C:\Users\Rodrigo Furtado\Desktop\imagem\Capturar.PNG)

Agora vamos adicionar o seu projeto local ao seu Repositório no Github, clique com o botão direito do seu mouse, depois clique em 'Git Bash Here' dentro da pasta onde esta seu repositório.

![](C:\Users\Rodrigo Furtado\Desktop\imagem\Capturar2.PNG)

Digite o comando 'git init' em seu terminal

 ![](C:\Users\Rodrigo Furtado\Desktop\imagem\Capturar3.PNG)

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



![](C:\Users\Rodrigo Furtado\Desktop\imagem\Capturar5.PNG)

No seu terminal use o seguinte comando:

git clone "link copiado sem aspas"

#### pronto!... O repositório já estará copiado em sua maquina.









