<!-- Output copied to clipboard! -->

<!-----

Yay, no errors, warnings, or alerts!

Conversion time: 0.46 seconds.


Using this Markdown file:

1. Paste this output into your source file.
2. See the notes and action items below regarding this conversion run.
3. Check the rendered output (headings, lists, code blocks, tables) for proper
   formatting and use a linkchecker before you publish this page.

Conversion notes:

* Docs to Markdown version 1.0β34
* Fri Sep 22 2023 00:52:30 GMT-0700 (PDT)
* Source doc: GPD_Miné-Hattab
----->


**1. Description des données et collecte ou réutilisation de données existantes**

**1a. Comment les données sont-elles recueillies ou produites et/ou comment peuvent-elles être réutilisées ?**



* Les données stockées sur psilo seront principalement des données de microscopie (images, films, metadata, fichiers de données analysées, programme permettrant l’analyse) acquises sur différents microscope de la plateforme de l’IBPS ou du LCQB. 
* Ces données seront produites par les différents membres de l’équipe FIONA.
* Chaque membre aura un répertoire Nom / Microscopie
* Les données seront accessibles par les autres membres de l’équipe. 
* Les données analysées qui seront utilisées pour des publications scientifiques devront être dupliquées dans un répertoire Papier / Data_Figure1, Papier / Data_Figure2 …

**1b. Quelles données (types, formats et volumes par ex.) seront collectées ou produites ?**



* Les données de microscopie seront des images ou films bruts en format : .nd2   .tif  ... 
* Les données analysées seront en format : mat   .m   trxyt …
* 
* Le volume des données varie selon les projets et les types de micrsocopie : entre quelques Mo et 10 To.  

**2. Documentation et qualité des données**

**2a. Quelles métadonnées et quelle documentation (par exemple méthodologie de collecte et mode d'organisation des données) accompagneront les données ?**



* Chaque utilisateur aura un répertoire contenant un dossier Microscopie. Il est **<span style="text-decoration:underline;">obligatoire</span> de respecter le rangement des données ci-dessous** :

                     Microscopie / Projet xx / Manip xx/ AnnéeMoisJour_nomSouche_condition


                     Microscopie / Projet yy / Manip ww/ AnnéeMoisJour_nomSouche_condition


    Exemple : Judith / Microscopie / Compression_yeast / Manip_foyers / 230921_3880_ON


    Chaque répertoire de données doit **impérativement contenir un fichier explicatif avec la description de l’expérience : la provenance des données doit être indiquée faute de quoi ces données ne seront pas exploitables. **En particulier, ce fichier doit préciser : le jour de la manip, les cellules utilisées, condition de culture, OD, préparation de l’échantillon, notes prises lors de l’expérience, condition d’acquisition (puissance laser, module utilisé….). Toute information utile à savoir pour analyser et interpréter les résultats doit être donnée (champs de vue avec problème…). 

* Les données pourront être lues avec NIS, Fiji, Matlab, Abbelight ou tout autre logiciel adapté selon le microscope utilisé.
* Tous les 3 mois, l’expérimenter devra résumer les meilleures manips dans word ou excel, en indiquant la date, les conditions expérimentales, les résultats … Ce fichier sera dans el répertoire Manip xx et permettra de rapidement retrouver les data.

**2b. Quelles mesures de contrôle de la qualité des données seront mises en œuvre ?**

Le PI de l’équipe FIONA controlera régulièrement l’organisation des données, en particulier pour les nouveaux arrivant et pour les étudiants. Les données non retraçables (pas de date ou de nom de souche) et sans fichiers explicatifs seront effacées.

**3. Stockage et sauvegarde pendant le processus de recherche**

**3a. Comment les données et les métadonnées seront-elles stockées et sauvegardées tout au long du processus de recherche ?**

_Recommandations_:



* Les données seront dupliquées sur disques durs externes et sur psilo. Chaque membre de l’équipe FIONA pourra se procurer un ou plusieurs disques durs externes pour faire une sauvegarde. Cette solution est temporaire. Un système de sauvegarde automatique est en cours de demande au LCQB pour dupliquer les données de psilo sur un autre serveur automatiquement. 
* Une sauvegarde et un nettoyage des données devra être effectués tous les 2 mois minimum. 

**4. Exigences légales et éthiques, codes de conduite**

**4a. Si des données à caractère personnel sont traitées, comment le respect des dispositions de la législation sur les données à caractère personnel et sur la sécurité des données sera-t-il assuré ?**



* Aucune donnée personnelle n’est stockées sur psilo. 

**4b. Comment les autres questions juridiques, comme la titularité ou les droits de propriété intellectuelle sur les données, seront-elles abordées ? Quelle est la législation applicable en la matière ?**

_Recommandations_:



* Les données sont libres d’accès par les membres de l’équipe FIONA. 
* Les données appartiennent à l’expérimentateur et à l’équipe FIONA.

**5. Partage des données et conservation à long terme**

**5a. Comment et quand les données seront-elles partagées ? Y-a-t-il des restrictions au partage des données ou des raisons de définir un embargo ?**

_Recommandations_:



* Les données publiées seront stockées pendant 5 ans après publication. Si aucun projet n’utilise ces données, elles pourront être effacées, dans le cas contraire, elles seront stockées temps que 1 ou plusieurs projets nécessitent leur consultation.   **5b. Comment les données à conserver seront-elles sélectionnées et où seront-elles préservées sur le long terme (par ex. un entrepôt de données ou une archive) ?**

**5c. Quelles méthodes ou quels outils logiciels seront nécessaires pour accéder et utiliser les données ?**

_Recommandations_:



* Les logiciels nécessaires seront principalement: Matlab, NIS, Abbelight, Fiji, word, excel, visp, inferenceMap, Genuage. 

**5d. Comment l'attribution d'un identifiant unique et pérenne (comme le DOI) sera-t-elle assurée pour chaque jeu de données ?**

_Recommandations_:



* Expliquer comment les données pourraient être réutilisées dans d'autres contextes. Les identifiants pérennes devraient être appliqués de manière à ce que les données puissent être localisées et référencées de façon fiable et efficace. Les identifiants pérennes aident aussi à comptabiliser les citations et les réutilisations.
* Indiquer s’il sera envisagé d’attribuer aux données un identifiant pérenne. Typiquement, un entrepôt pérenne de confiance attribuera des identifiants pérennes.

**6. Responsabilités et ressources en matière de gestion des données**

**6a. Qui (par exemple rôle, position et institution de rattachement) sera responsable de la gestion des données (c'est-à-dire le gestionnaire des données) ?**



* Chaque membre_ _est responsable des données contenues dans le répertoire à son nom.
* Le PI aura la responsabilité de controler régulièrement la qualité et l’organisation de ces données.
* Le PDG sera remis à jour tous les ans en cas de changement.

