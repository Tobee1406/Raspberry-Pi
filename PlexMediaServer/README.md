# Plex Media Server

## Step 0:


## Step 1: Update Rasbian
```
sudo apt-get update
sudo apt-get upgrade
```

## Step 2: Enable HTTPS
```
sudo apt-get install apt-transport-https
```

## Step 3: Install Plex Media Server
```
apt-get install plexmediaserver-installer
```

## Step 4: Change server user
```
sudo nano /etc/default/plexmediaserver
```
```
sudo service plexmediaserver restart
```

## Step 5: Set the static IP address
```
hostname -I
```
```
sudo nano /boot/cmdline.txt
```

## Step 6: Add files to the Plex library
```
192.168.0.1:32400/web/
```

Your directory should look as follows:
```
/Media
   /Movies
      movie content
   /Music
      music content
   /TV Shows
      television content
```

## Step 7: Create/connect an account


## Step 8: Connect to the Raspberry Pi Plex Center
