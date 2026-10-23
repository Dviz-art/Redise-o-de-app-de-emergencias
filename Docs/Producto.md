## Fundamentos de Ingeniería en Software - entrega 1

# Nombre del proyecto
## Security

# Equipo
| Nombre            | Rol        |
|-------------------|------------|
| David Chin        | Lider      |

# Problemática
Cuando una persona se siente en peligro, no siempre cuenta con una forma rápida, discreta y confiable de avisar a alguien de confianza dónde está, y las opciones actuales no se adaptan a ese momento. Situaciones como sentirse seguido, caminar solo por la noche o viajar en transporte público con desconocidos pueden generar una sensación de inseguridad sin llegar necesariamente a justificar una llamada inmediata a los servicios de emergencia.
En esos casos, desbloquear el teléfono, abrir una aplicación y buscar el botón correcto consume tiempo valioso, y una alerta con sonido o pantalla llamativa puede empeorar la situación frente a quien representa el riesgo.

# Objetivo
El objetivo del proyecto es crear una aplicación móvil de seguridad personal que permita a los  usuarios avisar a sus contactos de confianza cuando se sienten en peligro, compartiendo su ubicación junto con un mensaje de emergencia que el propio usuario configuró previamente, de forma rápida y discreta. Para que pedir ayuda no alargue el tiempo en un momento crítico, las funciones principales estarán disponibles desde un widget en la pantalla de inicio del dispositivo o a través de la misma app. De manera secundaria, la app permitirá abrir el marcador del dispositivo móvil con el número de emergencia ya escrito, sin realizar la llamada de forma automática, de modo que el usuario decide si la confirma.

# Alcance
El alcance del proyecto es elaborar un aplicación móvil en la que el usuario podrá crear una cuenta, iniciar y cerrar sesión, recuperar su contraseña, registrar contactos de confianza, configurar un único mensaje de emergencia, compartir su ubicación junto con ese mensaje. También contará con un widget de acceso rápido y con un botón para abrir el marcador de emergencias con el número prellenado. Incluso todos los avisos se envían sin sonido ni pantalla llamativa, y el usuario recibe solo una confirmación sutil. Para evitar avisos accidentales, el envío a contactos y la apertura del marcador tendrán una cuenta regresiva cancelable. Los avisos se asocian a cuentas, tanto el usuario como sus contactos deben registrarse; al cerrar sesión, el dispositivo deja de recibir avisos y el widget se desactiva. La aplicación solo funciona con conexión a internet; si no la hay, se lo indica claramente al usuario. Por el momento el proyecto se centrara en los requisitos, alcances, limitaciones y más artefactos.

# Limitaciones
Se requiere una cuenta para usar la aplicación, tanto para quien envía avisos como para quien los recibe. Todas las funciones ocurren dentro de la aplicación, con una sola excepción: el botón de emergencias, que abre el marcador del teléfono con el número prellenado y, por lo tanto, saca al usuario de la app. La aplicación no realiza llamadas por sí sola: el usuario es quien decide llamar. Para recibirlos, los contactos deben tener la aplicación instalada, y el envío requiere conexión a internet. Su funcionamiento requiere permisos del dispositivo (ubicación, contactos y notificaciones), y la precisión de la ubicación depende del GPS y de la cobertura.

# Usuarios/Clientes
El proyecto está dirigido a personas que, en algún momento, puedan encontrarse en una situación de riesgo, como estudiantes que regresan a casa, trabajadores con turnos nocturnos, usuarios del transporte público o personas que transitan por zonas poco concurridas o durante la noche.

Usuarios Primarios: Estudiantes, trabajadores, usuarios frecuentes del transporte público, personas que transitan solas y personas entre 16 y 60 años que quieren mejorar su seguridad personal.

Usuarios secundarios: Los contactos de confianza los cuales recibirán el aviso y la ubicación del usuario primario (familiares, amistades o pareja).

# Propuesta de valor
El proyecto consiste en crear una aplicación móvil de seguridad personal que permite al usuario avisar a sus contactos de confianza que se siente en peligro, compartiendo su ubicación junto con un mensaje que el propio usuario configuró previamente. El aviso puede enviarse en uno o dos toques, desde la app o desde un widget en la pantalla de inicio, y de forma discreta, sin sonido ni pantalla llamativa. Con todo esto se busca que pedir ayuda sea rápido, sencillo y discreto en el momento en que más se necesita.

Antes de enviarse, el aviso pasa por una cuenta regresiva cancelable, de modo que el usuario puede detenerlo si ya se siente seguro o si lo activó por accidente. Por ahora los avisos llegan a los contactos como notificaciones de la propia app, donde ven el mensaje y la ubicación en un mapa; para ello, tanto el usuario como sus contactos crean una cuenta e inician sesión. Además, la app ofrece la opción de abrir el marcador del teléfono con el número de emergencia (911) ya escrito, sin realizar la llamada de forma automática, para evitar llamadas accidentales o de broma que saturen las líneas de emergencia. Por ahora, el usuario configurara un único mensaje, reservado para situaciones de emergencia, para que quien lo reciba entienda de inmediato que se trata de un aviso serio.

Esta propuesta responde a un problema real: en situaciones de riesgo, llamar al 911 no siempre es la respuesta inmediata, y desbloquear el teléfono y buscar una aplicación consume tiempo valioso. Está dirigida a personas que se desplazan solas, como estudiantes, trabajadores con turnos nocturnos y usuarios del transporte público de Yucatán.
