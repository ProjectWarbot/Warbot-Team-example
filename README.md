# Warbot-Team-example
Exemple d'une équipe Warbot

### Changelog

- Chargement d'équipes scriptées totalement fonctionnel (en dossier)
-- Python (par fonctions)
-- Javascript (avec classes)

- Chargement d'équipes Java fonctionnel (En jar, uniquement sur Eclipse)

## Utilisation

Modifiez le fichier config.yml en fonction du nouveau nom de votre équipe. (et de votre package)

### Console

Compilez votre équipe en .jar. (avec les resources)

Lancer la commande suivante

"""java -cp libs/warbot-${version}.jar edu.warbot.launcher.WarMain """

### Eclipse

Rajoutez la librairie warbot du dossier libs dans votre "build path". (Clique droit > BuildPath > Add)

A l'aide du fichier jar-description.jardesc, vous pouvez produire le jar de votre équipe java.

Vous devez ensuite exécuter la classe edu.warbot.launcher.WarMain. Rajoutez une nouvelle configuration de type
"Java Application".

### Intellij Idea

Rajoutez la librairie warbot aux dépendances de votre projet. (Project Structure > Modules > Dependencies)

Créez une configuration "Jar Application" dont le jar

## Divers


