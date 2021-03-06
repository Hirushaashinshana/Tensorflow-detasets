# red_caps

References:

*   [Code](https://github.com/huggingface/datasets/blob/master/datasets/red_caps)
*   [Huggingface](https://huggingface.co/datasets/red_caps)


## all


Use the following command to load this dataset in TFDS:

```python
ds = tfds.load('huggingface:red_caps/all')
```

*   **Description**:

```
RedCaps is a large-scale dataset of 12M image-text pairs collected from Reddit.
Images and captions from Reddit depict and describe a wide variety of objects and scenes.
The data is collected from a manually curated set of subreddits (350 total),
which give coarse image labels and allow steering of the dataset composition
without labeling individual instances.
```

*   **License**: CC BY 4.0
*   **Version**: 1.0.0
*   **Splits**:

Split  | Examples
:----- | -------:
`'train'` | 12011121

*   **Features**:

```json
{
    "image_id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "author": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "image_url": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "raw_caption": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "caption": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "subreddit": {
        "num_classes": 350,
        "names": [
            "abandonedporn",
            "abandoned",
            "absoluteunits",
            "airplants",
            "alltheanimals",
            "amateurphotography",
            "amateurroomporn",
            "animalporn",
            "antiques",
            "antkeeping",
            "ants",
            "aquariums",
            "architectureporn",
            "artefactporn",
            "astronomy",
            "astrophotography",
            "australiancattledog",
            "australianshepherd",
            "autumnporn",
            "averagebattlestations",
            "awwducational",
            "awwnverts",
            "axolotls",
            "backpacking",
            "backyardchickens",
            "baking",
            "ballpython",
            "barista",
            "bassfishing",
            "battlestations",
            "bbq",
            "beagle",
            "beardeddragons",
            "beekeeping",
            "beerandpizza",
            "beerporn",
            "beerwithaview",
            "beginnerwoodworking",
            "bengalcats",
            "bento",
            "bernesemountaindogs",
            "berries",
            "bettafish",
            "bicycling",
            "bikecommuting",
            "birding",
            "birdphotography",
            "birdpics",
            "birdsofprey",
            "birds",
            "blackcats",
            "blacksmith",
            "bladesmith",
            "boatporn",
            "bonsai",
            "bookporn",
            "bookshelf",
            "bordercollie",
            "bostonterrier",
            "botanicalporn",
            "breadit",
            "breakfastfood",
            "breakfast",
            "bridgeporn",
            "brochet",
            "budgetfood",
            "budgies",
            "bulldogs",
            "burgers",
            "butterflies",
            "cabinporn",
            "cactus",
            "cakedecorating",
            "cakewin",
            "cameras",
            "campingandhiking",
            "camping",
            "carnivorousplants",
            "carpentry",
            "carporn",
            "cassetteculture",
            "castiron",
            "castles",
            "casualknitting",
            "catpictures",
            "cats",
            "ceramics",
            "chameleons",
            "charcuterie",
            "cheesemaking",
            "cheese",
            "chefit",
            "chefknives",
            "chickens",
            "chihuahua",
            "chinchilla",
            "chinesefood",
            "churchporn",
            "cider",
            "cityporn",
            "classiccars",
            "cockatiel",
            "cocktails",
            "coffeestations",
            "coins",
            "cookiedecorating",
            "corgi",
            "cornsnakes",
            "cozyplaces",
            "crafts",
            "crestedgecko",
            "crochet",
            "crossstitch",
            "crows",
            "crystals",
            "cupcakes",
            "dachshund",
            "damnthatsinteresting",
            "desertporn",
            "designmyroom",
            "desksetup",
            "dessertporn",
            "dessert",
            "diy",
            "dobermanpinscher",
            "doggos",
            "dogpictures",
            "drunkencookery",
            "duck",
            "dumpsterdiving",
            "earthporn",
            "eatsandwiches",
            "embroidery",
            "entomology",
            "equestrian",
            "espresso",
            "exposureporn",
            "eyebleach",
            "f1porn",
            "farming",
            "femalelivingspace",
            "fermentation",
            "ferrets",
            "fireporn",
            "fishing",
            "fish",
            "flowers",
            "flyfishing",
            "foodporn",
            "food",
            "foraging",
            "fossilporn",
            "fountainpens",
            "foxes",
            "frenchbulldogs",
            "frogs",
            "gardening",
            "gardenwild",
            "geckos",
            "gemstones",
            "geologyporn",
            "germanshepherds",
            "glutenfree",
            "goldenretrievers",
            "goldfish",
            "gold",
            "greatpyrenees",
            "grilledcheese",
            "grilling",
            "guineapigs",
            "gunporn",
            "guns",
            "hamsters",
            "handtools",
            "healthyfood",
            "hedgehog",
            "helicopters",
            "herpetology",
            "hiking",
            "homestead",
            "horses",
            "hotpeppers",
            "houseplants",
            "houseporn",
            "husky",
            "icecreamery",
            "indoorgarden",
            "infrastructureporn",
            "insects",
            "instantpot",
            "interestingasfuck",
            "interiordesign",
            "itookapicture",
            "jellyfish",
            "jewelry",
            "kayakfishing",
            "kayaking",
            "ketorecipes",
            "knifeporn",
            "knives",
            "labrador",
            "leathercraft",
            "leopardgeckos",
            "lizards",
            "lookatmydog",
            "macarons",
            "machineporn",
            "macroporn",
            "malelivingspace",
            "mead",
            "mealprepsunday",
            "mechanicalkeyboards",
            "mechanicalpencils",
            "melts",
            "metalworking",
            "microgreens",
            "microporn",
            "mildlyinteresting",
            "mineralporn",
            "monitors",
            "monstera",
            "mostbeautiful",
            "motorcycleporn",
            "muglife",
            "mushroomgrowers",
            "mushroomporn",
            "mushrooms",
            "mycology",
            "natureisfuckinglit",
            "natureporn",
            "nebelung",
            "orchids",
            "otters",
            "outdoors",
            "owls",
            "parrots",
            "pelletgrills",
            "pens",
            "perfectfit",
            "permaculture",
            "photocritique",
            "photographs",
            "pics",
            "pitbulls",
            "pizza",
            "plantbaseddiet",
            "plantedtank",
            "plantsandpots",
            "plants",
            "pomeranians",
            "pottery",
            "pourpainting",
            "proplifting",
            "pugs",
            "pug",
            "quilting",
            "rabbits",
            "ramen",
            "rarepuppers",
            "reeftank",
            "reptiles",
            "resincasting",
            "roomporn",
            "roses",
            "rottweiler",
            "ruralporn",
            "sailing",
            "salsasnobs",
            "samoyeds",
            "savagegarden",
            "scotch",
            "seaporn",
            "seriouseats",
            "sewing",
            "sharks",
            "shiba",
            "shihtzu",
            "shrimptank",
            "siamesecats",
            "siberiancats",
            "silverbugs",
            "skyporn",
            "sloths",
            "smoking",
            "snails",
            "snakes",
            "sneakers",
            "sneks",
            "somethingimade",
            "soup",
            "sourdough",
            "sousvide",
            "spaceporn",
            "spicy",
            "spiderbro",
            "spiders",
            "squirrels",
            "steak",
            "streetphotography",
            "succulents",
            "superbowl",
            "supermodelcats",
            "sushi",
            "tacos",
            "tarantulas",
            "tastyfood",
            "teaporn",
            "tea",
            "tequila",
            "terrariums",
            "thedepthsbelow",
            "thriftstorehauls",
            "tinyanimalsonfingers",
            "tonightsdinner",
            "toolporn",
            "tools",
            "torties",
            "tortoise",
            "tractors",
            "trailrunning",
            "trains",
            "trucks",
            "turtle",
            "underwaterphotography",
            "upcycling",
            "urbanexploration",
            "urbanhell",
            "veganfoodporn",
            "veganrecipes",
            "vegetablegardening",
            "vegetarian",
            "villageporn",
            "vintageaudio",
            "vintage",
            "vinyl",
            "volumeeating",
            "watches",
            "waterporn",
            "weatherporn",
            "wewantplates",
            "wildernessbackpacking",
            "wildlifephotography",
            "wine",
            "winterporn",
            "woodcarving",
            "woodworking",
            "workbenches",
            "workspaces",
            "yarnaddicts",
            "zerowaste"
        ],
        "id": null,
        "_type": "ClassLabel"
    },
    "score": {
        "dtype": "int32",
        "id": null,
        "_type": "Value"
    },
    "created_utc": {
        "dtype": "timestamp[s, tz=UTC]",
        "id": null,
        "_type": "Value"
    },
    "permalink": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "crosspost_parents": {
        "feature": {
            "dtype": "string",
            "id": null,
            "_type": "Value"
        },
        "length": -1,
        "id": null,
        "_type": "Sequence"
    }
}
```


