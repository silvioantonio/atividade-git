# atividade-git

## passo a passo
Primeiro crie um novo projeto no github e em seguida, clone o repositorio.
No terminal do seu computador(LINUX).
'mkdir atividade-git'
dentro do seu computador, clone o repositorio com o comando:
' git clone git@github.com:silvioantonio/atividade-git.git '
Para criar o arquivo README do seu projeto utilize o comando:
' echo "#atividade-git" >> README.MD '
Em seguida inicialize o repositorio
' git init '
para ver o status dos arquivos do seu projeto utilize o comando
' git status '
Em seguida adicione o arquivo recem criado README a lista do git
' git add README.MD '
Utilize o comando COMMIT com o atributo -m para colocar uma mensagem de orientaçao
' git commit -m "primeiro commit" '
Em seguida adicione as alteraçoes feitas para o ramo master
' git remote add origin https://github.com/silvioantonio/atividade-git.git '
Por fim envie em definitivo
' git push -u origin master '

