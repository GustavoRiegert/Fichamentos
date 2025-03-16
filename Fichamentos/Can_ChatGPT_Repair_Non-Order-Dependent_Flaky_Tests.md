# Can ChatGPT Repair Non-Order-Dependent Flaky Tests?

Yang Chen and Reyhaneh Jabbarvand. 2024. Can ChatGPT Repair Non-Order-Dependent Flaky Tests? In Proceedings of the 1st International Workshop on Flaky Tests (FTW '24). Association for Computing Machinery, New York, NY, USA, 22–29. https://doi.org/10.1145/3643656.3643900

## 1. Fichamento de Conteúdo

O artigo investiga a capacidade do ChatGPT na reparação de testes instáveis (flaky tests) que não dependem da ordem de execução (Non-Order-Dependent, NOD). Testes instáveis podem prejudicar a qualidade do software ao produzir resultados inconsistentes. A pesquisa utiliza um conjunto de 118 testes extraídos do dataset IDoFT para avaliar a eficácia do ChatGPT na correção desses testes. O estudo segue uma abordagem estruturada através da ferramenta NODoctor, que inclui inspeção, geração de prompts, tentativa de reparação e validação. Os resultados indicam que ChatGPT obteve sucesso na geração de patches plausíveis para apenas 8 testes, dos quais apenas 2 foram corretos. As principais dificuldades do modelo estão relacionadas à incapacidade de identificar corretamente as causas-raiz dos problemas e a geração de soluções que alteram a lógica original dos testes. O estudo destaca a necessidade de avanços na localização e correção automática de testes instáveis.

## 2. Fichamento Bibliográfico

- _Flaky Tests_: Testes que podem passar ou falhar de forma não determinística na mesma versão do código, prejudicando a confiança na regressão de software.
- _Non-Order-Dependent_ (NOD) Tests: Testes instáveis cuja falha não está relacionada à ordem de execução, mas a fatores como concorrência, dependências de plataforma e condições de tempo de execução.
- NODoctor: Ferramenta criada para testar a eficácia do ChatGPT na correção de testes NOD, composta por quatro etapas: inspeção, geração de prompts, reparação e validação.
- Patches Falsos Positivos: Modificações que fazem o teste passar, mas não corrigem o problema subjacente.

## 3. Fichamento de Citações

- "_Flaky tests can non-deterministically pass or fail when running on the same code version._"
- "_Our comprehensive study on 118 from the IDoFT dataset shows that ChatGPT is ineffective in repairing NOD test flakiness._"
- "_Developers waste their time pinpointing a bug that does not exist due to flaky tests._"
- "_Our findings offer valuable insights for future research directions in NOD test flakiness repair._"
- "_To the best of our knowledge, we are the first to explore using LLM (GPT-4) for repairing NOD test flakiness._"

