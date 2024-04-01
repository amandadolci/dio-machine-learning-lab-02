### Image analysis - Add caption to images (store-camera-1.jpg)

```json
{
	"apim-request-id": "a311caeb-2a0b-4de9-9029-59393fc9e721",
	"content-length": "165",
	"content-type": "application/json; charset=utf-8",
	"modelVersion": "2023-10-01",
	"captionResult": {
		"text": "a woman and a girl in a grocery store",
		"confidence": 0.7764207124710083
	},
	"metadata": {
		"width": 1024,
		"height": 682
	}
}
```

### Image analysis - Add dense captions to images (store-camera-1.jpg)

```json
{
	"apim-request-id": "b9171bb9-d2fe-4f66-8003-ba5b2267c88e",
	"content-length": "1363",
	"content-type": "application/json; charset=utf-8",
	"modelVersion": "2023-10-01",
	"denseCaptionsResult": {
		"values": [
			{
				"text": "a woman and a girl in a grocery store",
				"confidence": 0.7764207124710083,
				"boundingBox": {
					"x": 0,
					"y": 0,
					"w": 1024,
					"h": 682
				}
			},
			{
				"text": "a woman smiling while holding a phone",
				"confidence": 0.7425119280815125,
				"boundingBox": {
					"x": 212,
					"y": 47,
					"w": 342,
					"h": 591
				}
			},
			{
				"text": "a person holding a phone case",
				"confidence": 0.7824985980987549,
				"boundingBox": {
					"x": 441,
					"y": 197,
					"w": 75,
					"h": 102
				}
			},
			{
				"text": "a woman wearing a purple hat",
				"confidence": 0.7497276663780212,
				"boundingBox": {
					"x": 467,
					"y": 311,
					"w": 433,
					"h": 357
				}
			},
			{
				"text": "a woman holding a cell phone to a girl in a store",
				"confidence": 0.7348417043685913,
				"boundingBox": {
					"x": 0,
					"y": 0,
					"w": 997,
					"h": 664
				}
			},
			{
				"text": "a person holding a piece of ginger",
				"confidence": 0.765824556350708,
				"boundingBox": {
					"x": 701,
					"y": 246,
					"w": 156,
					"h": 119
				}
			},
			{
				"text": "a close-up of a person wearing a purple hat",
				"confidence": 0.7765249609947205,
				"boundingBox": {
					"x": 652,
					"y": 324,
					"w": 236,
					"h": 207
				}
			},
			{
				"text": "a woman smiling at a cell phone",
				"confidence": 0.719761312007904,
				"boundingBox": {
					"x": 242,
					"y": 53,
					"w": 250,
					"h": 390
				}
			},
			{
				"text": "a row of jars on a shelf",
				"confidence": 0.711879312992096,
				"boundingBox": {
					"x": 0,
					"y": 301,
					"w": 217,
					"h": 120
				}
			},
			{
				"text": "a blurry image of a person standing in a room",
				"confidence": 0.7165694236755371,
				"boundingBox": {
					"x": 0,
					"y": 484,
					"w": 540,
					"h": 190
				}
			}
		]
	},
	"metadata": {
		"width": 1024,
		"height": 682
	}
}
```

### Image analysis - Extract common tags from images (store-camera-2.jpg)

```json
{
	"apim-request-id": "5c5a7cfc-033c-4a7b-9a5b-7c222039b712",
	"content-length": "1088",
	"content-type": "application/json; charset=utf-8",
	"modelVersion": "2023-10-01",
	"metadata": {
		"width": 1024,
		"height": 682
	},
	"tagsResult": {
		"values": [
			{
				"name": "roupas",
				"confidence": 0.9903867244720459
			},
			{
				"name": "pessoa",
				"confidence": 0.9825903177261353
			},
			{
				"name": "loja de conveniência",
				"confidence": 0.9799700975418091
			},
			{
				"name": "varejo",
				"confidence": 0.9788037538528442
			},
			{
				"name": "supermercado",
				"confidence": 0.9576846361160278
			},
			{
				"name": "loja de mantimentos",
				"confidence": 0.9418376684188843
			},
			{
				"name": "compras",
				"confidence": 0.9195953011512756
			},
			{
				"name": "cliente",
				"confidence": 0.9176949262619019
			},
			{
				"name": "texto",
				"confidence": 0.906154215335846
			},
			{
				"name": "comércio",
				"confidence": 0.9014638066291809
			},
			{
				"name": "rosto humano",
				"confidence": 0.9004635810852051
			},
			{
				"name": "interior",
				"confidence": 0.8902596235275269
			},
			{
				"name": "mulher",
				"confidence": 0.88371741771698
			},
			{
				"name": "venda",
				"confidence": 0.8815276622772217
			},
			{
				"name": "loja",
				"confidence": 0.8811236619949341
			},
			{
				"name": "mercado",
				"confidence": 0.8682040572166443
			},
			{
				"name": "prateleira",
				"confidence": 0.6904568672180176
			},
			{
				"name": "em pé",
				"confidence": 0.6564067602157593
			},
			{
				"name": "feira",
				"confidence": 0.5118435025215149
			}
		]
	}
}
```

### Image analysis - Detect common objects in images (store-camera-3.jpg)

```json
{
	"apim-request-id": "0c842edb-5f65-43a2-8db4-4d9da1dabdd1",
	"content-length": "290",
	"content-type": "application/json; charset=utf-8",
	"modelVersion": "2023-10-01",
	"metadata": {
		"width": 1024,
		"height": 682
	},
	"objectsResult": {
		"values": [
			{
				"boundingBox": {
					"x": 278,
					"y": 154,
					"w": 367,
					"h": 490
				},
				"tags": [
					{
						"name": "person",
						"confidence": 0.848
					}
				]
			},
			{
				"boundingBox": {
					"x": 0,
					"y": 0,
					"w": 717,
					"h": 677
				},
				"tags": [
					{
						"name": "supermarket",
						"confidence": 0.517
					}
				]
			}
		]
	}
}
```

### Face - Detect faces in an image (store-camera-1.jpg)

```json
[
	{
		"recognitionModel": "recognition_01",
		"faceRectangle": {
			"width": 93,
			"height": 144,
			"left": 324,
			"top": 95
		},
		"faceLandmarks": {
			"pupilLeft": {
				"x": 365.5,
				"y": 156.7
			},
			"pupilRight": {
				"x": 404.7,
				"y": 158.1
			},
			"noseTip": {
				"x": 396.8,
				"y": 183.8
			},
			"mouthLeft": {
				"x": 357.5,
				"y": 200.1
			},
			"mouthRight": {
				"x": 398.7,
				"y": 202.3
			},
			"eyebrowLeftOuter": {
				"x": 346.2,
				"y": 146.7
			},
			"eyebrowLeftInner": {
				"x": 381.6,
				"y": 145.9
			},
			"eyeLeftOuter": {
				"x": 358.1,
				"y": 156.6
			},
			"eyeLeftTop": {
				"x": 366,
				"y": 154.6
			},
			"eyeLeftBottom": {
				"x": 365.8,
				"y": 158.6
			},
			"eyeLeftInner": {
				"x": 372,
				"y": 157.1
			},
			"eyebrowRightInner": {
				"x": 400.1,
				"y": 147
			},
			"eyebrowRightOuter": {
				"x": 417,
				"y": 145.8
			},
			"eyeRightInner": {
				"x": 398.6,
				"y": 158.5
			},
			"eyeRightTop": {
				"x": 405,
				"y": 155.7
			},
			"eyeRightBottom": {
				"x": 404.9,
				"y": 159.9
			},
			"eyeRightOuter": {
				"x": 410.3,
				"y": 158.4
			},
			"noseRootLeft": {
				"x": 383,
				"y": 158.7
			},
			"noseRootRight": {
				"x": 395.2,
				"y": 159.2
			},
			"noseLeftAlarTop": {
				"x": 379.9,
				"y": 174.9
			},
			"noseRightAlarTop": {
				"x": 400.2,
				"y": 174.8
			},
			"noseLeftAlarOutTip": {
				"x": 373.8,
				"y": 182.8
			},
			"noseRightAlarOutTip": {
				"x": 402.9,
				"y": 183.2
			},
			"upperLipTop": {
				"x": 388.7,
				"y": 197.5
			},
			"upperLipBottom": {
				"x": 387.4,
				"y": 201.8
			},
			"underLipTop": {
				"x": 385.2,
				"y": 213.5
			},
			"underLipBottom": {
				"x": 384.1,
				"y": 220.1
			}
		},
		"faceAttributes": {
			"mask": {
				"type": "noMask",
				"noseAndMouthCovered": false
			}
		}
	}
]
```

### Face - Detect faces in an image (store-camera-4.jpg)

```json
[
	{
		"recognitionModel": "recognition_01",
		"faceRectangle": {
			"width": 68,
			"height": 113,
			"left": 274,
			"top": 111
		},
		"faceLandmarks": {
			"pupilLeft": {
				"x": 316.1,
				"y": 160.2
			},
			"pupilRight": {
				"x": 333.1,
				"y": 157.2
			},
			"noseTip": {
				"x": 342.3,
				"y": 176.6
			},
			"mouthLeft": {
				"x": 314,
				"y": 194.8
			},
			"mouthRight": {
				"x": 332.5,
				"y": 190.3
			},
			"eyebrowLeftOuter": {
				"x": 304.6,
				"y": 155.9
			},
			"eyebrowLeftInner": {
				"x": 325.2,
				"y": 151.4
			},
			"eyeLeftOuter": {
				"x": 312.5,
				"y": 160.9
			},
			"eyeLeftTop": {
				"x": 316.4,
				"y": 158.9
			},
			"eyeLeftBottom": {
				"x": 316.6,
				"y": 161.2
			},
			"eyeLeftInner": {
				"x": 318.7,
				"y": 159.8
			},
			"eyebrowRightInner": {
				"x": 332.4,
				"y": 150.9
			},
			"eyebrowRightOuter": {
				"x": 335.2,
				"y": 148.3
			},
			"eyeRightInner": {
				"x": 330.6,
				"y": 157.9
			},
			"eyeRightTop": {
				"x": 333.6,
				"y": 155.8
			},
			"eyeRightBottom": {
				"x": 333.6,
				"y": 158
			},
			"eyeRightOuter": {
				"x": 334.4,
				"y": 157
			},
			"noseRootLeft": {
				"x": 325.1,
				"y": 159.9
			},
			"noseRootRight": {
				"x": 331.6,
				"y": 159
			},
			"noseLeftAlarTop": {
				"x": 325.1,
				"y": 172.8
			},
			"noseRightAlarTop": {
				"x": 336.4,
				"y": 169.5
			},
			"noseLeftAlarOutTip": {
				"x": 322.7,
				"y": 179.4
			},
			"noseRightAlarOutTip": {
				"x": 337.3,
				"y": 175.3
			},
			"upperLipTop": {
				"x": 333.4,
				"y": 189.7
			},
			"upperLipBottom": {
				"x": 332.4,
				"y": 192.6
			},
			"underLipTop": {
				"x": 331.9,
				"y": 197.7
			},
			"underLipBottom": {
				"x": 332,
				"y": 202
			}
		},
		"faceAttributes": {
			"mask": {
				"type": "noMask",
				"noseAndMouthCovered": false
			}
		}
	},
	{
		"recognitionModel": "recognition_01",
		"faceRectangle": {
			"width": 69,
			"height": 106,
			"left": 624,
			"top": 80
		},
		"faceLandmarks": {
			"pupilLeft": {
				"x": 630.1,
				"y": 125.4
			},
			"pupilRight": {
				"x": 645.1,
				"y": 124.4
			},
			"noseTip": {
				"x": 622.8,
				"y": 146.4
			},
			"mouthLeft": {
				"x": 635.7,
				"y": 160.3
			},
			"mouthRight": {
				"x": 651.9,
				"y": 160.3
			},
			"eyebrowLeftOuter": {
				"x": 624.9,
				"y": 116.8
			},
			"eyebrowLeftInner": {
				"x": 628.1,
				"y": 117.8
			},
			"eyeLeftOuter": {
				"x": 629.1,
				"y": 125.5
			},
			"eyeLeftTop": {
				"x": 629.4,
				"y": 123.7
			},
			"eyeLeftBottom": {
				"x": 630.2,
				"y": 126.8
			},
			"eyeLeftInner": {
				"x": 631.8,
				"y": 125.5
			},
			"eyebrowRightInner": {
				"x": 634.9,
				"y": 117.1
			},
			"eyebrowRightOuter": {
				"x": 655,
				"y": 115.9
			},
			"eyeRightInner": {
				"x": 642.8,
				"y": 125
			},
			"eyeRightTop": {
				"x": 643.9,
				"y": 122.2
			},
			"eyeRightBottom": {
				"x": 645,
				"y": 126
			},
			"eyeRightOuter": {
				"x": 648.6,
				"y": 124.4
			},
			"noseRootLeft": {
				"x": 631.9,
				"y": 126.4
			},
			"noseRootRight": {
				"x": 636.1,
				"y": 126.5
			},
			"noseLeftAlarTop": {
				"x": 628.2,
				"y": 139.5
			},
			"noseRightAlarTop": {
				"x": 638.2,
				"y": 139.8
			},
			"noseLeftAlarOutTip": {
				"x": 628.5,
				"y": 145.9
			},
			"noseRightAlarOutTip": {
				"x": 641.5,
				"y": 146.8
			},
			"upperLipTop": {
				"x": 634.4,
				"y": 158.6
			},
			"upperLipBottom": {
				"x": 635.3,
				"y": 161
			},
			"underLipTop": {
				"x": 636.3,
				"y": 164.1
			},
			"underLipBottom": {
				"x": 637.1,
				"y": 168.2
			}
		},
		"faceAttributes": {
			"mask": {
				"type": "noMask",
				"noseAndMouthCovered": false
			}
		}
	},
	{
		"recognitionModel": "recognition_01",
		"faceRectangle": {
			"width": 52,
			"height": 86,
			"left": 874,
			"top": 273
		},
		"faceLandmarks": {
			"pupilLeft": {
				"x": 885.8,
				"y": 301
			},
			"pupilRight": {
				"x": 896.1,
				"y": 304.2
			},
			"noseTip": {
				"x": 875.4,
				"y": 316.9
			},
			"mouthLeft": {
				"x": 884.5,
				"y": 335.1
			},
			"mouthRight": {
				"x": 894.3,
				"y": 337.9
			},
			"eyebrowLeftOuter": {
				"x": 883.7,
				"y": 291.9
			},
			"eyebrowLeftInner": {
				"x": 885.2,
				"y": 293.5
			},
			"eyeLeftOuter": {
				"x": 885.4,
				"y": 300.7
			},
			"eyeLeftTop": {
				"x": 885.3,
				"y": 299.5
			},
			"eyeLeftBottom": {
				"x": 885.6,
				"y": 302.2
			},
			"eyeLeftInner": {
				"x": 887,
				"y": 301.5
			},
			"eyebrowRightInner": {
				"x": 889.8,
				"y": 294.7
			},
			"eyebrowRightOuter": {
				"x": 904.4,
				"y": 298.9
			},
			"eyeRightInner": {
				"x": 894.5,
				"y": 303.8
			},
			"eyeRightTop": {
				"x": 895.2,
				"y": 302.2
			},
			"eyeRightBottom": {
				"x": 895.7,
				"y": 305.6
			},
			"eyeRightOuter": {
				"x": 899,
				"y": 305.1
			},
			"noseRootLeft": {
				"x": 886.5,
				"y": 302.3
			},
			"noseRootRight": {
				"x": 889.2,
				"y": 303.2
			},
			"noseLeftAlarTop": {
				"x": 881.6,
				"y": 312.6
			},
			"noseRightAlarTop": {
				"x": 888.3,
				"y": 314.8
			},
			"noseLeftAlarOutTip": {
				"x": 881.3,
				"y": 318.2
			},
			"noseRightAlarOutTip": {
				"x": 889.9,
				"y": 321.6
			},
			"upperLipTop": {
				"x": 882.1,
				"y": 330.2
			},
			"upperLipBottom": {
				"x": 882.9,
				"y": 333
			},
			"underLipTop": {
				"x": 884.7,
				"y": 341.2
			},
			"underLipBottom": {
				"x": 885.1,
				"y": 345.1
			}
		},
		"faceAttributes": {
			"mask": {
				"type": "noMask",
				"noseAndMouthCovered": false
			}
		}
	}
]
```

### Face - Detect faces in an image (store-camera-1(hidden).jpg)

```json
No face detected
```

### OCR - Extract text from images (advert.jpg)

```json
[
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

### OCR - Extract text from images (letter.jpg)

```json
[
	{
		"lines": [
			{
				"text": "January 23rd 2020",
				"boundingPolygon": [
					{
						"x": 1205,
						"y": 16
					},
					{
						"x": 1575,
						"y": 13
					},
					{
						"x": 1575,
						"y": 50
					},
					{
						"x": 1205,
						"y": 54
					}
				],
				"words": [
					{
						"text": "January",
						"boundingPolygon": [
							{
								"x": 1210,
								"y": 16
							},
							{
								"x": 1361,
								"y": 16
							},
							{
								"x": 1361,
								"y": 51
							},
							{
								"x": 1210,
								"y": 55
							}
						],
						"confidence": 0.993
					},
					{
						"text": "23rd",
						"boundingPolygon": [
							{
								"x": 1390,
								"y": 16
							},
							{
								"x": 1465,
								"y": 15
							},
							{
								"x": 1466,
								"y": 50
							},
							{
								"x": 1390,
								"y": 51
							}
						],
						"confidence": 0.978
					},
					{
						"text": "2020",
						"boundingPolygon": [
							{
								"x": 1489,
								"y": 15
							},
							{
								"x": 1572,
								"y": 14
							},
							{
								"x": 1573,
								"y": 50
							},
							{
								"x": 1490,
								"y": 50
							}
						],
						"confidence": 0.991
					}
				]
			},
			{
				"text": "For the attention of:",
				"boundingPolygon": [
					{
						"x": 31,
						"y": 107
					},
					{
						"x": 496,
						"y": 106
					},
					{
						"x": 496,
						"y": 139
					},
					{
						"x": 31,
						"y": 140
					}
				],
				"words": [
					{
						"text": "For",
						"boundingPolygon": [
							{
								"x": 31,
								"y": 108
							},
							{
								"x": 93,
								"y": 108
							},
							{
								"x": 93,
								"y": 140
							},
							{
								"x": 31,
								"y": 140
							}
						],
						"confidence": 0.998
					},
					{
						"text": "the",
						"boundingPolygon": [
							{
								"x": 121,
								"y": 108
							},
							{
								"x": 180,
								"y": 108
							},
							{
								"x": 180,
								"y": 139
							},
							{
								"x": 121,
								"y": 140
							}
						],
						"confidence": 0.999
					},
					{
						"text": "attention",
						"boundingPolygon": [
							{
								"x": 211,
								"y": 108
							},
							{
								"x": 405,
								"y": 107
							},
							{
								"x": 404,
								"y": 140
							},
							{
								"x": 210,
								"y": 139
							}
						],
						"confidence": 0.994
					},
					{
						"text": "of:",
						"boundingPolygon": [
							{
								"x": 433,
								"y": 106
							},
							{
								"x": 495,
								"y": 106
							},
							{
								"x": 494,
								"y": 140
							},
							{
								"x": 432,
								"y": 140
							}
						],
						"confidence": 0.854
					}
				]
			},
			{
				"text": "The manager",
				"boundingPolygon": [
					{
						"x": 30,
						"y": 152
					},
					{
						"x": 274,
						"y": 153
					},
					{
						"x": 274,
						"y": 187
					},
					{
						"x": 30,
						"y": 185
					}
				],
				"words": [
					{
						"text": "The",
						"boundingPolygon": [
							{
								"x": 32,
								"y": 153
							},
							{
								"x": 89,
								"y": 154
							},
							{
								"x": 90,
								"y": 187
							},
							{
								"x": 33,
								"y": 186
							}
						],
						"confidence": 0.999
					},
					{
						"text": "manager",
						"boundingPolygon": [
							{
								"x": 117,
								"y": 154
							},
							{
								"x": 272,
								"y": 155
							},
							{
								"x": 272,
								"y": 186
							},
							{
								"x": 117,
								"y": 187
							}
						],
						"confidence": 0.996
					}
				]
			},
			{
				"text": "Northwind Traders",
				"boundingPolygon": [
					{
						"x": 26,
						"y": 198
					},
					{
						"x": 411,
						"y": 198
					},
					{
						"x": 411,
						"y": 229
					},
					{
						"x": 26,
						"y": 230
					}
				],
				"words": [
					{
						"text": "Northwind",
						"boundingPolygon": [
							{
								"x": 26,
								"y": 198
							},
							{
								"x": 225,
								"y": 198
							},
							{
								"x": 224,
								"y": 229
							},
							{
								"x": 26,
								"y": 231
							}
						],
						"confidence": 0.994
					},
					{
						"text": "Traders",
						"boundingPolygon": [
							{
								"x": 258,
								"y": 199
							},
							{
								"x": 409,
								"y": 199
							},
							{
								"x": 408,
								"y": 229
							},
							{
								"x": 257,
								"y": 229
							}
						],
						"confidence": 0.995
					}
				]
			},
			{
				"text": "123 Any Street",
				"boundingPolygon": [
					{
						"x": 30,
						"y": 241
					},
					{
						"x": 342,
						"y": 241
					},
					{
						"x": 342,
						"y": 276
					},
					{
						"x": 30,
						"y": 276
					}
				],
				"words": [
					{
						"text": "123",
						"boundingPolygon": [
							{
								"x": 32,
								"y": 242
							},
							{
								"x": 92,
								"y": 243
							},
							{
								"x": 93,
								"y": 276
							},
							{
								"x": 33,
								"y": 277
							}
						],
						"confidence": 0.993
					},
					{
						"text": "Any",
						"boundingPolygon": [
							{
								"x": 118,
								"y": 244
							},
							{
								"x": 180,
								"y": 245
							},
							{
								"x": 180,
								"y": 276
							},
							{
								"x": 118,
								"y": 276
							}
						],
						"confidence": 0.998
					},
					{
						"text": "Street",
						"boundingPolygon": [
							{
								"x": 212,
								"y": 245
							},
							{
								"x": 338,
								"y": 244
							},
							{
								"x": 338,
								"y": 275
							},
							{
								"x": 212,
								"y": 276
							}
						],
						"confidence": 0.997
					}
				]
			},
			{
				"text": "Bellevue, WA",
				"boundingPolygon": [
					{
						"x": 29,
						"y": 288
					},
					{
						"x": 299,
						"y": 288
					},
					{
						"x": 299,
						"y": 319
					},
					{
						"x": 29,
						"y": 319
					}
				],
				"words": [
					{
						"text": "Bellevue,",
						"boundingPolygon": [
							{
								"x": 29,
								"y": 288
							},
							{
								"x": 228,
								"y": 289
							},
							{
								"x": 228,
								"y": 320
							},
							{
								"x": 29,
								"y": 320
							}
						],
						"confidence": 0.992
					},
					{
						"text": "WA",
						"boundingPolygon": [
							{
								"x": 253,
								"y": 289
							},
							{
								"x": 293,
								"y": 289
							},
							{
								"x": 293,
								"y": 319
							},
							{
								"x": 253,
								"y": 320
							}
						],
						"confidence": 0.998
					}
				]
			},
			{
				"text": "Dear Sir or Madam,",
				"boundingPolygon": [
					{
						"x": 28,
						"y": 376
					},
					{
						"x": 427,
						"y": 378
					},
					{
						"x": 426,
						"y": 411
					},
					{
						"x": 28,
						"y": 409
					}
				],
				"words": [
					{
						"text": "Dear",
						"boundingPolygon": [
							{
								"x": 29,
								"y": 377
							},
							{
								"x": 114,
								"y": 377
							},
							{
								"x": 114,
								"y": 410
							},
							{
								"x": 28,
								"y": 410
							}
						],
						"confidence": 0.993
					},
					{
						"text": "Sir",
						"boundingPolygon": [
							{
								"x": 143,
								"y": 377
							},
							{
								"x": 205,
								"y": 378
							},
							{
								"x": 204,
								"y": 410
							},
							{
								"x": 142,
								"y": 410
							}
						],
						"confidence": 0.98
					},
					{
						"text": "or",
						"boundingPolygon": [
							{
								"x": 231,
								"y": 378
							},
							{
								"x": 273,
								"y": 378
							},
							{
								"x": 272,
								"y": 411
							},
							{
								"x": 230,
								"y": 410
							}
						],
						"confidence": 0.992
					},
					{
						"text": "Madam,",
						"boundingPolygon": [
							{
								"x": 295,
								"y": 378
							},
							{
								"x": 426,
								"y": 380
							},
							{
								"x": 425,
								"y": 412
							},
							{
								"x": 294,
								"y": 411
							}
						],
						"confidence": 0.995
					}
				]
			},
			{
				"text": "I am writing to thank you for the fantastic service I received at",
				"boundingPolygon": [
					{
						"x": 30,
						"y": 466
					},
					{
						"x": 1489,
						"y": 465
					},
					{
						"x": 1489,
						"y": 500
					},
					{
						"x": 30,
						"y": 502
					}
				],
				"words": [
					{
						"text": "I",
						"boundingPolygon": [
							{
								"x": 32,
								"y": 469
							},
							{
								"x": 50,
								"y": 469
							},
							{
								"x": 49,
								"y": 503
							},
							{
								"x": 31,
								"y": 503
							}
						],
						"confidence": 0.993
					},
					{
						"text": "am",
						"boundingPolygon": [
							{
								"x": 76,
								"y": 469
							},
							{
								"x": 112,
								"y": 468
							},
							{
								"x": 111,
								"y": 503
							},
							{
								"x": 75,
								"y": 503
							}
						],
						"confidence": 0.999
					},
					{
						"text": "writing",
						"boundingPolygon": [
							{
								"x": 138,
								"y": 468
							},
							{
								"x": 293,
								"y": 467
							},
							{
								"x": 292,
								"y": 503
							},
							{
								"x": 137,
								"y": 503
							}
						],
						"confidence": 0.994
					},
					{
						"text": "to",
						"boundingPolygon": [
							{
								"x": 321,
								"y": 467
							},
							{
								"x": 360,
								"y": 467
							},
							{
								"x": 359,
								"y": 503
							},
							{
								"x": 320,
								"y": 503
							}
						],
						"confidence": 0.999
					},
					{
						"text": "thank",
						"boundingPolygon": [
							{
								"x": 388,
								"y": 467
							},
							{
								"x": 497,
								"y": 467
							},
							{
								"x": 496,
								"y": 502
							},
							{
								"x": 388,
								"y": 503
							}
						],
						"confidence": 0.998
					},
					{
						"text": "you",
						"boundingPolygon": [
							{
								"x": 523,
								"y": 466
							},
							{
								"x": 584,
								"y": 466
							},
							{
								"x": 584,
								"y": 502
							},
							{
								"x": 522,
								"y": 502
							}
						],
						"confidence": 0.999
					},
					{
						"text": "for",
						"boundingPolygon": [
							{
								"x": 615,
								"y": 466
							},
							{
								"x": 677,
								"y": 466
							},
							{
								"x": 677,
								"y": 502
							},
							{
								"x": 615,
								"y": 502
							}
						],
						"confidence": 0.994
					},
					{
						"text": "the",
						"boundingPolygon": [
							{
								"x": 703,
								"y": 466
							},
							{
								"x": 765,
								"y": 466
							},
							{
								"x": 765,
								"y": 502
							},
							{
								"x": 703,
								"y": 502
							}
						],
						"confidence": 0.994
					},
					{
						"text": "fantastic",
						"boundingPolygon": [
							{
								"x": 793,
								"y": 466
							},
							{
								"x": 989,
								"y": 466
							},
							{
								"x": 989,
								"y": 502
							},
							{
								"x": 793,
								"y": 502
							}
						],
						"confidence": 0.994
					},
					{
						"text": "service",
						"boundingPolygon": [
							{
								"x": 1018,
								"y": 466
							},
							{
								"x": 1168,
								"y": 466
							},
							{
								"x": 1168,
								"y": 502
							},
							{
								"x": 1018,
								"y": 502
							}
						],
						"confidence": 0.995
					},
					{
						"text": "I",
						"boundingPolygon": [
							{
								"x": 1198,
								"y": 466
							},
							{
								"x": 1216,
								"y": 466
							},
							{
								"x": 1216,
								"y": 501
							},
							{
								"x": 1198,
								"y": 501
							}
						],
						"confidence": 0.995
					},
					{
						"text": "received",
						"boundingPolygon": [
							{
								"x": 1242,
								"y": 466
							},
							{
								"x": 1415,
								"y": 466
							},
							{
								"x": 1415,
								"y": 501
							},
							{
								"x": 1242,
								"y": 501
							}
						],
						"confidence": 0.991
					},
					{
						"text": "at",
						"boundingPolygon": [
							{
								"x": 1444,
								"y": 467
							},
							{
								"x": 1485,
								"y": 467
							},
							{
								"x": 1485,
								"y": 501
							},
							{
								"x": 1444,
								"y": 501
							}
						],
						"confidence": 0.997
					}
				]
			},
			{
				"text": "your store on January 20th. The store assistant who helped me was",
				"boundingPolygon": [
					{
						"x": 28,
						"y": 511
					},
					{
						"x": 1472,
						"y": 511
					},
					{
						"x": 1472,
						"y": 547
					},
					{
						"x": 28,
						"y": 548
					}
				],
				"words": [
					{
						"text": "your",
						"boundingPolygon": [
							{
								"x": 29,
								"y": 516
							},
							{
								"x": 115,
								"y": 515
							},
							{
								"x": 114,
								"y": 547
							},
							{
								"x": 28,
								"y": 547
							}
						],
						"confidence": 0.993
					},
					{
						"text": "store",
						"boundingPolygon": [
							{
								"x": 143,
								"y": 515
							},
							{
								"x": 248,
								"y": 514
							},
							{
								"x": 247,
								"y": 547
							},
							{
								"x": 142,
								"y": 547
							}
						],
						"confidence": 0.993
					},
					{
						"text": "on",
						"boundingPolygon": [
							{
								"x": 276,
								"y": 513
							},
							{
								"x": 316,
								"y": 513
							},
							{
								"x": 315,
								"y": 547
							},
							{
								"x": 275,
								"y": 547
							}
						],
						"confidence": 0.998
					},
					{
						"text": "January",
						"boundingPolygon": [
							{
								"x": 346,
								"y": 513
							},
							{
								"x": 496,
								"y": 512
							},
							{
								"x": 495,
								"y": 547
							},
							{
								"x": 345,
								"y": 547
							}
						],
						"confidence": 0.993
					},
					{
						"text": "20th.",
						"boundingPolygon": [
							{
								"x": 524,
								"y": 512
							},
							{
								"x": 620,
								"y": 512
							},
							{
								"x": 619,
								"y": 547
							},
							{
								"x": 523,
								"y": 547
							}
						],
						"confidence": 0.991
					},
					{
						"text": "The",
						"boundingPolygon": [
							{
								"x": 645,
								"y": 512
							},
							{
								"x": 704,
								"y": 511
							},
							{
								"x": 703,
								"y": 547
							},
							{
								"x": 644,
								"y": 547
							}
						],
						"confidence": 0.999
					},
					{
						"text": "store",
						"boundingPolygon": [
							{
								"x": 734,
								"y": 511
							},
							{
								"x": 839,
								"y": 511
							},
							{
								"x": 838,
								"y": 547
							},
							{
								"x": 733,
								"y": 547
							}
						],
						"confidence": 0.997
					},
					{
						"text": "assistant",
						"boundingPolygon": [
							{
								"x": 867,
								"y": 511
							},
							{
								"x": 1065,
								"y": 511
							},
							{
								"x": 1064,
								"y": 548
							},
							{
								"x": 866,
								"y": 547
							}
						],
						"confidence": 0.99
					},
					{
						"text": "who",
						"boundingPolygon": [
							{
								"x": 1088,
								"y": 512
							},
							{
								"x": 1154,
								"y": 512
							},
							{
								"x": 1153,
								"y": 548
							},
							{
								"x": 1087,
								"y": 548
							}
						],
						"confidence": 0.998
					},
					{
						"text": "helped",
						"boundingPolygon": [
							{
								"x": 1179,
								"y": 512
							},
							{
								"x": 1309,
								"y": 512
							},
							{
								"x": 1308,
								"y": 548
							},
							{
								"x": 1178,
								"y": 548
							}
						],
						"confidence": 0.995
					},
					{
						"text": "me",
						"boundingPolygon": [
							{
								"x": 1334,
								"y": 513
							},
							{
								"x": 1377,
								"y": 513
							},
							{
								"x": 1376,
								"y": 548
							},
							{
								"x": 1334,
								"y": 548
							}
						],
						"confidence": 0.998
					},
					{
						"text": "was",
						"boundingPolygon": [
							{
								"x": 1403,
								"y": 513
							},
							{
								"x": 1471,
								"y": 513
							},
							{
								"x": 1470,
								"y": 548
							},
							{
								"x": 1402,
								"y": 548
							}
						],
						"confidence": 0.999
					}
				]
			},
			{
				"text": "extremely pleasant and attentive; and took the time to find all of",
				"boundingPolygon": [
					{
						"x": 29,
						"y": 556
					},
					{
						"x": 1508,
						"y": 555
					},
					{
						"x": 1509,
						"y": 590
					},
					{
						"x": 29,
						"y": 592
					}
				],
				"words": [
					{
						"text": "extremely",
						"boundingPolygon": [
							{
								"x": 30,
								"y": 559
							},
							{
								"x": 226,
								"y": 558
							},
							{
								"x": 225,
								"y": 592
							},
							{
								"x": 29,
								"y": 592
							}
						],
						"confidence": 0.988
					},
					{
						"text": "pleasant",
						"boundingPolygon": [
							{
								"x": 252,
								"y": 558
							},
							{
								"x": 430,
								"y": 557
							},
							{
								"x": 429,
								"y": 592
							},
							{
								"x": 251,
								"y": 592
							}
						],
						"confidence": 0.994
					},
					{
						"text": "and",
						"boundingPolygon": [
							{
								"x": 456,
								"y": 557
							},
							{
								"x": 518,
								"y": 556
							},
							{
								"x": 517,
								"y": 592
							},
							{
								"x": 455,
								"y": 592
							}
						],
						"confidence": 0.999
					},
					{
						"text": "attentive;",
						"boundingPolygon": [
							{
								"x": 546,
								"y": 556
							},
							{
								"x": 767,
								"y": 556
							},
							{
								"x": 767,
								"y": 592
							},
							{
								"x": 545,
								"y": 592
							}
						],
						"confidence": 0.992
					},
					{
						"text": "and",
						"boundingPolygon": [
							{
								"x": 791,
								"y": 556
							},
							{
								"x": 853,
								"y": 556
							},
							{
								"x": 852,
								"y": 592
							},
							{
								"x": 790,
								"y": 592
							}
						],
						"confidence": 0.995
					},
					{
						"text": "took",
						"boundingPolygon": [
							{
								"x": 881,
								"y": 556
							},
							{
								"x": 966,
								"y": 556
							},
							{
								"x": 966,
								"y": 592
							},
							{
								"x": 881,
								"y": 592
							}
						],
						"confidence": 0.993
					},
					{
						"text": "the",
						"boundingPolygon": [
							{
								"x": 994,
								"y": 556
							},
							{
								"x": 1054,
								"y": 556
							},
							{
								"x": 1053,
								"y": 592
							},
							{
								"x": 994,
								"y": 592
							}
						],
						"confidence": 0.999
					},
					{
						"text": "time",
						"boundingPolygon": [
							{
								"x": 1082,
								"y": 556
							},
							{
								"x": 1167,
								"y": 556
							},
							{
								"x": 1167,
								"y": 592
							},
							{
								"x": 1082,
								"y": 592
							}
						],
						"confidence": 0.993
					},
					{
						"text": "to",
						"boundingPolygon": [
							{
								"x": 1195,
								"y": 556
							},
							{
								"x": 1234,
								"y": 556
							},
							{
								"x": 1234,
								"y": 591
							},
							{
								"x": 1195,
								"y": 592
							}
						],
						"confidence": 0.999
					},
					{
						"text": "find",
						"boundingPolygon": [
							{
								"x": 1265,
								"y": 556
							},
							{
								"x": 1345,
								"y": 556
							},
							{
								"x": 1345,
								"y": 591
							},
							{
								"x": 1265,
								"y": 591
							}
						],
						"confidence": 0.993
					},
					{
						"text": "all",
						"boundingPolygon": [
							{
								"x": 1373,
								"y": 556
							},
							{
								"x": 1437,
								"y": 556
							},
							{
								"x": 1437,
								"y": 591
							},
							{
								"x": 1373,
								"y": 591
							}
						],
						"confidence": 0.993
					},
					{
						"text": "of",
						"boundingPolygon": [
							{
								"x": 1463,
								"y": 556
							},
							{
								"x": 1507,
								"y": 556
							},
							{
								"x": 1507,
								"y": 591
							},
							{
								"x": 1463,
								"y": 591
							}
						],
						"confidence": 0.999
					}
				]
			},
			{
				"text": "the fresh produce I needed.",
				"boundingPolygon": [
					{
						"x": 30,
						"y": 601
					},
					{
						"x": 631,
						"y": 600
					},
					{
						"x": 631,
						"y": 635
					},
					{
						"x": 30,
						"y": 637
					}
				],
				"words": [
					{
						"text": "the",
						"boundingPolygon": [
							{
								"x": 32,
								"y": 602
							},
							{
								"x": 92,
								"y": 603
							},
							{
								"x": 91,
								"y": 636
							},
							{
								"x": 31,
								"y": 636
							}
						],
						"confidence": 0.999
					},
					{
						"text": "fresh",
						"boundingPolygon": [
							{
								"x": 121,
								"y": 603
							},
							{
								"x": 225,
								"y": 603
							},
							{
								"x": 225,
								"y": 637
							},
							{
								"x": 120,
								"y": 637
							}
						],
						"confidence": 0.998
					},
					{
						"text": "produce",
						"boundingPolygon": [
							{
								"x": 251,
								"y": 603
							},
							{
								"x": 404,
								"y": 603
							},
							{
								"x": 404,
								"y": 637
							},
							{
								"x": 250,
								"y": 637
							}
						],
						"confidence": 0.993
					},
					{
						"text": "I",
						"boundingPolygon": [
							{
								"x": 436,
								"y": 602
							},
							{
								"x": 453,
								"y": 602
							},
							{
								"x": 453,
								"y": 637
							},
							{
								"x": 435,
								"y": 637
							}
						],
						"confidence": 0.998
					},
					{
						"text": "needed.",
						"boundingPolygon": [
							{
								"x": 476,
								"y": 602
							},
							{
								"x": 630,
								"y": 600
							},
							{
								"x": 630,
								"y": 634
							},
							{
								"x": 476,
								"y": 636
							}
						],
						"confidence": 0.993
					}
				]
			},
			{
				"text": "I've always found the quality of the produce in your store to be",
				"boundingPolygon": [
					{
						"x": 30,
						"y": 690
					},
					{
						"x": 1466,
						"y": 690
					},
					{
						"x": 1466,
						"y": 728
					},
					{
						"x": 30,
						"y": 728
					}
				],
				"words": [
					{
						"text": "I've",
						"boundingPolygon": [
							{
								"x": 32,
								"y": 692
							},
							{
								"x": 118,
								"y": 691
							},
							{
								"x": 118,
								"y": 727
							},
							{
								"x": 32,
								"y": 726
							}
						],
						"confidence": 0.993
					},
					{
						"text": "always",
						"boundingPolygon": [
							{
								"x": 141,
								"y": 691
							},
							{
								"x": 275,
								"y": 691
							},
							{
								"x": 275,
								"y": 728
							},
							{
								"x": 141,
								"y": 727
							}
						],
						"confidence": 0.998
					},
					{
						"text": "found",
						"boundingPolygon": [
							{
								"x": 298,
								"y": 691
							},
							{
								"x": 408,
								"y": 691
							},
							{
								"x": 408,
								"y": 729
							},
							{
								"x": 297,
								"y": 728
							}
						],
						"confidence": 0.999
					},
					{
						"text": "the",
						"boundingPolygon": [
							{
								"x": 431,
								"y": 691
							},
							{
								"x": 498,
								"y": 691
							},
							{
								"x": 498,
								"y": 729
							},
							{
								"x": 430,
								"y": 729
							}
						],
						"confidence": 0.999
					},
					{
						"text": "quality",
						"boundingPolygon": [
							{
								"x": 521,
								"y": 691
							},
							{
								"x": 679,
								"y": 691
							},
							{
								"x": 678,
								"y": 729
							},
							{
								"x": 520,
								"y": 729
							}
						],
						"confidence": 0.996
					},
					{
						"text": "of",
						"boundingPolygon": [
							{
								"x": 706,
								"y": 691
							},
							{
								"x": 745,
								"y": 691
							},
							{
								"x": 745,
								"y": 729
							},
							{
								"x": 706,
								"y": 729
							}
						],
						"confidence": 0.999
					},
					{
						"text": "the",
						"boundingPolygon": [
							{
								"x": 768,
								"y": 691
							},
							{
								"x": 835,
								"y": 691
							},
							{
								"x": 835,
								"y": 729
							},
							{
								"x": 767,
								"y": 729
							}
						],
						"confidence": 0.999
					},
					{
						"text": "produce",
						"boundingPolygon": [
							{
								"x": 863,
								"y": 691
							},
							{
								"x": 1016,
								"y": 691
							},
							{
								"x": 1015,
								"y": 729
							},
							{
								"x": 862,
								"y": 729
							}
						],
						"confidence": 0.997
					},
					{
						"text": "in",
						"boundingPolygon": [
							{
								"x": 1038,
								"y": 691
							},
							{
								"x": 1082,
								"y": 692
							},
							{
								"x": 1082,
								"y": 728
							},
							{
								"x": 1038,
								"y": 729
							}
						],
						"confidence": 0.999
					},
					{
						"text": "your",
						"boundingPolygon": [
							{
								"x": 1105,
								"y": 692
							},
							{
								"x": 1196,
								"y": 692
							},
							{
								"x": 1196,
								"y": 727
							},
							{
								"x": 1104,
								"y": 728
							}
						],
						"confidence": 0.981
					},
					{
						"text": "store",
						"boundingPolygon": [
							{
								"x": 1219,
								"y": 692
							},
							{
								"x": 1329,
								"y": 693
							},
							{
								"x": 1329,
								"y": 726
							},
							{
								"x": 1218,
								"y": 727
							}
						],
						"confidence": 0.998
					},
					{
						"text": "to",
						"boundingPolygon": [
							{
								"x": 1352,
								"y": 693
							},
							{
								"x": 1396,
								"y": 693
							},
							{
								"x": 1395,
								"y": 725
							},
							{
								"x": 1351,
								"y": 726
							}
						],
						"confidence": 0.999
					},
					{
						"text": "be",
						"boundingPolygon": [
							{
								"x": 1423,
								"y": 693
							},
							{
								"x": 1462,
								"y": 693
							},
							{
								"x": 1461,
								"y": 725
							},
							{
								"x": 1422,
								"y": 725
							}
						],
						"confidence": 0.997
					}
				]
			},
			{
				"text": "high, and the prices to be competitive; and the helpfulness of your",
				"boundingPolygon": [
					{
						"x": 26,
						"y": 736
					},
					{
						"x": 1532,
						"y": 735
					},
					{
						"x": 1532,
						"y": 772
					},
					{
						"x": 26,
						"y": 772
					}
				],
				"words": [
					{
						"text": "high,",
						"boundingPolygon": [
							{
								"x": 26,
								"y": 738
							},
							{
								"x": 139,
								"y": 737
							},
							{
								"x": 138,
								"y": 773
							},
							{
								"x": 26,
								"y": 772
							}
						],
						"confidence": 0.997
					},
					{
						"text": "and",
						"boundingPolygon": [
							{
								"x": 165,
								"y": 737
							},
							{
								"x": 225,
								"y": 737
							},
							{
								"x": 225,
								"y": 773
							},
							{
								"x": 165,
								"y": 773
							}
						],
						"confidence": 0.995
					},
					{
						"text": "the",
						"boundingPolygon": [
							{
								"x": 254,
								"y": 737
							},
							{
								"x": 315,
								"y": 737
							},
							{
								"x": 315,
								"y": 773
							},
							{
								"x": 254,
								"y": 773
							}
						],
						"confidence": 0.999
					},
					{
						"text": "prices",
						"boundingPolygon": [
							{
								"x": 341,
								"y": 737
							},
							{
								"x": 477,
								"y": 736
							},
							{
								"x": 477,
								"y": 773
							},
							{
								"x": 341,
								"y": 773
							}
						],
						"confidence": 0.995
					},
					{
						"text": "to",
						"boundingPolygon": [
							{
								"x": 501,
								"y": 736
							},
							{
								"x": 540,
								"y": 736
							},
							{
								"x": 540,
								"y": 773
							},
							{
								"x": 501,
								"y": 773
							}
						],
						"confidence": 0.999
					},
					{
						"text": "be",
						"boundingPolygon": [
							{
								"x": 564,
								"y": 736
							},
							{
								"x": 608,
								"y": 736
							},
							{
								"x": 608,
								"y": 773
							},
							{
								"x": 564,
								"y": 773
							}
						],
						"confidence": 0.998
					},
					{
						"text": "competitive;",
						"boundingPolygon": [
							{
								"x": 635,
								"y": 736
							},
							{
								"x": 902,
								"y": 736
							},
							{
								"x": 902,
								"y": 773
							},
							{
								"x": 634,
								"y": 773
							}
						],
						"confidence": 0.993
					},
					{
						"text": "and",
						"boundingPolygon": [
							{
								"x": 929,
								"y": 736
							},
							{
								"x": 989,
								"y": 736
							},
							{
								"x": 988,
								"y": 773
							},
							{
								"x": 928,
								"y": 773
							}
						],
						"confidence": 0.999
					},
					{
						"text": "the",
						"boundingPolygon": [
							{
								"x": 1018,
								"y": 736
							},
							{
								"x": 1078,
								"y": 736
							},
							{
								"x": 1078,
								"y": 773
							},
							{
								"x": 1017,
								"y": 773
							}
						],
						"confidence": 0.999
					},
					{
						"text": "helpfulness",
						"boundingPolygon": [
							{
								"x": 1105,
								"y": 736
							},
							{
								"x": 1351,
								"y": 737
							},
							{
								"x": 1350,
								"y": 772
							},
							{
								"x": 1104,
								"y": 773
							}
						],
						"confidence": 0.993
					},
					{
						"text": "of",
						"boundingPolygon": [
							{
								"x": 1375,
								"y": 737
							},
							{
								"x": 1419,
								"y": 737
							},
							{
								"x": 1418,
								"y": 772
							},
							{
								"x": 1374,
								"y": 772
							}
						],
						"confidence": 0.999
					},
					{
						"text": "your",
						"boundingPolygon": [
							{
								"x": 1443,
								"y": 738
							},
							{
								"x": 1529,
								"y": 738
							},
							{
								"x": 1528,
								"y": 772
							},
							{
								"x": 1442,
								"y": 772
							}
						],
						"confidence": 0.993
					}
				]
			},
			{
				"text": "employees is another reason I will continue to remain a loyal",
				"boundingPolygon": [
					{
						"x": 29,
						"y": 781
					},
					{
						"x": 1396,
						"y": 780
					},
					{
						"x": 1396,
						"y": 817
					},
					{
						"x": 29,
						"y": 818
					}
				],
				"words": [
					{
						"text": "employees",
						"boundingPolygon": [
							{
								"x": 29,
								"y": 784
							},
							{
								"x": 228,
								"y": 782
							},
							{
								"x": 228,
								"y": 818
							},
							{
								"x": 29,
								"y": 819
							}
						],
						"confidence": 0.993
					},
					{
						"text": "is",
						"boundingPolygon": [
							{
								"x": 255,
								"y": 782
							},
							{
								"x": 296,
								"y": 782
							},
							{
								"x": 296,
								"y": 818
							},
							{
								"x": 255,
								"y": 818
							}
						],
						"confidence": 0.999
					},
					{
						"text": "another",
						"boundingPolygon": [
							{
								"x": 321,
								"y": 782
							},
							{
								"x": 475,
								"y": 781
							},
							{
								"x": 475,
								"y": 817
							},
							{
								"x": 321,
								"y": 818
							}
						],
						"confidence": 0.995
					},
					{
						"text": "reason",
						"boundingPolygon": [
							{
								"x": 501,
								"y": 781
							},
							{
								"x": 630,
								"y": 781
							},
							{
								"x": 630,
								"y": 817
							},
							{
								"x": 501,
								"y": 817
							}
						],
						"confidence": 0.993
					},
					{
						"text": "I",
						"boundingPolygon": [
							{
								"x": 658,
								"y": 781
							},
							{
								"x": 677,
								"y": 781
							},
							{
								"x": 677,
								"y": 817
							},
							{
								"x": 658,
								"y": 817
							}
						],
						"confidence": 0.997
					},
					{
						"text": "will",
						"boundingPolygon": [
							{
								"x": 698,
								"y": 781
							},
							{
								"x": 789,
								"y": 781
							},
							{
								"x": 789,
								"y": 817
							},
							{
								"x": 698,
								"y": 817
							}
						],
						"confidence": 0.992
					},
					{
						"text": "continue",
						"boundingPolygon": [
							{
								"x": 813,
								"y": 781
							},
							{
								"x": 987,
								"y": 781
							},
							{
								"x": 987,
								"y": 817
							},
							{
								"x": 813,
								"y": 817
							}
						],
						"confidence": 0.994
					},
					{
						"text": "to",
						"boundingPolygon": [
							{
								"x": 1015,
								"y": 781
							},
							{
								"x": 1055,
								"y": 781
							},
							{
								"x": 1055,
								"y": 817
							},
							{
								"x": 1015,
								"y": 817
							}
						],
						"confidence": 0.998
					},
					{
						"text": "remain",
						"boundingPolygon": [
							{
								"x": 1083,
								"y": 781
							},
							{
								"x": 1212,
								"y": 781
							},
							{
								"x": 1212,
								"y": 817
							},
							{
								"x": 1083,
								"y": 817
							}
						],
						"confidence": 0.993
					},
					{
						"text": "a",
						"boundingPolygon": [
							{
								"x": 1241,
								"y": 782
							},
							{
								"x": 1259,
								"y": 782
							},
							{
								"x": 1259,
								"y": 817
							},
							{
								"x": 1241,
								"y": 817
							}
						],
						"confidence": 0.997
					},
					{
						"text": "loyal",
						"boundingPolygon": [
							{
								"x": 1285,
								"y": 782
							},
							{
								"x": 1393,
								"y": 782
							},
							{
								"x": 1393,
								"y": 818
							},
							{
								"x": 1285,
								"y": 818
							}
						],
						"confidence": 0.993
					}
				]
			},
			{
				"text": "Northwind Traders customer.",
				"boundingPolygon": [
					{
						"x": 24,
						"y": 827
					},
					{
						"x": 631,
						"y": 827
					},
					{
						"x": 631,
						"y": 861
					},
					{
						"x": 24,
						"y": 860
					}
				],
				"words": [
					{
						"text": "Northwind",
						"boundingPolygon": [
							{
								"x": 27,
								"y": 828
							},
							{
								"x": 226,
								"y": 827
							},
							{
								"x": 226,
								"y": 861
							},
							{
								"x": 27,
								"y": 861
							}
						],
						"confidence": 0.993
					},
					{
						"text": "Traders",
						"boundingPolygon": [
							{
								"x": 255,
								"y": 827
							},
							{
								"x": 408,
								"y": 827
							},
							{
								"x": 408,
								"y": 861
							},
							{
								"x": 255,
								"y": 861
							}
						],
						"confidence": 0.991
					},
					{
						"text": "customer.",
						"boundingPolygon": [
							{
								"x": 433,
								"y": 828
							},
							{
								"x": 631,
								"y": 828
							},
							{
								"x": 631,
								"y": 861
							},
							{
								"x": 433,
								"y": 861
							}
						],
						"confidence": 0.994
					}
				]
			},
			{
				"text": "Sincerely,",
				"boundingPolygon": [
					{
						"x": 29,
						"y": 917
					},
					{
						"x": 248,
						"y": 918
					},
					{
						"x": 248,
						"y": 954
					},
					{
						"x": 29,
						"y": 951
					}
				],
				"words": [
					{
						"text": "Sincerely,",
						"boundingPolygon": [
							{
								"x": 32,
								"y": 917
							},
							{
								"x": 248,
								"y": 920
							},
							{
								"x": 247,
								"y": 955
							},
							{
								"x": 32,
								"y": 952
							}
						],
						"confidence": 0.993
					}
				]
			},
			{
				"text": "A Customer",
				"boundingPolygon": [
					{
						"x": 27,
						"y": 1010
					},
					{
						"x": 277,
						"y": 1011
					},
					{
						"x": 277,
						"y": 1048
					},
					{
						"x": 27,
						"y": 1047
					}
				],
				"words": [
					{
						"text": "A",
						"boundingPolygon": [
							{
								"x": 38,
								"y": 1010
							},
							{
								"x": 59,
								"y": 1011
							},
							{
								"x": 59,
								"y": 1048
							},
							{
								"x": 38,
								"y": 1048
							}
						],
						"confidence": 0.994
					},
					{
						"text": "Customer",
						"boundingPolygon": [
							{
								"x": 82,
								"y": 1011
							},
							{
								"x": 277,
								"y": 1013
							},
							{
								"x": 277,
								"y": 1048
							},
							{
								"x": 82,
								"y": 1048
							}
						],
						"confidence": 0.99
					}
				]
			},
			{
				"text": "A. Customer",
				"boundingPolygon": [
					{
						"x": 20,
						"y": 1066
					},
					{
						"x": 278,
						"y": 1068
					},
					{
						"x": 278,
						"y": 1100
					},
					{
						"x": 20,
						"y": 1099
					}
				],
				"words": [
					{
						"text": "A.",
						"boundingPolygon": [
							{
								"x": 28,
								"y": 1067
							},
							{
								"x": 72,
								"y": 1068
							},
							{
								"x": 72,
								"y": 1100
							},
							{
								"x": 28,
								"y": 1100
							}
						],
						"confidence": 0.991
					},
					{
						"text": "Customer",
						"boundingPolygon": [
							{
								"x": 97,
								"y": 1068
							},
							{
								"x": 274,
								"y": 1069
							},
							{
								"x": 273,
								"y": 1101
							},
							{
								"x": 97,
								"y": 1100
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

### OCR - Extract text from images (note.jpg)

```json
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

### OCR - Extract text from images (receipt.jpg)

```json
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
