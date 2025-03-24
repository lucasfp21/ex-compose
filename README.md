# Docker Compose

Docker Compose é gerenciado por um arquivo YAML (geralmente **compose.yaml**).  
O arquivo é **declarativo**, então basicamente temos parâmetros declarados e valores atribuídos a esses parâmetros.

## Primeiro Parâmetro: `version`
- Este parâmetro define a versão do arquivo.  
  **Observação:** Ele **não é mais usado** a partir da versão 2 do Compose.  
  **Exemplo:**
  ```yaml
  version: "3.8"