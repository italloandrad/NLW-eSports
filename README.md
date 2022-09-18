<h1 align="center">
	<img alt="Logo NLW eSports" src="https://gist.githubusercontent.com/vitorluigiorsini/d06d19995e0e33b0cd63a405daf0cb6f/raw/85fbd32e3642068228b231258ffbe38be1a3d3a8/nlw-esports-logo.svg" />
</h1>


# NLW-eSports
Projeto desenvolvido no evento Next Level Week (NLW) - eSports da Rocketseat 🚀

## Autor

- [@Itallo Andrade](https://github.com/italloandrad)

## Screenshots
![rkt](https://user-images.githubusercontent.com/63079674/190882974-26000509-1593-4e7e-9cbc-d29e984339dc.PNG)

![rokt2](https://user-images.githubusercontent.com/63079674/190882990-d6625008-1ab7-4fbc-9ee7-e015dd1f8cd2.PNG)



## Demonstração Apicação Mobile
### Aguarde o Gif 
![Screenrecorder-2022-09-17-23-00-19-781](https://user-images.githubusercontent.com/63079674/190882899-bca1695c-0b10-4ce0-a09e-77d838261568.gif)

## Projeto Online
Link do Projeto Online : https://nlw-e-sports-three.vercel.app/
para receber as informações do Servidor - é necessario abrir o Projeto "Server" e rodar o comando npm run dev no terminal 

## Stack utilizada

**Web:** React, Vite, TailwindCSS, Radix, TypeScript

**Back-end:** NodeJS, Express, SQLite, Prisma, TypeScript

**Mobile:** React-Native, Expo, React Navigation, TypeScript



## Funcionalidades

- Front-end e Aplicação Mobile integrada com Back-End
- Aplicação para encontrar Pessoas para jogar junto
- Publique um anúncio com seus dados, horarios e discord e espere um MATCH!
- Faça amigos e joguem juntos =)




## CORES E FONTES

  COLORS:{
    
    BACKGROUND_900: '#121214',
    BACKGROUND_800: '#18181B',

    TEXT: '#FFFFFF',

    CAPTION_500: '#71717A',
    CAPTION_400: '#A1A1AA',
    CAPTION_300: '#D4D4D8',

    SHAPE: '#2A2634',

    PRIMARY: '#8B5CF6',
    SUCCESS: '#34D399',
    ALERT: '#F87171',

    FOOTER: ['rgba(0,0,0,0)', 'rgba(0,0,0,0.9)'],
    OVERLAY: 'rgba(0,0,0,0.6)',
  },

  FONT_FAMILY: {
    
    REGULAR: 'Inter_400Regular',
    SEMI_BOLD: 'Inter_600SemiBold',
    BOLD: 'Inter_700Bold',
    BLACK: 'Inter_900Black'
  },

  FONT_SIZE: {

    SM: 14,
    MD: 16,
    LG: 24
     }

### 🖥️ Web App

```bash
# Go into the repository
$ cd nlw-eSports/web

# Install dependencies
$ npm install

# Run the development server
$ npm run dev

# Navigate to http://localhost:5173
# The app will automatically reload if you change any of the source files.
```

### 📱 Mobile App

```bash
# Go into the repository
$ cd nlw-eSports/mobile

# Install dependencies
$ npm install

# Run the development server
$ expo start

# The app will automatically starts Metro Bundler. You may use an emulator or your own smartphone.
# The app will automatically reload if you change any of the source files.
```

### ⚙️ Server API

```bash
# Go into the repository
$ cd nlw-eSports/server

# Install dependencies
$ npm install

# Create the .env file in the repository and add the following line
DATABASE_URL="file:../src/database/db.sqlite"

# Run the development server
$ npm run start

# The app will automatically reload if you change any of the source files.
```
