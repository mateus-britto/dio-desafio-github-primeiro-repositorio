

# Requisição HTTP

URL: https://pokeapi.co/docs/v2#pokemon?type=grass&name=1
    ${IP}${path = caminho de indentificação do recurso}

IP: https://pokeapi.co
    HTTP://127.0.0.1:3000
    
//Ambos os formatos acima representam a mesma coisa.

## Request Method: GET | POST | PUT| DELETE etc...
    Métodos dizem o que queremos fazer sobre o recurso*

## Request Headers: Configuração.
 Ex: Idiomas aceitos em ordem de prioridade.
 en-US
,en;q=0.9 // O número apos o '=' representa a prioridade.
,pt-BR;q=0.8
,pt;q=0.7
,de;q=0.6

Response Headers: Configuração

HEADERS: São uma espécie de configuração da nossa requisição*
- **Accept:** Configuração da requisição.
- **Response:** Configuração da resposta.


**GET:** Buscar recurso.
- **Query string:** Uma string de consulta é parte de um localizador uniforme de recursos que atribui valores a parâmetros especificados.

    ex: *?type=grass&name=1 (dentro da URL, do ponto de interrogação para frente.)*
- São compostas por chaves e valores: **type = grass | name = i**


### POST: Inserir algo.

### PUT: Atualizar algo.

### DELETE: Apagar algo.

### **Uma requisição HTTP é composta por:**

- URL
- REQUEST METHOD
- REQUEST HEADERS
- RESPONSE HEADERS
- REQUEST BODY

### **E a resposta do SERVIDOR:**

## STATUS CODE:
É um número que define o que aconteceu com a requisição.

200-299 = SUCESSO

300-399 = REDIRECT

400-499 = ERRO CLIENTE

500-599 = ERRO INTERNO SO SERVIDOR

RESPONSE HEADERS

RESPONSE BODY
