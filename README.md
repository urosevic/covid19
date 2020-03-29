# covid19
Кумулативни отворени подаци о случајевима у току епидемије COVID-19 у Србији у JSON формату добијени процесирањем Гугл табеле https://bit.ly/covid19-srbija

Ове податке можете слободно користити за своје пројекта.

Датасет садржи испод наведене JSON нодове:

```
{
    "name": "COVID-19 Srbija Community Data",
    "description": "Подаци о случајевима у току епидемије COVID-19 у Србији",
    "homepage": "https://github.com/urosevic/covid19",
    "license": "ODC Open Database License (ODbL)",
    "author":
    {
        "name": "Александар Урошевић",
        "email": "urke.kg@gmail.com"
    },
    "source": "https://bit.ly/covid19-srbija",
    "updated": "YYYY-MM-DDTHH:MM:SS+02:00",
    "latest":
    {
        "date": "DD/MM/YYYY HH:MM",
        "totals":
        {
            "tested": 2085,
            "confirmed": 659,
            "fatal": 10,
            "hospitalized": 334,
            "recovered": 0,
            "ventilator": 49,
            "caseP": "31.61",
            "fatalP": "1.52"
        },
        "details":
        {
            "positive": 131,
            "hospital": 22,
            "personal": 109,
            "negative": 240,
            "fatal": 2,
            "recovered": 0,
            "totalTested": 371
        },
        "info":
        {
            "refs": ["URL1", "URL2"],
            "note": "..."
        }
    },
    "data": [
    {
        "date": "DD/MM/YYY HH:MM",
        "totals":
        {
            "tested": 0,
            "confirmed": 0,
            "fatal": 0,
            "hospitalized": 0,
            "recovered": 0,
            "ventilator": 0,
            "caseP": "0.00",
            "fatalP": "0.00"
        },
        "details":
        {
            "positive": 0,
            "hospital": 0,
            "personal": 0,
            "negative": 0,
            "fatal": 0,
            "recovered": 0,
            "totalTested": 0
        },
        "info":
        {
            "refs": ["URL"],
            "note": "..."
        }
    }]
}
```
