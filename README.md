# Bienvenue sur le MTK-Framework

  Ce framework est un travail étudiant visant à crée un framework en scss pour que dans un futur il puisse être utile pour de l'intégration

## Comment il fonctionne

Ce framework fonctionne sur une bases de douze colonnes avec 4 breakpoint 

- 1er breakpoint: téléphone à 480px
- 2éme breakpoint : tablette à 768px
- 3éme breakpoint : laptop à 1024px
- 4éme breakpoint : moniteur à 2560px

### Comment faire appel à ces colonnes 

Pour appeler ces colonnes il suffit de mettre une class dans la balise

Pour appeler des colonnes dans le format téléphone il suffit de marquer comme class: 
`col-phone-1` le dernier chiffre pouvant être changer jusqu'à 12.

Pour appeler des colonnes dans le format tablettes il suffit de marquer comme class: 
`col-pad-1` le dernier chiffre pouvant être changer jusqu'à 12.

Pour appeler des colonnes dans le format laptop il suffit de marquer comme class: 
`col-laptop-1` le dernier chiffre pouvant être changer jusqu'à 12.

Pour appeler des colonnes dans le format moniteur il suffit de marquer comme class: 
`col-monitor-1` le dernier chiffre pouvant être changer jusqu'à 12.

### Appelez les margin et padding

Dans ce framework vous pouvez appelez aussi des margin et padding soit un margin et un padding total qui s'appliquera dnas chaque direction soit de maniére plus précise. Pour l'unités de mesure des margin et padding ils sont gérer en rem.

Appelez les margin:
- margin global : `m-1`ce chiffre pouvant varier de 0 jusqu'à 20

- margin top : `m-t-0` ce chiffre pouvant varier de 0 jusqu'à 20

- margin right : `m-r-0` ce chiffre pouvant varier de 0 jusqu'à 20

- margin bottom : `m-b-0` ce chiffre pouvant varier de 0 jusqu'à 20

- margin left : `m-l-0` ce chiffre pouvant varier de 0 jusqu'à 20

Appelez les padding:
- padding : `p-0` ce chiffre pouvant varier de 0 jusqu'à 20

- padding top : `p-t-0` ce chiffre pouvant varier de 0 jusqu'à 20

- padding right : `p-r-0` ce chiffre pouvant varier de 0 jusqu'à 20

- padding bottom : `p-b-0` ce chiffre pouvant varier de 0 jusqu'à 20

- padding left : `p-l-0` ce chiffre pouvant varier de 0 jusqu'à 20

### Appelez les font size

Pour la font size c'est un peut particulier elle est gérer en em mais elle progresse de 0.1em a chaque fois que la class progresse de 1.
Exemple: 
la class `class="f-s-4"`appliquera un font-size de 0.4 em
la class `class="f-s-30"` appliquera un font size de 3em

Pour faire appele a la class il suffit de noter `f-s-1` le chiffre pouvant varier de 0 jusqu'à 40

### Appelez les border radius

Dans ce framework vous pouvez appelez aussi des border radius soit un border radius total qui s'appliquera dans chaque direction soit de maniére plus précise. Pour l'unités de mesure des border radius ils sont gérer en px.

Appelez les border radius:
- border radius global : `b-r-1`ce chiffre pouvant varier de 0 jusqu'à 20

- border radius top left : `b-r-tl-1` ce chiffre pouvant varier de 0 jusqu'à 20

- border radius top right : `b-r-tr-1`  ce chiffre pouvant varier de 0 jusqu'à 20

- border radius bottom right : `b-r-br-1` ce chiffre pouvant varier de 0 jusqu'à 20

- border radius bottom left : `b-r-bl-1` ce chiffre pouvant varier de 0 jusqu'à 20

### Appelez les box shadow

Dans ce framework vous pouvez appelez aussi des box shadow à chaque fois qu'un chiffre augmente la distance de l'ombre augmente de 1 en 1 mais le blur reste à 10 constamment.
Vous pouvez aussi changer la couleur il suffit de la changer dans le scss, pour cela il suffit de changer la couleur dans la commande `$shadow-color` de bases elle est sur la couleur `grey`.

Appelez la box shadow:
- boox shadow : `shadow-1`ce chiffre pouvant varier de 0 jusqu'à 10

