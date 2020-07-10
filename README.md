# cloud-functions-template
A template for developing Google Cloud Functions outside of the console


## Instructions

1. Add your code

Copy in your index.js file

2. Add your dependencies

Copy the dependencies from your package.json to the one in this project; do not replace the whole file or devDependencies, otherwise the `npm run dev` script will not work

3. Install dependencies

Run `npm i` to install your dependencies and the dev dependencies

4. Run your code

Run `npm run dev` to start serving up your function locally -- this script uses nodemon so everytime you change the code, the server will automatically restart
