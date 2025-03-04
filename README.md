-Criar um repositório no GitHub
Vá até https://github.com e crie um novo repositório

-Acesse o que voc~e deseja mandar 
cd C:\Users\Desktop\Nome

-No terminal, inicialize o Git no projeto:
git init

-Conecte ao repositório remoto:
git remote add origin https://github.com/SEU_USUARIO/NOME_DO_REPOSITORIO.git

-Enviar para o GitHub

Verifique os arquivos:
git status

Adicione os arquivos:
git add .

Faça o primeiro commit:
git commit -m "Adicionando README com instruções"

Verifique o nome da branch:
git branch
Se aparecer main, use main no próximo passo.
Se for master, use master.

Envie o projeto para o GitHub:
git push -u origin main
ou, se a branch for master:
git push -u origin master
