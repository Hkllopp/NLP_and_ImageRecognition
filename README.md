# natural-language-processing-and-image-recognition


This repo is a report of my work on a project during an OpenClassrooms training course.


Pour que le notebook soit fonctionnel, il y a plusieurs étapes à suivre.

1. Mettez vos credentials pour vous connecter à l'API de yelp dans le fichier `credentials.py`.
2. Télécharger les deux dataset [ici](https://www.yelp.com/dataset/download) et extrayez dans le dossier `Dataset` de sorte à avoir l'arborescence suivante :
```
|-./Dataset/
    |-yelp_photos_comp/
        |-photos/
        |-Dataset_User_Agreement.pdf
        |-photos.json
    |-yelp_dataset/
        |-Dataset_User_Agreement.pdf
        |-yelp_academic_dataset_business.json
        |-yelp_academic_dataset_checkin.json
        |-yelp_academic_dataset_review.json
        |-yelp_academic_dataset_tip.json
        |-yelp_academic_dataset_user.json
```

3. Afin d'importer les poids du réseau de neurones et ne pas avoir à faire un entrainement d'une heure. Veillez à bien avoir dans votre dossier courant l'arborescence suivante :
```
|- ./training_1/
    |-cp.ckpt.index
    |-cp.ckpt.data-00000-of-00001
```
4. Assurez-vous d'avoir les deux images `model_accuracy.png` et `model_loss.png` dans le dossier courant. Comme le réseau de neurone ne sera pas entrainé, ces photos serviront à montrer l'évolution des métriques.
5. Installez les packages dans requirements.txt via la commande `pip install -r requirements.txt`. Nous vous conseillons de créer un environnement virtuel au préalable.