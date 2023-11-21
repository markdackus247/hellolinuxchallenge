# Webserver (als developmentserver) 5 Sterren
![Ubuntu Live Server](../images/Ubuntu%20Live%20Server.png)


## Device
Voor het ontwikkelen van applicaties wordt een development-server gebruikt op basis van Ubuntu Live Server 22.04. Alle zelf gemaakte software moet hierop werken. Ook moet er een WordPress website op komen die voor intern gebruik is.

![BLX](../icons/blocks2d_icon_32x32.jpg) _2 Blocks_


## Software
Op de server moet software geinstalleerd worden niet nodig is voor de software - en gamedeveloper.
* SSH
* Apache met PHP
* MySQL-Server
* VSFTP
* Samba
* Python

![BLX](../icons/blocks2d_icon_32x32.jpg) _10 Blocks_


## File management
Alle ontwikkelde applicaties worden in de onderstaande mappenstructuur opgeslagen. Ook de documentatie en de testrapportages worden hier opgeslagen.
* /apps
  * websites
    * Projecten
    * Tests
    * Documenatie
  * MobileApps
    * Projecten
    * Tests
    * Documenatie
  * Games
    * Projecten
    * Tests
    * Documenatie

![BLX](../icons/blocks2d_icon_32x32.jpg) _5 Blocks_


## Scripting
Maak een script dat alle bestanden backuped van alle homedirectories. Alle homedirectories worden dan ingepakt in een zip-bestand. Dit zipbestand bestaat uit de datum en het tijdstip waarop de backup gemaakt is (bijvoorbeeld 2023119_114.zip). Het zip-bestand moet worden gekopieerd naar de Linux Desktop middels secure copy (scp).

![BLX](../icons/blocks2d_icon_32x32.jpg) _7 Blocks_


## Website
Zorg ervoor dat WordPress beschikbaar is op de development server. Dit systeem moet als intranet website gebruikt gaan worden. Zoek een bijpassende template voor WordPress dat past bij het bedrijf. Deze template moet ook bij het bedrijf passen.

![BLX](../icons/blocks2d_icon_32x32.jpg) _7 Blocks_