
# Nodejs - Express-demo

# Ohjeet/komennot uuden sovelluksen alustamiseen:
Luo projektille oma kansio ja navigoi komentorivillä sinne

# Alustus 
_npm init_ -> 
Määrittele package.json syöttämällä pyydetyt arvot tai painamalla jokaisen kohdalla Enter

# Asenna express
_npm install express_

# Asenna tuki tyypeille
_npm install -D @types/express @types/node ts-node-dev ts-node_

# Hot reload/automaattinen uudelleenkäynnistys
Lisää package.json-tiedoston "scripts"-olioon uusi ominaisuus "start": "ts-node-dev --respawn index.ts"

-----------------------------------------------------------------------------------------------------------
# Sovelluksen käynnistäminen (esim. ladattaessa esimerkkikoodit githubista)
Navigoi projektikansion juureen -> 
_npm install -> 
npm run start_
