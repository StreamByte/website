# Guia de Contribución

¿Quieres colaborar? ¡Qué crack!

Para asegurar una colaboración fluida y eficiente, sigue las siguientes directrices.

## Antes de contribuir

1. **Lee las guías:** 

1. Haz **fork** a este repositorio
   - Da clic en el botón de **fork** para crear una copia del proyecto.

2. Clona el repositorio forkeado localmente:

        git clone https://github.com/StreamByte/website.git

3. Crea una rama para tu contribución:

        git checkout -b nombre-de-tu-rama

4. Realiza los cambios siguiendo las guías de estilo y convenciones del proyecto.

   - Puedes ver el diseño en [Figma](https://www.figma.com/design/ZvkKIGeJNrgLf1ceCxRNSf/StreamByte?node-id=4279-2990&t=R167AOYKOrLduJoH-1)
   - O revisar el [DESIGN_SYSTEM.md](https://github.com/StreamByte/website/blob/main/DESIGN_SYSTEM.md)

5. Haz un Commit localmente con tus cambios:

       git add .
       git commit -m "Descripción de los cambios realizados"

6. Si el proyecto ha recibido actualizaciones desde que hiciste fork, puedes síncronizarlo:

        git remote add upstream https://github.com/StreamByte/website.git
        git pull upstream main

7. Luego de realizar los cambios, súbelos a tu fork en GitHub:

        git push origin nombre-de-tu-rama

8. Crea el Pull Request en GitHub:
    - En tu rama en GitHub, deberás ver una opción para crear una Pull Request, da clic y asegurate de dejar un título y descripción claros especificando cualquier información relevante        sobre tus cambios.

9. Espera revisión y feedback:
    - Los mantenedores del proyecto revisarán tus cambios y es posible que te hagan comentarios. Ajusta tus cambios de ser necesario.

10. Merge del Pull Request:
    - Una vez aceptemos tus cambios, los mantenedores harán el Merge en la rama principal.

###### ¡Con esto habrás contribuido exitosamente al desarrollo Front-End de StreamByte!

