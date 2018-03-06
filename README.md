# Lion-gazelle

KEDJAR Damien 
FOUAISSI Wassim
TEP Rémy
NABET Benjamin

 Pb: Comment varie l'éco-système, la population entre les lions et les gazelles?
 
Utilisation d’un système dynamique non déterministe pour étudier l’évolution de 2 populations d’espèces différentes entretenant une relation proie-prédateur.
Les lions sont les prédateurs.
Les gazelles sont les proies.
L’environnement d’étude sera la savane (Pays possibles : Kenya / Afrique du Sud / Tanzanie / Zambie), simplifiée pour faciliter la visualisation de l’évolution des populations.
On pourra s’interroger sur l’impact de la présence variable de gazelles comme unique source de nourriture pour une population donnée de Lions.
Répartition initiale des populations:
• Sexe des Lions (M/F).
• Âge des Lions (+ vieillissement).
• Vitesse de reproduction des Lions (+ durée de gestation).
• Fréquence de chasse des Lions (1 fois tous les 4 jours).
• Entourage des Lions (meutes/solitaires).
• Vitesse de course des Lions.
• Âge des gazelles (+ vieillissement).
• Vitesse de reproduction des gazelles (repopulation).
• Rencontre entre proie et prédateur (nombre).
• Vitesse de course des Gazelles.
- Le lion dort 15h/24 donc il lui reste 9h pour chasser. Il chasse le soir ou très tôt le matin


Aujourd'hui nous avons présenté notre projet.
Nous avons vu différents paramètres, nous avons sélectionnés ceux qui nous ont semblait être les plus pertinents.
Nous allons rajouter peut être 2 ou 3 paramètres avant la semaine prochaine.



Mardi 6 Mars

On part du principe qu'un cylce fasse 24x30x7 ittérations soit 7 mois. Le lion dormant 15h par jour, la case lion ne bougera donc pas pendant environ 15x30x7 itérations , la gazelle quant à elle dort 8h par jour. 
Le lion a une vitesse inférieure à celle de la gazelle (lion = 80km/h et gazelle = 90km/h). Néanmoins utilisant son habitat naturel, son environnement, le lion arrivera à attraper la gazelle 2 fois sur 3. On peut donc se dire que 2 fois sur 3 (cas : le lion attrape la gazelle) lorsque la gazelle avance d'une case, le lion en avancera de 2. 
A savoir aussi que c'est la femmelle qui chasse 90% du temps, elle chasse en meute, elle est donc accompagnée d'autres liones.  Elle a une periode de gestation de 110 jours, pendant ce temps la elle est donc inactive et c'est le lion qui part chasser, cette fois ci solitairement. 
On sait également que les lions ne chassent que tous les 4 jours. Il y a donc 24x21x7 itérations ou les lions ne bougent pas.
Concernant la chasse en meute de la lionne, on part du principe que pendant cette période, ce n'est pas une mais plusieurs cases qui se déplacent au même moment. 99% du temps la meute de lionne arrive à attraper la gazelle, c'est pourquoi on partira du principe que lorsqu'un groupe de lionne entre en contact (à 2 cases d'écart) avec la gazelle, elle la chasse (pour une case déplacée par la gazelle, le groupe de lionne se déplace de deux) et l'attrapent 100% du temps.







