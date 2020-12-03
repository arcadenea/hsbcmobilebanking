# HSBC Mobile Banking Argentina - Android
Esta es una serie de instrucciones para hacer funcionar la app HSBC Mobile Banking en Argentina, especialmente para el soporte de dispositivo de seguridad digital, en reemplazo del antiguo Token que se utilizaba para validar las operaciones. El soporte de la misma no es muy bueno, por lo que agrego estas notas para aquellos que no han podido instalarla.


## Aplicación
Pueden encontrar la aplicación en la siguiente dirección (Google Play Store)
https://play.google.com/store/apps/details?id=com.htsu.hsbcpersonalbanking&hl=es_AR&gl=US


## Instalación
La aplicación está en el app store de Google, pero al parecer solamente se indicó que soporta dispositivos con Android 7, por lo que no deja descargarla desde otras versiones del sistema operativo. Una opción es descargarla desde algún mirror del app store (hay varias páginas y aplicaciones para esto, queda a cargo del lector buscarlas). El nombre de la app es "com.htsu.hsbcpersonalbanking".


## Reinstalar la aplicación ó cambiar de dispositivo
Si se reinstaló la aplicación y se borraron los datos antiguos ó se cambió de dispositivo, la misma no permitirá utilizarse como dispositivo de seguridad, indicando que ya se instaló en otro dispositivo. La solución propuesta es llamar a un 0-800 para solicitar el cambio de dispositivo. Otra opción es, previo backup de la aplicación original, copiar algunas carpetas internas de la aplicación (es necesario tener un dispositivo rooteado). Las carpetas y archivos a copiar son los siguientes:

- shared_prefs
- app_webview
- cache
- databases

Los datos de la aplicación se ubican en /data/data/com.htsu.hsbcpersonalbanking/
