<h3 align="center">Calcule Aqui</h3>

Em meu dia a dia na área de CX notei que existia um gap quanto à análise preditiva referente aos resultados do Reclame Aqui.
Cada avaliação é composta por 3 perguntas independentes, o montante é calculado de acordo com uma fórmula, resultando no indicador denominado AR que deve passar por algumas regras para ser validado como selo.
Apesar de particularmente considerar um cálculo justo, por vezes também torna-se um cálculo confuso, o que dificulta a análise descritiva e mais ainda a análise preditiva.
Segue o link com a explicação mais detalhada: https://www.reclameaqui.com.br/como-funciona/reputacao/

Pensando nisso desenvolvi um web app em linguagem Python(framework Streamlit), que informa ao usuário quais são as condições para que sua empresa eleve o selo, ou caia de selo.
Existem dois modos de uso:
- Na primeira opção o app realiza um web scraping no site do RA, de acordo com os parâmetros informados pelo usuário(nome da empresa e aba desejada).
- Já na segunda opção, é necessário que o usuário informe os dados para que o cálculo seja realizado. Essa opção é válida quando o usuário deseja analisar um período específico, ou analisar a performance de um consultor.

Segue abaixo o link:
https://calculeaqui.streamlit.app/

Obrigado!
