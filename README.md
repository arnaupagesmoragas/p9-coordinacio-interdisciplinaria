# Llar amb suport Sant Andreu · Sistema intern de seguiment

Aplicació web estàtica per al seguiment intern de la Llar amb suport Sant Andreu.

L’eina permet ordenar el funcionament quotidià del recurs a partir de quatre espais principals de treball:

- Diari de seguiment
- Registre d’incidències
- Reunions de coordinació
- Mediació

També incorpora apartats de suport documental vinculats al funcionament de la llar:

- Fitxes tècniques de les residents
- Fitxa de la llar
- Recursos del territori
- Consulta global
- Configuració

## Objectiu de l’eina

L’objectiu principal és facilitar la continuïtat professional dins del recurs, evitant que la informació quedi dispersa entre torns, converses informals o documents separats.

L’aplicació permet registrar, consultar i relacionar:

- seguiments ordinaris;
- incidències;
- reunions de coordinació;
- acords;
- revisions;
- processos de mediació;
- informació operativa de les residents;
- recursos externs vinculats al territori.

## Eines principals

### Diari de seguiment

Espai destinat a registrar l’evolució quotidiana de les residents.

Cada entrada permet diferenciar:

- observació;
- valoració professional;
- actuació realitzada;
- pendent o pla de seguiment.

### Registre d’incidències

Espai destinat a registrar fets no ordinaris que poden afectar la convivència, la seguretat, la salut, l’accessibilitat o la continuïtat del suport.

Cada incidència permet identificar:

- data i hora;
- resident o grup afectat;
- àmbit;
- nivell o estat;
- actuació immediata;
- seguiment posterior;
- relació amb altres registres.

### Reunions de coordinació

Espai destinat a documentar reunions internes, reunions de cas, reunions extraordinàries o revisions funcionals.

Cada reunió permet deixar constància de:

- motiu de la reunió;
- professionals implicades;
- situació revisada;
- acords;
- responsables;
- terminis;
- data de revisió.

### Mediació

Espai destinat al seguiment del procés de mediació vinculat al cas de convivència entre Sara i Laura.

Inclou:

- resum del cas;
- antecedents;
- necessitats de cada part;
- sessió de mediació;
- acords assolits;
- seguiment posterior;
- traçabilitat del procés.

## Suport documental

L’aplicació també inclou informació contextual del recurs:

- descripció de la llar;
- distribució dels espais;
- assignació d’habitacions;
- normativa de convivència;
- tasques domèstiques;
- distribució dels dinars;
- recursos del territori;
- mapa interactiu;
- fitxes operatives de les residents.

## Funcionament tècnic

Aquesta és una aplicació web estàtica creada amb:

- HTML
- CSS
- JavaScript

No necessita servidor ni base de dades externa.

Les dades creades o modificades dins l’aplicació es guarden localment al navegador mitjançant `localStorage`.

## Ús local

Per obrir l’aplicació en local, només cal obrir el fitxer:

```text
index.html
