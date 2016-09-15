Boky soratana amin'ny LaTeX

Ao amin'ny branche 'trunk' no anaovana pre-merge principal

Hizara parties maromaro ilay boky, ka isaky ny partie iray dia efa fichier iray ho anaovana input an'ny chapitres

Chapitre iray dia ataon'ny mpanoratra iray, ka ho fichier iray, na fichier maromaro mi-input sections

Chapitre iray dia mitaky branche iray atao hoe 'chap/titrecourt'

Raha mila manampy zavatra anaty préambule dia commitena anatin'ilay branche an'ilay chapitre ihany koa

Atao pdf ny output ka mila jerena izay type de fichier image raisin'ilay pdflatex

Ampiana anaty .gitignore ny fichiers izay mety ho generen'ny éditeur LaTeX
________________________________________________________________________________

Ouvrage écrit avec LaTeX

Les pre-merge principaux se feront dans la branche 'trunk'

L'ouvrage se divisera en plusieurs parties, chaque partie sera un fichier qui contiendra des input des chapitres

Un auteur se chargera d'un chapitre entier, et l'écrira dans un fichier entier, ou plusieurs fichiers qui inclueront des sections

Un chapitre requiert une branche nommée 'chap/titrecourt'

Si des ajouts dans le préambule sont nécessaires, les commits se feront dans la branche du chapitre en cours

L'output sera un pdf, il faudra considérer les types de fichiers images pris en compte par pdflatex

Si on utilise un éditeur LaTeX, ajouter les fichiers qu'ils pourraient génerer dans le .gitignore