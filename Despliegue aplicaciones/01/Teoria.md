
# Nombre de Dominio
Se trata del nombre único que se muestra después del signo *@* en las direcciones de correo y después de www. en las direcciones web

 
# Niveles de Dominio
El nivel de dominio en internet se refiere a la estructura jerárquica de los nombres de dominio, que va desde el dominio más específico hasta el más general.
## Niveles jerárquicos
### Dominio de tercer nivel (TLD): El más alto, como .com o .es.
### Dominio de segundo nivel (SLD): El nombre específico del sitio web, como openwebinars.
### Subdominios: Partes adicionales antes del dominio principal.
 

 # Zonas de búsqueda
## Zonas de búsqueda directa son más comunes y utilizadas en interacciones diarias con clientes.
## Zonas de búsqueda inversa son cruciales para administradores de red y análisis de seguridad.


 # Tipos de búsqueda
## La búsqueda directa es más común y utilizada en interacciones diarias con clientes.
## La búsqueda inversa es fundamental para administradores de red y análisis de seguridad.

 
# Tipos de servidores
## Servidores web
Alojan programas y datos solicitados por usuarios a través de internet o intranet y responden a solicitudes de páginas web y otros servicios web. Ejemplos comunes incluyen Apache, IIS y Nginx.
## Servidores de correo
Aceptan, almacenan y proporcionan mensajes de correo electrónico solicitados por clientes.
## Servidores virtuales
Software que se ejecuta en uno o más dispositivos informáticos físicos y se utilizan comúnmente en la nube para alojar aplicaciones y servicios.
## Servidores compartidos
Otorgan espacio para guardar información y comparten recursos como RAM, CPU, sistema operativo, conectividad y dirección IP. Útiles para recibir solicitudes de muchos clientes, pero con limitaciones en el número simultáneo de peticiones.
## Servidores de archivos e impresión
Almacenan archivos y aceptan trabajos de impresión de los clientes para enviarlos a una impresora conectada.
## Servidores basados en hardware
Son ordenadores más grandes y potentes que equipos cliente y generalmente tienen más memoria y espacio en disco. Estos se almacenan en salas de servidores y racks.
## Servidores de base de datos
Manejan y gestionan bases de datos para almacenar y recuperar información.


# Registros
## A (Address):
### Devuelve una dirección IP IPv4.
### Sirve para resolver nombres de alojamientos a números IPv4.
## AAAA (Address IPv6):
### Similar al registro A, pero devuelve direcciones IP IPv6.
## CNAME (Canonical Name):
### Crea alias de nombres.
### Puede apuntar a otro dominio o subdominio.
## MX (Mail Exchange):
### Apunta al servidor de correo del dominio.
### Se pueden establecer múltiples registros con prioridades.
## NS (Name Server):
### Indica los servidores de nombres autorizados para un dominio.
Los registros DNS son fundamentales para la funcionalidad y configuración de dominios en internet, permitiendo mapear nombres de dominio a direcciones IP y servicios específicos.


# Funcionamiento 
## Consulta recursiva 
### Ocurre entre el cliente y su servidor DNS local.
### El servidor DNS local realiza consultas a otros servidores DNS en nombre del cliente.
### Procesa consultas recursivamente hasta obtener una respuesta completa.
### Retorna la respuesta completa al cliente.
### Es más fácil de configurar pero puede ser menos eficiente.

## Consulta iterativa
### Ocurre entre el servidor DNS local y otros servidores DNS.
### El cliente realiza consultas directamente a varios servidores DNS.
### Puede recibir referencias hasta encontrar la información solicitada.
### No requiere resolución de nombres ya que cualquier servidor DNS puede proporcionar la resolución si lo sabe.
### Puede ser más eficiente en algunos casos.

