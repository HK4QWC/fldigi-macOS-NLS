# fldigi-macOS-NLS

fldigi-macOS-NLS es un repositorio para los archivos binarios de fldigi con soporte para NLS y compilados para **macOS Sierra**.

Aquí encontrará **[fldigi-3.23.21.dmg](https://github.com/HK4QWC/fldigi-macOS-NLS/blob/master/fldigi-3.23.21.dmg)** (2017-01-30) y **[fldigi-3.23.22.4.dmg](https://github.com/HK4QWC/fldigi-macOS-NLS/blob/master/fldigi-3.23.22.4.dmg)** (2017-02-13).

A la fecha, fldigi incluye los archivos de internacionalización para **español** (es), **francés** (fr), **italiano** (it), **polaco** (pl), **alemán** (de) and **neerlandés u holandés** (nl).

## Información importante

* Este repositorio se ha creado para el beneficio de los usuarios de fldigi que no usan inglés como su idioma primario que quieren ver los mensajes de la interfaz de usuario en su idioma nativo (si éste es soportado).
* Para activar este soporte, el código fuente descargado del sitio del proyecto de fldigi fué compilado **sin modificaciones** en un entorno macOS Sierra versión 10.12.3 activando el soporte NLS.
* Es posible que los binarios ofrecidos en este repositorio funcionen en versiones anteriores de macOS y OS X, pero no han sido verificadas. Por favor pruébelo en su sistema y déjeme saber si funciona.
* Es posible que encuentre algunos términos sin traducir.
* ,El proceso de traducción de fldigi es un trabajo en progreso realizado por voluntarios. Es posible que encuentre algunos términos sin traducir. 
* Si fldigi no soporta su idioma, por favor considere iniciar un proceso de traducción. Con gusto le orientaré en cómo hacerlo y así beneficiar a toda la comunidad de usuarios de fldigi.

## Configuración rápida y fácil

1. Descargue e instale [EnvPane](https://github.com/hschmidt/EnvPane), un panel de preferencias de OS X para manejar las variables de ambiente. Desarrollado por [Hannes Schmidt](https://diaryproducts.net/)
2. Descargue [fldigi-3.23.21.dmg](https://github.com/HK4QWC/fldigi-macOS-NLS/blob/master/fldigi-3.23.21.dmg) que es la versión estable actual o [fldigi-3.23.22.4.dmg](https://github.com/HK4QWC/fldigi-macOS-NLS/blob/master/fldigi-3.23.22.4.dmg) que es la versión alfa más reciente.
3. Abra el archivo DMG descargado y copie fldigi.app a la carpeta Aplicaciones de MacOS 
4. En el panel de preferencias EnvPanel, configure la variable LANGUAGE con el lenguaje deseado. Los posibles valores para esta variable son: _es_, _fr_, _it_, _pl_, _de_ y _nl_.
5. Ejecute fldig.app y, ¡disfrútelo en su idioma!
6. Recuerde revisar la configuración de fldigi, y asegúrese que el servidor Portaudio esté habilitado en "Configuración > Dispositivos de sonido > Dispositivos".

## Para tener en cuenta

* Si la variable _LANGUAGE_ es configurada con un valor no soportado, fldigi mostrará los mensajes en inglés.
* Si se reconfigura la variable _LANGUAGE_ mientras fldigi está funcionando, es necesario cerrar y volver a abrir fldigi.
* Si necesita soporte sobre la operación de fldigi en macOS le sugiero unirse al grupo [linuxham]https://groups.io/g/linuxham.

## Agradecimientos

* Dave Freese (W1HKJ) y al grupo de desarrolladores, colaboradores y traductores.
* Alberto Villegas Botero (HK4FZ) por inspirarme a hacer lo que amo. 
* Pavel Milanés Costa (CO7WT) por introducirme al fantástico mundo de la i18n de software de fuente abierta.
* Tomás Clemente (EA5ICX) por motivarme a solucionar este pequeño inconveniente de fldigi en macOS.

## Acerca de fldigi

Fldigi es un aplicativo de módem por software para uso de radioaficionados. Es un programa basado en tarjeta de audio usado para transmitir y recibir datos en cualquiera de los siguientes modos digitales:

```
* BPSK y QPSK          31, 63, 125, 250 (ambos), and 63F and 500 (solo BPSK)
* PSKR                 125, 250, y 500
* CW                   velocidades desde 5 a 200 palabras por minuto
* DominoEX             4, 5, 8, 11, 16 y 22; también con FEC
* Hellschreiber        Feld Hell, Slow Hell, Hell x5/x9, FSKHell(-105) y Hell 80
* MFSK                 4, 8, 11, 16, 22, 31, 32 y 64; la mayoría con soporte de imagen
* MT63                 500, 1000 y 2000
* OLIVIA               varios tonos y anchos de banda
* RTTY                 varias tasas de baudios, desplazamientos, número de bits de datos, etc.
* THOR                 4, 5, 8, 11, 16 y 22
* Throb y ThrobX       1, 2, y 4
* WWV                  solo recepción - calibre su tarjeta de audio con WWV
* Frequency Analysis   solo recepción - mida la frecuencia de una portadora
```

Fldigi puede controlar un transceptor usando Hamlib o RigCAT I/O, realizar búsquedas en línea o en cdrom en la base de datos de QRZ, registrar QSOs en el libro de guardia incorporado o con Xlog, y enviar reportes de recepción al sistema de reporte automático de propagación PSK.

La versión más reciente siempre estará disponible [http://www.w1hkj.com/](http://www.w1hkj.com/).

En esta página encontrará una extensa documentación y una colección de archivos XML para controlar los transceptores soportados por RigCAT.

El wiki contiene la lista de preguntas frecuentes FAQs, HOWTOs y enlaces a todos los recursos de fldigi [https://fedorahosted.org/fldigi/](https://fedorahosted.org/fldigi/).

El repositorio GIT se encuentra en [https://sourceforge.net/p/fldigi/fldigi/ci/master/tree/](https://sourceforge.net/p/fldigi/fldigi/ci/master/tree/).

Para obtener soporte, noticias y actualizaciones, inscríbase a alguna de las listas de correo o los grupos de discusión. Los anuncios de nuevas versiones estables se hacen en todas las listas y grupos; Las versiones de prueba solo se  anuncian en fldigi-alpha y fldigi-announce.

* Grupo linuxham: Discusiones generales sobre fldigi, software y otros temas relacionados con la radioafición [https://groups.io/g/linuxham](https://groups.io/g/linuxham).

* Grupo win-fldigi: Para usuarios de fldigi en Windows [http://groups.yahoo.com/group/win-fldigi/](http://groups.yahoo.com/group/win-fldigi/).

* Grupo NBEMSham: Grupo con especial enfoque en operaciones NBEMS (Narrow Band Emergency Messaging Software) [http://groups.yahoo.com/group/NBEMSham/](http://groups.yahoo.com/group/NBEMSham/). 

* Lista fldigi-alpha: Discusiones sobre pruebas de fldigi y temas relacionados [https://sourceforge.net/p/fldigi/mailman/fldigi-alpha/](https://sourceforge.net/p/fldigi/mailman/fldigi-alpha/).
    
* Lista fldigi-devel: Temas relacionados con el desarrollo de fldigi [https://sourceforge.net/p/fldigi/mailman/fldigi-devel/](https://sourceforge.net/p/fldigi/mailman/fldigi-devel/).
     
**Copyright (C) 2007-2010 Dave Freese, Stelios Bounanos, y otros.** Licencia GPLv3+: GNU GPL versión 3 or posterior [http://www.gnu.org/licenses/gpl-3.0.html](http://www.gnu.org/licenses/gpl-3.0.html)
