ruokakauppacom
==============
# tuote on todennäköisesti aina loppu™
Tuntikirjanpito (narchie): https://docs.google.com/spreadsheets/d/1cTXIJkHlUkoj8kyBmqMJWxvhCPQzi9a9JIG3hNqOlZQ/edit?usp=sharing
Tuntikirjanpito (samsalon): 

Osta ruokaa ja selaa ruokakauppaa!
Yeoman AngularJS fullstackilla™ luotu applikaatio.

# Riippuvaisuudet
* MongoDB
* Grunt

# Ohjeet
node.js käyttää NODE_ENV ja PORT -ympäristömuuttujia - muokkaa niitä, jos haluat käyttää productionia.
Suorita seuraavasti:

```
git clone https://github.com/narck/ruokakauppacom
cd ruokakauppacom/
npm install
bower install
grunt build
cd dist/
node server.js
```
