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

## Get the / partition free space
```bash
./freespace /
```
outputs 37001384

```bash
./freespace / -h 
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
