# Kin Cloud
Kin Cloud is a tool for visualizing family tree data in an interactive, 3D space.  

<!-- TOC -->
- [Install](#install)
- [Using Kin Cloud](#using-kin-cloud)
  - [Left-click & drag](#left-click--drag)
  - [Right-click & drag](#right-click--drag)
  - [Mouse wheel](#mouse-wheel)
  - [Left-click on node](#left-click-on-node)
  - [Right-click on node](#right-click-on-node)
- [About Kin Cloud](#about-kin-cloud)
  - [Data Parsing](#data-parsing)
  - [Visualization](#visualization)
- [About GEDCOM](#about-gedcom)

<!-- TOC END -->

## Install
`git clone https://github.com/mister-blanket/kin-cloud.git kin-cloud && cd kin-cloud && npm i`    
`npm start`

## Using Kin Cloud
#### Left-click & drag
Moves the camera.

#### Right-click & drag
Pans the camera.

#### Mouse wheel
 Zooms the camera.

#### Left-click on node
Mutes all other nodes which are not directly linked to the selected node. Clicking on that node again will unmute other nodes.

#### Right-click on node
Zooms in on node and set it as the new pivot point for the camera.

## About Kin Cloud

#### Data Parsing
Kin Cloud uses [GEDCOM-d3](https://github.com/mister-blanket/gedcom-d3), a custom GEDCOM parser designed for this project. It is based off of the [tmcw/parse-gedcom](https://github.com/tmcw/parse-gedcom) project.

#### Visualization
Kin Cloud uses [3D Force-Directed Graph](https://github.com/vasturiano/3d-force-graph) for visualizaiton.

## About GEDCOM
[GEDCOM](https://en.wikipedia.org/wiki/GEDCOM) is an open standard for exchanging genealogical data between different genealogy software. If you have created a family tree using a computer program or website, chances are you can export your data as a GEDCOM file.

If you haven't created a family tree, but are interested, there are many websites and applications available to help you do so. I recommend [GRAMPS](https://gramps-project.org/introduction-WP/), which is free and open-source genealogy software.
