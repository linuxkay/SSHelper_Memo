# SSHelper_Memo

## Category

Memo: android app.

## Description

Memo for SSHelper android app.

Things to write in bash_alias

Showing how to send ssh public key to Android.

## Demo in Animation

## Overview

## Requirements

## Install

## Usage

Copy ssh pub key file from computer to Android.

`ssh-copy-id -i ~/.ssh/id_rsa.pub  -p 2222 IP_Address`

bash_alias for rsync android.

`alias rsync_with_android='rsync -avzzhP --inplace --info=progress2 -e 'ssh -p 2222' Android_hostname_or_IP_Address:SDCard/DCIM/ /Destination_Directory/'`

## Contribution

## Updates

## Licence
Not specified.

## Author

[linuxkay](https://github.com/linuxkay)
