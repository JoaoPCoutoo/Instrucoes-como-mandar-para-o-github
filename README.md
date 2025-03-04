# Como Criar e Enviar um Projeto para o GitHub

## 1. Criar um Repositório no GitHub
1. Acesse [GitHub](https://github.com) e crie um novo repositório.
2. Copie a URL do repositório criado.

## 2. Acessar o Diretório do Projeto
Abra o terminal e navegue até a pasta do seu projeto:
```sh
cd C:\Users\Desktop\Nome
```

## 3. Inicializar o Git no Projeto
```sh
git init
```

## 4. Conectar ao Repositório Remoto
Substitua `SEU_USUARIO` e `NOME_DO_REPOSITORIO` pela sua conta e nome do repositório:
```sh
git remote add origin https://github.com/SEU_USUARIO/NOME_DO_REPOSITORIO.git
```

## 5. Verificar os Arquivos
```sh
git status
```

## 6. Adicionar os Arquivos ao Git
```sh
git add .
```

## 7. Criar o Primeiro Commit
```sh
git commit -m "Adicionando README com instruções"
```

## 8. Verificar o Nome da Branch
```sh
git branch
```
Se aparecer `main`, use `main` no próximo passo.
Se for `master`, use `master`.

## 9. Enviar o Projeto para o GitHub
Para a branch `main`:
```sh
git push -u origin main
```

Para a branch `master`:
```sh
git push -u origin master

