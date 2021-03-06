GWT-OpenLayers 3
==================

[![Build Status](https://travis-ci.org/TDesjardins/gwt-ol3.svg?branch=gwt%2F2.8)](https://travis-ci.org/TDesjardins/gwt-ol3)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.github.tdesjardins/gwt-ol3/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.github.tdesjardins/gwt-ol3)
[![Join the chat at https://gitter.im/gwt-ol3/Lobby](https://badges.gitter.im/gwt-ol3/Lobby.svg)](https://gitter.im/gwt-ol3/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

With gwt-ol3 you can write fast mapping applications for web and mobile in pure Java. Technically speaking, it is a [OpenLayers 3](http://openlayers.org/ "OpenLayers website") - Wrapper for GWT using the [JSInterop](https://docs.google.com/document/d/10fmlEYIHcyead_4R1S5wKGs1t2I7Fnp_PaNaa7XTEk0/edit)-Features of the [GWT-SDK](http://www.gwtproject.org/release-notes.html#Release_Notes_2_8_0 "Release notes"). The project consists of two parts:
  
  * a GWT wrapper for OpenLayers 3 (gwt-ol3-client)
  * a demo module for showing wrapper functionality (gwt-ol3-demo)

You can build (`mvn package`) and run (`mvn gwt:devmode`) the application using Maven.

If you want to build the application without Maven please consider the following hints: 

  * Building the application with older GWT-SDK than 2.8.0-beta1 will not work. You can download the latest SDK [here](http://www.gwtproject.org/versions.html).

Live example [here](https://tdesjardins.github.io/gwt-ol3/).

## Download

Releases are deployed to [the Central Repository][dl].

Snapshots of the development version are available in 
[Sonatype's `snapshots` repository][snap].


 [dl]: https://search.maven.org/#search%7Cga%7C1%7Cg%3A%22com.github.tdesjardins%22
 [snap]: https://oss.sonatype.org/content/repositories/snapshots/
 
