# adb_backup
Este script ha sido creado para copiar todas las carpetas de la memoria del teléfono hacia la PC con un solo comando.

Todo lo que debe hacer es ejecutar el archivo `./.script/adb_save_script` para que comience a copiar cada carpeta desde su teléfono hacia la carpeta raíz del script.

Si desea ignorar algunas carpetas en la copia, debe agregarlas, línea por línea al archivo `./.script/ignored_folders`

Actualmente el path de la memoria del teléfono se encuentra constante en `/storage/emulated/0`

Para cambiar este path todo lo que debe hacer es editar la línea número `7` del archivo `./.script/adb_save_script` y definir la dirección a la cual usted desea hacer copia de seguridad.
