### **Sugestão, Desenvolvimento e Avaliação dos Artefatos: Artefato 2 (Ux Arch v2)**

#### **1. Sugestão**

A proposta do **Ux Arch v2** consiste em um avanço em relação ao **Ux Arch v1**, com a utilização de tecnologias digitais, incluindo inteligência artificial (IA), para auxiliar arquitetos a projetar experiências arquitetônicas de forma intencional. A seguir, detalham-se os principais pontos relacionados à sua concepção.

##### **1.1. O que é o Artefato?**

- **Definição:**
  - Uma aplicação web que auxilia arquitetos e jovens projetistas a projetarem experiências arquitetônicas mais planejadas e intencionais.
  - Integra dados sensoriais, algoritmos de IA, e modelos de aprendizado de máquina para prever como usuários vivenciarão espaços arquitetônicos.
- **Base Conceitual:**
  - Influências teóricas incluem o modelo de emoções de Desmet (2007), a DSR de Simon (1996), e a abordagem pragmática para experiências de Hassenzahl (2010).
  - Arquitetos como Zumthor (2006) e Kotler (1974) são referências na definição de atmosferas e componentes espaciais.

##### **1.2. Quem está Envolvido?**

- **Stakeholders Diretos:**
  - Arquitetos e estudantes de arquitetura.
  - Usuários finais do espaço, cujas percepções influenciam os algoritmos de IA.
- **Desenvolvedores da Solução:**
  - Equipe interdisciplinar de arquitetos, cientistas de dados e programadores.
  - Papel do autor da tese como líder no desenvolvimento do sistema.
- **Colaboradores Indiretos:**
  - Instituições acadêmicas para validação de testes.
  - Usuários do setor público e privado interessados em ambientes planejados.

##### **1.3. Finalidade do Artefato**

- Criar um sistema que permita projetar experiências arquitetônicas de forma:
  - **Iterativa:** Testando e refinando continuamente as propostas.
  - **Intencional:** Baseando-se em dados para previsões precisas.
  - **Automatizada:** Reduzindo o tempo necessário para análise sensorial e espacial.
- **Expectativas:**
  - Melhorar a eficiência do processo de projeto.
  - Facilitar o uso de tecnologias de IA para prever emoções e comportamentos de usuários em relação a espaços projetados.

---

#### **2. Desenvolvimento**

O desenvolvimento do **Ux Arch v2** envolveu a construção de um sistema digital com várias camadas tecnológicas, divididas em etapas fundamentais.

##### **2.1. Arquitetura do Sistema**

- **Frontend (Cliente):**
  - Construído com React para interatividade e responsividade.
  - Interfaces amigáveis baseadas em princípios de UX Design (Norman, 2010).
  - Visualizações 3D para representar as experiências planejadas.
- **Backend (Servidor):**
  - Desenvolvido com Node.js para escalabilidade e suporte a operações intensivas de dados.
  - Comunicação por APIs RESTful para flexibilidade e modularidade.
- **Banco de Dados:**
  - MongoDB não-relacional para armazenar e recuperar rapidamente grandes volumes de dados de usuários, componentes espaciais e resultados de avaliações.
- **IA e Algoritmos:**
  - Redes neurais treinadas para analisar componentes arquitetônicos (ex.: luz, cor, textura) e prever experiências dos usuários.
  - Aprendizado supervisionado baseado em feedback de usuários reais.

---

##### **2.2. Telas e Funcionalidades do Sistema**

O **Ux Arch v2** oferece uma interface de usuário cuidadosamente projetada para guiar arquitetos e usuários finais através de várias etapas do processo de criação e avaliação de experiências arquitetônicas.

###### **2.2.1. Tela de Login e Cadastro**

- **Funcionalidades:**
  - Login seguro com autenticação baseada em e-mail e senha.
  - Cadastro intuitivo para arquitetos e usuários, com perfil diferenciado para cada tipo de usuário.
- **Destaque UX:**
  - Formulário simplificado e responsivo, reduzindo a fricção inicial.

###### **2.2.2. Tela de Cadastro de Referências**

- **Funcionalidades:**
  - Permite que o arquiteto insira fotos e informações sobre referências arquitetônicas, como nome, localização, e descrição.
  - Referências armazenadas para consulta futura.
- **Destaque UX:**
  - Interface limpa e organizada para facilitar o upload de imagens e entrada de dados.

###### **2.2.3. Tela de Definição de Componentes Arquitetônicas**

- **Funcionalidades:**

  - Arquitetos selecionam e configuram os componentes arquitetônicos de cada referência, como luz, cor, textura, material, forma e aberturas.
    - Forma Dominante
      Alternativas: Retangular, Curvilínea, Irregular.
    - Materiais
      Alternativas: Madeira, Concreto, Metal, Vidro, Alvenaria.
    - Texturas
      Alternativas: Lisa, Rugosa, Polida, Fosca.
    - Tons
      Alternativas: Claros, Médios, Escuros.
    - Cores Primárias
      Alternativas: Vermelho, Azul, Amarelo, Verde, Neutros (preto/branco).
    - Cores Secundárias e Terciárias
      Alternativas: Variações e combinações baseadas no círculo cromático.
    - Contraste Visual
      Alternativas: Alto, Médio, Baixo.
    - Intensidade da Luz
      Alternativas: Alta, Média, Baixa.
    - Aberturas
      Alternativas: Pequenas, Médias, Grandes.
    - Complexidade Volumétrica
      Alternativas: Simples, Moderada, Complexa.
    - Quantidade de Usuários
      Alternativas: Poucos, Moderados, Muitos.
    - Movimento
      Alternativas: Estático, Fluido, Dinâmico.

###### **2.2.4. Tela de Definição de Experiência**

- **Funcionalidades:**

  - Usuários avaliam a experiência proporcionada por cada referência arquitetônica com base em uma foto fornecida.
  - Avaliação feita usando **8 categorias de experiências arquitetônicas**, representadas por **emojis** para facilitar a compreensão e engajamento.
    - Tenso - Nervoso
      Representa estados emocionais intensos e negativos relacionados a estresse e ansiedade.
    - Estressado – Irritado
      Inclui emoções de desconforto e exaustão mental, geralmente associadas a estímulos excessivos.
    - Triste – Deprimido
      Abrange estados de melancolia e baixa energia emocional.
    - Letárgico – Fatigado
      Relaciona-se a sensações de cansaço e falta de vigor.
    - Calmo – Relaxado
      Reflete emoções neutras e tranquilas, indicando estabilidade emocional.
    - Sereno – Contente
      Representa estados de leve felicidade e satisfação, associados a experiências positivas e pacíficas.
    - Feliz – Alegre
      Inclui emoções de alegria e prazer intensos, associadas a experiências altamente satisfatórias.
    - Excitado - Eufórico
      Reflete estados emocionais intensamente positivos e estimulantes, caracterizados por energia elevada e entusiasmo
    - Usuários selecionam a categoria apropriada e classificam a intensidade da experiência em uma escala de 1 a 5.

- **Destaque UX:**
  - Uso de emojis torna o processo visual e acessível, promovendo interação amigável.

###### **2.2.5. Tela de Simulação de Novos Projetos**

- **Funcionalidades:**
  - Arquitetos ajustam componentes arquitetônicos de novos projetos (ex.: alterar iluminação ou textura) e observam, em tempo real, a predição da IA sobre a experiência resultante.
  - Predições baseadas nos dados de treinamento anteriores, incorporando feedback de experiências reais.
  - A predição é feita com base em uma das 8 categorias de experiência arquitetônica disponíveis (como Sereno - Contente ou Excitado - Eufórico), permitindo ao arquiteto visualizar como os usuários provavelmente perceberão o espaço projetado.
  - As predições utilizam os dados de treinamento anteriores, incorporando feedback de experiências reais e ajustando os resultados para maximizar a precisão e relevância.

---

##### **2.3. Ciclo Iterativo de Feedback**

- **Coleta de Dados:**
  - Informações sobre experiências anteriores em espaços arquitetônicos semelhantes.
  - Dados sensoriais (visuais, auditivos, táteis) integrados por sensores ou descrições arquitetônicas.
- **Treinamento de IA:**
  - Processamento contínuo para aprimorar previsões.
  - Utilização de modelos como o Circumplexo de Russell (1980) para avaliar emoções esperadas.
- **Validação:**
  - Comparação das previsões de IA com as percepções relatadas por usuários.
  - Iterações para ajustar pesos e parâmetros no algoritmo.

##### **2.4. Funcionalidades do Sistema**

- **Simulações de Experiências:**
  - Visualizações em realidade aumentada e virtual para testar atmosferas antes da construção.
- **Painel de Controle do Arquiteto:**
  - Opções para ajustar variáveis como cor, luz, materiais, e ver previsões de experiência em tempo real.
- **Sugestões Automáticas:**
  - IA oferece recomendações com base em análises anteriores.
- **Avaliação de Cenários:**
  - Permite comparar diferentes alternativas de projeto, classificando-as segundo intensidade e cardinalidade de emoções.

---

#### **3. Avaliação**

##### **3.1. Metodologia de Avaliação**

- **Validação Interna:**
  - Teste do funcionamento do sistema em prever experiências alinhadas aos objetivos do projeto.
  - Aplicação do modelo linear simplificado do Circumplexo de Russell.
- **Validação Externa:**
  - Participação de estudantes e profissionais de arquitetura para avaliar a interface e resultados do sistema.
  - Usuários finais verificaram se as previsões correspondem às suas percepções.

##### **3.2. Avaliação Final**

### **Pontuação Final**

- **Correlação:** Sim (Peso 5)
- **Causalidade:** Talvez (Peso 3)
- **Avanço Percebido:** Sim (Peso 5)
- **Média Calculada:** 4,33
- **Classificação:** Satisfatório
