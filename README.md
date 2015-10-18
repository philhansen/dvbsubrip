dvbsubrip
=========

A python script for extracting DVB image based subtitles from TS recordings.  Subtitles can be saved in either WebVTT (.vtt) or SubRip (.srt) format.

This is a fork of Luca Olivetti's "vdrsubrip" script: http://ventoso.org/luca/vdr/

## Requirements

This script uses ProjectX to extract the dvb subtitles, BDSup2Sub to convert them to images, and Tesseract to convert the images to text. It also uses dvbsnoop to detect the time difference between video and subtitles.

*   ProjectX: http://project-x.sourceforge.net/
*   BDSup2Sub: https://github.com/mjuhasz/BDSup2Sub
*   Tesseract OCR: https://github.com/tesseract-ocr
*   dvbsnoop: http://dvbsnoop.sourceforge.net/

## Use

Example of using the script:

`dvbsubrip input.ts subtitles.srt`
