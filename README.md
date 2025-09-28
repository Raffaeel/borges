📌 Portfólio de Rafael Borges Oliveira

Este é o meu portfólio pessoal, criado para apresentar minhas habilidades como desenvolvedor front end junior. O site inclui minhas hard skills, certificados, projetos e formas de contato.

🛠 Tecnologias Utilizadas

HTML

CSS

JavaScript

Bootstrap

Node.js

React Native

TypeScript

Git/GitHub

📩 Implementando um Formulário de Contato com Formspree

Durante o desenvolvimento do portfólio, eu precisava de uma forma para permitir que recrutadores e visitantes me enviassem um e-mail diretamente do site. Depois de pesquisar sobre possíveis soluções, encontrei o Formspree e aprendi a usá-lo com a ajuda do ChatGPT. Seguem os passos que utilizei para configurar o envio de e-mails:

Passo a Passo da Configuração

1️⃣ Criar uma conta no Formspree

Acesse: https://formspree.io

Crie uma conta e faça login.

2️⃣ Criar um novo formulário

No dashboard, clique em "Create new form".

Escolha "Send emails to my email" e insira seu e-mail.

Copie o link gerado (parecido com https://formspree.io/f/abc123).

3️⃣ Adicionar o formulário ao HTML

No arquivo HTML, adicione o seguinte código:

<form action="https://formspree.io/f/SEU_ID_AQUI" method="POST">
    <label>Seu Nome:
        <input type="text" name="name" required>
    </label>
    <label>Seu Email:
        <input type="email" name="email" required>
    </label>
    <label>Mensagem:
        <textarea name="message" required></textarea>
    </label>
    <button type="submit">Enviar</button>
</form>

4️⃣ Testar o envio

Abra o site e envie um teste para garantir que o e-mail chegue corretamente.

🔹 Agora, recrutadores podem me enviar mensagens diretamente pelo meu portfólio!

🔗 Links do Portfólio

LinkedIn

GitHub

Este projeto me ajudou a aprender novas tecnologias e a implementar funcionalidades que antes eu não conhecia. O ChatGPT foi um grande aliado na solução de problemas e aprendizado durante esse processo. 💡🚀

