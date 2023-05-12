## Lect 1 :

- Emmet :
- CDN :
 - Crossorigin:
- Async & defer:

------

## Lect 2 : Ignite Our App
- Package is kind of module in js file;

- Npm : 
- npm init -y
- it stands for npm initialize and also -y means yes for all options
- Need of npm: because our react app comes with alot of powers to use them We need npm because while we build our app we need alot of other powers like minify the - code in our app, which comes with npm or yarn 

### Parcel : Like CRA or Vite > 
- "npm install -D parcel": > -D if want the thing only in our development phase ; Dev dependencies

- #### Package.lock.json : 
it basically tells us which version we're using while we are building our app...which locks the version of all dependencies
its an important file you never keep in git-ignore, it cause such kind of mistakes when your app is running on your local machine but not on the server 


- #### Package.json : 
we can use "^2.88.2" this (^) is a caret which automatically update the version of existing app
npx parcel index.html > npx means execute