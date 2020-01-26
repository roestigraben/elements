# elements

test site to check the setup:
  - create Angular Elements (not part of this repository)
  - insert it into minimalistic vue.js based app
  - test it on github pages
  
the construction is as follows so not to have error message when a vue.js app 
is used after npm run build. Here the error was that duplicates were present in Registry.

Hence, I used a plain vanilla html setup and add the div with id="app" to plsce the vue app.
Then I add all the js and css files for the dist folder of the separate folder where I built 
the vue.js app with the Angular Element included. In the development mode, this app never had 
any trouble to accept the Angular Elements.

the file elements.js is the angular elements bundle exported from the Angular app representing the element.

