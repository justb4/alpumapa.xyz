---
title: App - StreetComplete
---
# StreetComplete App

![Logo](../assets/images/streetcomplete-logo.png)

*"[StreetComplete](https://streetcomplete.app/?lang=en) es un editor fácil de usar para OpenStreetMap, diseñado para teléfonos y tabletas Android. Se utiliza para topografía de campo.*

*La aplicación está diseñada específicamente para colaboradores ocasionales y principiantes, ya que no se requieren conocimientos previos de OpenStreetMap (como esquemas de etiquetado) para contribuir. Además, la aplicación incluye gamificación y estadísticas para presentar y animar a los usuarios a explorar el mundo de OpenStreetMap.*

Fuente: [OSM Wiki](https://wiki.openstreetmap.org/wiki/StreetComplete).

StreetComplete fue creado originalmente por [Tobias Zwick](https://wiki.openstreetmap.org/wiki/User:Westnordost) 
y posteriormente desarrollado con la ayuda de  [numerosos colaboradores](https://github.com/streetcomplete/StreetComplete/graphs/contributors)..

## Instalación

StreetComplete solo está disponible para Android (a través de Google Play o F-Droid). Sigue el enlace aquí:

* [StreetComplete Home](https://streetcomplete.app/?lang=en)

## Documentación

No existe un manual oficial, pero la aplicación es intuitiva. Sin embargo, existen varias fuentes de información, que hemos recopilado aquí:

* [The README](https://github.com/streetcomplete/StreetComplete/blob/master/README.md)
* [A FAQ](https://wiki.openstreetmap.org/wiki/StreetComplete/FAQ)
* [StreetComplete on OSM Wiki](https://wiki.openstreetmap.org/wiki/StreetComplete)
* [SC Forum/QA on GitHub](https://github.com/streetcomplete/StreetComplete/discussions)

## Uso

Primero, consulta el archivo Léame: [README](https://github.com/streetcomplete/StreetComplete/blob/master/README.md) (en inglés):

StreetComplete (SC) busca automáticamente lugares cercanos donde se necesita información adicional. Estos se presentan como "misiones" en el mapa. SC muestra estas "misiones" como marcadores en el mapa. Cada una de estas misiones se puede resolver in situ respondiendo a una pregunta sencilla. Por ejemplo, al tocar un marcador, podría aparecer la pregunta "¿Cómo se llama esta calle?" y un campo de texto para responder. Se muestran más ejemplos en las capturas de pantalla a continuación.


<figure markdown>
![StreetComplete Screenshots](../assets/images/streetcomplete-screenshots-1.jpg){ data-title="StreetComplete Screenshots" data-description="Source: https://github.com/streetcomplete/StreetComplete" }
<figcaption>StreetComplete Screenshots - Source: https://github.com/streetcomplete/StreetComplete</figcaption>
</figure>

Las respuestas del usuario se procesan automáticamente y se suben directamente a la base de datos de OSM.
Las modificaciones se envían en conjuntos de cambios relevantes mediante la cuenta de OSM del usuario.
Dado que la aplicación está diseñada para uso en campo, también puede funcionar sin conexión (mediante la 
configuración) y está optimizada para minimizar el consumo de datos.

Para facilitar el uso de la aplicación, las misiones se limitan a aquellas que se pueden responder 
mediante preguntas sencillas. Aquí está el [listo de preguntas posible](https://wiki.openstreetmap.org/wiki/StreetComplete/Quests).

!!! tip

    A veces te encontrarás con una situación en el campo que no puedes resolver directamente en StreetComplete. 
    Por ejemplo, un sendero podría haber sido eliminado o un edificio demolido.
    En estos casos, puedes dejar notas (e incluso fotos) vinculadas a la ubicación y resolverlas más tarde en 
    casa con un editor de OSM como iD o JOSM. ¡No olvides "resolver" la nota después!

¿Cómo crear una nota? En SC, mantén pulsado el punto donde quieres dejar la nota. También puedes seleccionar "Otras respuestas... | No lo sé" en la búsqueda y crear la nota allí.

[Aquí puedes ver las últimas notas de los Países Bajos](https://resultmaps.neis-one.org/osm-notes-country?c=Netherlands), o ver tus propias notas en tu perfil de usuario al iniciar sesión en openstreetmap.org.
### Modo equipo

Existe un modo de equipo para casos en los que varias personas inspeccionan la misma calle y desean evitar la duplicación de tareas.
Este modo podría probarse durante el taller.