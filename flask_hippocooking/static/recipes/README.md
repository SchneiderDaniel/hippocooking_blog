# 0 Text 
Bitte korrigiere diesen Text, aber behalte den Stil des textes: 


# 1 Prompt for json creation:
"Please provide the following list of recipe ingredients in JSON format. Each ingredient should be listed on a new line, with no additional attributes.  Keep all the units"

# 1.1 Stichpunkte

Bitte schreibe den Inhalt unten in eine json struktur wie hier
recipeInstructions": [
      {
        "@type": "HowToStep",
        "name": "YYYYY",
        "text": "XXXXX"
      }
]
Der key "name" soll eine Zusammenfassung in 1-3 worten von "text" sein.
zusätzlich, kannst du hier auch die Rechtschreibung prüfen und korrigieren, aber nur wenig verändern?
Der Text ist:


# 2. Prompt um die Nutrion werte zu schätzen.

Ganz Unten findest du ein rezept als json im google recipe schema. Kannst du bitte zu diesem rezept die Nutrition Werte schätzen und eintragen. Das schema habe ich unten auch ergänzt. Bitte trage die Nutritionwerte für das gesamte Rezept ein in integriere es in mein Beispiel json. 
"nutrition": {
    "@type": "NutritionInformation",
    "calories": "xxx kcal",
    "proteinContent": "xxx g",
    "carbohydrateContent": "xx g",
    "fatContent": "xx g",
    "servingSize": "xxx",
    "servingCalories": "xxx kcal"
  }

Hier ist das Rezept als json:


# 3. Prompt for Translation

Could you please translate the values of this JSON into German (de), English (en), Spanish (es) and French (fr)? Also correct writing error, but keep the changes minimal. For each language, provide a separate output. Please do not translate the types in the json. Also make sure that prepTime, cookTime and totalTime are in the ISO 8601 timeformat. But do not add 0 minutes or 0 hours in the format. So no 0H or 0M: 



# HTML texte

Unten ist eine json beigefügt. Bitte prüfe hier als erstes die Rechschreibung der values. Danach übersetze die values der json in English, spanisch und französisch. Bitte gebe mir alle 4 json codes zum kopieren:






## Prompt für name hinzu
bitte füge in dieser json zu recipeInstructions für jedes element einen  key "name" hinzu. Der Value soll in 1-3 worten deb Text zusammenfassen.



## Kategorien:
- Vorspeise
- Hauptspeise
- Dessert
- Kuchen
- Weihnachtsplätzchen
- Kekse
- Frühstück



## Küchen:

- Amerikanisch
- Indisch
- Deutsch
- Italienisch
- Ungarisch
- Chinesisch
- Thailändisch
- Türkisch
- Griechisch
- Österreichisch
- Schweizerisch
- Englisch


## Keywords
- XXL
- Curry
- Gesund
- Schnell
- Vegetarisch
- Vegan
- Weihnachten
- Liebling
- Süß
- Backen
- Einfach



