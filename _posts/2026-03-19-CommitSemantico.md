---
title: Commits Semânticos
date: 2026-03-19 23:00:00 -0300
categories: [Desenvolvimento, Git]
tags: [git, boas-praticas, conventional-commits, dev-tips]
---

# Estrutura
```
<tipo>(<escopo>): <descrição>
```
```
feat(auth): adiciona login com Google
fix(cart): corrige total ao remover item
docs: atualiza README
```

O escopo é opcional, mas ajuda a indicar qual parte do projeto foi afetada.

# Tipos

| Tipo       | Uso                                 |
| ---------- | ----------------------------------- |
| `feat`     | Nova funcionalidade                 |
| `fix`      | Correção de bug                     |
| `refactor` | Refatoração sem mudar comportamento |
| `docs`     | Documentação                        |
| `test`     | Testes                              |
| `chore`    | Manutenção, dependências, CI        |
| `style`    | Formatação sem mudança de lógica    |
| `perf`     | Melhoria de performance             |

# Breaking Changes

Adicione `!` para sinalizar que a mudança quebra compatibilidade:
```
feat(api)!: remove endpoint /v1/users deprecado
```
