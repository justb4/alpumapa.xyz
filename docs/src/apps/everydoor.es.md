---
title: App - EveryDoor
---

# Aplicación EveryDoor

![Logo](../assets/images/everydoor-logo.png)

[EveryDoor](https://every-door.app/) es un editor móvil de código abierto diseñado para añadir o modificar "Puntos de Interés" (POIs), 
como tiendas y otros servicios ("amenities"), así como números de calle, de una manera muy fácil de usar para OpenStreetMap.

Esta aplicación está especialmente pensada para ayudar a los usuarios a mantener actualizados los servicios ("amenities") y tiendas, 
y para realizar el llamado "micro-mapeo". Esto incluye detalles como árboles, paneles informativos, papeleras e hidrantes.  
No todos estos objetos aparecen en los mapas estándar de OSM, pero al añadirse a la base de datos de OSM, pueden usarse para desarrollar mapas o apps especializados.

EveryDoor [se desarrolla en GitHub](https://github.com/zverik/every_door) por [Ilya Zverev](https://www.openstreetmap.org/user/Zverik), 
un miembro destacado de la comunidad OSM que ha contribuido a múltiples apps y aspectos de OSM desde 2010.

Ilya también fue invitado en [The Great Geo Show Episodio 15 - Especial OpenStreetMap](https://tv.osgeo.nl/episode/episode-0015/).

## Instalación

[EveryDoor](https://every-door.app/) está disponible para Android e iOS. Consulta los siguientes enlaces:

* Android: [Google Play](https://play.google.com/store/apps/details?id=info.zverev.ilya.every_door)
* Android: [F-Droid](https://f-droid.org/packages/info.zverev.ilya.every_door/)
* iOS: [AppStore](https://apps.apple.com/app/every-door/id1621945342)

## Uso

El uso de la app es mayormente autoexplicativo.  
Necesitas una cuenta OSM activa.  
Puedes introducirla desde el menú en la esquina superior izquierda de la pantalla principal, accediendo a la pantalla de Configuración.  
Arriba verás "Cuenta OSM". El resto de ajustes por ahora no son relevantes.

Hay una pantalla principal para cada actividad, dependiendo de la categoría de objetos que quieras mapear.  
Hay cuatro "Modos" en total, entre los que puedes cambiar usando los botones del menú inferior, como se muestra a continuación.  
Además, siempre puedes descargar datos de OSM con el botón en el extremo izquierdo.  
Si has hecho cambios, la flecha de este botón apuntará hacia arriba.  
En ese caso, puedes usarlo para subir todos tus cambios a OSM.  
Lo mejor es guardar los cambios y enviarlos como un único "changeset".

<figure markdown>
![EveryDoor: Menú inferior](../assets/images/everydoor-bottom-menu.png){ data-title="EveryDoor: Menú inferior" data-description="EveryDoor: Menú inferior" }
<figcaption>EveryDoor: Menú inferior</figcaption>
</figure>

Una vez que empieces a mapear, el "Botón de descarga" apuntará hacia arriba. Esto significa que hay cambios de datos que puedes subir directamente a OSM.  
NB: debes hacerlo manualmente; no se suben automáticamente (como sí ocurre con StreetComplete).

### Pantalla 1 - Servicios - Modo Micromapeo

Por ejemplo: mobiliario urbano, árboles, etc. Usa el botón `+` para añadir elementos en la ubicación del marcador negro.  
Desplaza la pantalla para mover el marcador negro a la posición deseada.

<figure markdown>
![EveryDoor: Pantalla de Micromapeo](../assets/images/everydoor-micromapping-screen.png){ data-title="EveryDoor: Pantalla de Micromapeo" data-description="EveryDoor: Pantalla de Micromapeo" }
<figcaption>EveryDoor: Pantalla de Micromapeo</figcaption>
</figure>

### Pantalla 2 - Tiendas, Restaurantes, etc. - Modo POI

Cada número en el mapa corresponde a un POI en la lista. Usa el botón `+` para añadir elementos en la ubicación del marcador negro.

<figure markdown>
![EveryDoor: Pantalla de Tiendas](../assets/images/everydoor-shops-screen.png){ data-title="EveryDoor: Pantalla de Tiendas" data-description="EveryDoor: Pantalla de Tiendas" }
<figcaption>EveryDoor: Pantalla de Tiendas</figcaption>
</figure>

### Pantalla 3 - Direcciones y Edificios

Puedes editar etiquetas de edificios y direcciones. Toca una dirección o edificio para editarlo, o usa el botón de "Casa" abajo a la izquierda o el botón de "Dirección"  
abajo a la derecha.  
Usa el marcador negro para seleccionar la dirección o edificio. Esto tiene el mismo efecto que pulsar directamente.

<figure markdown>
![EveryDoor: Pantalla de Direcciones](../assets/images/everydoor-addresses-screen.png){ data-title="EveryDoor: Pantalla de Direcciones" data-description="EveryDoor: Pantalla de Direcciones" }
<figcaption>EveryDoor: Pantalla de Direcciones</figcaption>
</figure>

### Pantalla 4 - Modo Notas

Aquí puedes añadir una [Nota OSM](https://wiki.openstreetmap.org/wiki/Notes) estándar asociada a una ubicación.  
Usa el botón azul de "Nota" abajo a la derecha para añadir una nota en la ubicación del marcador negro.  
Es una herramienta muy útil para añadir observaciones para ti o para otros, como errores que encuentres y no puedas corregir desde EveryDoor, o como "recordatorio" para editarlos más tarde con otro editor como iD o JOSM.  
Puedes encontrar tus propias notas en tu perfil en openstreetmap.org.

<figure markdown>
![EveryDoor: Pantalla de Notas](../assets/images/everydoor-notes-screen.png){ data-title="EveryDoor: Pantalla de Notas" data-description="EveryDoor: Pantalla de Notas" }
<figcaption>EveryDoor: Pantalla de Notas</figcaption>
</figure>

Aquí tienes algunos enlaces adicionales que pueden ayudarte a usar la app:

* [OSM Wiki Every_Door](https://wiki.openstreetmap.org/wiki/Every_Door)  
* [Sesión tutorial de Ilya en Tanzania - Video](https://www.youtube.com/watch?v=q7OscecqUJY)

## Introducción en video por Ilya Zverev

![type:video](https://www.youtube.com/embed/oQao9KgC5f8)

**Continúa con la [Aplicación inteligente StreetComplete](streetcomplete.md)!**