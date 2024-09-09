# Secumint
SecuMint: Máquina Virtual de OSINT para Auditoria y Pentesting

SecuMint: Máquina Virtual de OSINT para Auditoria y Pentesting

Introducción
En la ciberseguridad, la necesidad de herramientas robustas y accesibles para realizar auditorías y recolección de información se ha vuelto crucial. SecuMint es una máquina virtual creada específicamente para satisfacer estas necesidades en el ámbito de la autoría y el pentesting en OSINT. Basada en Linux Mint 21.3 "Virginia", SecuMint no solo centraliza una amplia gama de herramientas esenciales, sino que también organiza y facilita su uso mediante una interfaz gráfica personalizada.
Este artículo explorará en profundidad las características, herramientas instaladas, y la implementación de SecuMint, destacando su utilidad para los profesionales de la ciberseguridad.
 
 ![image](https://github.com/user-attachments/assets/d737f3d1-79c8-4c89-b073-079d8ef1bb99)

![image](https://github.com/user-attachments/assets/247d81e5-3172-4954-9855-bc37eaddd7b5)

Estructura y Características de SecuMint
Base en Linux Mint 21.3 "Virginia"
SecuMint utiliza Linux Mint 21.3 como base, una distribución popular por su seguridad, estabilidad y facilidad de uso. Esto garantiza que SecuMint sea accesible tanto para principiantes como para profesionales experimentados en ciberseguridad.

Personalización y Entorno
Uno de los aspectos más destacados de SecuMint es su alto grado de personalización y la creación de un entorno atractivo y funcional para los usuarios.
Fondos de Pantalla Personalizados: Para darle un toque único y diferenciador, SecuMint ha sido visualmente personalizada con una serie de fondos de pantalla y fotografías relacionadas con SecuMint, brindando una experiencia de usuario envolvente y enfocada en la identidad de la máquina.

![image](https://github.com/user-attachments/assets/15048c86-112c-4aa1-8efd-00c98c5db28d)
 
Programa Con Interfaz Gráfica Personalizada (GUI)
Una de las innovaciones más notables de SecuMint es el desarrollo de un programa con interfaz gráfica (GUI) diseñado para simplificar la gestión de las herramientas. Este programa permite a los usuarios navegar de manera intuitiva a través de las diferentes fases del proceso de auditoría, eligiendo entre herramientas locales y herramientas web según sus necesidades. Este programa organiza las herramientas en fases clave del proceso de ciberseguridad:
•	Fase 1: Recolección de Información
•	Fase 2: Análisis de Infraestructura
•	Fase 3: Identificación de Vulnerabilidades
•	Fase 4: Explotación
•	Fase 5: Post-Explotación y Análisis
•	Fase 6: Reporte y Remediación
•	Buscadores Generalistas
Funcionalidades del Programa GUI
•	Selección de Fases: Al iniciar el programa, el usuario puede seleccionar entre las fases 1 a 6, además de una opción adicional para Buscadores Generalistas. Esta organización asegura que los usuarios puedan enfocarse en la fase específica de su trabajo, optimizando el proceso de auditoría.
•	Tipo de Herramienta: Una vez seleccionada una fase, el usuario puede elegir entre utilizar una aplicación local o una herramienta web, brindando flexibilidad y adaptabilidad según las necesidades del proyecto.
•	Descripción y Ejemplos: Para cada herramienta seleccionada, ya sea local o web, el programa ofrece una pequeña descripción junto con un botón para "Ver Detalles". Al hacer clic en este botón, se despliega una guía básica que incluye la descripción completa de la herramienta, los comandos principales o ejemplos de uso para herramientas locales, o una explicación del funcionamiento y usos de las herramientas web.
•	Interacción con Herramientas Web: Para las herramientas web, el programa incluye un botón "Abrir Página Web" que, al hacer clic, abre automáticamente la herramienta en Firefox, permitiendo al usuario interactuar directamente con la herramienta seleccionada desde el navegador.
•	Interacción con Herramientas Locales: Si se selecciona una herramienta local, el programa ofrece un botón "Abrir CLI" que abre una terminal de comandos lista para ejecutar la herramienta seleccionada. Esta funcionalidad asegura que las herramientas locales se integren de manera fluida con el entorno de la máquina virtual, proporcionando una experiencia de usuario sin interrupciones.

 ![image](https://github.com/user-attachments/assets/4ab95036-3a22-48c6-b083-a95afdab0345)
 
![image](https://github.com/user-attachments/assets/0fb593bf-503b-4579-b32b-56521ae563b1)

![image](https://github.com/user-attachments/assets/1cc1bbce-6f95-4be8-a850-90750e03d4d6)


Herramientas Instaladas y Organización
SecuMint viene preconfigurada con una selección exhaustiva de herramientas esenciales para la auditoria y pentesting, todas organizadas de manera lógica y centralizadas para facilitar su acceso. A continuación, se detallan las herramientas incluidas:
•	Herramientas Instaladas
o	Nmap: Escáner de red utilizado para descubrir hosts y servicios en una red.
o	Metasploit Framework: Plataforma para el desarrollo y ejecución de exploits contra máquinas remotas.
o	Nikto: Escáner de vulnerabilidades web que identifica problemas de seguridad comunes en aplicaciones web.
o	Wireshark: Analizador de protocolos de red que permite capturar y examinar datos en tiempo real.
o	John the Ripper: Herramienta de crackeo de contraseñas.
o	Hydra: Herramienta de fuerza bruta para atacar contraseñas en múltiples protocolos.
o	Burp Suite: Herramienta integrada para la realización de pruebas de seguridad en aplicaciones web.
o	Sqlmap: Herramienta para la automatización de inyecciones SQL y toma de control de servidores de bases de datos.
o	Maltego: Herramienta de visualización de relaciones entre entidades como personas, empresas y dominios.
o	Recon-ng: Framework modular para la recolección de información similar a Metasploit.
o	The Harvester: Herramienta para la recolección de correos electrónicos, subdominios, hosts y direcciones IP.
o	Dirb: Herramienta para la detección de directorios y archivos ocultos en servidores web.
o	Dnsenum: Herramienta para la enumeración de DNS.
o	Dnsrecon: Herramienta de recolección de información de DNS, capaz de realizar varios tipos de consultas DNS.
o	Enum4linux: Herramienta para la enumeración de información en sistemas Windows.
o	Masscan: Escáner de puertos extremadamente rápido.
o	Netdiscover: Herramienta para la detección de direcciones IP en una red local.
o	Setoolkit (Social Engineering Toolkit): Herramienta para realizar ataques de ingeniería social.
o	ZAP (OWASP Zed Attack Proxy): Herramienta para encontrar vulnerabilidades en aplicaciones web.
o	Ettercap: Herramienta para realizar ataques Man-in-the-Middle (MITM) en una red.


•	Herramientas Web
SecuMint también incluye accesos directos a una variedad de herramientas web organizadas por fases dentro de los marcadores de Firefox:
o	Archive.is: Servicio de archivado de páginas web.
o	Baidu: Motor de búsqueda de China.
o	Bing: Motor de búsqueda de Microsoft.
o	Browserling: Servicio para probar sitios web en diferentes navegadores y sistemas operativos.
o	Censys: Motor de búsqueda que permite encontrar dispositivos conectados a Internet.
o	CVE Details: Base de datos de vulnerabilidades conocidas.
o	Dnsdumpster: Herramienta de inteligencia de DNS.
o	Duplichecker: Herramienta para la detección de plagio.
o	Exploit-DB: Base de datos de exploits públicos.
o	FotoForensics: Herramienta para analizar la autenticidad de imágenes.
o	Google: Motor de búsqueda más utilizado a nivel mundial.
o	Google Imágenes: Herramienta de búsqueda de imágenes de Google.
o	Hunter.io: Servicio para encontrar direcciones de correo electrónico asociadas a un dominio.
o	IG Downloader: Herramienta para descargar contenido de Instagram.
o	IPinfo: Servicio para obtener información sobre direcciones IP.
o	IP-API: API para obtener datos de geolocalización de una IP.
o	IP2Location: Servicio de geolocalización de direcciones IP.
o	Internet Archive: Herramienta para acceder a versiones archivadas de sitios web.
o	Mailinator: Servicio de correo electrónico temporal.
o	Namechk: Herramienta para verificar la disponibilidad de nombres de usuario en varias plataformas.
o	Packet Storm Security: Base de datos de exploits y herramientas de seguridad.
o	Robtex: Herramienta de inteligencia de red y análisis de DNS.
o	SearchFTPs: Motor de búsqueda para encontrar archivos en servidores FTP.
o	Shodan: Motor de búsqueda para dispositivos conectados a Internet.
o	TinEye: Herramienta de búsqueda inversa de imágenes.
o	URLscan: Servicio que analiza el contenido y los metadatos de una URL.
o	ViewDNS: Herramienta para la realización de diversas consultas DNS.
o	VirusTotal: Servicio de análisis de archivos y URLs para detectar malware.
o	Vulners: Base de datos de vulnerabilidades y exploits.
o	Webmii: Herramienta para encontrar información sobre personas en Internet.
o	Whois: Servicio para obtener información sobre la propiedad de un dominio.
o	Yandex: Motor de búsqueda de origen ruso.
o	Yandex Images: Herramienta de búsqueda de imágenes de Yandex.
o	ZoomEye: Motor de búsqueda para encontrar dispositivos conectados a Internet.


Organización de Marcadores en Firefox
Bookmarks Organizados en Firefox: En el navegador Firefox, se ha creado una organización meticulosa de los marcadores, distribuidos en carpetas específicas que corresponden a las fases del proceso de auditoría y ciberseguridad. Esta organización facilita el acceso rápido y eficiente a las herramientas web necesarias para cada etapa del proceso:
•	Fase 1: Recolección de Información: Carpeta con enlaces a herramientas web para la fase inicial de recolección de datos.
•	Fase 2: Análisis de Infraestructura: Carpeta con marcadores para herramientas web enfocadas en el análisis de la infraestructura objetivo.
•	Fase 3: Identificación de Vulnerabilidades: Carpeta con accesos a herramientas web diseñadas para identificar vulnerabilidades en sistemas y redes.
•	Fase 4: Explotación: Contiene marcadores para herramientas web utilizadas en la fase de explotación.
•	Fase 5: Pos-explotación y Análisis: Incluye enlaces a herramientas que facilitan la fase de análisis posterior a la explotación.
•	Fase 6: Reporte y Remediación: Carpeta con herramientas para la generación de informes y propuestas de remediación.
•	Buscadores Generalistas: Una carpeta separada que contiene enlaces a motores de búsqueda especializados en OSINT.

 ![image](https://github.com/user-attachments/assets/6b6d2c32-a44c-4eef-b290-3cd64334d967)

![image](https://github.com/user-attachments/assets/f88359dd-37b1-49ff-96ab-6b396869b801)

 
Esta estructura no solo organiza las herramientas por fases, sino que también permite a los usuarios navegar de manera intuitiva a través de las diferentes etapas del proceso de auditoría, optimizando su flujo de trabajo.


Conclusión

SecuMint es más que una simple máquina virtual; es una plataforma integral que reúne las mejores herramientas de OSINT y pentesting en un entorno accesible y bien organizado. Con su interfaz gráfica personalizada, organización lógica de herramientas, y accesibilidad universal, SecuMint es una herramienta indispensable para cualquier profesional de la ciberseguridad.
SecuMint facilita no solo el acceso a una amplia gama de herramientas, sino que también optimiza el flujo de trabajo, desde la recolección de información hasta la generación de informes detallados, todo dentro de un entorno diseñado para maximizar la productividad y la eficiencia.

