# Git-Github
Repositório destinado a aprender sobre Git e GitHub

# Comandos Úteis:
git remote add origin(apelido) url: conecta o diretório local ao repositório do git hub
git remote remove origin: usada para trocar o repositório
git remote set-url origin(apelido) nova_url: serve para trocar a url (caso esteja errada)
git remote rename origin novo-origin: trocar o apelido do repositório
git pull origin main: puxa os dados do repositório remoto para o local, evitando um conflito de dados e garantindo uma sincronização
git log -> copiar o id e usar git revert id: reverter um commit -> git push origin main
git reset --hard id: apaga o commit, só deve ser utilizado localmente
git commit --amend -m "Mensagem": altera a mensagem do commit antes de ser enviada
