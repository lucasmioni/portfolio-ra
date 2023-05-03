<h3 align="center">Calcule Aqui</h3>

Em meu dia a dia na área de CX notei que existia um gap quanto à definição de metas referentes à performance da empresa na plataforma Reclame Aqui.
Cada avaliação é composta por 3 perguntas independentes, o montante é calculado de acordo com uma fórmula, resultando no indicador denominado AR que deve passar por algumas regras para ser validado como selo RA(classificação).  
Apesar de particularmente considerar um cálculo justo, por vezes também torna-se confuso, o que resulta na dificuldade em elaborar metas e estratégias para o time de atendimento. Ou seja, se determinada empresa está classificada com o selo 'bom', não se sabe qual a meta que deverá ser batida para alcançar o selo 'ótimo'.
Segue o link com a explicação mais detalhada: https://www.reclameaqui.com.br/como-funciona/reputacao/

Pensando nisso desenvolvi um algoritmo de modelagem preditiva, que com base nos dados do cenário cenário atual, informa ao usuário as condições para que sua empresa alcance a classificação superior e também não retroceda à classificação inferior.
Existem dois modos de uso:
- Na primeira opção o app realiza um web scraping no site do RA, coletando os dados referentes à classificação atual da empresa. Basta que o usuário informe o nome da empresa e aba desejada. Apesar de prática, essa opção se limita à análise das abas do site, que são períodos pré-determinados. 
- Já na segunda opção, é necessário que o usuário informe os dados referentes à classificação atual da empresa. Essa opção é válida quando o usuário deseja analisar um período específico, ou analisar a performance de um consultor. Os dados a serem inseridos no Calcule Aqui ficam disponíveis no Hugme, que é uma ferramenta do próprio Reclame Aqui. 

O desenvolvimento da ferramenta se deu na linguagem Python, e com o uso do framework Streamlit pude publicar a ferramenta como um web app. O app está em sua versão mais básica(MVP), por isso disponibilizei acima o documento product_backlog.txt para registrar a colaboração sobre sugestões de melhoria. 

**APLICATIVO:
https://calculeaqui.streamlit.app/**

Obrigado!
