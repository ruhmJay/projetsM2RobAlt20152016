# Projet Alternants M2 Rob 2015 2016
Ces projets ont pour vocation première de vous sensibiliser à la recherche académique sur des sujets d'actualité en robotique. Ils peuvent prendre plusieurs dimensions :
* Projet "*Recherche Bibliographique*" [BIB] : Une thématique vous intéresse, proche de votre sujet d'alternance ou simplement par curiosité scientifique. Le projet vise à étudier l'état de l'art dans cette discipline et à produire un bref article au format scientifique.
* Projet "*Robotique mobile*" [Rob] : Vous devrez implémenter des algorithmes dédiés à la robotique sur une des plateformes de l'option (Nao, Voiture RC, Turtlebot, R2D2). Ce projet vise à montrer l'utilisation de ces plateformes comme vecteur de développement rapide pour les algorithmes en robotique.
* Projet "*Intégration/Développement*" [Rob/TR] : Un projet entre Robotique et Télécom/Rx avec utilisation de ROS sur plateforme embarquée (ARM V8/9, même processeur que sur BeagleBone, FPGA, ...)

## Sujets possibles :
* **Intelligence Artificielle** [BIB]. Il s'agit d'établir un état de l'art sur l'intelligence artificielle : définitions, méthodes existantes et perspectives académiques en cours.
 * Modalités d'évaluation : 10' d'exposé scientifique sur le sujet - rapport sous forme d'article scientifique entre 2 et 5 pages.
 * Prérequis : Bon niveau d'anglais, bonne pédagogie, esprit de synthèse.
* **Contrôle d'un essaim de robots** [BIB]. Il s'agit d'établir un état de l'art sur la SWARM Intelligence, méthodes de contrôle d'une meute de robots. Ces techniques visent à contrôler un grand nombre de robots comme une entité, sans qu'il n'y ait de leader (on parlerait alors de meute).
 * Modalités d'évaluation : 10' d'exposé scientifique sur le sujet - rapport sous forme d'article scientifique entre 2 et 5 pages.
 * Prérequis : Bon niveau d'anglais, bonne pédagogie, esprit de synthèse.
* **Contrôle d'un essaim de robots** [Rob]. Le projet vise à utiliser un grand nombre de turtlebots en réseau. ROS n'a pas été conçu pour l'utilisation en meute (la communication se fait habituellement avec 1 master et n slaves, ce qui n'est pas cohérent avec une approche type SWARM) et le déploiement d'une telle architecture n'est pas triviale. Des outils existent mais sont encore en développement.
 * Modalités d'évaluation : 10' d'exposé sur le sujet - rapport entre 2 et 5 pages (manuel d'utilisation si le projet est fonctionnel).
 * Prérequis : ROS, C++, réseau, aptitudes techniques.
* **Simulation d'un essaim de robots** [Rob]. Il s'agit de simuler un essaim de robot à travers un middleware dédié à la robotique (ROS, MOOS ou autre)
 * Modalités d'évaluation : 10' d'exposé sur le sujet - rapport entre 2 et 5 pages (manuel d'utilisation si le projet est fonctionnel).
 * Prérequis : MOOS, C++, système, aptitudes techniques.
* **Driver MOOS pour base Kobuki** [Rob]. Il s'agit de développer un driver MOOS pour le contrôle de la base des turtlebot : Kobuki.
 * Modalités d'évaluation : 10' d'exposé sur le sujet - rapport entre 2 et 5 pages (manuel d'utilisation si le projet est fonctionnel).
 * Prérequis : MOOS, C++, système, aptitudes techniques.
* **Projet dual ROB/TR** [Rob]. Les architectures à base de microprocesseurs ARM sont de plus en plus utilisées (smartphones, beaglebone, raspberry pi, ...). D'un autre point de vue, les FPGA sont des composants dédiés à embarquer des applications nécessitant une forte puissance de calcul inatteignable sur processeurs. Le projet vise à faire cohabiter ces deux entités sur une carte d'évaluation ZedBoard. Ces cartes sont équipées d'un ARMV8 (ou V9?) et d'un FPGA. ROS étant déjà en partie accessible pour ARM, des projets voient le jour pour l'utilisation des FPGA comme périphériques ROS. Ce projet doit permettre une telle utilisation des FPGA.
 * Modalités d'évaluation : 10' d'exposé sur le sujet - rapport entre 2 et 5 pages (manuel d'utilisation si le projet est fonctionnel).
 * Prérequis : ROS, C++, système, aptitudes techniques.
* **Projet R2D2** [Rob]. Le projet vise à améliorer le robot R2D2 de l'ISEN par l'apport de nouvelles fonctionnalités.
 * Modalités d'évaluation : 10' d'exposé sur le sujet - rapport entre 2 et 5 pages (manuel d'utilisation si le projet est fonctionnel).
 * Prérequis : Beaglebone, C++, système, aptitudes techniques.

## Remarques
Tous les projets incluant du développement doivent utiliser le gestionnaire de version GIT à travers la plateforme GitHub de l'ISEN. Ce point est très important pour la pérennité de votre travail, le suivi du projet et participera donc à l'évaluation.
De plus, ceux qui ne travaillent pas encore avec ce genre d'outils y seront sensibilisés.

MaJ le 6 Juin 2016 - Clément Aubry - clement.aubry@isen-bretagne.fr
