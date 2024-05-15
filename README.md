# AutomationTesting

# Testes Automatizados na API gorest.co.in/public/v2/todos

Este repositório contém scripts de testes automatizados para validar a API gorest.co.in/public/v2/todos utilizando o Postman.

## Como Executar os Testes

Para executar os testes automatizados, siga estas etapas:

1. **Instale o Postman:**
   Certifique-se de ter o Postman instalado em seu sistema. Você pode baixá-lo em [getpostman.com](https://www.getpostman.com/downloads/).

2. **Clone o Repositório:**
   Clone este repositório para o seu ambiente local usando o seguinte comando: git clone https://github.com/seu-nome-de-usuario/nome-do-repositorio.git

3. **Abra o Postman:**
Abra o Postman em seu sistema.

4. **Importe a Coleção de Testes:**
No Postman, clique em "Import" (Importar) e selecione o arquivo JSON da coleção de testes fornecido neste repositório.

5. **Execute os Testes:**
Selecione a coleção de testes importada e clique em "Run" (Executar) para executar todos os testes automatizados.

## Detalhes dos Testes

### 1. Validação de Schema
- Este teste verifica se a resposta da API está de acordo com o schema JSON esperado.

### 2. Validação de Status "completed"
- Este teste verifica se todos os resultados têm o status "completed" na resposta da API.

### 3. Interpretação e Validação do Valor "due_on"
- Este teste interpreta e valida o valor "due_on" em cada resultado, garantindo que seja uma data válida.

## Contribuições
Contribuições são bem-vindas! Se você encontrar algum problema ou tiver sugestões de melhorias, sinta-se à vontade para abrir uma issue ou enviar um pull request.

