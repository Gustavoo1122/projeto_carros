# 🚀 Fluxo de Uso do Git

Este guia deve ser seguido por todos os membros ao iniciar e finalizar uma tarefa.

---

## ▶️ Antes de começar qualquer tarefa

### 1 - Ir para a branch `develop`

```bash
git switch develop
```

### 2 - Atualizar a branch

```bash
git pull origin develop
```

### 3 - Criar sua branch de feature

```bash
git switch -c feature/nome_da_sua_feature
```

Exemplo:

```bash
git switch -c feature/tela_login
```

---

## 💻 Durante o desenvolvimento

Você pode fazer vários commits ao longo do processo.

---

## ✅ Quando terminar a tarefa

### 1 - Adicionar as alterações

```bash
git add .
```

### 2 - Criar o commit

```bash
git commit -m "feat: descrição da alteração"
```

Seguindo a convenção de commits definida para o projeto.

### 3 - Enviar para o GitHub

```bash
git push origin feature/nome_da_sua_feature
```

Exemplo:

```bash
git push origin feature/tela_login
```

---

## 🔁 Depois disso

1. Vá no GitHub
2. Abra um **Pull Request**
3. Direcione para a branch `develop`
4. Aguarde revisão de outro membro

#### ⚠️ Nunca fazer alterações direto na `main`.