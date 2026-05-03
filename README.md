# 🐙 Git & GitHub

### 📚 Guia Rápido de Comandos Essenciais

Repositório destinado ao aprendizado de **Git e GitHub** 🚀
Aqui você encontra os principais comandos para controle de versão de forma **simples e prática**.

---

# 🔗 1. Conectar Repositório Local ao GitHub

### ➕ Adicionar repositório remoto

```bash
git remote add origin URL_DO_REPOSITORIO
```

📌 Conecta seu projeto local ao GitHub

---

### ❌ Remover repositório remoto

```bash
git remote remove origin
```

📌 Remove a conexão atual

---

### 🔄 Alterar URL do repositório

```bash
git remote set-url origin NOVA_URL
```

📌 Útil quando a URL está errada

---

### ✏️ Renomear repositório remoto

```bash
git remote rename origin novo-nome
```

📌 Altera o apelido (ex: origin → upstream)

---

# 🔄 2. Sincronização com o Repositório

### ⬇️ Atualizar projeto (pull)

```bash
git pull origin main
```

📌 Baixa alterações do GitHub para sua máquina
📌 Evita conflitos e mantém tudo atualizado

---

# 🕓 3. Histórico e Controle de Commits

### 📜 Ver histórico

```bash
git log
```

---

### ⏪ Reverter um commit (seguro)

```bash
git revert ID_DO_COMMIT
git push origin main
```

📌 Cria um novo commit desfazendo o anterior
📌 Seguro para projetos compartilhados

---

### ⚠️ Resetar commit (CUIDADO)

```bash
git reset --hard ID_DO_COMMIT
```

🚨 Apaga commits permanentemente
🚨 Use **apenas localmente**

---

# ✏️ 4. Alterar último commit

```bash
git commit --amend -m "Nova mensagem"
```

📌 Permite corrigir a mensagem do último commit
📌 Use antes de fazer push

---

# 💡 Dicas Importantes

* ✅ Sempre faça `git pull` antes de começar a trabalhar
* ✅ Use `git revert` em projetos com outras pessoas
* ⚠️ Evite `reset --hard` em repositórios compartilhados
* 📦 Commits pequenos e organizados ajudam muito

---

# 🎯 Resumo

✔️ Conectar repositório
✔️ Sincronizar alterações
✔️ Corrigir commits
✔️ Evitar conflitos

---

🔥 **Dominar Git é essencial para qualquer desenvolvedor — pratique todos os dias!**
