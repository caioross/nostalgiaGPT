<p align='center'>
  <a href="https://github.com/sponsors/caioross"><img alt="Sponsors" src="https://img.shields.io/badge/sponsor-30363D?style=for-the-badge&logo=GitHub-Sponsors&logoColor=#white" /></a>
  &nbsp;
  <a href="#"><img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/caioross/NostalgiaGPT?style=for-the-badge" /></a>
</p>

<p align='center'>
  <a href="https://github.com/caioross/NostalgiaGPT/pulse" alt="Activity">
          <img src="https://img.shields.io/github/commit-activity/m/caioross/NostalgiaGPT" /></a>
  <a href="https://github.com/caioross/NostalgiaGPT/discussions" alt="Discussions">
          <img src="https://img.shields.io/github/discussions/caioross/NostalgiaGPT" /></a>
  <a href="https://github.com/caioross/NostalgiaGPT/actions/workflows/daily-tests.yml">
          <img src="https://img.shields.io/github/actions/workflow/status/caioross/NostalgiaGPT/run.yml?label=Testes" alt="Daily Tests Status"></a>
</p>

# nostalgiaGPT: Converse com Personalidades Históricas

## Descrição

O nostalgiaGPT é um chat interativo que permite aos usuários conversarem com personalidades históricas famosas. Através de uma interface simples e intuitiva, você pode selecionar a personalidade desejada e enviar mensagens. O nostalgiaGPT utiliza a API da OpenAI para gerar respostas que simulam o estilo e a voz da personalidade escolhida, proporcionando uma experiência única e imersiva.

Este projeto é ideal para fins educacionais, entretenimento ou simplesmente para satisfazer a curiosidade sobre como figuras históricas poderiam responder a perguntas e situações modernas.

## Funcionalidades

*   **Chat com personalidades históricas:** Converse com uma variedade de figuras históricas famosas.
*   **Interface intuitiva:** Uma interface de chat simples e fácil de usar.
*   **Respostas geradas pela IA:** As respostas são geradas pela API da OpenAI, simulando o estilo da personalidade selecionada.
*   **Seleção de personalidades:** Escolha entre uma lista crescente de personalidades históricas.

## Personalidades Disponíveis

*   Albert Einstein
*   Alexandre, o Grande
*   Aristóteles
*   Ayrton Senna
*   Beethoven
*   Buda
*   Charles Darwin
*   Che Guevara
*   Cândido Rondon
*   Cleópatra
*   Claudio Coutinho
*   Confúcio
*   Dom Pedro II
*   Edgar Allan Poe
*   Eleanor Roosevelt
*   Elis Regina
*   Elvis Presley
*   Ernest Hemingway
*   Galileu Galilei
*   Gandhi
*   George Washington
*   Getúlio Vargas
*   Heitor Villa-Lobos
*   Isaac Newton
*   Jane Austen
*   Jesus Cristo
*   Johann Sebastian Bach
*   John F. Kennedy
*   Leonardo da Vinci
*   Ludwig van Beethoven
*   Machado de Assis
*   Mahatma Gandhi
*   Martin Luther King Jr.
*   Michelangelo
*   Napoleão Bonaparte
*   Nelson Mandela
*   Nikola Tesla
*   Pablo Picasso
*   Platão
*   Princesa Diana
*   Robin Hood
*   Salvador Dali
*   Shakespeare
*   Sigmund Freud
*   Steve Jobs
*   Thomas Edison
*   Van Gogh
*   Vincente de Paulo
*   Winston Churchill

## Como Usar

1.  **Clone este repositório:**

    ```bash
    git clone https://github.com/caioross/nostalgiaGPT.git
    ```

2.  **Abra o arquivo `index.html` em seu navegador.**

3.  **Selecione a personalidade com quem gostaria de conversar no menu suspenso.**

4.  **Escreva sua mensagem na caixa de texto na parte inferior da tela e clique em "Enviar".**

5.  **A personalidade escolhida responderá com uma mensagem gerada pela IA.**

### Configuração da API da OpenAI

Este projeto utiliza a API da OpenAI para gerar as respostas das personalidades históricas. Para que o projeto funcione corretamente, você precisa obter uma chave de API da OpenAI e configurá-la no código.

1.  **Crie uma conta na OpenAI:**

    *   Acesse o site da OpenAI: [https://www.openai.com/](https://www.openai.com/)
    *   Crie uma conta e obtenha sua chave de API.

2.  **Configure a chave de API no código:**

    *   Abra o arquivo `js/mainJs.js`.
    *   Localize a linha que define o cabeçalho `Authorization` na função `insertMessage`.
    *   Substitua `''` pela sua chave de API da OpenAI.

    ```javascript
    requestOptions = {
        method: 'POST',
        headers: {
            'Content-Type': 'application/json',
            'Authorization': 'SUA_CHAVE_DE_API_AQUI', // Substitua por sua chave de API
        },
        // ...
    };
    ```

## Tecnologias Utilizadas

*   HTML
*   CSS
*   JavaScript
*   [API da OpenAI](https://www.openai.com/): Utilizada para gerar as respostas das personalidades históricas.

## Contribuindo

Este é um projeto aberto e aceitamos contribuições da comunidade. Se quiser contribuir, siga os passos abaixo:

1.  **Fork este repositório.**
2.  **Crie um branch para sua nova funcionalidade:**

    ```bash
    git checkout -b feature/nova-funcionalidade
    ```

3.  **Faça as mudanças necessárias e commit:**

    ```bash
    git commit -am "Adicionando nova funcionalidade"
    ```

4.  **Envie as mudanças para o seu branch:**

    ```bash
    git push origin feature/nova-funcionalidade
    ```

5.  **Abra um Pull Request.**

## Roadmap

*   Adicionar mais personalidades históricas.
*   Implementar um sistema de autenticação para permitir que os usuários salvem suas conversas.
*   Melhorar a qualidade das respostas geradas pela IA.
*   Adicionar suporte para outros idiomas.
*   Implementar testes automatizados.

## Licença

Este projeto está licenciado sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais informações.
