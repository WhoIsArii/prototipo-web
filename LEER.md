
# LEER IMPORTANTE

## prototipo (FALTA NOMBRE)

---
### Ideas 

 **zona caliente:**
 * *Forma:* 
    La forma de esta zona caliente sera como una **onda
    transversal** en el agua que cambiara de tamaño de 
    menor tamaño a gran tamaño abarcando la zona que
    este en mas "peligro" o que tendrias que "evitar"

 * *Estilo*
    El Color de esta dependera de los factores de la zona, 
    los colores van a variar entre esta tanda de colores:
    Verde

 * *Factores* 
    \+ Mayor cantidad de puntos mayor peligro 
    \-- Menor cantidad de puntos menor peligro
    **(Tendriamos que detallar mas este apartado para mas eficacia)**
    Los factores que se tomaran en cuenta para 
    agrandar o achicar y cambiar el color de la onda seran:
    * Lejania:
        * Lugares poco poblados +1 punto 
        * Zonas de seguridad -5 puntos
    * Noticias:
        * Robo +2 puntos
        * Asesinato +4 puntos
    * Actividad:
        * Reciente +3 puntos
        * Viejas -1 punto 

**Nota: La zona caliente claramente desaparecera en caso de 
que no cumpla ningun factor mencionado anteriormente**


--- 
### Estructura del Sitio Web

Partes del Sitio Web en resumidas cuentas:

* Pagina principal
    
    * Header 
        * Logo
        * Links a Paginas
        * (modificar en caso de alguna idea mas)
    * Body 
        * idea del prototipo
        * presentacion del prototipo
        * objetivos a alcanzar
    * Footer 
        * Licencia 
        * Informacion extra (a checar)

* Pagina de mapa interactivo 

    * Header (**Mismo que pagina principal**)
    <br>
    * Mapa 3d que contendra estas caracteristicas:
        * Zoom in & out
        * Zona de peligro
        * Rotacion  
        <br>
    * Footer (**Mismo que pagina principal**)

* Pagina de foro

    * Header (**Mismo que pagina principal**)
    <br>
    * Foro global (A checar)
    * Usuarios y Administradores 
    <br>
    * Footer (**Mismo que pagina principal**)
    
---

## Estructura de carpetas e archivos

### public:
en esta se encontraran 
archivos como iconos
! **no** necesita proteccion !

### src:
esta carpeta principal contendra subcarpetas
como podrian ser:
* assets
* pages

### src / assets:
    Esta carpeta contendra subcarpetas
    que se usaran basicamente para guardar 
    tanto fuentes e imagenes que se puedan
    a llegar a utilizar globlamente dentro
    de las paginas web, ejemplo imagen de 
    un logo las fuentes y algun estilo css

### src / pages:
    Esta carpeta sera la que ayude del 
    manejo tanto de los scripts de las paginas
    como de los estilos de esta, tambien se podra
    guardar imagenes mas dedicadas a estas paginas
    que no se deberian de guardar en los assets globables

### .gitignore:
archivo que efectua en que como
su propio nombre lo dice ignore
a algunos archivos carpetas etc de
ser podera agregados en git

### index.html:
pagina principal, tiene que estar en esta 
parte de la jerarquia de carpetas debido
a su importancia en la ejecucion de la
paginas web

### package.json:
archivo que contiene informacion vital para npm,
el manejo de paquetes de 3ros en caso llegar
a usarlos, etc

