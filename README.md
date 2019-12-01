# angular-demo
A tutorial of how to use Angular CLI.  This demo was created to introduce Angular to students who may have no prior experience.  The offical documentation and tutorials can be found here: https://angular.io/guide/setup-local 

## Prerequisites
1. If you don't have Node.js, get it here: https://nodejs.org/en/ You can check by running `node -v` in the command terminal.
2. Update npm by running `npm install npm@latest -g`  For more information about npm, see https://www.npmjs.com/get-npm 
3. Install Angular CLI by running `npm install -g @angular/cli`
4. If you do not already have an IDE for web development, I recommend installing Visual Studio Code. https://code.visualstudio.com/

## Creating a basic app
1. Go to the directory where you want to create your app.
2. Run `ng new my-demo-app` "ng" stands for Angular.  "my-demo-app" would be the name of your app.
3. You will be prompted for several options for setting up your new app.  You can accept the defaults by pressing Enter.
4. This will generate a functioning sample app.

## Run the app
1. `cd my-demo-app` to navigate into your app directory.
2. `ng serve --open` will serve the app and open a browser so you can test your app.

## Creating a component
A component is a reusable piece of your application.  For example, if I want to display a list of items for sale on my website, I might make a component called ProductList to hold the layout of all the items.  I might also make a component called ProductCard which would hold the data for a single product.  The ProductList component would hold multiple instances of the ProductCard component.

To create a component, run `ng generate component product-list` replacing "product-list" with the name of your component.
