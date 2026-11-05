# Bouchée : produits hors ligne

Extraits français d'Open Food Facts que l'application Bouchée peut télécharger pour reconnaître les codes-barres sans internet. Les fichiers sont dans les [Releases](../../releases).

## Contenu

Chaque Release contient `manifest.json` et des paquets `off_fr_<date>_<niveau>.bin`. Les produits sont classés selon leur nombre de scans. Un niveau s'ajoute aux niveaux inférieurs : le niveau 80 demande les paquets 50, 60, 70 et 80. Le niveau 100 ajoute tous les autres produits français exploitables.

Champs conservés : code-barres, nom, marque, portion, contenance, calories et macronutriments pour 100 g, sodium, Nutri-Score, groupe NOVA, additifs, allergènes.

## Licence et attribution

Ces données proviennent d'[Open Food Facts](https://world.openfoodfacts.org) et ont été filtrées et reformatées pour cette application.

Cette base est mise à disposition sous la licence [Open Database License (ODbL) 1.0](https://opendatacommons.org/licenses/odbl/1-0/). Tout droit sur le contenu individuel de la base est soumis à la licence [Database Contents License](https://opendatacommons.org/licenses/dbcl/1-0/).

## Avertissement

Ces données viennent de contributions bénévoles et peuvent être incomplètes ou fausses. Elles ne conviennent pas à un usage médical : vérifiez toujours l'étiquette, surtout pour les allergènes.
