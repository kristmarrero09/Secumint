# **SecuMint**

**SecuMint: Máquina Virtual de OSINT para Auditoría y Pentesting**

---

## **Introducción**

En la ciberseguridad, la necesidad de herramientas robustas y accesibles para realizar auditorías y recolección de información se ha vuelto crucial. **SecuMint** es una máquina virtual creada específicamente para satisfacer estas necesidades en el ámbito de la auditoría y el pentesting en OSINT. Basada en **Linux Mint 21.3 "Virginia"**, SecuMint no solo centraliza una amplia gama de herramientas esenciales, sino que también organiza y facilita su uso mediante una interfaz gráfica personalizada.

Este artículo explorará en profundidad las características, herramientas instaladas y la implementación de SecuMint, destacando su utilidad para los profesionales de la ciberseguridad.

---

![Image](https://github.com/user-attachments/assets/d737f3d1-79c8-4c89-b073-079d8ef1bb99)

![Image](https://github.com/user-attachments/assets/247d81e5-3172-4954-9855-bc37eaddd7b5)

---

## **Estructura y Características de SecuMint**

### **Base en Linux Mint 21.3 "Virginia"**

SecuMint utiliza **Linux Mint 21.3** como base, una distribución popular por su seguridad, estabilidad y facilidad de uso. Esto garantiza que SecuMint sea accesible tanto para principiantes como para profesionales experimentados en ciberseguridad.

### **Personalización y Entorno**

Uno de los aspectos más destacados de **SecuMint** es su alto grado de personalización y la creación de un entorno atractivo y funcional para los usuarios.

- **Fondos de Pantalla Personalizados:** Para darle un toque único y diferenciador, SecuMint ha sido visualmente personalizada con una serie de fondos de pantalla y fotografías relacionadas con SecuMint, brindando una experiencia de usuario envolvente y enfocada en la identidad de la máquina.

![Image](https://github.com/user-attachments/assets/15048c86-112c-4aa1-8efd-00c98c5db28d)

---

## **Programa Con Interfaz Gráfica Personalizada (GUI)**

Una de las innovaciones más notables de **SecuMint** es el desarrollo de un programa con interfaz gráfica (**GUI**) diseñado para simplificar la gestión de las herramientas. Este programa permite a los usuarios navegar de manera intuitiva a través de las diferentes fases del proceso de auditoría, eligiendo entre herramientas locales y herramientas web según sus necesidades.

Este programa organiza las herramientas en fases clave del proceso de ciberseguridad:

- **Fase 1:** Recolección de Información
- **Fase 2:** Análisis de Infraestructura
- **Fase 3:** Identificación de Vulnerabilidades
- **Fase 4:** Explotación
- **Fase 5:** Post-Explotación y Análisis
- **Fase 6:** Reporte y Remediación
- **Buscadores Generalistas**

### **Funcionalidades del Programa GUI**

- **Selección de Fases:** Al iniciar el programa, el usuario puede seleccionar entre las fases 1 a 6, además de una opción adicional para Buscadores Generalistas. Esta organización asegura que los usuarios puedan enfocarse en la fase específica de su trabajo, optimizando el proceso de auditoría.
- **Tipo de Herramienta:** Una vez seleccionada una fase, el usuario puede elegir entre utilizar una aplicación local o una herramienta web, brindando flexibilidad y adaptabilidad según las necesidades del proyecto.
- **Descripción y Ejemplos:** Para cada herramienta seleccionada, ya sea local o web, el programa ofrece una pequeña descripción junto con un botón para "Ver Detalles". Al hacer clic en este botón, se despliega una guía básica que incluye la descripción completa de la herramienta, los comandos principales o ejemplos de uso para herramientas locales, o una explicación del funcionamiento y usos de las herramientas web.
- **Interacción con Herramientas Web:** Para las herramientas web, el programa incluye un botón "Abrir Página Web" que, al hacer clic, abre automáticamente la herramienta en Firefox, permitiendo al usuario interactuar directamente con la herramienta seleccionada desde el navegador.
- **Interacción con Herramientas Locales:** Si se selecciona una herramienta local, el programa ofrece un botón "Abrir CLI" que abre una terminal de comandos lista para ejecutar la herramienta seleccionada. Esta funcionalidad asegura que las herramientas locales se integren de manera fluida con el entorno de la máquina virtual, proporcionando una experiencia de usuario sin interrupciones.

![Image](https://github.com/user-attachments/assets/4ab95036-3a22-48c6-b083-a95afdab0345)

![Image](https://github.com/user-attachments/assets/0fb593bf-503b-4579-b32b-56521ae563b1)

![Image](https://github.com/user-attachments/assets/1cc1bbce-6f95-4be8-a850-90750e03d4d6)

---

## **Herramientas Instaladas y Organización**

**SecuMint** viene preconfigurada con una selección exhaustiva de herramientas esenciales para la auditoría y pentesting, todas organizadas de manera lógica y centralizadas para facilitar su acceso. A continuación, se detallan las herramientas incluidas:

- **Herramientas Instaladas:**
  - **Nmap:** Escáner de red utilizado para descubrir hosts y servicios en una red.
  - **Metasploit Framework:** Plataforma para el desarrollo y ejecución de exploits contra máquinas remotas.
  - **Nikto:** Escáner de vulnerabilidades web que identifica problemas de seguridad comunes en aplicaciones web.
  - **Wireshark:** Analizador de protocolos de red que permite capturar y examinar datos en tiempo real.
  - **John the Ripper:** Herramienta de crackeo de contraseñas.
  - **Hydra:** Herramienta de fuerza bruta para atacar contraseñas en múltiples protocolos.
  - **Burp Suite:** Herramienta integrada para la realización de pruebas de seguridad en aplicaciones web.
  - **Sqlmap:** Herramienta para la automatización de inyecciones SQL y toma de control de servidores de bases de datos.
  - **Maltego:** Herramienta de visualización de relaciones entre entidades como personas, empresas y dominios.
  - **Recon-ng:** Framework modular para la recolección de información similar a Metasploit.
  - **The Harvester:** Herramienta para la recolección de correos electrónicos, subdominios, hosts y direcciones IP.
  - **Dirb:** Herramienta para la detección de directorios y archivos ocultos en servidores web.
  - **Dnsenum:** Herramienta para la enumeración de DNS.
  - **Dnsrecon:** Herramienta de recolección de información de DNS, capaz de realizar varios tipos de consultas DNS.
  - **Enum4linux:** Herramienta para la enumeración de información en sistemas Windows.
  - **Masscan:** Escáner de puertos extremadamente rápido.
  - **Netdiscover:** Herramienta para la detección de direcciones IP en una red local.
  - **Setoolkit (Social Engineering Toolkit):** Herramienta para realizar ataques de ingeniería social.
  - **ZAP (OWASP Zed Attack Proxy):** Herramienta para encontrar vulnerabilidades en aplicaciones web.
  - **Ettercap:** Herramienta para realizar ataques Man-in-the-Middle (MITM) en una red.

---

### **Herramientas Web**

SecuMint también incluye accesos directos a una variedad de herramientas web organizadas por fases dentro de los marcadores de Firefox:

- **Herramientas Web:**
  - **Archive.is:** Servicio de archivado de páginas web.
  - **Baidu:** Motor de búsqueda de China.
  - **Bing:** Motor de búsqueda de Microsoft.
  - **Browserling:** Servicio para probar sitios web en diferentes navegadores y sistemas operativos.
  - **Censys:** Motor de búsqueda que permite encontrar dispositivos conectados a Internet.
  - **CVE Details:** Base de datos de vulnerabilidades conocidas.
  - **Dnsdumpster:** Herramienta de inteligencia de DNS.
  - **Duplichecker:** Herramienta para la detección de plagio.
  - **Exploit-DB:** Base de datos de exploits públicos.
  - **FotoForensics:** Herramienta para analizar la autenticidad de imágenes.
  - **Google:** Motor de búsqueda más utilizado a nivel mundial.
  - **Google Imágenes:** Herramienta de búsqueda de imágenes de Google.
  - **Hunter.io:** Servicio para encontrar direcciones de correo electrónico asociadas a un dominio.
  - **IG Downloader:** Herramienta para descargar contenido de Instagram.
  - **IPinfo:** Servicio para obtener información sobre direcciones IP.
  - **IP-API:** API para obtener datos de geolocalización de una IP.
  - **IP2Location:** Servicio de geolocalización de direcciones IP.
  - **Internet Archive:** Herramienta para acceder a versiones archivadas de sitios web.
  - **Mailinator:** Servicio de correo electrónico temporal.
  - **Namechk:** Herramienta para verificar la disponibilidad de nombres de usuario en varias plataformas.
  - **Packet Storm Security:** Base de datos de exploits y herramientas de seguridad.
  - **Robtex:** Herramienta de inteligencia de red y análisis de DNS.
  - **SearchFTPs:** Motor de búsqueda para encontrar archivos en servidores FTP.
  - **Shodan:** Motor de búsqueda para dispositivos conectados a Internet.
  - **TinEye:** Herramienta de búsqueda inversa de imágenes.
  - **URLscan:** Servicio que analiza el contenido y los metadatos de una URL.
  - **ViewDNS:** Herramienta para la realización de diversas consultas DNS.
  - **VirusTotal:** Servicio de análisis de archivos y URLs para detectar malware.
  - **Vulners:** Base de datos de vulnerabilidades y exploits.
  - **Webmii:** Herramienta para encontrar información sobre personas en Internet.
  - **Whois:** Servicio para obtener información sobre la propiedad de un dominio.
  - **Yandex:** Motor de búsqueda de origen ruso.
  - **Yandex Images:** Herramienta de búsqueda de imágenes de Yandex.
  - **ZoomEye:** Motor de búsqueda para encontrar dispositivos conectados a Internet.

---

## **Organización de Marcadores en Firefox**

En el navegador **Firefox**, se ha creado una organización meticulosa de los marcadores, distribuidos en carpetas específicas que corresponden a las fases del proceso de auditoría y ciberseguridad. Esta organización facilita el acceso rápido y eficiente a las herramientas web necesarias para cada etapa del proceso:

- **Fase 1:** Recolección de Información: Carpeta con enlaces a herramientas web para la fase inicial de recolección de datos.
- **Fase 2:** Análisis de Infraestructura: Carpeta con marcadores para herramientas web enfocadas en el análisis de la infraestructura objetivo.
- **Fase 3:** Identificación de Vulnerabilidades: Carpeta con accesos a herramientas web diseñadas para identificar vulnerabilidades en sistemas y redes.
- **Fase 4:** Explotación: Contiene marcadores para herramientas web utilizadas en la fase de explotación.
- **Fase 5:** Pos-Explotación y Análisis: Incluye enlaces a herramientas que facilitan la fase de análisis posterior a la explotación.
- **Fase 6:** Reporte y Remediación: Carpeta con herramientas para la generación de informes y propuestas de remediación.
- **Buscadores Generalistas:** Una carpeta separada que contiene enlaces a motores de búsqueda especializados en OSINT.

![Image](https://github.com/user-attachments/assets/6b6d2c32-a44c-4eef-b290-3cd64334d967)

![Image](https://github.com/user-attachments/assets/f88359dd-37b1-49ff-96ab-6b396869b801)

---

## **Conclusión**

**SecuMint** es más que una simple máquina virtual; es una plataforma integral que reúne las mejores herramientas de **OSINT** y **pentesting** en un entorno accesible y bien organizado. Con su interfaz gráfica personalizada, organización lógica de herramientas y accesibilidad universal, **SecuMint** es una herramienta indispensable para cualquier profesional de la ciberseguridad.

**SecuMint** facilita no solo el acceso a una amplia gama de herramientas, sino que también optimiza el flujo de trabajo desde la recolección de información hasta la generación de informes detallados, todo dentro de un entorno diseñado para maximizar la productividad y la eficiencia.

---

## **Descarga del .iso**

Contactame al correo kristmarrero@hotmail.com o a mi linkedin para brindarte la .iso https://www.linkedin.com/in/kristophermarrero/.
