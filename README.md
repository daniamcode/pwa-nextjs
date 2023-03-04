# pwa-nextjs
Building a Progressive Web App with Nextjs (following https://www.youtube.com/watch?v=ARNN_zmrwcw)

1) npx create-next-app ./
2) npm run dev
3) npm i next-pwa (external library: Zero Config PWA Plugin for Next.js)
4) generate manifest file (i.e via https://www.simicart.com/manifest-generator.html/) and copy files into /public, renaming manifest to manifest.json
5) create the _document.js file in /pages (just put in the code shown there)
6) add some config to next.config.js
7) npm run build
8) add pwa folders to gitignore
9) npm run start


And now we can see on the browser the "install app" icon

Note: I launched the /app experimental feature in nextjs 13 and I had to move some files to the 
/pages folder so the styles break. But this is irrelevant for the purpose of this project, that is to build a PWA
