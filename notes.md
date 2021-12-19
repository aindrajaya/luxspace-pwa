BWA - PWA REACTJS 
-----
# Introduction
This course teach about how to implement PWA to React. The study case is about eCommerce. So we can learn on how to create an eCommerce based on PWA with React with some advance features such as add to cart, push notification, navigate and etc.

# Class Preparation
1. Trailer
2. Download Materi

# Into The Projects
1. Opening
***
2. Inisiasi Project
### Using CRA for PWA.
```bash
$ npx create-react-app your_project_name --template cra-template-pwa
```
`--template` : the command line flag that can be used to call specific react cra template (in this case we use pwa template that build from community)
`cra-template-pwa` : The template that provide by CRA community, you can learn more to this [link](https://create-react-app.dev/docs/making-a-progressive-web-app/) documentation.
### Deploy on Server
You can commit to your GitHub repository and deploy it to a cloud service such as Vercel. Why did we set up this in the early time? because we want to do continuous deployment at the first step. So at the next push to your GitHub repository, you can instantly see the changes on your online appearances.
***
3. Tailwind dan React
### Tailwind Installation on React
```bash
$ npm install -D tailwindcss@npm:@tailwindcss/postcss7-compat @tailwindcss/postcss7-compat postcss@^7 autoprefixer@^9

$ npm install -D npm-run-all chokidar-cli
```
`-D` : just using on the development stage, the lib will not used on our production stage (because we only use the compilation output from Tailwind)
`npm-run-all` : It will allow us to run react-scripts by parallel or one by one. Ex: we can runn react-scripts start to run our app, and at the same time we can also do tailwind compile.
`chokidar-cli` : It can allow us to do monitoring file changes. Ex. if some css file changes, so we can run one of our script to do another process.

4. Migrasi Komponent
5. Menampilkan Modal
6. Offline dengan Workbox
7. Event Service Worker
8. Cache CDN
9. Membaca Data JSON
10. Info Offline
11. App Icon dan Nama
12. Add to Homescreen
13. Customize Splash Screen
14. Kustomisasi Status Bar
15. Navigasi
16. Push Notification
17. Light House
18. Closing
19. Quiz

# Updated
1. Detail Page Part1
2. Detail Page Part2
3. Detail Page Part3
4. Implementasi Image Galery
5. Add to Cart
6. Cart LocalStorage