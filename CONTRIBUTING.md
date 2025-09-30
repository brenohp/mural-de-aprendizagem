# 🚀 Guia de Contribuição: Adicione seu Card ao Mural

Ficamos muito felizes com o seu interesse em contribuir com o **Mural da Comunidade**! Este guia rápido irá te levar à sua **primeira contribuição open source**.

## ✅ Passo 1: Preparação do Ambiente

1.  **Faça um Fork:** Clique no botão "Fork" no canto superior direito deste repositório para criar uma cópia em sua conta do GitHub.
2.  **Clone o seu fork:** Clone a cópia para a sua máquina local e entre na pasta do projeto.
    ```bash
    git clone [https://github.com/SEU_USUARIO/mural-de-aprendizagem.git](https://github.com/SEU_USUARIO/mural-de-aprendizagem.git)
    cd mural-de-aprendizagem
    ```
3.  **Crie uma nova branch:** Crie uma branch específica para a sua alteração.
    ```bash
    git checkout -b adiciona-SEU-NOME
    ```

## ✍️ Passo 2: Adicionando seu Card ao `index.html`

O único arquivo que você precisa editar é o `index.html`.

1.  Abra o arquivo **`index.html`** no seu editor de código.
2.  Role a tela até a seção que contém a tag `<main class="grid-container">`.
3.  Você encontrará o bloco de código do **Card de Exemplo**. Copie **TODO** o bloco abaixo:

    ```html
    <div class="card">
        <img
          src="[https://github.com/SEU_USUARIO_AQUI.png](https://github.com/SEU_USUARIO_AQUI.png)"
          alt="Foto de perfil do GitHub"
        />
        <h2>Seu Nome Aqui</h2>
        <p>
          Uma breve descrição sobre você, seus hobbies ou o que está aprendendo.
        </p>
        <div class="social-links">
          <a href="[https://github.com/SEU_USUARIO_AQUI](https://github.com/SEU_USUARIO_AQUI)" target="_blank"
            >GitHub</a
          >
          <a href="[https://linkedin.com/in/SEU_USUARIO_AQUI](https://linkedin.com/in/SEU_USUARIO_AQUI)" target="_blank"
            >LinkedIn</a
          >
        </div>
      </div>
    ```
4.  Cole este novo bloco **imediatamente após o último card existente** no `index.html`.
    > **⚠️ ATENÇÃO:** Não remova ou altere nada além das informações dentro do seu novo bloco de código. O sistema de revisão irá detectar se você apagar outros cards.

5.  **Personalize as informações** no bloco de código que você colou:
    * **Foto:** Substitua `SEU_USUARIO_AQUI` pelo seu username do GitHub na URL (Ex: `https://github.com/brenohp.png`).
    * **Nome e Descrição:** Coloque seu nome e sua descrição pessoal.
    * **Links Sociais:** Atualize os URLs e o texto para os seus perfis (GitHub, LinkedIn, etc.).

## 📤 Passo 3: Finalizando e Abrindo o Pull Request

1.  **Faça o commit das suas alterações:**
    ```bash
    git add index.html
    git commit -m "feat: adiciona card de [Seu Nome Aqui]"
    ```
2.  **Faça o push** para o seu repositório remoto (seu fork):
    ```bash
    git push origin adiciona-SEU-NOME
    ```
3.  **Abra um Pull Request (PR):** Vá para a página do seu fork no GitHub e você verá um botão para **"Compare & pull request"**.

Pronto! Nosso robô de qualidade irá checar seu código e um mantenedor fará a revisão final.

Obrigado por fazer parte da nossa comunidade!
