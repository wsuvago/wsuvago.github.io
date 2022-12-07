
```bash

sudo apt update && apt upgrade -y

sudo apt install clonezilla -y

```

## Back up a disk to image

```
sudo clonezilla
```

Backup the disk to image directory `/home/partimage/2022-12-06-19-img`

## Restore image to a disk

```
sudo ocs-sr -g auto restoredisk 2022-12-06-19-img sdc
```
