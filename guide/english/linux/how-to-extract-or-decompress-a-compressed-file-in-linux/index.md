---
title: How to extract or decompress a compressed file in Linux
---
Before extracting the data from a compressed file, you must first determine the compressed file type.<br>

Run the following command to determine the file type: <br>
`file File-Name`

## How to extract or decompress a tar file

Run the following command to decompress a tar file<br>
`tar xvf File-Name -C /Directory-Location`

`We Use (-C) for specific directory if we do not use (-C) then it automatically extract to current directory.`

## How ot extract or decompress a gzip file
Run the following command to decompress a gzip file:

`gunzip File-Name

## Links
* GNU Tar (https://www.gnu.org/software/tar/)
* GNU Gzip (https://www.gnu.org/software/gzip/)
