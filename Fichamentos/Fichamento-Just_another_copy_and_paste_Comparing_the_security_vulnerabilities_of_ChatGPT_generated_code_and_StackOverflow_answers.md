# Just another copy and paste? Comparing the security vulnerabilities of ChatGPT generated code and StackOverflow answers

S. Hamer, M. d’Amorim and L. Williams, "Just another copy and paste? Comparing the security vulnerabilities of ChatGPT generated code and StackOverflow answers," 2024 IEEE Security and Privacy Workshops (SPW), San Francisco, CA, USA, 2024, pp. 87-94, doi: 10.1109/SPW63631.2024.00014.


## 1. Fichamento de Conteúdo

O artigo examina a segurança do código produzido pelo ChatGPT em relação a trechos extraídos do StackOverflow (SO). Para essa análise, os autores avaliaram 108 trechos de código de ambas as plataformas, utilizando a ferramenta de análise estática CodeQL para detectar vulnerabilidades. Os resultados revelaram que o código gerado pelo ChatGPT apresentou 248 vulnerabilidades, em comparação com 302 encontradas nos trechos do SO, o que significa que o ChatGPT gerou cerca de 20% menos vulnerabilidades. Além disso, o estudo destacou que o ChatGPT produziu um menor número de tipos distintos de vulnerabilidades 19 _Common Weakness Enumeration_ (CWEs) em comparação aos 22 CWEs do SO. Contudo, ambas as plataformas apresentaram um total de 274 vulnerabilidades únicas, o que sugere que os desenvolvedores devem ser cautelosos ao utilizar código de qualquer uma dessas fontes. A pesquisa conclui que, embora o ChatGPT exiba menos vulnerabilidades, isso não elimina o risco de disseminação de código inseguro, enfatizando a importância de seguir boas práticas na engenharia de software. 

## 2. Fichamento Bibliográfico

- CodeQL é uma ferramenta _opensource_ (código aberto) de análise estática usada para detectar vulnerabilidades no código (página 3).
- _Common Weakness Enumeration (CWE)_: é um sistema para categorizar falhas de segurança de software, focando em defeitos de implementação que podem levar a vulnerabilidades (página 2).
- _CWE-327_: captura quando os algoritmos criptográficos usados ​​são inseguros (página 4).
- _CWE-798_: A vulnerabilidade descreve quando credenciais como senhas ou chaves criptográficas são codificadas no código e podem ser aproveitadas por invasores para ignorar a autenticação (página 4).

## 3. Fichamento de Citações

- "_We found 248 vulnerabilities across all ChatGPT code snippets. Meanwhile, we found 302 vulnerabilities in the SO code snippets._" 
- "_Still, developers are under-educated on insecure code propagation from both platforms, as both contain vulnerable code that can propagate to developers_"
- "_Any code copied and pasted, created by AI or humans, cannot be trusted blindly, requiring good software engineering practices to reduce risk_" 
- "_[...]CWE-328 is similar as it covers when the hash algorithm does not meet security expectations._" 
- "_Additionally, the vulnerabilities found in the ChatGPT-generated code and SO overlapped only in 25% of the vulnerabilities._"
