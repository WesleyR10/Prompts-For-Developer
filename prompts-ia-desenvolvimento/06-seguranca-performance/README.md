# 🔒 **Segurança e Otimização de Código**

> 🛡️ **Código seguro e performático!** Prompts para auditorias de segurança e otimizações de performance.

---

### **46. 🛡️ Auditoria Completa de Segurança**

**Para que serve:** Análise abrangente de segurança

```jsx
Execute uma auditoria de segurança no seguinte código:
[Cole seu código aqui]

Identifique vulnerabilidades incluindo:
- Injeções (SQL, NoSQL, OS)
- Autenticação quebrada
- Exposição de dados confidenciais
- XXE, controle de acesso quebrado
- Configurações incorretas
- XSS, deserialização insegura
- Componentes vulneráveis
- Logging insuficiente

Para cada vulnerabilidade:
1. Explique o impacto
2. Sugira correção/mitigação
3. Forneça código demonstrativo
4. Recomende bibliotecas/ferramentas de segurança
```

### **47. ⚡ Otimização Abrangente de Performance**

**Para que serve:** Melhorar desempenho geral

```jsx
Analise este código para otimizações de performance:
[Cole seu código aqui]

Identifique:
1. Gargalos e operações ineficientes
2. Melhorias em complexidade de tempo/memória
3. Reduções de operações desnecessárias
4. Potencial para paralelização/async
5. Estratégias de cache

Para cada sugestão: explique impacto esperado, forneça código otimizado e discuta trade-offs.
```

### **48. 📚 Atualização de Melhores Práticas**

**Para que serve:** Manter-se atualizado

```jsx
Forneça atualizações sobre práticas recomendadas para [linguagem/framework] focando em:
1. Melhorias de segurança e vulnerabilidades recentes
2. Técnicas de otimização de performance
3. Novos recursos que melhoram segurança/performance
4. Práticas obsoletas a evitar

Para cada ponto explique: o que é, por que é importante, como implementar.
```

### **49. 💉 Análise de SQL Injection**

**Para que serve:** Identificar vulnerabilidades específicas de injeção

```jsx
Revise este código de BD para vulnerabilidades de SQL injection:
[Cole código de interação com BD]

Para cada vulnerabilidade:
1. Explique como pode ser explorada
2. Forneça implementação segura alternativa
3. Sugira bibliotecas/técnicas de segurança específicas
```

### **50. 🔧 Otimização de Operações Intensivas**

**Para que serve:** Melhorar funções com alto consumo

```jsx
Esta função está causando problemas de performance:
[Cole sua função]

Sugira otimizações considerando:
1. Melhorias na complexidade de tempo
2. Otimização do uso de memória
3. Cache/memoização
4. Processamento paralelo

Para cada sugestão: explique ganho esperado e trade-offs.
```

### **51. 🌐 Melhoria da Segurança Front-end**

**Para que serve:** Fortalecer segurança client-side

```jsx
Revise este código front-end para melhores práticas de segurança:
[Cole código front-end]

Considere:
1. Prevenção de XSS
2. Manuseio seguro de dados confidenciais
3. Proteção contra CSRF
4. Comunicação segura com APIs

Forneça recomendações específicas incluindo bibliotecas/técnicas relevantes.
```

---

## 🎯 **Áreas de Foco**

| 🔒 **Segurança**      | ⚡ **Performance**    | 📝 **Prompt** |
| --------------------- | --------------------- | ------------- |
| **Auditoria Geral**   | Análise abrangente    | #46           |
| **SQL Injection**     | Vulnerabilidades BD   | #49           |
| **Front-end**         | Segurança client-side | #51           |
| **Otimização Geral**  | Performance completa  | #47           |
| **Operações Pesadas** | Funções intensivas    | #50           |
| **Melhores Práticas** | Atualizações recentes | #48           |

---

## ⚠️ **Melhores Práticas**

### **🔒 Segurança:**

- ✅ Validação de entrada rigorosa
- ✅ Princípio do menor privilégio
- ✅ Criptografia adequada
- ✅ Logs de segurança
- ✅ Atualizações regulares

### **⚡ Performance:**

- ✅ Profile antes de otimizar
- ✅ Cache estratégico
- ✅ Operações assíncronas
- ✅ Monitoramento contínuo
- ✅ Testes de carga

### **❌ Evite:**

- ❌ Otimização prematura
- ❌ Segurança por obscuridade
- ❌ Dados sensíveis em logs
- ❌ Dependências desatualizadas
- ❌ Configurações padrão inseguras

---

## 🔄 **Fluxo Recomendado**

1. **Auditoria inicial** → Use prompt #46
2. **Análise específica** → Use prompts #49, #51
3. **Otimização** → Use prompts #47, #50
4. **Atualização** → Use prompt #48 regularmente
5. **Monitoramento** → Implemente métricas
6. **Revisão periódica** → Repita o ciclo

---

## 🔗 **Links Relacionados**

- **[02 - Código](../02-codigo/)** - Para revisar código antes da auditoria
- **[03 - Banco de Dados](../03-banco-dados/)** - Para segurança de dados
- **[05 - Testes & QA](../05-testes-qa/)** - Para testes de segurança
- **[04 - Documentação](../04-documentacao/)** - Para documentar práticas

---

> ⚡ **Lembre-se:** Segurança e performance devem ser consideradas desde o design, não apenas no final!

