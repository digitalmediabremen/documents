# Directions for Technical Documentations of Installations and Tech Riders

## Technical Documentation of Projects

In general, it is recommended to document the full hard- and software stack of your projects to adapt, recreate and repair them in the future.

- archive parts/components (e.g., cad + 3d files to repair or recreate all elements of a particular work)
- note part/model numbers and where you have ordered them. make a BOM
- archive source code and comment your code
- write detailed README.md files ;)
- make backups; sometimes even full raspberry pi images.
- a git repository can be an excellent way to track changes and distribute them on different devices.
- document critical parts of the installation process (photos and screenshots)
- try to make the installation of your work as easy as possible. (Ideally, it should work without you)
- try to avoid *dirty* hacks ;)
- have a lookg at the [Directions for Marking Save and Stable Installations](Directions_for_Marking_Save_and_Stable_Installations.md)

## Technical Riders

[Technical rider](https://en.wikipedia.org/wiki/Rider_(theater)#Technical_rider) have their origin in theater, dance, and live music events (sometimges they are called *stage rider*). They are a standard in the new media art world as well. They are requested and sent to the museum/institution at the beginning of exhibition planning, often with the first inquiry. They help the exhibitor to verify and confirm that they have the spatial, technical, and financial resources to exhibit a piece according to its requirements defined in the technical rider. Ideally, the tech rider answers all questions to the exhibitor. A *negotiation* process often starts to adapt the work to the particular spatial/exhibition situation. Finally, the venue’s technical team uses the tech rider to prepare/build the setting according to the rider, ideally before the arrival of the artist or assistants to install it. Previous describes a perfect scenario. But unfortunately, tech riders are often not read carefully or not even at all, making setups a f*cking nightmare for the artist. ;(

This documents compiles a list of questions that guies you through the process of writing a propper tech rider.

### Descriptio
- formal and functional description of the work
- installtion shot

### Dimensions/Duration
- dimensions of the work `Lenght x Width x Height cm`
- if its a performance or video piece name the `duration in minutes`
- if exits form (e.g wood), dimesions and weight of the transport crates `Lenght x Width x Height cm` + `KG`

### Spatial Requirements
- how much floor/wall space is needed? `Lengt x Width m ` + `m²` 
- Does it need a separate room? 
- Does the work go well with daylight?
- or does it need a blackout room?
- wall color? `RAL <number>` [overview](https://www.ral-farben.de/en/all-ral-colours)
- maybe a light trap at the entrance?
- special floor requirements? concrete?
- add a floor plan/drawing of the installation to the rider.
- Does the work need modification of the space?
- does it hang from the ceiling? is it possible?
- humidity?


### Technical Requirements to be provided by the Exhibition/Venue?
- [mains power](https://en.wikipedia.org/wiki/Mains_electricity) e.g. `220V / 50hz / max 16 amps`
- plug system? [Schuko](https://en.wikipedia.org/wiki/Schuko), French, British, US
- do you need [earthing](https://en.m.wikipedia.org/wiki/Earthing_system)/ground/[Schutzleiter](https://de.wikipedia.org/wiki/Schutzleiter)?
- remember that’s not common outside of Europe, North America, and parts of East Asia)
- [example of a not so well done mains power extension](https://photos.app.goo.gl/xEAfmE82VwtSfs2R7)
- does it need audio tech? what speakers/PA is it exactly?
- does it need a network (ethernet/wifi) connection?
- does it need a projector (what resolution/lumen etc.)? `4k 6000 Lumens`
- best is to name the exact model. Looks professional, but in most cases, you get something else ;(

### Consumables
- do you need consumables for the installation?
- things that can't be shipped because they are marked as dangerous? e.g chemicals, gasses etc
- e.g. cable ties?

### Componets (technological and others) to be provided by the Artist (shipped)
- make a list of all components (eventually document every single part/element photographically)
- parts/packing list are often requires for custom declartions 

### Lighting
- what kind of light setting is required for optimal presentation. spots, wall washer, profiles?

### Sound / Audio
- is it a loud piece?
- does it interfere with surrounding works?
- does it needs its own acoustic space?

### Installation
- materials like tools, monitor, tables, charis needed for the installation preocess.

### Transport Requirements
- consider different transport option
- try to make packaging small and light
- in general, transport is covered by the exhibitor
- build crates (only sometimes comes by the exhibitor)
- make them ready for international shipping ( ISPM 15)
- check custom situation for countries outside EU / maybe a [Carnet ATA](https://en.wikipedia.org/wiki/ATA_Carnet) (passport for goods is needed)


### Setup / Installation
- how long do you need for the installation
- do you have to do the installation by yourself?
- do you need an assisting person for the installation, and for how long?


### Maintenance
- what is needed to run the installation over a longer period? Wear of materials? cleaning?
- make a manual for the task.
- eventually, train a staff member of the institution.

### Operation Manual
- how to turn the piece on and off?
- define the order in which the different parts are started.
- how to fix common errors?
- another chapter is usability: make it easy for the staff (that might not be technically skilled) to start and stop the work. make autostart scripts, autologin, etc.


### Dismantling and Packing Guide
- make a detailed packing guide to make sure nothing gets broken while dismantling it.


## Resources

- Best practices for conservation of media art (Rafael Lozano-Hemmer)
[link](https://github.com/antimodular/Best-practices-for-conservation-of-media-art)

- some of [@rlfbckr](https://github.com/rlfbckr/) tech riders + guides
[link](https://drive.google.com/drive/folders/180cgY8QufPIBlDxNgju6u0dyK-2E21Qy?usp=sharing)
