# Comptes signalés pour propos haineux

Liste publique et collaborative de comptes X (Twitter) ayant publié des contenus haineux au sens de la loi française. Chaque personne peut l'importer en un clic pour bloquer ces comptes depuis son propre profil.

*English: a community-maintained list of X accounts that posted hateful content under French law, importable in one click to block them from your own account.*

## Utiliser la liste

1. Installer l'extension **X Block List Manager** (Chrome, Edge, Brave ou Firefox).
2. Ouvrir x.com, connecté à son compte.
3. Ouvrir le tableau de bord de l'extension et coller cette adresse dans le champ **Load from URL** :

   ```
   https://raw.githubusercontent.com/common-blocklist/blocklist/main/list.txt
   ```

4. Relire la liste qui s'affiche. Rien n'est bloqué à ce stade.
5. Cliquer sur **Block these accounts**.

Le blocage se fait un compte après l'autre, avec une pause entre chaque. Pour plusieurs centaines de comptes, il faut compter plusieurs heures. Laissez l'onglet x.com ouvert.

**Avertissement.** L'extension agit dans votre session X comme si vous cliquiez vous-même. X n'autorise pas officiellement l'automatisation : bloquer beaucoup de comptes d'un coup peut entraîner une déconnexion ou une limitation temporaire de votre compte. Gardez un délai d'au moins 2 secondes et procédez par lots si vous le souhaitez.

## Ce que contient la liste

Un compte n'est ajouté que s'il a publié au moins un contenu correspondant aux [critères](CRITERES.md), avec une preuve archivée. La liste ne classe personne selon ses opinions politiques : elle recense des **publications**, pas des personnes.

Le fichier [`list.txt`](list.txt) contient un identifiant par ligne. Les lignes qui commencent par `#` sont des commentaires (nom de la liste, date de mise à jour, liens).

## Contribuer

- **Proposer un ajout** : ouvrir une [demande d'ajout](../../issues/new?template=ajout.yml), avec le lien vers la publication et une archive.
- **Demander un retrait** : voir la [procédure de retrait](RETRAIT.md). Elle est ouverte à tous, y compris aux titulaires des comptes listés.

Chaque ajout est vérifié par au moins une personne de l'équipe avant d'être fusionné. En cas de doute, le compte n'est pas ajouté.

## Licence

La liste et la documentation sont placées sous [CC0 1.0](LICENSE) : vous pouvez les réutiliser librement.
