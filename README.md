# examenDAM


# Explicación de los pasos

1. Primero entro al repositorio que quiero clonar. En el apartado <> Code copio el link.
Me posiciono dentro de la consola en donde quiero que se cree la carpeta al clonarlo.

Utilizo el comando:
    - "git clone -o nombreQueLeQuieroDar 'enlace'" -> Comando para clonar el repositorio de otra persona a mi ordenador

2. Una vez hecho esto, creo mi repositorio en github, y añado la nueva carpeta con el comando
    - "git remote add origin 'enlace'"" -> Comando para añadir la carpeta clonada a mi repositorio remoto

3. Modifico el Readme.

Ejecuto los comandos:
    - "git add README.md" -> Comando para añadir el archivo modificado que quiero subir a mi repositorio remoto
    - "git commit -m "mensaje"" -> Comando para añadir el mensaje que va fijado al cambio que hice, tiene que ser un mensaje corto y descriptivo de los cambios
    - "git push -u origin main" -> Comando para subir los cambios junto al commit a mi repositorio remoto
escribo mi cuenta y mi token.

4. Copio un programa que ya tenga hecho o creo uno nuevo dentro de la carpeta del repositorio remoto. Accedo a la carpeta src para encontrar el archivo Main.java, y repito los comandos del paso 3, pero añadiendo Main.java en vez de README.md

5. Vuelvo a editar el README para escribir los pasos, y vuelvo a repetir el paso 3.
