# ios-openURL-maree-info

URL de l'application iOS marée.info
https://itunes.apple.com/fr/app/maree.info/id642338158?mt=8

Ref Apple SDK iOS - UIApplication
- [canOpenURL] (https://developer.apple.com/library/ios/documentation/UIKit/Reference/UIApplication_Class/#//apple_ref/occ/instm/UIApplication/canOpenURL:)
- [openURL] (https://developer.apple.com/library/ios/documentation/UIKit/Reference/UIApplication_Class/#//apple_ref/occ/instm/UIApplication/openURL:)

## URL d'appel de l'application depuis une autre application ou un site web
<pre>
Exemple pour Saint-Malo (id=52)
Marée : maree-info://52
Horloge : maree-info://52/horloge
Calendrier : maree-info://52/calendrier
</pre>

## avec paramètres
<pre>
  maree-info://52?d=20150801
  maree-info://52?d=201510010
  maree-info://52?d=201510012&ht=5
  maree-info://52?d=201510024&ht=5&hm=12h
  maree-info://52?d=201510024&ht=5&hm=12h&nuit=1
  maree-info://52?d=201510024&ht=5&hm=12h&nuit=1&detail=0
  maree-info://52?d=201510024&ht=5&hm=12h&nuit=1&detail=1
  maree-info://52?d=201510024&ht=5&hm=12h&nuit=1&detail=2
  maree-info://52?d=201510024&ht=5&hm=12h&nuit=1&detail=8h12
  maree-info://52?d=201510024&hm=9h15&detail=2

  maree-info://52/calendrier?d=201508
  maree-info://52/calendrier?d=201508&f=1&fc=78&fd=1000111
  maree-info://52/calendrier?d=201508&f=1&fc=-78&fd=1000111
</pre>

## Rubriques :
<pre>
  cgu       : maree-info://cgu
  réglages  : maree-info://reglages
  settings  : maree-info://settings
  ports     : maree-info://ports
  abo       : maree-info://abo
  appdata   : maree-info://appdata
</pre>
