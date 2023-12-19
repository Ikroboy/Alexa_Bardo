# Modelo de Skill Alexa para integrar o Bard
Use o Bard na Alexa 😊  

# Instruções

- Crie uma Skill Alexa-hosted (Python) na Alexa: https://developer.amazon.com/alexa/console/ask/create-new-skill
  - Name your Skill: Escolha um nome de sua preferência (Ex: ChatGPT)
  - Choose a primary locale: Portuguese (BR)  
  - Em tipo de experiência selecione: Other > Custom > Alexa-hosted (Python)  
  - Hosting region: Pode deixar o padrão (US East (N. Virginia))
  - Templates: Clique em Import Skill
  - Insira o endereço: https://github.com/Ikroboy/Alexa_Bardo.git

- Vá na aba "Code"
- Insira sua chave no código: lambda > lambda_function.py:
  ```python
  openai.api_key = "substitua-por-sua-api-key-da-openai"
  ```
- Salve as alterações

- Faça Build do Modelo e Deploy do Código.

- Seja feliz!
