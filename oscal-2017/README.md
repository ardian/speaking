# OSCAL 2017

# Internets in the Mountains (or strange cities)

---

# whoami

 - Ardian Haxha

 - Fedora Ambassador

 - Web Developer

 - <3 Unix

---

# The Offline Apocalypse

---

## Offline Maps

 - http://maps.me/en/home
 - http://osmand.net/

---

## Offline social media

## Scuttlebot

Scuttlebot is an open source peer-to-peer log store used as a database,
identity provider, and messaging system. It features global replication,
file-syncronization, and end-to-end encryption.


### ssbc/patchwork

A decentralized messaging and sharing app built on top of Secure
Scuttlebutt (SSB). 

https://github.com/ssbc/patchwork

```
$ git clone https://github.com/ssbc/patchwork
$ cd patchwork
$ npm install
$ npm start
```

---

# Offline Reading

 - Scrapbook
 - Httrack

---

# Offline Wiki
 
 - Vimwiki
https://github.com/vimwiki/vimwiki
---

# youtube-mp3


youtube-dl -F https://www.youtube.com/watch?v=xSkCny-HtTw

```
[youtube] xSkCny-HtTw: Downloading webpage
[youtube] xSkCny-HtTw: Downloading video info webpage
[youtube] xSkCny-HtTw: Extracting video information
[youtube] xSkCny-HtTw: Downloading MPD manifest
[info] Available formats for xSkCny-HtTw:
format code  extension  resolution note
249          webm       audio only DASH audio   52k , 1fps, opus @ 50k, 987.15KiB
139          m4a        audio only DASH audio   56k , m4a_dash container, mp4a.40.5@ 48k (22050Hz), 1002.82KiB
250          webm       audio only DASH audio   67k , 1fps, opus @ 70k, 1.17MiB
171          webm       audio only DASH audio   91k , 1fps, vorbis@128k, 1.69MiB
140          m4a        audio only DASH audio  129k , m4a_dash container, mp4a.40.2@128k (44100Hz), 2.60MiB
251          webm       audio only DASH audio  178k , 1fps, opus @160k, 3.25MiB
160          mp4        194x144    DASH video  110k , avc1.4d400c, 15fps, video only, 2.18MiB
133          mp4        322x240    DASH video  247k , avc1.4d400d, 30fps, video only, 4.91MiB
17           3gp        176x144    small , mp4v.20.3, mp4a.40.2@ 24k
36           3gp        320x238    small , mp4v.20.3, mp4a.40.2
18           mp4        352x262    medium , avc1.42001E, mp4a.40.2@ 96k
43           webm       640x360    medium , vp8.0, vorbis@128k (best)

```

pick the best quality (this case 43)

youtube-dl -f **43** https://www.youtube.com/watch?v=xSkCny-HtTw

---

# Mosh

Remote Connection high latency

#### Fedora:
```
sudo dnf install -y mosh-server
```
#### Debian / Ubuntu

```
sudo apt-get install -y mosh
```

Start a new server:

`mosh-server new -l LANG=en_US.UTF-8 -p 60500`

Connecting:

mosh username@hostname


---

# Code Documentation Offline 

`dnf install zeal`

---

# Offline npm Installs

```
$ ls -1 ~/.npm|wc -l
1451
```

alias npmi='npm install --cache-min passwifi'

---

# readme 
Install:

`npm install -g readme`

Run:

`readme passwifi`

---

# Thank you

https://github.com/ardian/speaking/tree/master/oscal-2017

