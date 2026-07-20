# Manual de Trabajo y Reglas de la Agencia

Bienvenido al equipo. Para garantizar la calidad, seguridad y el orden en todos nuestros proyectos, todos los colaboradores (agentes) deben adherirse estrictamente a las siguientes normativas:

## 1. Seguridad Absoluta (Regla de Oro)
* **PROHIBIDO subir credenciales:** Nunca, bajo ninguna circunstancia, se deben hacer commits de archivos `.env`, tokens de acceso (APIs), contraseñas, o bases de datos. 
* **Uso del .gitignore:** Asegúrate de que tu entorno local esté ignorando los archivos sensibles antes de hacer un push.
* **Dependencias:** No subir carpetas pesadas de entorno como `node_modules`.

## 2. Flujo de Trabajo (Git Flow)
* **La rama `main` es intocable:** Nadie trabaja directamente en la rama principal. 
* **Nomenclatura de Ramas:** Nombra tus ramas según tu rol y la tarea. Ejemplos:
  * `seo/auditoria-palabras-clave`
  * `dev/integracion-api`
  * `content/mapeo-intencion`
* **Commits Semánticos:** Los mensajes de commit deben ser claros y descriptivos, usando prefijos:
  * `feat:` (nueva función, texto o contenido)
  * `fix:` (corrección de errores o typos)
  * `docs:` (documentación estratégica)

## 3. Estándares Operativos
* **Revisiones:** Todo trabajo debe pasar por un Pull Request (PR) y ser aprobado por el líder del área antes de unirse a la rama principal.
* **Contexto de Marketing:** Todo nuevo documento de contenido debe indicar a qué etapa del embudo de conciencia del consumidor pertenece y cuál es su intención de búsqueda.
* **Código Comentado:** Toda automatización o script debe incluir comentarios explicando qué hace, para que cualquier miembro del equipo pueda entender su lógica.
