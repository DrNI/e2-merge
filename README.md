# e2-merge
Script for merging video files from Z Cam E2 camera series

## Introduction

The relatively young camera manufacturer Z Cam makes interesting stuff with their E2 camera series. 
These cameras split their recordings into multiple files, by default starting with a new file every
five minutes.

Windows and OS X users may use the Z Cam VideoConcatenator to merge these files before using them in video editing.

Linux users do not have this option. e2-merge aims at providing a similar functionality on the basis of ffmpeg.

Furthermore, the script may allow to use the output of your E2 when importing the files directly into your NLE fails (as it likely to happen possible with Lightworks 2020.1).

## Status

This is alpha software. Feel free to give feedback. It is being used with the files of an E2C camera.

## Requirements

These other programs are needed:

* ffmpeg
* mediainfo


## Legal stuff

This software is free software under the terms of GNU GPL v3.

