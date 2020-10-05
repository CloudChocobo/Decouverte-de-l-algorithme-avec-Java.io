# Tutoriel d'algorithmie avec le langage Java

## Le langage Java

Java est un langage de programmation dit "orienté objet" c'est à dire que chaque concept, idée ou entité physique sera mis dans une "brique logicielle" appelée objet.  Ensuite l'interaction que l'on créera entre ces objets permettra de concevoir les fonctionnalités désirées.  

Par exemple pour créer une voiture on doit assembler et créer differente interractions entre different éléments et concepts comme par exemple le volant pour diriger , les roues pour avancer, les sièges pour s'assoire etc...  après avoir mis tout ces éléements en relation entre eux nous arrivons à la création d'une voiture qui nous permettra de nous déplacer. 


## L'algorithmie

L'algorithmie c'est le processus par lequel on va etudier et diviser une tâche complexe en en une série de plusieurs tâches élémentaires à effectuer dans un ordre bien particulier.



### La notion de variable

Une variable est une donnée ou objet, identifiée par son nom et associé à une valeur qui peut être modifiée pendant l'exécution d'un programme Java.
La variable ne peut en aucun cas commencer par un chiffre. Elle doit donc débuter par une lettre ou éventuellement un _ et ne peut comporter d'autres caractères spéciaux. 

exemple : 

Seront des noms de variables acceptés :

* MaVie
* _MaVie
* Ma_Vie
* maVie_

Ne seront pas des noms de variables acceptés:

* (Mavie)
* ma=vie
* 'maVie
* -maVie
        
-----------------------
-----------------------
### Les Types de variables

Il existe 3 types de variables qui peuvent comprendre 2 types de données.

Il y a la *local variable*, déclarée à l'intérieur du corps d'une méthode et qui ne peut être utilisée que dans la fonction ou bloc défini.

L' *instance variable*, déclarée sans mot-clé static et en dehors d'une méthode de déclaration.

la *static variable*, initialisée qu'une seule fois au début de l'exécution du programme et avant toutes autres *instance variables*

Ces variables peuvent contenir différents types de données.

Les données dites primitives. Elles sont déjà définies dans Java.

* int : concerne les nombres entiers qui peuvent être longs ou courts  
    
    int age = 40;

* byte: concerne des entiers plutôt courts

    byte b = 10;

* long: concerne des entiers très longs

    long num1 = 123456789;

* short: concerne des entiers très courts

    short num = 5;

* float : concerne des nombres réels (à virgules, et moins précis que double si on prend loin derrière la virgule)
    
    float D = (float)12.5;

* double: concerne des nombres réels (à virgules) 

    double pi = 3.1415

* char : concerne une seule et unique lettre (caractère unicode)

    char grade = 'F';

* boolean : concerne une valeur logique, uniquement True ou False

    boolean dodo = true;

Les données dites non-primitives: elles ne contiennent pas de valeurs mais des adresses ou des références.

* strings: une chaîne de caractères compris entre double "".

    // créer une string variable
    String name = "Aurelie";

-----------------------------
-----------------------------

### Les mots-clés

Il existe une série de 53 mots-clés qui sont réservés. on ne peut pas les utiliser pour nommer des variables ou des objets sous peine de renvoyer à des erreurs et ne ne pas pouvoir compiler notre code.
Les noms des données types de Java font partie des mots-clés.
    
voici la liste par ordre alphabétique :

* A
    abstract
    assert
* B
    boolean
    break
    byte
* C
    case
    char
    class
    const
    continue
* D
    default
    do
    double
* E
    else
    enum
    extends
* F
    false
    final
    finally
    float
    for
* G
    goto
* I
    if
    implements
    import
    instanceof
    int
    interface
* L
    long
* N
    native
    new
    null
* P
    package
    private
    protected
    public
* R
    return
* S
    short
    static
    strictfp
    super
    switch
    synchronized
* T
    this
    throw
    throws
    transient
    true
    try
* V 
    void
    volatile
* W
    while
    
-------------------------
--------------------------

### Les Opérateurs

Il existe différents types d'opérateurs en Java permettant de travailler les variables.

Les plus courants et les plus basiques sont les **opérateurs de calcul**, qui s'appliquent aux types de données **int** , **double** et **float**.

* + pour les additions
* - pour les soustractions
* * pour les multiplications
* / pour les divisions
* % pour le modulo (donne le restant après avoir dividé le dividende par le diviseur)

exemple : 
**int** a = 40;
**int** b = 20;

result = a **+** b; //60
result = a **-** b; //20
result = a * b; //800
result = a **/** b //2
result = a **%** b //0

-----
Il y a aussi les **opérateurs de comparaison**, utilisés pour comparer 2 valeurs.

* > plus grand que
* < plus petit que
* >= plus grand ou égal à
* <= plus petit ou égal à
* == égal à
* != différent de

exemple :
**int** a = 3;
**int** b = 5;

**boolean** result = a **>** b; // le resultat sera False

------







## L'instruction

L'instruction est une ligne de code qui décris une tâche à executer. 

par exemple:  

            10 + 3 ;

ici on demande d'aditionner la valeur "10" à la valeur "3";

            int numero1 = 13 ;

ici on demande d'initialiser la variable "numero1" comme "integer" et demande de lui assigner la valeur 13.

## L'assignation

Pour manipuler des valeurs un programme a besoin de variables pour les contenir. L'assignation consiste à affecter une valeur à une variable.

par exemple: 

            int numero1 = 13 ;

-"numéro1" est notre variable .   
-"int" nous indique que la variable n'accepte pour assignation que des entiers .  
-"=" indique que l'on souhaite assigner la valeur de droite à la variable de gauche.  

on peut affecter le contenu d'une variable à une autre variable:

par exemple: 

            int numero1 = 13 ;
            int numero2 = 2 ;

pour le moment la valeur "13" est assignée à la variable "numéro1" et la valeur "2" est assignée à la variable "numéro2".

mais si j'écris:

             numero1 = numero2  ;

Alors désormais la variable "numero1" contient la valeur de la variable "numero2" autrement dit la valeur "2" est assigné à la variable "numer1":

            numero1 = 2;

## L'évaluation

Lors de l'évaluation on va fabriquer de nouvelles valeurs à partir d'autres valeurs préexistantes à l'aide d'expressions arithmétiques tel que l'addition, la multiplication etc...  
ou de comparaisons logiques dont la valeur produite sera dite de type "boolean".

par exemple :  
                
            int numero1 = 13;
            int numero2 = 2;
            int numero3 = numero1 + numero2;

ici les valeurs de "numero1" et "numero2" ont été additionné et le résultat a été assigné à une nouvelle variable que l'on a appelée "numero3".   
La valeur contenue par la variable "numero3" est donc : **13+2 = 15**

Maintenant si j'écris:  

               numero1 < numero2 

Alors la valeur de type "boolean" créée sera dite "false" car **13** n'est pas plus petit que **2**.

En revanche si j'écris:

               numero2 < numero1 

Ici la va leur créer par cette evaluation sera dite "True" car effectivement **2** est plus petit que **13**.



## le bloc d'instructions

Il est possible de regrouper plusieurs instructions par bloc dont les limites seront identifiés par des accolades **{}** .

par exemple: 

            int numero1 = 13;
            int numero2 = 2;
             

            if (numero1 < numero2 ){
                 int numero3 = numero1 + numero2;
                 return numero3
               }else return -1

Ici on demande d'executer les instructions contenues dans le bloc encadrer par les symboles **{}** à la condition que la valeur contenue par la variable "numero1" soit plus petite que celle contenue par "numero2".
dans le l'exemple ci-dessus la condition n'étant pas remplie , les instructions du bloc ci-dessous:
                
                {
                 int numero3 = numero1 + numero2;
                 return numero3
               }

ne seront pas executées et la console la console affichera -1.

Il est possible d'insérer des blocs dans des blocs.


## le commentaire

Le commentaire consiste à annoter le code pour le rendre plus comprensible et plus lisible. Le commentaire n'est pas perçu comme une instruction executable par le programme en lui-même. Il est un suplement d'information que l'on s'adresse à soi-même ou à un autre développeur dans le but de faciliter la maintenance.

En langage Java le commentaire commence par le signe *//* si il ne comprend qu'une seule ligne.
Si le commentaire contient plusieurs ligne on préfèrera l'encadrer par les signes */** et **/* .


par exemple: 

            // blblblablabalblablalbalblabal.

et 


            /*blablablbalablablabalbalaballa  
            blablbalbablablbalbalbalbalablaba  
            blblblablabalbabablabalablaablbalb
            blblbalblablabalbalbalbalbalbalabab*/
            
