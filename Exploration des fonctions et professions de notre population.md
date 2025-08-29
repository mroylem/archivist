# Exploration des professions au sein de la population d'archiviste

### Rappel du questionnement traité dans cette partie

- Est-ce que ce type de métier exige nécessairement de travailler dans le secteur public (national ou étatique, par exemple) ? Y a-t-il des exemples où cela pourrait être différent ?
- Peut-on étudier l’évolution des employeurs de cette population ?
______________

### Inspection de nos données

![Inspection des relations](https://github.com/mroylem/archivist/blob/main/sparqlnotebook/images/Inspection%20des%20relations%20valables_r%C3%A9seaux.jpg "Inspection des relations")

Pour répondre à nos questions, nous avons réalisé une analyse de réseau. 

Nous avons tout d'abord analysé la distribution dans le temps des relations entre les générations, puis nous avons inspecté les différentes relations existantes. 

Il semble que les archivistes aient souvent travaillé dans l'éducation publique, notamment entre 1941 et 1970. Pourtant, il semble qu'entre 1851 et 1910, ils ont eu tendance à faire partie d'association ou être membres de communauté scientifique plutôt qu'employés ou professeur. Même si, beaucoup sont professeurs (ou, en tout cas, travaillent dans l'éducation) dès 1881. 
La tendance s'inverse dès 1911-1940, les individus sont alors très souvent embauchés par le secteur de l'éducation ou comme employé. 

Pour mieux comprendre cette répartition, nous avons analysé, regroupée, puis lister les types d'organisations les plus courants parmi les employeurs (ou association) qui comportaient des archivistes. 
Puis nous avons réalisé une analyse bivariée.

![Type de relation avec type d'organisation](https://github.com/mroylem/archivist/blob/main/sparqlnotebook/images/Type%20de%20relation%20avec%20type%20d'organisation_r%C3%A9seaux.jpg "Type de relation avec type d'organisation")

Dans ce tableau de contingence, plusieurs phénomènes sont intéressants :
- D'abord on constate bien qu'un nombre surreprésenté d'archivistes ont été membres d'une société savante.
- Ensuite, les universités (publique et non publique) sont également bien représentées
- Dans les emplois, on voit également une représentation attendue pour les archives nationales, municipales ou état (pour les pays fédéraux).
___________

### Évolution dans le temps 

Pour plus de précision et une meilleure représentation, nous avons ajouté la temporalité à notre précédente analyse.

![Relation entre organisation et la période](https://github.com/mroylem/archivist/blob/main/sparqlnotebook/images/relation%20%C3%A0%20organisation%20avec%20la%20p%C3%A9riode_r%C3%A9seau.jpg "Relation entre organisation et la période")

Dans ce tableau de contingence, nous pouvons constater une répartition du type d'organisation avec la période.
- Une surreprésentation est visible pour les archivistes faisant partie des sociétés savantes pour la fin du XIXe et le début du XXe. Résultats plutôt logiques quand on sait que ces sociétés ont été très en vogue à cette période. Puis, dès 1941, cette catégorie devient sous-représentée ici.
- Pour les emplois (hors éducation), on constate également une augmentation de la représentation dès 1911-1940. C'est également cohérent avec le pic des naissances que nous avons constaté plutôt, mais également avec la fonction qui se coordonne et se structure.
- Enfin, la partie éducation prend un essor tout au long de la période étudiée. Mais reste stable par la suite.
- Les archivistes étaient plus susceptibles d’occuper un emploi que d’enseigner entre 1940 et 1970.

Enfin, nous avons souhaité effectuer une autre analyse en mettant en relation les relations entre les organisations, le type d'organisation et l'évolution de ce phénomène dans le temps.

![Table de relation avec l'organisation et la période](https://github.com/mroylem/archivist/blob/main/sparqlnotebook/images/Table%20de%20relation%20avec%20l'organisation%20et%20la%20p%C3%A9riode_r%C3%A9seaux.jpg "Table de relation avec l'organisation et la période")

Ce qu’on peut analyser ici, c’est :

- On constate ici également une surreprésentation des sociétés savantes, mais également des académies des sciences pour la période 1852-1880. Ensuite, leurs sous-représentations pour la période après 1940.
— À l’inverse, les universités sont sous-représentées au début de la période 1851-1940, puis, à partir de 1941, leurs résultats se rapprochent de ceux espérés. Les archivistes y sont présents, mais pas en grand nombre. Pour la période 1971-2000, on peut même constater une baisse du nombre d'universitaires et une augmentation d'archiviste faisant partie d'un organisme de recherche.
- Les universités privées sont très peu présentes en tant qu'employeur d'archivistes
- Le nombre d'archivistes municipaux, étatiques, nationaux reste représenté dès 1940
- Le nombre d'archivistes faisant partie d'une entreprise privée varie en fonction des époques.

_____________________

### Conclusion

Ainsi, un individu peut être archiviste dans différents milieux, que ce soit au niveau municipal, provincial, national, etc. Cependant, il est également possible qu’il exerce sa profession dans d’autres secteurs, comme l’enseignement, la recherche ou le secteur privé. 

Bien sûr, l’étude montre que ce changement s’est produit progressivement. 

Au tournant du XIXe siècle et au début du XXe, les archivistes étaient principalement présents dans des sociétés savantes et comme professeurs. C’est avec l’évolution de la société et l’émergence d’une fonction structurée d’« archiviste » que ceux-ci ont commencé à se concentrer sur le secteur dédié. Ils sont toutefois restés présents dans des postes universitaires ou d'entreprises privées.


