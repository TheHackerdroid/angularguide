# Start Prject Angular

`ng new name-project`

## Firebase

El primer módulo de nodo que necesitamos instalar es el módulo @types. En el desarrollo inicial de TypeScript, había varios gestores de declaración de tipos diferentes para los archivos .d.ts. Con el lanzamiento de TypeScript 2.0, el método preferido es utilizar el módulo @types para administrar cualquier declaración de biblioteca adicional:

`npm install @types/request --save-dev --save-exact`

Luego instalamos firebase

`npm install firebase  --save`

y por ultimo el modulo de angularfirebase

`npm install angularfire2 --save`

ingresar al arcivo app.modulee.ts y agregar la tablade firebase

`import { AngularFireModule } from 'angularfire2';`

`import { AngularFireDatabaseModule } from 'angularfire2/database';`

`export const firebaseConfig = {`

`  apiKey: "",`

`  authDomain: "",`

`  databaseURL: "",`

`  projectId: "",`

`  storageBucket: "",`

`  messagingSenderId: ""`

`};`

y agregar las siguientes lineas en import

`...`

`  imports: [`

`    AngularFireModule.initializeApp(firebaseConfig),`

`    AngularFireDatabaseModule`

`  ],`

`....`





