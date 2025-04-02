# Can ChatGPT Repair Non-Order-Dependent Flaky Tests?

Yang Chen and Reyhaneh Jabbarvand. 2024. Can ChatGPT Repair Non-Order-Dependent Flaky Tests? In Proceedings of the 1st International Workshop on Flaky Tests (FTW '24). Association for Computing Machinery, New York, NY, USA, 22–29. https://doi.org/10.1145/3643656.3643900

## 1. Fichamento de Conteúdo

Este artigo examina a capacidade do ChatGPT de reparar testes instáveis (_flaky tests_) que não dependem da ordem de execução (_Non-Order-Dependent_, NOD). Esses testes ​​podem produzir resultados inconsistentes, comprometendo a qualidade do software. O artigo em questão utiliza um conjunto de 118 testes extraídos da base de dados _International Dataset of Flaky Tests_ (IDoFT) para avaliar a eficácia do ChatGPT na correção desses testes. O estudo segue uma abordagem estruturada por meio da técnica proposta _NODoctor_, que é criada para inspeção, geração de _prompts_, tentativa de reparação e validação dos NOD testes. Os resultados mostram que o ChatGPT gerou _patches_ razoáveis ​​com sucesso em apenas 8 testes, dos quais apenas 2 estavam corretos. As principais dificuldades deste modelo estão relacionadas à incapacidade de identificar corretamente a causa raiz do problema e gerar soluções que alterem a lógica original do teste. Este estudo destaca a necessidade de avanços no posicionamento e correção de testes instáveis automatizados.
## 2. Fichamento Bibliográfico

- _Regression testing_ (testes de regressão) são testes determinísticos que visam garantir que novas mudanças não impactaram no funcionamento do código (página 1). 
- _Flaky tests_ (testes instáveis) são testes que podem passar ou falhar de forma não determinística na mesma configuração, ambiente, sistema operacional e código (página 1).
- _Non-Order-Dependent Tests_ é uma subcatecoria de _flaky tests_ eles podem ser instáveis ​​devido à simultaneidade, tempo limite, dependência de plataforma, dependência de fuso horário, etc (página 4).
- _NODoctor_ é uma técnica proposta para testar a eficácia do ChatGPT na correção de testes NOD, composta por quatro etapas: inspeção, geração de _prompts_, reparação e validação (página 1 e página 2).
- _False positive patches_ (Patches Falsos Positivos) são modificações que fazem o teste passar, mas não corrigem o problema latente (página 4).

## 3. Fichamento de Citações

- "_We observe that GPT-4 is unable to repair NOD test flakiness, and performed a deep analysis of the cases where GPT-4 were or were not successful in repairing them._"
- "_Flaky tests can non-deterministically pass or fail when running on the same code version._"
- "_However, when test failures are, in fact, due to test flakiness, not a bug in the code, developers waste their time pinpointing a bug that does not exist [21]._"
- "_The first step for repairing NOD tests is to pinpoint the root cause in the test implementation._"
- "_This flakiness can only be detected through manual inspection of the local file systems and understanding that the file name should be corrected (Line 5), which is hard and time-consuming._"

