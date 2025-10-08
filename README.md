# repositorio-01 🌟 AULÃO ALPHA DE GIT 1 - INTRODUÇÃO
---
## Contexto

No dia **07 de outubro de 2025** nos reunimos às _8h e 30 minutos_ de uma manhã de **_terça-feira_** para aprimorar nossos conhecimentos sobre o tema **GIT**. Nosso tutor, ex-aspirante Alpha Lumen, *Leonardo Mori*, nos orientou sobre o assunto e nos deixou uma missão.

> Agora é a vez de vocês!

---
## A missão

A atividade proposta incluía os seguintes passos ordenados, e colocava em prática o conteúdo aprendido durante o encontro síncrono: 

1. Instalar o git no computador.
2. Configurar o git.
3. Criar conta no git hub.
4. Configurar chave ssh.
5. Criar um novo repositório remoto.
6. Criar um novo repositório local.
7. Configurar git remote no repositório local.
8. Criar arquivo readme.md ou index.html.
9. Fazer o primeiro commit.
10. Fazer o primeiro push.
11. Servir a página no git hub pages.

**Ponto em prática**

Segue os códigos usados no Git Bash para configurar a chave ssh:

```
ssh-keygen -t ed25519 -C "bia.gonzag@gmail.com"
cd /c/Users/Bianca/.ssh
ls
cat chaveprivada.pub
```
A chave ssh gerada deve ser anexada ao Git Hub.
 
Segue os códigos usados no Git Bash para criar um repositório remoto, um repositório local, configurar o git remote no repositório local, criar o readme.md, fazer o primeiro commit e o primeiro push :

```
cd /d/Aprendizado
mkdir repositorio-01
cd repositorio-01
git init
git remote add origin git@github.com:biagonzag-hue/repositorio-01.git
git remote -v
echo "#repositorio-01" > README.md
git add .
git commit -m "Primeiro commit: criando estrutura inicial"
git branch -M main
git push -u origin main
```

## README.md

Após a conclusão da atividade seguindo as ordens especificadas, este arquivo em questão foi preenchido com texto para treinar a escrita da formatação Markdown. Após as alterações, ele foi upado no GitHub!

```
git status
git add README.md
git commit -m "Atualizando conteúdo do README"
git push
```
Para concluir essa etapa segue um [link para uma música de vitória](https://youtu.be/04854XqcfCY?list=RD04854XqcfCY) e uma imagem em comemoração:

![](https://img.freepik.com/vetores-premium/emoticon-de-pulso-para-cima-piscando_1303870-100.jpg?semt=ais_hybrid&w=740&q=80)