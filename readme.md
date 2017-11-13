git clone https://github.com/ionic-team/stencil-starter.git my-app
cd my-app
git remote rm origin
git remote add origin https://github.com/kwokhung/testStencil.git

npm uninstall -g npm

npm install
npm start
npm run dev
npm run build
npm test
npm run test.watch
