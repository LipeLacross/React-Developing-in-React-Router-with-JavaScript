## 🌐 [English Version of README](README_EN.md)

# Olá Mundo

**Olá Mundo** é um blog pessoal desenvolvido com React, projetado para compartilhar conhecimentos, experiências e atualizações sobre desenvolvimento front-end. Com uma interface amigável e responsiva, o blog permite que os visitantes naveguem facilmente entre diferentes posts e páginas informativas, proporcionando uma excelente experiência em dispositivos móveis e desktops.

## 🔨 Funcionalidades do Projeto

- **Página Inicial:** Exibe uma lista de posts recentes com títulos e imagens de capa.
- **Página Sobre Mim:** Seção dedicada para compartilhar informações pessoais e profissionais.
- **Visualização de Posts:** Cada post pode ser visualizado individualmente com seu conteúdo completo.
- **Página 404 Personalizada:** Página de erro personalizada para rotas inexistentes.
- **Navegação Intuitiva:** Menu de navegação simples para acessar as diferentes seções do blog.
- **Responsividade:** Design adaptável para diferentes tamanhos de tela, garantindo uma boa experiência em dispositivos móveis e desktops.
- **Scroll To Top:** Componente que rola automaticamente para o topo da página ao navegar entre rotas.

### Exemplo Visual do Projeto	

![Tela Inicial do Blog](public/assets/screenshots/homepage.png)

*Nota: Adicione capturas de tela reais do seu projeto na pasta `public/assets/screenshots/` e atualize os caminhos das imagens conforme necessário.*

## ✔️ Técnicas e Tecnologias Utilizadas

- **React:** Biblioteca JavaScript para construção de interfaces de usuário.
- **React Router:** Biblioteca para gerenciamento de rotas no aplicativo.
- **CSS Modules:** Abordagem para estilização de componentes com escopo local.
- **React Markdown:** Biblioteca para renderizar conteúdo Markdown como HTML.
- **JavaScript Moderno (ES6+):** Utilização das últimas funcionalidades da linguagem.
- **Create React App:** Ferramenta para configuração inicial e scripts de build.
- **Ferramentas de Build:** Utilização de ferramentas como Webpack e Babel através do Create React App.

## 📁 Estrutura do Projeto

- **public/**
  - `favicon.ico`: Ícone do site.
  - `index.html`: Arquivo HTML principal.
  - `assets/`: Diretório para recursos estáticos como imagens e gifs.
    - `posts/`: Contém imagens relacionadas a cada post.
      - `1/`: Imagens do post 1.
        - `capa.png`: Imagem de capa do post.
        - `gif-1.gif`: GIF relacionado ao post.
        - `gif-2.gif`: Outro GIF relacionado ao post.
      - `2/` a `8/`: Imagens de capa para outros posts.
    - `circulo_colorido.png`: Imagem decorativa.
    - `erro_404.png`: Imagem para a página 404.
    - `marca_registrada.svg`: Logotipo em SVG.
    - `minha_foto.png`: Foto do autor.
    - `sobre_mim_capa.png`: Imagem de capa para a página "Sobre Mim".
    - `sobre_mim_foto.png`: Foto adicional para a página "Sobre Mim".
  - `logo192.png`: Logo para dispositivos móveis.
  - `logo512.png`: Logo para dispositivos de alta resolução.
  - `manifest.json`: Configurações do aplicativo web.
  - `robots.txt`: Arquivo para controle de indexação por motores de busca.
  
- **src/**
  - `assets/`: Imagens e ícones utilizados no projeto.
  - `componentes/`: Componentes reutilizáveis do React.
    - `Banner/`: Componente de banner com título e imagens.
      - `Banner.module.css`: Estilos para o banner.
      - `index.js`: Implementação do componente Banner.
    - `BotaoPrincipal/`: Botão estilizado principal.
      - `BotaoPrincipal.module.css`: Estilos para o botão.
      - `index.js`: Implementação do componente BotaoPrincipal.
    - `Menu/`: Navegação principal do site.
      - `Menu.module.css`: Estilos para o menu.
      - `index.js`: Implementação do componente Menu.
    - `MenuLink/`: Links individuais do menu.
      - `MenuLink.module.css`: Estilos para os links do menu.
      - `index.js`: Implementação do componente MenuLink.
    - `PaginaPadrao/`: Layout padrão para as páginas.
      - `index.js`: Implementação do componente PaginaPadrao.
    - `PostCard/`: Cartão de apresentação de cada post.
      - `Post.module.css`: Estilos para o PostCard.
      - `index.js`: Implementação do componente PostCard.
    - `PostModelo/`: Modelo de página para exibição de posts.
      - `PostModelo.module.css`: Estilos para o PostModelo.
      - `index.js`: Implementação do componente PostModelo.
    - `Rodape/`: Rodapé do site.
      - `Rodape.module.css`: Estilos para o rodapé.
      - `index.js`: Implementação do componente Rodape.
    - `ScrollToTop/`: Componente para rolagem automática para o topo.
      - `index.js`: Implementação do componente ScrollToTop.
  - `index.css`: Estilos globais da aplicação.
  - `index.js`: Ponto de entrada da aplicação.
  - `json/`: Arquivos JSON contendo dados estáticos, como os posts.
    - `posts.json`: Dados dos posts do blog.
  - `paginas/`: Páginas principais do site.
    - `Inicio/`: Página inicial com lista de posts.
      - `Inicio.module.css`: Estilos para a página inicial.
      - `index.js`: Implementação da página Inicio.
    - `NaoEncontrada/`: Página 404 personalizada.
      - `NaoEncontrada.module.css`: Estilos para a página 404.
      - `index.js`: Implementação da página NaoEncontrada.
    - `Post/`: Página individual para cada post.
      - `Post.css`: Estilos específicos para posts.
      - `Post.module.css`: Estilos adicionais para a página de posts.
      - `index.js`: Implementação da página Post.
    - `SobreMim/`: Página sobre o autor.
      - `SobreMim.module.css`: Estilos para a página SobreMim.
      - `index.js`: Implementação da página SobreMim.
  - `routes.js`: Configuração das rotas do aplicativo.
  
- **package.json**: Dependências e scripts do projeto.
- **README.md**: Documentação do projeto.
- **README_EN.md**: Versão em inglês do README.
- **LICENSE**: Licença do projeto.
- **jsconfig.json**: Configurações do JavaScript.
- **package-lock.json**: Lockfile para dependências do npm.
- **directory_listing_1.txt**: Listagem de diretórios (provavelmente para referência).

## 🛠️ Abrir e rodar o projeto

Para iniciar o projeto localmente, siga os passos abaixo:

1. **Certifique-se de que o Node.js está instalado**:
   - O [Node.js](https://nodejs.org/) é necessário para rodar o projeto. Você pode verificar se já o tem instalado com:
     
     ```bash
     node -v
     ```
   
   - Se não estiver instalado, baixe e instale a versão recomendada.

2. **Clone o Repositório**:
   - Copie a URL do repositório e execute o comando abaixo no terminal:
     
     ```bash
     git clone <URL_DO_REPOSITORIO>
     ```

3. **Navegue para o Diretório do Projeto**:
   
   ```bash
   cd OláMundo
   ```

4. **Instale as Dependências**:

   ```bash
   npm install
   ```

   ou

   ```bash
   yarn install
   ```

5. **Inicie o Servidor de Desenvolvimento**:

   ```bash
   npm start
   ```

   ou

   ```bash
   yarn start
   ```

   O aplicativo será aberto no seu navegador padrão em `http://localhost:3000`.

## 🌐 Deploy

Para fazer o deploy da sua aplicação, você pode utilizar plataformas como **Vercel**, **Netlify** ou **GitHub Pages**. Abaixo estão os passos para realizar o deploy usando o **Vercel**:

1. **Instale a CLI do Vercel** (se ainda não tiver):

   ```bash
   npm install -g vercel
   ```

2. **Faça Login no Vercel**:

   ```bash
   vercel login
   ```

3. **Realize o Deploy**:

   ```bash
   vercel
   ```

   Siga as instruções no terminal para completar o processo de deploy.

4. **Configurações Adicionais**:
    - Certifique-se de que o script de build no `package.json` está correto:

      ```json
      "scripts": {
        "start": "react-scripts start",
        "build": "react-scripts build",
        "test": "react-scripts test",
        "eject": "react-scripts eject"
      }
      ```

    - O Vercel detecta automaticamente que se trata de um projeto React e configura as etapas de build e deploy adequadamente.

5. **Acesse sua Aplicação**:
    - Após o deploy, o Vercel fornecerá uma URL onde sua aplicação estará disponível.
