## Exécuter le script

\--- task ---

Tape la commande suivante dans le terminal et appuie sur <kbd>Entrée</kbd> pour exécuter le script :

```bash
./run_sd.sh
```

\--- /task ---

\--- task ---

Il te sera demandé de saisir un prompt. C'est une description de l'image que tu souhaites générer. Le prompt guide le processus de génération d'images en décrivant la scène ou l'objet souhaité. Si tu souhaites en savoir plus sur le prompt d'un générateur d'images IA, [consulte le projet ici](https://projects.raspberrypi.org/fr-FR/projects/ai-image-prompt/){:target="_blank"}.

```bash
Saisis le prompt : Un chat
```

Appuie sur <kbd>Entrée</kbd>.

\--- /task ---

\--- task ---

Ensuite, saisis le nombre d’étapes. Cela affecte la qualité de l'image. Un plus grand nombre d'étapes produit généralement des images de meilleure qualité, car le modèle a plus de possibilités d'affiner le résultat. Cela prend environ 1 minute par étape sur un Raspberry Pi 5 avec 4 Go de RAM.

```bash
Saisis le nombre d'étapes : 5
```

Appuie sur <kbd>Entrée</kbd>.

\--- /task ---

\--- task ---

Saisis le nom du fichier image. Il s’agit du nom sous lequel ton image générée sera enregistrée.

```bash
Saisis le nom du fichier image de sortie : cat.png
```

Appuie sur <kbd>Entrée</kbd>.

\--- /task ---

\--- task ---

Attends que l'image soit générée.

Le script va maintenant s'exécuter avec tes entrées pour générer l'image. Cela peut prendre quelques minutes en fonction du nombre d'étapes et des performances de ton ordinateur.

\--- /task ---

\--- task ---

Vérifie le résultat.

Une fois le processus terminé, ton image générée sera enregistrée dans le répertoire actuel avec le nom de fichier spécifié.

![Un chaton orange et blanc avec de grands yeux expressifs et un nez rose est assis sur une surface en bois. Le chaton a un nœud rose autour du cou. En arrière-plan, il y a des brins de lavande et un bouquet de fleurs de lavande enveloppé dans de la toile de jute, sur un arrière-plan rose clair.](images/cat.jpg)

\--- /task ---

En suivant ces étapes, tu peux facilement générer des images à l’aide du script. Le prompt définit ce que l'image va représenter, le nombre d'étapes influence sa qualité et le nom détermine le nom du fichier lorsqu'il est enregistré.

Amuse-toi à créer tes images !
