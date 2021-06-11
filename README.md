# Transpofilms

### C'est quoi TranspoFilms

TranspoFilms est une plate-forme de streaming gratuit et sans publicité. 

### Comment installer un serveur TranspoFilms... 

#### Installer Apache2:

```
sudo apt install apache2
```
#### Dupliquer repo:

```
cd /var/www/html/
sudo rm index.html
git clone https://github.com/Ecoriap/transport.git
mv transport/* /var/www/html/
```
