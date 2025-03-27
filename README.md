# Better-Comments-Settings
Minhas configuracoes da extensao do Better Comments do vscode


### 🛠️ **Correção de Erros e Depuração**
- **`# BUG:`** Indica a presença de um erro conhecido no código.  
  ```python
  # BUG: O cálculo do desconto está errado para valores negativos.
  ```
  🔹 **Usado para marcar partes do código que precisam de correção urgente.**  

- **`# FIXME:`** Algo que precisa ser corrigido, mas ainda não foi feito.  
  ```python
  # FIXME: Esta função não verifica entradas inválidas.
  ```
  🔹 **Sinaliza algo que está errado e precisa de uma solução.**  

- **`# HACK:`** Solução improvisada ou temporária que pode não ser ideal.  
  ```python
  # HACK: Forçando um delay para evitar um bug de sincronização.
  ```
  🔹 **Geralmente indica código que pode ser substituído por algo melhor no futuro.**  

- **`# DEBUG:`** Usado para marcações de depuração.  
  ```python
  # DEBUG: Verificar se o valor da variável está correto.
  print(valor)
  ```
  🔹 **Ajuda a rastrear erros e entender o comportamento do código.**  

- **`# TRACE:`** Para registrar pontos críticos no fluxo de execução.  
  ```python
  # TRACE: Esta função é chamada toda vez que o botão é pressionado.
  ```
  🔹 **Geralmente usado para monitorar fluxos complexos de código.**  

---

### 🎯 **Melhoria e Organização do Código**
- **`# TODO:`** Algo que ainda precisa ser feito.  
  ```python
  # TODO: Implementar autenticação de usuário.
  ```
  🔹 **Lista tarefas pendentes no código.**  

- **`# OPTIMIZE:`** Código que pode ser melhorado para um desempenho superior.  
  ```python
  # OPTIMIZE: Melhorar o tempo de execução desta busca.
  ```
  🔹 **Indica partes do código que podem ser mais eficientes.**  

- **`# REFACTOR:`** Código que precisa ser reestruturado para melhor organização.  
  ```python
  # REFACTOR: Separar esta lógica em uma função auxiliar.
  ```
  🔹 **Usado quando o código funciona, mas pode ser escrito de maneira melhor.**  

- **`# CLEANUP:`** Código desnecessário que precisa ser removido.  
  ```python
  # CLEANUP: Remover esta variável temporária não utilizada.
  ```
  🔹 **Ajuda a manter o código limpo e organizado.**  

- **`# DEPRECATED:`** Código que não deve mais ser usado e pode ser removido no futuro.  
  ```python
  # DEPRECATED: Este método será substituído na próxima versão.
  ```
  🔹 **Útil para alertar sobre funcionalidades antigas.**  

- **`# LEGACY:`** Código antigo que ainda é usado, mas pode precisar de revisão.  
  ```python
  # LEGACY: Mantendo esta função para compatibilidade com versões antigas.
  ```
  🔹 **Ajuda a identificar código que pode precisar ser modernizado.**  

---

### 🚀 **Questões de Segurança e Performance**
- **`# SECURITY:`** Código com implicações de segurança.  
  ```python
  # SECURITY: Sanitizar entrada do usuário para evitar injeção SQL.
  ```
  🔹 **Garante que vulnerabilidades sejam identificadas e corrigidas.**  

- **`# PERFORMANCE:`** Código que pode ser otimizado para melhor desempenho.  
  ```python
  # PERFORMANCE: Reduzir chamadas de banco de dados desnecessárias.
  ```
  🔹 **Foca em tornar o código mais rápido e eficiente.**  

- **`# SCALABILITY:`** Código que pode apresentar problemas com aumento da carga.  
  ```python
  # SCALABILITY: Este método pode não funcionar bem com milhões de registros.
  ```
  🔹 **Ajuda a planejar sistemas que precisam lidar com crescimento.**  

---

### 🔗 **Dependências e Compatibilidade**
- **`# COMPATIBILITY:`** Questões de compatibilidade entre versões ou ambientes.  
  ```python
  # COMPATIBILITY: Verificar se esta API funciona no Python 3.8.
  ```
  🔹 **Garante que o código funcione corretamente em diferentes versões.**  

- **`# DEPENDENCY:`** Indica uma dependência importante do código.  
  ```python
  # DEPENDENCY: Requer a biblioteca requests para fazer chamadas HTTP.
  ```
  🔹 **Ajuda a lembrar que bibliotecas externas são necessárias.**  

---

### 💡 **Sugestões e Dúvidas**
- **`# NOTE:`** Informação importante sobre o código.  
  ```python
  # NOTE: Esta função usa um algoritmo recursivo.
  ```
  🔹 **Explica algo relevante para facilitar a compreensão.**  

- **`# WARNING:`** Aviso sobre possíveis problemas.  
  ```python
  # WARNING: Este método pode gerar exceções se a entrada for inválida.
  ```
  🔹 **Ajuda a alertar sobre riscos no código.**  

- **`# QUESTION:`** Dúvida ou ponto que precisa ser revisado.  
  ```python
  # QUESTION: Será que esta abordagem é a mais eficiente?
  ```
  🔹 **Levanta questões sobre o funcionamento do código.**  

- **`# IDEA:`** Sugestão para melhoria futura.  
  ```python
  # IDEA: Criar uma versão assíncrona desta função.
  ```
  🔹 **Ajuda a manter um registro de possíveis inovações.**  

- **`# REVIEW:`** Código que precisa ser revisado antes de ser considerado final.  
  ```python
  # REVIEW: Conferir se os cálculos estão corretos.
  ```
  🔹 **Indica que um trecho do código precisa ser analisado novamente.**  

- **`# WTF:`** Algo estranho ou inesperado no código.  
  ```python
  # WTF: Esta variável muda de valor sem explicação aparente.
  ```
  🔹 **Usado para destacar trechos confusos ou suspeitos.**  
