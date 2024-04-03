## Explorando os recursos da IA Generativa

Proposto para este laboratório final será feita a descrição da extração de textos. As imagens utilizadas estarão no diretório inputs e os resultados gerados no diretório outputs.

# 1º Criação de um recurso no Azure al services

[Portal Azure](http:/www.portal.azure.com)

- Em Categorias AI + Machine Learning.
- Azure Al Services
- Create

![Criando um recurso](https://github.com/cezarscarvalho/DIO-Projeto-Microsoft-IA-Generativa/assets/158849910/cecb6d1d-5bcd-41de-aea4-739d14c30a5a)

# 💡
Não esqueça de marcar a Caixa de diálogo

![Caixa de texto](https://github.com/cezarscarvalho/DIO-Projeto-Microsoft-IA-Generativa/assets/158849910/214a651a-2363-4e7c-88be-740299f291f3)

![Review](https://github.com/cezarscarvalho/DIO-Projeto-Microsoft-IA-Generativa/assets/158849910/7c30e5e0-44da-4013-91ea-1a2d9e91282d)

# 2º Configurando o Portal Al Vision Studio

[Vision Studio Azure](http:/https://portal.vision.cognitive.azure.com)

Caso o recurso criado não apareça na tela inicial, deveremos seleciona-lo.

![Inicinado no Vision](https://github.com/cezarscarvalho/DIO-Projeto-Microsoft-IA-Generativa/assets/158849910/a4fd751a-3c4c-4b6a-b9d1-42895fd3b28a)

- Selecionar Optical character recognition 

![Caracter Optico](https://github.com/cezarscarvalho/DIO-Projeto-Microsoft-IA-Generativa/assets/158849910/8079c1fa-9c0e-4664-ba9e-dd3ef49c0f66)

![Extração de Textos](https://github.com/cezarscarvalho/DIO-Projeto-Microsoft-IA-Generativa/assets/158849910/968c5ff9-2f1a-42d6-83c3-afff4e7f7259)

- Selecione a caixa de diálogo
- Baixe a foto da sua máquina ou tire uma

# Foto 01 e Resultados

![Foto 01](https://github.com/cezarscarvalho/DIO-Projeto-Microsoft-IA-Generativa/assets/158849910/e52a7595-5d07-47f7-a9c7-a018a3737800)

![Json foto 01](https://github.com/cezarscarvalho/DIO-Projeto-Microsoft-IA-Generativa/assets/158849910/4d8525cc-2467-4b13-b363-8388b1632de7)


```


  {
    "lines": [
      {
        "text": "Northwind Traders",
        "boundingPolygon": [
          {
            "x": 78,
            "y": 65
          },
          {
            "x": 1019,
            "y": 64
          },
          {
            "x": 1019,
            "y": 164
          },
          {
            "x": 78,
            "y": 165
          }
        ],
        "words": [
          {
            "text": "Northwind",
            "boundingPolygon": [
              {
                "x": 78,
                "y": 70
              },
              {
                "x": 600,
                "y": 65
              },
              {
                "x": 600,
                "y": 166
              },
              {
                "x": 78,
                "y": 158
              }
            ],
            "confidence": 0.995
          },
          {
            "text": "Traders",
            "boundingPolygon": [
              {
                "x": 653,
                "y": 65
              },
              {
                "x": 1016,
                "y": 64
              },
              {
                "x": 1016,
                "y": 161
              },
              {
                "x": 653,
                "y": 166
              }
            ],
            "confidence": 0.994
          }
        ]
      },
      {
        "text": "PIE WINNER",
        "boundingPolygon": [
          {
            "x": 1604,
            "y": 102
          },
          {
            "x": 1678,
            "y": 62
          },
          {
            "x": 1694,
            "y": 95
          },
          {
            "x": 1620,
            "y": 138
          }
        ],
        "words": [
          {
            "text": "PIE",
            "boundingPolygon": [
              {
                "x": 1604,
                "y": 104
              },
              {
                "x": 1621,
                "y": 93
              },
              {
                "x": 1640,
                "y": 127
              },
              {
                "x": 1619,
                "y": 138
              }
            ],
            "confidence": 0.137
          },
          {
            "text": "WINNER",
            "boundingPolygon": [
              {
                "x": 1627,
                "y": 89
              },
              {
                "x": 1675,
                "y": 62
              },
              {
                "x": 1694,
                "y": 96
              },
              {
                "x": 1647,
                "y": 123
              }
            ],
            "confidence": 0.636
          }
        ]
      },
      {
        "text": "Fresh produce,",
        "boundingPolygon": [
          {
            "x": 75,
            "y": 260
          },
          {
            "x": 478,
            "y": 260
          },
          {
            "x": 478,
            "y": 322
          },
          {
            "x": 75,
            "y": 324
          }
        ],
        "words": [
          {
            "text": "Fresh",
            "boundingPolygon": [
              {
                "x": 76,
                "y": 263
              },
              {
                "x": 215,
                "y": 261
              },
              {
                "x": 216,
                "y": 325
              },
              {
                "x": 76,
                "y": 325
              }
            ],
            "confidence": 0.998
          },
          {
            "text": "produce,",
            "boundingPolygon": [
              {
                "x": 233,
                "y": 260
              },
              {
                "x": 477,
                "y": 262
              },
              {
                "x": 478,
                "y": 322
              },
              {
                "x": 233,
                "y": 325
              }
            ],
            "confidence": 0.994
          }
        ]
      },
      {
        "text": "friendly service",
        "boundingPolygon": [
          {
            "x": 72,
            "y": 339
          },
          {
            "x": 490,
            "y": 337
          },
          {
            "x": 490,
            "y": 404
          },
          {
            "x": 73,
            "y": 405
          }
        ],
        "words": [
          {
            "text": "friendly",
            "boundingPolygon": [
              {
                "x": 73,
                "y": 341
              },
              {
                "x": 282,
                "y": 341
              },
              {
                "x": 282,
                "y": 405
              },
              {
                "x": 73,
                "y": 405
              }
            ],
            "confidence": 0.994
          },
          {
            "text": "service",
            "boundingPolygon": [
              {
                "x": 296,
                "y": 341
              },
              {
                "x": 483,
                "y": 338
              },
              {
                "x": 484,
                "y": 405
              },
              {
                "x": 296,
                "y": 405
              }
            ],
            "confidence": 0.997
          }
        ]
      },
      {
        "text": "Open 7 days a week",
        "boundingPolygon": [
          {
            "x": 1158,
            "y": 1069
          },
          {
            "x": 1709,
            "y": 1066
          },
          {
            "x": 1709,
            "y": 1131
          },
          {
            "x": 1158,
            "y": 1134
          }
        ],
        "words": [
          {
            "text": "Open",
            "boundingPolygon": [
              {
                "x": 1160,
                "y": 1070
              },
              {
                "x": 1305,
                "y": 1069
              },
              {
                "x": 1304,
                "y": 1134
              },
              {
                "x": 1159,
                "y": 1134
              }
            ],
            "confidence": 0.993
          },
          {
            "text": "7",
            "boundingPolygon": [
              {
                "x": 1327,
                "y": 1069
              },
              {
                "x": 1357,
                "y": 1069
              },
              {
                "x": 1356,
                "y": 1134
              },
              {
                "x": 1326,
                "y": 1134
              }
            ],
            "confidence": 0.994
          },
          {
            "text": "days",
            "boundingPolygon": [
              {
                "x": 1370,
                "y": 1069
              },
              {
                "x": 1499,
                "y": 1068
              },
              {
                "x": 1498,
                "y": 1133
              },
              {
                "x": 1369,
                "y": 1134
              }
            ],
            "confidence": 0.993
          },
          {
            "text": "a",
            "boundingPolygon": [
              {
                "x": 1512,
                "y": 1068
              },
              {
                "x": 1542,
                "y": 1067
              },
              {
                "x": 1541,
                "y": 1133
              },
              {
                "x": 1511,
                "y": 1133
              }
            ],
            "confidence": 0.998
          },
          {
            "text": "week",
            "boundingPolygon": [
              {
                "x": 1555,
                "y": 1067
              },
              {
                "x": 1700,
                "y": 1066
              },
              {
                "x": 1699,
                "y": 1132
              },
              {
                "x": 1554,
                "y": 1133
              }
            ],
            "confidence": 0.993
          }
        ]
      }
    ]
  }
]
 ```

 # Foto 02 e Resultados


![Foto 02](https://github.com/cezarscarvalho/DIO-Projeto-Microsoft-IA-Generativa/assets/158849910/eb2d6bbf-0047-421d-bcdc-94a0b52a019d)

![Json foto 02](https://github.com/cezarscarvalho/DIO-Projeto-Microsoft-IA-Generativa/assets/158849910/d61f9a88-e260-4a7c-9f42-453d04303686)


```
 [
  {
    "lines": [
      {
        "text": "Shopping List",
        "boundingPolygon": [
          {
            "x": 231,
            "y": 141
          },
          {
            "x": 693,
            "y": 147
          },
          {
            "x": 691,
            "y": 245
          },
          {
            "x": 230,
            "y": 240
          }
        ],
        "words": [
          {
            "text": "Shopping",
            "boundingPolygon": [
              {
                "x": 240,
                "y": 141
              },
              {
                "x": 535,
                "y": 149
              },
              {
                "x": 531,
                "y": 245
              },
              {
                "x": 234,
                "y": 234
              }
            ],
            "confidence": 0.963
          },
          {
            "text": "List",
            "boundingPolygon": [
              {
                "x": 554,
                "y": 149
              },
              {
                "x": 689,
                "y": 147
              },
              {
                "x": 686,
                "y": 244
              },
              {
                "x": 550,
                "y": 245
              }
            ],
            "confidence": 0.83
          }
        ]
      },
      {
        "text": "Non- Fat milk",
        "boundingPolygon": [
          {
            "x": 149,
            "y": 302
          },
          {
            "x": 633,
            "y": 297
          },
          {
            "x": 633,
            "y": 374
          },
          {
            "x": 150,
            "y": 378
          }
        ],
        "words": [
          {
            "text": "Non-",
            "boundingPolygon": [
              {
                "x": 150,
                "y": 303
              },
              {
                "x": 309,
                "y": 301
              },
              {
                "x": 310,
                "y": 378
              },
              {
                "x": 153,
                "y": 378
              }
            ],
            "confidence": 0.577
          },
          {
            "text": "Fat",
            "boundingPolygon": [
              {
                "x": 324,
                "y": 301
              },
              {
                "x": 438,
                "y": 300
              },
              {
                "x": 437,
                "y": 378
              },
              {
                "x": 325,
                "y": 378
              }
            ],
            "confidence": 0.842
          },
          {
            "text": "milk",
            "boundingPolygon": [
              {
                "x": 476,
                "y": 299
              },
              {
                "x": 620,
                "y": 298
              },
              {
                "x": 617,
                "y": 374
              },
              {
                "x": 475,
                "y": 377
              }
            ],
            "confidence": 0.994
          }
        ]
      },
      {
        "text": "Bread",
        "boundingPolygon": [
          {
            "x": 138,
            "y": 400
          },
          {
            "x": 382,
            "y": 399
          },
          {
            "x": 383,
            "y": 472
          },
          {
            "x": 138,
            "y": 474
          }
        ],
        "words": [
          {
            "text": "Bread",
            "boundingPolygon": [
              {
                "x": 152,
                "y": 400
              },
              {
                "x": 366,
                "y": 400
              },
              {
                "x": 368,
                "y": 471
              },
              {
                "x": 151,
                "y": 475
              }
            ],
            "confidence": 0.995
          }
        ]
      },
      {
        "text": "Eggs",
        "boundingPolygon": [
          {
            "x": 146,
            "y": 517
          },
          {
            "x": 351,
            "y": 526
          },
          {
            "x": 348,
            "y": 605
          },
          {
            "x": 146,
            "y": 609
          }
        ],
        "words": [
          {
            "text": "Eggs",
            "boundingPolygon": [
              {
                "x": 149,
                "y": 517
              },
              {
                "x": 342,
                "y": 519
              },
              {
                "x": 341,
                "y": 610
              },
              {
                "x": 148,
                "y": 609
              }
            ],
            "confidence": 0.992
          }
        ]
      }
    ]
  }
]
```

# Foto 3 e Resultados

![Foto 03](https://github.com/cezarscarvalho/DIO-Projeto-Microsoft-IA-Generativa/assets/158849910/ed3411d2-c96a-460d-b805-5e904cec8716)

![Json foto 03](https://github.com/cezarscarvalho/DIO-Projeto-Microsoft-IA-Generativa/assets/158849910/5b5d729a-0474-4f5a-b203-1c09e906de8f)

```
[
  {
    "lines": [
      {
        "text": "Northwind Traders",
        "boundingPolygon": [
          {
            "x": 19,
            "y": 16
          },
          {
            "x": 234,
            "y": 15
          },
          {
            "x": 235,
            "y": 45
          },
          {
            "x": 19,
            "y": 45
          }
        ],
        "words": [
          {
            "text": "Northwind",
            "boundingPolygon": [
              {
                "x": 20,
                "y": 17
              },
              {
                "x": 141,
                "y": 17
              },
              {
                "x": 140,
                "y": 45
              },
              {
                "x": 20,
                "y": 46
              }
            ],
            "confidence": 0.994
          },
          {
            "text": "Traders",
            "boundingPolygon": [
              {
                "x": 151,
                "y": 17
              },
              {
                "x": 234,
                "y": 16
              },
              {
                "x": 233,
                "y": 46
              },
              {
                "x": 150,
                "y": 45
              }
            ],
            "confidence": 0.996
          }
        ]
      },
      {
        "text": "123 Main Street",
        "boundingPolygon": [
          {
            "x": 17,
            "y": 73
          },
          {
            "x": 174,
            "y": 73
          },
          {
            "x": 174,
            "y": 94
          },
          {
            "x": 17,
            "y": 94
          }
        ],
        "words": [
          {
            "text": "123",
            "boundingPolygon": [
              {
                "x": 18,
                "y": 74
              },
              {
                "x": 52,
                "y": 74
              },
              {
                "x": 52,
                "y": 94
              },
              {
                "x": 18,
                "y": 94
              }
            ],
            "confidence": 0.994
          },
          {
            "text": "Main",
            "boundingPolygon": [
              {
                "x": 57,
                "y": 74
              },
              {
                "x": 105,
                "y": 74
              },
              {
                "x": 104,
                "y": 94
              },
              {
                "x": 57,
                "y": 94
              }
            ],
            "confidence": 0.993
          },
          {
            "text": "Street",
            "boundingPolygon": [
              {
                "x": 113,
                "y": 74
              },
              {
                "x": 173,
                "y": 74
              },
              {
                "x": 173,
                "y": 95
              },
              {
                "x": 113,
                "y": 94
              }
            ],
            "confidence": 0.997
          }
        ]
      },
      {
        "text": "555-123-4567",
        "boundingPolygon": [
          {
            "x": 17,
            "y": 128
          },
          {
            "x": 150,
            "y": 128
          },
          {
            "x": 150,
            "y": 149
          },
          {
            "x": 17,
            "y": 149
          }
        ],
        "words": [
          {
            "text": "555-123-4567",
            "boundingPolygon": [
              {
                "x": 17,
                "y": 129
              },
              {
                "x": 149,
                "y": 130
              },
              {
                "x": 149,
                "y": 149
              },
              {
                "x": 17,
                "y": 150
              }
            ],
            "confidence": 0.994
          }
        ]
      },
      {
        "text": "2/17/2020 13:07",
        "boundingPolygon": [
          {
            "x": 15,
            "y": 182
          },
          {
            "x": 190,
            "y": 182
          },
          {
            "x": 190,
            "y": 205
          },
          {
            "x": 15,
            "y": 206
          }
        ],
        "words": [
          {
            "text": "2/17/2020",
            "boundingPolygon": [
              {
                "x": 19,
                "y": 182
              },
              {
                "x": 119,
                "y": 183
              },
              {
                "x": 118,
                "y": 206
              },
              {
                "x": 18,
                "y": 206
              }
            ],
            "confidence": 0.994
          },
          {
            "text": "13:07",
            "boundingPolygon": [
              {
                "x": 136,
                "y": 183
              },
              {
                "x": 190,
                "y": 183
              },
              {
                "x": 190,
                "y": 206
              },
              {
                "x": 135,
                "y": 206
              }
            ],
            "confidence": 0.977
          }
        ]
      },
      {
        "text": "1 Apple",
        "boundingPolygon": [
          {
            "x": 18,
            "y": 267
          },
          {
            "x": 92,
            "y": 266
          },
          {
            "x": 92,
            "y": 289
          },
          {
            "x": 18,
            "y": 289
          }
        ],
        "words": [
          {
            "text": "1",
            "boundingPolygon": [
              {
                "x": 19,
                "y": 267
              },
              {
                "x": 30,
                "y": 267
              },
              {
                "x": 30,
                "y": 290
              },
              {
                "x": 19,
                "y": 290
              }
            ],
            "confidence": 0.994
          },
          {
            "text": "Apple",
            "boundingPolygon": [
              {
                "x": 35,
                "y": 267
              },
              {
                "x": 91,
                "y": 267
              },
              {
                "x": 91,
                "y": 290
              },
              {
                "x": 35,
                "y": 290
              }
            ],
            "confidence": 0.989
          }
        ]
      },
      {
        "text": "$0.90",
        "boundingPolygon": [
          {
            "x": 166,
            "y": 264
          },
          {
            "x": 222,
            "y": 264
          },
          {
            "x": 223,
            "y": 288
          },
          {
            "x": 166,
            "y": 288
          }
        ],
        "words": [
          {
            "text": "$0.90",
            "boundingPolygon": [
              {
                "x": 168,
                "y": 264
              },
              {
                "x": 222,
                "y": 264
              },
              {
                "x": 222,
                "y": 288
              },
              {
                "x": 168,
                "y": 288
              }
            ],
            "confidence": 0.995
          }
        ]
      },
      {
        "text": "1 Orange",
        "boundingPolygon": [
          {
            "x": 18,
            "y": 322
          },
          {
            "x": 105,
            "y": 322
          },
          {
            "x": 105,
            "y": 344
          },
          {
            "x": 18,
            "y": 344
          }
        ],
        "words": [
          {
            "text": "1",
            "boundingPolygon": [
              {
                "x": 18,
                "y": 323
              },
              {
                "x": 29,
                "y": 323
              },
              {
                "x": 29,
                "y": 344
              },
              {
                "x": 18,
                "y": 344
              }
            ],
            "confidence": 0.995
          },
          {
            "text": "Orange",
            "boundingPolygon": [
              {
                "x": 34,
                "y": 323
              },
              {
                "x": 104,
                "y": 323
              },
              {
                "x": 103,
                "y": 345
              },
              {
                "x": 34,
                "y": 344
              }
            ],
            "confidence": 0.995
          }
        ]
      },
      {
        "text": "$0.80",
        "boundingPolygon": [
          {
            "x": 165,
            "y": 321
          },
          {
            "x": 221,
            "y": 320
          },
          {
            "x": 221,
            "y": 343
          },
          {
            "x": 165,
            "y": 343
          }
        ],
        "words": [
          {
            "text": "$0.80",
            "boundingPolygon": [
              {
                "x": 166,
                "y": 320
              },
              {
                "x": 220,
                "y": 320
              },
              {
                "x": 220,
                "y": 343
              },
              {
                "x": 167,
                "y": 343
              }
            ],
            "confidence": 0.995
          }
        ]
      },
      {
        "text": "Sub-Total",
        "boundingPolygon": [
          {
            "x": 58,
            "y": 377
          },
          {
            "x": 151,
            "y": 376
          },
          {
            "x": 151,
            "y": 397
          },
          {
            "x": 58,
            "y": 397
          }
        ],
        "words": [
          {
            "text": "Sub-Total",
            "boundingPolygon": [
              {
                "x": 60,
                "y": 377
              },
              {
                "x": 152,
                "y": 377
              },
              {
                "x": 151,
                "y": 398
              },
              {
                "x": 60,
                "y": 398
              }
            ],
            "confidence": 0.994
          }
        ]
      },
      {
        "text": "$1.70",
        "boundingPolygon": [
          {
            "x": 167,
            "y": 376
          },
          {
            "x": 226,
            "y": 376
          },
          {
            "x": 225,
            "y": 398
          },
          {
            "x": 166,
            "y": 397
          }
        ],
        "words": [
          {
            "text": "$1.70",
            "boundingPolygon": [
              {
                "x": 172,
                "y": 376
              },
              {
                "x": 223,
                "y": 376
              },
              {
                "x": 223,
                "y": 398
              },
              {
                "x": 172,
                "y": 398
              }
            ],
            "confidence": 0.994
          }
        ]
      },
      {
        "text": "Tax",
        "boundingPolygon": [
          {
            "x": 56,
            "y": 404
          },
          {
            "x": 94,
            "y": 405
          },
          {
            "x": 94,
            "y": 423
          },
          {
            "x": 56,
            "y": 424
          }
        ],
        "words": [
          {
            "text": "Tax",
            "boundingPolygon": [
              {
                "x": 60,
                "y": 404
              },
              {
                "x": 93,
                "y": 404
              },
              {
                "x": 93,
                "y": 424
              },
              {
                "x": 60,
                "y": 424
              }
            ],
            "confidence": 0.994
          }
        ]
      },
      {
        "text": "$0.17",
        "boundingPolygon": [
          {
            "x": 170,
            "y": 403
          },
          {
            "x": 225,
            "y": 402
          },
          {
            "x": 224,
            "y": 424
          },
          {
            "x": 170,
            "y": 425
          }
        ],
        "words": [
          {
            "text": "$0.17",
            "boundingPolygon": [
              {
                "x": 170,
                "y": 403
              },
              {
                "x": 224,
                "y": 402
              },
              {
                "x": 224,
                "y": 424
              },
              {
                "x": 170,
                "y": 425
              }
            ],
            "confidence": 0.993
          }
        ]
      },
      {
        "text": "Total",
        "boundingPolygon": [
          {
            "x": 57,
            "y": 458
          },
          {
            "x": 111,
            "y": 458
          },
          {
            "x": 111,
            "y": 479
          },
          {
            "x": 57,
            "y": 479
          }
        ],
        "words": [
          {
            "text": "Total",
            "boundingPolygon": [
              {
                "x": 60,
                "y": 458
              },
              {
                "x": 110,
                "y": 458
              },
              {
                "x": 110,
                "y": 479
              },
              {
                "x": 60,
                "y": 479
              }
            ],
            "confidence": 0.997
          }
        ]
      },
      {
        "text": "$1.87",
        "boundingPolygon": [
          {
            "x": 169,
            "y": 457
          },
          {
            "x": 225,
            "y": 458
          },
          {
            "x": 224,
            "y": 479
          },
          {
            "x": 169,
            "y": 480
          }
        ],
        "words": [
          {
            "text": "$1.87",
            "boundingPolygon": [
              {
                "x": 171,
                "y": 457
              },
              {
                "x": 224,
                "y": 457
              },
              {
                "x": 224,
                "y": 480
              },
              {
                "x": 171,
                "y": 480
              }
            ],
            "confidence": 0.994
          }
        ]
      }
    ]
  }
]
```

## Essas ferramentas podem vir a otimiar se bem aplicadas em Empresas que direcionem bem os seus objetivos. São ferramentas que desempenham um papel de inclusão seja através da transcrição do texto ou das demais funcionalidades da ferramenta.




