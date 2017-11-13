git clone https://github.com/ionic-team/stencil-starter.git my-app
cd my-app
git remote rm origin

curl -u 'kwokhung' https://api.github.com/user/repos -d '{"name":"testStencil"}'
git remote rm origin
git remote add origin git@github.com:kwokhung/testStencil.git
git push origin master

npm uninstall -g npm

npm install
npm start
npm run dev
npm run build
npm test
npm run test.watch
