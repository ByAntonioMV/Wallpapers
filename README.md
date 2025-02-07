Hola/Hi





Este es una comunidad

# Instalación de Arch Linux

<aside>
💡 En la década de 1940, el profesor de Cornell Walter Pauk desarrolló un nuevo sistema de toma de notas para ofrecer a los estudiantes universitarios una forma mejor de organizar, resumir y asimilar los conocimientos. Este sistema demostró ser una herramienta de aprendizaje increíblemente eficaz. A continuación te explicamos cómo usarlo en Notion.

</aside>

# Proceso de instalación

1. Cambiar el teclado a latam con el comando 1
2. Poner en español el sistema exportando el lenguaje a español con el comando 2
3. Sincronzar la base de datos en español con el comando 2
4. En caso que no se tenga internet 
    - Saber el nombre de nuestro dispositivo de red con el comando 4 y saldra el nombre del dispositivo
    - Encender el servicio de iwd con el 5to comando
    - Conectarse a la red con el 6to comando
    - siempre despues de hacer alguna instalacion siempre se debe de actualizar el sistema con: pacman -sy
5. Listar los discos con el 7mo comando

### Lista de comandos

| No | Comando |
| --- | --- |
| 1 | loadkeys la-latin1 |
| 2 | export LANG=es_ES.UTF-8 |
| 3 | pacman -Sy |
| 4 | ls /sys/class/net | grep w |
| 5 | systemctl start —now iwd.service |
| 6 | iwctl —passphrase ‘contraseña’ station “nombre del dispositivo” connect ‘nombre de la red’ |
| 7 | fdisk -l |
| 8 |  |
| 9 |  |
| 10 |  |
