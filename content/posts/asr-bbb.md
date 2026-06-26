---
title: "ASR BBB"
summary: "Speech recognition and TV remote control using Android and BeagleBone Black"
date: 2015-12-01
draft: false
---

![](featured.png)

## Beaglebone Black and Speech Recognition

This is an attempt to provide some online documentation for my
undergraduation term paper (mostly from 2015) which used a client-server model
to control a TV set via speech commands. The client module runs over an Android
smartphone and the server uses Julius as backend over a Beaglebone Black board
running a Debian-based Linux. There is nothing properly documented in English
so I recommend you to follow another one of my projects called 
[ASR Remote](https://cassiotbatista.github.io/project/asr-remote/). The Android source
code can be found in this link too.

## Demo

{{< youtube vY7kQsz_mHw >}}

## Useful Links

- ["Uma Proposta de Sistema de Controle Remoto Universal com Suporte a Reconhecimento e Síntese de Voz"](./main_tcc.pdf):
  this is my undergrad thesis, but it unfortunatelly is written in Brazilian
  Portuguese. Most of the code, on the other hand, is scattered across many of
  my GitHub repos.
- ["Uso de Reconhecedor e Sintetizador de Voz Embarcados para Controle de Equipamentos Eletrônicos via Luz Infravermelha"](./tech_report_II.pdf):
  this is the main documentation written for the project "as it is" during my
  undergrad, also written in Brazilian Portuguese. It comes with a 
  [presentation PDF](./present.pdf) as well.
- https://github.com/cassiobatista/Beagle-Beagle. 
  Here you may find the ASR server built over Julius decoder.
