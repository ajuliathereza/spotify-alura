# 🎵 Clone do Spotify - Imersão Alura  

Este projeto é um clone da interface do Spotify, desenvolvido como parte da **Imersão Alura**. Ele utiliza **HTML, CSS e JavaScript** para criar uma experiência interativa semelhante à plataforma original. 

   ## 📸 Prévia do projeto:
   
   ![Captura de tela 2025-02-05 193523](https://github.com/user-attachments/assets/ba5432df-e0f4-4d49-8aeb-9580cd44437e)

## 🚀 Funcionalidades:  

✔ Interface inspirada no Spotify, incluindo sidebar, barra de busca e seções de playlists.  
✔ Listagem de playlists organizadas em seções.  
✔ Pesquisa de artistas.  
✔ Design responsivo para melhor experiência em dispositivos móveis.  

   
   ## 📌 Tecnologias utilizadas:
    - HTML5.
    - CSS3 (com Media Queries para responsividade).
    - JavaScript (ES6+).
    - JSON Server.


## 📂 Estrutura do Projeto:

📦 seu-repositorio  
┣ 📂 api-artists
\
┃
   ┣ artists.json → Dados da API
\
┣ 📂 src  
┃ ┣ 📂 assets  
┃ ┃ ┣ 📂 icons → Ícones do projeto  
┃ ┃ ┗ 📂 playlist → Imagens das playlists  
┃ ┣ 📂 styles  
┃ ┃ ┣ 📜 reset.css → Reset de estilos  
┃ ┃ ┣ 📜 vars.css → Variáveis CSS  
┃ ┃ ┣ 📜 main-content.css → Estilos do conteúdo principal  
┃ ┃ ┣ 📜 sidebar-footer.css → Estilos da barra lateral e rodapé  
┃ ┃ ┗ 📜 media-query.css → Estilos responsivos  
┃ ┣ 📜 script.js → Funcionalidade de saudações e renderização da lista conforme tamanho de tela
\
┃ ┗ 📜 search.js → Funcionalidade de pesquisa de Artistas na API
\
┣ 📜 index.html → Página principal  
┣ 📜 README.md → Documentação do projeto  



## 🛠 Como executar o projeto:  

1. **Clone o repositório:**  
  ```
https://github.com/ajuliathereza/spotify-alura.git
  ```

2. **Acesse o diretório pelo seu terminal:**
```
cd seu-repositorio
```
3. **Para abrir o projeto no VS code utilize o comando:**
```
code .
```
4. **Para utilizar o JSON Server que simula a API artists é necessário instalar o Node.js**  
aqui está o **link** para download: [https://nodejs.org/pt/download](https://nodejs.org/pt/download)

5. Depois de baixar e instalar o **Node.js** será necessário instalar o JSON Server através do comando abaixo no seu **Terminal**:  
```
npm i json-server -g
```

6. **Após isso, suba o JSON Server para simular a API Artists com o comando a seguir:**
```
json-server --watch api-artists/artists.json --port 3000
```
7. **Agora o projeto está todo configurado, a partir de agora ele também é seu. Execute-o e divirta-se!🚀**

  📜 Créditos
Projeto desenvolvido durante a Imersão Alura, uma série de aulas práticas para aprendizado de tecnologias web.

