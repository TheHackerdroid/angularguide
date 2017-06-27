# Agregar el Home Component

Utlizando el angular cli

`ng g component home`



home.component.ts

import {AngularFireDatabase, FirebaseListObservable} from 'angularfire2/database';

tasks: FirebaseListObservable&lt;any\[\]&gt;;

