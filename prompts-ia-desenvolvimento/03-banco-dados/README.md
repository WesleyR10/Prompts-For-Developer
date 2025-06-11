# 🗄️ **Design e Otimização de Banco de Dados**

> 🚀 **Dados bem estruturados = performance garantida!** Prompts para criar esquemas eficientes e consultas otimizadas.

---

## 🏗️ **DESIGN DE ESQUEMAS**

### **24. 🏗️ Esquema de Banco de Dados Completo**

**Para que serve:** Criar estrutura de banco de dados robusta e escalável

```jsx
Estou projetando um banco de dados para [descreva sua aplicação]. As principais entidades são:
[Liste as principais entidades]

Requisitos principais:
1. [Requisito 1, por exemplo, "Deve oferecer suporte à recuperação rápida de postagens do usuário"]
2. [Requisito 2, por exemplo, "Necessidade de rastrear relacionamentos do usuário (seguidores/seguindo)"]
3. [Requisito 3, por exemplo, "Deve lidar com grandes volumes de dados de séries temporais para análise"]

Sugira um esquema de banco de dados que inclua:
1. Tabelas e suas colunas (com os tipos de dados apropriados)
2. Relacionamentos de chave primária e estrangeira
3. Quaisquer tabelas de junção necessárias para relacionamentos muitos-para-muitos
4. Índices sugeridos para desempenho
5. Considerações sobre escalabilidade

Além disso, explique a lógica por trás de suas escolhas de design.
```

### **25. 🔄 Refinamento de Esquema de Banco**

**Para que serve:** Aprimorar e normalizar estrutura de banco existente

```jsx
Considerando este esquema inicial:
[Cole seu esquema aqui]

Analise-o considerando o seguinte:
1. Normalização: O esquema está corretamente normalizado? Caso contrário, sugira melhorias.
2. Desnormalização: Há casos em que a desnormalização pode melhorar o desempenho?
3. Estratégia de indexação: Sugira índices adicionais que possam melhorar o desempenho da consulta.
4. Escalabilidade: Como este esquema lidará com o crescimento? Há algum gargalo em potencial?
5. Integridade dos dados: Há alguma restrição ou gatilho que devemos considerar para garantir a consistência dos dados?

Para cada sugestão, explique os prós e os contras.
```

---

## ⚡ **OTIMIZAÇÃO DE CONSULTAS**

### **26. ⚡ Otimização de Consultas SQL**

**Para que serve:** Melhorar performance de consultas complexas

> **⚠️ Observação Vital:** Sempre teste otimizações em ambiente semelhante à produção!

```jsx
Preciso otimizar a seguinte consulta SQL:
[Cole sua consulta aqui]

A consulta está demorando muito para ser executada em conjuntos de dados grandes. Por favor:
1. Analise a consulta e identifique possíveis problemas de desempenho.
2. Sugira otimizações, que podem incluir:
   - Reescrever a consulta
   - Adicionar ou modificar índices
   - Sugestões de alterações de esquema, se necessário
3. Explique o raciocínio por trás de cada otimização.
4. Se possível, forneça uma estimativa da melhoria de desempenho que podemos esperar.

Contexto adicional:
- Sistema de banco de dados: [ex.: PostgreSQL, MySQL]
- Tamanhos aproximados das tabelas: [ex.: a tabela "Usuários" tem 1 milhão de linhas]
- Quaisquer restrições de hardware relevantes.
```

### **27. 🔍 Estratégia de Indexação**

**Para que serve:** Otimizar índices para melhor performance

```jsx
Dada a seguinte estrutura de tabela e consultas comuns:
[Colar estrutura de tabela e consultas de exemplo]

Sugira uma estratégia de indexação ideal. Considere:
1. Quais colunas devem ser indexadas?
2. Devemos usar índices de coluna única ou de múltiplas colunas?
3. Há algum caso em que um índice de cobertura seria benéfico?
4. Como esses índices podem afetar o desempenho da gravação?
```

---

## 🔄 **MIGRAÇÃO E MANUTENÇÃO**

### **28. 🔄 Planejamento de Migração de Dados**

**Para que serve:** Migrar dados entre esquemas diferentes com segurança

```jsx
Preciso migrar dados de um esquema antigo para um novo:

Esquema antigo:
[Colar esquema antigo]

Novo esquema:
[Colar novo esquema]

Por favor, ajude-me a criar um plano de migração:
1. Identifique as etapas necessárias para transformar os dados
2. Sugira quaisquer tabelas ou visualizações intermediárias que possam ser úteis
3. Considere a integridade dos dados e como lidar com potenciais conflitos
4. Proponha uma estratégia para verificar o sucesso da migração
```

### **29. 🐛 Solução de Problemas de Performance**

**Para que serve:** Diagnosticar e resolver gargalos de consulta

```jsx
A consulta a seguir está apresentando baixo desempenho:
[Colar consulta problemática]

Plano de execução:
[Colar plano de execução, se disponível]

Analise esta consulta e sugira melhorias:
1. Identifique quaisquer partes subótimas da consulta ou do plano de execução
2. Sugira maneiras alternativas de escrever a consulta
3. Há algum índice ausente que possa ajudar?
4. A desnormalização de qualquer parte do esquema melhoraria o desempenho desta consulta?
```

### **30. 🚀 Ajuste Geral de Performance do BD**

**Para que serve:** Otimização completa do banco de dados

```jsx
Estou procurando melhorar o desempenho geral do meu banco de dados. Aqui está uma visão geral:
- Sistema de banco de dados: [ex.: PostgreSQL 13]
- Tamanho atual: [ex.: 500 GB]
- Tabelas principais e seus tamanhos: [Listar as tabelas principais]
- Padrões comuns de consulta: [Descrever consultas típicas]
- Pontos problemáticos atuais: [ex.: junções lentas em tabelas grandes, baixo desempenho de gravação durante horários de pico]

Forneça um plano abrangente de ajuste de desempenho, incluindo:
1. Parâmetros de configuração que podem precisar de ajuste
2. Revisão da estratégia de indexação
3. Técnicas de otimização de consulta
4. Possíveis otimizações de esquema
5. Estratégias de cache
6. Quaisquer outras sugestões relevantes para melhorar o desempenho

Para cada sugestão, explique o impacto esperado e quaisquer possíveis compensações.
```

---

## 🎯 **Fluxo Recomendado**

1. **Design inicial** → Use prompt #24
2. **Refinamento** → Use prompt #25
3. **Implementação** → Crie as tabelas
4. **Otimização** → Use prompts #26-27
5. **Monitoramento** → Use prompts #29-30
6. **Migração** → Use prompt #28 quando necessário

---

## ⚠️ **Melhores Práticas**

### **✅ Sempre Faça:**

- ✅ Teste em ambiente similar à produção
- ✅ Faça backup antes de migrações
- ✅ Monitore performance após mudanças
- ✅ Documente decisões de design

### **❌ Evite:**

- ❌ Otimizações prematuras
- ❌ Índices desnecessários
- ❌ Migrações sem plano de rollback
- ❌ Mudanças em produção sem teste

---

## 🔗 **Links Relacionados**

- **[01 - Planejamento](../01-planejamento/)** - Para design inicial
- **[06 - Segurança & Performance](../06-seguranca-performance/)** - Para segurança de dados
- **[05 - Testes & QA](../05-testes-qa/)** - Para testes de dados

---

> 💡 **Dica:** Comece sempre com um esquema bem normalizado, depois otimize conforme necessário!
