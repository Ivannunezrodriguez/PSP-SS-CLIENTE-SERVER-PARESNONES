
PSP-SS-CLIENTE-SERVER-PARESNONES
Este proyecto es una aplicación desarrollada en Java, como parte de las actividades del módulo de Programación de Servicios y Procesos (PSP). La aplicación implementa un juego de "Pares o Nones" utilizando una arquitectura cliente-servidor basada en sockets.

🧠 Descripción
La aplicación permite a dos clientes conectarse a un servidor central para jugar al clásico juego de "Pares o Nones". Cada cliente elige una cantidad de dedos (número) y una opción (par o non). El servidor recibe las elecciones de ambos clientes, calcula la suma de los números y determina el ganador según las reglas del juego.

📁 Estructura del Proyecto
objectivec
Copiar
Editar
PSP-SS-CLIENTE-SERVER-PARESNONES/
├── ClienteParesNones.java
├── HiloEscuchadorParesNones.java
├── ServidorParesNones.java
├── readme.txt
└── .gitattributes
ClienteParesNones.java: Implementación del cliente que permite al usuario conectarse al servidor, enviar sus elecciones y recibir los resultados del juego.

HiloEscuchadorParesNones.java: Clase que maneja la comunicación del cliente con el servidor en un hilo separado, permitiendo la recepción asíncrona de mensajes.

ServidorParesNones.java: Implementación del servidor que gestiona las conexiones de los clientes, recibe sus elecciones y determina el resultado del juego.

readme.txt: Archivo de documentación adicional.

🚀 Instrucciones de Ejecución
Clonar el repositorio:

bash
Copiar
Editar
git clone https://github.com/Ivannunezrodriguez/PSP-SS-CLIENTE-SERVER-PARESNONES.git
Compilar los archivos Java:

Navega a la carpeta del proyecto y compila los archivos .java:

bash
Copiar
Editar
javac *.java
Ejecutar el servidor:

En una terminal, ejecuta:

bash
Copiar
Editar
java ServidorParesNones
Ejecutar los clientes:

En otras terminales (una por cliente), ejecuta:

bash
Copiar
Editar
java ClienteParesNones
Cada cliente podrá ingresar su elección y ver el resultado del juego.

🛠️ Tecnologías Utilizadas
Java: Lenguaje de programación principal.

Sockets: Para la comunicación en red entre cliente y servidor.

Programación Concurrente: Uso de hilos para manejar múltiples conexiones de clientes simultáneamente.

📄 Licencia
Este proyecto se distribuye bajo la licencia MIT. Consulta el archivo LICENSE para más detalles.

👨‍💻 Autor
Iván Núñez Rodríguez - GitHub
