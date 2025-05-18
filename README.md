🤖 Chef IA & Cia: Seu Assistente Culinário Multiagente Inteligente 🧑‍🍳💰🥗
Projeto desenvolvido para o Concurso de Chatbots Criativos da Alura com a API do Google Gemini.

Este projeto apresenta o "Chef IA & Cia", um assistente culinário inovador e interativo, construído em Python e integrado com a poderosa API do Google Gemini. Ele não é apenas um chatbot, mas um sistema multiagente projetado para oferecer uma experiência completa e divertida na cozinha, desde a inspiração para receitas até dicas de economia e bem-estar.

✨ Funcionalidades Principais:
O "Chef IA & Cia" é composto por três agentes especialistas que trabalham individualmente ou em conjunto:

🧑‍🍳 Chef Criativo de Geladeira:

Transforma os ingredientes que você tem em casa em receitas criativas e deliciosas.
Utiliza a busca do Google (integrada via Gemini) para se inspirar em tendências culinárias e sugestões atuais.
Formata as receitas de forma clara e permite que o usuário escolha uma para análise pelos outros agentes.
💰 Caçador de Ofertas:

Ajuda a encontrar as melhores promoções para ingredientes específicos ou para os itens de uma receita sugerida pelo Chef.
Utiliza a busca do Google para informações de ofertas (considerando a data atual para relevância).
Pode receber contexto do Chef Criativo para buscar ofertas para uma receita específica.
🥗 Nutricionista Lúdico e Motivador de Hábitos:

Fornece dicas de alimentação saudável, curiosidades sobre alimentos e sugestões para tornar as receitas mais nutritivas, tudo de forma leve e divertida.
Pode analisar uma receita específica (sugerida pelo Chef) para dar insights nutricionais gerais ou ideias de substituições saudáveis.
Propõe pequenos desafios para incentivar hábitos positivos.
Utiliza a busca do Google para embasar suas dicas com informações atuais.
Interatividade entre Agentes:
Uma das principais inovações é a capacidade dos agentes de interagirem e passarem contexto entre si. Por exemplo, após o Chef Criativo sugerir receitas, o usuário pode optar por:

Enviar os ingredientes de uma receita escolhida para o Caçador de Ofertas.
Enviar o texto de uma receita escolhida para o Nutricionista Lúdico para análise e dicas.
💡 Inovação e Criatividade para o Concurso Alura:
Abordagem Multiagente: Demonstra uma arquitetura mais complexa e uma divisão de responsabilidades que enriquece a interação.
Integração Profunda com Gemini e Google Search: As respostas dos agentes são potencializadas pela capacidade de geração de linguagem natural do Gemini e pelo acesso a informações em tempo real via Google Search.
Fluxo de Usuário Contextual: A capacidade de um agente chamar outro com base na interação atual (ex: Chef -> Caçador ou Chef -> Nutricionista) cria uma experiência mais fluida e inteligente.
Personas Criativas: Cada agente possui uma personalidade distinta, tornando a interação mais engajadora e divertida.
Foco em Utilidade e Diversão: O projeto não só resolve problemas práticos (o que cozinhar, como economizar, como ser mais saudável), mas também o faz de uma maneira lúdica e criativa.
🚀 Tecnologias Utilizadas:
Python
API do Google Gemini (para processamento de linguagem natural, geração de texto e controle dos agentes)
Google Search (integrado via funcionalidade de ferramentas do Gemini)
Google Colab (como ambiente de desenvolvimento e execução)
🔧 Como Executar:
O projeto foi desenvolvido em um notebook Google Colab (.ipynb). Para executá-lo:

Abra o notebook no Google Colab.
Configure sua GOOGLE_API_KEY nos segredos do Colab, conforme instruído nas primeiras células do notebook.
Execute todas as células em ordem.
A última célula iniciará o menu principal do assistente, permitindo a interação com os agentes.
