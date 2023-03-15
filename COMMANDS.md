# Vite 
    npm/pnpm create vite
    npm/pnpm create vite .

# Sass
    npm install sass /-D
    pnpm add sass /-D

# ESLint
    npm/pnpm install --save-dev eslint
    npx eslint --init
    eslint-config-prettier

# Prettier
    npm/pnpm install --save-dev --save-exact prettier
    npx prettier --write .

# THREE.JS
    npm/pnpm install three
    
# Interface
    npm/pnpm install dat.gui

# Github
    git merge branchname

# GSAP
    npm/pnpm install gsap

# Parcel
    npm/pnpm install --save-dev parcel
    npx parcel root (src/index.html) --no-cache
    uninstall parcel

# General
    cd'.\name\'

# Jest
    npm i --save-dev jest ts-jest @types/jest
    npx jest
    npx jest –watchAll
    npm i --save-dev ts-jest
    npm test
    npx jest --coverage
    npm i --save-dev jest-environment-jsdom
    
    package.json 

    "jest": {
       "preset": "ts-jest",
       "testEnvironment": "node",
       "collectCoverage": true,
       "coverageReporters": ["html"]
    }
    
    "scripts": {
        "test": "npx jest --watchAll"
    }
    
    /**
      * @jest-environment jsdom
    */

# Axios
    npm i axios

13. Cypress
    npm i --save-dev cypress
    npx cypress open
    
    I tsconfig.json
    {
      "compilerOptions": {
        "target": "ESNEXT",
        "lib": ["ESNEXT", "dom"],
        "types": ["cypress", "node"]
      },
      "include": ["**/*.ts"]
    }
  
  14. Git
      git init
      git add
      git add .
      git add *
      git rm
      git commit -m "Description of changes here".
      git log
      git --oneline
      git remote add origin <UrlToRepo> 
      git puch -u origin branchname
      git push
      git pull
 
 15. Nodemon
     npm/pnpm install nodemon
     npm/pnpm installl -g nodemon
 
 16. Express
     npx express-generator --no-view
 
17. MongoDB
    npm/pnpm install mondodb

18. ENV
    npm install dotenv
