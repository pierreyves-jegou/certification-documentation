# *************** Formation "Concurrency" ***************

## Liens utils
* [Cours vidéo "perceptio" (avec tests)]((https://cgi.percipio.com/courses/a31b0176-86e1-4567-bdbd-91493329f09e/videos/a86bd764-95f3-43c0-88c4-5e0c7e48b185))
* [Cours sur Percipio OCP Exam 1Z0-819 and Upgrade Exam 1Z0-817](https://cgi.percipio.com/books/9530c338-69e3-47ef-aa1e-71a116105641#epubcfi(/6/348!/4/2%5Bepubmain%5D/2%5Bch18%5D/2/2/1:0))
* [Post (très) avancé sur la concurrence](https://jenkov.com/tutorials/java-concurrency/blocking-queues.html)

## *** Vue d'ensemble
* Unité de travail : Process / Thread / Task
* Avantages des threads
>* Meilleur utilisation du CPU : les traitements "IO" (lecture disque/requete HTTP/requeteBDD) sont extremement lents par rapport à des traitements CPU et le processeur ne fait quasiment plus rien pendant ces traitements => le multithreading permet de mieux utiliser le CPU
>* Programme plus "reponsive" : le multithreading permet de faire en sorte que les interfaces utilisateurs soient tjs responsive même si d'autres traitements sont lancés en arrière plan
* Inconvénients des threads
* Partage de la mémoire (Shared memory)
* OS thread scheduler
* Run vs Call


## Création d'un Thread

## Comment partager des objects entre threads

## Communication / interraction entre Thread

## Thread & ThreadPool

## Systèmes de synchronisation
### Synchronized
### Cyclic barrier
### Lock
### Semaphore
### Blocking queues

## Livelock / DeadLock / Starvation

## Etats d'un thread

## Daemon

## Structures clef
### AtomicXXXX
### Collections
### Map
### Paralled Stream



## Focus certification
### Méthod de "Executors" vs "ExecutorService"


