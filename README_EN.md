## 🌐 [Portuguese Version of README](README.md)

# Olá Mundo

**Olá Mundo** is a personal blog developed with React, designed to share knowledge, experiences, and updates on front-end development. With a user-friendly and responsive interface, the blog allows visitors to easily navigate between different posts and informational pages, providing an excellent experience on both mobile devices and desktops.

## 🔨 Project Features

- **Home Page:** Displays a list of recent posts with titles and cover images.
- **About Me Page:** A dedicated section to share personal and professional information.
- **Post Viewing:** Each post can be viewed individually with its complete content.
- **Custom 404 Page:** Personalized error page for non-existent routes.
- **Intuitive Navigation:** Simple navigation menu to access different sections of the blog.
- **Responsiveness:** Adaptive design for different screen sizes, ensuring a good experience on mobile devices and desktops.
- **Scroll To Top:** Component that automatically scrolls to the top of the page when navigating between routes.

### Project Visual Example

![Blog Home Screen](public/assets/screenshots/homepage.png)

*Note: Add real screenshots of your project in the `public/assets/screenshots/` folder and update image paths as necessary.*

## ✔️ Techniques and Technologies Used

- **React:** JavaScript library for building user interfaces.
- **React Router:** Library for managing routes in the application.
- **CSS Modules:** Approach for styling components with local scope.
- **React Markdown:** Library for rendering Markdown content as HTML.
- **Modern JavaScript (ES6+):** Utilization of the latest language features.
- **Create React App:** Tool for initial setup and build scripts.
- **Build Tools:** Utilization of tools like Webpack and Babel through Create React App.

## 📁 Project Structure

- **public/**
  - `favicon.ico`: Site icon.
  - `index.html`: Main HTML file.
  - `assets/`: Directory for static resources like images and gifs.
    - `posts/`: Contains images related to each post.
      - `1/`: Images for post 1.
        - `capa.png`: Cover image for the post.
        - `gif-1.gif`: GIF related to the post.
        - `gif-2.gif`: Another GIF related to the post.
      - `2/` to `8/`: Cover images for other posts.
    - `circulo_colorido.png`: Decorative image.
    - `erro_404.png`: Image for the 404 page.
    - `marca_registrada.svg`: SVG logo.
    - `minha_foto.png`: Author's photo.
    - `sobre_mim_capa.png`: Cover image for the "About Me" page.
    - `sobre_mim_foto.png`: Additional photo for the "About Me" page.
  - `logo192.png`: Logo for mobile devices.
  - `logo512.png`: Logo for high-resolution devices.
  - `manifest.json`: Web app configurations.
  - `robots.txt`: File for search engine indexing control.

- **src/**
  - `assets/`: Images and icons used in the project.
  - `componentes/`: Reusable React components.
    - `Banner/`: Banner component with title and images.
      - `Banner.module.css`: Styles for the banner.
      - `index.js`: Implementation of the Banner component.
    - `BotaoPrincipal/`: Main styled button.
      - `BotaoPrincipal.module.css`: Styles for the button.
      - `index.js`: Implementation of the BotaoPrincipal component.
    - `Menu/`: Main site navigation.
      - `Menu.module.css`: Styles for the menu.
      - `index.js`: Implementation of the Menu component.
    - `MenuLink/`: Individual menu links.
      - `MenuLink.module.css`: Styles for the menu links.
      - `index.js`: Implementation of the MenuLink component.
    - `PaginaPadrao/`: Default layout for pages.
      - `index.js`: Implementation of the PaginaPadrao component.
    - `PostCard/`: Presentation card for each post.
      - `Post.module.css`: Styles for the PostCard.
      - `index.js`: Implementation of the PostCard component.
    - `PostModelo/`: Page model for displaying posts.
      - `PostModelo.module.css`: Styles for the PostModelo.
      - `index.js`: Implementation of the PostModelo component.
    - `Rodape/`: Site footer.
      - `Rodape.module.css`: Styles for the footer.
      - `index.js`: Implementation of the Rodape component.
    - `ScrollToTop/`: Component for automatic scroll to top.
      - `index.js`: Implementation of the ScrollToTop component.
  - `index.css`: Global styles for the application.
  - `index.js`: Entry point of the application.
  - `json/`: JSON files containing static data, like posts.
    - `posts.json`: Blog posts data.
  - `paginas/`: Main pages of the site.
    - `Inicio/`: Home page with list of posts.
      - `Inicio.module.css`: Styles for the home page.
      - `index.js`: Implementation of the Inicio page.
    - `NaoEncontrada/`: Custom 404 page.
      - `NaoEncontrada.module.css`: Styles for the 404 page.
      - `index.js`: Implementation of the NaoEncontrada page.
    - `Post/`: Individual post page.
      - `Post.css`: Specific styles for posts.
      - `Post.module.css`: Additional styles for the post page.
      - `index.js`: Implementation of the Post page.
    - `SobreMim/`: About the author page.
      - `SobreMim.module.css`: Styles for the SobreMim page.
      - `index.js`: Implementation of the SobreMim page.
  - `routes.js`: Application routes configuration.

- **package.json**: Project dependencies and scripts.
- **README.md**: Project documentation.
- **README_EN.md**: English version of the README.
- **LICENSE**: Project license.
- **jsconfig.json**: JavaScript configurations.
- **package-lock.json**: npm dependencies lockfile.
- **directory_listing_1.txt**: Directory listing (probably for reference).

## 🛠️ Open and Run the Project

To start the project locally, follow the steps below:

1. **Ensure that Node.js is installed**:
   - [Node.js](https://nodejs.org/) is required to run the project. You can check if it's already installed by running:
     
     ```bash
     node -v
     ```
   
   - If not installed, download and install the recommended version.

2. **Clone the Repository**:
   - Copy the repository URL and run the following command in the terminal:
     
     ```bash
     git clone <REPOSITORY_URL>
     ```

3. **Navigate to the Project Directory**:
   
   ```bash
   cd OláMundo
   ```

4. **Install Dependencies**:

   ```bash
   npm install
   ```

   or

   ```bash
   yarn install
   ```

5. **Start the Development Server**:

   ```bash
   npm start
   ```

   or

   ```bash
   yarn start
   ```

   The application will open in your default browser at `http://localhost:3000`.

## 🌐 Deploy

To deploy your application, you can use platforms like **Vercel**, **Netlify**, or **GitHub Pages**. Below are the steps to deploy using **Vercel**:

1. **Install the Vercel CLI** (if not already installed):

   ```bash
   npm install -g vercel
   ```

2. **Log in to Vercel**:

   ```bash
   vercel login
   ```

3. **Deploy**:

   ```bash
   vercel
   ```

   Follow the instructions in the terminal to complete the deployment process.

4. **Additional Configurations**:
    - Ensure that the build script in `package.json` is correct:

      ```json
      "scripts": {
        "start": "react-scripts start",
        "build": "react-scripts build",
        "test": "react-scripts test",
        "eject": "react-scripts eject"
      }
      ```

    - Vercel automatically detects that it's a React project and configures the build and deploy steps accordingly.

5. **Access Your Application**:
    - After deployment, Vercel will provide a URL where your application will be available.
urther assistance or additional sections in your documentation, feel free to ask!
