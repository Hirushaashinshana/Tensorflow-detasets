# turkish_shrinked_ner

References:

*   [Code](https://github.com/huggingface/datasets/blob/master/datasets/turkish_shrinked_ner)
*   [Huggingface](https://huggingface.co/datasets/turkish_shrinked_ner)



Use the following command to load this dataset in TFDS:

```python
ds = tfds.load('huggingface:turkish_shrinked_ner')
```

*   **Description**:

```
Shrinked version (48 entity type) of the turkish_ner.

Original turkish_ner dataset: Automatically annotated Turkish corpus for named entity recognition and text categorization using large-scale gazetteers. The constructed gazetteers contains approximately 300K entities with thousands of fine-grained entity types under 25 different domains.

Shrinked entity types are: academic, academic_person, aircraft, album_person, anatomy, animal, architect_person, capital, chemical, clothes, country, culture, currency, date, food, genre, government, government_person, language, location, material, measure, medical, military, military_person, nation, newspaper, organization, organization_person, person, production_art_music, production_art_music_person, quantity, religion, science, shape, ship, software, space, space_person, sport, sport_name, sport_person, structure, subject, tech, train, vehicle
```

*   **License**: Attribution 4.0 International (CC BY 4.0)
*   **Version**: 0.0.0
*   **Splits**:

Split  | Examples
:----- | -------:
`'train'` | 614515

*   **Features**:

```json
{
    "id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "tokens": {
        "feature": {
            "dtype": "string",
            "id": null,
            "_type": "Value"
        },
        "length": -1,
        "id": null,
        "_type": "Sequence"
    },
    "ner_tags": {
        "feature": {
            "num_classes": 97,
            "names": [
                "O",
                "B-academic",
                "I-academic",
                "B-academic_person",
                "I-academic_person",
                "B-aircraft",
                "I-aircraft",
                "B-album_person",
                "I-album_person",
                "B-anatomy",
                "I-anatomy",
                "B-animal",
                "I-animal",
                "B-architect_person",
                "I-architect_person",
                "B-capital",
                "I-capital",
                "B-chemical",
                "I-chemical",
                "B-clothes",
                "I-clothes",
                "B-country",
                "I-country",
                "B-culture",
                "I-culture",
                "B-currency",
                "I-currency",
                "B-date",
                "I-date",
                "B-food",
                "I-food",
                "B-genre",
                "I-genre",
                "B-government",
                "I-government",
                "B-government_person",
                "I-government_person",
                "B-language",
                "I-language",
                "B-location",
                "I-location",
                "B-material",
                "I-material",
                "B-measure",
                "I-measure",
                "B-medical",
                "I-medical",
                "B-military",
                "I-military",
                "B-military_person",
                "I-military_person",
                "B-nation",
                "I-nation",
                "B-newspaper",
                "I-newspaper",
                "B-organization",
                "I-organization",
                "B-organization_person",
                "I-organization_person",
                "B-person",
                "I-person",
                "B-production_art_music",
                "I-production_art_music",
                "B-production_art_music_person",
                "I-production_art_music_person",
                "B-quantity",
                "I-quantity",
                "B-religion",
                "I-religion",
                "B-science",
                "I-science",
                "B-shape",
                "I-shape",
                "B-ship",
                "I-ship",
                "B-software",
                "I-software",
                "B-space",
                "I-space",
                "B-space_person",
                "I-space_person",
                "B-sport",
                "I-sport",
                "B-sport_name",
                "I-sport_name",
                "B-sport_person",
                "I-sport_person",
                "B-structure",
                "I-structure",
                "B-subject",
                "I-subject",
                "B-tech",
                "I-tech",
                "B-train",
                "I-train",
                "B-vehicle",
                "I-vehicle"
            ],
            "names_file": null,
            "id": null,
            "_type": "ClassLabel"
        },
        "length": -1,
        "id": null,
        "_type": "Sequence"
    }
}
```


