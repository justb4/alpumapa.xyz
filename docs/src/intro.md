---
title: Intro - OSM Basics
---
# OSM Basics

This section explains the basic principles of OSM.

## History

OpenStreetMap was founded in 2004 by [Steve Coast](https://stevecoast.com/). 
Read more in the [History of OpenStreetMap](https://wiki.openstreetmap.org/wiki/History_of_OpenStreetMap).

## Exploring the OpenStreetMap Website

[Start with OSM on LearnOSM](https://learnosm.org/en/beginner/start-osm/)

## The OSM Data Model

See [Understanding OSM Data](https://wiki.openstreetmap.org/wiki/Beginners_Guide_1.3).

In the OSM data model, geometries are central.  
Think of points, lines, areas, and combinations thereof.

These geometries are called **Elements** in OSM.  
Each Element is assigned properties, sometimes referred to as metadata, in the form of **Tags**.

The Elements in OSM terminology are:

* **[Node](https://wiki.openstreetmap.org/wiki/Node)** (think: points)  
* **[Way](https://wiki.openstreetmap.org/wiki/Way)** (think: lines)  
* **[Closed Way](https://wiki.openstreetmap.org/wiki/Way#Closed_way)** and **[Area](https://wiki.openstreetmap.org/wiki/Way#Area)** (think: open and filled areas, polygons)  
* **[Relation](https://wiki.openstreetmap.org/wiki/Relation)**, combinations of Elements, e.g., hiking routes. We will not cover this here.  
* Each Element has a **[unique 64-bit integer Id](https://wiki.openstreetmap.org/wiki/64-bit_Identifiers)**.

Instead of models and schemas with attributes, like in GML, OSM uses **Tagging**:

* Each Element (see above) is described with one or more **Tags**.  
* A Tag is a `key=value` pair.  
* For example, for a Way: `highway=residential` or for a parking lot (Closed Way): `amenity=parking`.  
* Within OSM, there is "ongoing" consensus via the [Wiki](https://wiki.openstreetmap.org/wiki/Tags) on the set of Tags to use.  
* Some OSM editors, like iD, use presets for Tags to assist users.  
* See the [detailed explanation](https://wiki.openstreetmap.org/wiki/Tags).  
* OSM implicitly recognizes [Map Features](https://wiki.openstreetmap.org/wiki/Map_features) through tagging.

!!! tip

    The TagInfo website/app at [taginfo.openstreetmap.org](https://taginfo.openstreetmap.org/) provides detailed information about the use of tags.  
    The tags used specifically in the Netherlands can be found at [taginfo.geofabrik.de/europe/netherlands](https://taginfo.geofabrik.de/europe/netherlands).  
    Specific tagging conventions for the Netherlands: [Wiki NL:Kaartelementen](https://wiki.openstreetmap.org/wiki/NL:Kaartelementen).  
    Every tag, whether it's a key or a key=value, can be found on the OSM Wiki. For example, [amenity=hospital](https://wiki.openstreetmap.org/wiki/Tag:amenity%3Dhospital).

## Creating an Account

We ask participants to do this in advance (via email) to save time.  
Registration is easy via [www.openstreetmap.org/user/new](https://www.openstreetmap.org/user/new).  
You don’t necessarily have to use your real name as your username, also known as an "OSM handle." This can be changed later.  
Additionally, your home location doesn’t need to be your actual address. That, too, can be adjusted later.

## iD Editor

This is the default editor available on openstreetmap.org.  
When you [log in](https://www.openstreetmap.org/login), you’ll see an 'Edit' button in the top left corner. Clicking this will open the iD Editor.  
The background map will then change, usually to the most detailed aerial imagery. In the Netherlands, this is the PDOK aerial imagery with 8cm resolution.

We will only cover the basics of the iD Editor.
!!! tip

    You can add a custom background map in iD, for example from Catastre. Go to Layers and then "Custom..."  
    In a form, you can insert a symbolic URL, for example, a layer from Top10NL.  
    Here’s an example for the "Spanish Cadastral Parcel Web Map Service of the Directorate General of Cadastre according INSPIRE profile" Buildings Layer
    layer, which you can copy-paste:  
    `https://ovc.catastro.meh.es/cartografia/INSPIRE/spadgcwms.aspx?REQUEST=GetMap&SERVICE=WMS&VERSION=1.3.0&FORMAT=image/png&TRANSPARENT=true&LAYERS=BU.Building&CRS={proj}&STYLES=&WIDTH={width}&HEIGHT={height}&BBOX={bbox}`
    But beware: Spain buildings and addresses import should be done via 
    the [Buildings and Addresses import guidelines](https://wiki.openstreetmap.org/wiki/Spanish_Cadastre/Buildings_import)!

## Community

* [OSM Forum](https://community.openstreetmap.org)
* [Spanish Community on OSM Forum](https://openstreetmap.es)
* [Spain Landing Page on OSM Wiki](https://wiki.openstreetmap.org/wiki/ES:Espa%C3%B1a)
* [OpenStreetMap Spain Telegram Group](https://www.t.me/OSMES)

The main communication channel for the Spanish Community is its [open Telegram Group](https://www.t.me/OSMES).

!!! tip

    With your OSM account, you automatically have access to the OSM Forum.

## More Information

* [OSM Wiki](https://wiki.openstreetmap.org/)  
* [Start with OSM on LearnOSM](https://learnosm.org/en/beginner/start-osm/) (the English version is slightly more up-to-date)

**Continue to [Organic Maps](apps/organic.md)!**
