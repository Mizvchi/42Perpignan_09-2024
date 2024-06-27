# Prérequis

Tout d'abord, vous aurez besoin d'un logiciel de virtualisation (VirtualBox/VMware), et d'une image Ubuntu **.iso**.
Vous trouverez ci-dessous les liens vers les sites officiels de VirtualBox, VMware et Ubuntu :

- [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
- [VMware](https://www.vmware.com/products/workstation-player/workstation-player-evaluation.html)
- [Ubuntu](https://ubuntu.com/download/desktop)


# Créer une Machine Virtuelle

La première étape sera d'installer votre logiciel de virtualisation (il suffit d'installer le fichier **.exe** que vous aurez téléchargé).
Ensuite, nous commencerons à créer une **VM** (**V**irtual **M**achine), assurez-vous que votre fichier Ubuntu .iso est téléchargé.

*Vous trouverez ci-dessous les étapes d'installation en fonction du logiciel de votre choix.*

<details>
  <summary>Virtual Box</summary>

  ---
  Commencez à créer votre VM sur **VirtualBox** en cliquant sur le bouton *Nouveau*.
    
  > ![VBox_0](https://github.com/Mizvchi/42Perpignan_ressources/assets/173720716/6bb940e5-8652-4874-ab7b-11023192b696)


  Vous serez invité à choisir un nom, à modifier l'emplacement de la VM et enfin, à choisir votre image .iso.
  Si vous choisissez de cocher l'option "*Ignorer l'installation sans surveillance*" *(Première image)*, vous créerez vos informations d'identification lors du premier démarrage de la VM au lieu de le faire dans le logiciel.
  Si cette case n'est pas cochée, vous créerez vos informations d'identification dans la fenêtre suivante *(Deuxième image)*.

  > ![VBox_1 1](https://github.com/Mizvchi/EN__42Perpignan_Resources/assets/173720716/bbf8b4f5-b836-4927-b849-be72322a038c)
  > ![VBox_1 2](https://github.com/Mizvchi/EN__42Perpignan_Resources/assets/173720716/579868a1-b4cd-4808-8146-8c441829662e)


  L'étape suivante consiste à allouer des ressources matérielles à la VM.
  Il est recommandé d'allouer la moitié des ressources de votre ordinateur.
  Dans mon cas, j'ai 16 Go de RAM et un processeur 8 cœurs, j'allouerai donc 8 Go de RAM et 4 cœurs.

  > *Pour convertir votre RAM de Go en Mo, multipliez le Go par **1024***. (Dans mon cas, **8 * 1024 = 8192**)
  >
  > Si vous ne savez pas combien de RAM ni de cœurs de processeur vous avez sur votre ordinateur, ouvrez le **Gestionnaire des tâches** (*Ctrl + Shift + Escape*) et accédez à la section *Performances*.

  > ![VBox_2](https://github.com/Mizvchi/42Perpignan_ressources/assets/173720716/e9af0f71-f771-4b47-b1e9-f85d620ccd6f)


  Enfin, vous pouvez créer un *Disque dur virtuel* et modifier sa taille, celle par défaut étant de 25 Go.

  > ![VBox_3](https://github.com/Mizvchi/42Perpignan_ressources/assets/173720716/c1ff6ca6-f554-483f-892c-b8a38e6678bc)


  Vous aurez alors un résumé de vos paramètres pour la VM, qui une fois ajouté, se trouvera sur le côté gauche de la fenêtre principale.
  Vous pouvez maintenant démarrer votre VM en double-cliquant dessus ou simplement en cliquant sur le bouton *Démarrer*. *(Merci Capitaine Obvious...)*

  > ![VBox_4](https://github.com/Mizvchi/42Perpignan_ressources/assets/173720716/e47878c8-9cd5-4e74-abe8-43db3ea3f972)
  > ![VBox_5](https://github.com/Mizvchi/42Perpignan_ressources/assets/173720716/dc632093-f340-468d-af9b-a3edda936e5c)
</details>

<details>
  <summary>VMware</summary>

  ---
  Commencez à créer votre VM sur **VMware** en cliquant sur "*Créer une nouvelle machine virtuelle*".

  > ![VMW_0](https://github.com/Mizvchi/42Perpignan_ressources/assets/173720716/c9a10834-12c8-4825-a8f9-6e02defbb6c6)


  Vous serez d’abord invité à sélectionner votre fichier .iso.

  > ![VMW_1](https://github.com/Mizvchi/EN__42Perpignan_Resources/assets/173720716/221eb9ef-c47c-458d-bf03-c2478b18d1e2)


  Contrairement à VirtualBox, vous ne pouvez pas choisir si vous souhaitez créer vos informations d'identification lors de la création de la VM ou lors du démarrage et de l'installation d'Ubuntu.
  Il vous sera donc demandé par défaut de les créer à ce stade.

  > ![VMW_2](https://github.com/Mizvchi/EN__42Perpignan_Resources/assets/173720716/9bf70127-7c79-4b16-8a67-33c8a0461e18)


  Vous pouvez ensuite nommer votre VM, modifier son emplacement et créer un *Disque dur virtuel*.
  Le choix de l'option de stockage vous appartient.

  > ![VMW_3](https://github.com/Mizvchi/EN__42Perpignan_Resources/assets/173720716/699b0487-42e0-4cdf-b02b-301160a1b272)
  > ![VMW_4](https://github.com/Mizvchi/EN__42Perpignan_Resources/assets/173720716/df502387-d00a-42d7-a214-e1228bf3c92b)


  Enfin, vous aurez un récapitulatif des paramètres choisis et vous pourrez également personnaliser l'allocation des ressources matérielles.

  Il est recommandé d'allouer la moitié des ressources de votre ordinateur.
  Dans mon cas, j'ai 16 Go de RAM et un processeur 8 cœurs, j'allouerai donc 8 Go de RAM et 4 cœurs.

  > *Pour convertir votre RAM de Go en Mo, multipliez le Go par **1024***. (Dans mon cas, **8 * 1024 = 8192**)
  >
  > Si vous ne savez pas combien de RAM ni de cœurs de processeur vous avez sur votre ordinateur, ouvrez le **Gestionnaire des tâches** (*Ctrl + Shift + Escape*) et accédez à la section *Performances*.

  > ![VMW_5 1](https://github.com/Mizvchi/EN__42Perpignan_Resources/assets/173720716/34a756af-e7c2-402f-b325-03ec7e886825)
  > ![VMW_5 2](https://github.com/Mizvchi/EN__42Perpignan_Resources/assets/173720716/da5ae9ea-68ec-4b5e-a9a5-8364d971e919)


  Vous pouvez maintenant démarrer votre VM en double-cliquant dessus ou simplement en cliquant sur le bouton *Play*. *(Merci Capitaine Obvious...)*

  > ![VMW_6](https://github.com/Mizvchi/EN__42Perpignan_Resources/assets/173720716/7ea0a979-d22b-4053-a6c7-08e27412c926)  
</details>


# Configuration Ubuntu


