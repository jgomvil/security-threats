# Amenazas
# Express:
- Una vulnerabilidad: Cross-site Scripting (XSS)
- El paquete express en versiones anteriores a 3.11.0 y mayores o iguales a 4.0.0 pero menores a 4.5.0 es vulnerable a Cross-site Scripting (XSS). Las versiones afectadas no imponen un conjunto de caracteres específico en la cabecera content-type mientras muestran mensajes de respuesta del nivel 400, lo que podría ser aprovechado por atacantes remotos para realizar un ataque de script entre sitios utilizando codificaciones no estándar como UTF-7. Este tipo de ataque ocurre cuando el atacante engaña a una aplicación web legítima para aceptar una solicitud que parece provenir de una fuente confiable, permitiendo la ejecución de scripts maliciosos en el lado del cliente. 
# Sqlite3:
- Dos vulnerabilidades: Arbitrary Code Execution y Denial of Service (DoS)
- ACE: El paquete sqlite3 en versiones mayores o iguales a 5.0.0 y menores a 5.1.5 es vulnerable a la Ejecución de Código Arbitrario debido a una sanitización inadecuada en el método .ToString(). Esta vulnerabilidad permite la ejecución de código JavaScript arbitrario o la denegación de servicio (DoS) cuando un parámetro de enlace es un objeto manipulado.
- DoS: La versión afectada de este paquete (menor a 5.0.3) presenta una vulnerabilidad de Denegación de Servicio (DoS). La explotación de esta vulnerabilidad implica la invocación de la función toString del parámetro proporcionado. Si se le pasa un objeto de función no válido, se generará un error que puede resultar en la caída del motor V8.
# Angular:
- 1 Vulnerabilidad: Cross-site Scripting (XSS)
- El paquete @angular/core, en versiones afectadas entre <11.0.5 y >=11.1.0-next.0 <11.1.0-next.3, presenta una vulnerabilidad de Cross-site Scripting (XSS) durante el desarrollo con SSR habilitado. El XSS ocurre cuando un atacante engaña a una aplicación web legítima para aceptar una solicitud que parece provenir de una fuente confiable. Esto se logra al escapar del contexto de la aplicación web, que luego entrega esos datos a los usuarios junto con otro contenido dinámico de confianza, sin validarlos.
# Ionic:
-1 Vulnerabilidad: Cross-site Scripting (XSS)
-La vulnerabilidad de Cross-site Scripting (XSS) afecta a versiones de @ionic/core anteriores a la 4.0.3, 4.1.3, 4.2.1 y 4.3.1, permitiendo a un atacante ejecutar scripts maliciosos en un sitio web legítimo. Esta vulnerabilidad se debe a una sanitización inadecuada del innerHTML. En este caso es crítica.
