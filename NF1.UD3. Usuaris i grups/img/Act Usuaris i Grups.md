# NF1.UD3. Usuaris i grups-Maxim Slobodyan
<br>
<br>
<br>
<br>

## Tasca 1. Creació de la jerarquia de grups
<br>
<br>

![](/NF1.UD3.%20Usuaris%20i%20grups/img/1.png)

![](/NF1.UD3.%20Usuaris%20i%20grups/img/2.png)

Creació de grups de sistema i comprovació dels grups de l'usuari actual.
<br>
<br>

## Tasca 2. Gestió dels perfils d'usuari
<br>
<br>

![](/NF1.UD3.%20Usuaris%20i%20grups/img/3.png)

![](/NF1.UD3.%20Usuaris%20i%20grups/img/4.png)

Configuració de la plantilla /etc/skel/ amb una carpeta de documents i un àlies predeterminat.

<br>

![](/NF1.UD3.%20Usuaris%20i%20grups/img/5.png)

![](/NF1.UD3.%20Usuaris%20i%20grups/img/6.png)

Visualització del fitxer de configuració del paquet adduser (/etc/adduser.conf).

<br>

![](/NF1.UD3.%20Usuaris%20i%20grups/img/7.png)

![](/NF1.UD3.%20Usuaris%20i%20grups/img/8.png)

![](/NF1.UD3.%20Usuaris%20i%20grups/img/9.png)

Creació de l'usuari prova22, verificació del seu directori personal i prova d'inici de sessió.

<br>

![](/NF1.UD3.%20Usuaris%20i%20grups/img/13.png)

![](/NF1.UD3.%20Usuaris%20i%20grups/img/14.png)

Eliminació de l'usuari prova22 amb el seu directori i actualització manual des d'skel.

<br>
<br>

## Tasca 3. Creació i configuració d'usuaris
<br>
<br>

![](/NF1.UD3.%20Usuaris%20i%20grups/img/15.png)

![](/NF1.UD3.%20Usuaris%20i%20grups/img/16.png)

Creació dels usuaris pau_dev i laura_dev amb paràmetres específics.

<br>

![](/NF1.UD3.%20Usuaris%20i%20grups/img/17.png)

![](/NF1.UD3.%20Usuaris%20i%20grups/img/25.png)

Creació dels usuaris marc_sys i auditor amb useradd i assignació de contrasenyes amb chpasswd.

<br>

![](/NF1.UD3.%20Usuaris%20i%20grups/img/18.png)

![](/NF1.UD3.%20Usuaris%20i%20grups/img/19.png)

Forçament de canvi de contrasenya.

<br>
<br>

## Tasca 4. Inspecció del sistema i fitxers de configuració
<br>
<br>

![](/NF1.UD3.%20Usuaris%20i%20grups/img/20.png)

Visualització dels UID, GID i grups de l'usuari marc_sys.

<br>
<br>

### Quina diferència hi ha entre la informació de l'usuari pau_dev a /etc/passwd i la informació del fitxer /etc/shadow? Quin tipus de permisos té el fitxer /etc/shadow i per què?
<br>

Diferència: /etc/passwd guarda les dades públiques de l'usuari, mentre que /etc/shadow guarda la contrasenya xifrada i la seva caducitat.

Permisos i motiu: Té permisos de lectura restrictius només per a root per motius de seguretat, evitant que ningú pugui veure els hashes per intentar desxifrar les contrasenyes.

<br>
<br>

### Quin és el directori plantilla que s'utilitza per omplir el /home d'un usuari nou quan es crea? Quina comanda o fitxer en defineix aquesta configuració?
<br>
<br>

	Directori plantilla: /etc/skel
Fitxers que ho defineixen: /etc/default/useradd i /etc/adduser.conf.

<br>
<br>

## Tasca 5. Manteniment, bloqueig i eliminació

<br>
<br>

![](/NF1.UD3.%20Usuaris%20i%20grups/img/21.png)

![](/NF1.UD3.%20Usuaris%20i%20grups/img/22.png)

![](/NF1.UD3.%20Usuaris%20i%20grups/img/23.png)

![](/NF1.UD3.%20Usuaris%20i%20grups/img/24.png)

![](/NF1.UD3.%20Usuaris%20i%20grups/img/26.png)

Bloqueig i desbloqueig de la contrasenya de pau_dev, comprovació a /etc/shadow i eliminació de l'usuari auditor.

<br>
<br>

## Tasca 6. Personalització de l'entorn d'usuari
<br>
<br>

![](/NF1.UD3.%20Usuaris%20i%20grups/img/27.png)

![](/NF1.UD3.%20Usuaris%20i%20grups/img/28.png)

![](/NF1.UD3.%20Usuaris%20i%20grups/img/29.png)

![](/NF1.UD3.%20Usuaris%20i%20grups/img/30.png)

Instal·lació de la shell fish, canvi de shell per a laura_dev i comprovació de l'entorn.
