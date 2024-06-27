# Prerequisite

First of all, you will need a virtualization software (VirtualBox / VMware), and an Ubuntu **.iso** image.
Below you will find the links to the official sites for VirtualBox, VMware and Ubuntu :

- [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
- [VMware](https://www.vmware.com/products/workstation-player/workstation-player-evaluation.html)
- [Ubuntu](https://ubuntu.com/download/desktop)


# Creating a Virtual Machine

The first step will be to install your virtualization software (just install the **.exe** file you have downloaded).
Then we'll start creating a **VM** (**V**irtual **M**achine), make sure your Ubuntu .iso file is downloaded.

*You will find the installation steps depending on the software of your choice below.*

<details>
  <summary>Virtual Box</summary>

  ---
  Start creating your VM on **VirtualBox** by clicking on the *New* button.
  
  > ![VBox_0](https://github.com/Mizvchi/42Perpignan_ressources/assets/173720716/6bb940e5-8652-4874-ab7b-11023192b696)


  You will be prompted to choose a name, change the VM location, and finally, choose your .iso image.
  If you choose to check the "*Skip Unattended Installation*" option *(First picture)*, you will make your credentials when starting the VM for the first time instead of doing it inside the software.
  If unchecked, you will make your credentials on the next window *(Second picture)*.

  > ![VBox_1 1](https://github.com/Mizvchi/EN__42Perpignan_Resources/assets/173720716/bbf8b4f5-b836-4927-b849-be72322a038c)
  > ![VBox_1 2](https://github.com/Mizvchi/EN__42Perpignan_Resources/assets/173720716/579868a1-b4cd-4808-8146-8c441829662e)


  Next step is to allocate hardware resources for the VM.
  It is recommended to allocate half of your computer's resources.
  In my case, I have 16GB of RAM and an 8 Cores CPU, so I will allocate 8GB of RAM and 4 Cores.
  
  > *To convert your RAM from GB to MB, multiply the GB by **1024***. (In my case, **8 * 1024 = 8192**)
  > 
  > If you don't know how much RAM nor CPU Cores you have on your computer, open the **Task Manager** (*Ctrl + Shift + Escape*) and go to the *Performance* section.

  > ![VBox_2](https://github.com/Mizvchi/42Perpignan_ressources/assets/173720716/e9af0f71-f771-4b47-b1e9-f85d620ccd6f)
  

  Finally, you can create a *Virtual Hard Disk* and change it's size, the default one being 25GB.
  
  > ![VBox_3](https://github.com/Mizvchi/42Perpignan_ressources/assets/173720716/c1ff6ca6-f554-483f-892c-b8a38e6678bc)
  

  You will then have a summary of your settings for the VM, which once added, will be on the left side of the main window.
  Now you can start your VM by double-clicking it, or simply click the *Start* button. *(Thank you Captain Obvious...)*
  
  > ![VBox_4](https://github.com/Mizvchi/42Perpignan_ressources/assets/173720716/e47878c8-9cd5-4e74-abe8-43db3ea3f972)
  > ![VBox_5](https://github.com/Mizvchi/42Perpignan_ressources/assets/173720716/dc632093-f340-468d-af9b-a3edda936e5c)
</details>

<details>
  <summary>VMware</summary>

  ---
  Start creating your VM on **VMware** by clicking on the "*Create a New Virtual Machine*".

  > ![VMW_0](https://github.com/Mizvchi/42Perpignan_ressources/assets/173720716/c9a10834-12c8-4825-a8f9-6e02defbb6c6)


  You will first be prompted to select your .iso file.

  > ![VMW_1](https://github.com/Mizvchi/EN__42Perpignan_Resources/assets/173720716/221eb9ef-c47c-458d-bf03-c2478b18d1e2)


  Unlike VirtualBox, you can't choose whether you want to make your credentials while creating the VM, or when booting and installing Ubuntu.
  You will therefore be asked by default to create them at this stage.

  > ![VMW_2](https://github.com/Mizvchi/EN__42Perpignan_Resources/assets/173720716/9bf70127-7c79-4b16-8a67-33c8a0461e18)


  Then you can name your VM, change it's location, and create a *Virtual Hard Disk*.
  The choice of storage option is up to you.

  > ![VMW_3](https://github.com/Mizvchi/EN__42Perpignan_Resources/assets/173720716/699b0487-42e0-4cdf-b02b-301160a1b272)
  > ![VMW_4](https://github.com/Mizvchi/EN__42Perpignan_Resources/assets/173720716/df502387-d00a-42d7-a214-e1228bf3c92b)


  Finally, you will have a summary of the chosen settings and you will also be able to customize the allocation of hardware resources.

  It is recommended to allocate half of your computer's resources.
  In my case, I have 16GB of RAM and an 8 Cores CPU, so I will allocate 8GB of RAM and 4 Cores.
  
  > *To convert your RAM from GB to MB, multiply the GB by **1024***. (In my case, **8 * 1024 = 8192**)
  > 
  > If you don't know how much RAM nor CPU Cores you have on your computer, open the **Task Manager** (*Ctrl + Shift + Escape*) and go to the *Performance* section.

  > ![VMW_5 1](https://github.com/Mizvchi/EN__42Perpignan_Resources/assets/173720716/34a756af-e7c2-402f-b325-03ec7e886825)
  > ![VMW_5 2](https://github.com/Mizvchi/EN__42Perpignan_Resources/assets/173720716/da5ae9ea-68ec-4b5e-a9a5-8364d971e919)


  Now you can start your VM by double-clicking it, or simply click the *Play* button. *(Thank you Captain Obvious...)*

  > ![VMW_6](https://github.com/Mizvchi/EN__42Perpignan_Resources/assets/173720716/7ea0a979-d22b-4053-a6c7-08e27412c926)
</details>


# Ubuntu configuration


