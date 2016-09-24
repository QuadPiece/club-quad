# club-quad
club-quad is a continuation of the club-Swizards rutorrent theme. Swizards was hacked and shut down, after which the original repository seems to have been deleted. I decided to orphan the theme and fix some things.

## Install

Navigate to your plugins/themes directory, this is  `plugins/theme/themes` inside rutorrent's web root. 

(eg. if you cloned rutorrent into `/var/www`, then you're probably looking for `/var/www/rutorrent/plugins/theme/themes`)

Next, simply clone the club-quad theme into your themes folder and change the owner so it belongs to your web server
```
git clone https://github.com/QuadPiece/club-quad.git club-quad
chown -R www-data: club-quad
```
