# SSHelper_Memo

## Category

Memo: android app: file transfer.

## Description

Memo for SSHelper android app.

Things to write in bash_alias for convenience.

Showing how to send ssh public key to Android.

## Demo in Animation

## Overview

## Requirements

SSHelper app

may require android 8 or above

SSHelper does not complatible android 5x

## Install

## Usage

Copy ssh publick key file from a computer to Android.

`ssh-copy-id -i ~/.ssh/id_rsa.pub  -p 2222 IP_Address`

Add follwoing line in bash_alias or .zshrc for rsync android.

`alias rsync_with_android='rsync -avzzhP --inplace --info=progress2 -e 'ssh -p 2222' Android_hostname_or_IP_Address:SDCard/DCIM/ /Destination_Directory/'`

<hr>

For scp file transfer

PC to Android

`scp SourceDirectory AndroidHostName:/data/data/com.arachnoid.sshelper/files/home/SDCard/Music/`

Android to PC

PC to iPhone

Use an app called FTP Manager Pro

https://apps.apple.com/jp/app/ftpmanager-ftp-sftp-client/id525959186?ign-mpt=uo%3D4

Or

FE File Explorer

https://apps.apple.com/jp/app/fe-file-explorer-file-manager/id510282524

iPhone to PC

## Contribution

## Updates

## Licence
Not specified.

## Author

[linuxkay](https://github.com/linuxkay)
