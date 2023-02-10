# Vite 
    npm/pnpm create vite

2. Sass
    pnpm add sass -D

3. ESLint
    pnpm add @eslint/config

4. Prettier
    npm install --save-dev --save-exact prettier
    npx prettier --write .

5. THREE.JS
    npm install three

6. Interface
    npm install dat.gui

7. Github
    git merge branchname

8. GSAP
    npm install gsap / pnpm add gsap

9. Parcel
    npm install --save-dev parcel
    npx parcel root (src/index.html) --no-cache
    uninstall parcel

10. General
    cd'.\name\'

11. Jest
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

12. Axios
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
