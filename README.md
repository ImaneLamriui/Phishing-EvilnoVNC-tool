# Phishing-EvilnoVNC-tool
🕵🏻‍♀️ EvilnoVNC: HERRAMIENTA UTILIZADA EN PHISHING AVANZADO ⚠️

En mis últimas pruebas de herramientas de phishing en local, he estado analizando hashtag#EvilnoVNC, una herramienta que permite algo muy engañoso:

▪️EvilnoVNC permite hashtag#bypass de hashtag#2FA usando un navegador real dentro de un entorno controlado por el atacante: 👉 hace que la víctima use un navegador que está dentro del sistema del atacante, pero ella cree que es su navegador normal.
▪️ Funciona como un entorno de “hashtag#Browser_in_the_Browser”(escritorio remoto) vía hashtag#VNC en navegador”, donde la víctima interactúa con páginas legítimas (login, webs reales) pero todo pasa dentro del entorno controlado por el atacante.

**Nota: esta herramienta corre completamente dentro de un contenedor hashtag#Docker

En mi laboratorio, ejecutándolo en hashtag#Kali Linux, al iniciar se abrió hashtag#Chromium dentro del contenedor. Ese navegador funciona igual que uno normal y permite ver todas las acciones del usuario, capturar credenciales, hashtag#cookies y hashtag#sesiones.
La víctima cree que navega normalmente, pero en realidad todo está siendo monitorizado. No nota ninguna diferencia.

Mientras tanto, desde la otra parte (por ejemplo en la prueba local, desde http://localhost), el atacante puede ver todas las acciones que realiza en tiempo real usando la vista VNC.

Por eso es tan importante:
 ▪️ no permitir accesos remotos no solicitados
 ▪️ desconfiar si algo “se abre solo”

Solo ingeniería social: ⚠️ “abre este enlace”, “te ayudo remotamente”, etc.⚠️

💭 EvilnoVNC es una herramienta técnicamente compleja-->mezcla un navegador embebido con VNC. Justo porque no muestra señales visibles, es tan potente como peligrosa.
