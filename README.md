# **CoreLittle — Version 1.2 (Minecraft 1.21.4)**

> 📢 **Annonce importante — Prochaine mise à jour**  
> **CoreLittle fait peau neuve !** À partir de la version **V2.0**, le projet change de nom pour devenir **SculkCore**. Cette transition s'accompagnera d'une refonte du code, d'une meilleure optimisation et de nouvelles fonctionnalités.

---

**CoreLittle** est un plugin polyvalent et léger conçu pour enrichir l'expérience sur votre serveur Minecraft. Il centralise des outils complets adaptés à tous les rôles : Administrateurs, Builders, Créateurs de contenu, Joueurs VIP et Joueurs classiques.

---

### **Fonctionnalités principales**
* **Gestion globale** : Outils d'administration, de modération et commandes utilitaires.
* **Personnalisation** : Messages, TabList et système de grades 100% configurables.
* **Permissions intégrées** : Contrôle fin des accès pour chaque commande.

---

### **Nouveautés de la V1.2**
* **Système de Ranks** : Création et gestion de grades personnalisés.
* **TabList dynamique** : Mise en forme du TabList via un fichier de configuration dédié.
* **Menu GUI `/staff`** : Interface graphique moderne pour administrer le serveur *(en cours de développement)*.

---

### Configuration :
Les fichiers de configuration se trouvent dans le dossier de votre serveur :  
`plugins/CoreLittle/rank.yml` et `plugins/CoreLittle/TabList.yml`

---

### **Liste des commandes**

#### **Nouveautés V1.2**
* `/setrank <joueur> <grade>` : Modifie le grade d'un joueur.
* `/staff` : Ouvre l'interface GUI d'administration.

#### **Administration & Modération**
* `/stop` : Arrête le serveur avec un décompte de 10 secondes.
* `/ban <joueur>` : Banned un joueur en ligne.
* `/banoffline <joueur>` : Banned un joueur hors-ligne.
* `/unban <joueur>` (ou `/pardon`) : Débannit un joueur.
* `/op <joueur>` : Accorde les privilèges d'opérateur.
* `/deop <joueur>` : Retire les privilèges d'opérateur.
* `/gm <0|1|2|3>` : Change rapidement de mode de jeu.
* `/broadcast <message>` : Diffuse un message global à tout le serveur.
* `/freeze <joueur>` : Gèle ou dégèle un joueur.
* `/vanish` : Rend le joueur invisible aux yeux des autres.
* `/spawn-pet` : Fait apparaître un familier.
* `/pet` : Transforme le joueur en animal *(actuellement : chien)*.

#### **Outils de Build**
* `/set <bloc>` : Remplit la zone sélectionnée *(Bugs connus en cours de résolution)*.
* `/cut` : Supprime les blocs de la zone sélectionnée.
* `/undo` : Annule la dernière action de construction.

#### **Avantages VIP**
* `/hat` : Place le bloc tenu en main sur la tête.
* `/skin <pseudo>` : Modifie l'apparence du joueur.

#### **Créateurs de contenu (Streamers)**
* `/streammode` : Active le mode Streamer *(Masque les liens du chat et coupe les sons gênants — en développement)*.

#### **Joueurs & Général**
* `/help [admin|staff|vip|streamer]` : Affiche le menu d'aide général ou par catégorie.
