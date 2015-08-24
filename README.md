# iba_dataset_json

A dataset scraped and cleaned from the International Bartenders Association website, containing JSON entries for each cocktail.

This currently contains two files:

* recipes.json - a list of JSON associative arrays, each of which represents a recipe for a cocktail. All measurements are in centilitres. An example: 
```
  {
    "name": "RUSTY NAIL",
    "ingredients": [
      {
        "name": "scotch whisky",
        "quantity": 4.5
      },
      {
        "name": "drambuie",
        "quantity": 2.5
      }
    ],
    "type": "After Dinner Cocktail"
  }
```
* ingredients_strength.json - a supplementary file mapping each ingredient to a decimal number giving its alcohol by volume (ABV).
