# 🤖 Inteligência Artificial no Cotidiano

## 📑 Sumário
1. Contexto e Objetivos  
2. Curadoria de Fontes  
3. Engenharia de Prompts e Cicatrizes  
4. Miniguia de Estudo  
   - Resumos Estruturados  
   - Glossário  
   - Prompts Reutilizáveis  
5. Aplicabilidade Prática  
6. Conclusão Crítica  
7. Referências  

---

## 📂 Estrutura do Repositório
- 📘 README.md → Documento principal  
- 📂 sources/ → Fontes utilizadas (ex.: ia_basica.pdf, UNESCO guia)  
- 📂 prompts/ → Testes de engenharia de prompts  
- 📂 slides/ → Apresentação resumida  

---

## 📘 Contexto e Objetivos
Este caderno temático explora como a Inteligência Artificial (IA) já faz parte da nossa rotina, mesmo sem percebermos.  
**Objetivo:** compreender aplicações simples de IA em áreas como educação, segurança, serviços de streaming e e-commerce.  

---

## 📂 Curadoria de Fontes
- BRASIL ESCOLA. Inteligência artificial: o que é, como funciona. Disponível em: <https://brasilescola.uol.com.br/informatica/inteligencia-artificial.htm>. Acesso em: 24 jul. 2026.  
- ENGBLOG. Inteligência artificial no cotidiano: como é no dia a dia? Disponível em: <https://blog.engdb.com.br/inteligencia-artificial-no-dia-a-dia/#content>. Acesso em: 24 jul. 2026.  
- BRASIL. Ministério da Educação. Inteligência Artificial na Educação Básica. Brasília: MEC, 2025. Disponível em: <https://www.gov.br/mec/pt-br/escolas-conectadas/arquivos/ia-basica.pdf>. Acesso em: 24 jul. 2026.  
- UNESCO. Guia para a IA generativa na educação e na pesquisa. Paris: UNESCO, 2025. Disponível em: <https://unesdoc.unesco.org/ark:/48223/pf0000390241>. Acesso em: 24 jul. 2026.  
- STANFORD HAI. Relatório do Índice de IA de 2026. Stanford University, 2026. Disponível em: <https://hai.stanford.edu/ai-index/2026-ai-index-report>. Acesso em: 24 jul. 2026.  

---

## ⚙️ Engenharia de Prompts e "Cicatrizes"
Com o objetivo de compreender como a formulação de prompts influencia a qualidade das respostas geradas pelo NotebookLM, foram realizados dois testes utilizando exatamente o mesmo conjunto de perguntas. A única alteração realizada foi a inclusão de uma instrução prévia antes da segunda execução.

### Teste 1 – Perguntas sem instruções adicionais

No primeiro teste, as perguntas foram feitas diretamente ao NotebookLM, sem qualquer orientação sobre o formato das respostas.

#### Perguntas utilizadas

1. Quais são os principais tipos de Inteligência Artificial existentes hoje?
2. Como o Deep Learning funciona de forma similar aos neurônios?
3. Quais são os benefícios e riscos da IA no cotidiano?

#### Resultado observado

As respostas apresentaram elevado nível de detalhamento, trazendo explicações completas, classificações, exemplos e conceitos extraídos das fontes utilizadas no NotebookLM. Embora esse formato seja excelente para aprofundamento do estudo, os textos ficaram relativamente extensos para consultas rápidas.

---

### Teste 2 – Mesmo conjunto de perguntas com instrução prévia

Antes de repetir as mesmas perguntas, foi adicionada a seguinte instrução ao chat:

> **"A partir de agora responda às perguntas de forma curta, objetiva e resumida, preservando apenas as informações mais importantes."**

Após essa orientação, foram realizadas exatamente as mesmas perguntas do teste anterior.

#### Resultado observado

As respostas permaneceram coerentes com as fontes carregadas no NotebookLM, porém passaram a apresentar apenas os conceitos essenciais. O conteúdo foi sintetizado sem perda significativa das informações principais, tornando as respostas mais adequadas para revisão rápida do tema.

---

### Comparação dos Resultados

| Aspecto | Teste 1 | Teste 2 |
|----------|----------|----------|
| Perguntas utilizadas | Iguais | Iguais |
| Instrução prévia | Não | Sim |
| Nível de detalhamento | Alto | Resumido |
| Objetividade | Média | Alta |
| Tempo de leitura | Maior | Menor |
| Finalidade | Estudo aprofundado | Revisão rápida |

---

### Aprendizados Obtidos

O experimento demonstrou que não foi necessário modificar as perguntas para obter respostas diferentes. Apenas a inclusão de uma instrução orientando o formato desejado foi suficiente para alterar significativamente o nível de detalhamento das respostas.

Essa experiência evidenciou a importância da Engenharia de Prompts como ferramenta para adaptar a saída da Inteligência Artificial conforme o objetivo do usuário, seja para aprofundar um determinado assunto ou produzir resumos objetivos para revisão.

---

### Cicatrizes (Troubleshooting)

Durante os testes foi possível observar que:

- perguntas diretas tendem a produzir respostas bastante detalhadas;
- a ausência de orientações sobre formato faz com que o NotebookLM priorize explicações completas;
- pequenas alterações na instrução inicial influenciam diretamente a extensão, organização e objetividade das respostas;
- definir previamente o objetivo da resposta (estudo aprofundado ou revisão rápida) melhora significativamente a qualidade do resultado obtido.

Esses experimentos reforçaram que a elaboração de bons prompts é um processo iterativo, no qual pequenas mudanças na forma de solicitar uma informação podem produzir respostas mais adequadas às necessidades do usuário.

---

## 📖 Miniguia de Estudo

### Resumos Estruturados
- **Fundamentos e Funcionamento da IA:** A Inteligência Artificial busca simular a cognição humana através de métodos como o aprendizado de máquina e o aprendizado profundo, sendo classificada conforme sua capacidade de realizar tarefas específicas ou gerais.  
- **IA Generativa e Engenharia de Prompts:** A IA Generativa utiliza modelos de linguagem para produzir conteúdos originais a partir de comandos (prompts), embora exija supervisão humana constante devido à sua tendência de gerar informações imprecisas ou "alucinações".  
- **Aplicações no Cotidiano e Tendências:** A tecnologia já permeia o cotidiano em áreas como e-commerce, navegação e segurança, evoluindo para uma "fronteira irregular" onde modelos superam humanos em ciências complexas, mas ainda cometem erros em tarefas básicas.  
- **IA na Educação e Ética:** O uso da IA no ensino deve equilibrar o aprender com e sobre a tecnologia, fundamentando-se no letramento crítico e na proteção de direitos previstos por leis como a LGPD e o ECA Digital.

### Glossário
- **Alucinação:** Limitação de modelos de linguagem onde a IA gera informações imprecisas, fatos inventados ou erros de raciocínio que podem parecer convincentes.  
- **Aprendizado de Máquina (Machine Learning - ML):** Tipo de IA que utiliza algoritmos para permitir que os sistemas melhorem automaticamente seu desempenho a partir da análise de grandes volumes de dados.  
- **Deep Learning (Aprendizado Profundo):** Subcampo do aprendizado de máquina que utiliza grandes redes neurais artificiais com múltiplas camadas de processamento para emular o cérebro humano na identificação de padrões complexos em imagens e áudios.  
- **Descarregamento Cognitivo:** Fenômeno causado pela dependência excessiva de ferramentas de IA, onde o indivíduo deixa de exercer habilidades de pensamento crítico, criatividade e autonomia intelectual.  
- **ECA Digital (Lei 15.211/2025):** Legislação brasileira que dispõe sobre a proteção de crianças e adolescentes em ambientes digitais, exigindo níveis elevados de privacidade e segurança por padrão.  
- **EdGPT:** Modelo fundamental de IA generativa que é ajustado ou treinado com dados específicos para fins educacionais, visando apoiar professores e alunos de forma mais precisa e pedagógica.  
- **GPT (Transformador Generativo Pré-treinado):** Tipo específico de modelo de linguagem grande (LLM) treinado em quantidades massivas de dados para capturar as nuances da linguagem e gerar textos coerentes de acordo com o contexto.  
- **Inteligência Artificial (IA):** Campo da ciência da computação voltado ao desenvolvimento de sistemas e modelos computacionais que simulam operações cognitivas humanas para tomar decisões e realizar tarefas.  
- **IA Desplugada (AIED Unplugged):** Abordagem pedagógica que ensina conceitos fundamentais de IA por meio de atividades físicas, lúdicas e colaborativas que não exigem o uso de computadores ou internet.  
- **IA Generativa (IAGen):** Tecnologia que utiliza aprendizado de máquina para criar novos conteúdos (textos, imagens, códigos, áudios e vídeos) em resposta a comandos fornecidos pelo usuário.  
- **IA Preditiva:** Modelos que utilizam aprendizado de máquina para estimar ou antecipar comportamentos e resultados futuros com base em padrões extraídos de dados históricos.  
- **Letramento em IA:** Capacidade de compreender, utilizar e avaliar criticamente os sistemas de IA, reconhecendo seu funcionamento, limitações, riscos e impactos sociais e éticos.  
- **LGPD (Lei Geral de Proteção de Dados - Lei 13.709/2018):** Marco legal brasileiro que estabelece regras para o tratamento de dados pessoais, visando proteger os direitos fundamentais de liberdade e privacidade.  
- **LLM (Modelo de Linguagem Grande):** Tipo de IA generativa especializado em linguagem escrita, que estima a sequência de palavras mais provável a partir de um contexto, sem necessariamente "compreender" o mundo real.  
- **Parâmetros:** Variáveis numéricas (como os "pesos") dentro de um modelo de IA que podem ser ajustadas para aperfeiçoar seu desempenho e determinar como a entrada é processada.  
- **Processamento de Linguagem Natural (PLN):** Subcampo focado em algoritmos que permitem às máquinas compreender e simular a linguagem humana, permitindo a interação direta por voz ou texto.  
- **Prompt:** Comando ou estímulo escrito em linguagem natural que o usuário insere em uma interface de IA para obter uma resposta gerada automaticamente.  
- **Redes Neurais Artificiais (RNAs):** Tipo de aprendizado de máquina inspirado na estrutura e funcionamento do cérebro humano, especialmente nas conexões sinápticas entre neurônios.  
- **Tokens:** Unidades menores em que um estímulo (como uma frase) é dividido para ser processado por modelos como o GPT.  
- **Visão Computacional:** Capacidade de máquinas de visualizarem e interpretarem informações visuais (imagens e vídeos) para executar comandos, sendo fundamental para o reconhecimento facial.

### Prompts Reutilizáveis
Os prompts abaixo foram utilizados durante o desenvolvimento deste caderno temático e podem ser adaptados para estudos sobre Inteligência Artificial em diferentes contextos.

- **De que maneira a Inteligência Artificial já está presente no cotidiano, como em compras online, serviços de streaming e segurança residencial?**
- **Como o Brasil orienta o uso da Inteligência Artificial na educação, segundo os documentos oficiais apresentados?**
- **Quais são os principais desafios para a implementação de uma regulação ética da Inteligência Artificial?**

---

## 🎯 Aplicabilidade Prática
Este miniguia pode ser utilizado em diferentes contextos:  
- **Estudantes:** revisão rápida antes de provas ou trabalhos.  
- **Professores:** apoio em aulas sobre IA e tecnologia.  
- **Profissionais:** consulta rápida sobre conceitos e aplicações da IA.  
- **Pesquisadores:** base inicial para estudos mais aprofundados.  

---

## 📝 Conclusão Crítica
A Inteligência Artificial já está profundamente inserida no cotidiano, mas sua adoção exige cautela.  
- **Limitações:** modelos ainda cometem erros básicos e podem gerar informações imprecisas.  
- **Riscos:** descarregamento cognitivo e dependência excessiva da tecnologia.  
- **Necessidade:** regulação ética e políticas públicas que garantam segurança e privacidade.  
- **Perspectivas futuras:** IA generativa aplicada à educação, saúde e segurança, com potencial de transformar práticas sociais, mas sempre exigindo supervisão humana crítica.  

---

## 📚 Referências
*(já incluídas na seção de curadoria, em formato ABNT)*  

