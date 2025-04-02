# Investigating Code Generation Performance of ChatGPT with Crowdsourcing Social Data

Y. Feng, S. Vanam, M. Cherukupally, W. Zheng, M. Qiu and H. Chen, "Investigating Code Generation Performance of ChatGPT with Crowdsourcing Social Data," 2023 IEEE 47th Annual Computers, Software, and Applications Conference (COMPSAC), Torino, Italy, 2023, pp. 876-885, doi: 10.1109/COMPSAC57700.2023.00117.

## 1. Fichamento de Conteúdo

O artigo explora o desempenho do ChatGPT na criação de código, utilizando dados extraídos de plataformas de mídia social como Twitter e Reddit. Para isso, os autores desenvolveram um _framework_ de _crowdsourcing_ que combina análise de tópicos e modelos de aprendizado de máquina, com o intuito de descobrir padrões na forma como o ChatGPT gera o código. Entre dezembro de 2022 e janeiro de 2023, foram coletados 316 mil tweets e 3,2 mil postagens no Reddit, revelando que as linguagens mais frequentemente mencionadas são Python e JavaScript. A pesquisa revelou que o ChatGPT é utilizado para diversas finalidades, incluindo depuração, entrevistas técnicas e suporte acadêmico. No entanto, também surgiram preocupações entre os usuários, com um destaque para a emoção de "medo" associada ao seu uso. Além disso, os pesquisadores disponibilizaram um conjunto de dados público contendo _prompts_ e códigos gerados pelo ChatGPT e realizaram análises da qualidade do código utilizando a ferramenta Flake8. O estudo conclui que, apesar das notáveis habilidades do ChatGPT, existem desafios a serem enfrentados na sua adoção, incluindo questões éticas e limitações na produção de código de qualidade. 

## 2. Fichamento Bibliográfico

- _Crowdsourcing data-driven framework_ representa como coletar dados de
interesse, como analisar dados e como interpretar descobertas usando 3 fases: Expansão e seleção de palavras-chave, coleta de dados e análise de dados e reconhecimento de padrões (página 3).
- _Keyword Selection_ abordagem que visa que os dados sejam abrangentes e precisos, eliminando o risco de viés ou incompletude na seleção de palavras-chave de consulta (página 3).
- _latent Dirichlet allocation (LDA)_ é uma técnica de modelagem de tópicos para descobrir os tópicos centrais e suas distribuições em um conjunto de itens (página 4).
- Flake8 é um utilitário de linha de comando que verifica o código Python em relação ao estilo de codificação (PEP 8), erros de programação e construções complexas (página 7).

## 3. Fichamento de Citações

- "_ChatGPT has been used in more than 10 programming languages, with Python and JavaScript being the two most popular._"
- "_Fear is the dominant emotion associated with ChatGPT’s code generation, overshadowing emotions of happiness, anger, surprise, and sadness._"
- "_We have built a real-world programming dataset containing the ChatGPT prompt and the associated generated Python code._"
- "_Flake8 identifies the error codes for each file, along with the position and description of the error._"
- "_However, there have been instances where ChatGPT was instructed to compose a Python function for predicting someone’s seniority or assessing their competence as a scientist._"
