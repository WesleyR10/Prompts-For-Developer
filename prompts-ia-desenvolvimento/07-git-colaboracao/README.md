# 🔄 **Controle de Versão e Colaboração**

> 🤝 **Trabalho em equipe eficiente!** Prompts para otimizar fluxos Git e melhorar colaboração.

---

### **52. 📝 Mensagens de Commit Profissionais**

**Para que serve:** Criar histórico claro e informativo

```jsx
Fiz as seguintes alterações:
[Cole git diff ou descreva alterações]

Crie uma mensagem de commit que:
1. Resuma alterações concisamente (≤50 chars no título)
2. Forneça detalhes no corpo (quebra em 72 chars)
3. Siga melhores práticas do git
4. Inclua números de issues/referências relevantes

A mensagem deve ser informativa para que a equipe entenda sem consultar código.
```

### **53. ⚔️ Resolução de Conflitos de Merge**

**Para que serve:** Resolver conflitos eficientemente

```jsx
Enfrentando este conflito de merge:
[Cole seções conflitantes]

O recurso sendo mesclado visa: [Descreva objetivo do recurso]

Ajude a resolver:
1. Analisando ambas as versões
2. Sugerindo melhor forma de combinar alterações
3. Fornecendo versão resolvida
4. Explicando raciocínio da resolução

Há problemas/efeitos colaterais potenciais pós-merge?
```

### **54. 🔍 Revisão de Pull Requests**

**Para que serve:** Melhorar qualidade via revisões estruturadas

```jsx
Revise esta solicitação de pull:
[Cole diff do PR ou resumo das alterações]

Na revisão:
1. Identifique problemas/melhorias potenciais
2. Verifique aderência aos padrões do projeto
3. Sugira testes necessários
4. Indique partes que precisam mais documentação
5. Destaque preocupações de segurança/performance

Para cada ponto: forneça explicação e como abordar.
```

### **55. 📁 Criação de Arquivo .gitignore**

**Para que serve:** Configurar exclusões apropriadas

```jsx
Iniciando projeto [linguagem/framework]. Crie .gitignore abrangente que:
1. Exclua arquivos comuns de sistema/IDE
2. Ignore artefatos e dependências específicos da linguagem
3. Garanta que informações sensíveis não sejam commitadas

Forneça explicações para entradas não óbvias.
```

### **56. 📋 Notas de Lançamento**

**Para que serve:** Comunicar mudanças claramente

```jsx
Preparando release versão [XYZ]. Baseado neste histórico de commits:
[Colar histórico relevante]

Redija notas de lançamento que:
1. Resumam principais novos recursos
2. Listem mudanças significativas e etapas de migração
3. Mencionem correções de bugs e melhorias de performance
4. Agradeçam colaboradores

Tom profissional mas amigável, adequado para leitores técnicos e não-técnicos.
```

### **57. 🌿 Convenções de Nomenclatura de Branches**

**Para que serve:** Estabelecer padrões consistentes

```jsx
Nossa equipe precisa de convenção de nomenclatura de branches consistente. Sugira estratégia que:
1. Indique claramente tipo de trabalho (feature, bugfix, hotfix)
2. Inclua números de tickets/problemas relevantes
3. Seja concisa mas descritiva

Forneça exemplos para diferentes cenários e explique a lógica da convenção.
```

---

## 🎯 **Fluxos de Trabalho**

| 🔄 **Atividade**  | 🎯 **Objetivo**         | 📝 **Prompt** |
| ----------------- | ----------------------- | ------------- |
| **Commits**       | Histórico claro         | #52           |
| **Conflitos**     | Resolução eficiente     | #53           |
| **Pull Requests** | Revisões estruturadas   | #54           |
| **Configuração**  | Setup inicial           | #55           |
| **Releases**      | Comunicação de mudanças | #56           |
| **Branches**      | Organização consistente | #57           |

---

## ⚠️ **Melhores Práticas**

### **✅ Git Eficiente:**

- ✅ Commits pequenos e focados
- ✅ Mensagens descritivas
- ✅ Branches com propósito claro
- ✅ Revisões de código regulares
- ✅ Histórico limpo e linear

### **🤝 Colaboração:**

- ✅ Comunicação clara em PRs
- ✅ Feedback construtivo
- ✅ Padrões de equipe definidos
- ✅ Documentação atualizada
- ✅ Resolução rápida de conflitos

### **❌ Evite:**

- ❌ Commits gigantes
- ❌ Mensagens vagas ("fix bug")
- ❌ Branches abandonadas
- ❌ Conflitos não resolvidos
- ❌ Histórico confuso

---

## 🔄 **Fluxo de Trabalho Recomendado**

1. **Setup inicial** → Use prompt #55 (.gitignore)
2. **Desenvolvimento** → Use prompt #57 (branches)
3. **Commits** → Use prompt #52 (mensagens)
4. **Colaboração** → Use prompt #54 (PRs)
5. **Conflitos** → Use prompt #53 (resolução)
6. **Release** → Use prompt #56 (notas)

---

## 🛠️ **Comandos Git Essenciais**

```bash
# Configuração inicial
git config --global user.name "Seu Nome"
git config --global user.email "seu@email.com"

# Fluxo básico
git checkout -b feature/nova-funcionalidade
git add .
git commit -m "feat: adiciona nova funcionalidade"
git push origin feature/nova-funcionalidade

# Resolução de conflitos
git fetch origin
git rebase origin/main
# Resolver conflitos manualmente
git add .
git rebase --continue
```

---

## 🔗 **Links Relacionados**

- **[01 - Planejamento](../01-planejamento/)** - Para estruturar fluxos de trabalho
- **[04 - Documentação](../04-documentacao/)** - Para documentar processos
- **[05 - Testes & QA](../05-testes-qa/)** - Para integrar testes no fluxo
- **[02 - Código](../02-codigo/)** - Para revisar código em PRs

---

> 🚀 **Dica:** Boas práticas de Git facilitam colaboração e manutenção do projeto a longo prazo!

