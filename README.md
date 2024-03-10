mkdir docker_nodejs
cd docker_nodejs

code .

# install git
git init

# list the local branches
git branch --list

# rename the name of master branch to main
git branch -m master main

npm init
npm install express

# write a Hello World! sample nodejs code

# run the express server on port 3000
node index.js

# test on browser localhost:3000


