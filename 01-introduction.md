# Remote sensing - introduction
RS = Télémétrie
### :scroll: Histoire
- Sputnik 1 : 1957 :ru: Juste un objet
- Tiros 1: 1960 : premier satellite civil, premières images du ciel. :us:
- Nimbus 1: 1964 orbite héliosynchrone (= conditions stables d’illumination) - image + météo
- Spot 1986  :fr: CNES 
- Landsat 1972 : 80m*80m /pixel - plusieurs bandes spectrales
- QuickBird2 2001 - satelite commercial, précision < 1m
- TerraSAR-X 2007 radar imaging , metric resolution

Constellations: 
- 2011 WorldView-2 50cm
- 2012 : Orféo Pléiades 4 SAR - 4 optical centers: Pléiade très agile
- 2014 WoldView-3 30cm résolution
- 2017 PlanetScope : constellations 130 satelites (grande quantité, moins bonne qualité)

Constellations radar
- Capella (high resolution 30cm)
- Ice eye (50cm ) ~ 20 satellites

### Acteurs de l'espace
- Cost/mission 1 satellite launch: 100/200MEuros
- :free: free data from spatial agencies (:eu: Copernicus, :us: Landsat, ISRO :india:)
- :recycle: "désorbiter" les satellites

### Orbital mechatnics
- Heart = mass point

$F = G\frac{mM}{R²}$

- Constant, Ellipse. Correct initial speed = orbite cercle
- Orbite ~ 500 & 1000km
- Précession: le champs n'est pas radial, l'orbite peut tourner -> synchronisation de l'orbite avec le soleil. Orbite héliosynchrone.
- Optical: 10h du matin. SAR 6h du matin / 6h du soir. 

Cycle
$T \in [94 , 105] \text{min}$ 13.4 to 15.3 time / day

$n*T = p * 24$


Exemples: Landsat 1 : $p=13+\frac{17}{18}$ orbites par jour, $h=917km$ 
$q$ cycles en jours 18.
- :fr: Fauchée : :us: Swath size . Bande de sol 
- VHR very high resolution - satellite agile pointe pour augmenter le champ de vue
- Vitess 7km/s 1 période ~ 100minutes. 15 orbites/jour, inclinaison 98° par rapport à l'équateurs (un peu incliné par rapport aux axes des pôle)

- :turtle: Géostationnaire 24h - 36.000km (météo)
