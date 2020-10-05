JAVA
--------------

Java est un langage de programmation orienté objet, crée en 1995 par Sun Microsystems et racheté en 2009 par Oracle.
------------

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
    
