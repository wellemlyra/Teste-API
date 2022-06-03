# Teste-API
Teste de API para candidatos

## Descrição
 <p>Logo abaixa estará dois exemplos de entrada e saida de acordo com as descrições dos testes 1 e 2 respectivamente</p>


### Teste 1 

```
http://localhost:8080/v1/calc-avail/7110?dataCheckIn=01-06-2022&dataCheckOut=04-06-2022&adults=2&childs=1
```

```
[
    {
        "id": 3,
        "cityName": "Rio de Janeiro",
        "rooms": [
            {
                "roomId": 0,
                "categoryName": "Standard",
                "totalPrice": 11945.87,
                "pricesDetail": {
                    "pricePerDayAdult": 3304.41,
                    "pricePerDayChild": 1753.29
                }
            },
            {
                "roomId": 1,
                "categoryName": "Luxo",
                "totalPrice": 10968.86,
                "pricesDetail": {
                    "pricePerDayAdult": 3478.95,
                    "pricePerDayChild": 720.30
                }
            },
            {
                "roomId": 2,
                "categoryName": "Triplo",
                "totalPrice": 7836.08,
                "pricesDetail": {
                    "pricePerDayAdult": 1402.65,
                    "pricePerDayChild": 2679.96
                }
            }
        ]
    },
    {
        "id": 8,
        "cityName": "Rio de Janeiro",
        "rooms": [
            {
                "roomId": 0,
                "categoryName": "Standard",
                "totalPrice": 21040.03,
                "pricesDetail": {
                    "pricePerDayAdult": 5903.37,
                    "pricePerDayChild": 2921.28
                }
            },
            {
                "roomId": 1,
                "categoryName": "Luxo",
                "totalPrice": 11354.48,
                "pricesDetail": {
                    "pricePerDayAdult": 2987.73,
                    "pricePerDayChild": 1972.68
                }
            }
        ]
    }, etc etc etc.......
```

### Teste 2
```
http://localhost:8080/v1/calc-hotel/1
```
```
{
    "id": 1,
    "cityName": "Porto Seguro",
    "rooms": [
        {
            "roomId": 0,
            "categoryName": "Standard",
            "totalPrice": 3173.07,
            "pricesDetail": {
                "pricePerDayAdult": 1372.54,
                "pricePerDayChild": 848.61
            }
        }
    ]
}
```
