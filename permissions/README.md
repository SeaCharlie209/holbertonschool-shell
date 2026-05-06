# Shell, permissions

Este proyecto cubre la gestión de permisos, usuarios y grupos en sistemas Linux.

## Repositorio
* **GitHub repository:** `holbertonschool-shell`
* **Directory:** `permissions`

## Tasks List

A continuación se detalla la lista de tareas de este proyecto:

* **0. My name is Betty:** Script que cambia el usuario actual a `betty` (exactamente 8 caracteres).
* **1. Who am I:** Imprime el nombre de usuario efectivo actual.
* **2. Groups:** Imprime todos los grupos a los que pertenece el usuario actual.
* **3. New owner:** Cambia el propietario del archivo `hello` al usuario `betty`.
* **4. Empty!:** Crea un archivo vacío llamado `hello`.
* **5. Execute:** Añade permiso de ejecución al propietario del archivo `hello`.
* **6. Multiple permissions:** Añade ejecución al propietario y grupo, y lectura a otros usuarios al archivo `hello`.
* **7. Everybody!:** Añade permiso de ejecución a todos (propietario, grupo y otros) para el archivo `hello`.
* **8. James Bond:** Establece los permisos del archivo `hello` en `007` (sin permisos para dueño/grupo, todos para otros).
* **9. John Doe:** Establece los permisos del archivo `hello` en `753` (`-rwxr-x-wx`).
* **10. Look in the mirror:** Iguala los permisos del archivo `hello` a los del archivo `olleh`.
* **11. Directories:** Añade permiso de ejecución a todos los subdirectorios del directorio actual sin afectar archivos regulares.
* **12. More directories:** Crea un directorio llamado `my_dir` con permisos `751`.
* **13. Change group:** Cambia el grupo propietario del archivo `hello` a `school`.
* **14. Owner and group:** Cambia el dueño a `vincent` y el grupo a `staff` de todos los archivos y directorios del entorno de trabajo.
* **15. Symbolic links:** Cambia el dueño a `vincent` y grupo a `staff` del enlace simbólico `_hello`.
* **16. If only:** Cambia el propietario de `hello` a `vincent` solo si el dueño actual es `guillaume`.

---
*Nota: Todos los scripts deben ser ejecutables y cumplir con los requisitos de la corrección automática de Holberton.*
