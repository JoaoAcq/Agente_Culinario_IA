# 🤖 Chef IA & Cia: Seu Assistente Culinário Multiagente Inteligente 🧑‍🍳💰🥗

**Projeto desenvolvido para o Concurso de Chatbots Criativos da Alura com a API do Google Gemini.**
*(Data de Conclusão: 17 de maio de 2025)*

Este projeto apresenta o "Chef IA & Cia", um assistente culinário inovador e interativo, construído em Python e integrado com a poderosa API do Google Gemini. Ele não é apenas um chatbot, mas um sistema multiagente projetado para oferecer uma experiência completa e divertida na cozinha, desde a inspiração para receitas até dicas de economia e bem-estar alimentar.

## 📖 Visão Geral

Cansado de não saber o que cozinhar com os ingredientes da geladeira? Quer economizar nas compras do supermercado? Ou talvez busca dicas para uma alimentação mais saudável de forma divertida? O "Chef IA & Cia" está aqui para ajudar! Com uma equipe de agentes especializados, este chatbot oferece uma solução completa e inteligente para o seu dia a dia na cozinha.

## ✨ Funcionalidades Principais

O "Chef IA & Cia" é composto por três agentes especialistas que trabalham individualmente ou em conjunto:

1.  **🧑‍🍳 Chef Criativo de Geladeira:**
    * Transforma os ingredientes que você tem em casa em receitas criativas e deliciosas.
    * Utiliza a busca do Google (integrada via Gemini) para se inspirar em tendências culinárias e sugestões atuais.
    * Formata a saída para facilitar a leitura e permitir que o usuário escolha uma receita para análise pelos outros agentes.

2.  **💰 Caçador de Ofertas:**
    * Ajuda a encontrar as melhores promoções para ingredientes específicos ou para os itens de uma receita sugerida pelo Chef.
    * Utiliza a busca do Google para informações de ofertas, considerando a data atual para relevância.
    * Pode receber contexto do Chef Criativo para buscar ofertas para uma receita específica.

3.  **🥗 Nutricionista Lúdico e Motivador de Hábitos:**
    * Fornece dicas de alimentação saudável, curiosidades sobre alimentos e sugestões para tornar as receitas mais nutritivas, tudo de forma leve e divertida (sem substituir um profissional de saúde).
    * Pode analisar uma receita específica (sugerida pelo Chef) para dar insights nutricionais gerais ou ideias de substituições saudáveis.
    * Propõe pequenos desafios para incentivar hábitos positivos.
    * Utiliza a busca do Google para embasar suas dicas com informações atuais.

**🤝 Interatividade entre Agentes:**
Uma das principais inovações é a capacidade dos agentes de interagirem e passarem contexto entre si. Por exemplo, após o Chef Criativo sugerir receitas, o usuário pode optar por:
* Enviar os ingredientes de uma receita escolhida para o **Caçador de Ofertas**.
* Enviar o texto de uma receita escolhida para o **Nutricionista Lúdico** para análise e dicas.

## 💡 Inovação e Criatividade (Destaques para o Concurso Alura)

* **Abordagem Multiagente:** Demonstra uma arquitetura mais complexa e uma divisão de responsabilidades que enriquece a interação do usuário.
* **Integração Inteligente com Gemini & Google Search:** As respostas dos agentes são potencializadas pela capacidade de geração de linguagem natural do Gemini e pelo acesso a informações em tempo real via Google Search, tornando o chatbot mais dinâmico e útil.
* **Fluxo de Usuário Contextual e Fluido:** A capacidade de um agente chamar outro com base na interação atual (ex: Chef -> Caçador ou Chef -> Nutricionista) cria uma experiência de usuário mais coesa e inteligente.
* **Personas Criativas e Engajadoras:** Cada agente possui uma personalidade distinta, tornando a interação mais memorável e divertida.
* **Foco em Utilidade Prática e Entretenimento:** O projeto visa resolver problemas cotidianos (o que cozinhar, como economizar, como ser mais saudável) de uma maneira lúdica, incentivando o aprendizado e a experimentação.

## 🚀 Tecnologias Utilizadas

* **Python**
* **API do Google Gemini** (para PLN, geração de texto e controle dos agentes)
* **Google Search** (integrado via funcionalidade de ferramentas do Gemini)
* **Google Colab** (como ambiente de desenvolvimento e execução do notebook `.ipynb`)

## 🔧 Como Executar

O projeto foi desenvolvido e é executado como um notebook Google Colab (`agenteCulinario.ipynb`).

1.  **Pré-requisitos:**
    * Uma conta Google.
    * Uma Chave de API do Google Gemini (Google AI Studio).

2.  **Configuração:**
    * Abra o notebook `agenteCulinario.ipynb` no Google Colab.
    * No menu à esquerda do Colab, clique no ícone de chave (🔑) chamado "Segredos".
    * Clique em "Adicionar um novo segredo".
        * Nome: `GOOGLE_API_KEY`
        * Valor: Cole a sua Chave de API do Google Gemini.
    * Ative a chave "Acesso ao notebook".

3.  **Execução:**
    * Execute todas as células do notebook em ordem, de cima para baixo.
    * A última célula iniciará o menu principal do assistente no console de saída, permitindo a interação com os agentes.
      
---

Criado por: `João Vitor Acquesta`
Repositório do Projeto: `https://github.com/JoaoAcq/Agente_Culinario_IA`
