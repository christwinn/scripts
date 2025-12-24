# freespace

A simple script to find either a partition or system freespace.

Obviously your numbers will vary !

## Get the /home partition free space
This assumes that /home is on a seperate partition not a child 

```bash
./freespace /home
```
outputs 37001384

```bash
./freespace /home -h 
```
outputs 36G

## Get the /dev/sda3 partition free space
```bash
./freespace /dev/sda3
```
outputs 37001384

```bash
./freespace /dev/sda3 -h 
```
outputs 36G

## Get the system free space
```bash
./freespace
```
outputs 82857620

```bash
./freespace -h
```
outputs 80G

# filemod

A simple script to find when a file was modified (in seconds). Does it need to be backed up?

```bash
./filemod /home/me/myfile
```

outputs 12345



