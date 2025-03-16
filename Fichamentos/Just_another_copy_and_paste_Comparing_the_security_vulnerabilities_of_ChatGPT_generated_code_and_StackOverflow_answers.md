# Just another copy and paste? Comparing the security vulnerabilities of ChatGPT generated code and StackOverflow answers

S. Hamer, M. d’Amorim and L. Williams, "Just another copy and paste? Comparing the security vulnerabilities of ChatGPT generated code and StackOverflow answers," 2024 IEEE Security and Privacy Workshops (SPW), San Francisco, CA, USA, 2024, pp. 87-94, doi: 10.1109/SPW63631.2024.00014.


## 1. Fichamento de Conteúdo

O artigo investiga a segurança do código gerado pelo ChatGPT em comparação com trechos retirados do StackOverflow (SO). Para isso, os autores analisaram 108 trechos de código de cada plataforma, utilizando a ferramenta de análise estática CodeQL para identificar vulnerabilidades. Os resultados indicam que o código gerado pelo ChatGPT apresentou 248 vulnerabilidades, enquanto os trechos do SO continham 302, ou seja, o ChatGPT gerou aproximadamente 20% menos vulnerabilidades. Além disso, o estudo identificou que o ChatGPT gerou menos tipos distintos de vulnerabilidades (19 CWEs) em comparação com o SO (22 CWEs). No entanto, ambas as plataformas apresentaram 274 vulnerabilidades únicas, indicando que os desenvolvedores devem ter cautela ao copiar código de qualquer uma dessas fontes. O estudo conclui que, apesar de o ChatGPT apresentar menos vulnerabilidades, ele não elimina o risco de propagação de código inseguro, reforçando a necessidade de boas práticas de engenharia de software.

## 2. Fichamento Bibliográfico

- _CodeQL_: Ferramenta de análise estática usada para detectar vulnerabilidades nos códigos analisados do ChatGPT e do StackOverflow.
- _CWE (Common Weakness Enumeration)_: Uma taxonomia de vulnerabilidades de software usada para classificar os problemas de segurança identificados no estudo.
- _CWE-327 e CWE-328_: As vulnerabilidades mais comuns no estudo, relacionadas ao uso de algoritmos criptográficos fracos.
- _CWE-798 (Uso de credenciais hardcoded)_: Uma vulnerabilidade crítica encontrada mais frequentemente no ChatGPT do que no SO.
- _Diferença na sobreposição de vulnerabilidades_: Apenas 25% das vulnerabilidades identificadas estavam presentes em ambas as plataformas, evidenciando que cada fonte apresenta riscos distintos.

## 3. Fichamento de Citações

- "_ChatGPT-generated code contained 248 vulnerabilities compared to the 302 vulnerabilities found in SO snippets, producing 20% fewer vulnerabilities with a statistically significant difference._"
- "_Developers are under-educated on insecure code propagation from both platforms, as we found 274 unique vulnerabilities and 25 types of CWE._"
- "_Any code copied and pasted, created by AI or humans, cannot be trusted blindly, requiring good software engineering practices to reduce risk._"
- "_CWE-327: Use of a Broken or Risky Cryptographic Algorithm and CWE-328: Use of Weak Hash were the most common vulnerabilities found in both platforms._"
- "_The vulnerabilities found in the ChatGPT-generated code and SO overlapped only in 25% of the vulnerabilities._"
