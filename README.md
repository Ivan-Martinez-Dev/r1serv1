
# ✨ RISERVI PRUEBA TECNICA ✨

Hola 👋, esta es una guia para dar conocimiento incial sobre como correr las diferentes pruebas.

### _Prueba 1_

En este caso opte por usar un entorno como XAMPP que permite usar PHP, para que funcione es necesario colocar el archivo problema1.php en la carpeta **htdocs** donde se tenga instalado XAMPP.

```bash
\xamp\htdocs
```
Una vez iniciado nuestro entorno apache con php

![alt text](https://i.imgur.com/IF1QOyu.png "Logo Title Text 1")

podemos ir a nuestro localhost en el navegador para ver el resultado
### _Prueba 2_

Para la prueba N°2 realice el ejercicio practico de hacerlo en una base de datos interna, asi que use XAMPP nuevamente pues tiene un sistema de bases de datos que puede ser usado,
cree la base datos y la informacion necesaria, y ejecute pruebas para dar solucion siguiendo las instrucciones propuestas.

#### _Inconvenientes_

En este apartado habia un dato especificamente que pertenece a ciudades y el pais estaba nulo, en caso de tener integridad referencial en las tablas, no podria haber un dato nulo, la idea de la integridad referencial seria evitar estos datos --> Como solucion faltaria crear un pais, en este caso Mexico. para que sea parte de la solucion.

![alt text](https://i.imgur.com/QkYaOTj.png "Logo Title Text 1")
### _Prueba 3_

En el caso de la prueba 3, decidi crear un proyecto en Vue y para ejecutarlo se deben seguir los siguientes comandos:

- Revisar si tenemos node instalado, pues dependeremos de el para realizar la instalacion del proyecto.

```bash
npm -v
```
Si no lo tenemos, debemos descargarlo y lo instalamos desde la pagina oficial de Node.js

- Tambien debemos instalar el cli de Vue con el siguiente comando:

```bash
npm install -g @vue/cli
```
- Una vez lo tengamos, debemos crear nuestro proyecto con el comando:

```bash
vue create riservi
```
> **Nota**: Es importante mencionar que este proyecto lo realizamos con la opción VUE 3 mientras creamos el proyecto.

- Cuando el proyecto este creado, debemos ir a la carpeta de nuestro proyecto creado y ejecutar el servidor para ver nuestro proyecto en el localhost.

```bash
npm run serve
```
- El contenido del archivo enviado debe ser pegado en la siguiente carpeta:

```bash
/src/App.vue
```
Una vez añadido el codigo podemos ver nuestra prueba ejecutandose en el localhost. 

Disfrutala 😎!!