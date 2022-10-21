# halloween fight game

Spelet går ut på att två motståndare skall välja mellan olika karaktärer att ha i sitt lag. När spelet startas skall en vinnare slumpas.

Spara spelat spel i en collection. Förslagsvis 'matches'. Där spelare 1 och spelare 2 skall vara med, vem som vann och hur laguppställningen såg ut.

Du ska ha en databas med olika fighters som en användare skall kunna välja bland för sin laguppställning, förslagsvis i en collection som kan heta 'fighters'.

## Sammanfattning
* En db med fighters
* En db med spelade matcher
* Kunna starta en match och välja lag
* Spara spelad match i db
* Användning av React och TypeScript i frontend
* Användning av Node, express och firestore i backend

```
[
    {
        id: 0,
        name: 'Count Dracula',
        speciality: 'sleep, spook, drink blood, repeat'
    },
    {
        id: 1,
        name: "A fast Frankenstein's monster",
        speciality: "like regular Frankenstein's monster, but fast. I mean, look at his chest, he has just finished a marathon."
    },
    {
        id: 2,
        name: 'Ghost',
        speciality: "rattle some chains"
    },
    {
        id: 3,
        name: "Jason",
        speciality: "what doesn't this psychopath do"
        }
    },
    {
        id: 4,
        name: 'Samara',
        speciality: "she'll weird you out and disturb you everytime you watch tv"
        }
    },
    {
        id: 5,
        name: 'Scarecrow',
        speciality: "if you have trouble with crows on your crops - this is your man"
    },
    {
        id: 6,
        name: 'Troll',
        speciality: "a gentle soul who wants to be your ally (read friend)"
        }
    },
    {
        id: 7,
        name: 'Witch',
        speciality: "she's mostly into animals and love potions"
    },
]
```

## Level ups:
* Inloggning
* Mer avancerad spellogik (AKA inte slumpa vinnare)
* Lägga till nya karaktärer
* Deploya backend och frontend
* Lägga till matcher i efterhand

