#Consultar la lista de todas las medidas
![image](https://user-images.githubusercontent.com/69479452/153793157-9854bf24-5028-4074-8171-46d436aacf89.png)
[
    {
        "model": "measurements.measurement",
        "pk": 1,
        "fields": {
            "variable": 1,
            "value": 12.0,
            "unit": "C",
            "place": "Bogota",
            "dateTime": "2022-02-14T02:07:38.893Z"
        }
    },
    {
        "model": "measurements.measurement",
        "pk": 2,
        "fields": {
            "variable": 1,
            "value": 10.0,
            "unit": "C",
            "place": "Bogota",
            "dateTime": "2022-02-14T02:08:30.040Z"
        }
    },
    {
        "model": "measurements.measurement",
        "pk": 3,
        "fields": {
            "variable": 2,
            "value": 15.0,
            "unit": "g/m3",
            "place": "House",
            "dateTime": "2022-02-14T02:09:21.685Z"
        }
    },
    {
        "model": "measurements.measurement",
        "pk": 4,
        "fields": {
            "variable": 2,
            "value": 25.0,
            "unit": "g/m3",
            "place": "Bathroom",
            "dateTime": "2022-02-14T02:09:41.975Z"
        }
    }
]

#Consultar medida dado su identificador
![image](https://user-images.githubusercontent.com/69479452/153796731-30089ab8-87ee-45cc-8544-2b804ca45630.png)
[
    {
        "model": "measurements.measurement",
        "pk": 1,
        "fields": {
            "variable": 1,
            "value": 12.0,
            "unit": "C",
            "place": "Bogota",
            "dateTime": "2022-02-14T02:07:38.893Z"
        }
    }
]
#Borrar una medida dado su identificador
![image](https://user-images.githubusercontent.com/69479452/153799013-afa3ce61-38ec-4399-bf01-a054e495520f.png)
[
    {
        "model": "measurements.measurement",
        "pk": 1,
        "fields": {
            "variable": 1,
            "value": 12.0,
            "unit": "C",
            "place": "Bogota",
            "dateTime": "2022-02-14T02:07:38.893Z"
        }
    }
]
#Crear medida y cambiar medida dado su identificador, no funcionaron correctamente
![image](https://user-images.githubusercontent.com/69479452/153800381-cd73a547-e5ac-4be2-9012-62e21c46dfd2.png)
![image](https://user-images.githubusercontent.com/69479452/153800435-97e51f88-9898-403c-9d55-d8f6bd92df9f.png)

