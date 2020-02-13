# Scratch-si-wolof
Traduire Scratch en Wolof

![GitHub Logo](assets/img/intro.png)

## Rejoindre l'équipe
Vous avez une bonne maîtrise de scratch et du Wolof, parler Anglais ou Français. Rejoignez-nous

<ol>
    <li>Inscrivez-vous ici https://www.transifex.com/</li>
    <li>Rejoignez l’équipe Scratch</li>
    <li>Rejoindre la traduction en wolof</li>
</ol>

## Traduction

### En ligne
Vous pouvez traduire en ligne sur [transifex.com](https://www.transifex.com/)

### Locale
Avec l'aide Transifex CLI vous pouvez traduire en locale.

**Installation Transifex CLI**

Sous linux tapez la commande suivante

```
sudo apt install transifex-client
````

Sous Windows

**Initialisation projet**
Vous avez besoin d'un Token, allez à [https://www.transifex.com/user/settings/api/](https://www.transifex.com/user/settings/api/) pour vous générer un clé.

Tapez les commande suivantes

```
git clone https://github.com/KaayCoder/Scratch-si-wolof.git
cd Scratch-si-wolof
tx init --token=<votre_token_Transifex>
```
Si cela ne marche pas faites
```
sudo tx init --token=<votre_token_Transifex>
```
Pas besoin d'entrer le chemin local,tapez **ctrl-z** pour sortir

**Configuration projet**

tapez la commande suivante

```
tx config mapping-remote https://www.transifex.com/llk/scratch-editor/
```
**Téléchargez Traduction**
Avec la commande suivante vous allez télécharger la traduction en Wolof

```
sudo tx pull -l wo
```

La traduction est dans le dossier **translations**


## Référence


## Contribuer

Lisez s'il vous plait [CONTRIBUTING.md](CONTRIBUTING.md) pour plus de détails sur notre code de conduite et le processus de soumission des demandes de contribution.

## contributeurs

* Votant des sondages sur le compte twitter [@kaaycoder](https://twitter.com/kaaycoder)

## Auteurs

* **Mamadou Diagne** - [Genova](https://github.com/genova)

## Licence

Ce projet est sous licence MIT - voir le fichier [LICENSE](LICENSE) pour plus de détails.
