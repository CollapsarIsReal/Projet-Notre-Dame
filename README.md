# Projet-Notre-Dame

Le Projet Notre-Dame consiste en une transcription des [journaux quotidiens de l'année 1860](https://mediatheque-patrimoine.culture.gouv.fr/sites/mediatheque/files/jnd_1860.pdf) des travaux de restauration effectués de 1844 à 1865 à la cathédrale Notre-Dame de Paris sous la direction d'Eugène Viollet-le-Duc et Jean-Baptiste Lassus. Celle-ci a été effectuée sur eScriptorium à partir de la [numérisation des journaux des travaux](https://mediatheque-patrimoine.culture.gouv.fr/travaux-de-notre-dame-de-paris-1844-1865) réalisée par la Médiathèque de l'architecture et du patrimoine. 

Le projet a été réalisé dans le cadre du cours GIT du [master 2 TNAH de l'École nationale des chartes](https://www.chartes.psl.eu/fr/cursus/master-technologies-numeriques-appliquees-histoire). Ses données sont disponibles dans le dossier [data](https://github.com/dtsoline/Projet-Notre-Dame/tree/projetND/data).

Règles de transcription suivies:
-------------------------------------------------------------------------------------------------------------------------------------------------
- respect des majuscules et minuscules
- respect des ligatures (par exemple, transcrire "chœur")
- mot qui est barré : 难 (une seule fois par mot) mais seulement s'ils sont totalement/à moitié illisibles. Les restranscrire entre accolades {} s'ils sont lisibles. 
- Pour mettre en exergue les doutes de transcription : 
    - mot incertain: [incertain]
    - mot que l'on ne parvient pas à transcrire : [??]

Répartition de la transcription et relectures:
-------------------------------------------------------------------------------------------------------------------------------------------------
- Anaïs : pages 1 à 3 (relues par Ariane)
- Soline : pages 4 et 5 (relues par Anaïs)
- Ariane : pages 6 et 7 (relues par Soline)
- Elsa : pages 8 et 9 (relues par Margaux)
- Margaux : pages 10 à 12 (relues par Elsa)

Utilisation d'eScriptorium :
---------------------------------------------------------------------------------
Versions utilisées et considérations techniques : 
- [eScriptorium](https://gitlab.com/scripta/escriptorium) : Version Wed Dec 8 10:53:11 CET 2021 - a64ba80255ddab851728cbdc2427f701902901c7
- [Kraken](http://kraken.re/master/index.html) : Version 3.0.5
- Modèle de transcription utilisé : Kraken: Modèle Manuscrit 19e Lectaurep  
- Format d'export des transcriptions : ALTO (XML)

Application des zones :
- une zone principale qui constitue le corps du texte : "main"
- une zone marge : "marge"
- une zone pour encadrer les illustrations : "illustrations"
- une zone pour délimiter le numéro de folio : "folio"
- une zone pour délimiter les tableaux : "table"
 
 Aides possibles
 -------------------------------------------------
 - Un [lexique](https://github.com/dtsoline/Projet-Notre-Dame/blob/projetND/lexique_architectural.md) regroupant le vocabulaire architectural, une capture du mot et sa définition est disponible dans le repository.
 - Un tutoriel pour la bonne numérotation des lignes est disponible [ici](https://github.com/dtsoline/Projet-Notre-Dame/blob/projetND/Tutoriel_numerotation_lignes.md)

 
Bonnes pratiques : 
-----------------------------------------------------------------------------------------------------------------------------------------
- une branche par personne
- Un dossier par page, nommé comme suit pour la page 1 : "NDP_page01". Il comprend un fichier xml, un fichier txt et une image png.
- les fichiers xml doivent se nommer comme suit : NDP_page01.xml
- les fichiers txt doivent se nommer comme suit : NDP_page01.txt
- les images png doivent se nommer comme suit : NDP_page01.png
- pour toute demande d'aide en transcription (mots incertains, illisibles...) : créer une issue pour chaque page pour y répertorier les difficultés
- ne pas oublier d'ajouter dans le lexique (lexique_architectural.md) les mots spécifiques au domaine de l'architecture qui ont posé des problèmes de transcription.
