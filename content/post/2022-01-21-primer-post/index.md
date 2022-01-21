---
title: QGIS no está afectado por Log4J
subtitle: "Fuente: QGIS.org"
date: 2021-12-15T06:54:24.140Z
summary: "Fuente: QGIS.org"
draft: false
featured: true
authors:
  - gus-presa
tags:
  - QGIS
categories:
  - Noticias
image:
  filename: featured.png
  focal_point: TOPRIGHT
  preview_only: false
---
La vulnerabilidad causada por **Log4J** ha estado en todos los titulares tecnológicos de los últimos días. Hemos ([qgis.org](http://www.qgis.org)) recibido muchas preguntas queriendo saber si **QGIS** ha sido afectado. Por ello, nos gustaría aclarar:

**QGIS** no es una aplicación **Java**. **QGIS** está basado en **C++** y **Python**. **QGIS**, por lo tanto, no usa ningún componente de **Java**, incluyendo **Log4j**(ava).

Es técnicamente posible que algún "**plugin**" (complemento) utilice aplicaciones **Java**. Si estás preocupado por cualquier potencial vulnerabilidad, por favor ponte en contacto con los desarrolladores del "**plugin**" (complemento) a través de la información de contacto que puedes encontrar en sus metadatos.

![img](featured.png)