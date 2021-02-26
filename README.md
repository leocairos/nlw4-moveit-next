# moveit-next by NLW 4

$ yarn create next-app moveit-next

* trocar extensão dos arquivos js e jsx por ts e tsx.

$ yarn add -D typescript @types/react @types/react-dom @types/node

$ yarn dev

* Organizar os arquivos e pastas

* Copiar link da fonte para o src/pages/_document.tsx

  * importar Head de next/head
  * colocar na tag Head fechando a tag (/>)
  
## Deploy

* https://vercel.com/

* $ npm i -g vercel

* Executar no CMD, no terminal do VSCode apresenta erro.
  - $ vercel -h 

* Fazer login na estação com o vercel
  - $ vercel login
  - Vai pedir seu e-mail
  - Vai ser enviado e-mail para clicar em confirmar

* Acessar pasta do projeto e dar o comando vercel
  - $ ..\moveit-next> vercel
  ```    
    Vercel CLI 21.3.1
    ? Set up and deploy “~\rdlsc\rocketseat\nlw4\moveit-next”? [Y/n] y
    ? Which scope do you want to deploy to? leocairos
    ? Link to existing project? [y/N] n
    ? What’s your project’s name? moveit-next
    ? In which directory is your code located? ./
    Auto-detected Project Settings (Next.js):
    - Build Command: `npm run build` or `next build`
    - Output Directory: Next.js default
    - Development Command: next dev --port $PORT
    ? Want to override the settings? [y/N] n
    �  Linked to leocairos/moveit-next (created .vercel and added it to .gitignore)
    �  Inspect: https://vercel.com/leocairos/moveit-next/HUgx9pkHVcSkk4wpACVHEr9ycPG3 [1s]
    ✅  Production: https://moveit-next-silk.vercel.app [copied to clipboard] [52s]
    �  Deployed to production. Run `vercel --prod` to overwrite later (https://vercel.link/2F).
    �  To change the domain or build command, go to https://vercel.com/leocairos/moveit-next/settings
  ```

* Para fazer o deploy de nova versão
  - $ vercel --prod

## Demo

Demo disponivel em https://moveit-next-silk.vercel.app/

### Códigos para o desafio

* #rumoaoproximonivel
* #jornadainfinita
* #focopraticagrupo
* #neverstoplearning

