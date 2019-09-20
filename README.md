# [Traccar](https://www.traccar.org)

## Instrucciones para instalar

1. Ejecutar el siguiente git clone: `git clone --recursive https://github.com/SoftwareProyect/traccar-server.git`
2. Importar el proyecto. Existen tres herramientas, a continuación los procesos de importación en ellas: [Netbeans](https://www.traccar.org/build-in-netbeans/), [IntelliJ](https://www.traccar.org/build-in-intellij-idea/) o consola de comandos.

# Instrucción para trabajar encima del proyecto
Usaremos un estandar de Git llamado Git Flow:
![Git Flow](https://3.bp.blogspot.com/-K7fGmmH0kI8/WkHMyoUy3nI/AAAAAAAACA0/oU4PdlbrD_wMY5qerk4h-Btz4eiZH5zogCLcBGAs/s640/03%2B%25282%2529.png)

El primer paso es crear una rama que se derive de la rama `develop`:

## ¿Cómo nombrar a la rama?
`feature-verbo infinitivo principal-complemento...`
Ejemplo:
`feature-cambiar-interfaz-login`

## ¿Cómo subo mi código?
1. Primero haciendo un commit `git commit -m 'Mensaje del commit'`.
2. Luego `git push` y copiar el comando que sugiere git para publicar la nueva rama.

## ¿Qué hago después subir?
1. Se debe hacer un Pull Request de la rama subida hacia `develop`.
2. Asignar la revisión del PR al Ing. Diego.
3. Esperar la revisión del PR.💪

## License

    Apache License, Version 2.0

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
