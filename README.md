# lab-azure-language-studio
# Azure Sentiment Analysis

Este projeto tem como objetivo demonstrar a utilização do Azure Cognitive Services para realizar análise de sentimentos em textos. O Azure Text Analytics é uma ferramenta poderosa que permite extrair insights de textos, como sentimentos, frases-chave e entidades.

## Passos para Execução

1. **Criação do Repositório no GitHub**
   - Criou-se um novo repositório no GitHub.
   

2. **Estrutura do Projeto**
   - Criu-se uma pasta chamada `inputs` no diretório raiz do projeto.
   - Dentro da pasta `inputs`, criou-se o arquivo de texto  `sentences.txt` contendo algumas sentenças para análise.


3. **Configuração do Azure**
   - No portal do Azure e criou-se um recurso de `Language`.
   - Obteu-se a chave de API e o endpoint necessário para autenticar as requisições.

4. **Análise de Sentimentos**
   - Utilize o SDK do Azure ou faça requisições HTTP diretamente para o endpoint do Text Analytics.
   - Processe o arquivo `sentences.txt` e envie cada sentença para análise.
   - Armazene os resultados em um arquivo JSON ou exiba-os no console.

5. **Resultados e Insights**
   - Insights sobre o sentimento de cada sentença (positivo, negativo ou neutro):
     ```json
     [
       {
         "text": "Eu adorei o atendimento no restaurante, foi incrível!",
         "sentiment": "positive",
         "confidenceScores": {
           "positive": 0.99,
           "neutral": 0.01,
           "negative": 0.00
         }
       },
       {
         "text": "O produto chegou quebrado e o suporte foi péssimo.",
         "sentiment": "negative",
         "confidenceScores": {
           "positive": 0.02,
           "neutral": 0.05,
           "negative": 0.93
         }
       }
     ]
     ```

## Prints do Processo

![Criação do Repositório](prints/repo_creation.png)
![Configuração do Azure](prints/azure_setup.png)
![Resultados da Análise](prints/analysis_results.png)

## Possibilidades e Aprendizados

- **Automatização de Análise de Feedback**: Este projeto pode ser escalado para analisar feedbacks de clientes em larga escala, ajudando empresas a identificar pontos de melhoria.
- **Integração com Chatbots**: A análise de sentimentos pode ser integrada a chatbots para melhorar a interação com os usuários, detectando emoções e ajustando respostas conforme necessário.
- **Monitoramento de Redes Sociais**: Empresas podem utilizar essa ferramenta para monitorar o sentimento em relação à sua marca nas redes sociais.



---
