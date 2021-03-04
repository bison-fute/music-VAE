# music-VAE

La premiere fois : 
* creer un dossier "data", avec dedans le dossier lmd_aligned (si CSV pas déjà récupérer).
* creer un dossier "midi" vide, dans lequel seront écrits les CSV (si pas déjà récupérer).

**données utilisées :** lmd-aligned du Lahk MIDI Dataset

## infos, inspiration de base

 **Original idea**
https://www.jeremyjordan.me/variational-autoencoders/
https://magenta.tensorflow.org/music-vae
github : https://github.com/magenta/magenta/tree/master/magenta/models/music_vae

**A detailled notebook on the dataset**
https://nbviewer.jupyter.org/github/craffel/midi-dataset/blob/master/Tutorial.ipynb 

**Dataset**
https://colinraffel.com/projects/lmd/ 

**Kaggle notebook on music generation**
https://www.kaggle.com/basu369victor/generate-music-with-variational-autoencoder

**Auto-encoder treated with midi files**
Github : https://github.com/vikrosj/music-autoencoders
https://towardsdatascience.com/how-to-generate-music-using-a-lstm-neural-network-in-keras-68786834d4c5
With Pytorch : https://github.com/Variational-Autoencoder/MusicVAE (C'EST DE CE GITHUB QU'ON ETE RECUPERE LES CODES, ATTENTION TOUTEFOIS IL Y A DES CHANGEMENTS : mauvaise version python, arborescence mystique etc)

**Related doc on YouTube**
Project with code : https://www.youtube.com/watch?v=0eTYs4n1LKg&list=LL&index=1&ab_channel=JCOpUntukIndonesia
Animated midi file : https://www.youtube.com/watch?v=gGqrVAe0_Ek&list=LL&index=5&ab_channel=JanAbraham
Project : https://www.youtube.com/watch?v=aOsET8KapQQ&list=LL&index=4&ab_channel=KieCodes

## A faire

Mettre le VAE dans une classe, tester l'influence de ses paramètres, tester l'architecture avec les RNNs, coder la concatenation des extraits audios en fondus.
