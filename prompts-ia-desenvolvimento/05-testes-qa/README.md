# 🧪 **Testes, Depuração e Garantia de Qualidade**

> 🎯 **Qualidade desde o início!** Prompts para criar testes abrangentes e eliminar bugs eficientemente.

---

## 🎯 **TESTES UNITÁRIOS E FUNCIONAIS**

### **39. 🎯 Testes Unitários Abrangentes**

**Para que serve:** Criar conjunto completo de testes para funções específicas

> **⚠️ Observação Vital:** Cubra cenários de caminho feliz, casos extremos e condições de erro!

```jsx
Preciso de testes unitários para a seguinte função:
[Cole sua função aqui]

Gere um conjunto abrangente de testes unitários que abranjam:
1. Cenários de caminho feliz
2. Casos extremos
3. Condições de erro
4. Análise de valor limite

Para cada caso de teste, por favor:
1. Forneça uma breve descrição do que o teste está verificando
2. Escreva o código de teste real usando [estrutura de teste preferida, por exemplo, pytest]
3. Explique quaisquer objetos ou acessórios simulados que possam ser necessários

Além disso, sugira quaisquer testes adicionais que possam ser relevantes com base em armadilhas comuns ou práticas recomendadas para esse tipo de função.
```

### **40. 🐛 Depuração Assistida por IA**

**Para que serve:** Diagnosticar e resolver bugs complexos

```jsx
Estou enfrentando o seguinte bug:
[Descreva o bug, incluindo quaisquer mensagens de erro e as etapas para reproduzi-lo]

Aqui está o código relevante:
[Cole o código relacionado ao bug]

Por favor, ajude-me a depurar este problema:
1. Analise o código e sugira possíveis causas do bug
2. Forneça estratégias de depuração passo a passo que eu possa seguir
3. Sugira quaisquer ferramentas ou técnicas que possam ser úteis no diagnóstico do problema
4. Se possível, proponha possíveis correções e explique o raciocínio

Além disso, há alguma prática recomendada ou armadilha comum relacionada a esse tipo de problema que eu deva conhecer para referência futura?
```

### **41. 🔍 Revisão Contínua de Código para QA**

**Para que serve:** Manter qualidade de código através de revisões regulares

```jsx
Revise o código a seguir em busca de qualidade e possíveis problemas:
[Cole seu código aqui]

Em sua revisão, considere:
1. Estilo do código e adesão às melhores práticas
2. Possíveis bugs ou casos extremos não tratados
3. Otimizações de desempenho
4. Vulnerabilidades de segurança
5. Legibilidade e manutenibilidade

Para cada problema encontrado, por favor:
1. Explique o problema
2. Sugira uma correção
3. Forneça uma breve justificativa para a alteração sugerida

Além disso, há alguma melhoria geral ou sugestão de refatoração que você faria para este código?
```

---

## 🔗 **TESTES DE INTEGRAÇÃO E SISTEMA**

### **42. 🔗 Testes de Integração**

**Para que serve:** Testar interação entre componentes do sistema

```jsx
Preciso criar testes de integração para os seguintes componentes:
[Listar componentes e suas interações]

Por favor, sugira um conjunto de testes de integração que:
1. Abranjam os principais cenários de interação entre esses componentes
2. Testem o tratamento adequado de erros e casos extremos
3. Incluam quaisquer procedimentos necessários de configuração e desmontagem

Forneçam os cenários de teste em um formato claro e passo a passo, e incluam quaisquer objetos simulados ou dados de teste necessários.
```

### **43. 🚀 Testes de Performance**

**Para que serve:** Avaliar e monitorar desempenho da aplicação

```jsx
Preciso criar um plano de testes de desempenho para minha aplicação. As principais áreas de interesse são:
[Listar as principais funcionalidades ou componentes a serem testados]

Por favor, ajude-me a criar um plano de testes de desempenho que inclua:
1. Indicadores-chave de desempenho a serem medidos
2. Cenários de teste para simular diversas condições de carga
3. Sugestões de ferramentas ou frameworks a serem utilizados
4. Estratégias para identificar gargalos de desempenho
5. Melhores práticas para interpretar e atuar sobre os resultados.
```

### **44. 🛡️ Testes de Segurança**

**Para que serve:** Identificar vulnerabilidades de segurança no código

```jsx
Revise o código a seguir para possíveis vulnerabilidades de segurança:
[Cole seu código]

Considere problemas comuns de segurança, como:
1. Falhas de injeção
2. Autenticação quebrada
3. Exposição de dados confidenciais
4. Entidades externas XML (XXE)
5. Controle de acesso quebrado
6. Configurações incorretas de segurança
7. Cross-site scripting (XSS)

Para cada vulnerabilidade encontrada, explique o risco e sugira práticas de codificação seguras para mitigá-lo.
```

---

## 📊 **DADOS DE TESTE**

### **45. 📊 Geração de Dados de Teste**

**Para que serve:** Criar dados realistas e diversos para testes

```jsx
Preciso gerar dados de teste para o seguinte esquema de banco de dados:
[Cole seu esquema aqui]

Ajude-me a criar um plano de geração de dados de teste:
1. Sugira intervalos ou tipos de valores apropriados para cada campo
2. Forneça SQL ou script para gerar um conjunto diversificado de dados de teste, incluindo:
   - Casos normais
   - Casos extremos
   - Dados inválidos para testar o tratamento de erros
3. Garanta que a integridade referencial seja mantida para tabelas relacionadas
4. Inclua quaisquer cenários específicos ou padrões de dados cruciais para testes completos

Os dados de teste devem ser abrangentes o suficiente para cobrir vários cenários de teste, mantendo um tamanho gerenciável.
```

---

## 🎯 **Estratégia de Testes**

| 🧪 **Tipo de Teste** | 🎯 **Objetivo**            | 📝 **Prompt** |
| -------------------- | -------------------------- | ------------- |
| **Unitário**         | Testar funções isoladas    | #39           |
| **Integração**       | Testar interações          | #42           |
| **Performance**      | Medir velocidade/carga     | #43           |
| **Segurança**        | Encontrar vulnerabilidades | #44           |
| **Dados**            | Gerar dados realistas      | #45           |

---

## ⚠️ **Melhores Práticas de QA**

### **✅ Testes Eficazes:**

- ✅ Cubra casos felizes e extremos
- ✅ Automatize testes repetitivos
- ✅ Mantenha testes independentes
- ✅ Use dados realistas
- ✅ Documente cenários de teste

### **❌ Armadilhas Comuns:**

- ❌ Testes dependentes entre si
- ❌ Dados de teste irrealistas
- ❌ Cobertura insuficiente
- ❌ Testes lentos demais
- ❌ Ignorar casos extremos

---

## 🔄 **Ciclo de QA**

1. **Planejamento** → Defina estratégia de testes
2. **Unitários** → Use prompt #39
3. **Integração** → Use prompt #42
4. **Performance** → Use prompt #43
5. **Segurança** → Use prompt #44
6. **Dados** → Use prompt #45
7. **Depuração** → Use prompt #40 quando necessário
8. **Revisão** → Use prompt #41 regularmente

---

## 🔗 **Links Relacionados**

- **[02 - Código](../02-codigo/)** - Para revisar código antes dos testes
- **[06 - Segurança & Performance](../06-seguranca-performance/)** - Para testes avançados
- **[03 - Banco de Dados](../03-banco-dados/)** - Para testes de dados

---

> 💡 **Dica:** Testes não são custo, são investimento! Quanto mais cedo você testar, menos bugs chegam à produção!

