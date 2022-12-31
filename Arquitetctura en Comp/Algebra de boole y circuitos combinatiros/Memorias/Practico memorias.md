---

excalidraw-plugin: parsed
tags: [excalidraw]

---
==⚠  Switch to EXCALIDRAW VIEW in the MORE OPTIONS menu of this document. ⚠==


# Text Elements
El chip select indica si es posible que el chip va a funcionar normalmente o por el contrario 
todos sus ouputs seran 0. Es utilizado para simplificar los circuitos de "expansion" de chips.

El ouput enable, indica si la salida del chip sera valida, en caso de no serlo (cuando se envia 0 al 
ouput enable, las salidas del chip estaran en el tercer estado, por lo que seran concideradas INVALIDAS)



 ^fTaukbHv

Se tomara el input del chip como el valor en el cual se evaluara la funcion, el ouput conformara
la imagen para ese valor. la cantdiad de palabras del chip determinara el numero de elementos 
en el dominio de la funcion, el tamanio de la palabra determinara la cantidad de elementos del
codominio de la funcion.


 ^Hz2zFpDM

La sigla ROM significa read only memory, por lo que  son memorias donde no es 
posible determinar el ouput de una palabra en particular ^NKL40Q2W

TO DO ^csrkOk23

8kx8 ^P0b65Gq5

CS
OE ^ldHZNxFH

8kx8 ^mx5M47NK

CS
OE ^cXiMzxEg

8kx8 ^6gqUqiUs

CS
OE ^kWuRIPX0

8kx8 ^NSqHBgcX

CS
OE ^zHoLJbXQ

Decoder ^ZRCQD5Ms

8kx8 ^31VcK4ux

CS
OE ^uyaLCXEl

8kx8 ^LgpzxiuG

CS
OE ^6Ma4qqd4

8kx8 ^AxsFrbUK

CS
OE ^OW7RxgGE

8kx8 ^jc5jidpo

CS
OE ^yVYvVy5g

Deben haber 2k palabras posibles (2^11) con salida de palabras de 8 bits. ^XTD3ocNM


char rightShift(char c, int d){
    return c >> d;
} ^anbNbWym

Como entrada se debe distinguir entre todos los
caracteres de ASCII, en este caso 256, lo que 
implica que seran necesarios 8 bits de entrada.

A  su vez es necesario poder realizar una salida distinta para 
cada combiancion de pixeles que represena una letra,
esto es 64 bits de salida (8 por cada columna)

b) la rom se construiria conectando "en paralelo"
8 roms de 1k8 de las cuales se ignoraran 2 bits de su entrada.

Si se interpreta que lo que se quiere es tener como input el codigo ACII del caracter Y su columna,
caso en el cual la salida serían los 8 bits de la representacion de la columna, se requeririan 11bits de inputs
(2k inputs) y 8 bits de salida por lo que habria que construir un chip de tipo 2kx8 a partir de dos 
de tipo 1kx8 ^VqHqpN3P

32kx16 ^vrGokl0i

"primeros" 8 bits ^hKcmbsHe

"segundos" 8 bits ^5i2DUwFQ


# Embedded files
ec5ef32c8fc6234facb69ba2132d8354d81cd3b9: [[Pasted Image 20220905021020_378.png]]
68c6618ade1f67c15cd9345bc320c3f4c6cbdcb1: [[Pasted Image 20220905032427_401.png]]
0cdf83581507587401d7e5b0c7be394391161316: [[Pasted Image 20220905032710_392.png]]
861bce15eb6cf914e3d4b8432b55cf9daa451ad8: [[Pasted Image 20220905033452_175.png]]
59ac83ff8f0b442b44a01ddfc835f9f8263b1ba0: [[Pasted Image 20220905170129_934.png]]
cff9d323d9d35f9a6c5ea129c036648eebdfb4c8: [[Pasted Image 20220905210931_219.png]]
87422d731f16c7219d4fe2378d68bb0468b3158b: [[Pasted Image 20220905212145_716.png]]
bf04731834e2a478e8c1c5002d0d720c51a89e10: [[Pasted Image 20220906205900_583.png]]
76057c86bc3cd666f1e3f640ecd1842279750eb2: [[Pasted Image 20220906212856_314.png]]

%%
# Drawing
```json
{
	"type": "excalidraw",
	"version": 2,
	"source": "https://excalidraw.com",
	"elements": [
		{
			"type": "image",
			"version": 461,
			"versionNonce": 12688516,
			"isDeleted": false,
			"id": "hnrM2Z_awXZLRsRz_OqnO",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -514.3478932324902,
			"y": -447.50426569744144,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"width": 561.3277497204102,
			"height": 63.13326641843941,
			"seed": 1562688514,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223432,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "ec5ef32c8fc6234facb69ba2132d8354d81cd3b9",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "text",
			"version": 905,
			"versionNonce": 454516156,
			"isDeleted": false,
			"id": "fTaukbHv",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -510.7138748497369,
			"y": -377.5310914124489,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 981,
			"height": 209,
			"seed": 909746846,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1662511223432,
			"link": null,
			"locked": false,
			"fontSize": 18.43959079224997,
			"fontFamily": 1,
			"text": "El chip select indica si es posible que el chip va a funcionar normalmente o por el contrario \ntodos sus ouputs seran 0. Es utilizado para simplificar los circuitos de \"expansion\" de chips.\n\nEl ouput enable, indica si la salida del chip sera valida, en caso de no serlo (cuando se envia 0 al \nouput enable, las salidas del chip estaran en el tercer estado, por lo que seran concideradas INVALIDAS)\n\n\n\n",
			"rawText": "El chip select indica si es posible que el chip va a funcionar normalmente o por el contrario \ntodos sus ouputs seran 0. Es utilizado para simplificar los circuitos de \"expansion\" de chips.\n\nEl ouput enable, indica si la salida del chip sera valida, en caso de no serlo (cuando se envia 0 al \nouput enable, las salidas del chip estaran en el tercer estado, por lo que seran concideradas INVALIDAS)\n\n\n\n",
			"baseline": 202,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "El chip select indica si es posible que el chip va a funcionar normalmente o por el contrario \ntodos sus ouputs seran 0. Es utilizado para simplificar los circuitos de \"expansion\" de chips.\n\nEl ouput enable, indica si la salida del chip sera valida, en caso de no serlo (cuando se envia 0 al \nouput enable, las salidas del chip estaran en el tercer estado, por lo que seran concideradas INVALIDAS)\n\n\n\n"
		},
		{
			"type": "image",
			"version": 363,
			"versionNonce": 1256418308,
			"isDeleted": false,
			"id": "LsVnwrH-KupRpkd1FoGei",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -514.8875771217452,
			"y": -241.4979518185076,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"width": 791.8444079286836,
			"height": 32.993516997028486,
			"seed": 239932098,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223432,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "68c6618ade1f67c15cd9345bc320c3f4c6cbdcb1",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "text",
			"version": 743,
			"versionNonce": 1482442300,
			"isDeleted": false,
			"id": "Hz2zFpDM",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -506.0788384308948,
			"y": -206.77842280946123,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 863,
			"height": 157,
			"seed": 1258473374,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1662511223432,
			"link": null,
			"locked": false,
			"fontSize": 17.99150873621739,
			"fontFamily": 1,
			"text": "Se tomara el input del chip como el valor en el cual se evaluara la funcion, el ouput conformara\nla imagen para ese valor. la cantdiad de palabras del chip determinara el numero de elementos \nen el dominio de la funcion, el tamanio de la palabra determinara la cantidad de elementos del\ncodominio de la funcion.\n\n\n",
			"rawText": "Se tomara el input del chip como el valor en el cual se evaluara la funcion, el ouput conformara\nla imagen para ese valor. la cantdiad de palabras del chip determinara el numero de elementos \nen el dominio de la funcion, el tamanio de la palabra determinara la cantidad de elementos del\ncodominio de la funcion.\n\n\n",
			"baseline": 151,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Se tomara el input del chip como el valor en el cual se evaluara la funcion, el ouput conformara\nla imagen para ese valor. la cantdiad de palabras del chip determinara el numero de elementos \nen el dominio de la funcion, el tamanio de la palabra determinara la cantidad de elementos del\ncodominio de la funcion.\n\n\n"
		},
		{
			"type": "image",
			"version": 488,
			"versionNonce": 522144644,
			"isDeleted": false,
			"id": "fj_LOqGqnM-OZnFDfdsd9",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -514.7021383226243,
			"y": -90.43066543529682,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"width": 776.3384015716548,
			"height": 53.37326510805127,
			"seed": 379202370,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223432,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "0cdf83581507587401d7e5b0c7be394391161316",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "text",
			"version": 450,
			"versionNonce": 1576017596,
			"isDeleted": false,
			"id": "NKL40Q2W",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -515.719590839117,
			"y": -28.05352664525799,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 790,
			"height": 50,
			"seed": 1164242462,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1662511223432,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "La sigla ROM significa read only memory, por lo que  son memorias donde no es \nposible determinar el ouput de una palabra en particular",
			"rawText": "La sigla ROM significa read only memory, por lo que  son memorias donde no es \nposible determinar el ouput de una palabra en particular",
			"baseline": 43,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "La sigla ROM significa read only memory, por lo que  son memorias donde no es \nposible determinar el ouput de una palabra en particular"
		},
		{
			"type": "image",
			"version": 422,
			"versionNonce": 1337146116,
			"isDeleted": false,
			"id": "GstWo3cbrxS2Wdly7aljS",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -508.769313206657,
			"y": 56.24848222284544,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"width": 831.890588478474,
			"height": 67.01340851632152,
			"seed": 181663582,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223432,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "861bce15eb6cf914e3d4b8432b55cf9daa451ad8",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "text",
			"version": 252,
			"versionNonce": 611641148,
			"isDeleted": false,
			"id": "csrkOk23",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": -500.14606989427136,
			"y": 133.24374347961225,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 72,
			"height": 25,
			"seed": 323057054,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1662511223432,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "TO DO",
			"rawText": "TO DO",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "TO DO"
		},
		{
			"type": "image",
			"version": 389,
			"versionNonce": 924662404,
			"isDeleted": false,
			"id": "LBWoekOTowNhxoil4Rcjd",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 632.3332316766317,
			"y": -395.7078459365222,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"width": 445.2857317243304,
			"height": 155.02540289661871,
			"seed": 663065497,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223432,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "59ac83ff8f0b442b44a01ddfc835f9f8263b1ba0",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "freedraw",
			"version": 385,
			"versionNonce": 1078763452,
			"isDeleted": false,
			"id": "c7sZVo85dXeCEM5EK5SGT",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 571.5282284430998,
			"y": -201.47509690829042,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 31.99999128069203,
			"height": 34.285736083984375,
			"seed": 48833721,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223432,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.1428397042410552,
					0
				],
				[
					3.4285627092633604,
					0
				],
				[
					5.714285714285666,
					1.1428615025112094
				],
				[
					7.99996512276789,
					3.428562709263417
				],
				[
					10.285688127790081,
					4.57142421177457
				],
				[
					11.428571428571331,
					5.714285714285722
				],
				[
					12.5714111328125,
					8.000008719308084
				],
				[
					10.285688127790081,
					11.428593226841542
				],
				[
					6.857125418526721,
					13.71427263532371
				],
				[
					2.2856794084821104,
					18.28571864536832
				],
				[
					-2.285723005022419,
					21.714281354631737
				],
				[
					-6.857169015067029,
					22.857164655412987
				],
				[
					-10.28573172433039,
					20.571441650390625
				],
				[
					-11.428571428571445,
					18.28571864536832
				],
				[
					-9.142892020089334,
					13.71427263532371
				],
				[
					-5.714285714285779,
					8.000008719308084
				],
				[
					-2.285723005022419,
					3.428562709263417
				],
				[
					-1.14288330078125,
					0
				],
				[
					1.1428397042410552,
					-2.285723005022305
				],
				[
					2.2856794084821104,
					-5.714285714285666
				],
				[
					1.1428397042410552,
					-6.857147216796875
				],
				[
					0,
					-8.000008719308028
				],
				[
					-3.428606305803669,
					-9.142848423549083
				],
				[
					-8.000008719308084,
					-9.142848423549083
				],
				[
					-12.571454729352695,
					-9.142848423549083
				],
				[
					-16.00001743861617,
					-10.285709926060235
				],
				[
					-19.42858014787953,
					-10.285709926060235
				],
				[
					-18.28574044363836,
					-11.428571428571388
				],
				[
					-18.28574044363836,
					-11.428571428571388
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0048828125,
				0.0224609375,
				0.1982421875,
				0.357421875,
				0.44921875,
				0.546875,
				0.5771484375,
				0.6572265625,
				0.6669921875,
				0.6669921875,
				0.666015625,
				0.662109375,
				0.6533203125,
				0.642578125,
				0.6328125,
				0.6298828125,
				0.6298828125,
				0.62890625,
				0.62890625,
				0.6298828125,
				0.6298828125,
				0.6328125,
				0.63671875,
				0.640625,
				0.64453125,
				0.642578125,
				0.60546875,
				0.36328125,
				0.009765625,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 374,
			"versionNonce": 807094788,
			"isDeleted": false,
			"id": "ZygoT-01XYmi9Mki5O7jn",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 563.5282197237918,
			"y": -228.90366397720777,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 50.28573172433039,
			"height": 94.8571341378348,
			"seed": 615215159,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223432,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					3.428562709263474,
					0
				],
				[
					6.857125418526834,
					0
				],
				[
					12.5714111328125,
					2.2857012067522646
				],
				[
					18.285696847098166,
					4.57142421177457
				],
				[
					22.85714285714289,
					7.999986921037987
				],
				[
					28.571428571428555,
					14.857134137834862
				],
				[
					33.142830984933084,
					22.85714285714289
				],
				[
					35.42855398995539,
					33.142852783203125
				],
				[
					36.57143729073664,
					45.71428571428572
				],
				[
					34.285714285714334,
					57.14285714285717
				],
				[
					28.571428571428555,
					68.57142857142856
				],
				[
					17.142857142857224,
					80
				],
				[
					4.571402413504416,
					89.14284842354914
				],
				[
					-5.714285714285666,
					93.71429443359375
				],
				[
					-12.571454729352695,
					94.8571341378348
				],
				[
					-13.71429443359375,
					93.71429443359375
				],
				[
					-12.571454729352695,
					92.5714111328125
				],
				[
					-12.571454729352695,
					92.5714111328125
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0009765625,
				0.09765625,
				0.2392578125,
				0.34375,
				0.421875,
				0.4638671875,
				0.4990234375,
				0.5126953125,
				0.521484375,
				0.5302734375,
				0.5390625,
				0.5439453125,
				0.5400390625,
				0.509765625,
				0.40234375,
				0.2109375,
				0.064453125,
				0.0107421875,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 311,
			"versionNonce": 1771653180,
			"isDeleted": false,
			"id": "dM3K4oBgNMutZFCSJXQE8",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 576.6331459074361,
			"y": 108.32173388689569,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 11.350901426665018,
			"height": 13.032522392513897,
			"seed": 1584187737,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223432,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-0.4204132600252706
				],
				[
					-0.4203972228991688,
					-0.8408104829244678
				],
				[
					-0.4203972228991688,
					-1.2612077058236366
				],
				[
					-1.2612077058237219,
					-1.6816209658489072
				],
				[
					-1.6816049287228907,
					-1.6816209658489072
				],
				[
					-2.9428286716726006,
					-1.6816209658489072
				],
				[
					-4.624433600395491,
					-1.2612077058236366
				],
				[
					-6.30605456624437,
					0
				],
				[
					-7.567262272067978,
					1.261207705823665
				],
				[
					-9.248883237916857,
					2.9428286716725722
				],
				[
					-10.510090943740579,
					5.044846860420677
				],
				[
					-10.930488166639748,
					7.146865049168781
				],
				[
					-11.350901426665018,
					8.828469977891615
				],
				[
					-11.350901426665018,
					9.669280460816083
				],
				[
					-10.510090943740579,
					10.93048816663972
				],
				[
					-9.66928046081614,
					11.35090142666499
				],
				[
					-8.408072754992531,
					11.35090142666499
				],
				[
					-7.1468650491688095,
					11.35090142666499
				],
				[
					-5.8856413062190995,
					11.35090142666499
				],
				[
					-4.624433600395491,
					10.51009094374055
				],
				[
					-3.7836231174709383,
					10.08967768371528
				],
				[
					-2.9428286716726006,
					9.669280460816083
				],
				[
					-2.1020181887481613,
					9.669280460816083
				],
				[
					-1.6816049287228907,
					9.248883237916885
				],
				[
					-1.6816049287228907,
					9.248883237916885
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0,
				0.0283203125,
				0.3291015625,
				0.3916015625,
				0.4384765625,
				0.4853515625,
				0.58984375,
				0.6455078125,
				0.677734375,
				0.69140625,
				0.69921875,
				0.69921875,
				0.7001953125,
				0.7021484375,
				0.703125,
				0.7060546875,
				0.70703125,
				0.7021484375,
				0.6953125,
				0.662109375,
				0.5302734375,
				0.4189453125,
				0.2021484375,
				0.08203125,
				0.0234375,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 309,
			"versionNonce": 229337476,
			"isDeleted": false,
			"id": "snDn-BGL62yiEo6rdGUVa",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 585.0412186624287,
			"y": 108.32173388689569,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 10.089677683715308,
			"height": 11.77131468669026,
			"seed": 1952054103,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223432,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-0.4204132600252706
				],
				[
					-0.4203972228991688,
					0
				],
				[
					-1.2612077058237219,
					0.42039722289919723
				],
				[
					-1.6816049287228907,
					0.42039722289919723
				],
				[
					-2.9428286716726006,
					1.261207705823665
				],
				[
					-3.7836231174709383,
					2.1020181887481044
				],
				[
					-4.624433600395491,
					2.5224154116473017
				],
				[
					-5.044846860420762,
					2.9428286716725722
				],
				[
					-5.465244083319931,
					3.3632258945717695
				],
				[
					-5.044846860420762,
					3.7836231174709383
				],
				[
					-4.624433600395491,
					4.204036377496209
				],
				[
					-3.7836231174709383,
					4.624433600395406
				],
				[
					-2.52241541164733,
					4.624433600395406
				],
				[
					-0.4203972228991688,
					6.306054566244313
				],
				[
					0,
					7.567262272067978
				],
				[
					-1.6816049287228907,
					9.248883237916885
				],
				[
					-5.465244083319931,
					10.93048816663972
				],
				[
					-7.1468650491688095,
					11.35090142666499
				],
				[
					-7.987659494967147,
					11.35090142666499
				],
				[
					-9.248883237916857,
					10.51009094374055
				],
				[
					-10.089677683715308,
					9.669280460816083
				],
				[
					-10.089677683715308,
					9.248883237916885
				],
				[
					-10.089677683715308,
					9.248883237916885
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0009765625,
				0.03515625,
				0.361328125,
				0.44140625,
				0.453125,
				0.4736328125,
				0.478515625,
				0.4716796875,
				0.4765625,
				0.486328125,
				0.4912109375,
				0.48828125,
				0.486328125,
				0.4921875,
				0.501953125,
				0.5126953125,
				0.5166015625,
				0.525390625,
				0.5263671875,
				0.525390625,
				0.455078125,
				0.1884765625,
				0.1162109375,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 311,
			"versionNonce": 71098556,
			"isDeleted": false,
			"id": "WOyFhqu0Yv-CveWEVDhMt",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 566.1230549636955,
			"y": 132.7051416689485,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 11.771298649564187,
			"height": 13.452919615413066,
			"seed": 1428409369,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223432,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.2612077058237219,
					0
				],
				[
					2.1020181887480476,
					0
				],
				[
					2.9428286716726006,
					0.4203972228991688
				],
				[
					3.78363915459704,
					0.8408104829244394
				],
				[
					4.204036377496209,
					1.6816209658489072
				],
				[
					4.624449637521479,
					2.5224154116473017
				],
				[
					5.044846860420648,
					4.204036377496209
				],
				[
					5.044846860420648,
					5.885657343345116
				],
				[
					4.624449637521479,
					7.56726227206795
				],
				[
					3.78363915459704,
					9.669280460816083
				],
				[
					2.522431448773318,
					11.350901426664961
				],
				[
					0,
					12.612109132488627
				],
				[
					-2.1020181887480476,
					13.452919615413066
				],
				[
					-6.30605456624437,
					11.771298649564187
				],
				[
					-6.726451789143539,
					7.56726227206795
				],
				[
					-5.465244083319817,
					4.624433600395406
				],
				[
					-3.7836231174709383,
					2.5224154116473017
				],
				[
					-2.1020181887480476,
					0.8408104829244394
				],
				[
					-0.4203972228991688,
					0.4203972228991688
				],
				[
					0.8408104829244394,
					0.4203972228991688
				],
				[
					1.6816209658489925,
					0.8408104829244394
				],
				[
					2.1020181887480476,
					2.5224154116473017
				],
				[
					2.9428286716726006,
					4.624433600395406
				],
				[
					2.9428286716726006,
					5.044846860420648
				],
				[
					2.9428286716726006,
					5.044846860420648
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.001953125,
				0.267578125,
				0.3642578125,
				0.48046875,
				0.599609375,
				0.6611328125,
				0.6943359375,
				0.732421875,
				0.744140625,
				0.7412109375,
				0.7451171875,
				0.74609375,
				0.73828125,
				0.7353515625,
				0.734375,
				0.7451171875,
				0.751953125,
				0.7548828125,
				0.7568359375,
				0.7412109375,
				0.6396484375,
				0.466796875,
				0.19921875,
				0.01953125,
				0.00390625,
				0
			]
		},
		{
			"type": "rectangle",
			"version": 991,
			"versionNonce": 319527172,
			"isDeleted": false,
			"id": "2E_G9qGAdlLI7MNc5TFJ3",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1292.7132021012308,
			"y": -212.82028801451656,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 112.30011255130835,
			"height": 118.32467760697281,
			"seed": 1690089433,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "sharp",
			"boundElements": [
				{
					"id": "P0b65Gq5",
					"type": "text"
				}
			],
			"updated": 1662511223432,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 518,
			"versionNonce": 668559676,
			"isDeleted": false,
			"id": "P0b65Gq5",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1297.7132021012308,
			"y": -162.15794921103014,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 102.30011255130835,
			"height": 17,
			"seed": 1806643545,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1662511223432,
			"link": null,
			"locked": false,
			"fontSize": 13.865014610506565,
			"fontFamily": 1,
			"text": "8kx8",
			"rawText": "8kx8",
			"baseline": 12,
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "2E_G9qGAdlLI7MNc5TFJ3",
			"originalText": "8kx8"
		},
		{
			"type": "line",
			"version": 659,
			"versionNonce": 1807341700,
			"isDeleted": false,
			"id": "A-LwgAFFm419Jx_yJ7i06",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 636.4728036647418,
			"y": -200.68806513337563,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 87.61973250133843,
			"height": 0,
			"seed": 960878615,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223432,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					87.61973250133843,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 719,
			"versionNonce": 668000700,
			"isDeleted": false,
			"id": "qx6Fk2YtL0Lffgt1eRvwW",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 635.3600267584291,
			"y": -186.2867447477148,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 87.61973250133843,
			"height": 0,
			"seed": 1728258359,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223432,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					87.61973250133843,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 727,
			"versionNonce": 594814980,
			"isDeleted": false,
			"id": "oWhwDem1eiBTxtUGZS_Sy",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 637.0381969509056,
			"y": -165.21762529115063,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 87.61973250133843,
			"height": 0,
			"seed": 863283833,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223432,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					87.61973250133843,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 786,
			"versionNonce": 457525820,
			"isDeleted": false,
			"id": "g5og3xXSLQ0qOccuiL0_l",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 635.9265735162896,
			"y": -149.736310426792,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 87.61973250133843,
			"height": 0,
			"seed": 1801196951,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223432,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					87.61973250133843,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 689,
			"versionNonce": 507021188,
			"isDeleted": false,
			"id": "5dBFSI617zW9XJSX15R9M",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 636.2258095111358,
			"y": -134.26117188376975,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 87.61973250133843,
			"height": 0,
			"seed": 797664473,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223432,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					87.61973250133843,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 751,
			"versionNonce": 1696113340,
			"isDeleted": false,
			"id": "GSoGJCSKdgLquwFYAQsyO",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 635.1141524048037,
			"y": -118.7012779360607,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 87.61973250133843,
			"height": 0,
			"seed": 1827451191,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223432,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					87.61973250133843,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 758,
			"versionNonce": 272955140,
			"isDeleted": false,
			"id": "Nuhhz_9ZC65OghA_nbE29",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 636.7700315052173,
			"y": -98.6960752507614,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 87.61973250133843,
			"height": 0,
			"seed": 710631865,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223432,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					87.61973250133843,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 819,
			"versionNonce": 1005382460,
			"isDeleted": false,
			"id": "Ja9kb8gxK3tavBcMECVoU",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 635.6561610260121,
			"y": -83.19911196244493,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 87.61973250133843,
			"height": 0,
			"seed": 1154445911,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223432,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					87.61973250133843,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 711,
			"versionNonce": 1981249156,
			"isDeleted": false,
			"id": "g8-VQNysCE7653qGkH0E3",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 634.1269992346963,
			"y": -66.55768800291526,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 87.61973250133843,
			"height": 0,
			"seed": 1229761335,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223432,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					87.61973250133843,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 772,
			"versionNonce": 841229244,
			"isDeleted": false,
			"id": "YqWdJfEWIaf6Yg5cYIpv7",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 632.9895222494081,
			"y": -50.9828358823072,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 87.61973250133843,
			"height": 0,
			"seed": 1066403769,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223432,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					87.61973250133843,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 779,
			"versionNonce": 208537092,
			"isDeleted": false,
			"id": "4TbdHDLIwNs19YrnRitk-",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 634.7136359106923,
			"y": -31.029422701752196,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 87.61973250133843,
			"height": 0,
			"seed": 1193290839,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223432,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					87.61973250133843,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 840,
			"versionNonce": 1038109756,
			"isDeleted": false,
			"id": "nWsgquzq5cZA-DmaDQvXY",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 633.5743628171715,
			"y": -15.468668805081734,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 87.61973250133843,
			"height": 0,
			"seed": 1535682713,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223432,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					87.61973250133843,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 744,
			"versionNonce": 1212589444,
			"isDeleted": false,
			"id": "UAOzMu4UHL-jZAdSIUupO",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 633.8420021067266,
			"y": 0.08854514991389806,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 87.61973250133843,
			"height": 0,
			"seed": 2099677559,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223432,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					87.61973250133843,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 964,
			"versionNonce": 1090741436,
			"isDeleted": false,
			"id": "W1cBFRxzlZ9zhCVV3W9HI",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 585.4299216537122,
			"y": 38.52344538702482,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 137.81530402171904,
			"height": 0.47223351979378947,
			"seed": 897199481,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223433,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					137.81530402171904,
					-0.47223351979378947
				]
			]
		},
		{
			"type": "line",
			"version": 822,
			"versionNonce": 1323259140,
			"isDeleted": false,
			"id": "hrnQgZiDxbxdzukICfPlE",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1258.6363238607623,
			"y": -206.97934477719434,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 1944736953,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223433,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 881,
			"versionNonce": 288320828,
			"isDeleted": false,
			"id": "CX-HtLn0mwVKW7zY2wlG7",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1258.5237619544027,
			"y": -200.73442237862514,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 152130969,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223433,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 889,
			"versionNonce": 1840649348,
			"isDeleted": false,
			"id": "s7dpYDx45AtE7zFyXfHBj",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1258.6074430799558,
			"y": -192.97298051765802,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 1734687353,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223433,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 950,
			"versionNonce": 2143708604,
			"isDeleted": false,
			"id": "g7I5kuBAnxwOD70Cp3FHX",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1258.5699118390125,
			"y": -187.21707741362718,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 531202905,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223433,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 851,
			"versionNonce": 310961156,
			"isDeleted": false,
			"id": "8IKodIIWIL0ehNifxW0qO",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1258.5598477892977,
			"y": -181.0439242492564,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 1580314681,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223433,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 914,
			"versionNonce": 1642745404,
			"isDeleted": false,
			"id": "A4VPylbxnx0A0569VRCGR",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1258.1426118662316,
			"y": -175.31533675912283,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 2028028185,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223433,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 921,
			"versionNonce": 1129694084,
			"isDeleted": false,
			"id": "tm_AVRAGfZX-IMOqUxokv",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1258.545541195184,
			"y": -167.61579433130896,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 1026274809,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223433,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 982,
			"versionNonce": 410855100,
			"isDeleted": false,
			"id": "iDVbWYAWo7UQiv28Jrcv5",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1258.3142496762507,
			"y": -161.22111666426815,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 2115276505,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223433,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 872,
			"versionNonce": 375042820,
			"isDeleted": false,
			"id": "FTWHEdBv9rv1D04fXZ4tX",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1257.512824280367,
			"y": -155.41859545000113,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 1647266745,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223433,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 934,
			"versionNonce": 404811580,
			"isDeleted": false,
			"id": "gTV1HmhplDowWuOZNIyOG",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1257.1106501955514,
			"y": -148.92872721504727,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 1906273433,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223433,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 941,
			"versionNonce": 706065028,
			"isDeleted": false,
			"id": "_BCkVRu8EWcw-JlevBuS-",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1257.7825883689097,
			"y": -141.35352904956767,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 1679323513,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223433,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1001,
			"versionNonce": 1899472828,
			"isDeleted": false,
			"id": "cjhBH5x_bvtHGUBDlLous",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1257.5114835558184,
			"y": -135.6883326701177,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 786291289,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223433,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 907,
			"versionNonce": 491045380,
			"isDeleted": false,
			"id": "HDYWy9g5V65AG2mVi2Ljs",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1257.4289311886264,
			"y": -129.60383249720917,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 1388521273,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223433,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 908,
			"versionNonce": 1474515004,
			"isDeleted": false,
			"id": "UYnHRZQmvh17Fc2UKQn6C",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 586.2563920622135,
			"y": 53.945208661217066,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 136.22962868239676,
			"height": 0.9476051889347517,
			"seed": 978211543,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223433,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					136.22962868239676,
					0.9476051889347517
				]
			]
		},
		{
			"type": "text",
			"version": 441,
			"versionNonce": 115728772,
			"isDeleted": false,
			"id": "ldHZNxFH",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1296.1936798376305,
			"y": -122.23541862024854,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 14,
			"height": 22,
			"seed": 1083249305,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1662511223433,
			"link": null,
			"locked": false,
			"fontSize": 9.301747036482514,
			"fontFamily": 1,
			"text": "CS\nOE",
			"rawText": "CS\nOE",
			"baseline": 19,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "CS\nOE"
		},
		{
			"type": "line",
			"version": 925,
			"versionNonce": 738584764,
			"isDeleted": false,
			"id": "GfHTAB01EQJHdnd-tuAXi",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1262.9291022461225,
			"y": -116.66738862826742,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 29.63565761011434,
			"height": 0,
			"seed": 416664217,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223433,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					29.63565761011434,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 913,
			"versionNonce": 1849102596,
			"isDeleted": false,
			"id": "f4603f5QWUqQHw6eu9ZeC",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1263.1435799155674,
			"y": -105.83528443060095,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 29.63565761011434,
			"height": 0,
			"seed": 210285689,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223433,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					29.63565761011434,
					0
				]
			]
		},
		{
			"type": "rectangle",
			"version": 1045,
			"versionNonce": 21066044,
			"isDeleted": false,
			"id": "mA1NJcjGIidfQzTtUCTpj",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1294.5239194182718,
			"y": -88.63656875804554,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 112.30011255130835,
			"height": 118.32467760697281,
			"seed": 1666347545,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "sharp",
			"boundElements": [
				{
					"id": "mx5M47NK",
					"type": "text"
				}
			],
			"updated": 1662511223433,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 574,
			"versionNonce": 1119244420,
			"isDeleted": false,
			"id": "mx5M47NK",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1299.5239194182718,
			"y": -37.974229954559135,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 102.30011255130835,
			"height": 17,
			"seed": 114825207,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1662511223433,
			"link": null,
			"locked": false,
			"fontSize": 13.865014610506565,
			"fontFamily": 1,
			"text": "8kx8",
			"rawText": "8kx8",
			"baseline": 12,
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "mA1NJcjGIidfQzTtUCTpj",
			"originalText": "8kx8"
		},
		{
			"type": "line",
			"version": 873,
			"versionNonce": 653781436,
			"isDeleted": false,
			"id": "B-NS2PB9rbZnUrQZxJK3V",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1260.4470411778034,
			"y": -82.7956255207232,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 72271609,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223433,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 932,
			"versionNonce": 1411489796,
			"isDeleted": false,
			"id": "KDlaSAyJs6H5OZREHvoat",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1260.334479271443,
			"y": -76.55070312215389,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 1109393687,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223433,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 940,
			"versionNonce": 810242620,
			"isDeleted": false,
			"id": "bzgWE_NrLDqaFPXw0Wp7J",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1260.4181603969969,
			"y": -68.78926126118677,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 1890418649,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223433,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1001,
			"versionNonce": 1249312644,
			"isDeleted": false,
			"id": "Lz-JJIyMud49q7WidrYEK",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1260.3806291560536,
			"y": -63.033358157156044,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 1523435063,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223433,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 902,
			"versionNonce": 2082319036,
			"isDeleted": false,
			"id": "FrbtKac9mPRS2ICnMW13p",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1260.3705651063378,
			"y": -56.86020499278516,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 1451367609,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223433,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 965,
			"versionNonce": 502558468,
			"isDeleted": false,
			"id": "xP3vWANtO6PvfF5JDg88y",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1259.9533291832718,
			"y": -51.13161750265158,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 1606805335,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223433,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 972,
			"versionNonce": 1024521020,
			"isDeleted": false,
			"id": "Op-BkLDsTe-L_cCDVLK3I",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1260.356258512224,
			"y": -43.43207507483771,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 1433410969,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223433,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1033,
			"versionNonce": 253226628,
			"isDeleted": false,
			"id": "Z0iLFrLhB8XQ8bth9e1_m",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1260.1249669932909,
			"y": -37.037397407797016,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 257746039,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223433,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 924,
			"versionNonce": 25635772,
			"isDeleted": false,
			"id": "Svr8GhDm7YuMhqY7PgE6S",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1259.3235415974073,
			"y": -31.23487619353,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 1286275705,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223433,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 986,
			"versionNonce": 513768964,
			"isDeleted": false,
			"id": "rOiMGT_vfSfyT6el0Trnu",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1258.9213675125916,
			"y": -24.745007958576025,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 1767325079,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223433,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 993,
			"versionNonce": 1000494140,
			"isDeleted": false,
			"id": "aHZmDQRmgKrAJgVsclDCs",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1259.5933056859508,
			"y": -17.16980979309642,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 1760971609,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223433,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1053,
			"versionNonce": 92872068,
			"isDeleted": false,
			"id": "9vSTssIHtJ0CKR9egn6y3",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1259.3222008728594,
			"y": -11.504613413646439,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 15299255,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223433,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 959,
			"versionNonce": 1229221052,
			"isDeleted": false,
			"id": "xKU4b-bV9KaHDIX7oaywO",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1259.2396485056674,
			"y": -5.420113240737919,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 1923446841,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223433,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 493,
			"versionNonce": 756206852,
			"isDeleted": false,
			"id": "cXiMzxEg",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1298.0043971546706,
			"y": 1.9483006362224842,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 14,
			"height": 22,
			"seed": 246940631,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1662511223433,
			"link": null,
			"locked": false,
			"fontSize": 9.301747036482514,
			"fontFamily": 1,
			"text": "CS\nOE",
			"rawText": "CS\nOE",
			"baseline": 19,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "CS\nOE"
		},
		{
			"type": "line",
			"version": 977,
			"versionNonce": 2081387836,
			"isDeleted": false,
			"id": "riucK_L6BOkcTg-u1V0Hz",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1264.7398195631636,
			"y": 7.516330628203832,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 29.63565761011434,
			"height": 0,
			"seed": 1536952601,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223433,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					29.63565761011434,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 965,
			"versionNonce": 649759876,
			"isDeleted": false,
			"id": "OhlWgqxfZQRkRA7JL0wf7",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1264.9542972326076,
			"y": 18.3484348258703,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 29.63565761011434,
			"height": 0,
			"seed": 1121415415,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223433,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					29.63565761011434,
					0
				]
			]
		},
		{
			"type": "rectangle",
			"version": 1105,
			"versionNonce": 560295356,
			"isDeleted": false,
			"id": "q27ivZdrKGkWfcfI4sAng",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1292.3315965540128,
			"y": 36.31321699753403,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 112.30011255130835,
			"height": 118.32467760697281,
			"seed": 1670930105,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "sharp",
			"boundElements": [
				{
					"id": "6gqUqiUs",
					"type": "text"
				}
			],
			"updated": 1662511223433,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 633,
			"versionNonce": 608066564,
			"isDeleted": false,
			"id": "6gqUqiUs",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1297.3315965540128,
			"y": 86.97555580102043,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 102.30011255130835,
			"height": 17,
			"seed": 128763223,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1662511223433,
			"link": null,
			"locked": false,
			"fontSize": 13.865014610506565,
			"fontFamily": 1,
			"text": "8kx8",
			"rawText": "8kx8",
			"baseline": 12,
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "q27ivZdrKGkWfcfI4sAng",
			"originalText": "8kx8"
		},
		{
			"type": "line",
			"version": 912,
			"versionNonce": 174609980,
			"isDeleted": false,
			"id": "-oOPL85Som4kiumK1WW-2",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1258.2547183135443,
			"y": 42.15416023485636,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 711860121,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223433,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 971,
			"versionNonce": 1872509828,
			"isDeleted": false,
			"id": "W93f0Bj8MiSA62X9jN4G4",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1258.1421564071838,
			"y": 48.39908263342568,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 314049143,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223434,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 979,
			"versionNonce": 335163068,
			"isDeleted": false,
			"id": "XQOJCjlWIwBMPo790Irq7",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1258.2258375327378,
			"y": 56.1605244943928,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 379110521,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223434,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1040,
			"versionNonce": 1662135044,
			"isDeleted": false,
			"id": "IGTEIAHDdTDfXQjKwI0iy",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1258.1883062917946,
			"y": 61.916427598423525,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 1335794583,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223434,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 941,
			"versionNonce": 784135996,
			"isDeleted": false,
			"id": "WL7bNymv_gSGSic7EhNcJ",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1258.1782422420788,
			"y": 68.08958076279441,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 1943784793,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223434,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1004,
			"versionNonce": 1629366916,
			"isDeleted": false,
			"id": "orNZ-A80db5JA66MGXbyY",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1257.7610063190127,
			"y": 73.81816825292776,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 580194487,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223434,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1011,
			"versionNonce": 1729277884,
			"isDeleted": false,
			"id": "49OEYgtKXYFo1YVTrqK3c",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1258.163935647965,
			"y": 81.51771068074186,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 1233828409,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223434,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1072,
			"versionNonce": 1283340804,
			"isDeleted": false,
			"id": "sgSLHmBpB6WTzicZeXQSE",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1257.9326441290318,
			"y": 87.91238834778255,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 1967120855,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223434,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 963,
			"versionNonce": 1830639676,
			"isDeleted": false,
			"id": "XkPtq6HsPrsM3_FEg8Ma7",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1257.1312187331482,
			"y": 93.71490956204957,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 1753811737,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223434,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1025,
			"versionNonce": 3168644,
			"isDeleted": false,
			"id": "rnRwFsSZhD2DZl7FiJrCE",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1256.7290446483325,
			"y": 100.20477779700332,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 145985271,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223434,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1032,
			"versionNonce": 482275516,
			"isDeleted": false,
			"id": "DpXU8Xf-u4AGVASbXdx-j",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1257.4009828216917,
			"y": 107.77997596248292,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 961167353,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223434,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1092,
			"versionNonce": 1198688516,
			"isDeleted": false,
			"id": "q1xDtXwWO15n-fxA-CKU3",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1257.1298780086004,
			"y": 113.44517234193313,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 125081623,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223434,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 998,
			"versionNonce": 93944124,
			"isDeleted": false,
			"id": "wXvk-0aLdeGPSR7zlRrZL",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1257.0473256414084,
			"y": 119.52967251484142,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 1238489305,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223434,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 532,
			"versionNonce": 1438828676,
			"isDeleted": false,
			"id": "kWuRIPX0",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1295.8120742904116,
			"y": 126.89808639180205,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 14,
			"height": 22,
			"seed": 1467448631,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1662511223434,
			"link": null,
			"locked": false,
			"fontSize": 9.301747036482514,
			"fontFamily": 1,
			"text": "CS\nOE",
			"rawText": "CS\nOE",
			"baseline": 19,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "CS\nOE"
		},
		{
			"type": "line",
			"version": 1016,
			"versionNonce": 1930359228,
			"isDeleted": false,
			"id": "8847jZVXrvUn5zDc445BC",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1262.5474966989045,
			"y": 132.46611638378317,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 29.63565761011434,
			"height": 0,
			"seed": 464737721,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223434,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					29.63565761011434,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1004,
			"versionNonce": 1054808068,
			"isDeleted": false,
			"id": "0XiYyS0088Z8AM1YDneTE",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1262.7619743683485,
			"y": 143.29822058144987,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 29.63565761011434,
			"height": 0,
			"seed": 740343383,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223434,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					29.63565761011434,
					0
				]
			]
		},
		{
			"type": "rectangle",
			"version": 1138,
			"versionNonce": 1950439996,
			"isDeleted": false,
			"id": "Ex94rwUJTUPPGOYmfkpv7",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1294.142313871053,
			"y": 160.49693625400528,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 112.30011255130835,
			"height": 118.32467760697281,
			"seed": 840054425,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "sharp",
			"boundElements": [
				{
					"id": "NSqHBgcX",
					"type": "text"
				}
			],
			"updated": 1662511223434,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 666,
			"versionNonce": 1858434948,
			"isDeleted": false,
			"id": "NSqHBgcX",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1299.142313871053,
			"y": 211.1592750574917,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 102.30011255130835,
			"height": 17,
			"seed": 1480907639,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1662511223434,
			"link": null,
			"locked": false,
			"fontSize": 13.865014610506565,
			"fontFamily": 1,
			"text": "8kx8",
			"rawText": "8kx8",
			"baseline": 12,
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "Ex94rwUJTUPPGOYmfkpv7",
			"originalText": "8kx8"
		},
		{
			"type": "line",
			"version": 964,
			"versionNonce": 1678947004,
			"isDeleted": false,
			"id": "ofGFbnDuLz3iXxMdK0w1M",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1260.0654356305845,
			"y": 166.33787949132739,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 1604451193,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223434,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1023,
			"versionNonce": 565438212,
			"isDeleted": false,
			"id": "MAmIUTHrLdeYoq9U5ofZM",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1259.952873724225,
			"y": 172.5828018898967,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 1613255831,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223434,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1031,
			"versionNonce": 1898249020,
			"isDeleted": false,
			"id": "lVh53cCyqU8Pc3RrwU-M4",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1260.036554849778,
			"y": 180.34424375086382,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 1420174425,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223434,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1092,
			"versionNonce": 1546151556,
			"isDeleted": false,
			"id": "oPNtIyzp5f765D-W5MQu7",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1259.9990236088347,
			"y": 186.10014685489455,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 1266657719,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223434,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 993,
			"versionNonce": 635057084,
			"isDeleted": false,
			"id": "VOg62YcqYnsWspZ5jdTom",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1259.9889595591198,
			"y": 192.27330001926543,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 1827811641,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223434,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1056,
			"versionNonce": 1658910212,
			"isDeleted": false,
			"id": "_EG1VcwPlf34r0Gbys-ka",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1259.5717236360538,
			"y": 198.001887509399,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 930044631,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223434,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1063,
			"versionNonce": 1884576828,
			"isDeleted": false,
			"id": "19p3VTAIrcPzfGoKkgD8f",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1259.974652965006,
			"y": 205.70142993721288,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 1038721561,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223434,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1124,
			"versionNonce": 853251460,
			"isDeleted": false,
			"id": "Yb3PshPwQ2pRS6w99FSQs",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1259.7433614460729,
			"y": 212.09610760425358,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 680257527,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223434,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1015,
			"versionNonce": 712340668,
			"isDeleted": false,
			"id": "CcCx2TUbO7pcWaDnhDaGj",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1258.9419360501893,
			"y": 217.8986288185206,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 1686107897,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223434,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1077,
			"versionNonce": 2035696900,
			"isDeleted": false,
			"id": "H0JegPiqZ_yUKLFEle05H",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1258.5397619653736,
			"y": 224.38849705347457,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 484036887,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223434,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1084,
			"versionNonce": 568294716,
			"isDeleted": false,
			"id": "vwXXbq7BY0I5zJEtec-ei",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1259.2117001387319,
			"y": 231.96369521895417,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 322482137,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223434,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1144,
			"versionNonce": 198116484,
			"isDeleted": false,
			"id": "7APj2tqidcaBKdRKvWYJL",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1258.9405953256405,
			"y": 237.62889159840415,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 1573754423,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223435,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1050,
			"versionNonce": 536114620,
			"isDeleted": false,
			"id": "FNjB6cVqz8sBTuUzHRY4j",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1258.8580429584486,
			"y": 243.71339177131267,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 1613188281,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223435,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 584,
			"versionNonce": 1610863620,
			"isDeleted": false,
			"id": "zHoLJbXQ",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1297.6227916074527,
			"y": 251.08180564827325,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 14,
			"height": 22,
			"seed": 306952023,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1662511223435,
			"link": null,
			"locked": false,
			"fontSize": 9.301747036482514,
			"fontFamily": 1,
			"text": "CS\nOE",
			"rawText": "CS\nOE",
			"baseline": 19,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "CS\nOE"
		},
		{
			"type": "line",
			"version": 1068,
			"versionNonce": 1909874236,
			"isDeleted": false,
			"id": "5M7xi4e3P-jK2fQ4DpCDB",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1264.3582140159447,
			"y": 256.6498356402544,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 29.63565761011434,
			"height": 0,
			"seed": 1391414681,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223435,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					29.63565761011434,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1056,
			"versionNonce": 66237316,
			"isDeleted": false,
			"id": "FsZqfV0asl2zuzNnR2Sms",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1264.5726916853896,
			"y": 267.4819398379209,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 29.63565761011434,
			"height": 0,
			"seed": 279491703,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223435,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					29.63565761011434,
					0
				]
			]
		},
		{
			"type": "rectangle",
			"version": 579,
			"versionNonce": 1885812412,
			"isDeleted": false,
			"id": "ISg8k14kE1sOGSl3UEFCY",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 956.9793717217078,
			"y": 81.15494162091841,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 76,
			"height": 58,
			"seed": 12817849,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "sharp",
			"boundElements": [
				{
					"type": "text",
					"id": "ZRCQD5Ms"
				}
			],
			"updated": 1662511223435,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 734,
			"versionNonce": 366584580,
			"isDeleted": false,
			"id": "hPmhXqqZKLVcpYyU9NIUd",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1032.5680247920025,
			"y": 96.8160123497064,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 58.12816068176073,
			"height": 0,
			"seed": 1345037975,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223435,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					58.12816068176073,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 794,
			"versionNonce": 139001660,
			"isDeleted": false,
			"id": "5O_f2q_9_UePIpUx8YefE",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1032.4208228110135,
			"y": 105.63946834375486,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 58.12816068176073,
			"height": 0,
			"seed": 1454961241,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223435,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					58.12816068176073,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 801,
			"versionNonce": 1010213508,
			"isDeleted": false,
			"id": "GfEfaNLXhE6BrFpqnAnFL",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1033.0207963917107,
			"y": 119.86119508938214,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 58.12816068176073,
			"height": 0,
			"seed": 1128840119,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223435,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					58.12816068176073,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 860,
			"versionNonce": 1105049532,
			"isDeleted": false,
			"id": "S6p0PxINZA7cPy1Q4gzo_",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1032.6599548469574,
			"y": 130.43478845980098,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 58.12816068176073,
			"height": 0,
			"seed": 2138783545,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223435,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					58.12816068176073,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 349,
			"versionNonce": 499626500,
			"isDeleted": false,
			"id": "ZRCQD5Ms",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 961.9793717217078,
			"y": 100.15494162091841,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 66,
			"height": 20,
			"seed": 300424345,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1662511223435,
			"link": null,
			"locked": false,
			"fontSize": 16,
			"fontFamily": 1,
			"text": "Decoder",
			"rawText": "Decoder",
			"baseline": 15,
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "ISg8k14kE1sOGSl3UEFCY",
			"originalText": "Decoder"
		},
		{
			"type": "line",
			"version": 423,
			"versionNonce": 1229414460,
			"isDeleted": false,
			"id": "ECi8sSOQSCflChPSBCvqi",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1092.5853052964972,
			"y": 96.94568265090311,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 169.3733962835529,
			"height": 214.50586355726136,
			"seed": 936402489,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223435,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					169.3733962835529,
					-214.50586355726136
				]
			]
		},
		{
			"type": "line",
			"version": 445,
			"versionNonce": 1502269828,
			"isDeleted": false,
			"id": "xOTOTNe9ikylfqcoW8jXY",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1087.0071075799797,
			"y": 106.58070571047074,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 176.9800260161569,
			"height": 96.85727089373245,
			"seed": 398245751,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223435,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					176.9800260161569,
					-96.85727089373245
				]
			]
		},
		{
			"type": "line",
			"version": 374,
			"versionNonce": 1986525372,
			"isDeleted": false,
			"id": "3C-gx3pAe2xpVh43fM5Vg",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1088.528441264325,
			"y": 120.27255411308806,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 173.93735864746623,
			"height": 13.184750070876476,
			"seed": 475486137,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223435,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					173.93735864746623,
					13.184750070876476
				]
			]
		},
		{
			"type": "line",
			"version": 414,
			"versionNonce": 2126381316,
			"isDeleted": false,
			"id": "ZO4Hvvin18nX7GE3NNxy3",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1087.0071075799797,
			"y": 130.41467550439666,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 177.99422267963882,
			"height": 126.77653673591692,
			"seed": 297129431,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223435,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					177.99422267963882,
					126.77653673591692
				]
			]
		},
		{
			"type": "line",
			"version": 711,
			"versionNonce": 1424064828,
			"isDeleted": false,
			"id": "xumbdFy7z8ehz_mRZ5lg9",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1407.6586873050715,
			"y": -198.2890693313143,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 66.64546861703714,
			"height": 0,
			"seed": 1580743799,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223435,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					66.64546861703714,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 772,
			"versionNonce": 81739908,
			"isDeleted": false,
			"id": "lrRv6LZIX1qYDHfu0uWG2",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1406.7247003469079,
			"y": -187.26052329098525,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 66.64546861703714,
			"height": 0,
			"seed": 1842424441,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223435,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					66.64546861703714,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 780,
			"versionNonce": 739637692,
			"isDeleted": false,
			"id": "EbH1W2ok-3zTjBmiuBmSL",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1408.1209780779786,
			"y": -171.19509403903135,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 66.64546861703714,
			"height": 0,
			"seed": 1929876887,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223435,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					66.64546861703714,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 839,
			"versionNonce": 1135382532,
			"isDeleted": false,
			"id": "fmrazgQ5mLjw5pHrIfqyc",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1406.975549136106,
			"y": -159.35096816241048,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 66.64546861703714,
			"height": 0,
			"seed": 1394045785,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223435,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					66.64546861703714,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 742,
			"versionNonce": 120021564,
			"isDeleted": false,
			"id": "0a7r-YhZrSDde4d4gmflK",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1407.618093622888,
			"y": -147.66539288704416,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 66.64546861703714,
			"height": 0,
			"seed": 583977655,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223435,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					66.64546861703714,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 804,
			"versionNonce": 1797517188,
			"isDeleted": false,
			"id": "3vfQ8NU0EnmM_8Oi2q_PV",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1406.3365237086296,
			"y": -135.74686969817049,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 66.64546861703714,
			"height": 0,
			"seed": 1315020857,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223435,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					66.64546861703714,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 810,
			"versionNonce": 1022868156,
			"isDeleted": false,
			"id": "a54aAAxY8Haick16FvZ-W",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1407.6449807322465,
			"y": -120.38008306816994,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 66.64546861703714,
			"height": 0,
			"seed": 2050120663,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223435,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					66.64546861703714,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 872,
			"versionNonce": 2072207108,
			"isDeleted": false,
			"id": "VTPuNyVc0SBpQcGNN-MOV",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1407.21225560825,
			"y": -108.58386923605417,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 66.64546861703714,
			"height": 0,
			"seed": 1033056537,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223435,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					66.64546861703714,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 771,
			"versionNonce": 2015953724,
			"isDeleted": false,
			"id": "f4UDFfB0HLaWTll3D8xWT",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1407.8282992722038,
			"y": -69.3342415914658,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 66.64546861703714,
			"height": 0,
			"seed": 2052898969,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223435,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					66.64546861703714,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 832,
			"versionNonce": 1028185732,
			"isDeleted": false,
			"id": "faFkRQ5IhjnlrRQ7DnQfl",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1406.8943123140402,
			"y": -58.305695551136864,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 66.64546861703714,
			"height": 0,
			"seed": 2000679287,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223435,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					66.64546861703714,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 840,
			"versionNonce": 1058880444,
			"isDeleted": false,
			"id": "LceOBVn24ai0q14LDDyna",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1408.290590045111,
			"y": -42.24026629918285,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 66.64546861703714,
			"height": 0,
			"seed": 302728569,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223435,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					66.64546861703714,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 899,
			"versionNonce": 959606276,
			"isDeleted": false,
			"id": "GM47QiDNTYFTpA0YKVJG8",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1407.1451611032385,
			"y": -30.396140422562098,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 66.64546861703714,
			"height": 0,
			"seed": 1532013207,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223435,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					66.64546861703714,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 802,
			"versionNonce": 2079745084,
			"isDeleted": false,
			"id": "efNyDsceu_3MPnneoI3Ra",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1407.7877055900203,
			"y": -18.71056514719578,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 66.64546861703714,
			"height": 0,
			"seed": 1062612569,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223435,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					66.64546861703714,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 864,
			"versionNonce": 809373060,
			"isDeleted": false,
			"id": "oOVBsdCubH-pF4e-8n7Xp",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1406.506135675762,
			"y": -6.792041958322102,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 66.64546861703714,
			"height": 0,
			"seed": 724385719,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223435,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					66.64546861703714,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 870,
			"versionNonce": 76971196,
			"isDeleted": false,
			"id": "mTz2umDjVApDEUOAIrICd",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1407.8145926993789,
			"y": 8.574744671678445,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 66.64546861703714,
			"height": 0,
			"seed": 1494285113,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223435,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					66.64546861703714,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 932,
			"versionNonce": 329891076,
			"isDeleted": false,
			"id": "8WSDsuVWzWVvUXdR_Z8_0",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1407.3818675753823,
			"y": 20.370958503794213,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 66.64546861703714,
			"height": 0,
			"seed": 955920599,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223435,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					66.64546861703714,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 778,
			"versionNonce": 580879676,
			"isDeleted": false,
			"id": "wK2g_8PjZCPilr7gbSRbP",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1406.9222395656602,
			"y": 55.543361427968875,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 66.64546861703714,
			"height": 0,
			"seed": 1423535095,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223435,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					66.64546861703714,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 839,
			"versionNonce": 2096331908,
			"isDeleted": false,
			"id": "y5b9Td32LGkFbRe1E7ZSS",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1405.9882526074966,
			"y": 66.57190746829792,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 66.64546861703714,
			"height": 0,
			"seed": 280802041,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223435,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					66.64546861703714,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 847,
			"versionNonce": 460553660,
			"isDeleted": false,
			"id": "ULGb1mwAUX3ElIj1loNUX",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1407.3845303385674,
			"y": 82.63733672025194,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 66.64546861703714,
			"height": 0,
			"seed": 1826018583,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223435,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					66.64546861703714,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 906,
			"versionNonce": 634997764,
			"isDeleted": false,
			"id": "oFEwJSxEso7FJkNFAKhaM",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1406.2391013966949,
			"y": 94.48146259687269,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 66.64546861703714,
			"height": 0,
			"seed": 276687833,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223435,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					66.64546861703714,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 809,
			"versionNonce": 942958140,
			"isDeleted": false,
			"id": "-wWxsAqPFNazmYciNBAHk",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1406.8816458834767,
			"y": 106.167037872239,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 66.64546861703714,
			"height": 0,
			"seed": 797579831,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223435,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					66.64546861703714,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 871,
			"versionNonce": 1616456580,
			"isDeleted": false,
			"id": "ajFKTZnnze74Tpg4v75rp",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1405.6000759692183,
			"y": 118.08556106111268,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 66.64546861703714,
			"height": 0,
			"seed": 2036664505,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223436,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					66.64546861703714,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 877,
			"versionNonce": 1304706748,
			"isDeleted": false,
			"id": "cV-DdkifvEVztVZwbewCt",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1406.9085329928353,
			"y": 133.45234769111323,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 66.64546861703714,
			"height": 0,
			"seed": 30915415,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223436,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					66.64546861703714,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 939,
			"versionNonce": 246487812,
			"isDeleted": false,
			"id": "t1xgZENwBc5-ox7edtBp5",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1406.4758078688387,
			"y": 145.248561523229,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 66.64546861703714,
			"height": 0,
			"seed": 1964345753,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223436,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					66.64546861703714,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 768,
			"versionNonce": 1153763132,
			"isDeleted": false,
			"id": "TV1MYG0wsjxzLI5dlqRSH",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1410.395330195443,
			"y": 174.22997118859485,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 66.64546861703714,
			"height": 0,
			"seed": 13985559,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223436,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					66.64546861703714,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 829,
			"versionNonce": 459217540,
			"isDeleted": false,
			"id": "DVesRVll69aKnko3Ko48h",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1409.4613432372794,
			"y": 185.2585172289239,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 66.64546861703714,
			"height": 0,
			"seed": 787053017,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223436,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					66.64546861703714,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 837,
			"versionNonce": 563658684,
			"isDeleted": false,
			"id": "FHnq0BOFQjnrXhc5F2QZh",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1410.8576209683492,
			"y": 201.3239464808779,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 66.64546861703714,
			"height": 0,
			"seed": 702966839,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223436,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					66.64546861703714,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 896,
			"versionNonce": 1897998852,
			"isDeleted": false,
			"id": "Xnn182PxZpMJ65pxPV5NR",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1409.7121920264767,
			"y": 213.16807235749866,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 66.64546861703714,
			"height": 0,
			"seed": 523163321,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223436,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					66.64546861703714,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 799,
			"versionNonce": 207710268,
			"isDeleted": false,
			"id": "TyTTKBDzB6oDu0O28yeOY",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1410.3547365132586,
			"y": 224.85364763286498,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 66.64546861703714,
			"height": 0,
			"seed": 1356451159,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223436,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					66.64546861703714,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 861,
			"versionNonce": 1928677764,
			"isDeleted": false,
			"id": "tow8E67KVbTrbYZXCrr84",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1409.0731665990002,
			"y": 236.77217082173865,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 66.64546861703714,
			"height": 0,
			"seed": 477468569,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223436,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					66.64546861703714,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 867,
			"versionNonce": 1493237948,
			"isDeleted": false,
			"id": "qaiGivZ0uLG-QW4TGqxwg",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1410.381623622618,
			"y": 252.1389574517392,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 66.64546861703714,
			"height": 0,
			"seed": 1090783863,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223436,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					66.64546861703714,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 929,
			"versionNonce": 1947826436,
			"isDeleted": false,
			"id": "8nnt8QwR5fRRlzCbbEIX_",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1409.9488984986215,
			"y": 263.93517128385497,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 66.64546861703714,
			"height": 0,
			"seed": 1223769209,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223436,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					66.64546861703714,
					0
				]
			]
		},
		{
			"type": "freedraw",
			"version": 504,
			"versionNonce": 253331772,
			"isDeleted": false,
			"id": "RdYG5ZpLZlJKGvp44bkjr",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1653.9385967145458,
			"y": -156.44351696584317,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 38.22662305870338,
			"height": 17.0549526596831,
			"seed": 1291164087,
			"groupIds": [
				"W7xrk6JMYIVkBN7FMTmSD",
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223436,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					-1.859719048296891
				],
				[
					2.0583476525152196,
					-2.447823184938402
				],
				[
					3.2345334914913364,
					-2.7418808618358548
				],
				[
					3.822671279593089,
					-3.035927321579911
				],
				[
					4.998857118569314,
					-3.6240314582213955
				],
				[
					6.175042957545434,
					-3.6240314582213955
				],
				[
					7.645297690572484,
					-3.6240314582213955
				],
				[
					9.115552423599537,
					-3.6240314582213955
				],
				[
					10.879876050677517,
					-3.329973781323968
				],
				[
					12.64419967775539,
					-3.035927321579911
				],
				[
					14.702547330270596,
					-2.447823184938402
				],
				[
					17.05496387683653,
					-1.859719048296891
				],
				[
					19.407335554788872,
					-0.9775684519113527
				],
				[
					21.759752101354923,
					-0.09541785552578459
				],
				[
					23.5240757284329,
					0.7867327408597535
				],
				[
					26.170516300436066,
					2.5510451507842578
				],
				[
					28.228863952951162,
					3.727242206913854
				],
				[
					29.69911868597823,
					4.903450480196844
				],
				[
					31.46344231305621,
					6.373705213223926
				],
				[
					32.93369704608326,
					7.549902269353494
				],
				[
					34.10988288505936,
					8.726110542636519
				],
				[
					35.28611359264928,
					9.902318815919532
				],
				[
					35.87420651213735,
					10.784469412305079
				],
				[
					36.462299431625425,
					11.37257354894658
				],
				[
					37.05039235111345,
					11.960666468434663
				],
				[
					37.63853013921534,
					12.254724145332116
				],
				[
					37.932554164652466,
					12.842828281973638
				],
				[
					37.932554164652466,
					13.136874741717666
				],
				[
					38.22662305870338,
					13.136874741717666
				],
				[
					38.22662305870338,
					13.430921201461704
				],
				[
					38.22662305870338,
					13.136874741717666
				],
				[
					38.22662305870338,
					13.136874741717666
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0009765625,
				0.1845703125,
				0.2314453125,
				0.265625,
				0.2998046875,
				0.3212890625,
				0.3486328125,
				0.3759765625,
				0.400390625,
				0.4130859375,
				0.421875,
				0.4267578125,
				0.4287109375,
				0.4287109375,
				0.4287109375,
				0.4296875,
				0.4306640625,
				0.431640625,
				0.4306640625,
				0.4306640625,
				0.4296875,
				0.427734375,
				0.427734375,
				0.427734375,
				0.427734375,
				0.4208984375,
				0.4228515625,
				0.4248046875,
				0.4248046875,
				0.296875,
				0.11328125,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 499,
			"versionNonce": 806074500,
			"isDeleted": false,
			"id": "tSBdfZf49t7YljnocfOky",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1725.9818169218192,
			"y": -143.60068868386963,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.22776594013406,
			"height": 22.347867455149828,
			"seed": 1895347033,
			"groupIds": [
				"W7xrk6JMYIVkBN7FMTmSD",
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223436,
			"link": null,
			"locked": false,
			"points": [
				[
					-34.4046900680561,
					0
				],
				[
					-34.4046900680561,
					0.2940464597440292
				],
				[
					-34.11066604261899,
					0.2940464597440292
				],
				[
					-34.4046900680561,
					0.2940464597440292
				],
				[
					-34.11066604261899,
					0.2940464597440292
				],
				[
					-34.11066604261899,
					0
				],
				[
					-33.81659714856802,
					0
				],
				[
					-34.11066604261899,
					0.2940464597440292
				],
				[
					-34.4046900680561,
					1.176197056129597
				],
				[
					-34.99282785615795,
					2.0583476525151365
				],
				[
					-35.874944801083124,
					3.5286023855421855
				],
				[
					-37.3451995341102,
					5.292914795466689
				],
				[
					-38.81545426713721,
					6.763169528493736
				],
				[
					-41.75596373319132,
					9.409621317650384
				],
				[
					-44.69647319924543,
					11.467980187318945
				],
				[
					-46.754865720374326,
					12.938234920345995
				],
				[
					-49.69537518642842,
					14.996593790014561
				],
				[
					-52.635884652482495,
					16.466848523041612
				],
				[
					-55.28232522448566,
					17.937103256068653
				],
				[
					-57.6347417710517,
					19.113311529351684
				],
				[
					-59.98715831761771,
					19.995462125737205
				],
				[
					-62.04550597013284,
					20.877612722122773
				],
				[
					-64.10385362264796,
					21.465716858764264
				],
				[
					-65.86817724972597,
					21.759763318508316
				],
				[
					-66.45627016921404,
					22.05382099540578
				],
				[
					-67.04436308870208,
					22.347867455149828
				],
				[
					-67.04436308870208,
					22.347867455149828
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0,
				0.005859375,
				0.1240234375,
				0.1484375,
				0.1552734375,
				0.1591796875,
				0.193359375,
				0.3017578125,
				0.3017578125,
				0.3017578125,
				0.3017578125,
				0.3017578125,
				0.3017578125,
				0.3037109375,
				0.3037109375,
				0.3037109375,
				0.3037109375,
				0.3017578125,
				0.2998046875,
				0.29296875,
				0.275390625,
				0.244140625,
				0.203125,
				0.158203125,
				0.1162109375,
				0.013671875,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 508,
			"versionNonce": 1913455036,
			"isDeleted": false,
			"id": "HQio0ZLjQ7yxqwb4hoXdC",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1654.526689634035,
			"y": -158.5813810642005,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 10.585852025240156,
			"height": 38.52068073560078,
			"seed": 1600238489,
			"groupIds": [
				"W7xrk6JMYIVkBN7FMTmSD",
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223436,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					-0.3099590865812296
				],
				[
					0.29406889405082104,
					-0.6040167634786826
				],
				[
					0.5880929194880581,
					-0.6040167634786826
				],
				[
					0.8821618135388795,
					-0.6040167634786826
				],
				[
					1.1761858389761162,
					-0.6040167634786826
				],
				[
					1.470254733027048,
					-0.3099590865812296
				],
				[
					2.0583476525151063,
					-0.015912626837172775
				],
				[
					2.940509466054096,
					0.8662379695483662
				],
				[
					3.8226712795929765,
					1.7483997830873268
				],
				[
					4.704833093131964,
					2.6305503794728673
				],
				[
					5.586950038057263,
					3.806747435602462
				],
				[
					6.469111851596251,
					5.57105984552699
				],
				[
					7.351273665135238,
					7.041314578554014
				],
				[
					7.9393665846232935,
					8.21751163468361
				],
				[
					8.82152839816229,
					9.981824044608143
				],
				[
					9.409621317650345,
					11.746125237379228
				],
				[
					9.997714237138402,
					14.3925882436893
				],
				[
					10.291783131189339,
					16.450947113357845
				],
				[
					10.585852025240156,
					18.803352442770443
				],
				[
					10.585852025240156,
					20.861711312439
				],
				[
					10.291783131189339,
					22.9200589649541
				],
				[
					9.997714237138402,
					24.978417834622647
				],
				[
					9.703690211701284,
					26.448672567649705
				],
				[
					8.82152839816229,
					29.095135573959777
				],
				[
					8.23343547867423,
					30.271332630089383
				],
				[
					7.645342559186061,
					31.741587363116412
				],
				[
					6.763180745647182,
					32.6237491766554
				],
				[
					5.881018932108192,
					33.505899773040916
				],
				[
					4.998857118569201,
					34.38805036942647
				],
				[
					3.8226712795929765,
					35.270200965812045
				],
				[
					2.940509466054096,
					35.85830510245355
				],
				[
					2.0583476525151063,
					36.44640923909503
				],
				[
					1.7643236270778706,
					37.034513375736516
				],
				[
					1.1761858389761162,
					37.32855983548059
				],
				[
					0.8821618135388795,
					37.62260629522461
				],
				[
					0.5880929194880581,
					37.62260629522461
				],
				[
					0.5880929194880581,
					37.916663972122095
				],
				[
					0.5880929194880581,
					37.916663972122095
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.00390625,
				0.1318359375,
				0.248046875,
				0.2978515625,
				0.310546875,
				0.3310546875,
				0.357421875,
				0.3720703125,
				0.3798828125,
				0.3818359375,
				0.3818359375,
				0.3818359375,
				0.3798828125,
				0.3798828125,
				0.3798828125,
				0.37890625,
				0.37890625,
				0.37890625,
				0.380859375,
				0.3798828125,
				0.37890625,
				0.3779296875,
				0.376953125,
				0.37890625,
				0.3818359375,
				0.380859375,
				0.3798828125,
				0.3798828125,
				0.37890625,
				0.3759765625,
				0.37109375,
				0.3583984375,
				0.3330078125,
				0.2998046875,
				0.248046875,
				0.1728515625,
				0.125,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 508,
			"versionNonce": 1116342276,
			"isDeleted": false,
			"id": "399bFz6vS7zSTm3BTnXUL",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1653.3615572829617,
			"y": -106.34263445432941,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 38.22662305870338,
			"height": 17.0549526596831,
			"seed": 18187545,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223436,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					-1.859719048296891
				],
				[
					2.0583476525152196,
					-2.447823184938402
				],
				[
					3.2345334914913364,
					-2.7418808618358548
				],
				[
					3.822671279593089,
					-3.035927321579911
				],
				[
					4.998857118569314,
					-3.6240314582213955
				],
				[
					6.175042957545434,
					-3.6240314582213955
				],
				[
					7.645297690572484,
					-3.6240314582213955
				],
				[
					9.115552423599537,
					-3.6240314582213955
				],
				[
					10.879876050677517,
					-3.329973781323968
				],
				[
					12.64419967775539,
					-3.035927321579911
				],
				[
					14.702547330270596,
					-2.447823184938402
				],
				[
					17.05496387683653,
					-1.859719048296891
				],
				[
					19.407335554788872,
					-0.9775684519113527
				],
				[
					21.759752101354923,
					-0.09541785552578459
				],
				[
					23.5240757284329,
					0.7867327408597535
				],
				[
					26.170516300436066,
					2.5510451507842578
				],
				[
					28.228863952951162,
					3.727242206913854
				],
				[
					29.69911868597823,
					4.903450480196844
				],
				[
					31.46344231305621,
					6.373705213223926
				],
				[
					32.93369704608326,
					7.549902269353494
				],
				[
					34.10988288505936,
					8.726110542636519
				],
				[
					35.28611359264928,
					9.902318815919532
				],
				[
					35.87420651213735,
					10.784469412305079
				],
				[
					36.462299431625425,
					11.37257354894658
				],
				[
					37.05039235111345,
					11.960666468434663
				],
				[
					37.63853013921534,
					12.254724145332116
				],
				[
					37.932554164652466,
					12.842828281973638
				],
				[
					37.932554164652466,
					13.136874741717666
				],
				[
					38.22662305870338,
					13.136874741717666
				],
				[
					38.22662305870338,
					13.430921201461704
				],
				[
					38.22662305870338,
					13.136874741717666
				],
				[
					38.22662305870338,
					13.136874741717666
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0009765625,
				0.1845703125,
				0.2314453125,
				0.265625,
				0.2998046875,
				0.3212890625,
				0.3486328125,
				0.3759765625,
				0.400390625,
				0.4130859375,
				0.421875,
				0.4267578125,
				0.4287109375,
				0.4287109375,
				0.4287109375,
				0.4296875,
				0.4306640625,
				0.431640625,
				0.4306640625,
				0.4306640625,
				0.4296875,
				0.427734375,
				0.427734375,
				0.427734375,
				0.427734375,
				0.4208984375,
				0.4228515625,
				0.4248046875,
				0.4248046875,
				0.296875,
				0.11328125,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 501,
			"versionNonce": 150825532,
			"isDeleted": false,
			"id": "2zY7eoGluxg3URyTht3ic",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1725.4047774902333,
			"y": -93.49980617235553,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.22776594013406,
			"height": 22.347867455149828,
			"seed": 1757656311,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223436,
			"link": null,
			"locked": false,
			"points": [
				[
					-34.4046900680561,
					0
				],
				[
					-34.4046900680561,
					0.2940464597440292
				],
				[
					-34.11066604261899,
					0.2940464597440292
				],
				[
					-34.4046900680561,
					0.2940464597440292
				],
				[
					-34.11066604261899,
					0.2940464597440292
				],
				[
					-34.11066604261899,
					0
				],
				[
					-33.81659714856802,
					0
				],
				[
					-34.11066604261899,
					0.2940464597440292
				],
				[
					-34.4046900680561,
					1.176197056129597
				],
				[
					-34.99282785615795,
					2.0583476525151365
				],
				[
					-35.874944801083124,
					3.5286023855421855
				],
				[
					-37.3451995341102,
					5.292914795466689
				],
				[
					-38.81545426713721,
					6.763169528493736
				],
				[
					-41.75596373319132,
					9.409621317650384
				],
				[
					-44.69647319924543,
					11.467980187318945
				],
				[
					-46.754865720374326,
					12.938234920345995
				],
				[
					-49.69537518642842,
					14.996593790014561
				],
				[
					-52.635884652482495,
					16.466848523041612
				],
				[
					-55.28232522448566,
					17.937103256068653
				],
				[
					-57.6347417710517,
					19.113311529351684
				],
				[
					-59.98715831761771,
					19.995462125737205
				],
				[
					-62.04550597013284,
					20.877612722122773
				],
				[
					-64.10385362264796,
					21.465716858764264
				],
				[
					-65.86817724972597,
					21.759763318508316
				],
				[
					-66.45627016921404,
					22.05382099540578
				],
				[
					-67.04436308870208,
					22.347867455149828
				],
				[
					-67.04436308870208,
					22.347867455149828
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0,
				0.005859375,
				0.1240234375,
				0.1484375,
				0.1552734375,
				0.1591796875,
				0.193359375,
				0.3017578125,
				0.3017578125,
				0.3017578125,
				0.3017578125,
				0.3017578125,
				0.3017578125,
				0.3037109375,
				0.3037109375,
				0.3037109375,
				0.3037109375,
				0.3017578125,
				0.2998046875,
				0.29296875,
				0.275390625,
				0.244140625,
				0.203125,
				0.158203125,
				0.1162109375,
				0.013671875,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 511,
			"versionNonce": 529688452,
			"isDeleted": false,
			"id": "ox9CEEdbXxovKkyjLjc0E",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1653.9496502024508,
			"y": -108.48049855268641,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 10.585852025240156,
			"height": 38.52068073560078,
			"seed": 1043823097,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223436,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					-0.3099590865812296
				],
				[
					0.29406889405082104,
					-0.6040167634786826
				],
				[
					0.5880929194880581,
					-0.6040167634786826
				],
				[
					0.8821618135388795,
					-0.6040167634786826
				],
				[
					1.1761858389761162,
					-0.6040167634786826
				],
				[
					1.470254733027048,
					-0.3099590865812296
				],
				[
					2.0583476525151063,
					-0.015912626837172775
				],
				[
					2.940509466054096,
					0.8662379695483662
				],
				[
					3.8226712795929765,
					1.7483997830873268
				],
				[
					4.704833093131964,
					2.6305503794728673
				],
				[
					5.586950038057263,
					3.806747435602462
				],
				[
					6.469111851596251,
					5.57105984552699
				],
				[
					7.351273665135238,
					7.041314578554014
				],
				[
					7.9393665846232935,
					8.21751163468361
				],
				[
					8.82152839816229,
					9.981824044608143
				],
				[
					9.409621317650345,
					11.746125237379228
				],
				[
					9.997714237138402,
					14.3925882436893
				],
				[
					10.291783131189339,
					16.450947113357845
				],
				[
					10.585852025240156,
					18.803352442770443
				],
				[
					10.585852025240156,
					20.861711312439
				],
				[
					10.291783131189339,
					22.9200589649541
				],
				[
					9.997714237138402,
					24.978417834622647
				],
				[
					9.703690211701284,
					26.448672567649705
				],
				[
					8.82152839816229,
					29.095135573959777
				],
				[
					8.23343547867423,
					30.271332630089383
				],
				[
					7.645342559186061,
					31.741587363116412
				],
				[
					6.763180745647182,
					32.6237491766554
				],
				[
					5.881018932108192,
					33.505899773040916
				],
				[
					4.998857118569201,
					34.38805036942647
				],
				[
					3.8226712795929765,
					35.270200965812045
				],
				[
					2.940509466054096,
					35.85830510245355
				],
				[
					2.0583476525151063,
					36.44640923909503
				],
				[
					1.7643236270778706,
					37.034513375736516
				],
				[
					1.1761858389761162,
					37.32855983548059
				],
				[
					0.8821618135388795,
					37.62260629522461
				],
				[
					0.5880929194880581,
					37.62260629522461
				],
				[
					0.5880929194880581,
					37.916663972122095
				],
				[
					0.5880929194880581,
					37.916663972122095
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.00390625,
				0.1318359375,
				0.248046875,
				0.2978515625,
				0.310546875,
				0.3310546875,
				0.357421875,
				0.3720703125,
				0.3798828125,
				0.3818359375,
				0.3818359375,
				0.3818359375,
				0.3798828125,
				0.3798828125,
				0.3798828125,
				0.37890625,
				0.37890625,
				0.37890625,
				0.380859375,
				0.3798828125,
				0.37890625,
				0.3779296875,
				0.376953125,
				0.37890625,
				0.3818359375,
				0.380859375,
				0.3798828125,
				0.3798828125,
				0.37890625,
				0.3759765625,
				0.37109375,
				0.3583984375,
				0.3330078125,
				0.2998046875,
				0.248046875,
				0.1728515625,
				0.125,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 548,
			"versionNonce": 650953404,
			"isDeleted": false,
			"id": "sRxjGOjdCJE4avQAcKOkH",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1653.9971254016605,
			"y": -57.9364871229177,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 38.22662305870338,
			"height": 17.0549526596831,
			"seed": 2123365911,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223436,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					-1.859719048296891
				],
				[
					2.0583476525152196,
					-2.447823184938402
				],
				[
					3.2345334914913364,
					-2.7418808618358548
				],
				[
					3.822671279593089,
					-3.035927321579911
				],
				[
					4.998857118569314,
					-3.6240314582213955
				],
				[
					6.175042957545434,
					-3.6240314582213955
				],
				[
					7.645297690572484,
					-3.6240314582213955
				],
				[
					9.115552423599537,
					-3.6240314582213955
				],
				[
					10.879876050677517,
					-3.329973781323968
				],
				[
					12.64419967775539,
					-3.035927321579911
				],
				[
					14.702547330270596,
					-2.447823184938402
				],
				[
					17.05496387683653,
					-1.859719048296891
				],
				[
					19.407335554788872,
					-0.9775684519113527
				],
				[
					21.759752101354923,
					-0.09541785552578459
				],
				[
					23.5240757284329,
					0.7867327408597535
				],
				[
					26.170516300436066,
					2.5510451507842578
				],
				[
					28.228863952951162,
					3.727242206913854
				],
				[
					29.69911868597823,
					4.903450480196844
				],
				[
					31.46344231305621,
					6.373705213223926
				],
				[
					32.93369704608326,
					7.549902269353494
				],
				[
					34.10988288505936,
					8.726110542636519
				],
				[
					35.28611359264928,
					9.902318815919532
				],
				[
					35.87420651213735,
					10.784469412305079
				],
				[
					36.462299431625425,
					11.37257354894658
				],
				[
					37.05039235111345,
					11.960666468434663
				],
				[
					37.63853013921534,
					12.254724145332116
				],
				[
					37.932554164652466,
					12.842828281973638
				],
				[
					37.932554164652466,
					13.136874741717666
				],
				[
					38.22662305870338,
					13.136874741717666
				],
				[
					38.22662305870338,
					13.430921201461704
				],
				[
					38.22662305870338,
					13.136874741717666
				],
				[
					38.22662305870338,
					13.136874741717666
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0009765625,
				0.1845703125,
				0.2314453125,
				0.265625,
				0.2998046875,
				0.3212890625,
				0.3486328125,
				0.3759765625,
				0.400390625,
				0.4130859375,
				0.421875,
				0.4267578125,
				0.4287109375,
				0.4287109375,
				0.4287109375,
				0.4296875,
				0.4306640625,
				0.431640625,
				0.4306640625,
				0.4306640625,
				0.4296875,
				0.427734375,
				0.427734375,
				0.427734375,
				0.427734375,
				0.4208984375,
				0.4228515625,
				0.4248046875,
				0.4248046875,
				0.296875,
				0.11328125,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 540,
			"versionNonce": 191026948,
			"isDeleted": false,
			"id": "iN7g-2oSoEtJ505FUmIf0",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1726.0403456089302,
			"y": -45.093658840943704,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.22776594013406,
			"height": 22.347867455149828,
			"seed": 1896338137,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223436,
			"link": null,
			"locked": false,
			"points": [
				[
					-34.4046900680561,
					0
				],
				[
					-34.4046900680561,
					0.2940464597440292
				],
				[
					-34.11066604261899,
					0.2940464597440292
				],
				[
					-34.4046900680561,
					0.2940464597440292
				],
				[
					-34.11066604261899,
					0.2940464597440292
				],
				[
					-34.11066604261899,
					0
				],
				[
					-33.81659714856802,
					0
				],
				[
					-34.11066604261899,
					0.2940464597440292
				],
				[
					-34.4046900680561,
					1.176197056129597
				],
				[
					-34.99282785615795,
					2.0583476525151365
				],
				[
					-35.874944801083124,
					3.5286023855421855
				],
				[
					-37.3451995341102,
					5.292914795466689
				],
				[
					-38.81545426713721,
					6.763169528493736
				],
				[
					-41.75596373319132,
					9.409621317650384
				],
				[
					-44.69647319924543,
					11.467980187318945
				],
				[
					-46.754865720374326,
					12.938234920345995
				],
				[
					-49.69537518642842,
					14.996593790014561
				],
				[
					-52.635884652482495,
					16.466848523041612
				],
				[
					-55.28232522448566,
					17.937103256068653
				],
				[
					-57.6347417710517,
					19.113311529351684
				],
				[
					-59.98715831761771,
					19.995462125737205
				],
				[
					-62.04550597013284,
					20.877612722122773
				],
				[
					-64.10385362264796,
					21.465716858764264
				],
				[
					-65.86817724972597,
					21.759763318508316
				],
				[
					-66.45627016921404,
					22.05382099540578
				],
				[
					-67.04436308870208,
					22.347867455149828
				],
				[
					-67.04436308870208,
					22.347867455149828
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0,
				0.005859375,
				0.1240234375,
				0.1484375,
				0.1552734375,
				0.1591796875,
				0.193359375,
				0.3017578125,
				0.3017578125,
				0.3017578125,
				0.3017578125,
				0.3017578125,
				0.3017578125,
				0.3037109375,
				0.3037109375,
				0.3037109375,
				0.3037109375,
				0.3017578125,
				0.2998046875,
				0.29296875,
				0.275390625,
				0.244140625,
				0.203125,
				0.158203125,
				0.1162109375,
				0.013671875,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 552,
			"versionNonce": 1914506044,
			"isDeleted": false,
			"id": "LsIOHL8jC9JNo9c7QzzmP",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1654.5852183211477,
			"y": -60.07435122127458,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 10.585852025240156,
			"height": 38.52068073560078,
			"seed": 1647715127,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223436,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					-0.3099590865812296
				],
				[
					0.29406889405082104,
					-0.6040167634786826
				],
				[
					0.5880929194880581,
					-0.6040167634786826
				],
				[
					0.8821618135388795,
					-0.6040167634786826
				],
				[
					1.1761858389761162,
					-0.6040167634786826
				],
				[
					1.470254733027048,
					-0.3099590865812296
				],
				[
					2.0583476525151063,
					-0.015912626837172775
				],
				[
					2.940509466054096,
					0.8662379695483662
				],
				[
					3.8226712795929765,
					1.7483997830873268
				],
				[
					4.704833093131964,
					2.6305503794728673
				],
				[
					5.586950038057263,
					3.806747435602462
				],
				[
					6.469111851596251,
					5.57105984552699
				],
				[
					7.351273665135238,
					7.041314578554014
				],
				[
					7.9393665846232935,
					8.21751163468361
				],
				[
					8.82152839816229,
					9.981824044608143
				],
				[
					9.409621317650345,
					11.746125237379228
				],
				[
					9.997714237138402,
					14.3925882436893
				],
				[
					10.291783131189339,
					16.450947113357845
				],
				[
					10.585852025240156,
					18.803352442770443
				],
				[
					10.585852025240156,
					20.861711312439
				],
				[
					10.291783131189339,
					22.9200589649541
				],
				[
					9.997714237138402,
					24.978417834622647
				],
				[
					9.703690211701284,
					26.448672567649705
				],
				[
					8.82152839816229,
					29.095135573959777
				],
				[
					8.23343547867423,
					30.271332630089383
				],
				[
					7.645342559186061,
					31.741587363116412
				],
				[
					6.763180745647182,
					32.6237491766554
				],
				[
					5.881018932108192,
					33.505899773040916
				],
				[
					4.998857118569201,
					34.38805036942647
				],
				[
					3.8226712795929765,
					35.270200965812045
				],
				[
					2.940509466054096,
					35.85830510245355
				],
				[
					2.0583476525151063,
					36.44640923909503
				],
				[
					1.7643236270778706,
					37.034513375736516
				],
				[
					1.1761858389761162,
					37.32855983548059
				],
				[
					0.8821618135388795,
					37.62260629522461
				],
				[
					0.5880929194880581,
					37.62260629522461
				],
				[
					0.5880929194880581,
					37.916663972122095
				],
				[
					0.5880929194880581,
					37.916663972122095
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.00390625,
				0.1318359375,
				0.248046875,
				0.2978515625,
				0.310546875,
				0.3310546875,
				0.357421875,
				0.3720703125,
				0.3798828125,
				0.3818359375,
				0.3818359375,
				0.3818359375,
				0.3798828125,
				0.3798828125,
				0.3798828125,
				0.37890625,
				0.37890625,
				0.37890625,
				0.380859375,
				0.3798828125,
				0.37890625,
				0.3779296875,
				0.376953125,
				0.37890625,
				0.3818359375,
				0.380859375,
				0.3798828125,
				0.3798828125,
				0.37890625,
				0.3759765625,
				0.37109375,
				0.3583984375,
				0.3330078125,
				0.2998046875,
				0.248046875,
				0.1728515625,
				0.125,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 551,
			"versionNonce": 309941892,
			"isDeleted": false,
			"id": "sfExAY9NM2eAx4bgq7p2_",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1655.6918444194148,
			"y": -9.318475670766134,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 38.22662305870338,
			"height": 17.0549526596831,
			"seed": 56145527,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223436,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					-1.859719048296891
				],
				[
					2.0583476525152196,
					-2.447823184938402
				],
				[
					3.2345334914913364,
					-2.7418808618358548
				],
				[
					3.822671279593089,
					-3.035927321579911
				],
				[
					4.998857118569314,
					-3.6240314582213955
				],
				[
					6.175042957545434,
					-3.6240314582213955
				],
				[
					7.645297690572484,
					-3.6240314582213955
				],
				[
					9.115552423599537,
					-3.6240314582213955
				],
				[
					10.879876050677517,
					-3.329973781323968
				],
				[
					12.64419967775539,
					-3.035927321579911
				],
				[
					14.702547330270596,
					-2.447823184938402
				],
				[
					17.05496387683653,
					-1.859719048296891
				],
				[
					19.407335554788872,
					-0.9775684519113527
				],
				[
					21.759752101354923,
					-0.09541785552578459
				],
				[
					23.5240757284329,
					0.7867327408597535
				],
				[
					26.170516300436066,
					2.5510451507842578
				],
				[
					28.228863952951162,
					3.727242206913854
				],
				[
					29.69911868597823,
					4.903450480196844
				],
				[
					31.46344231305621,
					6.373705213223926
				],
				[
					32.93369704608326,
					7.549902269353494
				],
				[
					34.10988288505936,
					8.726110542636519
				],
				[
					35.28611359264928,
					9.902318815919532
				],
				[
					35.87420651213735,
					10.784469412305079
				],
				[
					36.462299431625425,
					11.37257354894658
				],
				[
					37.05039235111345,
					11.960666468434663
				],
				[
					37.63853013921534,
					12.254724145332116
				],
				[
					37.932554164652466,
					12.842828281973638
				],
				[
					37.932554164652466,
					13.136874741717666
				],
				[
					38.22662305870338,
					13.136874741717666
				],
				[
					38.22662305870338,
					13.430921201461704
				],
				[
					38.22662305870338,
					13.136874741717666
				],
				[
					38.22662305870338,
					13.136874741717666
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0009765625,
				0.1845703125,
				0.2314453125,
				0.265625,
				0.2998046875,
				0.3212890625,
				0.3486328125,
				0.3759765625,
				0.400390625,
				0.4130859375,
				0.421875,
				0.4267578125,
				0.4287109375,
				0.4287109375,
				0.4287109375,
				0.4296875,
				0.4306640625,
				0.431640625,
				0.4306640625,
				0.4306640625,
				0.4296875,
				0.427734375,
				0.427734375,
				0.427734375,
				0.427734375,
				0.4208984375,
				0.4228515625,
				0.4248046875,
				0.4248046875,
				0.296875,
				0.11328125,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 544,
			"versionNonce": 1833976764,
			"isDeleted": false,
			"id": "4rpy1CEeskNUSUuGj3d2P",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1727.7350646266864,
			"y": 3.5243526112071777,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.22776594013406,
			"height": 22.347867455149828,
			"seed": 76370041,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223436,
			"link": null,
			"locked": false,
			"points": [
				[
					-34.4046900680561,
					0
				],
				[
					-34.4046900680561,
					0.2940464597440292
				],
				[
					-34.11066604261899,
					0.2940464597440292
				],
				[
					-34.4046900680561,
					0.2940464597440292
				],
				[
					-34.11066604261899,
					0.2940464597440292
				],
				[
					-34.11066604261899,
					0
				],
				[
					-33.81659714856802,
					0
				],
				[
					-34.11066604261899,
					0.2940464597440292
				],
				[
					-34.4046900680561,
					1.176197056129597
				],
				[
					-34.99282785615795,
					2.0583476525151365
				],
				[
					-35.874944801083124,
					3.5286023855421855
				],
				[
					-37.3451995341102,
					5.292914795466689
				],
				[
					-38.81545426713721,
					6.763169528493736
				],
				[
					-41.75596373319132,
					9.409621317650384
				],
				[
					-44.69647319924543,
					11.467980187318945
				],
				[
					-46.754865720374326,
					12.938234920345995
				],
				[
					-49.69537518642842,
					14.996593790014561
				],
				[
					-52.635884652482495,
					16.466848523041612
				],
				[
					-55.28232522448566,
					17.937103256068653
				],
				[
					-57.6347417710517,
					19.113311529351684
				],
				[
					-59.98715831761771,
					19.995462125737205
				],
				[
					-62.04550597013284,
					20.877612722122773
				],
				[
					-64.10385362264796,
					21.465716858764264
				],
				[
					-65.86817724972597,
					21.759763318508316
				],
				[
					-66.45627016921404,
					22.05382099540578
				],
				[
					-67.04436308870208,
					22.347867455149828
				],
				[
					-67.04436308870208,
					22.347867455149828
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0,
				0.005859375,
				0.1240234375,
				0.1484375,
				0.1552734375,
				0.1591796875,
				0.193359375,
				0.3017578125,
				0.3017578125,
				0.3017578125,
				0.3017578125,
				0.3017578125,
				0.3017578125,
				0.3037109375,
				0.3037109375,
				0.3037109375,
				0.3037109375,
				0.3017578125,
				0.2998046875,
				0.29296875,
				0.275390625,
				0.244140625,
				0.203125,
				0.158203125,
				0.1162109375,
				0.013671875,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 556,
			"versionNonce": 26469892,
			"isDeleted": false,
			"id": "g_ZipRUYmQlYvxqr9lKVl",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1656.279937338902,
			"y": -11.456339769123588,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 10.585852025240156,
			"height": 38.52068073560078,
			"seed": 1376309143,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223436,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					-0.3099590865812296
				],
				[
					0.29406889405082104,
					-0.6040167634786826
				],
				[
					0.5880929194880581,
					-0.6040167634786826
				],
				[
					0.8821618135388795,
					-0.6040167634786826
				],
				[
					1.1761858389761162,
					-0.6040167634786826
				],
				[
					1.470254733027048,
					-0.3099590865812296
				],
				[
					2.0583476525151063,
					-0.015912626837172775
				],
				[
					2.940509466054096,
					0.8662379695483662
				],
				[
					3.8226712795929765,
					1.7483997830873268
				],
				[
					4.704833093131964,
					2.6305503794728673
				],
				[
					5.586950038057263,
					3.806747435602462
				],
				[
					6.469111851596251,
					5.57105984552699
				],
				[
					7.351273665135238,
					7.041314578554014
				],
				[
					7.9393665846232935,
					8.21751163468361
				],
				[
					8.82152839816229,
					9.981824044608143
				],
				[
					9.409621317650345,
					11.746125237379228
				],
				[
					9.997714237138402,
					14.3925882436893
				],
				[
					10.291783131189339,
					16.450947113357845
				],
				[
					10.585852025240156,
					18.803352442770443
				],
				[
					10.585852025240156,
					20.861711312439
				],
				[
					10.291783131189339,
					22.9200589649541
				],
				[
					9.997714237138402,
					24.978417834622647
				],
				[
					9.703690211701284,
					26.448672567649705
				],
				[
					8.82152839816229,
					29.095135573959777
				],
				[
					8.23343547867423,
					30.271332630089383
				],
				[
					7.645342559186061,
					31.741587363116412
				],
				[
					6.763180745647182,
					32.6237491766554
				],
				[
					5.881018932108192,
					33.505899773040916
				],
				[
					4.998857118569201,
					34.38805036942647
				],
				[
					3.8226712795929765,
					35.270200965812045
				],
				[
					2.940509466054096,
					35.85830510245355
				],
				[
					2.0583476525151063,
					36.44640923909503
				],
				[
					1.7643236270778706,
					37.034513375736516
				],
				[
					1.1761858389761162,
					37.32855983548059
				],
				[
					0.8821618135388795,
					37.62260629522461
				],
				[
					0.5880929194880581,
					37.62260629522461
				],
				[
					0.5880929194880581,
					37.916663972122095
				],
				[
					0.5880929194880581,
					37.916663972122095
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.00390625,
				0.1318359375,
				0.248046875,
				0.2978515625,
				0.310546875,
				0.3310546875,
				0.357421875,
				0.3720703125,
				0.3798828125,
				0.3818359375,
				0.3818359375,
				0.3818359375,
				0.3798828125,
				0.3798828125,
				0.3798828125,
				0.37890625,
				0.37890625,
				0.37890625,
				0.380859375,
				0.3798828125,
				0.37890625,
				0.3779296875,
				0.376953125,
				0.37890625,
				0.3818359375,
				0.380859375,
				0.3798828125,
				0.3798828125,
				0.37890625,
				0.3759765625,
				0.37109375,
				0.3583984375,
				0.3330078125,
				0.2998046875,
				0.248046875,
				0.1728515625,
				0.125,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 595,
			"versionNonce": 2122869820,
			"isDeleted": false,
			"id": "llaV_1iQ0xlr9PCKYFiOC",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1657.7518438032707,
			"y": 38.50512007946577,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 38.22662305870338,
			"height": 17.0549526596831,
			"seed": 1643176567,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223436,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					-1.859719048296891
				],
				[
					2.0583476525152196,
					-2.447823184938402
				],
				[
					3.2345334914913364,
					-2.7418808618358548
				],
				[
					3.822671279593089,
					-3.035927321579911
				],
				[
					4.998857118569314,
					-3.6240314582213955
				],
				[
					6.175042957545434,
					-3.6240314582213955
				],
				[
					7.645297690572484,
					-3.6240314582213955
				],
				[
					9.115552423599537,
					-3.6240314582213955
				],
				[
					10.879876050677517,
					-3.329973781323968
				],
				[
					12.64419967775539,
					-3.035927321579911
				],
				[
					14.702547330270596,
					-2.447823184938402
				],
				[
					17.05496387683653,
					-1.859719048296891
				],
				[
					19.407335554788872,
					-0.9775684519113527
				],
				[
					21.759752101354923,
					-0.09541785552578459
				],
				[
					23.5240757284329,
					0.7867327408597535
				],
				[
					26.170516300436066,
					2.5510451507842578
				],
				[
					28.228863952951162,
					3.727242206913854
				],
				[
					29.69911868597823,
					4.903450480196844
				],
				[
					31.46344231305621,
					6.373705213223926
				],
				[
					32.93369704608326,
					7.549902269353494
				],
				[
					34.10988288505936,
					8.726110542636519
				],
				[
					35.28611359264928,
					9.902318815919532
				],
				[
					35.87420651213735,
					10.784469412305079
				],
				[
					36.462299431625425,
					11.37257354894658
				],
				[
					37.05039235111345,
					11.960666468434663
				],
				[
					37.63853013921534,
					12.254724145332116
				],
				[
					37.932554164652466,
					12.842828281973638
				],
				[
					37.932554164652466,
					13.136874741717666
				],
				[
					38.22662305870338,
					13.136874741717666
				],
				[
					38.22662305870338,
					13.430921201461704
				],
				[
					38.22662305870338,
					13.136874741717666
				],
				[
					38.22662305870338,
					13.136874741717666
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0009765625,
				0.1845703125,
				0.2314453125,
				0.265625,
				0.2998046875,
				0.3212890625,
				0.3486328125,
				0.3759765625,
				0.400390625,
				0.4130859375,
				0.421875,
				0.4267578125,
				0.4287109375,
				0.4287109375,
				0.4287109375,
				0.4296875,
				0.4306640625,
				0.431640625,
				0.4306640625,
				0.4306640625,
				0.4296875,
				0.427734375,
				0.427734375,
				0.427734375,
				0.427734375,
				0.4208984375,
				0.4228515625,
				0.4248046875,
				0.4248046875,
				0.296875,
				0.11328125,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 590,
			"versionNonce": 1571849604,
			"isDeleted": false,
			"id": "Gk_V0QjgxetOjNjUiEaUt",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1729.7950640105387,
			"y": 51.34794836143942,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.22776594013406,
			"height": 22.347867455149828,
			"seed": 467526777,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223436,
			"link": null,
			"locked": false,
			"points": [
				[
					-34.4046900680561,
					0
				],
				[
					-34.4046900680561,
					0.2940464597440292
				],
				[
					-34.11066604261899,
					0.2940464597440292
				],
				[
					-34.4046900680561,
					0.2940464597440292
				],
				[
					-34.11066604261899,
					0.2940464597440292
				],
				[
					-34.11066604261899,
					0
				],
				[
					-33.81659714856802,
					0
				],
				[
					-34.11066604261899,
					0.2940464597440292
				],
				[
					-34.4046900680561,
					1.176197056129597
				],
				[
					-34.99282785615795,
					2.0583476525151365
				],
				[
					-35.874944801083124,
					3.5286023855421855
				],
				[
					-37.3451995341102,
					5.292914795466689
				],
				[
					-38.81545426713721,
					6.763169528493736
				],
				[
					-41.75596373319132,
					9.409621317650384
				],
				[
					-44.69647319924543,
					11.467980187318945
				],
				[
					-46.754865720374326,
					12.938234920345995
				],
				[
					-49.69537518642842,
					14.996593790014561
				],
				[
					-52.635884652482495,
					16.466848523041612
				],
				[
					-55.28232522448566,
					17.937103256068653
				],
				[
					-57.6347417710517,
					19.113311529351684
				],
				[
					-59.98715831761771,
					19.995462125737205
				],
				[
					-62.04550597013284,
					20.877612722122773
				],
				[
					-64.10385362264796,
					21.465716858764264
				],
				[
					-65.86817724972597,
					21.759763318508316
				],
				[
					-66.45627016921404,
					22.05382099540578
				],
				[
					-67.04436308870208,
					22.347867455149828
				],
				[
					-67.04436308870208,
					22.347867455149828
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0,
				0.005859375,
				0.1240234375,
				0.1484375,
				0.1552734375,
				0.1591796875,
				0.193359375,
				0.3017578125,
				0.3017578125,
				0.3017578125,
				0.3017578125,
				0.3017578125,
				0.3017578125,
				0.3037109375,
				0.3037109375,
				0.3037109375,
				0.3037109375,
				0.3017578125,
				0.2998046875,
				0.29296875,
				0.275390625,
				0.244140625,
				0.203125,
				0.158203125,
				0.1162109375,
				0.013671875,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 600,
			"versionNonce": 2007467196,
			"isDeleted": false,
			"id": "64BSvCYEXvhzs_1kmlFNP",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1658.339936722758,
			"y": 36.367255981108315,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 10.585852025240156,
			"height": 38.52068073560078,
			"seed": 79395735,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223436,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					-0.3099590865812296
				],
				[
					0.29406889405082104,
					-0.6040167634786826
				],
				[
					0.5880929194880581,
					-0.6040167634786826
				],
				[
					0.8821618135388795,
					-0.6040167634786826
				],
				[
					1.1761858389761162,
					-0.6040167634786826
				],
				[
					1.470254733027048,
					-0.3099590865812296
				],
				[
					2.0583476525151063,
					-0.015912626837172775
				],
				[
					2.940509466054096,
					0.8662379695483662
				],
				[
					3.8226712795929765,
					1.7483997830873268
				],
				[
					4.704833093131964,
					2.6305503794728673
				],
				[
					5.586950038057263,
					3.806747435602462
				],
				[
					6.469111851596251,
					5.57105984552699
				],
				[
					7.351273665135238,
					7.041314578554014
				],
				[
					7.9393665846232935,
					8.21751163468361
				],
				[
					8.82152839816229,
					9.981824044608143
				],
				[
					9.409621317650345,
					11.746125237379228
				],
				[
					9.997714237138402,
					14.3925882436893
				],
				[
					10.291783131189339,
					16.450947113357845
				],
				[
					10.585852025240156,
					18.803352442770443
				],
				[
					10.585852025240156,
					20.861711312439
				],
				[
					10.291783131189339,
					22.9200589649541
				],
				[
					9.997714237138402,
					24.978417834622647
				],
				[
					9.703690211701284,
					26.448672567649705
				],
				[
					8.82152839816229,
					29.095135573959777
				],
				[
					8.23343547867423,
					30.271332630089383
				],
				[
					7.645342559186061,
					31.741587363116412
				],
				[
					6.763180745647182,
					32.6237491766554
				],
				[
					5.881018932108192,
					33.505899773040916
				],
				[
					4.998857118569201,
					34.38805036942647
				],
				[
					3.8226712795929765,
					35.270200965812045
				],
				[
					2.940509466054096,
					35.85830510245355
				],
				[
					2.0583476525151063,
					36.44640923909503
				],
				[
					1.7643236270778706,
					37.034513375736516
				],
				[
					1.1761858389761162,
					37.32855983548059
				],
				[
					0.8821618135388795,
					37.62260629522461
				],
				[
					0.5880929194880581,
					37.62260629522461
				],
				[
					0.5880929194880581,
					37.916663972122095
				],
				[
					0.5880929194880581,
					37.916663972122095
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.00390625,
				0.1318359375,
				0.248046875,
				0.2978515625,
				0.310546875,
				0.3310546875,
				0.357421875,
				0.3720703125,
				0.3798828125,
				0.3818359375,
				0.3818359375,
				0.3818359375,
				0.3798828125,
				0.3798828125,
				0.3798828125,
				0.37890625,
				0.37890625,
				0.37890625,
				0.380859375,
				0.3798828125,
				0.37890625,
				0.3779296875,
				0.376953125,
				0.37890625,
				0.3818359375,
				0.380859375,
				0.3798828125,
				0.3798828125,
				0.37890625,
				0.3759765625,
				0.37109375,
				0.3583984375,
				0.3330078125,
				0.2998046875,
				0.248046875,
				0.1728515625,
				0.125,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 600,
			"versionNonce": 1544369412,
			"isDeleted": false,
			"id": "LSuYfRIvip_eJ1IE6yx8Y",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1657.174804371683,
			"y": 88.60600259097964,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 38.22662305870338,
			"height": 17.0549526596831,
			"seed": 1400696153,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223436,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					-1.859719048296891
				],
				[
					2.0583476525152196,
					-2.447823184938402
				],
				[
					3.2345334914913364,
					-2.7418808618358548
				],
				[
					3.822671279593089,
					-3.035927321579911
				],
				[
					4.998857118569314,
					-3.6240314582213955
				],
				[
					6.175042957545434,
					-3.6240314582213955
				],
				[
					7.645297690572484,
					-3.6240314582213955
				],
				[
					9.115552423599537,
					-3.6240314582213955
				],
				[
					10.879876050677517,
					-3.329973781323968
				],
				[
					12.64419967775539,
					-3.035927321579911
				],
				[
					14.702547330270596,
					-2.447823184938402
				],
				[
					17.05496387683653,
					-1.859719048296891
				],
				[
					19.407335554788872,
					-0.9775684519113527
				],
				[
					21.759752101354923,
					-0.09541785552578459
				],
				[
					23.5240757284329,
					0.7867327408597535
				],
				[
					26.170516300436066,
					2.5510451507842578
				],
				[
					28.228863952951162,
					3.727242206913854
				],
				[
					29.69911868597823,
					4.903450480196844
				],
				[
					31.46344231305621,
					6.373705213223926
				],
				[
					32.93369704608326,
					7.549902269353494
				],
				[
					34.10988288505936,
					8.726110542636519
				],
				[
					35.28611359264928,
					9.902318815919532
				],
				[
					35.87420651213735,
					10.784469412305079
				],
				[
					36.462299431625425,
					11.37257354894658
				],
				[
					37.05039235111345,
					11.960666468434663
				],
				[
					37.63853013921534,
					12.254724145332116
				],
				[
					37.932554164652466,
					12.842828281973638
				],
				[
					37.932554164652466,
					13.136874741717666
				],
				[
					38.22662305870338,
					13.136874741717666
				],
				[
					38.22662305870338,
					13.430921201461704
				],
				[
					38.22662305870338,
					13.136874741717666
				],
				[
					38.22662305870338,
					13.136874741717666
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0009765625,
				0.1845703125,
				0.2314453125,
				0.265625,
				0.2998046875,
				0.3212890625,
				0.3486328125,
				0.3759765625,
				0.400390625,
				0.4130859375,
				0.421875,
				0.4267578125,
				0.4287109375,
				0.4287109375,
				0.4287109375,
				0.4296875,
				0.4306640625,
				0.431640625,
				0.4306640625,
				0.4306640625,
				0.4296875,
				0.427734375,
				0.427734375,
				0.427734375,
				0.427734375,
				0.4208984375,
				0.4228515625,
				0.4248046875,
				0.4248046875,
				0.296875,
				0.11328125,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 594,
			"versionNonce": 508529980,
			"isDeleted": false,
			"id": "4Jq3LFne2i7GqFJpT3uuR",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1729.2180245789582,
			"y": 101.4488308729533,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.22776594013406,
			"height": 22.347867455149828,
			"seed": 1628827831,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223436,
			"link": null,
			"locked": false,
			"points": [
				[
					-34.4046900680561,
					0
				],
				[
					-34.4046900680561,
					0.2940464597440292
				],
				[
					-34.11066604261899,
					0.2940464597440292
				],
				[
					-34.4046900680561,
					0.2940464597440292
				],
				[
					-34.11066604261899,
					0.2940464597440292
				],
				[
					-34.11066604261899,
					0
				],
				[
					-33.81659714856802,
					0
				],
				[
					-34.11066604261899,
					0.2940464597440292
				],
				[
					-34.4046900680561,
					1.176197056129597
				],
				[
					-34.99282785615795,
					2.0583476525151365
				],
				[
					-35.874944801083124,
					3.5286023855421855
				],
				[
					-37.3451995341102,
					5.292914795466689
				],
				[
					-38.81545426713721,
					6.763169528493736
				],
				[
					-41.75596373319132,
					9.409621317650384
				],
				[
					-44.69647319924543,
					11.467980187318945
				],
				[
					-46.754865720374326,
					12.938234920345995
				],
				[
					-49.69537518642842,
					14.996593790014561
				],
				[
					-52.635884652482495,
					16.466848523041612
				],
				[
					-55.28232522448566,
					17.937103256068653
				],
				[
					-57.6347417710517,
					19.113311529351684
				],
				[
					-59.98715831761771,
					19.995462125737205
				],
				[
					-62.04550597013284,
					20.877612722122773
				],
				[
					-64.10385362264796,
					21.465716858764264
				],
				[
					-65.86817724972597,
					21.759763318508316
				],
				[
					-66.45627016921404,
					22.05382099540578
				],
				[
					-67.04436308870208,
					22.347867455149828
				],
				[
					-67.04436308870208,
					22.347867455149828
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0,
				0.005859375,
				0.1240234375,
				0.1484375,
				0.1552734375,
				0.1591796875,
				0.193359375,
				0.3017578125,
				0.3017578125,
				0.3017578125,
				0.3017578125,
				0.3017578125,
				0.3017578125,
				0.3037109375,
				0.3037109375,
				0.3037109375,
				0.3037109375,
				0.3017578125,
				0.2998046875,
				0.29296875,
				0.275390625,
				0.244140625,
				0.203125,
				0.158203125,
				0.1162109375,
				0.013671875,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 604,
			"versionNonce": 1512567940,
			"isDeleted": false,
			"id": "ZxvkJqN3XTXTbqC7EpmFM",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1657.762897291172,
			"y": 86.46813849262242,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 10.585852025240156,
			"height": 38.52068073560078,
			"seed": 1476909625,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223436,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					-0.3099590865812296
				],
				[
					0.29406889405082104,
					-0.6040167634786826
				],
				[
					0.5880929194880581,
					-0.6040167634786826
				],
				[
					0.8821618135388795,
					-0.6040167634786826
				],
				[
					1.1761858389761162,
					-0.6040167634786826
				],
				[
					1.470254733027048,
					-0.3099590865812296
				],
				[
					2.0583476525151063,
					-0.015912626837172775
				],
				[
					2.940509466054096,
					0.8662379695483662
				],
				[
					3.8226712795929765,
					1.7483997830873268
				],
				[
					4.704833093131964,
					2.6305503794728673
				],
				[
					5.586950038057263,
					3.806747435602462
				],
				[
					6.469111851596251,
					5.57105984552699
				],
				[
					7.351273665135238,
					7.041314578554014
				],
				[
					7.9393665846232935,
					8.21751163468361
				],
				[
					8.82152839816229,
					9.981824044608143
				],
				[
					9.409621317650345,
					11.746125237379228
				],
				[
					9.997714237138402,
					14.3925882436893
				],
				[
					10.291783131189339,
					16.450947113357845
				],
				[
					10.585852025240156,
					18.803352442770443
				],
				[
					10.585852025240156,
					20.861711312439
				],
				[
					10.291783131189339,
					22.9200589649541
				],
				[
					9.997714237138402,
					24.978417834622647
				],
				[
					9.703690211701284,
					26.448672567649705
				],
				[
					8.82152839816229,
					29.095135573959777
				],
				[
					8.23343547867423,
					30.271332630089383
				],
				[
					7.645342559186061,
					31.741587363116412
				],
				[
					6.763180745647182,
					32.6237491766554
				],
				[
					5.881018932108192,
					33.505899773040916
				],
				[
					4.998857118569201,
					34.38805036942647
				],
				[
					3.8226712795929765,
					35.270200965812045
				],
				[
					2.940509466054096,
					35.85830510245355
				],
				[
					2.0583476525151063,
					36.44640923909503
				],
				[
					1.7643236270778706,
					37.034513375736516
				],
				[
					1.1761858389761162,
					37.32855983548059
				],
				[
					0.8821618135388795,
					37.62260629522461
				],
				[
					0.5880929194880581,
					37.62260629522461
				],
				[
					0.5880929194880581,
					37.916663972122095
				],
				[
					0.5880929194880581,
					37.916663972122095
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.00390625,
				0.1318359375,
				0.248046875,
				0.2978515625,
				0.310546875,
				0.3310546875,
				0.357421875,
				0.3720703125,
				0.3798828125,
				0.3818359375,
				0.3818359375,
				0.3818359375,
				0.3798828125,
				0.3798828125,
				0.3798828125,
				0.37890625,
				0.37890625,
				0.37890625,
				0.380859375,
				0.3798828125,
				0.37890625,
				0.3779296875,
				0.376953125,
				0.37890625,
				0.3818359375,
				0.380859375,
				0.3798828125,
				0.3798828125,
				0.37890625,
				0.3759765625,
				0.37109375,
				0.3583984375,
				0.3330078125,
				0.2998046875,
				0.248046875,
				0.1728515625,
				0.125,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 638,
			"versionNonce": 870483388,
			"isDeleted": false,
			"id": "tGi5lLC8C8amfeT4dJsqA",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1657.8103724903826,
			"y": 137.01214992239147,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 38.22662305870338,
			"height": 17.0549526596831,
			"seed": 1889845719,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223436,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					-1.859719048296891
				],
				[
					2.0583476525152196,
					-2.447823184938402
				],
				[
					3.2345334914913364,
					-2.7418808618358548
				],
				[
					3.822671279593089,
					-3.035927321579911
				],
				[
					4.998857118569314,
					-3.6240314582213955
				],
				[
					6.175042957545434,
					-3.6240314582213955
				],
				[
					7.645297690572484,
					-3.6240314582213955
				],
				[
					9.115552423599537,
					-3.6240314582213955
				],
				[
					10.879876050677517,
					-3.329973781323968
				],
				[
					12.64419967775539,
					-3.035927321579911
				],
				[
					14.702547330270596,
					-2.447823184938402
				],
				[
					17.05496387683653,
					-1.859719048296891
				],
				[
					19.407335554788872,
					-0.9775684519113527
				],
				[
					21.759752101354923,
					-0.09541785552578459
				],
				[
					23.5240757284329,
					0.7867327408597535
				],
				[
					26.170516300436066,
					2.5510451507842578
				],
				[
					28.228863952951162,
					3.727242206913854
				],
				[
					29.69911868597823,
					4.903450480196844
				],
				[
					31.46344231305621,
					6.373705213223926
				],
				[
					32.93369704608326,
					7.549902269353494
				],
				[
					34.10988288505936,
					8.726110542636519
				],
				[
					35.28611359264928,
					9.902318815919532
				],
				[
					35.87420651213735,
					10.784469412305079
				],
				[
					36.462299431625425,
					11.37257354894658
				],
				[
					37.05039235111345,
					11.960666468434663
				],
				[
					37.63853013921534,
					12.254724145332116
				],
				[
					37.932554164652466,
					12.842828281973638
				],
				[
					37.932554164652466,
					13.136874741717666
				],
				[
					38.22662305870338,
					13.136874741717666
				],
				[
					38.22662305870338,
					13.430921201461704
				],
				[
					38.22662305870338,
					13.136874741717666
				],
				[
					38.22662305870338,
					13.136874741717666
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0009765625,
				0.1845703125,
				0.2314453125,
				0.265625,
				0.2998046875,
				0.3212890625,
				0.3486328125,
				0.3759765625,
				0.400390625,
				0.4130859375,
				0.421875,
				0.4267578125,
				0.4287109375,
				0.4287109375,
				0.4287109375,
				0.4296875,
				0.4306640625,
				0.431640625,
				0.4306640625,
				0.4306640625,
				0.4296875,
				0.427734375,
				0.427734375,
				0.427734375,
				0.427734375,
				0.4208984375,
				0.4228515625,
				0.4248046875,
				0.4248046875,
				0.296875,
				0.11328125,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 634,
			"versionNonce": 1438565380,
			"isDeleted": false,
			"id": "esIrRf64smmk1DC07YjFl",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1729.8535926976533,
			"y": 149.85497820436512,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.22776594013406,
			"height": 22.347867455149828,
			"seed": 1784818457,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223436,
			"link": null,
			"locked": false,
			"points": [
				[
					-34.4046900680561,
					0
				],
				[
					-34.4046900680561,
					0.2940464597440292
				],
				[
					-34.11066604261899,
					0.2940464597440292
				],
				[
					-34.4046900680561,
					0.2940464597440292
				],
				[
					-34.11066604261899,
					0.2940464597440292
				],
				[
					-34.11066604261899,
					0
				],
				[
					-33.81659714856802,
					0
				],
				[
					-34.11066604261899,
					0.2940464597440292
				],
				[
					-34.4046900680561,
					1.176197056129597
				],
				[
					-34.99282785615795,
					2.0583476525151365
				],
				[
					-35.874944801083124,
					3.5286023855421855
				],
				[
					-37.3451995341102,
					5.292914795466689
				],
				[
					-38.81545426713721,
					6.763169528493736
				],
				[
					-41.75596373319132,
					9.409621317650384
				],
				[
					-44.69647319924543,
					11.467980187318945
				],
				[
					-46.754865720374326,
					12.938234920345995
				],
				[
					-49.69537518642842,
					14.996593790014561
				],
				[
					-52.635884652482495,
					16.466848523041612
				],
				[
					-55.28232522448566,
					17.937103256068653
				],
				[
					-57.6347417710517,
					19.113311529351684
				],
				[
					-59.98715831761771,
					19.995462125737205
				],
				[
					-62.04550597013284,
					20.877612722122773
				],
				[
					-64.10385362264796,
					21.465716858764264
				],
				[
					-65.86817724972597,
					21.759763318508316
				],
				[
					-66.45627016921404,
					22.05382099540578
				],
				[
					-67.04436308870208,
					22.347867455149828
				],
				[
					-67.04436308870208,
					22.347867455149828
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0,
				0.005859375,
				0.1240234375,
				0.1484375,
				0.1552734375,
				0.1591796875,
				0.193359375,
				0.3017578125,
				0.3017578125,
				0.3017578125,
				0.3017578125,
				0.3017578125,
				0.3017578125,
				0.3037109375,
				0.3037109375,
				0.3037109375,
				0.3037109375,
				0.3017578125,
				0.2998046875,
				0.29296875,
				0.275390625,
				0.244140625,
				0.203125,
				0.158203125,
				0.1162109375,
				0.013671875,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 642,
			"versionNonce": 2105699900,
			"isDeleted": false,
			"id": "L26KRsEu3brBaUDhs_imE",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1658.3984654098726,
			"y": 134.87428582403413,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 10.585852025240156,
			"height": 38.52068073560078,
			"seed": 75263735,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223436,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					-0.3099590865812296
				],
				[
					0.29406889405082104,
					-0.6040167634786826
				],
				[
					0.5880929194880581,
					-0.6040167634786826
				],
				[
					0.8821618135388795,
					-0.6040167634786826
				],
				[
					1.1761858389761162,
					-0.6040167634786826
				],
				[
					1.470254733027048,
					-0.3099590865812296
				],
				[
					2.0583476525151063,
					-0.015912626837172775
				],
				[
					2.940509466054096,
					0.8662379695483662
				],
				[
					3.8226712795929765,
					1.7483997830873268
				],
				[
					4.704833093131964,
					2.6305503794728673
				],
				[
					5.586950038057263,
					3.806747435602462
				],
				[
					6.469111851596251,
					5.57105984552699
				],
				[
					7.351273665135238,
					7.041314578554014
				],
				[
					7.9393665846232935,
					8.21751163468361
				],
				[
					8.82152839816229,
					9.981824044608143
				],
				[
					9.409621317650345,
					11.746125237379228
				],
				[
					9.997714237138402,
					14.3925882436893
				],
				[
					10.291783131189339,
					16.450947113357845
				],
				[
					10.585852025240156,
					18.803352442770443
				],
				[
					10.585852025240156,
					20.861711312439
				],
				[
					10.291783131189339,
					22.9200589649541
				],
				[
					9.997714237138402,
					24.978417834622647
				],
				[
					9.703690211701284,
					26.448672567649705
				],
				[
					8.82152839816229,
					29.095135573959777
				],
				[
					8.23343547867423,
					30.271332630089383
				],
				[
					7.645342559186061,
					31.741587363116412
				],
				[
					6.763180745647182,
					32.6237491766554
				],
				[
					5.881018932108192,
					33.505899773040916
				],
				[
					4.998857118569201,
					34.38805036942647
				],
				[
					3.8226712795929765,
					35.270200965812045
				],
				[
					2.940509466054096,
					35.85830510245355
				],
				[
					2.0583476525151063,
					36.44640923909503
				],
				[
					1.7643236270778706,
					37.034513375736516
				],
				[
					1.1761858389761162,
					37.32855983548059
				],
				[
					0.8821618135388795,
					37.62260629522461
				],
				[
					0.5880929194880581,
					37.62260629522461
				],
				[
					0.5880929194880581,
					37.916663972122095
				],
				[
					0.5880929194880581,
					37.916663972122095
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.00390625,
				0.1318359375,
				0.248046875,
				0.2978515625,
				0.310546875,
				0.3310546875,
				0.357421875,
				0.3720703125,
				0.3798828125,
				0.3818359375,
				0.3818359375,
				0.3818359375,
				0.3798828125,
				0.3798828125,
				0.3798828125,
				0.37890625,
				0.37890625,
				0.37890625,
				0.380859375,
				0.3798828125,
				0.37890625,
				0.3779296875,
				0.376953125,
				0.37890625,
				0.3818359375,
				0.380859375,
				0.3798828125,
				0.3798828125,
				0.37890625,
				0.3759765625,
				0.37109375,
				0.3583984375,
				0.3330078125,
				0.2998046875,
				0.248046875,
				0.1728515625,
				0.125,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 642,
			"versionNonce": 1691329412,
			"isDeleted": false,
			"id": "hwDON7pJYSMuwZIBHNVg3",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1659.505091508137,
			"y": 185.6301613745428,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 38.22662305870338,
			"height": 17.0549526596831,
			"seed": 1660903417,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223436,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					-1.859719048296891
				],
				[
					2.0583476525152196,
					-2.447823184938402
				],
				[
					3.2345334914913364,
					-2.7418808618358548
				],
				[
					3.822671279593089,
					-3.035927321579911
				],
				[
					4.998857118569314,
					-3.6240314582213955
				],
				[
					6.175042957545434,
					-3.6240314582213955
				],
				[
					7.645297690572484,
					-3.6240314582213955
				],
				[
					9.115552423599537,
					-3.6240314582213955
				],
				[
					10.879876050677517,
					-3.329973781323968
				],
				[
					12.64419967775539,
					-3.035927321579911
				],
				[
					14.702547330270596,
					-2.447823184938402
				],
				[
					17.05496387683653,
					-1.859719048296891
				],
				[
					19.407335554788872,
					-0.9775684519113527
				],
				[
					21.759752101354923,
					-0.09541785552578459
				],
				[
					23.5240757284329,
					0.7867327408597535
				],
				[
					26.170516300436066,
					2.5510451507842578
				],
				[
					28.228863952951162,
					3.727242206913854
				],
				[
					29.69911868597823,
					4.903450480196844
				],
				[
					31.46344231305621,
					6.373705213223926
				],
				[
					32.93369704608326,
					7.549902269353494
				],
				[
					34.10988288505936,
					8.726110542636519
				],
				[
					35.28611359264928,
					9.902318815919532
				],
				[
					35.87420651213735,
					10.784469412305079
				],
				[
					36.462299431625425,
					11.37257354894658
				],
				[
					37.05039235111345,
					11.960666468434663
				],
				[
					37.63853013921534,
					12.254724145332116
				],
				[
					37.932554164652466,
					12.842828281973638
				],
				[
					37.932554164652466,
					13.136874741717666
				],
				[
					38.22662305870338,
					13.136874741717666
				],
				[
					38.22662305870338,
					13.430921201461704
				],
				[
					38.22662305870338,
					13.136874741717666
				],
				[
					38.22662305870338,
					13.136874741717666
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0009765625,
				0.1845703125,
				0.2314453125,
				0.265625,
				0.2998046875,
				0.3212890625,
				0.3486328125,
				0.3759765625,
				0.400390625,
				0.4130859375,
				0.421875,
				0.4267578125,
				0.4287109375,
				0.4287109375,
				0.4287109375,
				0.4296875,
				0.4306640625,
				0.431640625,
				0.4306640625,
				0.4306640625,
				0.4296875,
				0.427734375,
				0.427734375,
				0.427734375,
				0.427734375,
				0.4208984375,
				0.4228515625,
				0.4248046875,
				0.4248046875,
				0.296875,
				0.11328125,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 637,
			"versionNonce": 1276200636,
			"isDeleted": false,
			"id": "EWtyLERdt-6nT0nZT9Cgu",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1731.5483117154104,
			"y": 198.47298965651646,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.22776594013406,
			"height": 22.347867455149828,
			"seed": 1461811223,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223436,
			"link": null,
			"locked": false,
			"points": [
				[
					-34.4046900680561,
					0
				],
				[
					-34.4046900680561,
					0.2940464597440292
				],
				[
					-34.11066604261899,
					0.2940464597440292
				],
				[
					-34.4046900680561,
					0.2940464597440292
				],
				[
					-34.11066604261899,
					0.2940464597440292
				],
				[
					-34.11066604261899,
					0
				],
				[
					-33.81659714856802,
					0
				],
				[
					-34.11066604261899,
					0.2940464597440292
				],
				[
					-34.4046900680561,
					1.176197056129597
				],
				[
					-34.99282785615795,
					2.0583476525151365
				],
				[
					-35.874944801083124,
					3.5286023855421855
				],
				[
					-37.3451995341102,
					5.292914795466689
				],
				[
					-38.81545426713721,
					6.763169528493736
				],
				[
					-41.75596373319132,
					9.409621317650384
				],
				[
					-44.69647319924543,
					11.467980187318945
				],
				[
					-46.754865720374326,
					12.938234920345995
				],
				[
					-49.69537518642842,
					14.996593790014561
				],
				[
					-52.635884652482495,
					16.466848523041612
				],
				[
					-55.28232522448566,
					17.937103256068653
				],
				[
					-57.6347417710517,
					19.113311529351684
				],
				[
					-59.98715831761771,
					19.995462125737205
				],
				[
					-62.04550597013284,
					20.877612722122773
				],
				[
					-64.10385362264796,
					21.465716858764264
				],
				[
					-65.86817724972597,
					21.759763318508316
				],
				[
					-66.45627016921404,
					22.05382099540578
				],
				[
					-67.04436308870208,
					22.347867455149828
				],
				[
					-67.04436308870208,
					22.347867455149828
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0,
				0.005859375,
				0.1240234375,
				0.1484375,
				0.1552734375,
				0.1591796875,
				0.193359375,
				0.3017578125,
				0.3017578125,
				0.3017578125,
				0.3017578125,
				0.3017578125,
				0.3017578125,
				0.3037109375,
				0.3037109375,
				0.3037109375,
				0.3037109375,
				0.3017578125,
				0.2998046875,
				0.29296875,
				0.275390625,
				0.244140625,
				0.203125,
				0.158203125,
				0.1162109375,
				0.013671875,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 646,
			"versionNonce": 764973828,
			"isDeleted": false,
			"id": "FDADMopexcRJqrT2sU6I5",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1660.093184427627,
			"y": 183.49229727618558,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 10.585852025240156,
			"height": 38.52068073560078,
			"seed": 1071839449,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223436,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					-0.3099590865812296
				],
				[
					0.29406889405082104,
					-0.6040167634786826
				],
				[
					0.5880929194880581,
					-0.6040167634786826
				],
				[
					0.8821618135388795,
					-0.6040167634786826
				],
				[
					1.1761858389761162,
					-0.6040167634786826
				],
				[
					1.470254733027048,
					-0.3099590865812296
				],
				[
					2.0583476525151063,
					-0.015912626837172775
				],
				[
					2.940509466054096,
					0.8662379695483662
				],
				[
					3.8226712795929765,
					1.7483997830873268
				],
				[
					4.704833093131964,
					2.6305503794728673
				],
				[
					5.586950038057263,
					3.806747435602462
				],
				[
					6.469111851596251,
					5.57105984552699
				],
				[
					7.351273665135238,
					7.041314578554014
				],
				[
					7.9393665846232935,
					8.21751163468361
				],
				[
					8.82152839816229,
					9.981824044608143
				],
				[
					9.409621317650345,
					11.746125237379228
				],
				[
					9.997714237138402,
					14.3925882436893
				],
				[
					10.291783131189339,
					16.450947113357845
				],
				[
					10.585852025240156,
					18.803352442770443
				],
				[
					10.585852025240156,
					20.861711312439
				],
				[
					10.291783131189339,
					22.9200589649541
				],
				[
					9.997714237138402,
					24.978417834622647
				],
				[
					9.703690211701284,
					26.448672567649705
				],
				[
					8.82152839816229,
					29.095135573959777
				],
				[
					8.23343547867423,
					30.271332630089383
				],
				[
					7.645342559186061,
					31.741587363116412
				],
				[
					6.763180745647182,
					32.6237491766554
				],
				[
					5.881018932108192,
					33.505899773040916
				],
				[
					4.998857118569201,
					34.38805036942647
				],
				[
					3.8226712795929765,
					35.270200965812045
				],
				[
					2.940509466054096,
					35.85830510245355
				],
				[
					2.0583476525151063,
					36.44640923909503
				],
				[
					1.7643236270778706,
					37.034513375736516
				],
				[
					1.1761858389761162,
					37.32855983548059
				],
				[
					0.8821618135388795,
					37.62260629522461
				],
				[
					0.5880929194880581,
					37.62260629522461
				],
				[
					0.5880929194880581,
					37.916663972122095
				],
				[
					0.5880929194880581,
					37.916663972122095
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.00390625,
				0.1318359375,
				0.248046875,
				0.2978515625,
				0.310546875,
				0.3310546875,
				0.357421875,
				0.3720703125,
				0.3798828125,
				0.3818359375,
				0.3818359375,
				0.3818359375,
				0.3798828125,
				0.3798828125,
				0.3798828125,
				0.37890625,
				0.37890625,
				0.37890625,
				0.380859375,
				0.3798828125,
				0.37890625,
				0.3779296875,
				0.376953125,
				0.37890625,
				0.3818359375,
				0.380859375,
				0.3798828125,
				0.3798828125,
				0.37890625,
				0.3759765625,
				0.37109375,
				0.3583984375,
				0.3330078125,
				0.2998046875,
				0.248046875,
				0.1728515625,
				0.125,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 490,
			"versionNonce": 70324028,
			"isDeleted": false,
			"id": "wKxXeznIyztQe2IDhe3E9",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 714.1560507841452,
			"y": -213.6179729485914,
			"strokeColor": "#343a40",
			"backgroundColor": "transparent",
			"width": 25.115774613722238,
			"height": 229.05587597423528,
			"seed": 869066903,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223436,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.0046156550965861,
					0
				],
				[
					1.5069426444601959,
					0
				],
				[
					2.009250472008489,
					0
				],
				[
					2.5115774613722124,
					0
				],
				[
					3.516193116468912,
					0
				],
				[
					4.520827933380815,
					-0.5023078275482931
				],
				[
					6.027770577841011,
					-0.5023078275482931
				],
				[
					7.5347323841165235,
					-0.5023078275482931
				],
				[
					9.54398285612524,
					-1.0046348169119597
				],
				[
					11.050925500585436,
					-1.5069426444602527
				],
				[
					12.557887306861176,
					-1.5069426444602527
				],
				[
					13.562502961957762,
					-1.5069426444602527
				],
				[
					15.069464768233274,
					-1.5069426444602527
				],
				[
					16.07408042332986,
					-1.5069426444602527
				],
				[
					17.078715240241763,
					-1.5069426444602527
				],
				[
					17.581042229605373,
					-1.0046348169119597
				],
				[
					18.585657884702186,
					0.5023269893636666
				],
				[
					18.585657884702186,
					2.0092696338239193
				],
				[
					18.585657884702186,
					3.013904450735879
				],
				[
					18.585657884702186,
					5.023154922744482
				],
				[
					18.585657884702186,
					7.032424556568344
				],
				[
					18.083350057153893,
					10.548636834852516
				],
				[
					18.083350057153893,
					14.064829951321315
				],
				[
					17.581042229605373,
					16.576407412693527
				],
				[
					17.581042229605373,
					20.594946680341366
				],
				[
					17.581042229605373,
					24.11113979681022
				],
				[
					17.581042229605373,
					27.627352075094393
				],
				[
					17.581042229605373,
					32.148199170290525
				],
				[
					17.581042229605373,
					35.16208445921103
				],
				[
					17.581042229605373,
					40.68756637131912
				],
				[
					17.581042229605373,
					44.70608647715159
				],
				[
					17.581042229605373,
					48.72460658298411
				],
				[
					17.581042229605373,
					51.738491871904614
				],
				[
					17.581042229605373,
					55.25470415018873
				],
				[
					17.078715240241763,
					60.277859072933154
				],
				[
					17.078715240241763,
					63.29176352366909
				],
				[
					17.078715240241763,
					66.80795664013789
				],
				[
					16.57640741269347,
					70.32416891842206
				],
				[
					16.57640741269347,
					73.84038119670623
				],
				[
					16.57640741269347,
					77.3565934749904
				],
				[
					16.57640741269347,
					81.37511358082287
				],
				[
					16.57640741269347,
					83.88669104219508
				],
				[
					16.57640741269347,
					88.40753813739121
				],
				[
					16.57640741269347,
					91.92373125386007
				],
				[
					16.57640741269347,
					94.93763570459589
				],
				[
					17.078715240241763,
					98.45384798288006
				],
				[
					17.078715240241763,
					102.47236808871259
				],
				[
					17.078715240241763,
					105.98858036699676
				],
				[
					17.078715240241763,
					109.50477348346556
				],
				[
					17.078715240241763,
					112.51867793420143
				],
				[
					17.078715240241763,
					115.03025539557365
				],
				[
					17.078715240241763,
					117.03950586758219
				],
				[
					17.078715240241763,
					120.05341031831807
				],
				[
					17.078715240241763,
					122.06266079032662
				],
				[
					17.078715240241763,
					124.07193042415054
				],
				[
					17.078715240241763,
					126.58350788552275
				],
				[
					17.078715240241763,
					128.59277751934667
				],
				[
					16.57640741269347,
					131.10435498071888
				],
				[
					16.57640741269347,
					133.6159324420911
				],
				[
					16.07408042332986,
					136.1275099034633
				],
				[
					15.571772595781567,
					138.63908736483552
				],
				[
					15.571772595781567,
					141.15066482620773
				],
				[
					15.571772595781567,
					142.65760747066804
				],
				[
					15.571772595781567,
					146.1738197489522
				],
				[
					15.571772595781567,
					147.68076239341246
				],
				[
					15.571772595781567,
					150.69464768233297
				],
				[
					15.571772595781567,
					153.20622514370518
				],
				[
					15.571772595781567,
					155.7178026050774
				],
				[
					15.571772595781567,
					158.2293800664496
				],
				[
					15.069464768233274,
					161.2432653553701
				],
				[
					15.069464768233274,
					163.75484281674233
				],
				[
					15.069464768233274,
					166.76876642929358
				],
				[
					15.069464768233274,
					169.78265171821408
				],
				[
					15.069464768233274,
					172.2942291795863
				],
				[
					15.069464768233274,
					173.80115266223123
				],
				[
					14.567137778869665,
					176.31273012360344
				],
				[
					14.064829951321371,
					178.32199975742736
				],
				[
					13.562502961957762,
					179.82896156370293
				],
				[
					13.562502961957762,
					181.83823119752685
				],
				[
					14.064829951321371,
					183.3451546801718
				],
				[
					14.064829951321371,
					185.3544243139957
				],
				[
					13.562502961957762,
					187.36369394781957
				],
				[
					13.562502961957762,
					189.87527140919184
				],
				[
					13.060195134409241,
					192.38684887056405
				],
				[
					12.557887306861176,
					194.89842633193626
				],
				[
					12.557887306861176,
					196.90769596576018
				],
				[
					12.557887306861176,
					198.41461944840506
				],
				[
					12.557887306861176,
					200.42388908222898
				],
				[
					12.557887306861176,
					202.4331587160529
				],
				[
					12.055560317497566,
					204.44242834987682
				],
				[
					12.055560317497566,
					206.45165966007005
				],
				[
					12.055560317497566,
					208.4609292938939
				],
				[
					12.055560317497566,
					209.96789110016954
				],
				[
					12.055560317497566,
					211.47481458281447
				],
				[
					12.055560317497566,
					212.47946856154175
				],
				[
					12.055560317497566,
					213.4840842166384
				],
				[
					12.055560317497566,
					214.99104602291396
				],
				[
					11.553252489949045,
					215.9956616780106
				],
				[
					11.553252489949045,
					216.4979695055589
				],
				[
					11.553252489949045,
					218.00493131183447
				],
				[
					11.553252489949045,
					219.0095469669311
				],
				[
					11.553252489949045,
					220.0142009456584
				],
				[
					11.553252489949045,
					221.01881660075503
				],
				[
					11.050925500585436,
					221.52112442830332
				],
				[
					11.050925500585436,
					222.5257784070306
				],
				[
					11.050925500585436,
					223.02808623457895
				],
				[
					11.050925500585436,
					224.03270188967554
				],
				[
					11.050925500585436,
					224.53504804085452
				],
				[
					11.050925500585436,
					225.0373558684028
				],
				[
					10.548617673037143,
					225.53966369595116
				],
				[
					10.04630984548885,
					225.53966369595116
				],
				[
					9.54398285612524,
					226.04197152349946
				],
				[
					8.539348039213337,
					226.54427935104775
				],
				[
					8.037040211665044,
					226.54427935104775
				],
				[
					7.5347323841165235,
					227.04662550222673
				],
				[
					6.530097567204621,
					227.04662550222673
				],
				[
					6.027770577841011,
					227.04662550222673
				],
				[
					5.023154922744425,
					227.04662550222673
				],
				[
					3.516193116468912,
					227.04662550222673
				],
				[
					1.5069426444601959,
					227.04662550222673
				],
				[
					-0.5023269893636098,
					227.04662550222673
				],
				[
					-2.5115774613722124,
					226.54427935104775
				],
				[
					-4.520847095196132,
					226.54427935104775
				],
				[
					-6.027789739656328,
					226.54427935104775
				],
				[
					-6.027789739656328,
					227.04662550222673
				],
				[
					-6.530116729020051,
					227.54893332977502
				],
				[
					-6.530116729020051,
					227.54893332977502
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0,
				0.158203125,
				0.166015625,
				0.1748046875,
				0.1787109375,
				0.1923828125,
				0.203125,
				0.21484375,
				0.2255859375,
				0.2255859375,
				0.2255859375,
				0.224609375,
				0.224609375,
				0.224609375,
				0.2236328125,
				0.224609375,
				0.224609375,
				0.2236328125,
				0.2236328125,
				0.2236328125,
				0.22265625,
				0.22265625,
				0.2236328125,
				0.224609375,
				0.2236328125,
				0.2236328125,
				0.22265625,
				0.22265625,
				0.21875,
				0.21484375,
				0.2099609375,
				0.2021484375,
				0.2060546875,
				0.2060546875,
				0.20703125,
				0.2060546875,
				0.205078125,
				0.203125,
				0.203125,
				0.201171875,
				0.19921875,
				0.2001953125,
				0.2021484375,
				0.2021484375,
				0.201171875,
				0.2021484375,
				0.2021484375,
				0.2021484375,
				0.2021484375,
				0.203125,
				0.203125,
				0.2021484375,
				0.201171875,
				0.201171875,
				0.2021484375,
				0.2080078125,
				0.212890625,
				0.21484375,
				0.21875,
				0.224609375,
				0.2294921875,
				0.2373046875,
				0.2451171875,
				0.2490234375,
				0.25390625,
				0.25390625,
				0.25390625,
				0.25390625,
				0.2548828125,
				0.25390625,
				0.25390625,
				0.2529296875,
				0.25390625,
				0.2548828125,
				0.2548828125,
				0.25390625,
				0.2548828125,
				0.2548828125,
				0.25390625,
				0.2529296875,
				0.2529296875,
				0.251953125,
				0.251953125,
				0.251953125,
				0.251953125,
				0.251953125,
				0.25,
				0.244140625,
				0.232421875,
				0.2265625,
				0.2236328125,
				0.2216796875,
				0.220703125,
				0.2197265625,
				0.220703125,
				0.2197265625,
				0.2197265625,
				0.2236328125,
				0.2216796875,
				0.2197265625,
				0.21875,
				0.21875,
				0.2177734375,
				0.2177734375,
				0.2197265625,
				0.2197265625,
				0.2177734375,
				0.216796875,
				0.216796875,
				0.2177734375,
				0.216796875,
				0.216796875,
				0.2177734375,
				0.216796875,
				0.216796875,
				0.2177734375,
				0.2177734375,
				0.2177734375,
				0.216796875,
				0.216796875,
				0.2177734375,
				0.2177734375,
				0.216796875,
				0.2021484375,
				0.166015625,
				0.146484375,
				0,
				0
			]
		},
		{
			"type": "line",
			"version": 328,
			"versionNonce": 1586991748,
			"isDeleted": false,
			"id": "9pah5zylQLmQkPF5_lhxL",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1271.086891692638,
			"y": -213.4931559767233,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 18.585696208332593,
			"height": 1.0046348169119597,
			"seed": 1947721111,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223436,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-18.585696208332593,
					1.0046348169119597
				]
			]
		},
		{
			"type": "line",
			"version": 402,
			"versionNonce": 641976252,
			"isDeleted": false,
			"id": "W7eff5EWVTg-NZ1f_TbGA",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1250.99423367803,
			"y": -213.99547338517925,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 1.5069234826448792,
			"height": 92.42605824322368,
			"seed": 765448313,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223436,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-1.5069234826448792,
					92.42605824322368
				]
			]
		},
		{
			"type": "line",
			"version": 323,
			"versionNonce": 646619652,
			"isDeleted": false,
			"id": "KcAjLwUtOhmyoN5a3xgMw",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1247.9803483891096,
			"y": -120.06247249749526,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 23.106543303528724,
			"height": 1.5069426444602527,
			"seed": 1879852855,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223436,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					23.106543303528724,
					-1.5069426444602527
				]
			]
		},
		{
			"type": "line",
			"version": 416,
			"versionNonce": 1449881660,
			"isDeleted": false,
			"id": "42qiMXX1znJmP6x0SPTPm",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 731.7558244614513,
			"y": -179.9536941275926,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 516.8464420627183,
			"height": 10.94343986768223,
			"seed": 1560550617,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223437,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					516.8464420627183,
					10.94343986768223
				]
			]
		},
		{
			"type": "line",
			"version": 374,
			"versionNonce": 745521540,
			"isDeleted": false,
			"id": "lYIPmKjelt82U1eYXBKSJ",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1270.7102087265152,
			"y": -89.79794684232638,
			"strokeColor": "#a61e4d",
			"backgroundColor": "transparent",
			"width": 18.585696208332593,
			"height": 1.0046348169119597,
			"seed": 295713719,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223437,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-18.585696208332593,
					1.0046348169119597
				]
			]
		},
		{
			"type": "line",
			"version": 448,
			"versionNonce": 1686767804,
			"isDeleted": false,
			"id": "cFPXOxa62IWvvU9j3z3hD",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1250.6175507119074,
			"y": -90.30026425078245,
			"strokeColor": "#a61e4d",
			"backgroundColor": "transparent",
			"width": 1.5069234826448792,
			"height": 92.42605824322368,
			"seed": 73121593,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223437,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-1.5069234826448792,
					92.42605824322368
				]
			]
		},
		{
			"type": "line",
			"version": 369,
			"versionNonce": 126152964,
			"isDeleted": false,
			"id": "OS23d8-I9KbBbF91vmUfK",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1247.603665422987,
			"y": 3.6327366369016545,
			"strokeColor": "#a61e4d",
			"backgroundColor": "transparent",
			"width": 23.106543303528724,
			"height": 1.5069426444602527,
			"seed": 1336782039,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223437,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					23.106543303528724,
					-1.5069426444602527
				]
			]
		},
		{
			"type": "line",
			"version": 405,
			"versionNonce": 1413583164,
			"isDeleted": false,
			"id": "W5hzGaZHvsdl5U11qnuPf",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 730.691027187064,
			"y": -135.85707150053145,
			"strokeColor": "#a61e4d",
			"backgroundColor": "transparent",
			"width": 519.1280655173382,
			"height": 86.62108532991417,
			"seed": 1121858425,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223437,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					519.1280655173382,
					86.62108532991417
				]
			]
		},
		{
			"type": "line",
			"version": 391,
			"versionNonce": 927477892,
			"isDeleted": false,
			"id": "MSmNbLE2MUNqK0idrvLPn",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 732.8724845455388,
			"y": -82.95777190229478,
			"strokeColor": "#862e9c",
			"backgroundColor": "transparent",
			"width": 512.0940168782804,
			"height": 151.5954076022685,
			"seed": 1720586073,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223437,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					512.0940168782804,
					151.5954076022685
				]
			]
		},
		{
			"type": "line",
			"version": 346,
			"versionNonce": 1693714876,
			"isDeleted": false,
			"id": "J4pyBgbwst7CZJo6C-B-6",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1271.589237843817,
			"y": 32.64145439956906,
			"strokeColor": "#862e9c",
			"backgroundColor": "transparent",
			"width": 18.585696208332593,
			"height": 1.0046348169119597,
			"seed": 319399959,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223437,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-18.585696208332593,
					1.0046348169119597
				]
			]
		},
		{
			"type": "line",
			"version": 420,
			"versionNonce": 460816388,
			"isDeleted": false,
			"id": "CdWddYH_kg2fJA0R5F8C5",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1251.4965798292092,
			"y": 32.139136991113105,
			"strokeColor": "#862e9c",
			"backgroundColor": "transparent",
			"width": 1.5069234826448792,
			"height": 92.42605824322368,
			"seed": 970311897,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223437,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-1.5069234826448792,
					92.42605824322368
				]
			]
		},
		{
			"type": "line",
			"version": 341,
			"versionNonce": 432239164,
			"isDeleted": false,
			"id": "uzU-r7QjL4z84Qo-pOa1J",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1248.4826945402888,
			"y": 126.0721378787971,
			"strokeColor": "#862e9c",
			"backgroundColor": "transparent",
			"width": 23.106543303528724,
			"height": 1.5069426444602527,
			"seed": 1307217207,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223437,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					23.106543303528724,
					-1.5069426444602527
				]
			]
		},
		{
			"type": "line",
			"version": 375,
			"versionNonce": 1813045124,
			"isDeleted": false,
			"id": "-UdaX8dHIqCy1bOy3M4_w",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1271.4636704678383,
			"y": 156.71339440462725,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 18.585696208332593,
			"height": 1.0046348169119597,
			"seed": 1200946617,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223437,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-18.585696208332593,
					1.0046348169119597
				]
			]
		},
		{
			"type": "line",
			"version": 449,
			"versionNonce": 1100073660,
			"isDeleted": false,
			"id": "JnYLApaxENPtAZXQOfTSN",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1251.3710124532295,
			"y": 156.2110769961714,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 1.5069234826448792,
			"height": 92.42605824322368,
			"seed": 1720555095,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223437,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-1.5069234826448792,
					92.42605824322368
				]
			]
		},
		{
			"type": "line",
			"version": 370,
			"versionNonce": 827477764,
			"isDeleted": false,
			"id": "dqWzfbudZ_X33vuK5W59k",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1248.357127164309,
			"y": 250.14407788385523,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 23.106543303528724,
			"height": 1.5069426444602527,
			"seed": 1132387993,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223437,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					23.106543303528724,
					-1.5069426444602527
				]
			]
		},
		{
			"type": "line",
			"version": 386,
			"versionNonce": 2130776892,
			"isDeleted": false,
			"id": "v3IKdqu8A0WdDSuBPfN26",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 730.8181906840825,
			"y": -28.841009296015727,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 520.1761004793934,
			"height": 218.70722810693778,
			"seed": 140834073,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223437,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					520.1761004793934,
					218.70722810693778
				]
			]
		},
		{
			"type": "freedraw",
			"version": 298,
			"versionNonce": 1002032772,
			"isDeleted": false,
			"id": "3ckqG0CZoXK0aKneP0peR",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1479.1049417475756,
			"y": -193.66741498611805,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 11.710777876750626,
			"height": 14.052937919407896,
			"seed": 1527669335,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223437,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					0.4684329019929123
				],
				[
					0.468423967378385,
					0.4684329019929123
				],
				[
					0.468423967378385,
					0
				],
				[
					0.93684793475677,
					-1.4052897713642665
				],
				[
					1.8736958695137673,
					-3.2790213793359158
				],
				[
					2.3421555753500343,
					-4.684311150700239
				],
				[
					3.2790035101070316,
					-7.02646672605033
				],
				[
					4.215851444863802,
					-9.368622301400478
				],
				[
					5.152735118078681,
					-11.242344974757657
				],
				[
					6.089583052835678,
					-12.179210778743482
				],
				[
					6.558007020214063,
					-13.116072115422128
				],
				[
					6.558007020214063,
					-13.584505017414983
				],
				[
					7.02646672605033,
					-13.116072115422128
				],
				[
					7.494890693428715,
					-12.647639213429159
				],
				[
					7.9633146608073275,
					-11.242344974757657
				],
				[
					8.431738628185713,
					-9.368622301400478
				],
				[
					9.368622301400592,
					-7.4948996280432425
				],
				[
					9.837046268778977,
					-5.152744052693151
				],
				[
					10.305470236157362,
					-3.2790213793359158
				],
				[
					11.242318170914132,
					-1.8737226733571788
				],
				[
					11.242318170914132,
					-1.4052897713642665
				],
				[
					11.242318170914132,
					-0.4684329019929123
				],
				[
					11.710777876750626,
					-0.4684329019929123
				],
				[
					11.710777876750626,
					-0.9368658039858246
				],
				[
					11.710777876750626,
					-0.9368658039858246
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0078125,
				0.16015625,
				0.53125,
				0.560546875,
				0.6171875,
				0.6435546875,
				0.6484375,
				0.650390625,
				0.6494140625,
				0.6484375,
				0.6494140625,
				0.6513671875,
				0.6513671875,
				0.654296875,
				0.658203125,
				0.6611328125,
				0.6630859375,
				0.6669921875,
				0.671875,
				0.6708984375,
				0.625,
				0.560546875,
				0.265625,
				0.064453125,
				0.0322265625,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 279,
			"versionNonce": 1349733308,
			"isDeleted": false,
			"id": "sRpmC1WQrAGjBThpAmxER",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1488.4735640489757,
			"y": -198.35172613681834,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 5.15277085653679,
			"height": 0,
			"seed": 805292537,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223437,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-0.9368836732148793,
					0
				],
				[
					-1.4053076405932643,
					0
				],
				[
					-2.8106152811865286,
					0
				],
				[
					-4.215887183321911,
					0
				],
				[
					-5.15277085653679,
					0
				],
				[
					-5.15277085653679,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0029296875,
				0.2412109375,
				0.330078125,
				0.357421875,
				0.2548828125,
				0.060546875,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 279,
			"versionNonce": 470113796,
			"isDeleted": false,
			"id": "fw4F9AFJUBbScTUFveLfM",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1496.9053026771612,
			"y": -201.63074751615432,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 0.93684793475677,
			"height": 13.116076582729363,
			"seed": 1380091257,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223437,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.468423967378385,
					4.215887183321797
				],
				[
					0.468423967378385,
					6.089609856679033
				],
				[
					-0.468423967378385,
					8.431765432029124
				],
				[
					-0.468423967378385,
					10.773921007379272
				],
				[
					-0.468423967378385,
					13.116076582729363
				],
				[
					-0.468423967378385,
					13.116076582729363
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0,
				0.259765625,
				0.263671875,
				0.20703125,
				0.0791015625,
				0.0029296875,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 279,
			"versionNonce": 403338300,
			"isDeleted": false,
			"id": "4fgT2OL7PXc8In0UgM9oe",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1482.3839452576826,
			"y": -80.77551446731968,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 2.3421555753500343,
			"height": 14.05293345210066,
			"seed": 709741081,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223437,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-0.468423967378385
				],
				[
					0.468423967378385,
					-0.468423967378385
				],
				[
					0.468423967378385,
					0
				],
				[
					0,
					0
				],
				[
					0,
					1.8737316079717061
				],
				[
					-0.468423967378385,
					4.215887183321797
				],
				[
					-0.9368479347569973,
					7.494890693428829
				],
				[
					-1.4053076405932643,
					10.305488105386303
				],
				[
					-1.4053076405932643,
					12.179201844129068
				],
				[
					-1.8737316079716493,
					13.584509484722275
				],
				[
					-1.4053076405932643,
					13.584509484722275
				],
				[
					-1.4053076405932643,
					13.584509484722275
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0068359375,
				0.044921875,
				0.51953125,
				0.74609375,
				0.796875,
				0.8515625,
				0.8466796875,
				0.802734375,
				0.705078125,
				0.576171875,
				0.3408203125,
				0.02734375,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 294,
			"versionNonce": 456326532,
			"isDeleted": false,
			"id": "99zxKJ5VhDoBTPQFyPdYd",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1483.7892528982752,
			"y": -82.18080423868378,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 9.368622301400364,
			"height": 13.584491615493278,
			"seed": 1582551097,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223437,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.4052719021353823,
					0
				],
				[
					1.8736958695137673,
					0.468423967378385
				],
				[
					2.8105795427284193,
					0.468423967378385
				],
				[
					3.2790035101070316,
					0.9368658039858246
				],
				[
					4.215851444863802,
					0.9368658039858246
				],
				[
					4.684311150700296,
					1.4052897713642096
				],
				[
					4.684311150700296,
					2.810579542728533
				],
				[
					4.215851444863802,
					3.7474453467143576
				],
				[
					3.2790035101070316,
					4.684311150700182
				],
				[
					2.8105795427284193,
					5.152735118078681
				],
				[
					2.3421555753500343,
					5.152735118078681
				],
				[
					2.8105795427284193,
					5.621176954686007
				],
				[
					3.2790035101070316,
					5.621176954686007
				],
				[
					4.215851444863802,
					6.0896009220645055
				],
				[
					5.152735118078681,
					6.5580248894428905
				],
				[
					6.558007020213836,
					7.494890693428772
				],
				[
					7.494890693428715,
					8.431756497414597
				],
				[
					7.494890693428715,
					9.368622301400421
				],
				[
					7.02646672605033,
					9.837046268778863
				],
				[
					6.089583052835451,
					10.773912072764688
				],
				[
					3.7474274774854166,
					12.179201844129011
				],
				[
					1.8736958695137673,
					13.116067648114836
				],
				[
					-0.4684597058364943,
					13.584491615493278
				],
				[
					-1.8737316079716493,
					13.116067648114836
				],
				[
					-1.8737316079716493,
					12.647643680736337
				],
				[
					-1.4053076405932643,
					11.710777876750512
				],
				[
					-1.4053076405932643,
					11.710777876750512
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.001953125,
				0.255859375,
				0.2958984375,
				0.328125,
				0.3310546875,
				0.33203125,
				0.333984375,
				0.3349609375,
				0.337890625,
				0.3388671875,
				0.337890625,
				0.3369140625,
				0.3388671875,
				0.3388671875,
				0.3388671875,
				0.3388671875,
				0.33984375,
				0.3408203125,
				0.33984375,
				0.3408203125,
				0.3466796875,
				0.3681640625,
				0.3798828125,
				0.3779296875,
				0.3046875,
				0.0947265625,
				0.0029296875,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 273,
			"versionNonce": 598248636,
			"isDeleted": false,
			"id": "tyW_XYPyYzFRDJAZcQb2e",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1496.4368787097833,
			"y": -74.68591354525506,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 1.405271902135155,
			"height": 9.837064138007861,
			"seed": 1790629783,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223437,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.468423967378385,
					2.342155575350091
				],
				[
					0.468423967378385,
					3.7474453467144144
				],
				[
					0,
					6.0896009220645055
				],
				[
					-0.93684793475677,
					7.494908562657713
				],
				[
					-0.93684793475677,
					9.837064138007861
				],
				[
					-0.93684793475677,
					9.837064138007861
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.009765625,
				0.3125,
				0.34765625,
				0.279296875,
				0.125,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 282,
			"versionNonce": 847293700,
			"isDeleted": false,
			"id": "B6lzjEFdtPC2PlZKRCWcA",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1488.4735640489757,
			"y": 43.82717286284401,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 7.9633503992652095,
			"height": 8.90019833402198,
			"seed": 1150473239,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223437,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-1.4053076405932643,
					0.9368479347568837
				],
				[
					-2.3421555753502616,
					1.8737316079716493
				],
				[
					-3.2790392485649136,
					2.342155575350091
				],
				[
					-4.215887183321911,
					3.7474274774854166
				],
				[
					-4.684311150700296,
					4.684311150700182
				],
				[
					-5.15277085653679,
					5.621159085457123
				],
				[
					-5.15277085653679,
					7.02646672605033
				],
				[
					-4.215887183321911,
					7.963314660807214
				],
				[
					-3.2790392485649136,
					8.90019833402198
				],
				[
					-1.8737316079718767,
					8.90019833402198
				],
				[
					-0.4684597058364943,
					8.431738628185656
				],
				[
					0.468423967378385,
					7.963314660807214
				],
				[
					1.405271902135155,
					7.963314660807214
				],
				[
					2.8105795427284193,
					7.963314660807214
				],
				[
					2.8105795427284193,
					7.963314660807214
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0029296875,
				0.2236328125,
				0.2744140625,
				0.2900390625,
				0.2939453125,
				0.296875,
				0.3193359375,
				0.390625,
				0.41796875,
				0.421875,
				0.40234375,
				0.314453125,
				0.216796875,
				0.103515625,
				0.0029296875,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 275,
			"versionNonce": 888116540,
			"isDeleted": false,
			"id": "-e-QqULizHk5518jSip0a",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1495.9684547424044,
			"y": 46.16932843819404,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 0.468423967378385,
			"height": 8.431738628185713,
			"seed": 1550332889,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223437,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.468423967378385,
					0.46842396737844183
				],
				[
					0.468423967378385,
					1.4052719021353255
				],
				[
					0.468423967378385,
					2.810579542728533
				],
				[
					0.468423967378385,
					4.215887183321797
				],
				[
					0.468423967378385,
					6.089583052835565
				],
				[
					0.468423967378385,
					7.963314660807214
				],
				[
					0.468423967378385,
					8.431738628185713
				],
				[
					0.468423967378385,
					8.431738628185713
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0009765625,
				0.2041015625,
				0.298828125,
				0.3310546875,
				0.263671875,
				0.123046875,
				0.0146484375,
				0.0009765625,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 280,
			"versionNonce": 57437316,
			"isDeleted": false,
			"id": "-y3_7ggqvG5JSAzauW1LK",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1487.0682564083831,
			"y": 170.77200683374326,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 1.8736958695137673,
			"height": 12.17921971335798,
			"seed": 791653433,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223437,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.468423967378385,
					-0.9368658039858531
				],
				[
					0,
					-0.9368658039858531
				],
				[
					0,
					-1.4053076405932359
				],
				[
					0.468423967378385,
					-1.4053076405932359
				],
				[
					0.468423967378385,
					-0.4684418366073828
				],
				[
					0,
					0.46842396737844183
				],
				[
					-0.468423967378385,
					4.215869314092856
				],
				[
					-0.9368479347569973,
					7.02646672605033
				],
				[
					-0.9368479347569973,
					8.431756497414597
				],
				[
					-1.4052719021353823,
					9.83704626877892
				],
				[
					-1.4052719021353823,
					10.773912072764745
				],
				[
					-0.9368479347569973,
					10.305470236157362
				],
				[
					-0.9368479347569973,
					10.305470236157362
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0,
				0.10546875,
				0.4248046875,
				0.548828125,
				0.568359375,
				0.775390625,
				0.818359375,
				0.82421875,
				0.8134765625,
				0.77734375,
				0.7060546875,
				0.5439453125,
				0.0576171875,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 283,
			"versionNonce": 155291068,
			"isDeleted": false,
			"id": "-2nG0vqdcMF65ydeFQr50",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1489.8788359511113,
			"y": 167.4929854544073,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 7.4948906934289425,
			"height": 14.989799256086542,
			"seed": 1096456119,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223437,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.4053076405934917,
					-0.46844183660741123
				],
				[
					1.8737316079718767,
					0
				],
				[
					2.3421555753502616,
					0.46842396737844183
				],
				[
					2.8106152811865286,
					0.9368658039858246
				],
				[
					3.2790392485649136,
					1.4052897713642665
				],
				[
					3.747463215943526,
					2.342155575350091
				],
				[
					3.747463215943526,
					4.215869314092828
				],
				[
					3.747463215943526,
					6.558024889442976
				],
				[
					2.8106152811865286,
					8.900180464793067
				],
				[
					1.4053076405934917,
					10.773912072764716
				],
				[
					-0.468423967378385,
					13.584491615493306
				],
				[
					-2.3421555753500343,
					14.52135741947913
				],
				[
					-3.2790035101068042,
					14.52135741947913
				],
				[
					-3.7474274774854166,
					14.052933452100689
				],
				[
					-3.2790035101068042,
					13.584491615493306
				],
				[
					-3.2790035101068042,
					13.584491615493306
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0048828125,
				0.20703125,
				0.328125,
				0.3759765625,
				0.400390625,
				0.4072265625,
				0.408203125,
				0.408203125,
				0.4072265625,
				0.40625,
				0.40625,
				0.400390625,
				0.36328125,
				0.283203125,
				0.134765625,
				0.0302734375,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 274,
			"versionNonce": 1337211908,
			"isDeleted": false,
			"id": "-o66nkG2CRK-IYsLzFIIv",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1498.3106103177556,
			"y": 174.98787614783612,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 1.8737316079718767,
			"height": 8.90019833402198,
			"seed": 1570046423,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223437,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-0.46842396737861236,
					2.810597411957474
				],
				[
					-0.46842396737861236,
					4.21588718332174
				],
				[
					-0.9368479347569973,
					6.0896009220645055
				],
				[
					-1.4053076405932643,
					7.494908562657713
				],
				[
					-1.8737316079718767,
					8.431756497414597
				],
				[
					-1.8737316079718767,
					8.90019833402198
				],
				[
					-1.8737316079718767,
					8.90019833402198
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.00390625,
				0.3271484375,
				0.3544921875,
				0.3115234375,
				0.162109375,
				0.0224609375,
				0.00390625,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 268,
			"versionNonce": 1640003132,
			"isDeleted": false,
			"id": "rus7325zCu_-BCXJhqTf_",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1624.7870113866616,
			"y": -160.40877722537994,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 0.0001,
			"height": 0.0001,
			"seed": 531568281,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223437,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.0001,
					0.0001
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 292,
			"versionNonce": 1901468548,
			"isDeleted": false,
			"id": "rnzYW2zO-n8FrTND_vbw0",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1621.9764318439325,
			"y": -160.40877722537994,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 7.0264667260505576,
			"height": 8.900180464793095,
			"seed": 237335703,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223437,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-0.46844183660732597
				],
				[
					-0.46842396737861236,
					0
				],
				[
					-0.46842396737861236,
					-0.46844183660732597
				],
				[
					0,
					-0.46844183660732597
				],
				[
					0,
					-0.9368658039858246
				],
				[
					0.46842396737861236,
					-1.4053076405931506
				],
				[
					0.9368836732148793,
					-2.342155575350091
				],
				[
					1.4053076405932643,
					-2.810597411957474
				],
				[
					1.8737316079716493,
					-3.7474632159432986
				],
				[
					2.3421555753500343,
					-4.684311150700182
				],
				[
					2.8105795427284193,
					-5.621176954686007
				],
				[
					2.8105795427284193,
					-6.5580427586718315
				],
				[
					3.2790392485649136,
					-6.5580427586718315
				],
				[
					3.7474632159432986,
					-7.02646672605033
				],
				[
					4.215887183321911,
					-6.5580427586718315
				],
				[
					4.684311150700296,
					-6.0896187912934465
				],
				[
					4.684311150700296,
					-5.152752987307622
				],
				[
					5.152735118078681,
					-3.2790213793359158
				],
				[
					5.621194823914948,
					-1.8737316079716493
				],
				[
					6.089618791293333,
					-0.46844183660732597
				],
				[
					6.089618791293333,
					0.9368479347569405
				],
				[
					6.558042758671945,
					1.4052897713643233
				],
				[
					6.089618791293333,
					1.8737137387427651
				],
				[
					6.558042758671945,
					1.8737137387427651
				],
				[
					6.558042758671945,
					1.8737137387427651
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0,
				0.0107421875,
				0.376953125,
				0.4931640625,
				0.5,
				0.5126953125,
				0.517578125,
				0.5185546875,
				0.5185546875,
				0.51953125,
				0.5205078125,
				0.5185546875,
				0.5185546875,
				0.5185546875,
				0.53515625,
				0.6318359375,
				0.65234375,
				0.6669921875,
				0.6806640625,
				0.677734375,
				0.654296875,
				0.513671875,
				0.3798828125,
				0.197265625,
				0.1142578125,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 273,
			"versionNonce": 189681340,
			"isDeleted": false,
			"id": "M0oONaocG2HUW6v09BAJV",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1627.5976266678476,
			"y": -163.2193746373373,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 3.2790392485649136,
			"height": 0.9368658039858246,
			"seed": 569189305,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223437,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-0.9368836732146519,
					0
				],
				[
					-1.8737316079716493,
					0.4684418366073828
				],
				[
					-2.3421555753500343,
					0.9368658039858246
				],
				[
					-3.2790392485649136,
					0.9368658039858246
				],
				[
					0,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0078125,
				0.19921875,
				0.3173828125,
				0.31640625,
				0.2333984375,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 272,
			"versionNonce": 1385171716,
			"isDeleted": false,
			"id": "Z6mFBLgN8Cf26Ey2v9WLV",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1632.2819378185482,
			"y": -162.75093280072997,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 7.026466726050387,
			"seed": 953483065,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223437,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					3.2790035101070316
				],
				[
					0,
					5.152735118078681
				],
				[
					0,
					6.089600922064562
				],
				[
					0,
					7.026466726050387
				],
				[
					0,
					7.026466726050387
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0,
				0.19140625,
				0.1767578125,
				0.078125,
				0.0185546875,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 292,
			"versionNonce": 1720522556,
			"isDeleted": false,
			"id": "VObofdLtkqOgNHTL-z_o-",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1623.381739484526,
			"y": -151.50859676058678,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 5.621159085457066,
			"height": 7.494890693428829,
			"seed": 2043144247,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223437,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.468423967378385,
					2.8105974119575308
				],
				[
					0.468423967378385,
					3.7474453467144144
				],
				[
					0.468423967378385,
					4.215887183321797
				],
				[
					0.468423967378385,
					3.7474453467144144
				],
				[
					0.93684793475677,
					2.342155575350091
				],
				[
					1.405271902135155,
					0.9368658039858815
				],
				[
					1.8737316079716493,
					0
				],
				[
					2.3421555753500343,
					-1.4052897713642665
				],
				[
					2.8105795427286466,
					-2.342155575350091
				],
				[
					3.7474274774854166,
					-2.342155575350091
				],
				[
					4.2158871833216836,
					-2.81057954272859
				],
				[
					4.6843111507000685,
					-2.342155575350091
				],
				[
					4.2158871833216836,
					-0.46842396737844183
				],
				[
					3.7474274774854166,
					0
				],
				[
					3.7474274774854166,
					0.4684418366073828
				],
				[
					4.2158871833216836,
					0.4684418366073828
				],
				[
					5.152735118078681,
					0.4684418366073828
				],
				[
					5.621159085457066,
					1.4052897713642665
				],
				[
					5.621159085457066,
					1.8737316079717061
				],
				[
					4.6843111507000685,
					2.8105974119575308
				],
				[
					3.7474274774854166,
					3.7474453467144144
				],
				[
					2.3421555753500343,
					4.215887183321797
				],
				[
					1.405271902135155,
					4.684311150700239
				],
				[
					0.93684793475677,
					4.684311150700239
				],
				[
					0.93684793475677,
					4.684311150700239
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0009765625,
				0.205078125,
				0.2294921875,
				0.2275390625,
				0.1494140625,
				0.1298828125,
				0.1396484375,
				0.1474609375,
				0.15234375,
				0.154296875,
				0.1552734375,
				0.158203125,
				0.1630859375,
				0.1689453125,
				0.1728515625,
				0.1748046875,
				0.171875,
				0.1669921875,
				0.1708984375,
				0.1748046875,
				0.193359375,
				0.2041015625,
				0.20703125,
				0.1962890625,
				0.177734375,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 272,
			"versionNonce": 1709181572,
			"isDeleted": false,
			"id": "OlnLpaUJvzMNYH_FAOgen",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1631.3450541453335,
			"y": -147.292709577265,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 4.215869314092856,
			"seed": 1163058713,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223437,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					1.8737137387427651
				],
				[
					0,
					2.81057954272859
				],
				[
					0,
					4.215869314092856
				],
				[
					0,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0078125,
				0.15234375,
				0.1201171875,
				0.0087890625,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 283,
			"versionNonce": 1876873148,
			"isDeleted": false,
			"id": "JNoMkB1xF-uKY1xSaMDk3",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1625.2554710924974,
			"y": -141.67153262257898,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 6.089618791293333,
			"height": 6.558042758671888,
			"seed": 1229110103,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223437,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.468423967378385,
					-0.4684418366073828
				],
				[
					0,
					0
				],
				[
					-0.9368836732148793,
					0.46842396737844183
				],
				[
					-1.8737316079716493,
					1.4052897713643233
				],
				[
					-2.3421555753500343,
					2.342155575350148
				],
				[
					-2.810615281186301,
					3.2790035101070316
				],
				[
					-3.2790392485649136,
					3.7474453467143576
				],
				[
					-3.2790392485649136,
					4.215869314092856
				],
				[
					-2.810615281186301,
					5.152735118078681
				],
				[
					-2.3421555753500343,
					5.621159085457123
				],
				[
					-0.9368836732148793,
					6.0896009220645055
				],
				[
					0,
					5.621159085457123
				],
				[
					1.4052719021353823,
					5.621159085457123
				],
				[
					2.3421555753500343,
					4.684311150700239
				],
				[
					2.8105795427284193,
					4.215869314092856
				],
				[
					2.8105795427284193,
					4.215869314092856
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0029296875,
				0.171875,
				0.39453125,
				0.4189453125,
				0.4306640625,
				0.4501953125,
				0.501953125,
				0.5205078125,
				0.537109375,
				0.541015625,
				0.5283203125,
				0.4208984375,
				0.33203125,
				0.2041015625,
				0.0810546875,
				0.0302734375,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 274,
			"versionNonce": 503585284,
			"isDeleted": false,
			"id": "W_4kWFGo7Zo7dsrReSIzE",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1629.471322537362,
			"y": -139.79781888383627,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 0.9368479347569973,
			"height": 5.6211769546861206,
			"seed": 2090209655,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223437,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					0.46844183660743965
				],
				[
					0,
					0.9368658039858246
				],
				[
					-0.46842396737861236,
					1.8737316079716493
				],
				[
					-0.46842396737861236,
					3.2790213793359726
				],
				[
					-0.9368479347569973,
					4.684311150700239
				],
				[
					-0.46842396737861236,
					5.6211769546861206
				],
				[
					-0.46842396737861236,
					5.6211769546861206
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.005859375,
				0.189453125,
				0.2080078125,
				0.2099609375,
				0.169921875,
				0.0634765625,
				0.0029296875,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 277,
			"versionNonce": 1197832252,
			"isDeleted": false,
			"id": "ads5ndooy_8F8YlAt2r3Z",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1623.8501634519048,
			"y": -130.89762054981418,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 0.93684793475677,
			"height": 7.494890693428772,
			"seed": 1486889209,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223437,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.468423967378385,
					1.8737137387427651
				],
				[
					0.468423967378385,
					2.81057954272859
				],
				[
					0.93684793475677,
					4.215869314092856
				],
				[
					0.468423967378385,
					5.152735118078681
				],
				[
					0.468423967378385,
					5.621176954686064
				],
				[
					0.468423967378385,
					6.558024889442947
				],
				[
					0.468423967378385,
					7.494890693428772
				],
				[
					0.468423967378385,
					7.026466726050387
				],
				[
					0.468423967378385,
					6.558024889442947
				],
				[
					0.468423967378385,
					6.558024889442947
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0,
				0.1845703125,
				0.216796875,
				0.2548828125,
				0.259765625,
				0.2578125,
				0.23828125,
				0.1787109375,
				0.0224609375,
				0.0009765625,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 281,
			"versionNonce": 1710897540,
			"isDeleted": false,
			"id": "oduXJxv24JRqjomE8BS6E",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1626.192319027255,
			"y": -133.23977612516433,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 5.152735118078681,
			"height": 13.116085517343834,
			"seed": 1957384761,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223437,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.468423967378385,
					-0.46844183660743965
				],
				[
					1.873731607971422,
					0.9368658039858246
				],
				[
					1.873731607971422,
					1.8737137387427083
				],
				[
					2.3421555753500343,
					2.810579542728533
				],
				[
					2.8105795427284193,
					3.7474453467143576
				],
				[
					2.8105795427284193,
					5.621176954686007
				],
				[
					2.3421555753500343,
					7.02646672605033
				],
				[
					1.405307640593037,
					8.900180464793038
				],
				[
					0.468423967378385,
					9.837046268778863
				],
				[
					-1.4053076405934917,
					11.710777876750512
				],
				[
					-1.8737316079718767,
					12.647643680736394
				],
				[
					-2.3421555753502616,
					12.647643680736394
				],
				[
					-2.3421555753502616,
					11.710777876750512
				],
				[
					-2.3421555753502616,
					11.710777876750512
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.00390625,
				0.0166015625,
				0.2236328125,
				0.251953125,
				0.2666015625,
				0.275390625,
				0.28515625,
				0.29296875,
				0.294921875,
				0.2939453125,
				0.232421875,
				0.17578125,
				0.1484375,
				0.0029296875,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 273,
			"versionNonce": 956502204,
			"isDeleted": false,
			"id": "fMUCXZsu42ApiI4PxDvdc",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1630.8766301779547,
			"y": -124.80801962774967,
			"strokeColor": "#5f3dc4",
			"backgroundColor": "transparent",
			"width": 1.405307640593037,
			"height": 7.963332530036212,
			"seed": 2080033081,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223437,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-0.468423967378385,
					2.81057954272859
				],
				[
					-0.468423967378385,
					4.215887183321797
				],
				[
					-0.93684793475677,
					5.621176954686064
				],
				[
					-0.93684793475677,
					7.026466726050387
				],
				[
					-1.405307640593037,
					7.963332530036212
				],
				[
					-1.405307640593037,
					7.963332530036212
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0,
				0.181640625,
				0.1904296875,
				0.171875,
				0.076171875,
				0.0029296875,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 272,
			"versionNonce": 419457284,
			"isDeleted": false,
			"id": "Wji05JL2UA7WYUlUwE_f8",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1481.9155212903038,
			"y": -188.5146485968885,
			"strokeColor": "#364fc7",
			"backgroundColor": "transparent",
			"width": 0.9368836732148793,
			"height": 0.9368613366785894,
			"seed": 975430841,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223437,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-0.4684597058364943,
					0
				],
				[
					-0.4684597058364943,
					0.4684284346856771
				],
				[
					-0.9368836732148793,
					0.9368613366785894
				],
				[
					0,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0009765625,
				0.0458984375,
				0.08984375,
				0.0576171875,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 300,
			"versionNonce": 1146722620,
			"isDeleted": false,
			"id": "AgFzei06fkZcYQ_ekEAjS",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1480.5102136497112,
			"y": -187.5777872602098,
			"strokeColor": "#364fc7",
			"backgroundColor": "transparent",
			"width": 8.431738628185713,
			"height": 10.305483638079068,
			"seed": 1107503799,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223437,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.468423967378385,
					-0.4684329019929123
				],
				[
					0.468423967378385,
					-0.9368613366785894
				],
				[
					0.468423967378385,
					-1.4052942386715017
				],
				[
					0.468423967378385,
					-0.9368613366785894
				],
				[
					0,
					0
				],
				[
					0,
					1.4052942386715017
				],
				[
					-0.9368479347569973,
					2.810584010035825
				],
				[
					-1.8737316079716493,
					4.684311150700239
				],
				[
					-2.3421555753502616,
					6.558033824057418
				],
				[
					-2.8105795427286466,
					7.494895160736064
				],
				[
					-2.8105795427286466,
					8.900189399407566
				],
				[
					-3.2790035101070316,
					8.900189399407566
				],
				[
					-2.8105795427286466,
					8.431760964721889
				],
				[
					-2.3421555753502616,
					7.02646672605033
				],
				[
					-1.4053076405932643,
					5.152739585385916
				],
				[
					-0.468423967378385,
					3.7474498140216497
				],
				[
					0,
					2.342155575350148
				],
				[
					1.4053076405932643,
					0.4684284346856771
				],
				[
					1.8737316079716493,
					-0.4684329019929123
				],
				[
					2.8105795427286466,
					-0.9368613366785894
				],
				[
					2.8105795427286466,
					-1.4052942386715017
				],
				[
					3.2790035101070316,
					-1.4052942386715017
				],
				[
					3.7474632159432986,
					-0.9368613366785894
				],
				[
					3.7474632159432986,
					0
				],
				[
					3.7474632159432986,
					1.4052942386715017
				],
				[
					4.2158871833216836,
					2.810584010035825
				],
				[
					4.2158871833216836,
					4.215878248707327
				],
				[
					4.2158871833216836,
					5.152739585385916
				],
				[
					4.684311150700296,
					6.089605389371741
				],
				[
					4.684311150700296,
					6.558033824057418
				],
				[
					4.684311150700296,
					7.494895160736064
				],
				[
					5.152735118078681,
					7.02646672605033
				],
				[
					5.152735118078681,
					7.02646672605033
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0,
				0.115234375,
				0.197265625,
				0.2880859375,
				0.3525390625,
				0.421875,
				0.4306640625,
				0.43359375,
				0.431640625,
				0.4345703125,
				0.435546875,
				0.435546875,
				0.435546875,
				0.435546875,
				0.4345703125,
				0.4345703125,
				0.435546875,
				0.4365234375,
				0.439453125,
				0.451171875,
				0.46484375,
				0.46875,
				0.513671875,
				0.55859375,
				0.5712890625,
				0.5791015625,
				0.5791015625,
				0.5751953125,
				0.5517578125,
				0.4716796875,
				0.390625,
				0.259765625,
				0.0107421875,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 275,
			"versionNonce": 2056562820,
			"isDeleted": false,
			"id": "_TMWUN4yEqgmNL36Jvah6",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1485.1945248004108,
			"y": -184.29877034818105,
			"strokeColor": "#364fc7",
			"backgroundColor": "transparent",
			"width": 3.747463215943526,
			"height": 1.4052942386715017,
			"seed": 760151833,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223437,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-0.9368479347569973,
					-0.4684329019929123
				],
				[
					-1.4053076405932643,
					-0.4684329019929123
				],
				[
					-2.3421555753502616,
					-0.4684329019929123
				],
				[
					-2.8105795427286466,
					0
				],
				[
					-3.2790035101070316,
					0.4684329019929123
				],
				[
					-3.747463215943526,
					0.9368613366785894
				],
				[
					0,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0068359375,
				0.2431640625,
				0.330078125,
				0.349609375,
				0.341796875,
				0.2548828125,
				0.142578125,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 281,
			"versionNonce": 617288124,
			"isDeleted": false,
			"id": "QLgtjcTQTX1cvdrmIUfoY",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1490.3472599184902,
			"y": -183.36190901150258,
			"strokeColor": "#364fc7",
			"backgroundColor": "transparent",
			"width": 3.747463215943526,
			"height": 5.152744052693151,
			"seed": 640642937,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223437,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-0.9368479347569973,
					1.873727140664414
				],
				[
					-0.9368479347569973,
					2.342155575350091
				],
				[
					-1.4052719021353823,
					2.8105884773430034
				],
				[
					-1.8737316079718767,
					3.2790169120287374
				],
				[
					-1.8737316079718767,
					4.684311150700239
				],
				[
					-1.4052719021353823,
					4.684311150700239
				],
				[
					-0.9368479347569973,
					5.152744052693151
				],
				[
					-0.46842396737861236,
					5.152744052693151
				],
				[
					0.468423967378385,
					5.152744052693151
				],
				[
					1.405307640593037,
					5.152744052693151
				],
				[
					1.8737316079716493,
					5.152744052693151
				],
				[
					1.405307640593037,
					5.152744052693151
				],
				[
					1.8737316079716493,
					5.152744052693151
				],
				[
					1.8737316079716493,
					5.152744052693151
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0048828125,
				0.2080078125,
				0.2236328125,
				0.2314453125,
				0.232421875,
				0.2734375,
				0.3037109375,
				0.3154296875,
				0.3203125,
				0.3291015625,
				0.330078125,
				0.328125,
				0.181640625,
				0.140625,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 304,
			"versionNonce": 779417604,
			"isDeleted": false,
			"id": "6hZPjao__eklASW3r9wH8",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1481.9155212903038,
			"y": -59.22766351794644,
			"strokeColor": "#364fc7",
			"backgroundColor": "transparent",
			"width": 6.08961879129356,
			"height": 9.837064138007861,
			"seed": 1033741945,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223437,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					0.4684418366073828
				],
				[
					0,
					1.405289771364295
				],
				[
					0,
					1.8737316079716777
				],
				[
					0,
					3.2790213793359726
				],
				[
					-0.4684597058364943,
					4.215887183321797
				],
				[
					-0.4684597058364943,
					5.152752987307622
				],
				[
					-0.9368836732148793,
					6.089600922064534
				],
				[
					-0.9368836732148793,
					6.558042758671917
				],
				[
					-0.9368836732148793,
					7.026466726050359
				],
				[
					-0.9368836732148793,
					6.089600922064534
				],
				[
					-0.4684597058364943,
					4.684311150700239
				],
				[
					0.468423967378385,
					3.2790213793359726
				],
				[
					0.93684793475677,
					2.3421555753501195
				],
				[
					1.4052719021353823,
					1.405289771364295
				],
				[
					2.8105795427284193,
					0.9368658039858531
				],
				[
					3.2790035101070316,
					0.4684418366073828
				],
				[
					3.7474274774854166,
					0.4684418366073828
				],
				[
					3.7474274774854166,
					0.9368658039858531
				],
				[
					3.2790035101070316,
					1.8737316079716777
				],
				[
					3.2790035101070316,
					2.8105974119575023
				],
				[
					2.8105795427284193,
					3.7474453467144144
				],
				[
					2.3421555753500343,
					4.215887183321797
				],
				[
					1.8736958695137673,
					3.7474453467144144
				],
				[
					2.3421555753500343,
					3.7474453467144144
				],
				[
					2.8105795427284193,
					3.7474453467144144
				],
				[
					3.2790035101070316,
					3.7474453467144144
				],
				[
					4.215851444863802,
					4.215887183321797
				],
				[
					4.684311150700296,
					5.152752987307622
				],
				[
					5.152735118078681,
					6.558042758671917
				],
				[
					4.684311150700296,
					7.026466726050359
				],
				[
					3.7474274774854166,
					7.963332530036183
				],
				[
					2.8105795427284193,
					8.900198334022036
				],
				[
					1.4052719021353823,
					9.837064138007861
				],
				[
					0.468423967378385,
					9.368622301400478
				],
				[
					-0.4684597058364943,
					9.368622301400478
				],
				[
					-0.4684597058364943,
					8.900198334022036
				],
				[
					-0.4684597058364943,
					8.900198334022036
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0087890625,
				0.291015625,
				0.3984375,
				0.423828125,
				0.4482421875,
				0.451171875,
				0.4521484375,
				0.4580078125,
				0.4619140625,
				0.4658203125,
				0.4619140625,
				0.462890625,
				0.4638671875,
				0.462890625,
				0.4638671875,
				0.462890625,
				0.4638671875,
				0.46484375,
				0.4658203125,
				0.46875,
				0.46875,
				0.4697265625,
				0.4677734375,
				0.4638671875,
				0.462890625,
				0.462890625,
				0.462890625,
				0.4638671875,
				0.46484375,
				0.46875,
				0.4677734375,
				0.4677734375,
				0.4697265625,
				0.4697265625,
				0.4609375,
				0.35546875,
				0.30859375,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 286,
			"versionNonce": 1501133372,
			"isDeleted": false,
			"id": "Da1qeu5nNNgY2Gqz5IZHC",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1490.3472599184902,
			"y": -53.13806259588182,
			"strokeColor": "#364fc7",
			"backgroundColor": "transparent",
			"width": 4.6843111507000685,
			"height": 7.4948906934288,
			"seed": 364003063,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223438,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.468423967378385,
					-0.46842396737847025
				],
				[
					0.9368836732146519,
					-0.46842396737847025
				],
				[
					1.405307640593037,
					-0.9368479347569121
				],
				[
					2.3421555753500343,
					-0.9368479347569121
				],
				[
					2.8105795427284193,
					0
				],
				[
					2.3421555753500343,
					0.9368658039858246
				],
				[
					2.3421555753500343,
					1.8737316079716493
				],
				[
					1.405307640593037,
					3.279021379335944
				],
				[
					0.468423967378385,
					4.684311150700211
				],
				[
					0,
					5.621176954686064
				],
				[
					0,
					6.0896187912934465
				],
				[
					0,
					6.558042758671888
				],
				[
					0.9368836732146519,
					6.0896187912934465
				],
				[
					1.405307640593037,
					6.0896187912934465
				],
				[
					2.8105795427284193,
					5.621176954686064
				],
				[
					3.7474632159432986,
					5.621176954686064
				],
				[
					4.2158871833216836,
					5.621176954686064
				],
				[
					4.6843111507000685,
					5.621176954686064
				],
				[
					4.6843111507000685,
					5.621176954686064
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0048828125,
				0.37109375,
				0.369140625,
				0.3671875,
				0.3740234375,
				0.38671875,
				0.412109375,
				0.4248046875,
				0.4296875,
				0.435546875,
				0.44140625,
				0.4501953125,
				0.48046875,
				0.509765625,
				0.509765625,
				0.474609375,
				0.337890625,
				0.1806640625,
				0.0390625,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 285,
			"versionNonce": 815748996,
			"isDeleted": false,
			"id": "XAL1fv8lFMwZTvB379DeZ",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1483.7892171598182,
			"y": 63.96973404085281,
			"strokeColor": "#364fc7",
			"backgroundColor": "transparent",
			"width": 6.08961879129356,
			"height": 6.558042758671888,
			"seed": 1099406521,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223438,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-0.468423967378385,
					0
				],
				[
					-0.9368479347569973,
					0.46842396737844183
				],
				[
					-1.8736958695137673,
					0.46842396737844183
				],
				[
					-2.8105795427286466,
					0.9368479347568837
				],
				[
					-3.2790035101070316,
					1.4052719021353823
				],
				[
					-3.7474274774854166,
					1.8737316079717061
				],
				[
					-4.215851444864029,
					2.81057954272859
				],
				[
					-4.684311150700296,
					3.7474274774854734
				],
				[
					-4.684311150700296,
					4.215887183321797
				],
				[
					-4.684311150700296,
					5.152735118078681
				],
				[
					-4.215851444864029,
					6.089583052835565
				],
				[
					-3.2790035101070316,
					6.089583052835565
				],
				[
					-2.3421555753502616,
					6.558042758671888
				],
				[
					-0.9368479347569973,
					6.089583052835565
				],
				[
					0.46845970583626695,
					6.089583052835565
				],
				[
					0.9368836732146519,
					6.089583052835565
				],
				[
					1.4053076405932643,
					6.089583052835565
				],
				[
					1.4053076405932643,
					6.089583052835565
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.00390625,
				0.171875,
				0.373046875,
				0.41796875,
				0.439453125,
				0.4423828125,
				0.4521484375,
				0.4921875,
				0.552734375,
				0.583984375,
				0.59765625,
				0.603515625,
				0.6015625,
				0.6015625,
				0.599609375,
				0.5458984375,
				0.44921875,
				0.1201171875,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 292,
			"versionNonce": 759616188,
			"isDeleted": false,
			"id": "rli6qSUyuehyT1JeGmF9c",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1489.4104119837325,
			"y": 67.24873755095985,
			"strokeColor": "#364fc7",
			"backgroundColor": "transparent",
			"width": 4.684311150700296,
			"height": 5.621194823915005,
			"seed": 993769849,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223438,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.9368479347569973,
					0
				],
				[
					1.4052719021353823,
					0
				],
				[
					1.8737316079716493,
					0
				],
				[
					2.3421555753500343,
					0
				],
				[
					2.3421555753500343,
					0.46842396737844183
				],
				[
					2.3421555753500343,
					0.9368836732147656
				],
				[
					1.8737316079716493,
					1.8737316079716493
				],
				[
					1.4052719021353823,
					2.342155575350091
				],
				[
					1.4052719021353823,
					3.2790392485648567
				],
				[
					0.9368479347569973,
					3.2790392485648567
				],
				[
					0.468423967378385,
					3.7474632159433554
				],
				[
					0.468423967378385,
					4.215887183321797
				],
				[
					0.468423967378385,
					4.684311150700239
				],
				[
					0.9368479347569973,
					4.684311150700239
				],
				[
					1.4052719021353823,
					4.684311150700239
				],
				[
					1.8737316079716493,
					5.152735118078681
				],
				[
					2.3421555753500343,
					5.152735118078681
				],
				[
					2.8105795427286466,
					5.621194823915005
				],
				[
					2.8105795427286466,
					5.152735118078681
				],
				[
					2.8105795427286466,
					5.621194823915005
				],
				[
					3.2790035101070316,
					5.621194823915005
				],
				[
					3.7474274774854166,
					5.621194823915005
				],
				[
					4.215887183321911,
					5.621194823915005
				],
				[
					4.684311150700296,
					5.621194823915005
				],
				[
					4.684311150700296,
					5.621194823915005
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0068359375,
				0.279296875,
				0.330078125,
				0.345703125,
				0.3466796875,
				0.3505859375,
				0.3818359375,
				0.40625,
				0.4111328125,
				0.41796875,
				0.421875,
				0.4580078125,
				0.4736328125,
				0.529296875,
				0.533203125,
				0.5537109375,
				0.5751953125,
				0.59375,
				0.6123046875,
				0.6171875,
				0.6171875,
				0.615234375,
				0.572265625,
				0.3916015625,
				0.0810546875,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 299,
			"versionNonce": 1297204996,
			"isDeleted": false,
			"id": "oRgsM0Swwl5qW5BKVjPya",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1485.6629487677897,
			"y": 184.82494028584404,
			"strokeColor": "#364fc7",
			"backgroundColor": "transparent",
			"width": 6.089583052835678,
			"height": 11.242318170914245,
			"seed": 1353486647,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223438,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					0.4684597058363238
				],
				[
					0,
					0.9368836732148225
				],
				[
					0.468423967378385,
					1.4053076405932643
				],
				[
					0.468423967378385,
					2.342155575350148
				],
				[
					0,
					3.7474632159433554
				],
				[
					0,
					5.152770856536563
				],
				[
					-0.468423967378385,
					6.558042758671945
				],
				[
					-0.9368479347569973,
					7.026466726050387
				],
				[
					-0.9368479347569973,
					6.558042758671945
				],
				[
					-0.9368479347569973,
					5.621194823915005
				],
				[
					-0.468423967378385,
					4.215887183321797
				],
				[
					0,
					2.342155575350148
				],
				[
					0.468423967378385,
					1.4053076405932643
				],
				[
					0.9368836732148793,
					0
				],
				[
					1.8737316079716493,
					-1.4052719021353255
				],
				[
					2.3421555753500343,
					-1.8736958695137673
				],
				[
					2.8105795427284193,
					-1.8736958695137673
				],
				[
					3.2790392485649136,
					-1.8736958695137673
				],
				[
					4.2158871833216836,
					-1.4052719021353255
				],
				[
					4.684311150700296,
					-0.46842396737844183
				],
				[
					5.152735118078681,
					0.9368836732148225
				],
				[
					5.152735118078681,
					3.7474632159433554
				],
				[
					4.684311150700296,
					5.621194823915005
				],
				[
					3.7474632159432986,
					7.026466726050387
				],
				[
					2.8105795427284193,
					8.431774366643594
				],
				[
					2.3421555753500343,
					8.900198334022036
				],
				[
					1.4053076405932643,
					9.368622301400478
				],
				[
					0.9368836732148793,
					9.368622301400478
				],
				[
					0.468423967378385,
					9.368622301400478
				],
				[
					0.468423967378385,
					8.900198334022036
				],
				[
					0.9368836732148793,
					8.900198334022036
				],
				[
					0.9368836732148793,
					8.900198334022036
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0068359375,
				0.3447265625,
				0.4609375,
				0.53125,
				0.603515625,
				0.61328125,
				0.615234375,
				0.5947265625,
				0.5029296875,
				0.2138671875,
				0.150390625,
				0.0546875,
				0.029296875,
				0.029296875,
				0.0498046875,
				0.1337890625,
				0.1533203125,
				0.18359375,
				0.212890625,
				0.29296875,
				0.3359375,
				0.3720703125,
				0.39453125,
				0.4013671875,
				0.40234375,
				0.4013671875,
				0.400390625,
				0.3798828125,
				0.357421875,
				0.2861328125,
				0.14453125,
				0.0126953125,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 285,
			"versionNonce": 1054153532,
			"isDeleted": false,
			"id": "JXtH9yDNun4HKwm_6NFL8",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1494.5631471018119,
			"y": 190.91455907713748,
			"strokeColor": "#364fc7",
			"backgroundColor": "transparent",
			"width": 6.08961879129356,
			"height": 5.621159085457123,
			"seed": 184042583,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223438,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.468423967378385,
					-0.4684239673784987
				],
				[
					0.93684793475677,
					-0.4684239673784987
				],
				[
					1.8737316079716493,
					-0.9368479347569405
				],
				[
					2.3421555753502616,
					-0.9368479347569405
				],
				[
					3.2790035101070316,
					-0.4684239673784987
				],
				[
					3.2790035101070316,
					0.46842396737844183
				],
				[
					2.8105795427286466,
					1.8737316079716493
				],
				[
					2.3421555753502616,
					2.342155575350091
				],
				[
					1.4053076405932643,
					3.7474632159432986
				],
				[
					0.468423967378385,
					4.684311150700182
				],
				[
					0.93684793475677,
					4.684311150700182
				],
				[
					1.8737316079716493,
					4.684311150700182
				],
				[
					2.8105795427286466,
					4.21588718332174
				],
				[
					4.2158871833216836,
					4.21588718332174
				],
				[
					5.152735118078681,
					3.7474632159432986
				],
				[
					5.621159085457066,
					4.21588718332174
				],
				[
					6.08961879129356,
					4.21588718332174
				],
				[
					6.08961879129356,
					4.21588718332174
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.001953125,
				0.193359375,
				0.2802734375,
				0.326171875,
				0.328125,
				0.3291015625,
				0.34765625,
				0.376953125,
				0.3828125,
				0.3876953125,
				0.3935546875,
				0.423828125,
				0.427734375,
				0.42578125,
				0.390625,
				0.2646484375,
				0.0732421875,
				0.0380859375,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 295,
			"versionNonce": 420103812,
			"isDeleted": false,
			"id": "7BPpZY7UIhThquDiMWdBD",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1632.2819020800903,
			"y": -96.70215272354824,
			"strokeColor": "#364fc7",
			"backgroundColor": "transparent",
			"width": 14.98978138685743,
			"height": 16.39508902745081,
			"seed": 1737811321,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223438,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-0.468423967378385,
					-0.9368658039858815
				],
				[
					0,
					-1.4052897713642665
				],
				[
					0.468423967378385,
					-2.342155575350091
				],
				[
					0.468423967378385,
					-2.81057954272859
				],
				[
					1.405271902135155,
					-3.7474453467144144
				],
				[
					2.3421555753500343,
					-4.684311150700239
				],
				[
					3.7474274774854166,
					-5.152735118078681
				],
				[
					5.152735118078681,
					-5.152735118078681
				],
				[
					6.089583052835678,
					-5.152735118078681
				],
				[
					7.494890693428715,
					-4.215869314092856
				],
				[
					7.9633146608071,
					-2.81057954272859
				],
				[
					7.494890693428715,
					-1.4052897713642665
				],
				[
					7.02646672605033,
					0.9368658039858246
				],
				[
					5.621159085457066,
					3.7474453467144144
				],
				[
					4.6843111507000685,
					6.558042758671888
				],
				[
					3.2790035101070316,
					8.431756497414597
				],
				[
					2.3421555753500343,
					9.837064138007861
				],
				[
					2.3421555753500343,
					10.773912072764745
				],
				[
					2.3421555753500343,
					11.242353909372127
				],
				[
					3.2790035101070316,
					11.242353909372127
				],
				[
					4.6843111507000685,
					10.773912072764745
				],
				[
					7.02646672605033,
					10.305488105386246
				],
				[
					9.837046268778977,
					9.837064138007861
				],
				[
					11.710777876750399,
					8.900198334022036
				],
				[
					13.116049778886008,
					8.431756497414597
				],
				[
					14.05293345210066,
					7.963332530036155
				],
				[
					14.521357419479045,
					7.963332530036155
				],
				[
					14.05293345210066,
					8.431756497414597
				],
				[
					13.584509484722275,
					9.837064138007861
				],
				[
					13.584509484722275,
					10.773912072764745
				],
				[
					13.584509484722275,
					10.773912072764745
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0,
				0.1513671875,
				0.16015625,
				0.1728515625,
				0.1875,
				0.2490234375,
				0.326171875,
				0.392578125,
				0.431640625,
				0.4765625,
				0.501953125,
				0.505859375,
				0.5068359375,
				0.5078125,
				0.5126953125,
				0.517578125,
				0.521484375,
				0.52734375,
				0.5537109375,
				0.6240234375,
				0.65234375,
				0.6865234375,
				0.7275390625,
				0.7490234375,
				0.740234375,
				0.7353515625,
				0.7294921875,
				0.662109375,
				0.3291015625,
				0.0927734375,
				0.0048828125,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 288,
			"versionNonce": 143020988,
			"isDeleted": false,
			"id": "4yj5Ca7P3MLPMvdH2bN4X",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1479.1049060091177,
			"y": -164.62466440870162,
			"strokeColor": "#1864ab",
			"backgroundColor": "transparent",
			"width": 8.90019833402198,
			"height": 9.83705520339339,
			"seed": 729644183,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223438,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.46845970583626695,
					0
				],
				[
					0.46845970583626695,
					-0.4684329019929123
				],
				[
					0.9368836732148793,
					-1.4052897713642665
				],
				[
					0.9368836732148793,
					-2.342155575350091
				],
				[
					1.8737316079716493,
					-3.7474453467143576
				],
				[
					2.3421555753500343,
					-5.1527440526930945
				],
				[
					2.8106152811865286,
					-6.0896009220645055
				],
				[
					3.2790392485649136,
					-7.4948996280432425
				],
				[
					4.215887183321911,
					-8.900189399407509
				],
				[
					4.215887183321911,
					-9.368622301400421
				],
				[
					4.684311150700296,
					-9.83705520339339
				],
				[
					5.152770856536563,
					-9.368622301400421
				],
				[
					5.621194823914948,
					-8.900189399407509
				],
				[
					6.08961879129356,
					-7.963323595421684
				],
				[
					6.558042758671945,
					-6.558033824057418
				],
				[
					7.02646672605033,
					-4.684311150700239
				],
				[
					7.4949264318868245,
					-3.7474453467143576
				],
				[
					7.9633503992652095,
					-2.342155575350091
				],
				[
					8.431774366643594,
					-1.4052897713642665
				],
				[
					8.431774366643594,
					-0.9368568693713542
				],
				[
					8.90019833402198,
					-1.4052897713642665
				],
				[
					8.90019833402198,
					-1.8737226733571788
				],
				[
					8.90019833402198,
					-2.342155575350091
				],
				[
					8.90019833402198,
					-2.342155575350091
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.00390625,
				0.4033203125,
				0.42578125,
				0.4404296875,
				0.453125,
				0.49609375,
				0.546875,
				0.5693359375,
				0.580078125,
				0.5810546875,
				0.58203125,
				0.583984375,
				0.599609375,
				0.6181640625,
				0.6318359375,
				0.6357421875,
				0.6376953125,
				0.6376953125,
				0.625,
				0.5625,
				0.435546875,
				0.1455078125,
				0.08203125,
				0.0107421875,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 273,
			"versionNonce": 1753667076,
			"isDeleted": false,
			"id": "LuKs8bCZwCGDthQzd0cHx",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1487.0682564083831,
			"y": -169.77740846139477,
			"strokeColor": "#1864ab",
			"backgroundColor": "transparent",
			"width": 4.684311150700296,
			"height": 0.4684329019928555,
			"seed": 1445910327,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223438,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-1.4053076405932643,
					0
				],
				[
					-1.8737316079716493,
					0.4684329019928555
				],
				[
					-2.8105795427286466,
					0.4684329019928555
				],
				[
					-3.7474632159432986,
					0.4684329019928555
				],
				[
					-4.215887183321911,
					0.4684329019928555
				],
				[
					-4.684311150700296,
					0.4684329019928555
				],
				[
					-4.215887183321911,
					0
				],
				[
					0,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0009765625,
				0.1611328125,
				0.2080078125,
				0.24609375,
				0.2470703125,
				0.2255859375,
				0.1640625,
				0.00390625,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 285,
			"versionNonce": 1752988732,
			"isDeleted": false,
			"id": "5pNzAlLxNIN2-MAmrBsTx",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1492.6894154938395,
			"y": -171.65113113475195,
			"strokeColor": "#1864ab",
			"backgroundColor": "transparent",
			"width": 5.621159085457066,
			"height": 9.368622301400478,
			"seed": 329328665,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223438,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.468423967378385,
					0
				],
				[
					0.9368836732148793,
					0
				],
				[
					1.4053076405932643,
					0
				],
				[
					1.8737316079716493,
					0.4684329019929123
				],
				[
					1.8737316079716493,
					0.9368658039858246
				],
				[
					1.8737316079716493,
					1.8737226733572356
				],
				[
					1.4053076405932643,
					2.8105884773430603
				],
				[
					0.9368836732148793,
					3.747454281328885
				],
				[
					0.468423967378385,
					4.684311150700239
				],
				[
					0,
					5.152744052693151
				],
				[
					0.468423967378385,
					5.621176954686064
				],
				[
					1.4053076405932643,
					5.621176954686064
				],
				[
					1.8737316079716493,
					6.089609856678976
				],
				[
					2.3421555753500343,
					6.558033824057418
				],
				[
					2.3421555753500343,
					7.02646672605033
				],
				[
					1.8737316079716493,
					7.4948996280432425
				],
				[
					-2.8105795427286466,
					9.368622301400478
				],
				[
					-3.2790035101070316,
					9.368622301400478
				],
				[
					-3.2790035101070316,
					8.900189399407566
				],
				[
					-2.3421555753500343,
					8.431765432029067
				],
				[
					-2.3421555753500343,
					8.431765432029067
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.00390625,
				0.1171875,
				0.3427734375,
				0.3759765625,
				0.380859375,
				0.3818359375,
				0.3876953125,
				0.400390625,
				0.4111328125,
				0.4140625,
				0.4150390625,
				0.42578125,
				0.4267578125,
				0.4267578125,
				0.4326171875,
				0.451171875,
				0.4609375,
				0.484375,
				0.455078125,
				0.1669921875,
				0.005859375,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 312,
			"versionNonce": 1220900228,
			"isDeleted": false,
			"id": "vRJj7_MRJ-7S0HE8keem-",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1480.9786376170891,
			"y": -43.300998457874016,
			"strokeColor": "#1864ab",
			"backgroundColor": "transparent",
			"width": 7.9633503992652095,
			"height": 11.71077787675057,
			"seed": 1836436055,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223438,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.468423967378385,
					-0.4684418366073828
				],
				[
					0.468423967378385,
					0
				],
				[
					0.468423967378385,
					0.46842396737844183
				],
				[
					0.468423967378385,
					1.8737137387427367
				],
				[
					0.468423967378385,
					3.279021379335944
				],
				[
					0.468423967378385,
					4.684311150700239
				],
				[
					0.468423967378385,
					6.0896009220645055
				],
				[
					0.468423967378385,
					7.026466726050359
				],
				[
					0.468423967378385,
					7.4948906934288
				],
				[
					0,
					7.026466726050359
				],
				[
					0,
					5.621176954686064
				],
				[
					0.468423967378385,
					3.7474453467144144
				],
				[
					0.9368836732148793,
					1.8737137387427367
				],
				[
					1.8737316079716493,
					0
				],
				[
					2.3421555753502616,
					-0.9368658039858246
				],
				[
					2.8105795427286466,
					-2.3421555753501195
				],
				[
					3.7474632159432986,
					-3.279021379335944
				],
				[
					4.684311150700296,
					-3.747445346714386
				],
				[
					5.621194823915175,
					-4.215887183321769
				],
				[
					6.558042758671945,
					-3.747445346714386
				],
				[
					7.02646672605033,
					-3.279021379335944
				],
				[
					7.02646672605033,
					-1.8737316079716777
				],
				[
					6.558042758671945,
					-0.9368658039858246
				],
				[
					6.08961879129356,
					0
				],
				[
					5.152735118078681,
					0.9368658039858246
				],
				[
					4.684311150700296,
					0.9368658039858246
				],
				[
					4.215887183321911,
					0.9368658039858246
				],
				[
					4.215887183321911,
					1.405289771364295
				],
				[
					4.215887183321911,
					0.9368658039858246
				],
				[
					4.684311150700296,
					0.9368658039858246
				],
				[
					5.152735118078681,
					0.9368658039858246
				],
				[
					5.621194823915175,
					0.9368658039858246
				],
				[
					6.08961879129356,
					0.9368658039858246
				],
				[
					7.02646672605033,
					1.405289771364295
				],
				[
					7.02646672605033,
					1.8737137387427367
				],
				[
					7.494890693428715,
					2.3421555753501195
				],
				[
					7.9633503992652095,
					3.279021379335944
				],
				[
					7.9633503992652095,
					3.7474453467144144
				],
				[
					7.494890693428715,
					4.215869314092856
				],
				[
					7.494890693428715,
					5.152735118078681
				],
				[
					6.558042758671945,
					6.0896009220645055
				],
				[
					5.621194823915175,
					6.558024889442976
				],
				[
					4.684311150700296,
					6.558024889442976
				],
				[
					3.7474632159432986,
					6.558024889442976
				],
				[
					3.2790392485649136,
					6.558024889442976
				],
				[
					3.2790392485649136,
					6.0896009220645055
				],
				[
					3.7474632159432986,
					6.0896009220645055
				],
				[
					3.7474632159432986,
					6.0896009220645055
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0009765625,
				0.0546875,
				0.3798828125,
				0.4189453125,
				0.4677734375,
				0.5224609375,
				0.5419921875,
				0.5458984375,
				0.5322265625,
				0.48046875,
				0.375,
				0.2666015625,
				0.2431640625,
				0.244140625,
				0.26171875,
				0.2802734375,
				0.2958984375,
				0.3056640625,
				0.31640625,
				0.33203125,
				0.3408203125,
				0.34375,
				0.3486328125,
				0.349609375,
				0.3505859375,
				0.3515625,
				0.3515625,
				0.3505859375,
				0.3505859375,
				0.3515625,
				0.3544921875,
				0.3564453125,
				0.3544921875,
				0.353515625,
				0.353515625,
				0.3544921875,
				0.35546875,
				0.357421875,
				0.357421875,
				0.359375,
				0.361328125,
				0.365234375,
				0.365234375,
				0.365234375,
				0.3564453125,
				0.33203125,
				0.103515625,
				0.009765625,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 285,
			"versionNonce": 681153724,
			"isDeleted": false,
			"id": "AckSrixr4_M-QWCGCaiAR",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1491.2841435917048,
			"y": -40.02197707853816,
			"strokeColor": "#1864ab",
			"backgroundColor": "transparent",
			"width": 4.215887183321911,
			"height": 6.089600922064534,
			"seed": 1826943607,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223438,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.4052719021353823,
					0.46842396737847025
				],
				[
					1.8736958695137673,
					0.46842396737847025
				],
				[
					1.8736958695137673,
					1.405289771364295
				],
				[
					1.4052719021353823,
					2.8105795427285614
				],
				[
					0.468423967378385,
					3.2790035101070316
				],
				[
					0.468423967378385,
					3.7474453467144144
				],
				[
					0,
					3.7474453467144144
				],
				[
					0.9368479347569973,
					3.7474453467144144
				],
				[
					1.4052719021353823,
					3.7474453467144144
				],
				[
					1.8736958695137673,
					4.215869314092856
				],
				[
					2.3421555753502616,
					4.215869314092856
				],
				[
					2.3421555753502616,
					4.684311150700239
				],
				[
					1.8736958695137673,
					5.152735118078681
				],
				[
					1.4052719021353823,
					5.621159085457123
				],
				[
					0.468423967378385,
					6.089600922064534
				],
				[
					-0.46845970583626695,
					6.089600922064534
				],
				[
					-0.9368836732146519,
					6.089600922064534
				],
				[
					-1.4053076405932643,
					5.621159085457123
				],
				[
					-1.8737316079716493,
					6.089600922064534
				],
				[
					-1.4053076405932643,
					6.089600922064534
				],
				[
					-1.4053076405932643,
					6.089600922064534
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0,
				0.296875,
				0.33984375,
				0.3564453125,
				0.37109375,
				0.3759765625,
				0.3759765625,
				0.376953125,
				0.41796875,
				0.419921875,
				0.4267578125,
				0.451171875,
				0.5400390625,
				0.55078125,
				0.5556640625,
				0.556640625,
				0.55859375,
				0.5615234375,
				0.4794921875,
				0.265625,
				0.19921875,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 285,
			"versionNonce": 1996760324,
			"isDeleted": false,
			"id": "ieb2txKxj_UjtIDVNlV4e",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1487.0682564083831,
			"y": 78.49109146033197,
			"strokeColor": "#1864ab",
			"backgroundColor": "transparent",
			"width": 7.9633503992652095,
			"height": 7.494890693428772,
			"seed": 195932697,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223438,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-0.468423967378385,
					0
				],
				[
					-0.9368836732148793,
					0
				],
				[
					-1.4053076405932643,
					0.46842396737844183
				],
				[
					-2.3421555753502616,
					0.9368479347568837
				],
				[
					-2.8105795427286466,
					1.4053076405932075
				],
				[
					-3.7474632159432986,
					1.8737316079716493
				],
				[
					-4.684311150700296,
					2.810579542728533
				],
				[
					-5.152735118078681,
					4.215887183321797
				],
				[
					-5.621194823915175,
					5.152735118078681
				],
				[
					-5.621194823915175,
					6.0896187912934465
				],
				[
					-5.152735118078681,
					6.558042758671888
				],
				[
					-5.152735118078681,
					7.02646672605033
				],
				[
					-4.215887183321911,
					7.494890693428772
				],
				[
					-2.8105795427286466,
					7.494890693428772
				],
				[
					-1.4053076405932643,
					7.02646672605033
				],
				[
					0,
					6.558042758671888
				],
				[
					0.93684793475677,
					5.621159085457123
				],
				[
					1.405271902135155,
					5.621159085457123
				],
				[
					1.8737316079716493,
					5.621159085457123
				],
				[
					2.3421555753500343,
					5.621159085457123
				],
				[
					2.3421555753500343,
					5.621159085457123
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.00390625,
				0.0439453125,
				0.3720703125,
				0.4130859375,
				0.4453125,
				0.466796875,
				0.501953125,
				0.5478515625,
				0.5673828125,
				0.5712890625,
				0.57421875,
				0.5732421875,
				0.57421875,
				0.57421875,
				0.5751953125,
				0.5732421875,
				0.544921875,
				0.4296875,
				0.330078125,
				0.171875,
				0.0380859375,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 283,
			"versionNonce": 109026620,
			"isDeleted": false,
			"id": "9fHiJe-Dv-budBF59p1Af",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1493.626299167055,
			"y": 78.49109146033197,
			"strokeColor": "#1864ab",
			"backgroundColor": "transparent",
			"width": 4.215887183321911,
			"height": 8.900198334022036,
			"seed": 845717591,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223438,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.405271902135155,
					0
				],
				[
					1.87369586951354,
					0.9368479347568837
				],
				[
					1.87369586951354,
					1.4053076405932075
				],
				[
					1.87369586951354,
					2.342155575350091
				],
				[
					1.405271902135155,
					2.810579542728533
				],
				[
					0.93684793475677,
					3.7474632159433554
				],
				[
					0.93684793475677,
					4.215887183321797
				],
				[
					1.405271902135155,
					4.684311150700239
				],
				[
					2.3421555753500343,
					5.152735118078681
				],
				[
					2.8105795427284193,
					5.621159085457123
				],
				[
					3.2790035101070316,
					6.558042758671888
				],
				[
					3.2790035101070316,
					7.02646672605033
				],
				[
					2.8105795427284193,
					7.963314660807214
				],
				[
					2.3421555753500343,
					8.431774366643538
				],
				[
					1.405271902135155,
					8.900198334022036
				],
				[
					-0.4684597058364943,
					8.431774366643538
				],
				[
					-0.9368836732148793,
					8.431774366643538
				],
				[
					-0.9368836732148793,
					7.963314660807214
				],
				[
					-0.9368836732148793,
					7.963314660807214
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0078125,
				0.2919921875,
				0.392578125,
				0.4072265625,
				0.396484375,
				0.3974609375,
				0.4013671875,
				0.4052734375,
				0.4072265625,
				0.4072265625,
				0.4072265625,
				0.4091796875,
				0.4111328125,
				0.416015625,
				0.423828125,
				0.4287109375,
				0.427734375,
				0.283203125,
				0.130859375,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 276,
			"versionNonce": 1489036420,
			"isDeleted": false,
			"id": "xBmtkCo_7YHNqjrN1i-UN",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1485.1945248004108,
			"y": 197.00417786843104,
			"strokeColor": "#1864ab",
			"backgroundColor": "transparent",
			"width": 0.9368479347569973,
			"height": 8.431738628185656,
			"seed": 1647524185,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223438,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					0.46842396737844183
				],
				[
					0,
					1.4052719021353255
				],
				[
					0.468423967378385,
					1.8736958695137673
				],
				[
					0.468423967378385,
					2.342155575350091
				],
				[
					0.468423967378385,
					3.2790035101069748
				],
				[
					0.468423967378385,
					4.215851444863858
				],
				[
					0.468423967378385,
					5.621159085457123
				],
				[
					0,
					7.02646672605033
				],
				[
					0,
					7.963314660807214
				],
				[
					-0.46842396737861236,
					8.431738628185656
				],
				[
					0,
					7.494890693428772
				],
				[
					0,
					7.494890693428772
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0009765625,
				0.162109375,
				0.359375,
				0.4384765625,
				0.494140625,
				0.5244140625,
				0.529296875,
				0.5302734375,
				0.525390625,
				0.486328125,
				0.34375,
				0.0205078125,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 282,
			"versionNonce": 999331260,
			"isDeleted": false,
			"id": "R_JV8poDPz2P7R93WkxDY",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1488.00510434314,
			"y": 195.59887022783778,
			"strokeColor": "#1864ab",
			"backgroundColor": "transparent",
			"width": 6.558042758671718,
			"height": 13.116049778885952,
			"seed": 717940601,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223438,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.9368836732148793,
					-0.46842396737844183
				],
				[
					1.8737316079716493,
					0.46842396737844183
				],
				[
					2.3421555753502616,
					0.9368479347569405
				],
				[
					3.2790392485649136,
					1.4053076405932643
				],
				[
					3.7474632159432986,
					1.8737316079717061
				],
				[
					3.7474632159432986,
					3.2790035101070316
				],
				[
					3.7474632159432986,
					4.684311150700239
				],
				[
					3.7474632159432986,
					6.0896187912934465
				],
				[
					3.2790392485649136,
					7.963314660807271
				],
				[
					1.8737316079716493,
					9.368622301400478
				],
				[
					0.468423967378385,
					11.242353909372127
				],
				[
					-0.93684793475677,
					12.179201844129068
				],
				[
					-1.8737316079716493,
					12.64762581150751
				],
				[
					-2.3421555753500343,
					12.64762581150751
				],
				[
					-2.8105795427284193,
					12.179201844129068
				],
				[
					-1.8737316079716493,
					11.242353909372127
				],
				[
					-1.405271902135155,
					11.242353909372127
				],
				[
					-1.405271902135155,
					11.242353909372127
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0,
				0.14453125,
				0.2431640625,
				0.2880859375,
				0.310546875,
				0.318359375,
				0.3330078125,
				0.34765625,
				0.3544921875,
				0.359375,
				0.3623046875,
				0.3623046875,
				0.3603515625,
				0.34765625,
				0.3251953125,
				0.162109375,
				0.0302734375,
				0.0009765625,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 290,
			"versionNonce": 1941550084,
			"isDeleted": false,
			"id": "Y1FJGAKa0U9bKPA925MgQ",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1496.4368787097833,
			"y": 202.15691298650972,
			"strokeColor": "#1864ab",
			"backgroundColor": "transparent",
			"width": 5.621159085457066,
			"height": 6.089583052835565,
			"seed": 1768199225,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223438,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.46842396737861236,
					0
				],
				[
					0.9368479347569973,
					0
				],
				[
					1.4052719021353823,
					0
				],
				[
					1.8737316079716493,
					0
				],
				[
					2.3421555753500343,
					0.46842396737844183
				],
				[
					2.3421555753500343,
					0.9368479347568837
				],
				[
					2.3421555753500343,
					1.4052719021353255
				],
				[
					1.8737316079716493,
					2.342155575350091
				],
				[
					0.9368479347569973,
					2.810579542728533
				],
				[
					0.46842396737861236,
					3.2790035101069748
				],
				[
					0,
					3.2790035101069748
				],
				[
					0.46842396737861236,
					3.2790035101069748
				],
				[
					0.9368479347569973,
					3.2790035101069748
				],
				[
					1.4052719021353823,
					3.2790035101069748
				],
				[
					1.8737316079716493,
					3.2790035101069748
				],
				[
					2.8105795427286466,
					3.7474274774854166
				],
				[
					2.8105795427286466,
					4.21588718332174
				],
				[
					3.2790035101070316,
					4.21588718332174
				],
				[
					2.8105795427286466,
					4.684311150700182
				],
				[
					1.8737316079716493,
					5.152735118078681
				],
				[
					0.9368479347569973,
					5.621159085457123
				],
				[
					-0.468423967378385,
					5.621159085457123
				],
				[
					-1.4053076405932643,
					5.621159085457123
				],
				[
					-2.3421555753500343,
					6.089583052835565
				],
				[
					-2.3421555753500343,
					5.621159085457123
				],
				[
					-2.3421555753500343,
					5.621159085457123
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0048828125,
				0.4873046875,
				0.533203125,
				0.5390625,
				0.5390625,
				0.5400390625,
				0.5439453125,
				0.54296875,
				0.5458984375,
				0.5458984375,
				0.5478515625,
				0.5498046875,
				0.5498046875,
				0.5517578125,
				0.5517578125,
				0.552734375,
				0.560546875,
				0.578125,
				0.5859375,
				0.5966796875,
				0.603515625,
				0.59765625,
				0.544921875,
				0.435546875,
				0.265625,
				0.001953125,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 293,
			"versionNonce": 82738748,
			"isDeleted": false,
			"id": "p8V195DZty8vUIoLtFycK",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1637.4346371981687,
			"y": -53.13806259588182,
			"strokeColor": "#1864ab",
			"backgroundColor": "transparent",
			"width": 10.305470236157362,
			"height": 15.926647190843426,
			"seed": 1752730745,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223438,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-0.46842396737861236,
					-0.46842396737847025
				],
				[
					0,
					-0.46842396737847025
				],
				[
					0.468423967378385,
					-0.46842396737847025
				],
				[
					1.8737316079716493,
					-0.9368479347569121
				],
				[
					3.7474632159432986,
					-0.46842396737847025
				],
				[
					5.152735118078681,
					-0.46842396737847025
				],
				[
					6.558042758671718,
					0.4684418366073828
				],
				[
					7.02646672605033,
					1.8737316079716493
				],
				[
					6.558042758671718,
					3.279021379335944
				],
				[
					5.621159085457066,
					4.684311150700211
				],
				[
					3.7474632159432986,
					6.558042758671888
				],
				[
					2.3421555753500343,
					7.02646672605033
				],
				[
					1.8737316079716493,
					7.494908562657713
				],
				[
					2.3421555753500343,
					7.494908562657713
				],
				[
					3.2790035101070316,
					7.494908562657713
				],
				[
					4.215887183321911,
					7.494908562657713
				],
				[
					5.621159085457066,
					7.963332530036155
				],
				[
					7.02646672605033,
					8.900198334022008
				],
				[
					7.494890693428715,
					9.36862230140045
				],
				[
					7.9633146608073275,
					9.837064138007833
				],
				[
					7.494890693428715,
					11.242353909372127
				],
				[
					6.558042758671718,
					13.116085517343777
				],
				[
					4.684311150700296,
					14.052933452100689
				],
				[
					2.8105795427284193,
					14.989799256086513
				],
				[
					0.9368479347569973,
					14.989799256086513
				],
				[
					0,
					14.521375288708072
				],
				[
					-1.4053076405932643,
					13.584509484722247
				],
				[
					-2.3421555753500343,
					13.116085517343777
				],
				[
					-2.3421555753500343,
					13.116085517343777
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0009765625,
				0.2568359375,
				0.52734375,
				0.609375,
				0.6240234375,
				0.6328125,
				0.646484375,
				0.666015625,
				0.677734375,
				0.6826171875,
				0.6826171875,
				0.68359375,
				0.6875,
				0.6875,
				0.69140625,
				0.6865234375,
				0.6845703125,
				0.685546875,
				0.6875,
				0.689453125,
				0.6943359375,
				0.701171875,
				0.712890625,
				0.7236328125,
				0.7265625,
				0.7236328125,
				0.703125,
				0.44140625,
				0.1396484375,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 284,
			"versionNonce": 1710003076,
			"isDeleted": false,
			"id": "fAbCh9pDYrKZ815-7IeGu",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1480.0417896823324,
			"y": -155.25604210730114,
			"strokeColor": "#0b7285",
			"backgroundColor": "transparent",
			"width": 7.494890693428715,
			"height": 10.305479170771832,
			"seed": 1557163127,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223438,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.468423967378385,
					-0.4684329019929123
				],
				[
					0.468423967378385,
					-1.4052897713642665
				],
				[
					0.93684793475677,
					-2.8105884773430603
				],
				[
					1.405271902135155,
					-4.215878248707327
				],
				[
					1.8737316079716493,
					-6.0896009220645055
				],
				[
					2.8105795427284193,
					-7.963323595421741
				],
				[
					3.2790035101070316,
					-8.900189399407566
				],
				[
					3.2790035101070316,
					-9.83705520339339
				],
				[
					3.7474274774854166,
					-10.305479170771832
				],
				[
					4.2158871833216836,
					-9.83705520339339
				],
				[
					4.6843111507000685,
					-9.83705520339339
				],
				[
					5.152735118078681,
					-8.431756497414597
				],
				[
					5.152735118078681,
					-7.02646672605033
				],
				[
					5.621159085457066,
					-5.152744052693151
				],
				[
					6.089583052835451,
					-3.7474453467144144
				],
				[
					6.558042758671945,
					-2.342155575350091
				],
				[
					7.02646672605033,
					-1.4052897713642665
				],
				[
					7.494890693428715,
					-0.9368568693713542
				],
				[
					7.494890693428715,
					-1.4052897713642665
				],
				[
					7.494890693428715,
					-1.4052897713642665
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.00390625,
				0.5791015625,
				0.626953125,
				0.6484375,
				0.6513671875,
				0.6640625,
				0.6669921875,
				0.6689453125,
				0.6708984375,
				0.685546875,
				0.720703125,
				0.7470703125,
				0.77734375,
				0.80078125,
				0.8203125,
				0.8369140625,
				0.833984375,
				0.8056640625,
				0.6689453125,
				0.1552734375,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 271,
			"versionNonce": 729503420,
			"isDeleted": false,
			"id": "WI7yjrr3Cj5wSEFIxuvpz",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1487.0682564083831,
			"y": -158.53505455202253,
			"strokeColor": "#0b7285",
			"backgroundColor": "transparent",
			"width": 3.2790392485649136,
			"height": 0.46843290199296916,
			"seed": 450757847,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223438,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-0.468423967378385,
					-0.46843290199296916
				],
				[
					-0.9368836732148793,
					-0.46843290199296916
				],
				[
					-1.8737316079716493,
					-0.46843290199296916
				],
				[
					-2.3421555753502616,
					-0.46843290199296916
				],
				[
					-3.2790392485649136,
					-0.46843290199296916
				],
				[
					0,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0029296875,
				0.08203125,
				0.197265625,
				0.2685546875,
				0.2724609375,
				0.2412109375,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 279,
			"versionNonce": 1570210564,
			"isDeleted": false,
			"id": "Scs_q1fMPI_zwnJ8c9hdh",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1492.6894154938395,
			"y": -159.94035325800132,
			"strokeColor": "#0b7285",
			"backgroundColor": "transparent",
			"width": 3.2790035101070316,
			"height": 4.215887183321797,
			"seed": 1131234201,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223438,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-0.4684329019929123
				],
				[
					0,
					0
				],
				[
					-0.468423967378385,
					0.4684329019929123
				],
				[
					-0.9368479347569973,
					1.4052987059787938
				],
				[
					-1.4052719021353823,
					1.8737226733571788
				],
				[
					-1.4052719021353823,
					2.8105884773430603
				],
				[
					-1.4052719021353823,
					3.2790213793359726
				],
				[
					-0.9368479347569973,
					3.747454281328885
				],
				[
					0,
					3.747454281328885
				],
				[
					0.468423967378385,
					3.747454281328885
				],
				[
					0.9368836732148793,
					3.747454281328885
				],
				[
					1.8737316079716493,
					3.2790213793359726
				],
				[
					1.8737316079716493,
					2.8105884773430603
				],
				[
					0,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.001953125,
				0.0341796875,
				0.3115234375,
				0.3544921875,
				0.3759765625,
				0.37890625,
				0.3916015625,
				0.404296875,
				0.4033203125,
				0.3369140625,
				0.2890625,
				0.1494140625,
				0.0283203125,
				0.0009765625,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 272,
			"versionNonce": 198778684,
			"isDeleted": false,
			"id": "kX1rlL-6uWd-JWxKzMxLQ",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1494.5631471018119,
			"y": -159.0034874540156,
			"strokeColor": "#0b7285",
			"backgroundColor": "transparent",
			"width": 0.93684793475677,
			"height": 6.558033824057475,
			"seed": 1365112695,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223438,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					1.8737226733572356
				],
				[
					0,
					2.342155575350148
				],
				[
					-0.468423967378385,
					3.279012444721502
				],
				[
					-0.468423967378385,
					4.215878248707327
				],
				[
					-0.468423967378385,
					5.152744052693151
				],
				[
					-0.93684793475677,
					6.0896009220645055
				],
				[
					-0.468423967378385,
					6.558033824057475
				],
				[
					-0.468423967378385,
					6.558033824057475
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0009765625,
				0.2265625,
				0.2744140625,
				0.31640625,
				0.3251953125,
				0.263671875,
				0.12890625,
				0.0087890625,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 304,
			"versionNonce": 288916100,
			"isDeleted": false,
			"id": "frGYVOVPh-wjBjn2OJyTD",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1482.3839452576826,
			"y": -32.99551035248771,
			"strokeColor": "#0b7285",
			"backgroundColor": "transparent",
			"width": 5.15277085653679,
			"height": 10.773929941993686,
			"seed": 918646039,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223438,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					0.9368479347568837
				],
				[
					0,
					1.4052897713642665
				],
				[
					0,
					2.8105795427285614
				],
				[
					0,
					4.684311150700239
				],
				[
					0,
					5.152735118078681
				],
				[
					0,
					6.0896009220645055
				],
				[
					-0.468423967378385,
					6.558024889442947
				],
				[
					0,
					4.215869314092828
				],
				[
					0,
					2.8105795427285614
				],
				[
					0.468423967378385,
					1.4052897713642665
				],
				[
					0.9368479347569973,
					0.46842396737844183
				],
				[
					0.9368479347569973,
					-0.4684418366073828
				],
				[
					1.4052719021353823,
					-0.9368658039858246
				],
				[
					1.8737316079716493,
					-1.4053076405932359
				],
				[
					2.3421555753500343,
					-0.9368658039858246
				],
				[
					3.2790035101070316,
					-0.9368658039858246
				],
				[
					3.7474274774854166,
					-0.4684418366073828
				],
				[
					4.215887183321911,
					0.46842396737844183
				],
				[
					4.215887183321911,
					1.4052897713642665
				],
				[
					3.7474274774854166,
					2.8105795427285614
				],
				[
					3.2790035101070316,
					3.747445346714386
				],
				[
					2.8105795427286466,
					4.215869314092828
				],
				[
					2.3421555753500343,
					4.684311150700239
				],
				[
					1.8737316079716493,
					4.684311150700239
				],
				[
					2.3421555753500343,
					5.152735118078681
				],
				[
					2.8105795427286466,
					5.152735118078681
				],
				[
					3.7474274774854166,
					5.621159085457123
				],
				[
					4.215887183321911,
					6.0896009220645055
				],
				[
					4.215887183321911,
					7.02646672605033
				],
				[
					4.215887183321911,
					7.4948906934288
				],
				[
					4.215887183321911,
					7.963314660807242
				],
				[
					3.7474274774854166,
					8.431756497414625
				],
				[
					2.8105795427286466,
					8.900180464793067
				],
				[
					1.4052719021353823,
					9.36862230140045
				],
				[
					0.468423967378385,
					9.36862230140045
				],
				[
					0,
					8.900180464793067
				],
				[
					-0.9368836732148793,
					8.900180464793067
				],
				[
					-0.468423967378385,
					7.963314660807242
				],
				[
					0,
					7.963314660807242
				],
				[
					0,
					7.963314660807242
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.001953125,
				0.275390625,
				0.337890625,
				0.4296875,
				0.509765625,
				0.5263671875,
				0.5478515625,
				0.55078125,
				0.255859375,
				0.2265625,
				0.2255859375,
				0.240234375,
				0.2607421875,
				0.310546875,
				0.3564453125,
				0.388671875,
				0.42578125,
				0.4501953125,
				0.4716796875,
				0.474609375,
				0.4765625,
				0.4755859375,
				0.4755859375,
				0.4736328125,
				0.4736328125,
				0.4638671875,
				0.4638671875,
				0.462890625,
				0.4638671875,
				0.466796875,
				0.46875,
				0.46875,
				0.4677734375,
				0.46875,
				0.46875,
				0.4638671875,
				0.443359375,
				0.2744140625,
				0.0458984375,
				0.0048828125,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 279,
			"versionNonce": 510252988,
			"isDeleted": false,
			"id": "iz4mZ66H_BYYoEWZGajXl",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1491.2841435917048,
			"y": -28.779641038394857,
			"strokeColor": "#0b7285",
			"backgroundColor": "transparent",
			"width": 3.747463215943526,
			"height": 3.747463215943327,
			"seed": 1823969463,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223438,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-0.46842396737844183
				],
				[
					0,
					-0.9368658039858246
				],
				[
					-0.46845970583626695,
					-0.46842396737844183
				],
				[
					-0.9368836732146519,
					0.46844183660741123
				],
				[
					-1.4053076405932643,
					0.9368658039858531
				],
				[
					-1.4053076405932643,
					1.8737316079716777
				],
				[
					-0.9368836732146519,
					2.3421555753501195
				],
				[
					-0.9368836732146519,
					2.8105974119575023
				],
				[
					-0.46845970583626695,
					2.3421555753501195
				],
				[
					0.468423967378385,
					1.8737316079716777
				],
				[
					0.9368479347569973,
					1.8737316079716777
				],
				[
					1.4052719021353823,
					1.8737316079716777
				],
				[
					2.3421555753502616,
					0.9368658039858531
				],
				[
					0,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0,
				0.025390625,
				0.2802734375,
				0.3212890625,
				0.36328125,
				0.3974609375,
				0.41796875,
				0.431640625,
				0.435546875,
				0.4228515625,
				0.373046875,
				0.3193359375,
				0.2177734375,
				0.013671875,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 271,
			"versionNonce": 932024836,
			"isDeleted": false,
			"id": "XkdVMzsPySx8a7w_Md74M",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1494.094723134433,
			"y": -29.248065005773356,
			"strokeColor": "#0b7285",
			"backgroundColor": "transparent",
			"width": 0.9368836732148793,
			"height": 7.026466726050359,
			"seed": 1857532217,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223438,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					1.8737137387427367
				],
				[
					0,
					2.8105795427285614
				],
				[
					0,
					3.7474453467144144
				],
				[
					-0.9368836732148793,
					5.621176954686064
				],
				[
					-0.9368836732148793,
					6.558024889442976
				],
				[
					-0.468423967378385,
					7.026466726050359
				],
				[
					-0.468423967378385,
					7.026466726050359
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.001953125,
				0.2490234375,
				0.2802734375,
				0.2880859375,
				0.23046875,
				0.1494140625,
				0.0234375,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 286,
			"versionNonce": 2135916604,
			"isDeleted": false,
			"id": "TflG5leLGYokQlkMwEj-9",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1485.1945248004108,
			"y": 92.54402491243263,
			"strokeColor": "#0b7285",
			"backgroundColor": "transparent",
			"width": 7.9633503992652095,
			"height": 8.431738628185713,
			"seed": 475936599,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223438,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-0.46842396737844183
				],
				[
					0,
					0
				],
				[
					-0.46842396737861236,
					0
				],
				[
					-1.4053076405932643,
					0
				],
				[
					-1.8737316079716493,
					0.4684239673784987
				],
				[
					-1.8737316079716493,
					0.9368479347569405
				],
				[
					-2.8105795427286466,
					1.8737316079717061
				],
				[
					-3.747463215943526,
					4.684311150700239
				],
				[
					-3.747463215943526,
					5.62115908545718
				],
				[
					-3.2790035101070316,
					6.558042758671945
				],
				[
					-2.8105795427286466,
					7.026466726050387
				],
				[
					-2.3421555753502616,
					7.494890693428829
				],
				[
					-1.8737316079716493,
					7.963314660807271
				],
				[
					-1.4053076405932643,
					7.963314660807271
				],
				[
					-0.9368479347569973,
					7.963314660807271
				],
				[
					0.468423967378385,
					7.494890693428829
				],
				[
					1.4053076405932643,
					7.026466726050387
				],
				[
					2.3421555753500343,
					5.62115908545718
				],
				[
					3.2790035101068042,
					5.152735118078681
				],
				[
					3.7474632159432986,
					5.152735118078681
				],
				[
					4.2158871833216836,
					5.62115908545718
				],
				[
					4.2158871833216836,
					5.62115908545718
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.001953125,
				0.2373046875,
				0.4482421875,
				0.509765625,
				0.564453125,
				0.5966796875,
				0.630859375,
				0.64453125,
				0.6474609375,
				0.6484375,
				0.6552734375,
				0.65625,
				0.6572265625,
				0.66015625,
				0.66015625,
				0.65625,
				0.6162109375,
				0.544921875,
				0.3896484375,
				0.2099609375,
				0.0869140625,
				0.009765625,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 278,
			"versionNonce": 2140451204,
			"isDeleted": false,
			"id": "dRVqOO22HZe6WiBsWXvIw",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1495.0315710691898,
			"y": 94.41775652040428,
			"strokeColor": "#0b7285",
			"backgroundColor": "transparent",
			"width": 4.684311150700296,
			"height": 4.684311150700239,
			"seed": 835046615,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223438,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-0.468423967378385,
					0.46842396737844183
				],
				[
					-0.93684793475677,
					1.4052719021353255
				],
				[
					-1.405271902135155,
					1.8737316079716493
				],
				[
					-1.8737316079716493,
					2.810579542728533
				],
				[
					-1.8737316079716493,
					3.2790035101069748
				],
				[
					-1.8737316079716493,
					4.215887183321797
				],
				[
					-1.405271902135155,
					4.684311150700239
				],
				[
					-0.468423967378385,
					4.684311150700239
				],
				[
					0,
					4.684311150700239
				],
				[
					0.9368836732148793,
					4.684311150700239
				],
				[
					1.8737316079718767,
					4.215887183321797
				],
				[
					2.8105795427286466,
					3.7474274774854734
				],
				[
					0,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.00390625,
				0.294921875,
				0.3408203125,
				0.3505859375,
				0.3681640625,
				0.3798828125,
				0.3984375,
				0.3994140625,
				0.359375,
				0.3193359375,
				0.1904296875,
				0.0927734375,
				0.0107421875,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 274,
			"versionNonce": 1986795708,
			"isDeleted": false,
			"id": "SrUvhVOq92Wup9cgokwXv",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1499.2474582525115,
			"y": 93.9493325530259,
			"strokeColor": "#0b7285",
			"backgroundColor": "transparent",
			"width": 2.3421555753500343,
			"height": 11.71077787675057,
			"seed": 1863992791,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223438,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-0.46842396737861236,
					1.4052719021353255
				],
				[
					-0.46842396737861236,
					2.342155575350091
				],
				[
					-0.9368479347569973,
					3.7474274774854166
				],
				[
					-1.4053076405932643,
					5.152735118078681
				],
				[
					-1.8737316079716493,
					7.494890693428772
				],
				[
					-2.3421555753500343,
					8.900162595564098
				],
				[
					-2.3421555753500343,
					10.773894203535804
				],
				[
					-1.8737316079716493,
					11.71077787675057
				],
				[
					-1.4053076405932643,
					11.71077787675057
				],
				[
					-1.4053076405932643,
					11.71077787675057
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0068359375,
				0.18359375,
				0.2333984375,
				0.2470703125,
				0.2490234375,
				0.234375,
				0.201171875,
				0.111328125,
				0.0263671875,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 277,
			"versionNonce": 143384836,
			"isDeleted": false,
			"id": "yfvNX8ddyeuxiQHKnJf4t",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1484.726100833033,
			"y": 211.99395925528847,
			"strokeColor": "#0b7285",
			"backgroundColor": "transparent",
			"width": 0.9368479347569973,
			"height": 7.494890693428829,
			"seed": 870824087,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223438,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.46842396737861236,
					-0.46842396737844183
				],
				[
					0.46842396737861236,
					0
				],
				[
					0.46842396737861236,
					0.4684239673784987
				],
				[
					0.46842396737861236,
					1.8737316079717061
				],
				[
					0.46842396737861236,
					2.81057954272859
				],
				[
					0,
					4.215887183321797
				],
				[
					0,
					5.621159085457123
				],
				[
					0,
					6.0896187912934465
				],
				[
					-0.468423967378385,
					6.558042758671945
				],
				[
					-0.468423967378385,
					7.026466726050387
				],
				[
					0,
					6.0896187912934465
				],
				[
					0.46842396737861236,
					5.621159085457123
				],
				[
					0.46842396737861236,
					5.621159085457123
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.00390625,
				0.0673828125,
				0.6416015625,
				0.6884765625,
				0.7041015625,
				0.7080078125,
				0.70703125,
				0.6826171875,
				0.6376953125,
				0.3974609375,
				0.337890625,
				0.0283203125,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 279,
			"versionNonce": 2137104700,
			"isDeleted": false,
			"id": "2J-7Y-1J6Qc_tqVAv4dxD",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1488.00510434314,
			"y": 210.12022764731682,
			"strokeColor": "#0b7285",
			"backgroundColor": "transparent",
			"width": 5.152735118078681,
			"height": 9.83704626877892,
			"seed": 166497913,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223438,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.9368836732148793,
					0
				],
				[
					1.4053076405932643,
					0.46842396737844183
				],
				[
					1.8737316079716493,
					0.9368836732147656
				],
				[
					2.3421555753502616,
					1.8737316079716493
				],
				[
					2.3421555753502616,
					2.81057954272859
				],
				[
					2.3421555753502616,
					4.215887183321797
				],
				[
					1.4053076405932643,
					5.621194823915005
				],
				[
					0.9368836732148793,
					7.02646672605033
				],
				[
					0,
					7.963350399265096
				],
				[
					-0.93684793475677,
					8.900198334022036
				],
				[
					-1.8737316079716493,
					9.368622301400478
				],
				[
					-2.8105795427284193,
					9.83704626877892
				],
				[
					-2.8105795427284193,
					9.368622301400478
				],
				[
					-2.3421555753500343,
					8.900198334022036
				],
				[
					-2.3421555753500343,
					8.900198334022036
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0,
				0.15625,
				0.240234375,
				0.310546875,
				0.341796875,
				0.3486328125,
				0.3515625,
				0.3544921875,
				0.357421875,
				0.3583984375,
				0.357421875,
				0.349609375,
				0.255859375,
				0.05859375,
				0.0107421875,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 280,
			"versionNonce": 1508974724,
			"isDeleted": false,
			"id": "RHnuF7Dcg7yuX2PzZJdQO",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1494.5631471018119,
			"y": 214.80453879801712,
			"strokeColor": "#0b7285",
			"backgroundColor": "transparent",
			"width": 5.152770856536563,
			"height": 3.7474632159432986,
			"seed": 278407831,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223438,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-0.46842396737844183
				],
				[
					0,
					0
				],
				[
					-0.468423967378385,
					0.46842396737844183
				],
				[
					-0.93684793475677,
					1.4053076405932075
				],
				[
					-0.93684793475677,
					1.8737316079716493
				],
				[
					-1.4053076405932643,
					2.342155575350091
				],
				[
					-1.4053076405932643,
					2.810579542728533
				],
				[
					-0.93684793475677,
					2.810579542728533
				],
				[
					-0.468423967378385,
					3.2790392485648567
				],
				[
					0,
					3.2790392485648567
				],
				[
					1.4053076405932643,
					2.810579542728533
				],
				[
					1.8737316079716493,
					2.810579542728533
				],
				[
					2.8105795427286466,
					2.342155575350091
				],
				[
					3.7474632159432986,
					1.4053076405932075
				],
				[
					0,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0029296875,
				0.2509765625,
				0.3720703125,
				0.458984375,
				0.5185546875,
				0.5322265625,
				0.537109375,
				0.541015625,
				0.54296875,
				0.54296875,
				0.51953125,
				0.3740234375,
				0.30078125,
				0.1259765625,
				0.005859375,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 275,
			"versionNonce": 1368529340,
			"isDeleted": false,
			"id": "76mdQwrIIW6UwEb99yUgU",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1498.3106103177547,
			"y": 214.33611483063873,
			"strokeColor": "#0b7285",
			"backgroundColor": "transparent",
			"width": 0.9368836732146519,
			"height": 7.494890693428772,
			"seed": 1452300471,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223438,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					0.46842396737844183
				],
				[
					0.468423967378385,
					0.9368479347568837
				],
				[
					0.468423967378385,
					1.8737316079716493
				],
				[
					0,
					2.810579542728533
				],
				[
					0,
					3.7474632159432986
				],
				[
					0,
					5.152735118078681
				],
				[
					-0.46845970583626695,
					6.0896187912934465
				],
				[
					-0.46845970583626695,
					7.02646672605033
				],
				[
					-0.46845970583626695,
					7.494890693428772
				],
				[
					0,
					7.494890693428772
				],
				[
					0,
					7.494890693428772
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0048828125,
				0.173828125,
				0.2734375,
				0.349609375,
				0.3623046875,
				0.3623046875,
				0.3466796875,
				0.296875,
				0.2421875,
				0.140625,
				0.015625,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 281,
			"versionNonce": 1535275012,
			"isDeleted": false,
			"id": "fbss2W2OlfKbOnWLAuSeL",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1645.3979518589763,
			"y": -4.889643448286392,
			"strokeColor": "#0b7285",
			"backgroundColor": "transparent",
			"width": 5.621159085457066,
			"height": 12.17921971335798,
			"seed": 546648953,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223438,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-0.4684418366073828
				],
				[
					-0.46842396737861236,
					0
				],
				[
					-1.4052719021356097,
					0.46842396737844183
				],
				[
					-1.8736958695139947,
					0.9368479347569121
				],
				[
					-2.3421555753502616,
					1.8737137387427367
				],
				[
					-2.8105795427286466,
					3.279003510107003
				],
				[
					-3.2790035101070316,
					5.152735118078681
				],
				[
					-3.2790035101070316,
					7.026466726050359
				],
				[
					-3.2790035101070316,
					8.900180464793067
				],
				[
					-2.8105795427286466,
					10.773912072764773
				],
				[
					-2.8105795427286466,
					11.242336040143215
				],
				[
					-1.8736958695139947,
					11.710777876750598
				],
				[
					-0.46842396737861236,
					11.710777876750598
				],
				[
					0.46845970583626695,
					10.773912072764773
				],
				[
					1.873731607971422,
					10.30547023615739
				],
				[
					2.3421555753500343,
					9.837046268778892
				],
				[
					2.3421555753500343,
					9.837046268778892
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0,
				0.0341796875,
				0.421875,
				0.5126953125,
				0.5859375,
				0.6435546875,
				0.7080078125,
				0.828125,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.6181640625,
				0.3818359375,
				0.0517578125,
				0.00390625,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 273,
			"versionNonce": 1746895420,
			"isDeleted": false,
			"id": "Saxrh3c-r51YdnTrf8tvL",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1649.613839042298,
			"y": -2.0790639055578595,
			"strokeColor": "#0b7285",
			"backgroundColor": "transparent",
			"width": 2.3421555753502616,
			"height": 17.800378798815075,
			"seed": 233605815,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223438,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-0.93684793475677,
					4.215887183321797
				],
				[
					-1.4052719021353823,
					7.02646672605033
				],
				[
					-1.8737316079716493,
					9.83704626877892
				],
				[
					-1.8737316079716493,
					12.647643680736394
				],
				[
					-2.3421555753502616,
					14.052933452100717
				],
				[
					-2.3421555753502616,
					15.926665060072366
				],
				[
					-2.3421555753502616,
					16.86351299482925
				],
				[
					-1.8737316079716493,
					17.800378798815075
				],
				[
					-1.8737316079716493,
					17.800378798815075
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.005859375,
				0.37890625,
				0.5791015625,
				0.669921875,
				0.67578125,
				0.60546875,
				0.3857421875,
				0.205078125,
				0.0244140625,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 301,
			"versionNonce": 1295896452,
			"isDeleted": false,
			"id": "2IaaVXM1rGpl3AKz-VJP1",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1644.9295278915974,
			"y": 41.48502622210856,
			"strokeColor": "#087f5b",
			"backgroundColor": "transparent",
			"width": 12.647625811507396,
			"height": 18.737244602800956,
			"seed": 428842137,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223438,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.46842396737861236,
					0
				],
				[
					0,
					0
				],
				[
					-0.468423967378385,
					0
				],
				[
					-1.4052719021353823,
					0
				],
				[
					-2.3421555753500343,
					0
				],
				[
					-2.8105795427284193,
					0
				],
				[
					-3.2790035101068042,
					0
				],
				[
					-3.7474274774854166,
					0
				],
				[
					-3.2790035101068042,
					0
				],
				[
					-3.7474274774854166,
					0.4684418366073828
				],
				[
					-3.7474274774854166,
					1.8737316079716493
				],
				[
					-4.2158871833216836,
					3.2790213793359726
				],
				[
					-4.684311150700296,
					5.152735118078681
				],
				[
					-5.152735118078681,
					7.02646672605033
				],
				[
					-5.152735118078681,
					7.963350399265153
				],
				[
					-5.152735118078681,
					8.431774366643594
				],
				[
					-5.152735118078681,
					8.900198334022036
				],
				[
					-4.684311150700296,
					8.900198334022036
				],
				[
					-3.7474274774854166,
					8.900198334022036
				],
				[
					-2.8105795427284193,
					8.431774366643594
				],
				[
					-2.3421555753500343,
					8.431774366643594
				],
				[
					-1.4052719021353823,
					8.900198334022036
				],
				[
					-0.468423967378385,
					9.83704626877892
				],
				[
					0.46842396737861236,
					10.773929941993686
				],
				[
					1.4053076405932643,
					12.179201844129011
				],
				[
					1.8737316079716493,
					14.052933452100717
				],
				[
					1.8737316079716493,
					15.458241092693925
				],
				[
					0.9368836732148793,
					16.86351299482925
				],
				[
					-0.468423967378385,
					17.800396668044016
				],
				[
					-1.8737316079716493,
					18.268820635422458
				],
				[
					-5.152735118078681,
					18.737244602800956
				],
				[
					-7.02646672605033,
					18.268820635422458
				],
				[
					-8.431738628185713,
					17.331972700665574
				],
				[
					-9.83704626877875,
					16.39508902745081
				],
				[
					-10.773894203535747,
					15.458241092693925
				],
				[
					-10.773894203535747,
					14.989817125315483
				],
				[
					-10.773894203535747,
					14.989817125315483
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0,
				0.56640625,
				0.697265625,
				0.8935546875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.876953125,
				0.5048828125,
				0.0703125,
				0.0078125,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 290,
			"versionNonce": 166451900,
			"isDeleted": false,
			"id": "9AG3o8-u-rx8_bXqcjkD0",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1648.2085671401624,
			"y": 88.32813772911095,
			"strokeColor": "#2b8a3e",
			"backgroundColor": "transparent",
			"width": 9.837082007236631,
			"height": 20.142552243394107,
			"seed": 498960087,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223438,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-5.152770856536563,
					2.810579542728533
				],
				[
					-6.558042758671718,
					4.684311150700239
				],
				[
					-7.494926431886597,
					5.621194823915005
				],
				[
					-8.431774366643594,
					7.494890693428772
				],
				[
					-9.368622301400364,
					8.90019833402198
				],
				[
					-9.837082007236631,
					11.71077787675057
				],
				[
					-9.837082007236631,
					14.521357419479102
				],
				[
					-9.368622301400364,
					17.331972700665574
				],
				[
					-8.90019833402198,
					19.20566857017934
				],
				[
					-7.494926431886597,
					20.142552243394107
				],
				[
					-5.152770856536563,
					20.142552243394107
				],
				[
					-3.2790392485649136,
					19.674128276015665
				],
				[
					-2.3421555753500343,
					19.20566857017934
				],
				[
					-0.9368836732148793,
					18.7372446028009
				],
				[
					-0.9368836732148793,
					18.268820635422458
				],
				[
					-0.9368836732148793,
					17.331972700665574
				],
				[
					-1.4053076405932643,
					16.39508902745081
				],
				[
					-2.3421555753500343,
					15.926665060072366
				],
				[
					-3.7474632159432986,
					15.926665060072366
				],
				[
					-5.152770856536563,
					15.926665060072366
				],
				[
					-6.089618791293333,
					15.926665060072366
				],
				[
					-7.02646672605033,
					15.458241092693925
				],
				[
					-8.431774366643594,
					14.989817125315426
				],
				[
					-9.368622301400364,
					14.989817125315426
				],
				[
					-9.837082007236631,
					14.989817125315426
				],
				[
					-9.837082007236631,
					14.989817125315426
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.009765625,
				0.451171875,
				0.4892578125,
				0.509765625,
				0.5478515625,
				0.5751953125,
				0.59765625,
				0.6162109375,
				0.607421875,
				0.5966796875,
				0.5830078125,
				0.5546875,
				0.54296875,
				0.541015625,
				0.5400390625,
				0.5400390625,
				0.5498046875,
				0.56640625,
				0.5986328125,
				0.623046875,
				0.6298828125,
				0.6298828125,
				0.62109375,
				0.44921875,
				0.33203125,
				0.029296875,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 283,
			"versionNonce": 1063337732,
			"isDeleted": false,
			"id": "SRxA65By8kpZmUtxIjfom",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1647.7401074343256,
			"y": 155.78222544688583,
			"strokeColor": "#5c940d",
			"backgroundColor": "transparent",
			"width": 9.368622301400364,
			"height": 17.331936962207692,
			"seed": 1106375319,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223438,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					0.9368479347568837
				],
				[
					0,
					-0.46842396737844183
				],
				[
					0.46845970583626695,
					-2.342155575350091
				],
				[
					0.46845970583626695,
					-5.152735118078681
				],
				[
					0.46845970583626695,
					-7.963314660807214
				],
				[
					0.46845970583626695,
					-10.773929941993686
				],
				[
					0.46845970583626695,
					-13.116085517343777
				],
				[
					0.46845970583626695,
					-14.521357419479159
				],
				[
					0,
					-15.926665060072366
				],
				[
					-0.9368479347569973,
					-16.39508902745081
				],
				[
					-2.3421555753500343,
					-16.39508902745081
				],
				[
					-3.2790035101070316,
					-16.39508902745081
				],
				[
					-5.621159085457066,
					-15.926665060072366
				],
				[
					-7.02646672605033,
					-15.926665060072366
				],
				[
					-8.900162595564098,
					-14.9897813868576
				],
				[
					-8.900162595564098,
					-14.521357419479159
				],
				[
					-8.431738628185713,
					-14.05293345210066
				],
				[
					-8.431738628185713,
					-13.584509484722219
				],
				[
					-8.431738628185713,
					-13.584509484722219
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0048828125,
				0.4873046875,
				0.5537109375,
				0.5859375,
				0.611328125,
				0.6279296875,
				0.6396484375,
				0.6474609375,
				0.6513671875,
				0.65234375,
				0.6748046875,
				0.70703125,
				0.7265625,
				0.7412109375,
				0.744140625,
				0.5947265625,
				0.310546875,
				0.0537109375,
				0.0244140625,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 273,
			"versionNonce": 1368990524,
			"isDeleted": false,
			"id": "a_Go4U02nS60k4dBS_gdO",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1651.9559946176482,
			"y": 148.7557587208355,
			"strokeColor": "#5c940d",
			"backgroundColor": "transparent",
			"width": 14.521357419479273,
			"height": 1.8737316079716493,
			"seed": 668990233,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223438,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-3.2790035101070316,
					0.9368479347568837
				],
				[
					-5.152735118078908,
					0.9368479347568837
				],
				[
					-7.0264667260505576,
					0.9368479347568837
				],
				[
					-9.368622301400592,
					0.9368479347568837
				],
				[
					-11.242353909372241,
					0.46842396737844183
				],
				[
					-13.116049778886008,
					0.9368479347568837
				],
				[
					-14.052933452100888,
					1.8737316079716493
				],
				[
					-14.521357419479273,
					1.8737316079716493
				],
				[
					-14.521357419479273,
					1.8737316079716493
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0078125,
				0.36328125,
				0.51171875,
				0.5947265625,
				0.630859375,
				0.576171875,
				0.3134765625,
				0.037109375,
				0.0107421875,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 292,
			"versionNonce": 174767748,
			"isDeleted": false,
			"id": "vpDaeSKyb_JU3KtwrDokY",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1649.1454150749191,
			"y": 188.57240350178745,
			"strokeColor": "#e67700",
			"backgroundColor": "transparent",
			"width": 12.179201844129238,
			"height": 22.01624811290793,
			"seed": 636380311,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223438,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-4.215887183321911,
					1.4053076405932075
				],
				[
					-6.558042758671945,
					2.342155575350148
				],
				[
					-7.494890693428715,
					3.2790035101070316
				],
				[
					-8.900198334022207,
					4.215887183321797
				],
				[
					-9.368622301400592,
					4.684311150700239
				],
				[
					-9.368622301400592,
					5.621159085457123
				],
				[
					-8.900198334022207,
					7.02646672605033
				],
				[
					-7.9633146608073275,
					8.431774366643594
				],
				[
					-6.08961879129356,
					9.83704626877892
				],
				[
					-3.7474632159432986,
					11.71077787675057
				],
				[
					-1.8737316079718767,
					13.116085517343777
				],
				[
					-0.468423967378385,
					14.9897813868576
				],
				[
					0,
					17.331936962207692
				],
				[
					-0.468423967378385,
					18.737244602800956
				],
				[
					-2.3421555753502616,
					20.142552243394164
				],
				[
					-4.684311150700296,
					21.54782414552949
				],
				[
					-6.08961879129356,
					22.01624811290793
				],
				[
					-7.494890693428715,
					22.01624811290793
				],
				[
					-8.431774366643594,
					21.079400178151047
				],
				[
					-7.9633146608073275,
					19.205668570179398
				],
				[
					-2.3421555753502616,
					11.242353909372127
				],
				[
					0.468423967378385,
					7.963314660807271
				],
				[
					2.3421555753500343,
					6.0896187912934465
				],
				[
					2.8105795427286466,
					4.684311150700239
				],
				[
					2.8105795427286466,
					4.215887183321797
				],
				[
					2.8105795427286466,
					4.684311150700239
				],
				[
					2.3421555753500343,
					4.684311150700239
				],
				[
					2.3421555753500343,
					4.684311150700239
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.00390625,
				0.4482421875,
				0.4951171875,
				0.5048828125,
				0.5068359375,
				0.509765625,
				0.517578125,
				0.5185546875,
				0.5185546875,
				0.517578125,
				0.515625,
				0.513671875,
				0.5146484375,
				0.517578125,
				0.5185546875,
				0.5185546875,
				0.5205078125,
				0.5234375,
				0.5244140625,
				0.5244140625,
				0.5302734375,
				0.5341796875,
				0.5322265625,
				0.517578125,
				0.404296875,
				0.169921875,
				0.0595703125,
				0.005859375,
				0
			]
		},
		{
			"type": "line",
			"version": 326,
			"versionNonce": 898194364,
			"isDeleted": false,
			"id": "phbdzc4WOb6HLRh7BZNwc",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1689.0594212584142,
			"y": -144.01134186139666,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 158.45347697100578,
			"height": 0.5868669682334939,
			"seed": 1688287065,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223438,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					158.45347697100578,
					-0.5868669682334939
				]
			]
		},
		{
			"type": "line",
			"version": 367,
			"versionNonce": 1192775172,
			"isDeleted": false,
			"id": "W2lQOp1nmuiqUTz0aSyya",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1689.4995966700913,
			"y": -92.36725573763988,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 158.45347697100578,
			"height": 0.5868669682334939,
			"seed": 1570684985,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223438,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					158.45347697100578,
					-0.5868669682334939
				]
			]
		},
		{
			"type": "line",
			"version": 359,
			"versionNonce": 266241084,
			"isDeleted": false,
			"id": "8D6MLuiGuCSmLVIO2or4w",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1691.7003394057997,
			"y": -43.80421280194196,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 158.45347697100578,
			"height": 0.5868669682334939,
			"seed": 103720823,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223438,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					158.45347697100578,
					-0.5868669682334939
				]
			]
		},
		{
			"type": "line",
			"version": 366,
			"versionNonce": 1181216132,
			"isDeleted": false,
			"id": "4KeEXRi4oIfhNDc4rm1cH",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1693.9010821415072,
			"y": 3.2916906970632454,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 158.45347697100578,
			"height": 0.5868669682334939,
			"seed": 1927824985,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223439,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					158.45347697100578,
					-0.5868669682334939
				]
			]
		},
		{
			"type": "line",
			"version": 366,
			"versionNonce": 645569724,
			"isDeleted": false,
			"id": "jJXHDOQ2kpcrN1E3p8BZq",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1694.7813881906363,
			"y": 51.12117510797111,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 158.45347697100578,
			"height": 0.5868669682334939,
			"seed": 163781817,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223439,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					158.45347697100578,
					-0.5868669682334939
				]
			]
		},
		{
			"type": "line",
			"version": 347,
			"versionNonce": 160931076,
			"isDeleted": false,
			"id": "snzWHUHLzWzJsPOKWTC_L",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1690.9667137196707,
			"y": 101.15137986747482,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 158.45347697100578,
			"height": 0.5868669682334939,
			"seed": 1593521945,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223439,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					158.45347697100578,
					-0.5868669682334939
				]
			]
		},
		{
			"type": "line",
			"version": 363,
			"versionNonce": 855614780,
			"isDeleted": false,
			"id": "0oBecQVwpEm8o8e90t6mI",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1694.4879379161853,
			"y": 149.42101730294712,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 158.45347697100578,
			"height": 0.5868669682334939,
			"seed": 2049362775,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223439,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					158.45347697100578,
					-0.5868669682334939
				]
			]
		},
		{
			"type": "line",
			"version": 346,
			"versionNonce": 975527044,
			"isDeleted": false,
			"id": "RY3WzFjMQRsgd5ln3FSzj",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1696.6886806518937,
			"y": 199.74464994978916,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 158.45347697100578,
			"height": 0.5868669682334939,
			"seed": 1087783481,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223439,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					158.45347697100578,
					-0.5868669682334939
				]
			]
		},
		{
			"type": "line",
			"version": 432,
			"versionNonce": 1791991228,
			"isDeleted": false,
			"id": "PSVYTbohRludqDTsS2w6v",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 604.2486345303976,
			"y": 116.19312295124712,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 122.10104715478462,
			"height": 1.6444647784073823,
			"seed": 581480279,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223439,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					122.10104715478462,
					1.6444647784073823
				]
			]
		},
		{
			"type": "line",
			"version": 540,
			"versionNonce": 567225348,
			"isDeleted": false,
			"id": "zsGKTS5MfTjvi_3Bs8hsa",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 604.1458574420947,
			"y": 137.77662515047882,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 122.10104715478462,
			"height": 1.6444647784073823,
			"seed": 1120537657,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223439,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					122.10104715478462,
					1.6444647784073823
				]
			]
		},
		{
			"type": "freedraw",
			"version": 301,
			"versionNonce": 118261308,
			"isDeleted": false,
			"id": "auuh4J6F_UE-O6XSKufA7",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 579.5759745791086,
			"y": 133.12553889184778,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 2.522431448773318,
			"height": 12.612109132488627,
			"seed": 146177175,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223439,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.8408104829244394,
					-0.4203972228991688
				],
				[
					0.8408104829244394,
					0
				],
				[
					0.8408104829244394,
					0.8408104829244678
				],
				[
					0.8408104829244394,
					2.522431448773375
				],
				[
					0.4203972228991688,
					3.78363915459704
				],
				[
					-0.4203972228991688,
					6.306054566244342
				],
				[
					-0.8408104829244394,
					8.408072754992446
				],
				[
					-0.8408104829244394,
					10.089693720841353
				],
				[
					-1.2612077058236082,
					11.350901426665018
				],
				[
					-1.6816209658488788,
					12.191711909589458
				],
				[
					-0.8408104829244394,
					12.191711909589458
				],
				[
					-0.4203972228991688,
					11.771314686690289
				],
				[
					-0.4203972228991688,
					11.771314686690289
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0078125,
				0.359375,
				0.486328125,
				0.580078125,
				0.6025390625,
				0.6064453125,
				0.6083984375,
				0.609375,
				0.59765625,
				0.533203125,
				0.326171875,
				0.05078125,
				0.0048828125,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 301,
			"versionNonce": 580062084,
			"isDeleted": false,
			"id": "KHuUPZEgyu_ysgzvq_gJ0",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 587.9840473341012,
			"y": 133.12553889184778,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 7.987659494967261,
			"height": 2.5224154116473017,
			"seed": 1558153849,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223439,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.4203972228991688,
					-0.4203972228991688
				],
				[
					0,
					-0.4203972228991688
				],
				[
					-0.8408104829245531,
					0
				],
				[
					-1.6816209658489925,
					0
				],
				[
					-2.9428286716726006,
					0
				],
				[
					-4.2040363774963225,
					0
				],
				[
					-5.465244083319931,
					0.4204132600252706
				],
				[
					-6.30605456624437,
					0.4204132600252706
				],
				[
					-6.726451789143539,
					0.4204132600252706
				],
				[
					-7.567262272068092,
					0.8408104829244678
				],
				[
					-7.1468650491688095,
					1.6816209658489356
				],
				[
					-6.726451789143539,
					2.102018188748133
				],
				[
					-6.726451789143539,
					2.102018188748133
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0048828125,
				0.072265625,
				0.2978515625,
				0.4033203125,
				0.4326171875,
				0.470703125,
				0.484375,
				0.4912109375,
				0.4912109375,
				0.4794921875,
				0.2880859375,
				0.02734375,
				0.009765625,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 296,
			"versionNonce": 1285054140,
			"isDeleted": false,
			"id": "tT-kQd_wr9jg8eYw6bxHS",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 585.0412186624287,
			"y": 139.43159345809204,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 5.8856413062190995,
			"height": 1.26122374294971,
			"seed": 1053209975,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223439,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-0.4203972228991688,
					0
				],
				[
					-1.2612077058237219,
					0
				],
				[
					-2.1020181887481613,
					0.4204132600252706
				],
				[
					-3.3632258945717695,
					0.4204132600252706
				],
				[
					-4.624433600395491,
					0.4204132600252706
				],
				[
					-5.8856413062190995,
					0.8408104829244394
				],
				[
					-5.8856413062190995,
					1.26122374294971
				],
				[
					-5.8856413062190995,
					1.26122374294971
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0,
				0.296875,
				0.3154296875,
				0.3203125,
				0.3212890625,
				0.3134765625,
				0.2275390625,
				0.0185546875,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 299,
			"versionNonce": 783219460,
			"isDeleted": false,
			"id": "16InSKCgask3zHkeXG-n0",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 586.3024263682521,
			"y": 146.15806128436157,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 8.408072754992418,
			"height": 0.4204132600252706,
			"seed": 888367895,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223439,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-0.4203972228991688,
					0
				],
				[
					-0.8407944457983376,
					0
				],
				[
					-1.681604928722777,
					0
				],
				[
					-2.52241541164733,
					0
				],
				[
					-3.7836231174709383,
					-0.4204132600252706
				],
				[
					-5.0448308232945465,
					-0.4204132600252706
				],
				[
					-6.30605456624437,
					-0.4204132600252706
				],
				[
					-7.146849012042708,
					-0.4204132600252706
				],
				[
					-8.408072754992418,
					-0.4204132600252706
				],
				[
					-8.408072754992418,
					0
				],
				[
					-8.408072754992418,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.001953125,
				0.16796875,
				0.3076171875,
				0.3828125,
				0.421875,
				0.4599609375,
				0.515625,
				0.533203125,
				0.5361328125,
				0.3603515625,
				0.29296875,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 420,
			"versionNonce": 336930620,
			"isDeleted": false,
			"id": "Joc5MyPGyoMQovMTS1BvZ",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 795.6634507972633,
			"y": 37.273464580980885,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1.6816209658488788,
			"height": 38.677137880390376,
			"seed": 925874809,
			"groupIds": [
				"twneo-ZBMPfJe7Tq94YpM",
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223439,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-0.4203972228991688,
					-1.261207705823665
				],
				[
					0,
					-2.1020181887481044
				],
				[
					0,
					-2.5224154116472732
				],
				[
					0,
					-2.942828671672544
				],
				[
					0,
					-3.3632258945717695
				],
				[
					0.42042929715137234,
					-3.3632258945717695
				],
				[
					0.42042929715137234,
					-2.942828671672544
				],
				[
					0.8408265200505411,
					-1.6816049287228338
				],
				[
					1.26122374294971,
					0.4204132600252706
				],
				[
					1.26122374294971,
					4.204036377496209
				],
				[
					1.26122374294971,
					7.987675532093249
				],
				[
					1.26122374294971,
					12.612109132488627
				],
				[
					1.26122374294971,
					16.395748287085667
				],
				[
					0.8408265200505411,
					20.599784664581875
				],
				[
					0.8408265200505411,
					23.96302659627969
				],
				[
					0.42042929715137234,
					27.326236453725414
				],
				[
					0.42042929715137234,
					29.42825464247352
				],
				[
					0.42042929715137234,
					32.37109935127211
				],
				[
					0,
					34.052688242868896
				],
				[
					0.42042929715137234,
					34.89351476291944
				],
				[
					0,
					35.313911985818606
				],
				[
					0,
					34.89351476291944
				],
				[
					-0.4203972228991688,
					34.47311754002027
				],
				[
					-0.4203972228991688,
					34.052688242868896
				],
				[
					-0.4203972228991688,
					33.2118937970705
				],
				[
					-0.4203972228991688,
					33.2118937970705
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0087890625,
				0.1806640625,
				0.4404296875,
				0.5107421875,
				0.6181640625,
				0.76953125,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.6572265625,
				0.3818359375,
				0.2470703125,
				0.0087890625,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 625,
			"versionNonce": 1084291716,
			"isDeleted": false,
			"id": "61BR2OE9Lntd8qbHZ64fP",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 796.5042773173138,
			"y": 33.06942820348468,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 60.11773302789675,
			"height": 42.46076099786137,
			"seed": 909623993,
			"groupIds": [
				"twneo-ZBMPfJe7Tq94YpM",
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223439,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-0.42039722289922565
				],
				[
					0,
					0
				],
				[
					0.4203972228991688,
					0
				],
				[
					1.2611916686975064,
					0.4204132600252706
				],
				[
					2.1020181887480476,
					0.4204132600252706
				],
				[
					3.3632098574456677,
					0.4204132600252706
				],
				[
					4.204036377496209,
					0.4204132600252706
				],
				[
					5.0448308232945465,
					0.4204132600252706
				],
				[
					6.726451789143425,
					0.4204132600252706
				],
				[
					7.987675532093249,
					0.4204132600252706
				],
				[
					9.248867200790869,
					0.4204132600252706
				],
				[
					10.510090943740465,
					0.4204132600252706
				],
				[
					11.350885389538917,
					0.8408104829244394
				],
				[
					12.612109132488627,
					0.8408104829244394
				],
				[
					13.452903578286964,
					0.8408104829244394
				],
				[
					14.293730098337505,
					0.8408104829244394
				],
				[
					15.134524544135843,
					1.261207705823665
				],
				[
					16.395748287085667,
					1.261207705823665
				],
				[
					17.236542732884004,
					0.8408104829244394
				],
				[
					18.077337178682342,
					0.8408104829244394
				],
				[
					18.918163698732883,
					0.8408104829244394
				],
				[
					20.179355367430503,
					1.261207705823665
				],
				[
					21.020181887481044,
					1.261207705823665
				],
				[
					21.860976333279382,
					1.261207705823665
				],
				[
					22.701802853329923,
					1.261207705823665
				],
				[
					24.383391744926712,
					1.261207705823665
				],
				[
					25.224218264977253,
					1.261207705823665
				],
				[
					25.644615487876422,
					1.261207705823665
				],
				[
					26.48540993367476,
					1.261207705823665
				],
				[
					27.3262364537253,
					1.261207705823665
				],
				[
					28.167030899523752,
					1.6816209658489356
				],
				[
					28.58742812242292,
					1.6816209658489356
				],
				[
					29.848651865372744,
					1.6816209658489356
				],
				[
					30.689446311171082,
					1.6816209658489356
				],
				[
					31.530272831221623,
					1.6816209658489356
				],
				[
					31.950670054120792,
					1.261207705823665
				],
				[
					32.37106727701996,
					1.261207705823665
				],
				[
					32.79146449991924,
					1.6816209658489356
				],
				[
					33.2118937970705,
					1.6816209658489356
				],
				[
					33.63229101996967,
					1.6816209658489356
				],
				[
					34.47308546576812,
					1.6816209658489356
				],
				[
					34.89348268866729,
					1.6816209658489356
				],
				[
					35.31391198581866,
					1.6816209658489356
				],
				[
					35.73430920871783,
					1.6816209658489356
				],
				[
					36.57510365451617,
					1.6816209658489356
				],
				[
					37.41593017456671,
					1.6816209658489356
				],
				[
					37.83632739746588,
					1.6816209658489356
				],
				[
					39.0975190661635,
					1.6816209658489356
				],
				[
					39.93834558621404,
					1.6816209658489356
				],
				[
					40.77914003201238,
					2.1020181887481044
				],
				[
					41.61996655206292,
					2.522431448773375
				],
				[
					42.88115822076054,
					2.942828671672544
				],
				[
					44.14238196371025,
					3.3632258945717695
				],
				[
					45.403573632407756,
					3.78363915459704
				],
				[
					46.66479737535758,
					5.044846860420648
				],
				[
					47.50559182115592,
					5.8856573433451445
				],
				[
					48.76681556410563,
					6.726451789143482
				],
				[
					49.187212787004796,
					7.146881086294854
				],
				[
					49.60761000990408,
					7.567278309194023
				],
				[
					50.44843652995462,
					8.408072754992418
				],
				[
					51.28923097575296,
					9.248899275042959
				],
				[
					51.709628198652126,
					9.669296497942128
				],
				[
					52.55045471870267,
					10.930488166639691
				],
				[
					52.970851941601836,
					11.771314686690232
				],
				[
					53.39124916450112,
					13.032506355387852
				],
				[
					53.811646387400174,
					13.873332875438336
				],
				[
					54.23207568455166,
					15.134524544135957
				],
				[
					55.07287013035,
					16.395748287085667
				],
				[
					55.493267353249166,
					17.23654273288406
				],
				[
					55.913664576148335,
					18.49776647583377
				],
				[
					56.33409387329971,
					19.338560921632165
				],
				[
					56.33409387329971,
					20.179387441682707
				],
				[
					56.33409387329971,
					21.44057911038027
				],
				[
					56.754491096198876,
					22.28140563043081
				],
				[
					56.754491096198876,
					22.70180285332998
				],
				[
					56.754491096198876,
					23.542597299128374
				],
				[
					56.33409387329971,
					24.383423819178915
				],
				[
					56.33409387329971,
					25.224218264977253
				],
				[
					56.33409387329971,
					25.64461548787648
				],
				[
					56.33409387329971,
					26.065044785027794
				],
				[
					55.913664576148335,
					26.90583923082619
				],
				[
					55.913664576148335,
					27.746633676624583
				],
				[
					55.913664576148335,
					28.1670629737759
				],
				[
					55.913664576148335,
					28.587460196675124
				],
				[
					55.493267353249166,
					29.007857419574293
				],
				[
					55.07287013035,
					29.848651865372688
				],
				[
					55.07287013035,
					30.68947838542323
				],
				[
					54.652472907450715,
					31.109875608322398
				],
				[
					54.652472907450715,
					31.530272831221623
				],
				[
					54.23207568455166,
					31.950670054120792
				],
				[
					54.23207568455166,
					32.37109935127211
				],
				[
					53.811646387400174,
					32.79149657417133
				],
				[
					53.811646387400174,
					33.2118937970705
				],
				[
					53.39124916450112,
					33.63229101996973
				],
				[
					53.39124916450112,
					34.052688242868896
				],
				[
					52.970851941601836,
					34.47311754002021
				],
				[
					52.970851941601836,
					35.313911985818606
				],
				[
					52.55045471870267,
					35.73430920871783
				],
				[
					52.55045471870267,
					36.154706431617
				],
				[
					52.1300574958035,
					36.575135728768316
				],
				[
					51.709628198652126,
					36.99553295166754
				],
				[
					51.28923097575296,
					37.41593017456671
				],
				[
					50.868833752853675,
					37.836327397465936
				],
				[
					50.868833752853675,
					38.256724620365105
				],
				[
					50.44843652995462,
					38.256724620365105
				],
				[
					50.02803930705534,
					38.67715391751648
				],
				[
					49.60761000990408,
					39.097551140415646
				],
				[
					49.187212787004796,
					39.097551140415646
				],
				[
					48.76681556410563,
					39.517948363314815
				],
				[
					48.34641834120646,
					39.517948363314815
				],
				[
					47.50559182115592,
					39.93834558621404
				],
				[
					47.08519459825675,
					40.35874280911321
				],
				[
					46.66479737535758,
					40.35874280911321
				],
				[
					46.2444001524583,
					40.77917210626458
				],
				[
					45.82400292955913,
					40.77917210626458
				],
				[
					45.403573632407756,
					40.77917210626458
				],
				[
					44.56277918660942,
					40.77917210626458
				],
				[
					44.14238196371025,
					41.19956932916375
				],
				[
					43.72198474081108,
					41.19956932916375
				],
				[
					43.30155544365971,
					41.19956932916375
				],
				[
					42.88115822076054,
					41.19956932916375
				],
				[
					42.46076099786126,
					41.19956932916375
				],
				[
					42.0403637749622,
					41.19956932916375
				],
				[
					41.61996655206292,
					41.19956932916375
				],
				[
					42.0403637749622,
					41.19956932916375
				],
				[
					41.61996655206292,
					41.19956932916375
				],
				[
					42.0403637749622,
					41.19956932916375
				],
				[
					41.61996655206292,
					41.19956932916375
				],
				[
					41.19953725491166,
					41.19956932916375
				],
				[
					40.77914003201238,
					41.19956932916375
				],
				[
					39.93834558621404,
					41.19956932916375
				],
				[
					39.51794836331476,
					41.19956932916375
				],
				[
					38.67712184326422,
					41.19956932916375
				],
				[
					37.83632739746588,
					41.19956932916375
				],
				[
					37.41593017456671,
					41.19956932916375
				],
				[
					36.99550087741534,
					41.19956932916375
				],
				[
					36.57510365451617,
					41.61996655206292
				],
				[
					36.154706431617,
					41.61996655206292
				],
				[
					35.73430920871783,
					41.61996655206292
				],
				[
					35.31391198581866,
					41.61996655206292
				],
				[
					34.89348268866729,
					41.61996655206292
				],
				[
					34.05268824286884,
					41.61996655206292
				],
				[
					33.63229101996967,
					41.61996655206292
				],
				[
					33.2118937970705,
					41.61996655206292
				],
				[
					32.79146449991924,
					41.61996655206292
				],
				[
					32.37106727701996,
					41.61996655206292
				],
				[
					31.950670054120792,
					41.61996655206292
				],
				[
					31.530272831221623,
					41.61996655206292
				],
				[
					30.689446311171082,
					41.61996655206292
				],
				[
					30.2690490882718,
					42.040363774962145
				],
				[
					29.848651865372744,
					42.040363774962145
				],
				[
					29.428254642473462,
					42.040363774962145
				],
				[
					29.007857419574293,
					42.040363774962145
				],
				[
					28.167030899523752,
					42.040363774962145
				],
				[
					27.746633676624583,
					42.040363774962145
				],
				[
					27.3262364537253,
					42.040363774962145
				],
				[
					26.905839230826246,
					42.040363774962145
				],
				[
					26.48540993367476,
					42.040363774962145
				],
				[
					26.065012710775704,
					42.040363774962145
				],
				[
					25.644615487876422,
					42.040363774962145
				],
				[
					25.224218264977253,
					41.61996655206292
				],
				[
					24.803821042078084,
					41.61996655206292
				],
				[
					24.383391744926712,
					41.61996655206292
				],
				[
					23.962994522027543,
					41.61996655206292
				],
				[
					23.122200076229205,
					41.61996655206292
				],
				[
					22.701802853329923,
					41.61996655206292
				],
				[
					22.281373556178664,
					41.61996655206292
				],
				[
					21.860976333279382,
					41.61996655206292
				],
				[
					21.440579110380327,
					41.61996655206292
				],
				[
					20.599784664581875,
					41.61996655206292
				],
				[
					19.758958144531334,
					41.61996655206292
				],
				[
					19.338560921632165,
					41.61996655206292
				],
				[
					18.918163698732883,
					41.61996655206292
				],
				[
					18.497766475833828,
					41.61996655206292
				],
				[
					18.077337178682342,
					41.61996655206292
				],
				[
					17.656939955783287,
					41.61996655206292
				],
				[
					17.236542732884004,
					41.61996655206292
				],
				[
					16.816145509984835,
					41.61996655206292
				],
				[
					16.395748287085667,
					41.61996655206292
				],
				[
					15.975318989934294,
					41.61996655206292
				],
				[
					15.554921767035125,
					41.61996655206292
				],
				[
					15.134524544135843,
					41.61996655206292
				],
				[
					14.714127321236788,
					41.61996655206292
				],
				[
					14.293730098337505,
					41.61996655206292
				],
				[
					13.452903578286964,
					42.040363774962145
				],
				[
					13.032506355387795,
					41.61996655206292
				],
				[
					12.612109132488627,
					41.61996655206292
				],
				[
					12.191711909589458,
					41.61996655206292
				],
				[
					12.191711909589458,
					41.19956932916375
				],
				[
					11.771282612438085,
					41.19956932916375
				],
				[
					11.350885389538917,
					41.19956932916375
				],
				[
					10.930488166639748,
					41.19956932916375
				],
				[
					10.510090943740465,
					41.19956932916375
				],
				[
					10.08969372084141,
					41.19956932916375
				],
				[
					9.669264423689924,
					41.19956932916375
				],
				[
					9.248867200790869,
					41.19956932916375
				],
				[
					8.828469977891586,
					40.77917210626458
				],
				[
					8.408072754992418,
					40.77917210626458
				],
				[
					7.987675532093249,
					40.77917210626458
				],
				[
					7.5672462349418765,
					40.77917210626458
				],
				[
					7.146849012042708,
					40.77917210626458
				],
				[
					6.726451789143425,
					40.77917210626458
				],
				[
					6.30605456624437,
					40.77917210626458
				],
				[
					5.885657343345088,
					40.77917210626458
				],
				[
					5.465228046193829,
					40.77917210626458
				],
				[
					5.465228046193829,
					41.19956932916375
				],
				[
					5.0448308232945465,
					41.19956932916375
				],
				[
					4.624433600395378,
					41.19956932916375
				],
				[
					4.204036377496209,
					41.19956932916375
				],
				[
					3.7836391545969263,
					41.19956932916375
				],
				[
					3.3632098574456677,
					41.19956932916375
				],
				[
					2.942812634546499,
					41.19956932916375
				],
				[
					2.52241541164733,
					41.19956932916375
				],
				[
					2.1020181887480476,
					41.19956932916375
				],
				[
					1.6816209658488788,
					41.19956932916375
				],
				[
					1.2611916686975064,
					41.19956932916375
				],
				[
					0.8407944457984513,
					41.19956932916375
				],
				[
					0.4203972228991688,
					41.19956932916375
				],
				[
					0,
					41.19956932916375
				],
				[
					-0.4203972228991688,
					41.19956932916375
				],
				[
					-0.8408265200505411,
					41.19956932916375
				],
				[
					-1.26122374294971,
					41.19956932916375
				],
				[
					-1.6816209658489925,
					41.19956932916375
				],
				[
					-1.6816209658489925,
					40.77917210626458
				],
				[
					-2.1020181887480476,
					41.19956932916375
				],
				[
					-2.52241541164733,
					41.19956932916375
				],
				[
					-2.9428447087985887,
					41.19956932916375
				],
				[
					-3.3632419316978712,
					40.77917210626458
				],
				[
					-2.9428447087985887,
					40.77917210626458
				],
				[
					-2.1020181887480476,
					41.19956932916375
				],
				[
					-2.1020181887480476,
					41.19956932916375
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0029296875,
				0.4560546875,
				0.677734375,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.14453125,
				0.0068359375,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 486,
			"versionNonce": 1373953980,
			"isDeleted": false,
			"id": "lrgXUdymH3IqIZcJH4ZJV",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 795.2430535743645,
			"y": 33.06942820348468,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 2.1020181887481613,
			"height": 42.881190295012686,
			"seed": 1674553655,
			"groupIds": [
				"twneo-ZBMPfJe7Tq94YpM",
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223439,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					0.4204132600252706
				],
				[
					0.4203972228991688,
					0.4204132600252706
				],
				[
					0.4203972228991688,
					0.8408104829244394
				],
				[
					0.4203972228991688,
					1.261207705823665
				],
				[
					0.4203972228991688,
					1.6816209658489356
				],
				[
					0.8408265200505411,
					2.1020181887481044
				],
				[
					0.8408265200505411,
					2.942828671672544
				],
				[
					0.8408265200505411,
					3.3632258945717695
				],
				[
					0.8408265200505411,
					4.204036377496209
				],
				[
					0.8408265200505411,
					5.044846860420648
				],
				[
					1.26122374294971,
					5.8856573433451445
				],
				[
					1.26122374294971,
					6.306054566244313
				],
				[
					1.26122374294971,
					7.146881086294854
				],
				[
					1.26122374294971,
					8.408072754992418
				],
				[
					1.26122374294971,
					8.828469977891586
				],
				[
					1.26122374294971,
					9.669296497942128
				],
				[
					1.26122374294971,
					10.510090943740522
				],
				[
					1.26122374294971,
					11.350917463791063
				],
				[
					1.26122374294971,
					12.191711909589458
				],
				[
					1.26122374294971,
					12.612109132488627
				],
				[
					1.26122374294971,
					13.032506355387852
				],
				[
					1.26122374294971,
					13.452935652539168
				],
				[
					1.26122374294971,
					13.873332875438336
				],
				[
					1.26122374294971,
					14.293730098337562
				],
				[
					1.26122374294971,
					14.714127321236731
				],
				[
					1.26122374294971,
					15.134524544135957
				],
				[
					1.26122374294971,
					15.554953841287272
				],
				[
					1.26122374294971,
					15.975351064186441
				],
				[
					1.26122374294971,
					16.395748287085667
				],
				[
					1.26122374294971,
					17.23654273288406
				],
				[
					1.26122374294971,
					17.656972030035377
				],
				[
					1.6816209658488788,
					18.077369252934545
				],
				[
					1.6816209658488788,
					18.49776647583377
				],
				[
					1.26122374294971,
					18.91816369873294
				],
				[
					1.6816209658488788,
					18.91816369873294
				],
				[
					1.6816209658488788,
					19.338560921632165
				],
				[
					1.6816209658488788,
					19.75899021878348
				],
				[
					1.6816209658488788,
					20.599784664581875
				],
				[
					1.26122374294971,
					21.020181887481044
				],
				[
					1.6816209658488788,
					21.44057911038027
				],
				[
					1.6816209658488788,
					21.861008407531585
				],
				[
					1.6816209658488788,
					22.28140563043081
				],
				[
					1.6816209658488788,
					22.70180285332998
				],
				[
					1.6816209658488788,
					23.12220007622915
				],
				[
					1.6816209658488788,
					23.542597299128374
				],
				[
					1.6816209658488788,
					23.96302659627969
				],
				[
					1.6816209658488788,
					24.383423819178915
				],
				[
					1.6816209658488788,
					24.803821042078084
				],
				[
					1.6816209658488788,
					25.224218264977253
				],
				[
					1.6816209658488788,
					25.64461548787648
				],
				[
					1.6816209658488788,
					26.065044785027794
				],
				[
					1.6816209658488788,
					26.48544200792702
				],
				[
					1.6816209658488788,
					26.90583923082619
				],
				[
					1.6816209658488788,
					27.326236453725357
				],
				[
					1.6816209658488788,
					27.746633676624583
				],
				[
					1.6816209658488788,
					28.1670629737759
				],
				[
					1.6816209658488788,
					28.587460196675124
				],
				[
					1.6816209658488788,
					29.007857419574293
				],
				[
					1.6816209658488788,
					29.42825464247352
				],
				[
					1.6816209658488788,
					29.848651865372688
				],
				[
					1.26122374294971,
					30.269081162524003
				],
				[
					1.26122374294971,
					30.68947838542323
				],
				[
					1.26122374294971,
					31.109875608322398
				],
				[
					1.26122374294971,
					31.530272831221623
				],
				[
					1.26122374294971,
					31.950670054120792
				],
				[
					1.26122374294971,
					32.37109935127211
				],
				[
					1.26122374294971,
					32.79149657417133
				],
				[
					1.26122374294971,
					33.63229101996973
				],
				[
					1.26122374294971,
					34.47311754002021
				],
				[
					1.26122374294971,
					34.89351476291944
				],
				[
					1.26122374294971,
					35.313911985818606
				],
				[
					1.26122374294971,
					35.73430920871783
				],
				[
					1.26122374294971,
					36.154706431617
				],
				[
					0.8408265200505411,
					36.154706431617
				],
				[
					0.8408265200505411,
					36.575135728768316
				],
				[
					0.8408265200505411,
					36.99553295166754
				],
				[
					0.8408265200505411,
					37.41593017456671
				],
				[
					0.8408265200505411,
					37.836327397465936
				],
				[
					0.8408265200505411,
					38.256724620365105
				],
				[
					0.8408265200505411,
					39.097551140415646
				],
				[
					0.8408265200505411,
					39.517948363314815
				],
				[
					0.8408265200505411,
					39.93834558621404
				],
				[
					0.8408265200505411,
					40.35874280911321
				],
				[
					0.8408265200505411,
					40.77917210626458
				],
				[
					0.8408265200505411,
					41.19956932916375
				],
				[
					0.8408265200505411,
					41.61996655206292
				],
				[
					0.8408265200505411,
					42.040363774962145
				],
				[
					0.8408265200505411,
					42.460760997861314
				],
				[
					0.4203972228991688,
					42.460760997861314
				],
				[
					0.8408265200505411,
					42.881190295012686
				],
				[
					0.8408265200505411,
					42.460760997861314
				],
				[
					1.26122374294971,
					42.040363774962145
				],
				[
					1.6816209658488788,
					41.19956932916375
				],
				[
					2.1020181887481613,
					39.517948363314815
				],
				[
					2.1020181887481613,
					39.517948363314815
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0029296875,
				0.3876953125,
				0.6513671875,
				0.7490234375,
				0.8154296875,
				0.8701171875,
				0.9833984375,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9365234375,
				0.66796875,
				0.146484375,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 457,
			"versionNonce": 1395067396,
			"isDeleted": false,
			"id": "qBxudwmYbIAgLW5dycc3w",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 796.294094742989,
			"y": 96.34016445881491,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1.6816209658488788,
			"height": 38.677137880390376,
			"seed": 263395321,
			"groupIds": [
				"VozzIzLKoiJH4q1gUTW3E",
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223439,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-0.4203972228991688,
					-1.261207705823665
				],
				[
					0,
					-2.1020181887481044
				],
				[
					0,
					-2.5224154116472732
				],
				[
					0,
					-2.942828671672544
				],
				[
					0,
					-3.3632258945717695
				],
				[
					0.42042929715137234,
					-3.3632258945717695
				],
				[
					0.42042929715137234,
					-2.942828671672544
				],
				[
					0.8408265200505411,
					-1.6816049287228338
				],
				[
					1.26122374294971,
					0.4204132600252706
				],
				[
					1.26122374294971,
					4.204036377496209
				],
				[
					1.26122374294971,
					7.987675532093249
				],
				[
					1.26122374294971,
					12.612109132488627
				],
				[
					1.26122374294971,
					16.395748287085667
				],
				[
					0.8408265200505411,
					20.599784664581875
				],
				[
					0.8408265200505411,
					23.96302659627969
				],
				[
					0.42042929715137234,
					27.326236453725414
				],
				[
					0.42042929715137234,
					29.42825464247352
				],
				[
					0.42042929715137234,
					32.37109935127211
				],
				[
					0,
					34.052688242868896
				],
				[
					0.42042929715137234,
					34.89351476291944
				],
				[
					0,
					35.313911985818606
				],
				[
					0,
					34.89351476291944
				],
				[
					-0.4203972228991688,
					34.47311754002027
				],
				[
					-0.4203972228991688,
					34.052688242868896
				],
				[
					-0.4203972228991688,
					33.2118937970705
				],
				[
					-0.4203972228991688,
					33.2118937970705
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0087890625,
				0.1806640625,
				0.4404296875,
				0.5107421875,
				0.6181640625,
				0.76953125,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.6572265625,
				0.3818359375,
				0.2470703125,
				0.0087890625,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 662,
			"versionNonce": 506038332,
			"isDeleted": false,
			"id": "lPdCv7E1cx8Xxu2VKkAD9",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 797.1349212630396,
			"y": 92.1361280813187,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 60.11773302789675,
			"height": 42.46076099786137,
			"seed": 1252343831,
			"groupIds": [
				"VozzIzLKoiJH4q1gUTW3E",
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223439,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-0.42039722289922565
				],
				[
					0,
					0
				],
				[
					0.4203972228991688,
					0
				],
				[
					1.2611916686975064,
					0.4204132600252706
				],
				[
					2.1020181887480476,
					0.4204132600252706
				],
				[
					3.3632098574456677,
					0.4204132600252706
				],
				[
					4.204036377496209,
					0.4204132600252706
				],
				[
					5.0448308232945465,
					0.4204132600252706
				],
				[
					6.726451789143425,
					0.4204132600252706
				],
				[
					7.987675532093249,
					0.4204132600252706
				],
				[
					9.248867200790869,
					0.4204132600252706
				],
				[
					10.510090943740465,
					0.4204132600252706
				],
				[
					11.350885389538917,
					0.8408104829244394
				],
				[
					12.612109132488627,
					0.8408104829244394
				],
				[
					13.452903578286964,
					0.8408104829244394
				],
				[
					14.293730098337505,
					0.8408104829244394
				],
				[
					15.134524544135843,
					1.261207705823665
				],
				[
					16.395748287085667,
					1.261207705823665
				],
				[
					17.236542732884004,
					0.8408104829244394
				],
				[
					18.077337178682342,
					0.8408104829244394
				],
				[
					18.918163698732883,
					0.8408104829244394
				],
				[
					20.179355367430503,
					1.261207705823665
				],
				[
					21.020181887481044,
					1.261207705823665
				],
				[
					21.860976333279382,
					1.261207705823665
				],
				[
					22.701802853329923,
					1.261207705823665
				],
				[
					24.383391744926712,
					1.261207705823665
				],
				[
					25.224218264977253,
					1.261207705823665
				],
				[
					25.644615487876422,
					1.261207705823665
				],
				[
					26.48540993367476,
					1.261207705823665
				],
				[
					27.3262364537253,
					1.261207705823665
				],
				[
					28.167030899523752,
					1.6816209658489356
				],
				[
					28.58742812242292,
					1.6816209658489356
				],
				[
					29.848651865372744,
					1.6816209658489356
				],
				[
					30.689446311171082,
					1.6816209658489356
				],
				[
					31.530272831221623,
					1.6816209658489356
				],
				[
					31.950670054120792,
					1.261207705823665
				],
				[
					32.37106727701996,
					1.261207705823665
				],
				[
					32.79146449991924,
					1.6816209658489356
				],
				[
					33.2118937970705,
					1.6816209658489356
				],
				[
					33.63229101996967,
					1.6816209658489356
				],
				[
					34.47308546576812,
					1.6816209658489356
				],
				[
					34.89348268866729,
					1.6816209658489356
				],
				[
					35.31391198581866,
					1.6816209658489356
				],
				[
					35.73430920871783,
					1.6816209658489356
				],
				[
					36.57510365451617,
					1.6816209658489356
				],
				[
					37.41593017456671,
					1.6816209658489356
				],
				[
					37.83632739746588,
					1.6816209658489356
				],
				[
					39.0975190661635,
					1.6816209658489356
				],
				[
					39.93834558621404,
					1.6816209658489356
				],
				[
					40.77914003201238,
					2.1020181887481044
				],
				[
					41.61996655206292,
					2.522431448773375
				],
				[
					42.88115822076054,
					2.942828671672544
				],
				[
					44.14238196371025,
					3.3632258945717695
				],
				[
					45.403573632407756,
					3.78363915459704
				],
				[
					46.66479737535758,
					5.044846860420648
				],
				[
					47.50559182115592,
					5.8856573433451445
				],
				[
					48.76681556410563,
					6.726451789143482
				],
				[
					49.187212787004796,
					7.146881086294854
				],
				[
					49.60761000990408,
					7.567278309194023
				],
				[
					50.44843652995462,
					8.408072754992418
				],
				[
					51.28923097575296,
					9.248899275042959
				],
				[
					51.709628198652126,
					9.669296497942128
				],
				[
					52.55045471870267,
					10.930488166639691
				],
				[
					52.970851941601836,
					11.771314686690232
				],
				[
					53.39124916450112,
					13.032506355387852
				],
				[
					53.811646387400174,
					13.873332875438336
				],
				[
					54.23207568455166,
					15.134524544135957
				],
				[
					55.07287013035,
					16.395748287085667
				],
				[
					55.493267353249166,
					17.23654273288406
				],
				[
					55.913664576148335,
					18.49776647583377
				],
				[
					56.33409387329971,
					19.338560921632165
				],
				[
					56.33409387329971,
					20.179387441682707
				],
				[
					56.33409387329971,
					21.44057911038027
				],
				[
					56.754491096198876,
					22.28140563043081
				],
				[
					56.754491096198876,
					22.70180285332998
				],
				[
					56.754491096198876,
					23.542597299128374
				],
				[
					56.33409387329971,
					24.383423819178915
				],
				[
					56.33409387329971,
					25.224218264977253
				],
				[
					56.33409387329971,
					25.64461548787648
				],
				[
					56.33409387329971,
					26.065044785027794
				],
				[
					55.913664576148335,
					26.90583923082619
				],
				[
					55.913664576148335,
					27.746633676624583
				],
				[
					55.913664576148335,
					28.1670629737759
				],
				[
					55.913664576148335,
					28.587460196675124
				],
				[
					55.493267353249166,
					29.007857419574293
				],
				[
					55.07287013035,
					29.848651865372688
				],
				[
					55.07287013035,
					30.68947838542323
				],
				[
					54.652472907450715,
					31.109875608322398
				],
				[
					54.652472907450715,
					31.530272831221623
				],
				[
					54.23207568455166,
					31.950670054120792
				],
				[
					54.23207568455166,
					32.37109935127211
				],
				[
					53.811646387400174,
					32.79149657417133
				],
				[
					53.811646387400174,
					33.2118937970705
				],
				[
					53.39124916450112,
					33.63229101996973
				],
				[
					53.39124916450112,
					34.052688242868896
				],
				[
					52.970851941601836,
					34.47311754002021
				],
				[
					52.970851941601836,
					35.313911985818606
				],
				[
					52.55045471870267,
					35.73430920871783
				],
				[
					52.55045471870267,
					36.154706431617
				],
				[
					52.1300574958035,
					36.575135728768316
				],
				[
					51.709628198652126,
					36.99553295166754
				],
				[
					51.28923097575296,
					37.41593017456671
				],
				[
					50.868833752853675,
					37.836327397465936
				],
				[
					50.868833752853675,
					38.256724620365105
				],
				[
					50.44843652995462,
					38.256724620365105
				],
				[
					50.02803930705534,
					38.67715391751648
				],
				[
					49.60761000990408,
					39.097551140415646
				],
				[
					49.187212787004796,
					39.097551140415646
				],
				[
					48.76681556410563,
					39.517948363314815
				],
				[
					48.34641834120646,
					39.517948363314815
				],
				[
					47.50559182115592,
					39.93834558621404
				],
				[
					47.08519459825675,
					40.35874280911321
				],
				[
					46.66479737535758,
					40.35874280911321
				],
				[
					46.2444001524583,
					40.77917210626458
				],
				[
					45.82400292955913,
					40.77917210626458
				],
				[
					45.403573632407756,
					40.77917210626458
				],
				[
					44.56277918660942,
					40.77917210626458
				],
				[
					44.14238196371025,
					41.19956932916375
				],
				[
					43.72198474081108,
					41.19956932916375
				],
				[
					43.30155544365971,
					41.19956932916375
				],
				[
					42.88115822076054,
					41.19956932916375
				],
				[
					42.46076099786126,
					41.19956932916375
				],
				[
					42.0403637749622,
					41.19956932916375
				],
				[
					41.61996655206292,
					41.19956932916375
				],
				[
					42.0403637749622,
					41.19956932916375
				],
				[
					41.61996655206292,
					41.19956932916375
				],
				[
					42.0403637749622,
					41.19956932916375
				],
				[
					41.61996655206292,
					41.19956932916375
				],
				[
					41.19953725491166,
					41.19956932916375
				],
				[
					40.77914003201238,
					41.19956932916375
				],
				[
					39.93834558621404,
					41.19956932916375
				],
				[
					39.51794836331476,
					41.19956932916375
				],
				[
					38.67712184326422,
					41.19956932916375
				],
				[
					37.83632739746588,
					41.19956932916375
				],
				[
					37.41593017456671,
					41.19956932916375
				],
				[
					36.99550087741534,
					41.19956932916375
				],
				[
					36.57510365451617,
					41.61996655206292
				],
				[
					36.154706431617,
					41.61996655206292
				],
				[
					35.73430920871783,
					41.61996655206292
				],
				[
					35.31391198581866,
					41.61996655206292
				],
				[
					34.89348268866729,
					41.61996655206292
				],
				[
					34.05268824286884,
					41.61996655206292
				],
				[
					33.63229101996967,
					41.61996655206292
				],
				[
					33.2118937970705,
					41.61996655206292
				],
				[
					32.79146449991924,
					41.61996655206292
				],
				[
					32.37106727701996,
					41.61996655206292
				],
				[
					31.950670054120792,
					41.61996655206292
				],
				[
					31.530272831221623,
					41.61996655206292
				],
				[
					30.689446311171082,
					41.61996655206292
				],
				[
					30.2690490882718,
					42.040363774962145
				],
				[
					29.848651865372744,
					42.040363774962145
				],
				[
					29.428254642473462,
					42.040363774962145
				],
				[
					29.007857419574293,
					42.040363774962145
				],
				[
					28.167030899523752,
					42.040363774962145
				],
				[
					27.746633676624583,
					42.040363774962145
				],
				[
					27.3262364537253,
					42.040363774962145
				],
				[
					26.905839230826246,
					42.040363774962145
				],
				[
					26.48540993367476,
					42.040363774962145
				],
				[
					26.065012710775704,
					42.040363774962145
				],
				[
					25.644615487876422,
					42.040363774962145
				],
				[
					25.224218264977253,
					41.61996655206292
				],
				[
					24.803821042078084,
					41.61996655206292
				],
				[
					24.383391744926712,
					41.61996655206292
				],
				[
					23.962994522027543,
					41.61996655206292
				],
				[
					23.122200076229205,
					41.61996655206292
				],
				[
					22.701802853329923,
					41.61996655206292
				],
				[
					22.281373556178664,
					41.61996655206292
				],
				[
					21.860976333279382,
					41.61996655206292
				],
				[
					21.440579110380327,
					41.61996655206292
				],
				[
					20.599784664581875,
					41.61996655206292
				],
				[
					19.758958144531334,
					41.61996655206292
				],
				[
					19.338560921632165,
					41.61996655206292
				],
				[
					18.918163698732883,
					41.61996655206292
				],
				[
					18.497766475833828,
					41.61996655206292
				],
				[
					18.077337178682342,
					41.61996655206292
				],
				[
					17.656939955783287,
					41.61996655206292
				],
				[
					17.236542732884004,
					41.61996655206292
				],
				[
					16.816145509984835,
					41.61996655206292
				],
				[
					16.395748287085667,
					41.61996655206292
				],
				[
					15.975318989934294,
					41.61996655206292
				],
				[
					15.554921767035125,
					41.61996655206292
				],
				[
					15.134524544135843,
					41.61996655206292
				],
				[
					14.714127321236788,
					41.61996655206292
				],
				[
					14.293730098337505,
					41.61996655206292
				],
				[
					13.452903578286964,
					42.040363774962145
				],
				[
					13.032506355387795,
					41.61996655206292
				],
				[
					12.612109132488627,
					41.61996655206292
				],
				[
					12.191711909589458,
					41.61996655206292
				],
				[
					12.191711909589458,
					41.19956932916375
				],
				[
					11.771282612438085,
					41.19956932916375
				],
				[
					11.350885389538917,
					41.19956932916375
				],
				[
					10.930488166639748,
					41.19956932916375
				],
				[
					10.510090943740465,
					41.19956932916375
				],
				[
					10.08969372084141,
					41.19956932916375
				],
				[
					9.669264423689924,
					41.19956932916375
				],
				[
					9.248867200790869,
					41.19956932916375
				],
				[
					8.828469977891586,
					40.77917210626458
				],
				[
					8.408072754992418,
					40.77917210626458
				],
				[
					7.987675532093249,
					40.77917210626458
				],
				[
					7.5672462349418765,
					40.77917210626458
				],
				[
					7.146849012042708,
					40.77917210626458
				],
				[
					6.726451789143425,
					40.77917210626458
				],
				[
					6.30605456624437,
					40.77917210626458
				],
				[
					5.885657343345088,
					40.77917210626458
				],
				[
					5.465228046193829,
					40.77917210626458
				],
				[
					5.465228046193829,
					41.19956932916375
				],
				[
					5.0448308232945465,
					41.19956932916375
				],
				[
					4.624433600395378,
					41.19956932916375
				],
				[
					4.204036377496209,
					41.19956932916375
				],
				[
					3.7836391545969263,
					41.19956932916375
				],
				[
					3.3632098574456677,
					41.19956932916375
				],
				[
					2.942812634546499,
					41.19956932916375
				],
				[
					2.52241541164733,
					41.19956932916375
				],
				[
					2.1020181887480476,
					41.19956932916375
				],
				[
					1.6816209658488788,
					41.19956932916375
				],
				[
					1.2611916686975064,
					41.19956932916375
				],
				[
					0.8407944457984513,
					41.19956932916375
				],
				[
					0.4203972228991688,
					41.19956932916375
				],
				[
					0,
					41.19956932916375
				],
				[
					-0.4203972228991688,
					41.19956932916375
				],
				[
					-0.8408265200505411,
					41.19956932916375
				],
				[
					-1.26122374294971,
					41.19956932916375
				],
				[
					-1.6816209658489925,
					41.19956932916375
				],
				[
					-1.6816209658489925,
					40.77917210626458
				],
				[
					-2.1020181887480476,
					41.19956932916375
				],
				[
					-2.52241541164733,
					41.19956932916375
				],
				[
					-2.9428447087985887,
					41.19956932916375
				],
				[
					-3.3632419316978712,
					40.77917210626458
				],
				[
					-2.9428447087985887,
					40.77917210626458
				],
				[
					-2.1020181887480476,
					41.19956932916375
				],
				[
					-2.1020181887480476,
					41.19956932916375
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0029296875,
				0.4560546875,
				0.677734375,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.14453125,
				0.0068359375,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 523,
			"versionNonce": 1497311620,
			"isDeleted": false,
			"id": "WxO-zoFfUurboh5uNX90c",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 795.8736975200898,
			"y": 92.1361280813187,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 2.1020181887481613,
			"height": 42.881190295012686,
			"seed": 224375001,
			"groupIds": [
				"VozzIzLKoiJH4q1gUTW3E",
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223439,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					0.4204132600252706
				],
				[
					0.4203972228991688,
					0.4204132600252706
				],
				[
					0.4203972228991688,
					0.8408104829244394
				],
				[
					0.4203972228991688,
					1.261207705823665
				],
				[
					0.4203972228991688,
					1.6816209658489356
				],
				[
					0.8408265200505411,
					2.1020181887481044
				],
				[
					0.8408265200505411,
					2.942828671672544
				],
				[
					0.8408265200505411,
					3.3632258945717695
				],
				[
					0.8408265200505411,
					4.204036377496209
				],
				[
					0.8408265200505411,
					5.044846860420648
				],
				[
					1.26122374294971,
					5.8856573433451445
				],
				[
					1.26122374294971,
					6.306054566244313
				],
				[
					1.26122374294971,
					7.146881086294854
				],
				[
					1.26122374294971,
					8.408072754992418
				],
				[
					1.26122374294971,
					8.828469977891586
				],
				[
					1.26122374294971,
					9.669296497942128
				],
				[
					1.26122374294971,
					10.510090943740522
				],
				[
					1.26122374294971,
					11.350917463791063
				],
				[
					1.26122374294971,
					12.191711909589458
				],
				[
					1.26122374294971,
					12.612109132488627
				],
				[
					1.26122374294971,
					13.032506355387852
				],
				[
					1.26122374294971,
					13.452935652539168
				],
				[
					1.26122374294971,
					13.873332875438336
				],
				[
					1.26122374294971,
					14.293730098337562
				],
				[
					1.26122374294971,
					14.714127321236731
				],
				[
					1.26122374294971,
					15.134524544135957
				],
				[
					1.26122374294971,
					15.554953841287272
				],
				[
					1.26122374294971,
					15.975351064186441
				],
				[
					1.26122374294971,
					16.395748287085667
				],
				[
					1.26122374294971,
					17.23654273288406
				],
				[
					1.26122374294971,
					17.656972030035377
				],
				[
					1.6816209658488788,
					18.077369252934545
				],
				[
					1.6816209658488788,
					18.49776647583377
				],
				[
					1.26122374294971,
					18.91816369873294
				],
				[
					1.6816209658488788,
					18.91816369873294
				],
				[
					1.6816209658488788,
					19.338560921632165
				],
				[
					1.6816209658488788,
					19.75899021878348
				],
				[
					1.6816209658488788,
					20.599784664581875
				],
				[
					1.26122374294971,
					21.020181887481044
				],
				[
					1.6816209658488788,
					21.44057911038027
				],
				[
					1.6816209658488788,
					21.861008407531585
				],
				[
					1.6816209658488788,
					22.28140563043081
				],
				[
					1.6816209658488788,
					22.70180285332998
				],
				[
					1.6816209658488788,
					23.12220007622915
				],
				[
					1.6816209658488788,
					23.542597299128374
				],
				[
					1.6816209658488788,
					23.96302659627969
				],
				[
					1.6816209658488788,
					24.383423819178915
				],
				[
					1.6816209658488788,
					24.803821042078084
				],
				[
					1.6816209658488788,
					25.224218264977253
				],
				[
					1.6816209658488788,
					25.64461548787648
				],
				[
					1.6816209658488788,
					26.065044785027794
				],
				[
					1.6816209658488788,
					26.48544200792702
				],
				[
					1.6816209658488788,
					26.90583923082619
				],
				[
					1.6816209658488788,
					27.326236453725357
				],
				[
					1.6816209658488788,
					27.746633676624583
				],
				[
					1.6816209658488788,
					28.1670629737759
				],
				[
					1.6816209658488788,
					28.587460196675124
				],
				[
					1.6816209658488788,
					29.007857419574293
				],
				[
					1.6816209658488788,
					29.42825464247352
				],
				[
					1.6816209658488788,
					29.848651865372688
				],
				[
					1.26122374294971,
					30.269081162524003
				],
				[
					1.26122374294971,
					30.68947838542323
				],
				[
					1.26122374294971,
					31.109875608322398
				],
				[
					1.26122374294971,
					31.530272831221623
				],
				[
					1.26122374294971,
					31.950670054120792
				],
				[
					1.26122374294971,
					32.37109935127211
				],
				[
					1.26122374294971,
					32.79149657417133
				],
				[
					1.26122374294971,
					33.63229101996973
				],
				[
					1.26122374294971,
					34.47311754002021
				],
				[
					1.26122374294971,
					34.89351476291944
				],
				[
					1.26122374294971,
					35.313911985818606
				],
				[
					1.26122374294971,
					35.73430920871783
				],
				[
					1.26122374294971,
					36.154706431617
				],
				[
					0.8408265200505411,
					36.154706431617
				],
				[
					0.8408265200505411,
					36.575135728768316
				],
				[
					0.8408265200505411,
					36.99553295166754
				],
				[
					0.8408265200505411,
					37.41593017456671
				],
				[
					0.8408265200505411,
					37.836327397465936
				],
				[
					0.8408265200505411,
					38.256724620365105
				],
				[
					0.8408265200505411,
					39.097551140415646
				],
				[
					0.8408265200505411,
					39.517948363314815
				],
				[
					0.8408265200505411,
					39.93834558621404
				],
				[
					0.8408265200505411,
					40.35874280911321
				],
				[
					0.8408265200505411,
					40.77917210626458
				],
				[
					0.8408265200505411,
					41.19956932916375
				],
				[
					0.8408265200505411,
					41.61996655206292
				],
				[
					0.8408265200505411,
					42.040363774962145
				],
				[
					0.8408265200505411,
					42.460760997861314
				],
				[
					0.4203972228991688,
					42.460760997861314
				],
				[
					0.8408265200505411,
					42.881190295012686
				],
				[
					0.8408265200505411,
					42.460760997861314
				],
				[
					1.26122374294971,
					42.040363774962145
				],
				[
					1.6816209658488788,
					41.19956932916375
				],
				[
					2.1020181887481613,
					39.517948363314815
				],
				[
					2.1020181887481613,
					39.517948363314815
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0029296875,
				0.3876953125,
				0.6513671875,
				0.7490234375,
				0.8154296875,
				0.8701171875,
				0.9833984375,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9365234375,
				0.66796875,
				0.146484375,
				0,
				0
			]
		},
		{
			"type": "line",
			"version": 299,
			"versionNonce": 1019551932,
			"isDeleted": false,
			"id": "c_6tbqe4IWYL4QV-94dmk",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 720.4112573737332,
			"y": 36.853043302393075,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 77.35427576078075,
			"height": 2.1020181887481044,
			"seed": 1373040313,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223439,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					77.35427576078075,
					2.1020181887481044
				]
			]
		},
		{
			"type": "line",
			"version": 340,
			"versionNonce": 908548356,
			"isDeleted": false,
			"id": "xVQIK6n8cbssoNx9Rkiiv",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 724.6152937512295,
			"y": 118.8317526635692,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 73.57063660618383,
			"height": 0.4203972228991688,
			"seed": 2023995737,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223439,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					73.57063660618383,
					0.4203972228991688
				]
			]
		},
		{
			"type": "line",
			"version": 443,
			"versionNonce": 626633020,
			"isDeleted": false,
			"id": "9gL6IAJ7uod3gd2aTweap",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 740.5906448154158,
			"y": 118.8317526635692,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 2.1020181887481613,
			"height": 55.49328339037527,
			"seed": 233737145,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223439,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					2.1020181887481613,
					-55.49328339037527
				]
			]
		},
		{
			"type": "line",
			"version": 284,
			"versionNonce": 895326340,
			"isDeleted": false,
			"id": "rAKNccbFq9ji_jfcjHVC9",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 741.4314392612143,
			"y": 63.75888253321932,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 52.97088401585404,
			"height": 0.42039722289919723,
			"seed": 2013957463,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223439,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					52.97088401585404,
					0.42039722289919723
				]
			]
		},
		{
			"type": "line",
			"version": 280,
			"versionNonce": 189342140,
			"isDeleted": false,
			"id": "6Mc1F1rV9V7aHzsgB_81O",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 719.5704629279346,
			"y": 52.4079811065543,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1.2612237429495963,
			"height": 54.23205964742553,
			"seed": 1336274233,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223439,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-1.2612237429495963,
					54.23205964742553
				]
			]
		},
		{
			"type": "line",
			"version": 295,
			"versionNonce": 44034052,
			"isDeleted": false,
			"id": "u4YNZsxO9BbinPMtQYKAH",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 714.5256321046402,
			"y": 106.21964353108058,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 83.23990102987364,
			"height": 1.6816209658489356,
			"seed": 1762966617,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223439,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					83.23990102987364,
					1.6816209658489356
				]
			]
		},
		{
			"type": "line",
			"version": 303,
			"versionNonce": 1706396220,
			"isDeleted": false,
			"id": "2DaoKga2JQIyD9zT7yBwZ",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 853.6792297849145,
			"y": 56.19162026115123,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 62.64014843954408,
			"height": 2.1020181887481044,
			"seed": 656895833,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223439,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					62.64014843954408,
					2.1020181887481044
				]
			]
		},
		{
			"type": "line",
			"version": 244,
			"versionNonce": 569132932,
			"isDeleted": false,
			"id": "FbGr9LNz0KWl4MZm75pYR",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 914.2173600357103,
			"y": 58.71403567279856,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0.42042929715125865,
			"height": 35.31389594869253,
			"seed": 1683291351,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223439,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-0.42042929715125865,
					35.31389594869253
				]
			]
		},
		{
			"type": "line",
			"version": 266,
			"versionNonce": 2004935356,
			"isDeleted": false,
			"id": "7jkaSlT52uCI0UcllpPul",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 912.9561362927609,
			"y": 94.02793162149112,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 43.72198474081097,
			"height": 0.8408265200505411,
			"seed": 1324372567,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223439,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					43.72198474081097,
					0.8408265200505411
				]
			]
		},
		{
			"type": "line",
			"version": 306,
			"versionNonce": 1736488708,
			"isDeleted": false,
			"id": "dlPRuGPZ9F8gBR5S837YC",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 856.622042419461,
			"y": 117.57056099487158,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 101.31730235706061,
			"height": 1.26122374294971,
			"seed": 1937038391,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223439,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					101.31730235706061,
					-1.26122374294971
				]
			]
		},
		{
			"type": "line",
			"version": 282,
			"versionNonce": 1464675132,
			"isDeleted": false,
			"id": "7tOZOC501oFQlc86Ed9r1",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 722.730567188007,
			"y": 137.3215790808258,
			"strokeColor": "#495057",
			"backgroundColor": "transparent",
			"width": 540.9689714269887,
			"height": 130.65775683689424,
			"seed": 1720149751,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223439,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					540.9689714269887,
					130.65775683689424
				]
			]
		},
		{
			"type": "line",
			"version": 298,
			"versionNonce": 1876637316,
			"isDeleted": false,
			"id": "jZehSkg_4euUkTLwSlATU",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 723.4946360465831,
			"y": 136.55751022224968,
			"strokeColor": "#495057",
			"backgroundColor": "transparent",
			"width": 540.2049025684125,
			"height": 6.876736316619144,
			"seed": 2109192503,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223439,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					540.2049025684125,
					6.876736316619144
				]
			]
		},
		{
			"type": "line",
			"version": 287,
			"versionNonce": 2004640700,
			"isDeleted": false,
			"id": "rbgGUZ2JRtWE1WBq0IOhd",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 722.730567188007,
			"y": 141.90605052699948,
			"strokeColor": "#495057",
			"backgroundColor": "transparent",
			"width": 544.7893740145862,
			"height": 123.78102052027504,
			"seed": 2072663895,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223439,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					544.7893740145862,
					-123.78102052027504
				]
			]
		},
		{
			"type": "line",
			"version": 282,
			"versionNonce": 398050820,
			"isDeleted": false,
			"id": "AHSJt5Sh3LmFglUIuOUKx",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 723.4946360465831,
			"y": 144.19831539744496,
			"strokeColor": "#495057",
			"backgroundColor": "transparent",
			"width": 540.969029721706,
			"height": 251.382501922865,
			"seed": 1164110329,
			"groupIds": [
				"K5HnaSN8cHWOmeUrchnc6"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223439,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					540.969029721706,
					-251.382501922865
				]
			]
		},
		{
			"type": "rectangle",
			"version": 1410,
			"versionNonce": 1856488708,
			"isDeleted": false,
			"id": "e7ZLnfDdCFVYSKCmc5bzX",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1189.2603913289533,
			"y": 342.9064262109098,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 112.30011255130835,
			"height": 118.32467760697281,
			"seed": 97379097,
			"groupIds": [
				"ZUq1PDvxvHm0yuzH4n5ND",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "sharp",
			"boundElements": [
				{
					"id": "31VcK4ux",
					"type": "text"
				}
			],
			"updated": 1662511267740,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 933,
			"versionNonce": 73792828,
			"isDeleted": false,
			"id": "31VcK4ux",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1194.2603913289533,
			"y": 393.5687650143962,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 102.30011255130835,
			"height": 17,
			"seed": 1892169463,
			"groupIds": [
				"ZUq1PDvxvHm0yuzH4n5ND",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"fontSize": 13.865014610506565,
			"fontFamily": 1,
			"text": "8kx8",
			"rawText": "8kx8",
			"baseline": 12,
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "e7ZLnfDdCFVYSKCmc5bzX",
			"originalText": "8kx8"
		},
		{
			"type": "line",
			"version": 1228,
			"versionNonce": 1525712004,
			"isDeleted": false,
			"id": "Ez2QZbolVVlt59Uj2cOOF",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1155.183513088485,
			"y": 348.7473694482318,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 137631737,
			"groupIds": [
				"ZUq1PDvxvHm0yuzH4n5ND",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1287,
			"versionNonce": 1839920572,
			"isDeleted": false,
			"id": "3w49nN3eWFIPRED95zbGh",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1155.0709511821249,
			"y": 354.9922918468011,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 1454653463,
			"groupIds": [
				"ZUq1PDvxvHm0yuzH4n5ND",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1295,
			"versionNonce": 1324700676,
			"isDeleted": false,
			"id": "_UnTNn53IQUJ92M3eTevy",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1155.1546323076784,
			"y": 362.7537337077682,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 1304473817,
			"groupIds": [
				"ZUq1PDvxvHm0yuzH4n5ND",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1356,
			"versionNonce": 1153228348,
			"isDeleted": false,
			"id": "uz88flcJ-LibrCflMMDYD",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1155.1171010667351,
			"y": 368.50963681179894,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 1887577399,
			"groupIds": [
				"ZUq1PDvxvHm0yuzH4n5ND",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1257,
			"versionNonce": 414462852,
			"isDeleted": false,
			"id": "4urrVj4gmWAdHxcHZIGfY",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1155.1070370170198,
			"y": 374.68278997616983,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 1812409785,
			"groupIds": [
				"ZUq1PDvxvHm0yuzH4n5ND",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1320,
			"versionNonce": 578664124,
			"isDeleted": false,
			"id": "wETFCN9NDgHGwfq24DdSX",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1154.6898010939537,
			"y": 380.4113774663034,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 496395863,
			"groupIds": [
				"ZUq1PDvxvHm0yuzH4n5ND",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1327,
			"versionNonce": 376120068,
			"isDeleted": false,
			"id": "R_3fxJ54NGZxiZJBu6Pdf",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1155.092730422906,
			"y": 388.1109198941173,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 2049642137,
			"groupIds": [
				"ZUq1PDvxvHm0yuzH4n5ND",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1388,
			"versionNonce": 865042236,
			"isDeleted": false,
			"id": "j2ogPPqRZnNh11FRsN6sL",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1154.8614389039728,
			"y": 394.50559756115797,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 1556448119,
			"groupIds": [
				"ZUq1PDvxvHm0yuzH4n5ND",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1279,
			"versionNonce": 781722244,
			"isDeleted": false,
			"id": "ty7GOjZG6aSCvs7LPNvTQ",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1154.0600135080892,
			"y": 400.308118775425,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 1591726969,
			"groupIds": [
				"ZUq1PDvxvHm0yuzH4n5ND",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1341,
			"versionNonce": 1079261116,
			"isDeleted": false,
			"id": "dDsSrdeumK1YHbljL2jbf",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1153.6578394232736,
			"y": 406.79798701037896,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 1582562455,
			"groupIds": [
				"ZUq1PDvxvHm0yuzH4n5ND",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1348,
			"versionNonce": 1207513604,
			"isDeleted": false,
			"id": "qPt4eszl-qkNEXF4hgBYR",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1154.3297775966323,
			"y": 414.37318517585857,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 1583938649,
			"groupIds": [
				"ZUq1PDvxvHm0yuzH4n5ND",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1408,
			"versionNonce": 888004668,
			"isDeleted": false,
			"id": "hTO5SalogVhYInKp9yvv0",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1154.058672783541,
			"y": 420.03838155530855,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 1442206135,
			"groupIds": [
				"ZUq1PDvxvHm0yuzH4n5ND",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1314,
			"versionNonce": 1099714948,
			"isDeleted": false,
			"id": "80AY6uezAsai2rfky2R-I",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1153.976120416349,
			"y": 426.12288172821707,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 1754925369,
			"groupIds": [
				"ZUq1PDvxvHm0yuzH4n5ND",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 848,
			"versionNonce": 691959996,
			"isDeleted": false,
			"id": "uyaLCXEl",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1192.7408690653526,
			"y": 433.4912956051776,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 14,
			"height": 22,
			"seed": 215024343,
			"groupIds": [
				"ZUq1PDvxvHm0yuzH4n5ND",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"fontSize": 9.301747036482514,
			"fontFamily": 1,
			"text": "CS\nOE",
			"rawText": "CS\nOE",
			"baseline": 19,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "CS\nOE"
		},
		{
			"type": "line",
			"version": 1332,
			"versionNonce": 1787789572,
			"isDeleted": false,
			"id": "xGgbl0sOwTL8COOulBFoi",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1159.476291473845,
			"y": 439.0593255971588,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 29.63565761011434,
			"height": 0,
			"seed": 651590169,
			"groupIds": [
				"ZUq1PDvxvHm0yuzH4n5ND",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					29.63565761011434,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1320,
			"versionNonce": 1760035132,
			"isDeleted": false,
			"id": "26HX_2A9YYW8J-COHp5wb",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1159.6907691432896,
			"y": 449.8914297948253,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 29.63565761011434,
			"height": 0,
			"seed": 863539191,
			"groupIds": [
				"ZUq1PDvxvHm0yuzH4n5ND",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					29.63565761011434,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1032,
			"versionNonce": 2055258244,
			"isDeleted": false,
			"id": "sMTSj5czPWsvqRqFU2j0V",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1305.5134076533438,
			"y": 356.63946114549924,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 66.64546861703714,
			"height": 0,
			"seed": 1242681081,
			"groupIds": [
				"ZUq1PDvxvHm0yuzH4n5ND",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					66.64546861703714,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1093,
			"versionNonce": 2068609468,
			"isDeleted": false,
			"id": "K2sin4Sm8kc4qUpbIFTTv",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1304.5794206951798,
			"y": 367.6680071858283,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 66.64546861703714,
			"height": 0,
			"seed": 1945205015,
			"groupIds": [
				"ZUq1PDvxvHm0yuzH4n5ND",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					66.64546861703714,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1101,
			"versionNonce": 152965124,
			"isDeleted": false,
			"id": "B8av0YZgna45wcnmY6v4h",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1305.9756984262501,
			"y": 383.7334364377822,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 66.64546861703714,
			"height": 0,
			"seed": 416253913,
			"groupIds": [
				"ZUq1PDvxvHm0yuzH4n5ND",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					66.64546861703714,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1160,
			"versionNonce": 730718780,
			"isDeleted": false,
			"id": "gCgNalQ3HYYifKQtrqBDV",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1304.8302694843776,
			"y": 395.57756231440305,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 66.64546861703714,
			"height": 0,
			"seed": 1135623735,
			"groupIds": [
				"ZUq1PDvxvHm0yuzH4n5ND",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					66.64546861703714,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1063,
			"versionNonce": 107310980,
			"isDeleted": false,
			"id": "Zn3u5UPOS2mQnW2aJkdT8",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1305.4728139711594,
			"y": 407.26313758976937,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 66.64546861703714,
			"height": 0,
			"seed": 1025713337,
			"groupIds": [
				"ZUq1PDvxvHm0yuzH4n5ND",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					66.64546861703714,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1125,
			"versionNonce": 277756604,
			"isDeleted": false,
			"id": "Z8VIrNGLdZapm6NAFij-M",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1304.191244056901,
			"y": 419.18166077864305,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 66.64546861703714,
			"height": 0,
			"seed": 1972985687,
			"groupIds": [
				"ZUq1PDvxvHm0yuzH4n5ND",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					66.64546861703714,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1131,
			"versionNonce": 848617220,
			"isDeleted": false,
			"id": "VUfeuQJ8lKhRBggoU-DwF",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1305.499701080519,
			"y": 434.5484474086435,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 66.64546861703714,
			"height": 0,
			"seed": 1387275673,
			"groupIds": [
				"ZUq1PDvxvHm0yuzH4n5ND",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					66.64546861703714,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1193,
			"versionNonce": 351241020,
			"isDeleted": false,
			"id": "tPp88y9IJVG-2so1a26W0",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1305.066975956522,
			"y": 446.34466124075936,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 66.64546861703714,
			"height": 0,
			"seed": 201415799,
			"groupIds": [
				"ZUq1PDvxvHm0yuzH4n5ND",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					66.64546861703714,
					0
				]
			]
		},
		{
			"type": "rectangle",
			"version": 1495,
			"versionNonce": 603143228,
			"isDeleted": false,
			"id": "7X1PeiwyImK80B9yPpb00",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1189.707868338771,
			"y": 492.08999075204264,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 112.30011255130835,
			"height": 118.32467760697281,
			"seed": 888789495,
			"groupIds": [
				"Ed0GVD0AEqd2MAHFdn0Da",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "sharp",
			"boundElements": [
				{
					"id": "LgpzxiuG",
					"type": "text"
				}
			],
			"updated": 1662511398943,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1023,
			"versionNonce": 2131999676,
			"isDeleted": false,
			"id": "LgpzxiuG",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1194.707868338771,
			"y": 542.7523295555291,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 102.30011255130835,
			"height": 17,
			"seed": 329393401,
			"groupIds": [
				"Ed0GVD0AEqd2MAHFdn0Da",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"fontSize": 13.865014610506565,
			"fontFamily": 1,
			"text": "8kx8",
			"rawText": "8kx8",
			"baseline": 12,
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "7X1PeiwyImK80B9yPpb00",
			"originalText": "8kx8"
		},
		{
			"type": "line",
			"version": 1316,
			"versionNonce": 2044980740,
			"isDeleted": false,
			"id": "nMoQaG5LIYJkfIoGf3srO",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1155.6309900983026,
			"y": 497.9309339893648,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 179929879,
			"groupIds": [
				"Ed0GVD0AEqd2MAHFdn0Da",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1375,
			"versionNonce": 2031936572,
			"isDeleted": false,
			"id": "yVmBxpj9CJ0B4aU0blWht",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1155.5184281919426,
			"y": 504.1758563879341,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 971316697,
			"groupIds": [
				"Ed0GVD0AEqd2MAHFdn0Da",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1383,
			"versionNonce": 1589611908,
			"isDeleted": false,
			"id": "RIMxvqYDMkoFbXzlRKRYE",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1155.6021093174961,
			"y": 511.93729824890124,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 417794103,
			"groupIds": [
				"Ed0GVD0AEqd2MAHFdn0Da",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1444,
			"versionNonce": 418184380,
			"isDeleted": false,
			"id": "9qmhVVKGeU_rKlGSQUKZR",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1155.5645780765528,
			"y": 517.693201352932,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 320207545,
			"groupIds": [
				"Ed0GVD0AEqd2MAHFdn0Da",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1345,
			"versionNonce": 1979399428,
			"isDeleted": false,
			"id": "okhB9dol-z9_-5BIkYq8s",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1155.5545140268375,
			"y": 523.8663545173029,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 1298590039,
			"groupIds": [
				"Ed0GVD0AEqd2MAHFdn0Da",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1408,
			"versionNonce": 1747322172,
			"isDeleted": false,
			"id": "EnnH5cgSvTw4MLpVULfKh",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1155.1372781037715,
			"y": 529.5949420074364,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 1339571097,
			"groupIds": [
				"Ed0GVD0AEqd2MAHFdn0Da",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1415,
			"versionNonce": 420805764,
			"isDeleted": false,
			"id": "ShmBL9h-A1sXajWp1y9sl",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1155.5402074327237,
			"y": 537.2944844352503,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 1703782007,
			"groupIds": [
				"Ed0GVD0AEqd2MAHFdn0Da",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1476,
			"versionNonce": 1814691260,
			"isDeleted": false,
			"id": "u3gj7vMLE42WXsGoTYTnF",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1155.3089159137905,
			"y": 543.689162102291,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 1079992441,
			"groupIds": [
				"Ed0GVD0AEqd2MAHFdn0Da",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1367,
			"versionNonce": 1103809540,
			"isDeleted": false,
			"id": "jZ32axpN7Z8ldgG6RY5W0",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1154.507490517907,
			"y": 549.491683316558,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 2080663,
			"groupIds": [
				"Ed0GVD0AEqd2MAHFdn0Da",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1429,
			"versionNonce": 773514812,
			"isDeleted": false,
			"id": "kmyUx7vnRtj-VE_7t65Tn",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1154.1053164330913,
			"y": 555.981551551512,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 1651435865,
			"groupIds": [
				"Ed0GVD0AEqd2MAHFdn0Da",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1436,
			"versionNonce": 35302276,
			"isDeleted": false,
			"id": "Ya0jHXxX_29Baicdh13Ag",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1154.77725460645,
			"y": 563.5567497169917,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 1867625655,
			"groupIds": [
				"Ed0GVD0AEqd2MAHFdn0Da",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1496,
			"versionNonce": 1121631932,
			"isDeleted": false,
			"id": "a-ipAMI29r8HTk4ZK9XwO",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1154.5061497933586,
			"y": 569.2219460964417,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 794449465,
			"groupIds": [
				"Ed0GVD0AEqd2MAHFdn0Da",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1402,
			"versionNonce": 2084739844,
			"isDeleted": false,
			"id": "na3-u_nGDzaEgcdP_51V-",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1154.4235974261667,
			"y": 575.3064462693502,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 1254622679,
			"groupIds": [
				"Ed0GVD0AEqd2MAHFdn0Da",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 936,
			"versionNonce": 1393264444,
			"isDeleted": false,
			"id": "6Ma4qqd4",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1193.1883460751703,
			"y": 582.6748601463106,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 14,
			"height": 22,
			"seed": 704980761,
			"groupIds": [
				"Ed0GVD0AEqd2MAHFdn0Da",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"fontSize": 9.301747036482514,
			"fontFamily": 1,
			"text": "CS\nOE",
			"rawText": "CS\nOE",
			"baseline": 19,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "CS\nOE"
		},
		{
			"type": "line",
			"version": 1420,
			"versionNonce": 1522571908,
			"isDeleted": false,
			"id": "IlDI-UNMViHXEAm8ZTzz4",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1159.9237684836628,
			"y": 588.242890138292,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 29.63565761011434,
			"height": 0,
			"seed": 1100428023,
			"groupIds": [
				"Ed0GVD0AEqd2MAHFdn0Da",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					29.63565761011434,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1408,
			"versionNonce": 588201916,
			"isDeleted": false,
			"id": "uHWsjeyCDYVaMoaxW-0Jd",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1160.1382461531073,
			"y": 599.0749943359584,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 29.63565761011434,
			"height": 0,
			"seed": 753064953,
			"groupIds": [
				"Ed0GVD0AEqd2MAHFdn0Da",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					29.63565761011434,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1120,
			"versionNonce": 1213377028,
			"isDeleted": false,
			"id": "rPPsUmzoj66Qbd5uUe8jQ",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1305.9608846631638,
			"y": 505.82302568663226,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 66.64546861703714,
			"height": 0,
			"seed": 742636567,
			"groupIds": [
				"Ed0GVD0AEqd2MAHFdn0Da",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					66.64546861703714,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1181,
			"versionNonce": 453503036,
			"isDeleted": false,
			"id": "t5ycJtJxMeTZ46oXTdoGZ",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1305.0268977049998,
			"y": 516.8515717269613,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 66.64546861703714,
			"height": 0,
			"seed": 2012673241,
			"groupIds": [
				"Ed0GVD0AEqd2MAHFdn0Da",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					66.64546861703714,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1189,
			"versionNonce": 1744226692,
			"isDeleted": false,
			"id": "k9WF3VCVnvJWr_Dn6Vi9B",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1306.42317543607,
			"y": 532.9170009789152,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 66.64546861703714,
			"height": 0,
			"seed": 1589780791,
			"groupIds": [
				"Ed0GVD0AEqd2MAHFdn0Da",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					66.64546861703714,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1248,
			"versionNonce": 1322746044,
			"isDeleted": false,
			"id": "qUWBvi9Qx7a0wWO7kKzgN",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1305.2777464941976,
			"y": 544.7611268555361,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 66.64546861703714,
			"height": 0,
			"seed": 2127884729,
			"groupIds": [
				"Ed0GVD0AEqd2MAHFdn0Da",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					66.64546861703714,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1151,
			"versionNonce": 1290467588,
			"isDeleted": false,
			"id": "CuCYBNaslI0KUQXx6iKnz",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1305.9202909809794,
			"y": 556.4467021309024,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 66.64546861703714,
			"height": 0,
			"seed": 980869719,
			"groupIds": [
				"Ed0GVD0AEqd2MAHFdn0Da",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					66.64546861703714,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1213,
			"versionNonce": 102762812,
			"isDeleted": false,
			"id": "VRPnVsePkkPqmp2w-QYuz",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1304.638721066721,
			"y": 568.3652253197762,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 66.64546861703714,
			"height": 0,
			"seed": 1990218393,
			"groupIds": [
				"Ed0GVD0AEqd2MAHFdn0Da",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					66.64546861703714,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1219,
			"versionNonce": 1923954820,
			"isDeleted": false,
			"id": "9BCZxlC9pf-7mHR75rwB0",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1305.9471780903389,
			"y": 583.7320119497766,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 66.64546861703714,
			"height": 0,
			"seed": 3571575,
			"groupIds": [
				"Ed0GVD0AEqd2MAHFdn0Da",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					66.64546861703714,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1281,
			"versionNonce": 1145274812,
			"isDeleted": false,
			"id": "57Np5HM2mCOQ-IlOEtf32",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1305.5144529663419,
			"y": 595.5282257818925,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 66.64546861703714,
			"height": 0,
			"seed": 604804985,
			"groupIds": [
				"Ed0GVD0AEqd2MAHFdn0Da",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					66.64546861703714,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 638,
			"versionNonce": 888899588,
			"isDeleted": false,
			"id": "_kB_pO-hiOCadcY8ILH_D",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 687.1228732229737,
			"y": 717.3497572640621,
			"strokeColor": "#495057",
			"backgroundColor": "transparent",
			"width": 113.70431261977944,
			"height": 0,
			"seed": 393038841,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					113.70431261977944,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 774,
			"versionNonce": 1348725308,
			"isDeleted": false,
			"id": "JuzzSOh1P6Jccnd-QsuCV",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 685.8687901383237,
			"y": 736.1611736308695,
			"strokeColor": "#495057",
			"backgroundColor": "transparent",
			"width": 113.70431261977944,
			"height": 0,
			"seed": 1361882233,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					113.70431261977944,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 752,
			"versionNonce": 1205069700,
			"isDeleted": false,
			"id": "k05qDxSyCAVLko46qVFO7",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 686.1474516436543,
			"y": 755.6692224988718,
			"strokeColor": "#495057",
			"backgroundColor": "transparent",
			"width": 113.70431261977944,
			"height": 0,
			"seed": 1197494103,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					113.70431261977944,
					0
				]
			]
		},
		{
			"type": "freedraw",
			"version": 460,
			"versionNonce": 1029915324,
			"isDeleted": false,
			"id": "n2AmKQ1Tq29mJCSImZRWf",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 658.8361364517602,
			"y": 727.9398725247169,
			"strokeColor": "#495057",
			"backgroundColor": "transparent",
			"width": 10.032728463596527,
			"height": 10.032749725728763,
			"seed": 195030775,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-0.5573655349261344
				],
				[
					-0.5573867970583706,
					-0.5573655349261344
				],
				[
					-1.114752331984505,
					-0.5573655349261344
				],
				[
					-1.6721178669106393,
					-1.1147310698523256
				],
				[
					-2.786870198895258,
					-1.1147310698523256
				],
				[
					-3.901622530879763,
					-0.5573655349261344
				],
				[
					-5.573740397790516,
					0.5574080591906636
				],
				[
					-7.245858264701155,
					1.114773594116798
				],
				[
					-8.360610596685774,
					2.2295046639691236
				],
				[
					-8.917997393744145,
					2.786870198895258
				],
				[
					-9.475362928670279,
					3.3442782580859216
				],
				[
					-9.475362928670279,
					4.45900932793819
				],
				[
					-9.475362928670279,
					5.016374862864382
				],
				[
					-8.360610596685774,
					6.13114845698118
				],
				[
					-7.803245061759526,
					6.688513991907314
				],
				[
					-7.245858264701155,
					7.245879526833448
				],
				[
					-6.688492729775021,
					7.80324506175964
				],
				[
					-5.573740397790516,
					8.360610596685774
				],
				[
					-5.016374862864268,
					8.360610596685774
				],
				[
					-3.901622530879763,
					8.360610596685774
				],
				[
					-2.786870198895258,
					8.918018655876438
				],
				[
					-2.22950466396901,
					8.360610596685774
				],
				[
					-1.6721178669106393,
					8.360610596685774
				],
				[
					-0.5573867970583706,
					7.80324506175964
				],
				[
					0,
					7.80324506175964
				],
				[
					0.5573655349262481,
					7.80324506175964
				],
				[
					0.5573655349262481,
					7.80324506175964
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0,
				0.01171875,
				0.36328125,
				0.408203125,
				0.4453125,
				0.517578125,
				0.552734375,
				0.5771484375,
				0.578125,
				0.5751953125,
				0.5751953125,
				0.5751953125,
				0.5634765625,
				0.5556640625,
				0.54296875,
				0.5234375,
				0.4921875,
				0.474609375,
				0.466796875,
				0.4658203125,
				0.4677734375,
				0.46484375,
				0.4521484375,
				0.4384765625,
				0.3818359375,
				0.3330078125,
				0.1640625,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 477,
			"versionNonce": 796153604,
			"isDeleted": false,
			"id": "nGd51jbxpZrqwL8c3XbiD",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 671.0983695793259,
			"y": 728.4972805839076,
			"strokeColor": "#495057",
			"backgroundColor": "transparent",
			"width": 10.590093998522661,
			"height": 11.147480795581032,
			"seed": 526318201,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-0.5574080591906636
				],
				[
					0,
					0
				],
				[
					0,
					-0.5574080591906636
				],
				[
					0.5573655349261344,
					-0.5574080591906636
				],
				[
					0.5573655349261344,
					-1.114773594116798
				],
				[
					0.5573655349261344,
					-1.6721391290429892
				],
				[
					0,
					-2.2295046639691236
				],
				[
					0,
					-2.786870198895258
				],
				[
					-0.5573867970583706,
					-2.786870198895258
				],
				[
					-1.1147523319846186,
					-2.786870198895258
				],
				[
					-1.6721391290429892,
					-2.786870198895258
				],
				[
					-2.2295046639691236,
					-2.786870198895258
				],
				[
					-2.786870198895258,
					-2.2295046639691236
				],
				[
					-3.3442569959536286,
					-2.2295046639691236
				],
				[
					-3.3442569959536286,
					-1.6721391290429892
				],
				[
					-3.9016225308798766,
					-1.114773594116798
				],
				[
					-3.9016225308798766,
					-0.5574080591906636
				],
				[
					-3.9016225308798766,
					0
				],
				[
					-4.459009327938247,
					0.5573655349261344
				],
				[
					-3.9016225308798766,
					0.5573655349261344
				],
				[
					-3.3442569959536286,
					1.1147310698522688
				],
				[
					-2.786870198895258,
					1.1147310698522688
				],
				[
					-2.2295046639691236,
					1.67209660477846
				],
				[
					-1.6721391290429892,
					1.67209660477846
				],
				[
					-1.6721391290429892,
					2.2294621397045944
				],
				[
					-1.1147523319846186,
					2.2294621397045944
				],
				[
					-0.5573867970583706,
					2.786870198895258
				],
				[
					0.5573655349261344,
					3.3442357338213924
				],
				[
					1.1147310698522688,
					3.9016012687475268
				],
				[
					1.6721178669106393,
					4.458966803673718
				],
				[
					2.2294834018368874,
					5.016332338599852
				],
				[
					2.2294834018368874,
					5.573740397790516
				],
				[
					1.6721178669106393,
					6.13110593271665
				],
				[
					1.1147310698522688,
					6.13110593271665
				],
				[
					0.5573655349261344,
					6.688471467642785
				],
				[
					-0.5573867970583706,
					7.245837002568976
				],
				[
					-1.6721391290429892,
					7.80320253749511
				],
				[
					-3.3442569959536286,
					8.360610596685774
				],
				[
					-5.016374862864382,
					8.360610596685774
				],
				[
					-6.131127194848887,
					8.360610596685774
				],
				[
					-7.245879526833505,
					7.80320253749511
				],
				[
					-7.80324506175964,
					7.245837002568976
				],
				[
					-8.360610596685774,
					6.688471467642785
				],
				[
					-7.80324506175964,
					6.688471467642785
				],
				[
					-7.80324506175964,
					6.688471467642785
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0,
				0.12109375,
				0.15625,
				0.228515625,
				0.2802734375,
				0.3076171875,
				0.318359375,
				0.3212890625,
				0.322265625,
				0.326171875,
				0.33203125,
				0.3330078125,
				0.3330078125,
				0.3330078125,
				0.3330078125,
				0.333984375,
				0.333984375,
				0.333984375,
				0.333984375,
				0.3349609375,
				0.3349609375,
				0.333984375,
				0.3359375,
				0.3359375,
				0.3359375,
				0.3359375,
				0.3359375,
				0.333984375,
				0.3359375,
				0.3369140625,
				0.3369140625,
				0.3408203125,
				0.34375,
				0.34765625,
				0.3505859375,
				0.3525390625,
				0.3544921875,
				0.353515625,
				0.35546875,
				0.35546875,
				0.3544921875,
				0.3515625,
				0.34765625,
				0.3056640625,
				0.0078125,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 465,
			"versionNonce": 1910737724,
			"isDeleted": false,
			"id": "QRkU6FbaL95_DvTRIwsi_",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 653.2623960539697,
			"y": 753.0217043147742,
			"strokeColor": "#495057",
			"backgroundColor": "transparent",
			"width": 8.917976131611908,
			"height": 11.704846330507166,
			"seed": 1105393527,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.5573655349262481,
					-0.5573655349261912
				],
				[
					1.1147523319846186,
					-0.5573655349261912
				],
				[
					1.672117866910753,
					-0.5573655349261912
				],
				[
					2.2294834018368874,
					-1.1147310698523256
				],
				[
					2.786870198895258,
					-1.1147310698523256
				],
				[
					3.9016225308798766,
					-1.1147310698523256
				],
				[
					5.016353600732145,
					-0.5573655349261912
				],
				[
					6.131105932716764,
					0
				],
				[
					6.688492729775135,
					1.114773594116798
				],
				[
					7.245858264701269,
					2.2295046639690668
				],
				[
					7.245858264701269,
					3.3442782580859216
				],
				[
					7.245858264701269,
					5.016374862864325
				],
				[
					6.688492729775135,
					6.688513991907314
				],
				[
					6.131105932716764,
					8.360610596685774
				],
				[
					5.573740397790516,
					8.918018655876438
				],
				[
					4.458988065806011,
					10.032749725728706
				],
				[
					2.786870198895258,
					10.59011526065484
				],
				[
					2.2294834018368874,
					10.59011526065484
				],
				[
					1.1147523319846186,
					10.032749725728706
				],
				[
					0,
					9.475384190802572
				],
				[
					-0.5573867970583706,
					8.918018655876438
				],
				[
					-1.114752331984505,
					7.803245061759583
				],
				[
					-1.6721178669106393,
					6.13114845698118
				],
				[
					-1.6721178669106393,
					5.573740397790516
				],
				[
					-1.114752331984505,
					3.3442782580859216
				],
				[
					-0.5573867970583706,
					2.2295046639690668
				],
				[
					0.5573655349262481,
					1.114773594116798
				],
				[
					1.672117866910753,
					0.5574080591906636
				],
				[
					2.786870198895258,
					-0.5573655349261912
				],
				[
					3.9016225308798766,
					-0.5573655349261912
				],
				[
					4.458988065806011,
					0
				],
				[
					5.573740397790516,
					0.5574080591906636
				],
				[
					5.573740397790516,
					0.5574080591906636
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0029296875,
				0.1298828125,
				0.1650390625,
				0.205078125,
				0.2509765625,
				0.2861328125,
				0.328125,
				0.36328125,
				0.38671875,
				0.404296875,
				0.4189453125,
				0.42578125,
				0.4287109375,
				0.4267578125,
				0.423828125,
				0.423828125,
				0.421875,
				0.41015625,
				0.4033203125,
				0.3916015625,
				0.3896484375,
				0.3896484375,
				0.390625,
				0.3916015625,
				0.392578125,
				0.392578125,
				0.3935546875,
				0.3916015625,
				0.3818359375,
				0.3544921875,
				0.3076171875,
				0.1923828125,
				0.01953125,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 449,
			"versionNonce": 945477252,
			"isDeleted": false,
			"id": "fVK3WBSW9LipI0BxEqspL",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 669.4262304502829,
			"y": 753.5791123739649,
			"strokeColor": "#495057",
			"backgroundColor": "transparent",
			"width": 1.6721178669106393,
			"height": 11.704846330507166,
			"seed": 292222553,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.1147735941168548
				],
				[
					0,
					-1.6721391290429892
				],
				[
					0,
					-1.1147735941168548
				],
				[
					0,
					-0.5574080591906636
				],
				[
					0,
					0
				],
				[
					0,
					1.1147310698522688
				],
				[
					0,
					2.2294621397045944
				],
				[
					0,
					3.9016012687475268
				],
				[
					-0.5573655349261344,
					5.016332338599852
				],
				[
					-0.5573655349261344,
					6.688471467642785
				],
				[
					-0.5573655349261344,
					7.80320253749511
				],
				[
					-0.5573655349261344,
					8.917976131611908
				],
				[
					-1.1147310698522688,
					9.475341666538043
				],
				[
					-0.5573655349261344,
					10.032707201464177
				],
				[
					0,
					9.475341666538043
				],
				[
					0.5573867970583706,
					9.475341666538043
				],
				[
					0.5573867970583706,
					9.475341666538043
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.005859375,
				0.099609375,
				0.1533203125,
				0.15625,
				0.2744140625,
				0.29296875,
				0.298828125,
				0.2998046875,
				0.2998046875,
				0.2998046875,
				0.2998046875,
				0.2939453125,
				0.23828125,
				0.201171875,
				0.1220703125,
				0.0478515625,
				0.0009765625,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 444,
			"versionNonce": 809943996,
			"isDeleted": false,
			"id": "jVWKYMogND1izM10NCZIj",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 678.9015933789533,
			"y": 751.9069732449219,
			"strokeColor": "#495057",
			"backgroundColor": "transparent",
			"width": 8.360610596685774,
			"height": 2.786870198895258,
			"seed": 1521967575,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-0.5573655349262481,
					-0.5573655349261344
				],
				[
					-1.1147523319846186,
					0
				],
				[
					-2.2294834018368874,
					0.5573655349261344
				],
				[
					-3.344235733821506,
					0.5573655349261344
				],
				[
					-4.458988065806011,
					1.1147310698523256
				],
				[
					-5.573740397790516,
					1.1147310698523256
				],
				[
					-6.131105932716764,
					1.6721391290429892
				],
				[
					-7.245858264701269,
					1.6721391290429892
				],
				[
					-8.360610596685774,
					2.2295046639691236
				],
				[
					-7.803223799627403,
					2.2295046639691236
				],
				[
					-7.245858264701269,
					2.2295046639691236
				],
				[
					-7.245858264701269,
					2.2295046639691236
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0029296875,
				0.1357421875,
				0.1689453125,
				0.1982421875,
				0.201171875,
				0.201171875,
				0.201171875,
				0.201171875,
				0.201171875,
				0.1845703125,
				0.044921875,
				0.001953125,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 443,
			"versionNonce": 1866819076,
			"isDeleted": false,
			"id": "nlWa8Wsf-jFIDQROF8eoh",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 676.6721099771164,
			"y": 757.4807136427124,
			"strokeColor": "#495057",
			"backgroundColor": "transparent",
			"width": 7.80324506175964,
			"height": 1.6721391290429892,
			"seed": 1785145783,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-1.1147523319846186,
					0.5573655349261344
				],
				[
					-1.6721391290429892,
					0.5573655349261344
				],
				[
					-2.2295046639691236,
					0.5573655349261344
				],
				[
					-3.3442569959536286,
					0.5573655349261344
				],
				[
					-3.9016225308798766,
					0.5573655349261344
				],
				[
					-5.573740397790516,
					1.1147310698523256
				],
				[
					-6.131127194848887,
					1.1147310698523256
				],
				[
					-7.245879526833505,
					1.6721391290429892
				],
				[
					-7.80324506175964,
					1.6721391290429892
				],
				[
					-7.245879526833505,
					1.6721391290429892
				],
				[
					-7.245879526833505,
					1.6721391290429892
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0,
				0.1123046875,
				0.1484375,
				0.1728515625,
				0.23046875,
				0.2451171875,
				0.251953125,
				0.248046875,
				0.208984375,
				0.1767578125,
				0.02734375,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 442,
			"versionNonce": 514780220,
			"isDeleted": false,
			"id": "Y1EMnxkbcke1yareVFM8J",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 677.2294755120425,
			"y": 762.4970885055769,
			"strokeColor": "#495057",
			"backgroundColor": "transparent",
			"width": 9.475362928670279,
			"height": 1.1147310698522688,
			"seed": 1639232121,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-1.114752331984505,
					0
				],
				[
					-1.672117866910753,
					0
				],
				[
					-2.786870198895258,
					0
				],
				[
					-5.016374862864382,
					0.5573655349261344
				],
				[
					-7.245858264701269,
					0.5573655349261344
				],
				[
					-8.917976131611908,
					0.5573655349261344
				],
				[
					-9.475362928670279,
					1.1147310698522688
				],
				[
					-8.917976131611908,
					1.1147310698522688
				],
				[
					-8.360610596685774,
					0.5573655349261344
				],
				[
					-8.360610596685774,
					0.5573655349261344
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0,
				0.130859375,
				0.2001953125,
				0.275390625,
				0.349609375,
				0.37109375,
				0.357421875,
				0.2998046875,
				0.0556640625,
				0.005859375,
				0
			]
		},
		{
			"type": "line",
			"version": 764,
			"versionNonce": 422708612,
			"isDeleted": false,
			"id": "e5FgL89aQxAUCkn-JTtGU",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1092.030526465989,
			"y": 440.0802173163762,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 26.17321629211452,
			"height": 0,
			"seed": 2125397017,
			"groupIds": [
				"xk2k9GywzKY2RMpewkU5x",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					26.17321629211452,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 750,
			"versionNonce": 1325270204,
			"isDeleted": false,
			"id": "zZWoUZdBl7bkWjIq7fCPH",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1118.0728484055392,
			"y": 426.71779657006914,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 26.17321629211452,
			"seed": 1155608055,
			"groupIds": [
				"xk2k9GywzKY2RMpewkU5x",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					26.17321629211452
				]
			]
		},
		{
			"type": "line",
			"version": 843,
			"versionNonce": 727627012,
			"isDeleted": false,
			"id": "iqCXNWURvn-YoZNK9-EWA",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1117.7445752388387,
			"y": 427.0223908684691,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 26.17321629211452,
			"height": 13.08660814605726,
			"seed": 1468666105,
			"groupIds": [
				"xk2k9GywzKY2RMpewkU5x",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					26.17321629211452,
					13.08660814605726
				]
			]
		},
		{
			"type": "line",
			"version": 753,
			"versionNonce": 1188433212,
			"isDeleted": false,
			"id": "Os9enVlQE85UIB23CpjUq",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1118.2390733601496,
			"y": 453.0757050486159,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 26.17321629211452,
			"height": 13.08660814605726,
			"seed": 1251366679,
			"groupIds": [
				"xk2k9GywzKY2RMpewkU5x",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					26.17321629211452,
					-13.08660814605726
				]
			]
		},
		{
			"type": "line",
			"version": 828,
			"versionNonce": 1128887428,
			"isDeleted": false,
			"id": "0c5qOIrLVS8AFY7HWh4yg",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1150.5966647217501,
			"y": 440.45364164901184,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 13.206782687082496,
			"height": 0,
			"seed": 300911065,
			"groupIds": [
				"xk2k9GywzKY2RMpewkU5x",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					13.206782687082496,
					0
				]
			]
		},
		{
			"type": "ellipse",
			"version": 690,
			"versionNonce": 127468988,
			"isDeleted": false,
			"id": "Q0DcD9YSR_vMrIbFbI8A9",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1144.2274131324382,
			"y": 437.26940544901845,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 6.026048412597953,
			"height": 6.026048412597953,
			"seed": 1846107191,
			"groupIds": [
				"xk2k9GywzKY2RMpewkU5x",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 819,
			"versionNonce": 514868228,
			"isDeleted": false,
			"id": "7aTldjapUohtMmkVZqCUe",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 867.7359063671734,
			"y": 726.6226605864557,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 25.95483911818272,
			"height": 0,
			"seed": 947384855,
			"groupIds": [
				"JzWCWzK7Jt465zq2gGBOo",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					25.95483911818272,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 830,
			"versionNonce": 375975484,
			"isDeleted": false,
			"id": "qxt4LQSbrUOssUTfdJ9W7",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 798.5136401051359,
			"y": 718.5374344338976,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 34.60645215757695,
			"height": 0,
			"seed": 550051545,
			"groupIds": [
				"JzWCWzK7Jt465zq2gGBOo",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					34.60645215757695,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 833,
			"versionNonce": 328278916,
			"isDeleted": false,
			"id": "BI0VHGMzmhKqzxA9kf1zD",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 799.0970675552753,
			"y": 735.8507008703785,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 34.60645215757695,
			"height": 0,
			"seed": 50304823,
			"groupIds": [
				"JzWCWzK7Jt465zq2gGBOo",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					34.60645215757695,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 883,
			"versionNonce": 69715644,
			"isDeleted": false,
			"id": "8Ap27Dr_JzQNLY2f-WK8y",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 833.4980773410925,
			"y": 710.2270562989457,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 34.60645215757695,
			"seed": 1607588793,
			"groupIds": [
				"JzWCWzK7Jt465zq2gGBOo",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					34.60645215757695
				]
			]
		},
		{
			"type": "line",
			"version": 947,
			"versionNonce": 136975108,
			"isDeleted": false,
			"id": "TkqGXY3DqDf94nhhYyTJq",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 833.0907760762864,
			"y": 709.8613222894184,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 17.303226078788477,
			"height": 0,
			"seed": 597006423,
			"groupIds": [
				"JzWCWzK7Jt465zq2gGBOo",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					17.303226078788477,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 889,
			"versionNonce": 1970769724,
			"isDeleted": false,
			"id": "_ix3bLrSK4j4T9oYsCjdV",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 833.3912779482366,
			"y": 744.5796777844849,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 17.303226078788477,
			"height": 0,
			"seed": 1013972121,
			"groupIds": [
				"JzWCWzK7Jt465zq2gGBOo",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					17.303226078788477,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1616,
			"versionNonce": 1794708100,
			"isDeleted": false,
			"id": "Y2d39-Zr_dRs10lN0-Wgh",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 850.773869585789,
			"y": 709.9236958129273,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 16.532160633722352,
			"height": 34.60645215757695,
			"seed": 947575,
			"groupIds": [
				"JzWCWzK7Jt465zq2gGBOo",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					12.522502284101337,
					3.4081987255076056
				],
				[
					16.532160633722352,
					17.93552241894058
				],
				[
					11.581745597816239,
					31.506682716287298
				],
				[
					0,
					34.60645215757695
				]
			]
		},
		{
			"type": "line",
			"version": 814,
			"versionNonce": 716851132,
			"isDeleted": false,
			"id": "Th4HJ_uzfjsRLSj5eNwxD",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1502.1316290926748,
			"y": 362.87751926324506,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.137675383468306,
			"height": 0,
			"seed": 649545241,
			"groupIds": [
				"BfGixiLYaxWI3MGKa3X28",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					19.137675383468306,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 964,
			"versionNonce": 716972548,
			"isDeleted": false,
			"id": "sjmd15at81Xopk4-W1bWL",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1451.561634530218,
			"y": 355.8806555285745,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 29.676000212557554,
			"height": 0.058580530820291375,
			"seed": 937067511,
			"groupIds": [
				"BfGixiLYaxWI3MGKa3X28",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					29.676000212557554,
					-0.058580530820291375
				]
			]
		},
		{
			"type": "line",
			"version": 871,
			"versionNonce": 135393340,
			"isDeleted": false,
			"id": "VJPwtHOuDkQCpm1-2yJXr",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1451.5579479064897,
			"y": 369.4293047752028,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 29.79314947550106,
			"height": 0.05858053082021884,
			"seed": 737745657,
			"groupIds": [
				"BfGixiLYaxWI3MGKa3X28",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					29.79314947550106,
					-0.05858053082021884
				]
			]
		},
		{
			"type": "line",
			"version": 886,
			"versionNonce": 779174276,
			"isDeleted": false,
			"id": "lG3EGaDRGxErO5M9qilTm",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1477.2828340020665,
			"y": 350.1712129234651,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 6.379225127822771,
			"height": 25.516900511291084,
			"seed": 2146757911,
			"groupIds": [
				"BfGixiLYaxWI3MGKa3X28",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					6.379225127822771,
					12.758450255645542
				],
				[
					0,
					25.516900511291084
				]
			]
		},
		{
			"type": "line",
			"version": 962,
			"versionNonce": 492865724,
			"isDeleted": false,
			"id": "2gRrqY9dkr45wG_kjKmVX",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1477.1435897242611,
			"y": 349.53586270414746,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 25.516900511291084,
			"height": 12.758450255645542,
			"seed": 1475171289,
			"groupIds": [
				"BfGixiLYaxWI3MGKa3X28",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					13.241739634912506,
					1.2887392316283568
				],
				[
					25.516900511291084,
					12.758450255645542
				]
			]
		},
		{
			"type": "line",
			"version": 899,
			"versionNonce": 1297510660,
			"isDeleted": false,
			"id": "mCcnPnbG6L29eOyBJbOsC",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1477.0117383167608,
			"y": 376.06786026325074,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 25.516900511291084,
			"height": 12.758450255645542,
			"seed": 1730490935,
			"groupIds": [
				"BfGixiLYaxWI3MGKa3X28",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					12.597370019098307,
					-1.6109159279312522
				],
				[
					25.516900511291084,
					-12.758450255645538
				]
			]
		},
		{
			"type": "line",
			"version": 840,
			"versionNonce": 776474940,
			"isDeleted": false,
			"id": "NlRFIFh-KaWyWWEjACKWC",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1502.7035045189364,
			"y": 395.5181084069427,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.137675383468306,
			"height": 0,
			"seed": 919355929,
			"groupIds": [
				"U1xHhHxtyjhTfxNJnKIFl",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					19.137675383468306,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 990,
			"versionNonce": 1189720196,
			"isDeleted": false,
			"id": "l79XyG6wB-753MNNPMDhp",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1451.3745343907399,
			"y": 388.9768181869938,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 29.676000212557554,
			"height": 0.058580530820291375,
			"seed": 480462839,
			"groupIds": [
				"U1xHhHxtyjhTfxNJnKIFl",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					29.676000212557554,
					-0.058580530820291375
				]
			]
		},
		{
			"type": "line",
			"version": 897,
			"versionNonce": 975866300,
			"isDeleted": false,
			"id": "yvRovJE2b3tmoFj8F6j3s",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1451.3660922295858,
			"y": 401.9595668327654,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 29.79314947550106,
			"height": 0.05858053082021884,
			"seed": 1745786617,
			"groupIds": [
				"U1xHhHxtyjhTfxNJnKIFl",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					29.79314947550106,
					-0.05858053082021884
				]
			]
		},
		{
			"type": "line",
			"version": 912,
			"versionNonce": 988348420,
			"isDeleted": false,
			"id": "ROzNPFjBpYzxUVukpWq4B",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1477.4512760175007,
			"y": 382.83914777950883,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 6.379225127822771,
			"height": 25.516900511291084,
			"seed": 1459958039,
			"groupIds": [
				"U1xHhHxtyjhTfxNJnKIFl",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					6.379225127822771,
					12.758450255645542
				],
				[
					0,
					25.516900511291084
				]
			]
		},
		{
			"type": "line",
			"version": 987,
			"versionNonce": 69857852,
			"isDeleted": false,
			"id": "XPgqHh7Kw4ZwvT1p1JWQ_",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1477.1623827046585,
			"y": 382.10017964709516,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 25.516900511291084,
			"height": 12.758450255645542,
			"seed": 1811107801,
			"groupIds": [
				"U1xHhHxtyjhTfxNJnKIFl",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					13.241739634912506,
					1.2887392316283568
				],
				[
					25.516900511291084,
					12.758450255645542
				]
			]
		},
		{
			"type": "line",
			"version": 925,
			"versionNonce": 559046532,
			"isDeleted": false,
			"id": "BZFh4NWUvUfgGB0lgp--f",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1476.8782819768678,
			"y": 408.39498222954273,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 25.516900511291084,
			"height": 12.758450255645542,
			"seed": 2072835639,
			"groupIds": [
				"U1xHhHxtyjhTfxNJnKIFl",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					12.597370019098307,
					-1.6109159279312593
				],
				[
					25.516900511291084,
					-12.758450255645544
				]
			]
		},
		{
			"type": "line",
			"version": 842,
			"versionNonce": 455625404,
			"isDeleted": false,
			"id": "ezVtCXsYaQ1b38b04-_XH",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1502.7834813326103,
			"y": 425.80365954920296,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.137675383468306,
			"height": 0,
			"seed": 2137941719,
			"groupIds": [
				"0CPgJ71iObdXybX3ehbD6",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					19.137675383468306,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 993,
			"versionNonce": 1113837316,
			"isDeleted": false,
			"id": "ulUJIVRrGyHxFbS5XimX4",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1451.8666115481185,
			"y": 419.5751933419268,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 29.676000212557554,
			"height": 0.058580530820291375,
			"seed": 1110529561,
			"groupIds": [
				"0CPgJ71iObdXybX3ehbD6",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					29.676000212557554,
					-0.058580530820291375
				]
			]
		},
		{
			"type": "line",
			"version": 899,
			"versionNonce": 1640469308,
			"isDeleted": false,
			"id": "p1dk510VvovL2mMp50YB7",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1452.3684480532147,
			"y": 433.00771081529376,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 29.79314947550106,
			"height": 0.05858053082021884,
			"seed": 885617655,
			"groupIds": [
				"0CPgJ71iObdXybX3ehbD6",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					29.79314947550106,
					-0.05858053082021884
				]
			]
		},
		{
			"type": "line",
			"version": 914,
			"versionNonce": 781930116,
			"isDeleted": false,
			"id": "bJGXEYlYpwvSUCOrUL87Q",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1477.7284675044616,
			"y": 413.437522934442,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 6.379225127822771,
			"height": 25.516900511291084,
			"seed": 1840327417,
			"groupIds": [
				"0CPgJ71iObdXybX3ehbD6",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					6.379225127822771,
					12.758450255645542
				],
				[
					0,
					25.516900511291084
				]
			]
		},
		{
			"type": "line",
			"version": 990,
			"versionNonce": 376032188,
			"isDeleted": false,
			"id": "1FNAwJ-PPvt6iXa8czypq",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1477.4226945293676,
			"y": 413.0905970444353,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 25.516900511291084,
			"height": 12.758450255645542,
			"seed": 1636162839,
			"groupIds": [
				"0CPgJ71iObdXybX3ehbD6",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					13.241739634912506,
					1.2887392316283568
				],
				[
					25.516900511291084,
					12.758450255645542
				]
			]
		},
		{
			"type": "line",
			"version": 928,
			"versionNonce": 917954052,
			"isDeleted": false,
			"id": "qxGBSsqhwwUKxX_Ky3i07",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1477.7524176088177,
			"y": 438.7750567197513,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 25.516900511291084,
			"height": 12.758450255645542,
			"seed": 1210278873,
			"groupIds": [
				"0CPgJ71iObdXybX3ehbD6",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					12.597370019098307,
					-1.6109159279312593
				],
				[
					25.516900511291084,
					-12.758450255645544
				]
			]
		},
		{
			"type": "line",
			"version": 870,
			"versionNonce": 1529934908,
			"isDeleted": false,
			"id": "DW1lxqJ_vc-bBKenSZZ3D",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1502.9446419246078,
			"y": 458.8437551234738,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.137675383468306,
			"height": 0,
			"seed": 1226318391,
			"groupIds": [
				"rphNlMc3VJPweTkaLqDnE",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					19.137675383468306,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1020,
			"versionNonce": 1672772996,
			"isDeleted": false,
			"id": "FOqNa8CAfdqHZrQMjUrIS",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1452.3990871084036,
			"y": 452.08912566025333,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 29.676000212557554,
			"height": 0.058580530820291375,
			"seed": 228294841,
			"groupIds": [
				"rphNlMc3VJPweTkaLqDnE",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					29.676000212557554,
					-0.058580530820291375
				]
			]
		},
		{
			"type": "line",
			"version": 927,
			"versionNonce": 1040125116,
			"isDeleted": false,
			"id": "yFLdp07p097UQ5dImcS5n",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1452.2906969194344,
			"y": 464.9511970197369,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 29.79314947550106,
			"height": 0.05858053082021884,
			"seed": 1281672023,
			"groupIds": [
				"rphNlMc3VJPweTkaLqDnE",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					29.79314947550106,
					-0.05858053082021884
				]
			]
		},
		{
			"type": "line",
			"version": 942,
			"versionNonce": 1859267844,
			"isDeleted": false,
			"id": "PQl7KrOsLbsHtwzTok6DM",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1477.3942490289958,
			"y": 446.1576859730808,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 6.379225127822771,
			"height": 25.516900511291084,
			"seed": 733807001,
			"groupIds": [
				"rphNlMc3VJPweTkaLqDnE",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					6.379225127822771,
					12.758450255645542
				],
				[
					0,
					25.516900511291084
				]
			]
		},
		{
			"type": "line",
			"version": 1017,
			"versionNonce": 1081480508,
			"isDeleted": false,
			"id": "XEpa_aezOSvoOtZ63JvdP",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1477.8538420509635,
			"y": 445.4263890426016,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 25.516900511291084,
			"height": 12.758450255645542,
			"seed": 1002455159,
			"groupIds": [
				"rphNlMc3VJPweTkaLqDnE",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					13.241739634912506,
					1.2887392316283568
				],
				[
					25.516900511291084,
					12.758450255645542
				]
			]
		},
		{
			"type": "line",
			"version": 955,
			"versionNonce": 965602436,
			"isDeleted": false,
			"id": "3H-nT9zbyUB23DpKEAdy-",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1477.2574098383816,
			"y": 471.7948853767173,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 25.516900511291084,
			"height": 12.758450255645542,
			"seed": 263939705,
			"groupIds": [
				"rphNlMc3VJPweTkaLqDnE",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					12.597370019098307,
					-1.6109159279312593
				],
				[
					25.516900511291084,
					-12.758450255645544
				]
			]
		},
		{
			"type": "line",
			"version": 855,
			"versionNonce": 1610091964,
			"isDeleted": false,
			"id": "ccnsCE1CKjb-7zr4mDlwl",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1505.1390095076197,
			"y": 489.9563628396568,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.137675383468306,
			"height": 0,
			"seed": 2107213815,
			"groupIds": [
				"JgpaNEMljP1o-nJS-5Xzz",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					19.137675383468306,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1004,
			"versionNonce": 1168489476,
			"isDeleted": false,
			"id": "WkiFyoktAdVqC7bs7_43S",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1454.3039805798303,
			"y": 483.20367439178756,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 29.676000212557554,
			"height": 0.058580530820291375,
			"seed": 1755076345,
			"groupIds": [
				"JgpaNEMljP1o-nJS-5Xzz",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					29.676000212557554,
					-0.058580530820291375
				]
			]
		},
		{
			"type": "line",
			"version": 912,
			"versionNonce": 497481276,
			"isDeleted": false,
			"id": "aLg436DqrDlg2wlUHetEe",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1454.290009458618,
			"y": 496.1064449833434,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 29.79314947550106,
			"height": 0.05858053082021884,
			"seed": 1060335895,
			"groupIds": [
				"JgpaNEMljP1o-nJS-5Xzz",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					29.79314947550106,
					-0.05858053082021884
				]
			]
		},
		{
			"type": "line",
			"version": 927,
			"versionNonce": 756521860,
			"isDeleted": false,
			"id": "Z5sDZXM3CPn8oj8keHlMC",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1479.4944101066358,
			"y": 477.285466379597,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 6.379225127822771,
			"height": 25.516900511291084,
			"seed": 348721113,
			"groupIds": [
				"JgpaNEMljP1o-nJS-5Xzz",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					6.379225127822771,
					12.758450255645542
				],
				[
					0,
					25.516900511291084
				]
			]
		},
		{
			"type": "line",
			"version": 1003,
			"versionNonce": 107269820,
			"isDeleted": false,
			"id": "QzXRXhNJWxx7oRg7AkRpw",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1479.8663862651283,
			"y": 476.68885541470297,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 25.516900511291084,
			"height": 12.758450255645542,
			"seed": 1140012599,
			"groupIds": [
				"JgpaNEMljP1o-nJS-5Xzz",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					13.241739634912506,
					1.2887392316283568
				],
				[
					25.516900511291084,
					12.758450255645542
				]
			]
		},
		{
			"type": "line",
			"version": 940,
			"versionNonce": 438405892,
			"isDeleted": false,
			"id": "TZluM8i9SG3pBGZohGtRx",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1479.586297911088,
			"y": 502.30465275913684,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 25.516900511291084,
			"height": 12.758450255645542,
			"seed": 279686329,
			"groupIds": [
				"JgpaNEMljP1o-nJS-5Xzz",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					12.597370019098307,
					-1.6109159279312593
				],
				[
					25.516900511291084,
					-12.758450255645544
				]
			]
		},
		{
			"type": "line",
			"version": 881,
			"versionNonce": 986945340,
			"isDeleted": false,
			"id": "ZYn-ipoBzfsnbMNSob1Gu",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1505.193825608519,
			"y": 522.2912827164868,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.137675383468306,
			"height": 0,
			"seed": 1656575831,
			"groupIds": [
				"GEdUK177wr9xHy0jYg3Zv",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					19.137675383468306,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1032,
			"versionNonce": 1061259908,
			"isDeleted": false,
			"id": "X2F5zkdFdxSRVmL6ubQ9d",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1454.3008411303615,
			"y": 515.6523477385324,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 29.676000212557554,
			"height": 0.058580530820291375,
			"seed": 870821273,
			"groupIds": [
				"GEdUK177wr9xHy0jYg3Zv",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					29.676000212557554,
					-0.058580530820291375
				]
			]
		},
		{
			"type": "line",
			"version": 939,
			"versionNonce": 2002079676,
			"isDeleted": false,
			"id": "xYHYhRfmIKV6-37i8CQRu",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1454.2696041090169,
			"y": 529.0756116012203,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 29.79314947550106,
			"height": 0.05858053082021884,
			"seed": 568743031,
			"groupIds": [
				"GEdUK177wr9xHy0jYg3Zv",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					29.79314947550106,
					-0.05858053082021884
				]
			]
		},
		{
			"type": "line",
			"version": 954,
			"versionNonce": 1328912900,
			"isDeleted": false,
			"id": "lqXyy_rverwfok912U3oo",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1480.1244734477784,
			"y": 509.6222379861762,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 6.379225127822771,
			"height": 25.516900511291084,
			"seed": 363893369,
			"groupIds": [
				"GEdUK177wr9xHy0jYg3Zv",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					6.379225127822771,
					12.758450255645542
				],
				[
					0,
					25.516900511291084
				]
			]
		},
		{
			"type": "line",
			"version": 1030,
			"versionNonce": 470546492,
			"isDeleted": false,
			"id": "3ihDaCZ4ZTT_1qkVt75zo",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1479.7340791753631,
			"y": 509.5535173645234,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 25.516900511291084,
			"height": 12.758450255645542,
			"seed": 1228058007,
			"groupIds": [
				"GEdUK177wr9xHy0jYg3Zv",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					13.241739634912506,
					1.2887392316283568
				],
				[
					25.516900511291084,
					12.758450255645542
				]
			]
		},
		{
			"type": "line",
			"version": 967,
			"versionNonce": 1962654084,
			"isDeleted": false,
			"id": "96zHlr56QJBbP7AhcdkAZ",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1479.6089732599646,
			"y": 535.1726447692207,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 25.516900511291084,
			"height": 12.758450255645542,
			"seed": 449436505,
			"groupIds": [
				"GEdUK177wr9xHy0jYg3Zv",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					12.597370019098307,
					-1.6109159279312593
				],
				[
					25.516900511291084,
					-12.758450255645544
				]
			]
		},
		{
			"type": "line",
			"version": 885,
			"versionNonce": 886673596,
			"isDeleted": false,
			"id": "wY1p2OIQNaWG9daijgjRX",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1505.9232415658219,
			"y": 553.0270140066621,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.137675383468306,
			"height": 0,
			"seed": 869720759,
			"groupIds": [
				"KQ3pWq7JcGmQe9aMbFsLw",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					19.137675383468306,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1035,
			"versionNonce": 1272047876,
			"isDeleted": false,
			"id": "GdcrNwFWhJuQCP9SZCAfO",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1454.6137660426332,
			"y": 546.3585409425654,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 29.676000212557554,
			"height": 0.058580530820291375,
			"seed": 1132922937,
			"groupIds": [
				"KQ3pWq7JcGmQe9aMbFsLw",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					29.676000212557554,
					-0.058580530820291375
				]
			]
		},
		{
			"type": "line",
			"version": 941,
			"versionNonce": 23075132,
			"isDeleted": false,
			"id": "BpTEdiIxihF2pVlnuZHfi",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1454.5971180263864,
			"y": 559.1555541279375,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 29.79314947550106,
			"height": 0.05858053082021884,
			"seed": 1651995607,
			"groupIds": [
				"KQ3pWq7JcGmQe9aMbFsLw",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					29.79314947550106,
					-0.05858053082021884
				]
			]
		},
		{
			"type": "line",
			"version": 957,
			"versionNonce": 1463167108,
			"isDeleted": false,
			"id": "FxYjXRBfANNo0A3SYGRYO",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1479.6700158734852,
			"y": 540.2191032306846,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 6.379225127822771,
			"height": 25.516900511291084,
			"seed": 969644313,
			"groupIds": [
				"KQ3pWq7JcGmQe9aMbFsLw",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					6.379225127822771,
					12.758450255645542
				],
				[
					0,
					25.516900511291084
				]
			]
		},
		{
			"type": "line",
			"version": 1033,
			"versionNonce": 2097254844,
			"isDeleted": false,
			"id": "_eMONBzdUTDzJ8GgUWR-o",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1479.8128179103462,
			"y": 540.2099620351079,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 25.516900511291084,
			"height": 12.758450255645542,
			"seed": 1294524663,
			"groupIds": [
				"KQ3pWq7JcGmQe9aMbFsLw",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					13.241739634912506,
					1.2887392316283568
				],
				[
					25.516900511291084,
					12.758450255645542
				]
			]
		},
		{
			"type": "line",
			"version": 970,
			"versionNonce": 2061924356,
			"isDeleted": false,
			"id": "tWUQaBnFvxhXUsh89iGVa",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1480.4968227370168,
			"y": 565.9606313424963,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 25.516900511291084,
			"height": 12.758450255645542,
			"seed": 520818169,
			"groupIds": [
				"KQ3pWq7JcGmQe9aMbFsLw",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					12.597370019098307,
					-1.6109159279312593
				],
				[
					25.516900511291084,
					-12.758450255645544
				]
			]
		},
		{
			"type": "line",
			"version": 912,
			"versionNonce": 1725954620,
			"isDeleted": false,
			"id": "yPLZ_GEfLshFwJyofICp3",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1505.4843287003753,
			"y": 585.427726869133,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.137675383468306,
			"height": 0,
			"seed": 1970252311,
			"groupIds": [
				"g9hoS4KkQTDZ7bytRKw7O",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					19.137675383468306,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1062,
			"versionNonce": 1927337860,
			"isDeleted": false,
			"id": "LixwebS5anguDHCF5t72J",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1454.4414288575458,
			"y": 578.9848572939583,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 29.676000212557554,
			"height": 0.058580530820291375,
			"seed": 440985305,
			"groupIds": [
				"g9hoS4KkQTDZ7bytRKw7O",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					29.676000212557554,
					-0.058580530820291375
				]
			]
		},
		{
			"type": "line",
			"version": 968,
			"versionNonce": 1239241404,
			"isDeleted": false,
			"id": "t_VM6isBXu3_jddU_4j4w",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1454.662802631523,
			"y": 592.2609249462156,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 29.79314947550106,
			"height": 0.05858053082021884,
			"seed": 943738679,
			"groupIds": [
				"g9hoS4KkQTDZ7bytRKw7O",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					29.79314947550106,
					-0.05858053082021884
				]
			]
		},
		{
			"type": "line",
			"version": 984,
			"versionNonce": 1264797444,
			"isDeleted": false,
			"id": "DsSvogoAW7Tj-dqDXGmUI",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1480.2821479514957,
			"y": 572.8380544612868,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 6.379225127822771,
			"height": 25.516900511291084,
			"seed": 639148985,
			"groupIds": [
				"g9hoS4KkQTDZ7bytRKw7O",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					6.379225127822771,
					12.758450255645542
				],
				[
					0,
					25.516900511291084
				]
			]
		},
		{
			"type": "line",
			"version": 1059,
			"versionNonce": 77306684,
			"isDeleted": false,
			"id": "ks32XWDUf8FFx_goCDuiT",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1479.9626904446031,
			"y": 572.5428310293436,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 25.516900511291084,
			"height": 12.758450255645542,
			"seed": 1610567767,
			"groupIds": [
				"g9hoS4KkQTDZ7bytRKw7O",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					13.241739634912506,
					1.2887392316283568
				],
				[
					25.516900511291084,
					12.758450255645542
				]
			]
		},
		{
			"type": "line",
			"version": 997,
			"versionNonce": 1491846788,
			"isDeleted": false,
			"id": "USB4g4o-i1rGTqIS-G7ts",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1480.1756808495954,
			"y": 598.8020237592285,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 25.516900511291084,
			"height": 12.758450255645542,
			"seed": 513655961,
			"groupIds": [
				"g9hoS4KkQTDZ7bytRKw7O",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					12.597370019098307,
					-1.6109159279312593
				],
				[
					25.516900511291084,
					-12.758450255645544
				]
			]
		},
		{
			"type": "line",
			"version": 233,
			"versionNonce": 1367135164,
			"isDeleted": false,
			"id": "vQwPm1ixrIafwwPmmTYzA",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1152.6694634047503,
			"y": 350.5976646040052,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 2.22950466396901,
			"height": 76.36024770215647,
			"seed": 1456379031,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-2.22950466396901,
					76.36024770215647
				]
			]
		},
		{
			"type": "line",
			"version": 226,
			"versionNonce": 808998404,
			"isDeleted": false,
			"id": "E1iz1KSt8hiR_S7gxEOR3",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1151.554732334898,
			"y": 495.51493620869076,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 1.1147310698522688,
			"height": 79.14709663891949,
			"seed": 2104868759,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					1.1147310698522688,
					79.14709663891949
				]
			]
		},
		{
			"type": "rectangle",
			"version": 1431,
			"versionNonce": 1319304252,
			"isDeleted": false,
			"id": "Zq4xoa_GTz7VioIvLzF5K",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1190.8303799456414,
			"y": 624.423331380516,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 112.30011255130835,
			"height": 118.32467760697281,
			"seed": 2049237175,
			"groupIds": [
				"JXy-z3FeXfQkQeWX7NUoc",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "sharp",
			"boundElements": [
				{
					"id": "AxsFrbUK",
					"type": "text"
				}
			],
			"updated": 1662511267740,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 952,
			"versionNonce": 507966852,
			"isDeleted": false,
			"id": "AxsFrbUK",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1195.8303799456414,
			"y": 675.0856701840023,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 102.30011255130835,
			"height": 17,
			"seed": 1335880249,
			"groupIds": [
				"JXy-z3FeXfQkQeWX7NUoc",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"fontSize": 13.865014610506565,
			"fontFamily": 1,
			"text": "8kx8",
			"rawText": "8kx8",
			"baseline": 12,
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "Zq4xoa_GTz7VioIvLzF5K",
			"originalText": "8kx8"
		},
		{
			"type": "line",
			"version": 1242,
			"versionNonce": 99620028,
			"isDeleted": false,
			"id": "Nu5zRYy1IvQ3cG0xlmAc1",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1156.753501705173,
			"y": 630.2642746178376,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 1784000983,
			"groupIds": [
				"JXy-z3FeXfQkQeWX7NUoc",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1301,
			"versionNonce": 542483716,
			"isDeleted": false,
			"id": "xKdpWG5wgu-kyHok-bu89",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1156.640939798813,
			"y": 636.5091970164069,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 1417165593,
			"groupIds": [
				"JXy-z3FeXfQkQeWX7NUoc",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1309,
			"versionNonce": 1963334972,
			"isDeleted": false,
			"id": "V1RzUR6kZAtWYclON9BZZ",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1156.7246209243665,
			"y": 644.270638877374,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 2056216311,
			"groupIds": [
				"JXy-z3FeXfQkQeWX7NUoc",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1370,
			"versionNonce": 1541563524,
			"isDeleted": false,
			"id": "GQKWcmvI029bTNMi9XjEu",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1156.6870896834232,
			"y": 650.0265419814048,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 1070821369,
			"groupIds": [
				"JXy-z3FeXfQkQeWX7NUoc",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1271,
			"versionNonce": 356980156,
			"isDeleted": false,
			"id": "uYOJ7G4zMIqNt8ly0Y1nK",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1156.677025633708,
			"y": 656.1996951457756,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 1834379287,
			"groupIds": [
				"JXy-z3FeXfQkQeWX7NUoc",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1334,
			"versionNonce": 380318724,
			"isDeleted": false,
			"id": "_w8dPPTCkbmmXAILKlm5J",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1156.2597897106418,
			"y": 661.9282826359092,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 129304793,
			"groupIds": [
				"JXy-z3FeXfQkQeWX7NUoc",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1341,
			"versionNonce": 1674903100,
			"isDeleted": false,
			"id": "1qSkUE_KidtZfqZmEfmew",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1156.662719039594,
			"y": 669.6278250637231,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 1084181815,
			"groupIds": [
				"JXy-z3FeXfQkQeWX7NUoc",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1402,
			"versionNonce": 783160196,
			"isDeleted": false,
			"id": "uITfdoQYDvU22yFYQzMTP",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1156.431427520661,
			"y": 676.0225027307638,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 363890105,
			"groupIds": [
				"JXy-z3FeXfQkQeWX7NUoc",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1293,
			"versionNonce": 1771165372,
			"isDeleted": false,
			"id": "5B44v4YUXODMEZwUVx-tp",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1155.6300021247773,
			"y": 681.8250239450308,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 1070501463,
			"groupIds": [
				"JXy-z3FeXfQkQeWX7NUoc",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1355,
			"versionNonce": 304677636,
			"isDeleted": false,
			"id": "ZaMNGvKqU1q44TlRx4-oq",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1155.2278280399617,
			"y": 688.3148921799847,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 1424582297,
			"groupIds": [
				"JXy-z3FeXfQkQeWX7NUoc",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1362,
			"versionNonce": 1126145852,
			"isDeleted": false,
			"id": "xSubVaZsxg572-lrGNg5s",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1155.8997662133204,
			"y": 695.8900903454645,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 1438165879,
			"groupIds": [
				"JXy-z3FeXfQkQeWX7NUoc",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1422,
			"versionNonce": 932840068,
			"isDeleted": false,
			"id": "PQ1tEKpASQ9CVt9uFdZ0K",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1155.628661400229,
			"y": 701.5552867249145,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 1256313,
			"groupIds": [
				"JXy-z3FeXfQkQeWX7NUoc",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1328,
			"versionNonce": 685791164,
			"isDeleted": false,
			"id": "W7n1HjU0mgkxmYQszrSv2",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1155.546109033037,
			"y": 707.639786897823,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 513942679,
			"groupIds": [
				"JXy-z3FeXfQkQeWX7NUoc",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 862,
			"versionNonce": 364843524,
			"isDeleted": false,
			"id": "OW7RxgGE",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1194.3108576820407,
			"y": 715.0082007747834,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 14,
			"height": 22,
			"seed": 795956313,
			"groupIds": [
				"JXy-z3FeXfQkQeWX7NUoc",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"fontSize": 9.301747036482514,
			"fontFamily": 1,
			"text": "CS\nOE",
			"rawText": "CS\nOE",
			"baseline": 19,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "CS\nOE"
		},
		{
			"type": "line",
			"version": 1346,
			"versionNonce": 1995833404,
			"isDeleted": false,
			"id": "MCU3F2Jyj7GqFxt8TBOYO",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1161.0462800905332,
			"y": 720.5762307667645,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 29.63565761011434,
			"height": 0,
			"seed": 977238455,
			"groupIds": [
				"JXy-z3FeXfQkQeWX7NUoc",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					29.63565761011434,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1334,
			"versionNonce": 462827908,
			"isDeleted": false,
			"id": "dJMIN9CidAXL-1Q7eFLHh",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1161.2607577599777,
			"y": 731.408334964431,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 29.63565761011434,
			"height": 0,
			"seed": 651649337,
			"groupIds": [
				"JXy-z3FeXfQkQeWX7NUoc",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					29.63565761011434,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1046,
			"versionNonce": 893556924,
			"isDeleted": false,
			"id": "tEXz1u8YEoEtCXTaFFFYv",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1307.083396270032,
			"y": 638.1563663151051,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 66.64546861703714,
			"height": 0,
			"seed": 1572154071,
			"groupIds": [
				"JXy-z3FeXfQkQeWX7NUoc",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					66.64546861703714,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1107,
			"versionNonce": 677208324,
			"isDeleted": false,
			"id": "Kim8JCmDfnFs_UXIXkG6N",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1306.1494093118679,
			"y": 649.1849123554341,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 66.64546861703714,
			"height": 0,
			"seed": 1672008217,
			"groupIds": [
				"JXy-z3FeXfQkQeWX7NUoc",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					66.64546861703714,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1115,
			"versionNonce": 526917948,
			"isDeleted": false,
			"id": "TdlVMNo30GqmAIMQ6syLN",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1307.5456870429382,
			"y": 665.250341607388,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 66.64546861703714,
			"height": 0,
			"seed": 630700023,
			"groupIds": [
				"JXy-z3FeXfQkQeWX7NUoc",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					66.64546861703714,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1174,
			"versionNonce": 59940996,
			"isDeleted": false,
			"id": "9cCiY1LjkPRY8uaGy1ddo",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1306.4002581010657,
			"y": 677.0944674840089,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 66.64546861703714,
			"height": 0,
			"seed": 1792616185,
			"groupIds": [
				"JXy-z3FeXfQkQeWX7NUoc",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					66.64546861703714,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1077,
			"versionNonce": 751344060,
			"isDeleted": false,
			"id": "C43S0w_PRweCZz2mHklPf",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1307.0428025878475,
			"y": 688.7800427593751,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 66.64546861703714,
			"height": 0,
			"seed": 669753623,
			"groupIds": [
				"JXy-z3FeXfQkQeWX7NUoc",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					66.64546861703714,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1139,
			"versionNonce": 1425272836,
			"isDeleted": false,
			"id": "KXb0Y7P041BBu38LGaMCR",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1305.7612326735891,
			"y": 700.698565948249,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 66.64546861703714,
			"height": 0,
			"seed": 1458298841,
			"groupIds": [
				"JXy-z3FeXfQkQeWX7NUoc",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					66.64546861703714,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1145,
			"versionNonce": 411435580,
			"isDeleted": false,
			"id": "TxhC1MFFgV0HURPumHOfm",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1307.069689697207,
			"y": 716.0653525782492,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 66.64546861703714,
			"height": 0,
			"seed": 1176856119,
			"groupIds": [
				"JXy-z3FeXfQkQeWX7NUoc",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					66.64546861703714,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1207,
			"versionNonce": 478105476,
			"isDeleted": false,
			"id": "1g4zhrvMvltj8CBbKk-5W",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1306.63696457321,
			"y": 727.8615664103651,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 66.64546861703714,
			"height": 0,
			"seed": 636779705,
			"groupIds": [
				"JXy-z3FeXfQkQeWX7NUoc",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					66.64546861703714,
					0
				]
			]
		},
		{
			"type": "rectangle",
			"version": 1512,
			"versionNonce": 1770150588,
			"isDeleted": false,
			"id": "oXvgMzOm4EWURVJ-62u84",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1191.2778569554591,
			"y": 773.6068959216486,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 112.30011255130835,
			"height": 118.32467760697281,
			"seed": 1059686231,
			"groupIds": [
				"Nhxe8OvtELl5X2zXVW9MP",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "sharp",
			"boundElements": [
				{
					"id": "jc5jidpo",
					"type": "text"
				}
			],
			"updated": 1662511267740,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 1040,
			"versionNonce": 712163076,
			"isDeleted": false,
			"id": "jc5jidpo",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1196.2778569554591,
			"y": 824.269234725135,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 102.30011255130835,
			"height": 17,
			"seed": 1201044889,
			"groupIds": [
				"Nhxe8OvtELl5X2zXVW9MP",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"fontSize": 13.865014610506565,
			"fontFamily": 1,
			"text": "8kx8",
			"rawText": "8kx8",
			"baseline": 12,
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "oXvgMzOm4EWURVJ-62u84",
			"originalText": "8kx8"
		},
		{
			"type": "line",
			"version": 1331,
			"versionNonce": 2053088060,
			"isDeleted": false,
			"id": "v_f2TPxBhbS3OCBh7yC-U",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1157.2009787149907,
			"y": 779.4478391589706,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 21791863,
			"groupIds": [
				"Nhxe8OvtELl5X2zXVW9MP",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1390,
			"versionNonce": 390872708,
			"isDeleted": false,
			"id": "WV6mLQH6M30X6jwYCIUhx",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1157.0884168086307,
			"y": 785.6927615575399,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 1795515001,
			"groupIds": [
				"Nhxe8OvtELl5X2zXVW9MP",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1398,
			"versionNonce": 25156540,
			"isDeleted": false,
			"id": "Bi-LyGtMpipqNZ9XLD6YC",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1157.1720979341842,
			"y": 793.4542034185071,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 1012063639,
			"groupIds": [
				"Nhxe8OvtELl5X2zXVW9MP",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1459,
			"versionNonce": 1003081220,
			"isDeleted": false,
			"id": "SLil81axByq-cxP7R2gD-",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1157.134566693241,
			"y": 799.2101065225378,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 218409817,
			"groupIds": [
				"Nhxe8OvtELl5X2zXVW9MP",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1360,
			"versionNonce": 419759164,
			"isDeleted": false,
			"id": "3JFfpZBh2Pjo5_TY9Raw4",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1157.1245026435256,
			"y": 805.3832596869087,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 863048375,
			"groupIds": [
				"Nhxe8OvtELl5X2zXVW9MP",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1423,
			"versionNonce": 686386564,
			"isDeleted": false,
			"id": "_U5x1saK7DZTIYyxnShym",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1156.7072667204595,
			"y": 811.1118471770423,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 1172822073,
			"groupIds": [
				"Nhxe8OvtELl5X2zXVW9MP",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1430,
			"versionNonce": 1188109500,
			"isDeleted": false,
			"id": "iQngbkBml7otFmgnEgHFc",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1157.1101960494118,
			"y": 818.8113896048559,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 1330357207,
			"groupIds": [
				"Nhxe8OvtELl5X2zXVW9MP",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1491,
			"versionNonce": 535371012,
			"isDeleted": false,
			"id": "zbyTsDSsinYX2NxHJNO6L",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1156.8789045304786,
			"y": 825.2060672718968,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 1469212953,
			"groupIds": [
				"Nhxe8OvtELl5X2zXVW9MP",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1382,
			"versionNonce": 75900220,
			"isDeleted": false,
			"id": "DgkHe2xFOiQO36Ow4bj3w",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1156.077479134595,
			"y": 831.0085884861638,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 1878462711,
			"groupIds": [
				"Nhxe8OvtELl5X2zXVW9MP",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1444,
			"versionNonce": 172416132,
			"isDeleted": false,
			"id": "6QJYsg2tmnoxOlBSgWIAg",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1155.6753050497794,
			"y": 837.4984567211178,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 2071453177,
			"groupIds": [
				"Nhxe8OvtELl5X2zXVW9MP",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1451,
			"versionNonce": 1199971772,
			"isDeleted": false,
			"id": "fuPyFfgEKbmVH2w1WsBom",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1156.347243223138,
			"y": 845.0736548865972,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 2130172439,
			"groupIds": [
				"Nhxe8OvtELl5X2zXVW9MP",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1511,
			"versionNonce": 1908452356,
			"isDeleted": false,
			"id": "1IMat3LuivjgwXdySu9Eu",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1156.0761384100467,
			"y": 850.7388512660472,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 1889253081,
			"groupIds": [
				"Nhxe8OvtELl5X2zXVW9MP",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1417,
			"versionNonce": 150144572,
			"isDeleted": false,
			"id": "YI4w7OLHSzqdXhDBHPALM",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1155.9935860428548,
			"y": 856.8233514389557,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.75957634872119,
			"height": 0,
			"seed": 1094876983,
			"groupIds": [
				"Nhxe8OvtELl5X2zXVW9MP",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					33.75957634872119,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 951,
			"versionNonce": 2018806660,
			"isDeleted": false,
			"id": "yVYvVy5g",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1194.7583346918584,
			"y": 864.1917653159161,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 14,
			"height": 22,
			"seed": 1234269113,
			"groupIds": [
				"Nhxe8OvtELl5X2zXVW9MP",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"fontSize": 9.301747036482514,
			"fontFamily": 1,
			"text": "CS\nOE",
			"rawText": "CS\nOE",
			"baseline": 19,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "CS\nOE"
		},
		{
			"type": "line",
			"version": 1435,
			"versionNonce": 1303305916,
			"isDeleted": false,
			"id": "EeyZxtpUDhOgNFy1fTygw",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1161.4937571003509,
			"y": 869.7597953078974,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 29.63565761011434,
			"height": 0,
			"seed": 1765507159,
			"groupIds": [
				"Nhxe8OvtELl5X2zXVW9MP",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					29.63565761011434,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1423,
			"versionNonce": 1346403076,
			"isDeleted": false,
			"id": "Et9P_UPpZXv0KJWaWoSMu",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1161.7082347697954,
			"y": 880.5918995055639,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 29.63565761011434,
			"height": 0,
			"seed": 2054984857,
			"groupIds": [
				"Nhxe8OvtELl5X2zXVW9MP",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					29.63565761011434,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1135,
			"versionNonce": 777758524,
			"isDeleted": false,
			"id": "JRnkkxdxL-uggyczAw3tK",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1307.530873279852,
			"y": 787.3399308562381,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 66.64546861703714,
			"height": 0,
			"seed": 1756847479,
			"groupIds": [
				"Nhxe8OvtELl5X2zXVW9MP",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					66.64546861703714,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1196,
			"versionNonce": 872577668,
			"isDeleted": false,
			"id": "mbfEH8_HoKiR3kj39AF-3",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1306.5968863216879,
			"y": 798.3684768965671,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 66.64546861703714,
			"height": 0,
			"seed": 655399289,
			"groupIds": [
				"Nhxe8OvtELl5X2zXVW9MP",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					66.64546861703714,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1204,
			"versionNonce": 1599823804,
			"isDeleted": false,
			"id": "aIcsWgsr1EnAUg1xBA04W",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1307.9931640527582,
			"y": 814.433906148521,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 66.64546861703714,
			"height": 0,
			"seed": 49976983,
			"groupIds": [
				"Nhxe8OvtELl5X2zXVW9MP",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					66.64546861703714,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1263,
			"versionNonce": 1582860804,
			"isDeleted": false,
			"id": "gj93VMMoauczZIxbPdFVg",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1306.8477351108857,
			"y": 826.2780320251419,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 66.64546861703714,
			"height": 0,
			"seed": 814809689,
			"groupIds": [
				"Nhxe8OvtELl5X2zXVW9MP",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					66.64546861703714,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1166,
			"versionNonce": 953157692,
			"isDeleted": false,
			"id": "JH7PoCcdq9pO7xY0DxNf9",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1307.4902795976675,
			"y": 837.9636073005082,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 66.64546861703714,
			"height": 0,
			"seed": 515484599,
			"groupIds": [
				"Nhxe8OvtELl5X2zXVW9MP",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					66.64546861703714,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1228,
			"versionNonce": 37792132,
			"isDeleted": false,
			"id": "f_I9Fe6QHeI67PjdrVbmd",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1306.208709683409,
			"y": 849.8821304893817,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 66.64546861703714,
			"height": 0,
			"seed": 64048953,
			"groupIds": [
				"Nhxe8OvtELl5X2zXVW9MP",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					66.64546861703714,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1234,
			"versionNonce": 1050386620,
			"isDeleted": false,
			"id": "OzaXtTS5KmAF32G4QEyPD",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1307.517166707027,
			"y": 865.2489171193819,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 66.64546861703714,
			"height": 0,
			"seed": 1478040791,
			"groupIds": [
				"Nhxe8OvtELl5X2zXVW9MP",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					66.64546861703714,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1296,
			"versionNonce": 1123604740,
			"isDeleted": false,
			"id": "N0bOXBhixL0FxUXdbJQAk",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1307.08444158303,
			"y": 877.0451309514978,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 66.64546861703714,
			"height": 0,
			"seed": 657784857,
			"groupIds": [
				"Nhxe8OvtELl5X2zXVW9MP",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					66.64546861703714,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 825,
			"versionNonce": 677390652,
			"isDeleted": false,
			"id": "jH3FSa3HB45ZdHLf7iSTX",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1093.0431920720155,
			"y": 587.8273316768775,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 26.17321629211452,
			"height": 0,
			"seed": 1387096567,
			"groupIds": [
				"67Ia2vFN-xrosvd9AQIrd",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					26.17321629211452,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 811,
			"versionNonce": 738138244,
			"isDeleted": false,
			"id": "ZzK5OzeoLd97kjnmNiQ50",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1119.0855140115657,
			"y": 574.4649109305705,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 26.17321629211452,
			"seed": 145724665,
			"groupIds": [
				"67Ia2vFN-xrosvd9AQIrd",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					26.17321629211452
				]
			]
		},
		{
			"type": "line",
			"version": 904,
			"versionNonce": 1769972156,
			"isDeleted": false,
			"id": "ywVec0bvMFH_jpq-heOPI",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1118.7572408448652,
			"y": 574.7695052289704,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 26.17321629211452,
			"height": 13.08660814605726,
			"seed": 1266357015,
			"groupIds": [
				"67Ia2vFN-xrosvd9AQIrd",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					26.17321629211452,
					13.08660814605726
				]
			]
		},
		{
			"type": "line",
			"version": 814,
			"versionNonce": 689006596,
			"isDeleted": false,
			"id": "ApShxqsf-t2YDZCPrOXtS",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1119.2517389661762,
			"y": 600.8228194091172,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 26.17321629211452,
			"height": 13.08660814605726,
			"seed": 197430745,
			"groupIds": [
				"67Ia2vFN-xrosvd9AQIrd",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					26.17321629211452,
					-13.08660814605726
				]
			]
		},
		{
			"type": "line",
			"version": 889,
			"versionNonce": 958138940,
			"isDeleted": false,
			"id": "q2NACA7sqUj20pnl0vdQU",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1151.6093303277767,
			"y": 588.2007560095132,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 13.206782687082496,
			"height": 0,
			"seed": 1794545719,
			"groupIds": [
				"67Ia2vFN-xrosvd9AQIrd",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					13.206782687082496,
					0
				]
			]
		},
		{
			"type": "ellipse",
			"version": 751,
			"versionNonce": 2116929412,
			"isDeleted": false,
			"id": "1T8c-2ffXLxROEm6R_30M",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1145.2400787384647,
			"y": 585.0165198095198,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 6.026048412597953,
			"height": 6.026048412597953,
			"seed": 1468492473,
			"groupIds": [
				"67Ia2vFN-xrosvd9AQIrd",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 827,
			"versionNonce": 437740220,
			"isDeleted": false,
			"id": "8B8-NnfvmcP5ZKULlcYAh",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1503.701617709363,
			"y": 644.3944244328509,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.137675383468306,
			"height": 0,
			"seed": 1261752441,
			"groupIds": [
				"zgiwnbLPPBans9rt4rq7r",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					19.137675383468306,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 977,
			"versionNonce": 1066546948,
			"isDeleted": false,
			"id": "Y2eTILvuLyYZxs4j7KohZ",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1453.1316231469061,
			"y": 637.3975606981803,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 29.676000212557554,
			"height": 0.058580530820291375,
			"seed": 1268338583,
			"groupIds": [
				"zgiwnbLPPBans9rt4rq7r",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					29.676000212557554,
					-0.058580530820291375
				]
			]
		},
		{
			"type": "line",
			"version": 884,
			"versionNonce": 1662233404,
			"isDeleted": false,
			"id": "tljJ6993DavT41aBKUvge",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1453.1279365231778,
			"y": 650.9462099448085,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 29.79314947550106,
			"height": 0.05858053082021884,
			"seed": 1360419161,
			"groupIds": [
				"zgiwnbLPPBans9rt4rq7r",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					29.79314947550106,
					-0.05858053082021884
				]
			]
		},
		{
			"type": "line",
			"version": 899,
			"versionNonce": 1237104260,
			"isDeleted": false,
			"id": "UW6DXPqsLhQno7jn81mwz",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1478.8528226187548,
			"y": 631.6881180930709,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 6.379225127822771,
			"height": 25.516900511291084,
			"seed": 890848439,
			"groupIds": [
				"zgiwnbLPPBans9rt4rq7r",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					6.379225127822771,
					12.758450255645542
				],
				[
					0,
					25.516900511291084
				]
			]
		},
		{
			"type": "line",
			"version": 975,
			"versionNonce": 1181934524,
			"isDeleted": false,
			"id": "Qw-Z8c9QsGeyziKrqHK8a",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1478.7135783409492,
			"y": 631.0527678737533,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 25.516900511291084,
			"height": 12.758450255645542,
			"seed": 932431417,
			"groupIds": [
				"zgiwnbLPPBans9rt4rq7r",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					13.241739634912506,
					1.2887392316283568
				],
				[
					25.516900511291084,
					12.758450255645542
				]
			]
		},
		{
			"type": "line",
			"version": 912,
			"versionNonce": 963331588,
			"isDeleted": false,
			"id": "i-bM5kdD1PglDOuN-nyUb",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1478.5817269334486,
			"y": 657.5847654328567,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 25.516900511291084,
			"height": 12.758450255645542,
			"seed": 287151575,
			"groupIds": [
				"zgiwnbLPPBans9rt4rq7r",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					12.597370019098307,
					-1.6109159279312522
				],
				[
					25.516900511291084,
					-12.758450255645538
				]
			]
		},
		{
			"type": "line",
			"version": 854,
			"versionNonce": 1515654204,
			"isDeleted": false,
			"id": "J7c3wLYLRFN0wM0YLZbqQ",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1504.2734931356247,
			"y": 677.0350135765484,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.137675383468306,
			"height": 0,
			"seed": 1234212633,
			"groupIds": [
				"W6r9ZZvsFh4lfLqKc5HGb",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					19.137675383468306,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1004,
			"versionNonce": 1671161220,
			"isDeleted": false,
			"id": "2SL7fB_vz7Yw0UM6_v15J",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1452.9445230074282,
			"y": 670.4937233565997,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 29.676000212557554,
			"height": 0.058580530820291375,
			"seed": 1186644727,
			"groupIds": [
				"W6r9ZZvsFh4lfLqKc5HGb",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					29.676000212557554,
					-0.058580530820291375
				]
			]
		},
		{
			"type": "line",
			"version": 911,
			"versionNonce": 547497148,
			"isDeleted": false,
			"id": "K5NSZMxDa0zZoCeSzMkg7",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1452.9360808462736,
			"y": 683.476472002371,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 29.79314947550106,
			"height": 0.05858053082021884,
			"seed": 696273913,
			"groupIds": [
				"W6r9ZZvsFh4lfLqKc5HGb",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					29.79314947550106,
					-0.05858053082021884
				]
			]
		},
		{
			"type": "line",
			"version": 926,
			"versionNonce": 1301058820,
			"isDeleted": false,
			"id": "HeKHC1Um3ROU7mZmCsViQ",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1479.021264634189,
			"y": 664.3560529491147,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 6.379225127822771,
			"height": 25.516900511291084,
			"seed": 1718963223,
			"groupIds": [
				"W6r9ZZvsFh4lfLqKc5HGb",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					6.379225127822771,
					12.758450255645542
				],
				[
					0,
					25.516900511291084
				]
			]
		},
		{
			"type": "line",
			"version": 1001,
			"versionNonce": 251014460,
			"isDeleted": false,
			"id": "XgvhSu_u7waEjP1HBiVZg",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1478.7323713213466,
			"y": 663.617084816701,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 25.516900511291084,
			"height": 12.758450255645542,
			"seed": 1600546009,
			"groupIds": [
				"W6r9ZZvsFh4lfLqKc5HGb",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					13.241739634912506,
					1.2887392316283568
				],
				[
					25.516900511291084,
					12.758450255645542
				]
			]
		},
		{
			"type": "line",
			"version": 939,
			"versionNonce": 616256644,
			"isDeleted": false,
			"id": "0_PpkddyGtzvuXYvpiGEN",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1478.448270593556,
			"y": 689.9118873991484,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 25.516900511291084,
			"height": 12.758450255645542,
			"seed": 2084679991,
			"groupIds": [
				"W6r9ZZvsFh4lfLqKc5HGb",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					12.597370019098307,
					-1.6109159279312593
				],
				[
					25.516900511291084,
					-12.758450255645544
				]
			]
		},
		{
			"type": "line",
			"version": 856,
			"versionNonce": 380970428,
			"isDeleted": false,
			"id": "QqFmaptOoqmuZY56M3hEa",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1504.3534699492986,
			"y": 707.3205647188089,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.137675383468306,
			"height": 0,
			"seed": 651583929,
			"groupIds": [
				"ss-YlwsO7K9bs9uBHWLEa",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					19.137675383468306,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1007,
			"versionNonce": 921052164,
			"isDeleted": false,
			"id": "6HFobdOm-wcKCyxKk9ObG",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1453.4366001648066,
			"y": 701.0920985115328,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 29.676000212557554,
			"height": 0.058580530820291375,
			"seed": 562328151,
			"groupIds": [
				"ss-YlwsO7K9bs9uBHWLEa",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					29.676000212557554,
					-0.058580530820291375
				]
			]
		},
		{
			"type": "line",
			"version": 913,
			"versionNonce": 755043900,
			"isDeleted": false,
			"id": "5FjOGn438_ltvwXDCPvGs",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1453.9384366699026,
			"y": 714.5246159848995,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 29.79314947550106,
			"height": 0.05858053082021884,
			"seed": 2096349849,
			"groupIds": [
				"ss-YlwsO7K9bs9uBHWLEa",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					29.79314947550106,
					-0.05858053082021884
				]
			]
		},
		{
			"type": "line",
			"version": 928,
			"versionNonce": 1779106692,
			"isDeleted": false,
			"id": "3apVdEOjI3AO3SFHOcIP5",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1479.29845612115,
			"y": 694.9544281040477,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 6.379225127822771,
			"height": 25.516900511291084,
			"seed": 1326583671,
			"groupIds": [
				"ss-YlwsO7K9bs9uBHWLEa",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					6.379225127822771,
					12.758450255645542
				],
				[
					0,
					25.516900511291084
				]
			]
		},
		{
			"type": "line",
			"version": 1004,
			"versionNonce": 1388046012,
			"isDeleted": false,
			"id": "nT0bH-Q_Cy918gQc6iBCy",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1478.9926831460555,
			"y": 694.6075022140409,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 25.516900511291084,
			"height": 12.758450255645542,
			"seed": 1852966777,
			"groupIds": [
				"ss-YlwsO7K9bs9uBHWLEa",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					13.241739634912506,
					1.2887392316283568
				],
				[
					25.516900511291084,
					12.758450255645542
				]
			]
		},
		{
			"type": "line",
			"version": 942,
			"versionNonce": 879227652,
			"isDeleted": false,
			"id": "sphXxxMPYgghI8jIoMwzE",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1479.322406225506,
			"y": 720.2919618893571,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 25.516900511291084,
			"height": 12.758450255645542,
			"seed": 1865353367,
			"groupIds": [
				"ss-YlwsO7K9bs9uBHWLEa",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					12.597370019098307,
					-1.6109159279312593
				],
				[
					25.516900511291084,
					-12.758450255645544
				]
			]
		},
		{
			"type": "line",
			"version": 884,
			"versionNonce": 478654268,
			"isDeleted": false,
			"id": "Em9d8uJMScuJrzMvjp5Ho",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1504.5146305412957,
			"y": 740.3606602930796,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.137675383468306,
			"height": 0,
			"seed": 630501465,
			"groupIds": [
				"mO_LqSgBIUjXAYc5Qbt4w",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					19.137675383468306,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1034,
			"versionNonce": 343601796,
			"isDeleted": false,
			"id": "9cGyCHC4nKLSpIYeAanV6",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1453.9690757250917,
			"y": 733.6060308298592,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 29.676000212557554,
			"height": 0.058580530820291375,
			"seed": 797957559,
			"groupIds": [
				"mO_LqSgBIUjXAYc5Qbt4w",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					29.676000212557554,
					-0.058580530820291375
				]
			]
		},
		{
			"type": "line",
			"version": 941,
			"versionNonce": 986081212,
			"isDeleted": false,
			"id": "FJb_Ag1CmjttiPiQ-a6b1",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1453.8606855361224,
			"y": 746.4681021893426,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 29.79314947550106,
			"height": 0.05858053082021884,
			"seed": 942619961,
			"groupIds": [
				"mO_LqSgBIUjXAYc5Qbt4w",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					29.79314947550106,
					-0.05858053082021884
				]
			]
		},
		{
			"type": "line",
			"version": 956,
			"versionNonce": 151126532,
			"isDeleted": false,
			"id": "RiMFMjV0GXgjttATwaWLa",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1478.9642376456839,
			"y": 727.6745911426866,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 6.379225127822771,
			"height": 25.516900511291084,
			"seed": 324603607,
			"groupIds": [
				"mO_LqSgBIUjXAYc5Qbt4w",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					6.379225127822771,
					12.758450255645542
				],
				[
					0,
					25.516900511291084
				]
			]
		},
		{
			"type": "line",
			"version": 1031,
			"versionNonce": 26873916,
			"isDeleted": false,
			"id": "QdzsvPW8xtM_jYOcfMviv",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1479.4238306676518,
			"y": 726.9432942122074,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 25.516900511291084,
			"height": 12.758450255645542,
			"seed": 900017689,
			"groupIds": [
				"mO_LqSgBIUjXAYc5Qbt4w",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					13.241739634912506,
					1.2887392316283568
				],
				[
					25.516900511291084,
					12.758450255645542
				]
			]
		},
		{
			"type": "line",
			"version": 969,
			"versionNonce": 150675844,
			"isDeleted": false,
			"id": "8U2D7no6Rtn_V-wLZ4wo8",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1478.82739845507,
			"y": 753.3117905463231,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 25.516900511291084,
			"height": 12.758450255645542,
			"seed": 1159666679,
			"groupIds": [
				"mO_LqSgBIUjXAYc5Qbt4w",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					12.597370019098307,
					-1.6109159279312593
				],
				[
					25.516900511291084,
					-12.758450255645544
				]
			]
		},
		{
			"type": "line",
			"version": 869,
			"versionNonce": 1894033596,
			"isDeleted": false,
			"id": "CgnaH9ZGrKJUK09_Yb7sG",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1506.7089981243078,
			"y": 771.4732680092626,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.137675383468306,
			"height": 0,
			"seed": 1961493241,
			"groupIds": [
				"WgOLoW8LhV7KgycDXlZX0",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					19.137675383468306,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1018,
			"versionNonce": 2074366212,
			"isDeleted": false,
			"id": "xISG1lknXsE9cSr_oGQZv",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1455.8739691965186,
			"y": 764.7205795613933,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 29.676000212557554,
			"height": 0.058580530820291375,
			"seed": 686195991,
			"groupIds": [
				"WgOLoW8LhV7KgycDXlZX0",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					29.676000212557554,
					-0.058580530820291375
				]
			]
		},
		{
			"type": "line",
			"version": 926,
			"versionNonce": 1011364156,
			"isDeleted": false,
			"id": "NmEiVKNg58m5SBClxFzee",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1455.8599980753063,
			"y": 777.6233501529492,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 29.79314947550106,
			"height": 0.05858053082021884,
			"seed": 578894809,
			"groupIds": [
				"WgOLoW8LhV7KgycDXlZX0",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					29.79314947550106,
					-0.05858053082021884
				]
			]
		},
		{
			"type": "line",
			"version": 941,
			"versionNonce": 813404292,
			"isDeleted": false,
			"id": "xvmAxGhRvq0crVTwcS0jc",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1481.0643987233236,
			"y": 758.8023715492028,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 6.379225127822771,
			"height": 25.516900511291084,
			"seed": 774097463,
			"groupIds": [
				"WgOLoW8LhV7KgycDXlZX0",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					6.379225127822771,
					12.758450255645542
				],
				[
					0,
					25.516900511291084
				]
			]
		},
		{
			"type": "line",
			"version": 1017,
			"versionNonce": 1395042748,
			"isDeleted": false,
			"id": "Mtpa3vgHnwNXB7y8f-sF_",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1481.4363748818162,
			"y": 758.2057605843087,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 25.516900511291084,
			"height": 12.758450255645542,
			"seed": 243161273,
			"groupIds": [
				"WgOLoW8LhV7KgycDXlZX0",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					13.241739634912506,
					1.2887392316283568
				],
				[
					25.516900511291084,
					12.758450255645542
				]
			]
		},
		{
			"type": "line",
			"version": 954,
			"versionNonce": 1463738372,
			"isDeleted": false,
			"id": "UQS9Y9854TsrZ4wfy60Kj",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1481.1562865277758,
			"y": 783.8215579287424,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 25.516900511291084,
			"height": 12.758450255645542,
			"seed": 1639672663,
			"groupIds": [
				"WgOLoW8LhV7KgycDXlZX0",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					12.597370019098307,
					-1.6109159279312593
				],
				[
					25.516900511291084,
					-12.758450255645544
				]
			]
		},
		{
			"type": "line",
			"version": 895,
			"versionNonce": 1755451964,
			"isDeleted": false,
			"id": "TTCYv7TAlrpCrRSNda8Kk",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1506.7638142252074,
			"y": 803.8081878860925,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.137675383468306,
			"height": 0,
			"seed": 981784985,
			"groupIds": [
				"lSMDm7A3WXSek3dbLBaE7",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					19.137675383468306,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1046,
			"versionNonce": 2011971460,
			"isDeleted": false,
			"id": "4fCzzxZjDzq1muFytFIyT",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1455.8708297470496,
			"y": 797.1692529081382,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 29.676000212557554,
			"height": 0.058580530820291375,
			"seed": 1073866871,
			"groupIds": [
				"lSMDm7A3WXSek3dbLBaE7",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					29.676000212557554,
					-0.058580530820291375
				]
			]
		},
		{
			"type": "line",
			"version": 953,
			"versionNonce": 2073848508,
			"isDeleted": false,
			"id": "JKOB5erRB57lAP_Vfmn6m",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1455.839592725705,
			"y": 810.5925167708261,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 29.79314947550106,
			"height": 0.05858053082021884,
			"seed": 667434617,
			"groupIds": [
				"lSMDm7A3WXSek3dbLBaE7",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					29.79314947550106,
					-0.05858053082021884
				]
			]
		},
		{
			"type": "line",
			"version": 968,
			"versionNonce": 1791078148,
			"isDeleted": false,
			"id": "3NfgDXL50QfZlEuu7F7yX",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1481.6944620644665,
			"y": 791.1391431557819,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 6.379225127822771,
			"height": 25.516900511291084,
			"seed": 1186709911,
			"groupIds": [
				"lSMDm7A3WXSek3dbLBaE7",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					6.379225127822771,
					12.758450255645542
				],
				[
					0,
					25.516900511291084
				]
			]
		},
		{
			"type": "line",
			"version": 1044,
			"versionNonce": 1589097276,
			"isDeleted": false,
			"id": "iko86PAy37yJXCpTJQLUs",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1481.304067792051,
			"y": 791.0704225341291,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 25.516900511291084,
			"height": 12.758450255645542,
			"seed": 1695287129,
			"groupIds": [
				"lSMDm7A3WXSek3dbLBaE7",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					13.241739634912506,
					1.2887392316283568
				],
				[
					25.516900511291084,
					12.758450255645542
				]
			]
		},
		{
			"type": "line",
			"version": 981,
			"versionNonce": 1346186884,
			"isDeleted": false,
			"id": "QzdHgQvgLS4QJKbIgc36W",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1481.1789618766527,
			"y": 816.6895499388264,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 25.516900511291084,
			"height": 12.758450255645542,
			"seed": 1193113271,
			"groupIds": [
				"lSMDm7A3WXSek3dbLBaE7",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					12.597370019098307,
					-1.6109159279312593
				],
				[
					25.516900511291084,
					-12.758450255645544
				]
			]
		},
		{
			"type": "line",
			"version": 899,
			"versionNonce": 1079372732,
			"isDeleted": false,
			"id": "MEJWxv8mvqUSKSdpnDkW8",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1507.49323018251,
			"y": 834.5439191762677,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.137675383468306,
			"height": 0,
			"seed": 1554232377,
			"groupIds": [
				"WsIh_O56u_0ZulUU8i-L3",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					19.137675383468306,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1049,
			"versionNonce": 152878596,
			"isDeleted": false,
			"id": "P3egVIyER3V2Dc4JNKD0W",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1456.1837546593213,
			"y": 827.8754461121708,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 29.676000212557554,
			"height": 0.058580530820291375,
			"seed": 2009827287,
			"groupIds": [
				"WsIh_O56u_0ZulUU8i-L3",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					29.676000212557554,
					-0.058580530820291375
				]
			]
		},
		{
			"type": "line",
			"version": 955,
			"versionNonce": 848892988,
			"isDeleted": false,
			"id": "D3dR6j2ZSL8WoSIzKLLTG",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1456.1671066430747,
			"y": 840.672459297543,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 29.79314947550106,
			"height": 0.05858053082021884,
			"seed": 1651688729,
			"groupIds": [
				"WsIh_O56u_0ZulUU8i-L3",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					29.79314947550106,
					-0.05858053082021884
				]
			]
		},
		{
			"type": "line",
			"version": 971,
			"versionNonce": 777936260,
			"isDeleted": false,
			"id": "SrBVOgMWYCSuIsKFWlh_c",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1481.2400044901735,
			"y": 821.7360084002904,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 6.379225127822771,
			"height": 25.516900511291084,
			"seed": 1188721911,
			"groupIds": [
				"WsIh_O56u_0ZulUU8i-L3",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					6.379225127822771,
					12.758450255645542
				],
				[
					0,
					25.516900511291084
				]
			]
		},
		{
			"type": "line",
			"version": 1047,
			"versionNonce": 862137532,
			"isDeleted": false,
			"id": "KMI-jCmyA4LOayXwIV46o",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1481.3828065270343,
			"y": 821.7268672047136,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 25.516900511291084,
			"height": 12.758450255645542,
			"seed": 32291321,
			"groupIds": [
				"WsIh_O56u_0ZulUU8i-L3",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					13.241739634912506,
					1.2887392316283568
				],
				[
					25.516900511291084,
					12.758450255645542
				]
			]
		},
		{
			"type": "line",
			"version": 984,
			"versionNonce": 155192580,
			"isDeleted": false,
			"id": "fxrZ0GMFs9MKarnt8SfZE",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1482.0668113537051,
			"y": 847.4775365121017,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 25.516900511291084,
			"height": 12.758450255645542,
			"seed": 1808711191,
			"groupIds": [
				"WsIh_O56u_0ZulUU8i-L3",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					12.597370019098307,
					-1.6109159279312593
				],
				[
					25.516900511291084,
					-12.758450255645544
				]
			]
		},
		{
			"type": "line",
			"version": 926,
			"versionNonce": 878064956,
			"isDeleted": false,
			"id": "kjCbBlEGMj9smmA-DdCfb",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1507.0543173170634,
			"y": 866.9446320387386,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 19.137675383468306,
			"height": 0,
			"seed": 202707673,
			"groupIds": [
				"ba_pJFc_bNmZ8ophCB3ZO",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					19.137675383468306,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1076,
			"versionNonce": 188730500,
			"isDeleted": false,
			"id": "X9Q3AV4kbBY2bjnVBztni",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1456.0114174742341,
			"y": 860.5017624635638,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 29.676000212557554,
			"height": 0.058580530820291375,
			"seed": 966583095,
			"groupIds": [
				"ba_pJFc_bNmZ8ophCB3ZO",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					29.676000212557554,
					-0.058580530820291375
				]
			]
		},
		{
			"type": "line",
			"version": 982,
			"versionNonce": 584330684,
			"isDeleted": false,
			"id": "GOLJOT8nrYxSIjdUi3VKS",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1456.2327912482108,
			"y": 873.7778301158208,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 29.79314947550106,
			"height": 0.05858053082021884,
			"seed": 1702842297,
			"groupIds": [
				"ba_pJFc_bNmZ8ophCB3ZO",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					29.79314947550106,
					-0.05858053082021884
				]
			]
		},
		{
			"type": "line",
			"version": 998,
			"versionNonce": 1176214532,
			"isDeleted": false,
			"id": "bJaiMdoPGlxiAD92ZP2ta",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1481.8521365681838,
			"y": 854.354959630892,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 6.379225127822771,
			"height": 25.516900511291084,
			"seed": 816407639,
			"groupIds": [
				"ba_pJFc_bNmZ8ophCB3ZO",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					6.379225127822771,
					12.758450255645542
				],
				[
					0,
					25.516900511291084
				]
			]
		},
		{
			"type": "line",
			"version": 1073,
			"versionNonce": 1878988348,
			"isDeleted": false,
			"id": "nyajv1iMsDI-7gz46O9fH",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1481.532679061291,
			"y": 854.0597361989488,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 25.516900511291084,
			"height": 12.758450255645542,
			"seed": 340717721,
			"groupIds": [
				"ba_pJFc_bNmZ8ophCB3ZO",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					13.241739634912506,
					1.2887392316283568
				],
				[
					25.516900511291084,
					12.758450255645542
				]
			]
		},
		{
			"type": "line",
			"version": 1011,
			"versionNonce": 1674673028,
			"isDeleted": false,
			"id": "v2MBitBsmlsnsRJmTblIz",
			"fillStyle": "hachure",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 1481.7456694662835,
			"y": 880.3189289288338,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 25.516900511291084,
			"height": 12.758450255645542,
			"seed": 1355334007,
			"groupIds": [
				"ba_pJFc_bNmZ8ophCB3ZO",
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					12.597370019098307,
					-1.6109159279312593
				],
				[
					25.516900511291084,
					-12.758450255645544
				]
			]
		},
		{
			"type": "freedraw",
			"version": 218,
			"versionNonce": 414772924,
			"isDeleted": false,
			"id": "EVnwEW4XXr_2hJIAfWtCP",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1388.3365062043756,
			"y": 627.6555817078051,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 2.786870198895258,
			"height": 10.03272846359647,
			"seed": 238515577,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.5573655349262481,
					0.5573761659922525
				],
				[
					0,
					0.5573761659922525
				],
				[
					0.5573655349262481,
					0
				],
				[
					0.5573655349262481,
					-0.5573761659922525
				],
				[
					1.6721391290429892,
					-1.1147417009183869
				],
				[
					1.6721391290429892,
					-1.6721178669106962
				],
				[
					2.2295046639692373,
					-1.6721178669106962
				],
				[
					2.2295046639692373,
					-1.1147417009183869
				],
				[
					2.2295046639692373,
					0
				],
				[
					1.6721391290429892,
					2.2294940329030055
				],
				[
					1.6721391290429892,
					3.90162253087982
				],
				[
					1.6721391290429892,
					6.1311165637827685
				],
				[
					2.2295046639692373,
					7.245868895767387
				],
				[
					2.786870198895258,
					8.360610596685774
				],
				[
					2.786870198895258,
					8.360610596685774
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0,
				0.2578125,
				0.326171875,
				0.42578125,
				0.427734375,
				0.4287109375,
				0.427734375,
				0.427734375,
				0.4248046875,
				0.4091796875,
				0.3837890625,
				0.345703125,
				0.259765625,
				0.125,
				0.005859375,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 222,
			"versionNonce": 513764100,
			"isDeleted": false,
			"id": "IusFj1RwiZw2mVQpO89TF",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1382.2054002716588,
			"y": 646.6062969340796,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 5.573740397790516,
			"height": 8.360599965619599,
			"seed": 725580439,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.5573655349262481,
					-1.1147417009184437
				],
				[
					1.1147310698524961,
					-1.672117866910753
				],
				[
					1.6720966047785168,
					-2.2294940329030055
				],
				[
					2.2295046639692373,
					-2.786870198895258
				],
				[
					2.7868701988954854,
					-3.3442357338213924
				],
				[
					3.344235733821506,
					-3.3442357338213924
				],
				[
					3.344235733821506,
					-2.2294940329030055
				],
				[
					3.344235733821506,
					-1.672117866910753
				],
				[
					2.7868701988954854,
					0
				],
				[
					1.6720966047785168,
					1.6721284979768143
				],
				[
					1.6720966047785168,
					2.7868808299613193
				],
				[
					1.1147310698524961,
					3.901633161945938
				],
				[
					1.1147310698524961,
					4.458998696872072
				],
				[
					1.6720966047785168,
					5.016364231798207
				],
				[
					2.7868701988954854,
					4.458998696872072
				],
				[
					3.9016012687475268,
					4.458998696872072
				],
				[
					5.016374862864495,
					4.458998696872072
				],
				[
					5.573740397790516,
					5.016364231798207
				],
				[
					5.573740397790516,
					5.016364231798207
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.001953125,
				0.0771484375,
				0.205078125,
				0.259765625,
				0.3017578125,
				0.3134765625,
				0.31640625,
				0.32421875,
				0.326171875,
				0.326171875,
				0.326171875,
				0.326171875,
				0.3271484375,
				0.328125,
				0.326171875,
				0.326171875,
				0.3173828125,
				0.23828125,
				0.0986328125,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 226,
			"versionNonce": 765703996,
			"isDeleted": false,
			"id": "IfLRfEC8rHFzgWmiQST9g",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1381.6480347367328,
			"y": 661.0980240945482,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 6.1311484569812364,
			"height": 6.688492729775135,
			"seed": 1182555737,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.1147310698522688,
					-0.5573655349261912
				],
				[
					2.2294621397045375,
					-0.5573655349261912
				],
				[
					2.786870198895258,
					-0.5573655349261912
				],
				[
					3.344235733821506,
					-0.5573655349261912
				],
				[
					3.9016012687475268,
					-0.5573655349261912
				],
				[
					4.4589668036735475,
					0
				],
				[
					4.4589668036735475,
					0.5573867970584274
				],
				[
					3.9016012687475268,
					1.1147523319845618
				],
				[
					3.344235733821506,
					2.2295046639690668
				],
				[
					2.786870198895258,
					2.786870198895258
				],
				[
					3.344235733821506,
					2.786870198895258
				],
				[
					3.9016012687475268,
					3.3442569959536854
				],
				[
					4.4589668036735475,
					3.3442569959536854
				],
				[
					5.0163323385997955,
					3.90162253087982
				],
				[
					5.573740397790516,
					4.458988065805954
				],
				[
					5.573740397790516,
					5.016374862864325
				],
				[
					5.0163323385997955,
					5.573740397790516
				],
				[
					3.9016012687475268,
					5.573740397790516
				],
				[
					2.786870198895258,
					6.131127194848943
				],
				[
					1.6720966047785168,
					6.131127194848943
				],
				[
					0,
					6.131127194848943
				],
				[
					-0.5574080591907205,
					6.131127194848943
				],
				[
					-0.5574080591907205,
					6.131127194848943
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0,
				0.1826171875,
				0.2333984375,
				0.23828125,
				0.2412109375,
				0.25390625,
				0.2890625,
				0.30859375,
				0.3173828125,
				0.3134765625,
				0.306640625,
				0.2958984375,
				0.294921875,
				0.294921875,
				0.2958984375,
				0.2958984375,
				0.29296875,
				0.2880859375,
				0.2744140625,
				0.240234375,
				0.162109375,
				0.0166015625,
				0.0029296875,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 218,
			"versionNonce": 956525188,
			"isDeleted": false,
			"id": "GFTTuzB5AHtvGDl9WvJLR",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1380.5332611426159,
			"y": 672.2455048901293,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 3.9016012687475268,
			"height": 7.245858264701269,
			"seed": 885133239,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-0.5573655349261912
				],
				[
					0,
					0
				],
				[
					0,
					0.5573867970584274
				],
				[
					-0.5573655349260207,
					1.6721178669106962
				],
				[
					-0.5573655349260207,
					2.2295046639690668
				],
				[
					-1.1147310698520414,
					3.3442569959536854
				],
				[
					-1.1147310698520414,
					4.458988065805954
				],
				[
					-1.1147310698520414,
					5.573740397790516
				],
				[
					-0.5573655349260207,
					6.131127194848943
				],
				[
					0.5573655349262481,
					6.688492729775078
				],
				[
					1.1147735941169685,
					6.688492729775078
				],
				[
					1.6721391290429892,
					6.131127194848943
				],
				[
					2.2295046639692373,
					6.131127194848943
				],
				[
					2.7868701988954854,
					6.131127194848943
				],
				[
					2.7868701988954854,
					6.131127194848943
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.001953125,
				0.1513671875,
				0.2392578125,
				0.2861328125,
				0.3330078125,
				0.3388671875,
				0.345703125,
				0.3486328125,
				0.3486328125,
				0.3447265625,
				0.30078125,
				0.271484375,
				0.1826171875,
				0.154296875,
				0.0634765625,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 212,
			"versionNonce": 1528917948,
			"isDeleted": false,
			"id": "PHM-B0dS4hCok-28zdUiF",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1383.8774968764374,
			"y": 674.4750095540983,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 1.1147735941167412,
			"height": 8.360610596685774,
			"seed": 2079402809,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.5574080591907205,
					0
				],
				[
					0.5574080591907205,
					1.1147523319846186
				],
				[
					0.5574080591907205,
					2.2294834018368874
				],
				[
					0,
					3.9016225308798766
				],
				[
					0,
					5.016353600732145
				],
				[
					-0.5573655349260207,
					6.688492729775135
				],
				[
					0,
					7.245858264701269
				],
				[
					0,
					8.360610596685774
				],
				[
					0,
					8.360610596685774
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0029296875,
				0.173828125,
				0.279296875,
				0.296875,
				0.2939453125,
				0.265625,
				0.166015625,
				0.080078125,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 224,
			"versionNonce": 1975220740,
			"isDeleted": false,
			"id": "9hI0fzLdLIedFlXLL-rEE",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1382.2054002716588,
			"y": 683.9503724827686,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 5.016374862864495,
			"height": 7.245858264701212,
			"seed": 1467285719,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.5573655349262481,
					-0.5573867970584274
				],
				[
					0,
					0
				],
				[
					-0.5573655349260207,
					0.5573655349261344
				],
				[
					-1.1147735941167412,
					0.5573655349261344
				],
				[
					-1.1147735941167412,
					1.1147310698522688
				],
				[
					-1.1147735941167412,
					1.6721178669106393
				],
				[
					-1.1147735941167412,
					2.2294834018368306
				],
				[
					0,
					2.786870198895258
				],
				[
					0,
					3.9016012687475268
				],
				[
					0.5573655349262481,
					4.458988065805897
				],
				[
					1.1147310698524961,
					5.016353600732089
				],
				[
					1.1147310698524961,
					5.573740397790516
				],
				[
					1.1147310698524961,
					6.13110593271665
				],
				[
					0.5573655349262481,
					6.688471467642785
				],
				[
					0,
					6.688471467642785
				],
				[
					-1.1147735941167412,
					6.688471467642785
				],
				[
					-2.22950466396901,
					6.688471467642785
				],
				[
					-2.7868701988950306,
					6.13110593271665
				],
				[
					-3.3442357338212787,
					6.13110593271665
				],
				[
					-3.901643793011999,
					6.13110593271665
				],
				[
					-3.901643793011999,
					6.13110593271665
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.001953125,
				0.0341796875,
				0.2978515625,
				0.298828125,
				0.298828125,
				0.2998046875,
				0.3017578125,
				0.3017578125,
				0.296875,
				0.2958984375,
				0.2958984375,
				0.2998046875,
				0.3056640625,
				0.310546875,
				0.3125,
				0.3154296875,
				0.318359375,
				0.3076171875,
				0.2421875,
				0.2177734375,
				0.0029296875,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 224,
			"versionNonce": 1901336636,
			"isDeleted": false,
			"id": "ykdVDhyi8OoB8S2jHbO91",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1383.8774968764374,
			"y": 696.7699711452605,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 5.0163323385997955,
			"height": 7.80322379962729,
			"seed": 1190747161,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.6721178669106393
				],
				[
					-0.5573655349260207,
					-1.114752331984505
				],
				[
					-1.6720966047785168,
					0
				],
				[
					-2.786870198895258,
					1.1147523319846186
				],
				[
					-3.344235733821506,
					2.2294834018368874
				],
				[
					-3.9016012687475268,
					3.3442357338213924
				],
				[
					-3.9016012687475268,
					3.9016225308798766
				],
				[
					-3.9016012687475268,
					5.016353600732145
				],
				[
					-3.344235733821506,
					5.573740397790516
				],
				[
					-2.786870198895258,
					5.573740397790516
				],
				[
					-2.2294621397045375,
					6.13110593271665
				],
				[
					-1.1147310698522688,
					5.573740397790516
				],
				[
					-0.5573655349260207,
					4.458988065806011
				],
				[
					0,
					3.9016225308798766
				],
				[
					0,
					3.3442357338213924
				],
				[
					-0.5573655349260207,
					3.3442357338213924
				],
				[
					-1.1147310698522688,
					3.9016225308798766
				],
				[
					-2.786870198895258,
					3.9016225308798766
				],
				[
					-3.9016012687475268,
					4.458988065806011
				],
				[
					-5.0163323385997955,
					5.016353600732145
				],
				[
					-5.0163323385997955,
					5.016353600732145
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0009765625,
				0.140625,
				0.3212890625,
				0.3701171875,
				0.3828125,
				0.384765625,
				0.384765625,
				0.384765625,
				0.376953125,
				0.365234375,
				0.3466796875,
				0.3369140625,
				0.3310546875,
				0.330078125,
				0.3291015625,
				0.3291015625,
				0.328125,
				0.32421875,
				0.2880859375,
				0.1953125,
				0.0546875,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 220,
			"versionNonce": 264608132,
			"isDeleted": false,
			"id": "QrnoXo5GsZEfGpctI0v7A",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1385.5496360054804,
			"y": 719.0649327364223,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 4.458966803673775,
			"height": 9.475362928670279,
			"seed": 1156369911,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.5573655349260207,
					-1.114752331984505
				],
				[
					1.1147310698522688,
					-2.2295046639691236
				],
				[
					1.1147310698522688,
					-3.901622530879763
				],
				[
					1.1147310698522688,
					-5.016374862864382
				],
				[
					1.1147310698522688,
					-6.688492729775021
				],
				[
					1.1147310698522688,
					-7.80324506175964
				],
				[
					0.5573655349260207,
					-8.360610596685774
				],
				[
					0.5573655349260207,
					-8.917997393744145
				],
				[
					0,
					-9.475362928670279
				],
				[
					-1.1147310698522688,
					-9.475362928670279
				],
				[
					-2.22950466396901,
					-9.475362928670279
				],
				[
					-2.786870198895258,
					-8.917997393744145
				],
				[
					-3.344235733821506,
					-8.917997393744145
				],
				[
					-3.344235733821506,
					-8.360610596685774
				],
				[
					-2.786870198895258,
					-8.360610596685774
				],
				[
					-2.786870198895258,
					-7.80324506175964
				],
				[
					-2.786870198895258,
					-7.80324506175964
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.009765625,
				0.240234375,
				0.296875,
				0.2998046875,
				0.2998046875,
				0.302734375,
				0.318359375,
				0.3232421875,
				0.3271484375,
				0.33984375,
				0.35546875,
				0.361328125,
				0.359375,
				0.3515625,
				0.103515625,
				0.0302734375,
				0.00390625,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 210,
			"versionNonce": 1813885116,
			"isDeleted": false,
			"id": "2-hgX7llqqS-xLQY5JCvz",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1388.8938717393019,
			"y": 713.4911923386318,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 7.245837002569033,
			"height": 1.672117866910753,
			"seed": 1736995065,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-0.5573655349262481,
					0.5573655349261344
				],
				[
					-1.6720966047785168,
					1.1147523319845618
				],
				[
					-3.344235733821506,
					1.1147523319845618
				],
				[
					-5.016374862864495,
					1.1147523319845618
				],
				[
					-6.131105932716764,
					1.1147523319845618
				],
				[
					-7.245837002569033,
					1.672117866910753
				],
				[
					-7.245837002569033,
					1.672117866910753
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0,
				0.1962890625,
				0.3193359375,
				0.3154296875,
				0.25,
				0.130859375,
				0.0009765625,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 227,
			"versionNonce": 845138180,
			"isDeleted": false,
			"id": "6uITvU4Gq1zgGys4XkhkX",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1385.5496360054804,
			"y": 727.4255433331081,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 6.688471467643012,
			"height": 8.917976131611965,
			"seed": 137230103,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.5573655349260207,
					-1.1147523319845618
				],
				[
					0,
					-1.1147523319845618
				],
				[
					-2.22950466396901,
					0.5573655349261912
				],
				[
					-2.786870198895258,
					0.5573655349261912
				],
				[
					-3.344235733821506,
					1.1147523319845618
				],
				[
					-2.786870198895258,
					1.6721178669106962
				],
				[
					-2.22950466396901,
					2.2294834018368874
				],
				[
					-1.1147310698522688,
					2.786870198895258
				],
				[
					0,
					3.90162253087982
				],
				[
					0.5573655349260207,
					4.458988065805954
				],
				[
					1.1147310698522688,
					5.016353600732145
				],
				[
					0.5573655349260207,
					6.131105932716707
				],
				[
					0,
					7.245858264701212
				],
				[
					-1.1147310698522688,
					7.803223799627403
				],
				[
					-1.6721391290429892,
					7.803223799627403
				],
				[
					-2.22950466396901,
					7.803223799627403
				],
				[
					-2.22950466396901,
					6.688492729775078
				],
				[
					-1.6721391290429892,
					6.131105932716707
				],
				[
					-0.5573655349260207,
					4.458988065805954
				],
				[
					1.6721391290429892,
					2.786870198895258
				],
				[
					2.22950466396901,
					1.6721178669106962
				],
				[
					3.344235733821506,
					1.6721178669106962
				],
				[
					0,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0,
				0.0673828125,
				0.369140625,
				0.4248046875,
				0.4248046875,
				0.423828125,
				0.4169921875,
				0.396484375,
				0.3828125,
				0.3642578125,
				0.3564453125,
				0.3486328125,
				0.3408203125,
				0.337890625,
				0.3310546875,
				0.322265625,
				0.3115234375,
				0.30859375,
				0.30859375,
				0.3056640625,
				0.2294921875,
				0.111328125,
				0.01953125,
				0
			]
		},
		{
			"type": "line",
			"version": 248,
			"versionNonce": 2065709372,
			"isDeleted": false,
			"id": "yfAzAICwRPJK-Vml2mXrp",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1154.2394520214384,
			"y": 632.114569773611,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 2.22950466396901,
			"height": 76.36024770215647,
			"seed": 411754233,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-2.22950466396901,
					76.36024770215647
				]
			]
		},
		{
			"type": "line",
			"version": 241,
			"versionNonce": 1896351876,
			"isDeleted": false,
			"id": "KMV7ihNsquBrZUB--dpIG",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1153.1247209515861,
			"y": 777.0318413782965,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 1.1147310698522688,
			"height": 79.14709663891949,
			"seed": 827418903,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					1.1147310698522688,
					79.14709663891949
				]
			]
		},
		{
			"type": "line",
			"version": 291,
			"versionNonce": 163426748,
			"isDeleted": false,
			"id": "rVfi6PK55Hc1HKBh1Zmjc",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 887.4563118585561,
			"y": 725.4440161325048,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 279.3611540981601,
			"height": 7.786013006283122,
			"seed": 919255161,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					279.3611540981601,
					-7.786013006283122
				]
			]
		},
		{
			"type": "line",
			"version": 242,
			"versionNonce": 1065113604,
			"isDeleted": false,
			"id": "M15M6sEC_cWE9YkcVARaU",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1100.8335756470635,
			"y": 724.5957218394245,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 5.016374862864495,
			"height": 287.04764111727764,
			"seed": 887750935,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					-5.016374862864495,
					-287.04764111727764
				]
			]
		},
		{
			"type": "line",
			"version": 323,
			"versionNonce": 1192761916,
			"isDeleted": false,
			"id": "VBqWFeGWSyOwCbi_esUXB",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1099.1614365180205,
			"y": 719.5793257144279,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 2.22950466396901,
			"height": 151.6057218101962,
			"seed": 181807671,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					2.22950466396901,
					151.6057218101962
				]
			]
		},
		{
			"type": "line",
			"version": 222,
			"versionNonce": 1773844356,
			"isDeleted": false,
			"id": "t04CNF-RwdgQ1zCswF8I8",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1100.8335756470635,
			"y": 868.9555853849191,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 61.8685099106217,
			"height": 1.1147310698522688,
			"seed": 1297849591,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					61.8685099106217,
					1.1147310698522688
				]
			]
		},
		{
			"type": "line",
			"version": 258,
			"versionNonce": 772895420,
			"isDeleted": false,
			"id": "V_trvbD56ErLj91fHshLa",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 795.9499928976281,
			"y": 755.8086383000663,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 280.91648202923034,
			"height": 1.6721391290429324,
			"seed": 1587811479,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					280.91648202923034,
					-1.6721391290429324
				]
			]
		},
		{
			"type": "line",
			"version": 281,
			"versionNonce": 201402116,
			"isDeleted": false,
			"id": "2TpFtbQ_qJgEZQcTuBqDq",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1069.6206379242894,
			"y": 450.92503428849875,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 6.688471467642785,
			"height": 433.0796331607494,
			"seed": 879323321,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					6.688471467642785,
					433.0796331607494
				]
			]
		},
		{
			"type": "line",
			"version": 283,
			"versionNonce": 223066940,
			"isDeleted": false,
			"id": "NJcLcQYqXnyHpbbNIUWOL",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1078.3739687224797,
			"y": 879.3250044065747,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 89.34444917380529,
			"height": 0.22069623899892576,
			"seed": 1105303673,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					89.34444917380529,
					0.22069623899892576
				]
			]
		},
		{
			"type": "line",
			"version": 284,
			"versionNonce": 181249668,
			"isDeleted": false,
			"id": "6BFw2-ZAwPCGCUYJUMweI",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1074.6395725925186,
			"y": 732.3989031147872,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 94.19374647067707,
			"height": 0,
			"seed": 1614582007,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					94.19374647067707,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 280,
			"versionNonce": 254342076,
			"isDeleted": false,
			"id": "AbPLln5ESvf9FWn-Yjdvv",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1076.5514417818601,
			"y": 601.2218204791722,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 88.38019096405878,
			"height": 2.0353001142985363,
			"seed": 1475249881,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					88.38019096405878,
					-2.0353001142985363
				]
			]
		},
		{
			"type": "line",
			"version": 245,
			"versionNonce": 182334980,
			"isDeleted": false,
			"id": "Ystse7MJEnneE81TNVV3m",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1070.7353689941417,
			"y": 452.0397759894172,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 89.73725442383898,
			"height": 3.9016118998137017,
			"seed": 1325145239,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					89.73725442383898,
					-3.9016118998137017
				]
			]
		},
		{
			"type": "freedraw",
			"version": 200,
			"versionNonce": 1103830076,
			"isDeleted": false,
			"id": "RcUC9G-rNQiXPnM5-INAj",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1381.212980862689,
			"y": 349.6434745277177,
			"strokeColor": "#862e9c",
			"backgroundColor": "transparent",
			"width": 3.165619979572284,
			"height": 11.712790301653172,
			"seed": 1053045527,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.633114335208802,
					0
				],
				[
					0.633114335208802,
					-0.6331264110908137
				],
				[
					1.2662286704178314,
					-1.582809989786199
				],
				[
					1.5828099897860284,
					-2.2159364008770126
				],
				[
					2.2159243249950578,
					-2.849062811967883
				],
				[
					2.5324573408356628,
					-3.165619979572341
				],
				[
					2.849038660204087,
					-2.849062811967883
				],
				[
					2.849038660204087,
					-2.532499606422448
				],
				[
					2.849038660204087,
					-1.2662528221816842
				],
				[
					2.5324573408356628,
					0.9496835786953284
				],
				[
					2.5324573408356628,
					4.115303558267726
				],
				[
					2.5324573408356628,
					6.0146767535993035
				],
				[
					2.5324573408356628,
					7.914049948930938
				],
				[
					2.5324573408356628,
					8.54717032208083
				],
				[
					2.849038660204087,
					8.54717032208083
				],
				[
					3.165619979572284,
					8.230607116535396
				],
				[
					3.165619979572284,
					8.230607116535396
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.005859375,
				0.4365234375,
				0.447265625,
				0.5126953125,
				0.5634765625,
				0.59765625,
				0.5986328125,
				0.6015625,
				0.609375,
				0.6162109375,
				0.615234375,
				0.61328125,
				0.611328125,
				0.5673828125,
				0.40625,
				0.3564453125,
				0.0439453125,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 203,
			"versionNonce": 1764808068,
			"isDeleted": false,
			"id": "ad9ty7uQwMLLVjfrCEybV",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1377.7307795637482,
			"y": 365.788137631125,
			"strokeColor": "#862e9c",
			"backgroundColor": "transparent",
			"width": 6.014658639776371,
			"height": 9.813417106321594,
			"seed": 791888313,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-0.31656924348635584
				],
				[
					0.316581319368197,
					-0.6331264110908705
				],
				[
					0.6331143352090294,
					-0.9496835786953284
				],
				[
					0.9496956545772264,
					-1.582809989786199
				],
				[
					1.5828099897862558,
					-2.2159364008770126
				],
				[
					2.532505644363482,
					-2.5324935684815273
				],
				[
					2.849038660204087,
					-2.2159364008770126
				],
				[
					2.849038660204087,
					-0.9496835786953284
				],
				[
					2.2159243249950578,
					0.6331264110908705
				],
				[
					1.5828099897862558,
					2.5324935684815273
				],
				[
					0.6331143352090294,
					4.431860725872184
				],
				[
					0.316581319368197,
					7.280923537840067
				],
				[
					1.2662286704180588,
					7.280923537840067
				],
				[
					2.2159243249950578,
					6.9643663702355525
				],
				[
					4.1153156341495105,
					6.331239959144739
				],
				[
					5.065011288726737,
					6.331239959144739
				],
				[
					5.381544304567569,
					6.331239959144739
				],
				[
					6.014658639776371,
					6.331239959144739
				],
				[
					6.014658639776371,
					6.647797126749197
				],
				[
					6.014658639776371,
					6.647797126749197
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0,
				0.064453125,
				0.359375,
				0.3623046875,
				0.3623046875,
				0.3642578125,
				0.37109375,
				0.3720703125,
				0.3671875,
				0.3623046875,
				0.359375,
				0.3603515625,
				0.419921875,
				0.4365234375,
				0.439453125,
				0.43359375,
				0.3876953125,
				0.306640625,
				0.01953125,
				0.0029296875,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 207,
			"versionNonce": 521417916,
			"isDeleted": false,
			"id": "_iOcCgZgemNZfly911dFX",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1378.3638938989573,
			"y": 378.45061754941446,
			"strokeColor": "#862e9c",
			"backgroundColor": "transparent",
			"width": 6.014706943303963,
			"height": 7.597492781326423,
			"seed": 1026877273,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.316581319368197,
					-0.6331264110908705
				],
				[
					0.6331143352090294,
					-0.9496835786953852
				],
				[
					1.2662769739454234,
					-1.266252822181741
				],
				[
					1.8993913091544528,
					-1.582809989786199
				],
				[
					3.165619979572284,
					-1.8993792332725548
				],
				[
					4.1153156341495105,
					-1.8993792332725548
				],
				[
					4.4318969535177075,
					-1.582809989786199
				],
				[
					4.4318969535177075,
					-0.6331264110908705
				],
				[
					3.7987343147813135,
					0.31655716760445785
				],
				[
					3.165619979572284,
					1.2662407462997862
				],
				[
					2.5325056443632548,
					1.8993671573906568
				],
				[
					2.849086963731679,
					1.582809989786142
				],
				[
					3.165619979572284,
					1.582809989786142
				],
				[
					4.1153156341495105,
					1.2662407462997862
				],
				[
					5.065011288726737,
					0.9496835786953284
				],
				[
					5.698125623935766,
					1.2662407462997862
				],
				[
					6.014706943303963,
					1.8993671573906568
				],
				[
					6.014706943303963,
					2.849050736085985
				],
				[
					5.381544304567342,
					4.431860725872184
				],
				[
					4.1153156341495105,
					5.064987136962998
				],
				[
					2.5325056443632548,
					5.698113548053868
				],
				[
					1.5828099897860284,
					5.38155638044941
				],
				[
					0.316581319368197,
					4.431860725872184
				],
				[
					0,
					4.115303558267669
				],
				[
					0,
					4.115303558267669
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.00390625,
				0.302734375,
				0.3837890625,
				0.419921875,
				0.4287109375,
				0.4375,
				0.44140625,
				0.4423828125,
				0.439453125,
				0.4365234375,
				0.431640625,
				0.4267578125,
				0.4169921875,
				0.416015625,
				0.4111328125,
				0.41015625,
				0.4130859375,
				0.41796875,
				0.421875,
				0.4208984375,
				0.423828125,
				0.4228515625,
				0.4169921875,
				0.2919921875,
				0.1298828125,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 193,
			"versionNonce": 855868676,
			"isDeleted": false,
			"id": "LRN5M7dyosLRfD4ewcdNc",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1377.7307795637482,
			"y": 389.2137182344313,
			"strokeColor": "#862e9c",
			"backgroundColor": "transparent",
			"width": 4.74842996935854,
			"height": 7.597492781326423,
			"seed": 105872727,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-0.316581319368197,
					2.2159364008770694
				],
				[
					-0.6331143352090294,
					3.4821892230587537
				],
				[
					-0.9496956545772264,
					5.064999212844896
				],
				[
					-0.9496956545772264,
					6.014682791540281
				],
				[
					-0.316581319368197,
					6.964366370235609
				],
				[
					0.6331143352090294,
					7.597492781326423
				],
				[
					1.5828099897862558,
					7.280935613721965
				],
				[
					2.532505644363482,
					6.6478092026311515
				],
				[
					3.165619979572284,
					5.698125623935766
				],
				[
					3.7987343147813135,
					4.74842996935854
				],
				[
					3.7987343147813135,
					4.74842996935854
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0009765625,
				0.2900390625,
				0.337890625,
				0.35546875,
				0.36328125,
				0.3818359375,
				0.3818359375,
				0.3515625,
				0.248046875,
				0.0859375,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 191,
			"versionNonce": 346438972,
			"isDeleted": false,
			"id": "cRzRwzHv8xaQ1OSBrw26d",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1382.1626282137386,
			"y": 389.8468446455222,
			"strokeColor": "#862e9c",
			"backgroundColor": "transparent",
			"width": 0.9496956545772264,
			"height": 11.079669928503279,
			"seed": 1033937113,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.316581319368197,
					1.266252822181741
				],
				[
					0,
					2.2159364008770126
				],
				[
					-0.6331143352090294,
					4.115303558267669
				],
				[
					-0.6331143352090294,
					6.331239959144739
				],
				[
					-0.3165330158408324,
					8.547176360021751
				],
				[
					-0.6331143352090294,
					10.12998634980795
				],
				[
					-0.3165330158408324,
					10.76311276089882
				],
				[
					0,
					11.079669928503279
				],
				[
					0,
					11.079669928503279
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.00390625,
				0.37890625,
				0.4169921875,
				0.443359375,
				0.4638671875,
				0.447265625,
				0.3115234375,
				0.171875,
				0.013671875,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 210,
			"versionNonce": 500450436,
			"isDeleted": false,
			"id": "I47EgNpW0Rzhyik36uPFl",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1381.212980862689,
			"y": 401.5596409851163,
			"strokeColor": "#862e9c",
			"backgroundColor": "transparent",
			"width": 6.331264110908705,
			"height": 9.180302771112679,
			"seed": 1455297239,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-0.3165813193684244,
					0.3165571676045147
				],
				[
					-0.9496956545772264,
					0.6331264110908705
				],
				[
					-1.8993913091544528,
					0.6331264110908705
				],
				[
					-2.532505644363482,
					0.6331264110908705
				],
				[
					-2.849086963731679,
					0.9496835786953852
				],
				[
					-3.1656199795725115,
					0.9496835786953852
				],
				[
					-2.849086963731679,
					0.9496835786953852
				],
				[
					-2.849086963731679,
					1.266252822181741
				],
				[
					-2.849086963731679,
					1.8993671573907136
				],
				[
					-2.849086963731679,
					2.5324935684815273
				],
				[
					-2.849086963731679,
					3.4821771471769125
				],
				[
					-2.849086963731679,
					3.7987463906632684
				],
				[
					-2.849086963731679,
					4.431872801754082
				],
				[
					-2.532505644363482,
					4.431872801754082
				],
				[
					-2.2159726285226498,
					4.115303558267726
				],
				[
					-1.5828099897862558,
					3.7987463906632684
				],
				[
					-0.9496956545772264,
					3.7987463906632684
				],
				[
					-0.3165813193684244,
					4.431872801754082
				],
				[
					0,
					5.38155638044941
				],
				[
					0,
					6.6477971267492535
				],
				[
					-0.3165813193684244,
					7.597492781326423
				],
				[
					-1.2662769739456508,
					8.547176360021808
				],
				[
					-2.849086963731679,
					9.180302771112679
				],
				[
					-4.431896953517935,
					9.180302771112679
				],
				[
					-5.698149775699676,
					8.863733527626266
				],
				[
					-6.331264110908705,
					8.547176360021808
				],
				[
					-6.014706943304191,
					8.230607116535452
				],
				[
					-6.014706943304191,
					8.230607116535452
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0048828125,
				0.271484375,
				0.30859375,
				0.3125,
				0.3173828125,
				0.3310546875,
				0.34375,
				0.34375,
				0.3466796875,
				0.3466796875,
				0.3466796875,
				0.3466796875,
				0.345703125,
				0.337890625,
				0.3291015625,
				0.330078125,
				0.3359375,
				0.3408203125,
				0.3544921875,
				0.375,
				0.388671875,
				0.39453125,
				0.3974609375,
				0.3984375,
				0.396484375,
				0.375,
				0.2109375,
				0.0224609375,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 203,
			"versionNonce": 199439804,
			"isDeleted": false,
			"id": "tyeswKJElqdtN14ncPyfe",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1380.8963995433205,
			"y": 413.5889944923149,
			"strokeColor": "#862e9c",
			"backgroundColor": "transparent",
			"width": 4.431848649990343,
			"height": 9.496859938717137,
			"seed": 1139774391,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-0.9496956545772264,
					0.3165692434864127
				],
				[
					-1.5828099897860284,
					0.9496835786953852
				],
				[
					-2.5325056443632548,
					1.5828099897862558
				],
				[
					-3.165619979572284,
					2.5324935684815273
				],
				[
					-3.165619979572284,
					4.115303558267726
				],
				[
					-3.165619979572284,
					5.38155638044941
				],
				[
					-3.165619979572284,
					7.280923537840067
				],
				[
					-2.5325056443632548,
					8.547176360021808
				],
				[
					-1.8993913091542254,
					9.180302771112679
				],
				[
					-0.9496956545772264,
					9.496859938717137
				],
				[
					-0.316581319368197,
					9.180302771112679
				],
				[
					1.2662286704180588,
					6.331239959144796
				],
				[
					1.2662286704180588,
					5.064999212844953
				],
				[
					1.2662286704180588,
					4.74842996935854
				],
				[
					0.3165813193684244,
					4.74842996935854
				],
				[
					-0.633114335208802,
					5.064999212844953
				],
				[
					-1.8993913091542254,
					5.698113548053925
				],
				[
					-2.5325056443632548,
					5.698113548053925
				],
				[
					-2.849038660204087,
					6.014682791540281
				],
				[
					-2.5325056443632548,
					6.014682791540281
				],
				[
					-2.5325056443632548,
					6.014682791540281
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0029296875,
				0.3857421875,
				0.4775390625,
				0.5234375,
				0.572265625,
				0.6298828125,
				0.654296875,
				0.66015625,
				0.646484375,
				0.6181640625,
				0.548828125,
				0.513671875,
				0.43359375,
				0.416015625,
				0.4189453125,
				0.451171875,
				0.4775390625,
				0.49609375,
				0.484375,
				0.3896484375,
				0.0556640625,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 199,
			"versionNonce": 2137068548,
			"isDeleted": false,
			"id": "3K95UHFaNMBNkTbs3wihz",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1382.795790852475,
			"y": 437.3311443391076,
			"strokeColor": "#862e9c",
			"backgroundColor": "transparent",
			"width": 5.381544304567569,
			"height": 8.230607116535396,
			"seed": 1223818457,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-0.31655716760445785
				],
				[
					0.3165330158408324,
					-1.8993671573906568
				],
				[
					0.3165330158408324,
					-3.7987463906632115
				],
				[
					0.3165330158408324,
					-5.381556380449354
				],
				[
					0.3165330158408324,
					-6.964366370235609
				],
				[
					0.6331143352090294,
					-7.597480705444525
				],
				[
					0.3165330158408324,
					-8.230607116535396
				],
				[
					0,
					-8.230607116535396
				],
				[
					-0.633162638736394,
					-8.230607116535396
				],
				[
					-1.5828099897860284,
					-7.914049948930881
				],
				[
					-2.849086963731679,
					-7.28092353784001
				],
				[
					-3.798782618308678,
					-6.964366370235609
				],
				[
					-4.4318969535177075,
					-6.647797126749197
				],
				[
					-4.74842996935854,
					-6.647797126749197
				],
				[
					-4.4318969535177075,
					-6.647797126749197
				],
				[
					-4.1153156341495105,
					-6.647797126749197
				],
				[
					-4.1153156341495105,
					-6.647797126749197
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0029296875,
				0.275390625,
				0.39453125,
				0.392578125,
				0.392578125,
				0.3974609375,
				0.3974609375,
				0.3974609375,
				0.400390625,
				0.404296875,
				0.4091796875,
				0.41015625,
				0.4052734375,
				0.376953125,
				0.3134765625,
				0.11328125,
				0.0185546875,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 189,
			"versionNonce": 1911365180,
			"isDeleted": false,
			"id": "g-70g_wzbmXtqmd4LDhuM",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1385.01171517747,
			"y": 434.1655243595353,
			"strokeColor": "#862e9c",
			"backgroundColor": "transparent",
			"width": 6.014706943303736,
			"height": 0.9496835786953852,
			"seed": 1701860183,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-0.949695654576999,
					-0.3165571676045147
				],
				[
					-1.5828099897860284,
					-0.3165571676045147
				],
				[
					-3.165619979572284,
					-0.3165571676045147
				],
				[
					-4.7484299693583125,
					0
				],
				[
					-5.698125623935539,
					0.31656924348635584
				],
				[
					-6.014706943303736,
					0.6331264110908705
				],
				[
					-6.014706943303736,
					0.6331264110908705
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.001953125,
				0.43359375,
				0.4775390625,
				0.4453125,
				0.296875,
				0.0693359375,
				0.0009765625,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 205,
			"versionNonce": 1168634756,
			"isDeleted": false,
			"id": "2LSIETRvwPR3O9IM5da6J",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1381.8460951978977,
			"y": 443.3458271306479,
			"strokeColor": "#862e9c",
			"backgroundColor": "transparent",
			"width": 6.964354294353598,
			"height": 12.345910674803122,
			"seed": 1062493465,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-0.633114335208802,
					0.9496835786953852
				],
				[
					-1.5828099897860284,
					1.8993671573906568
				],
				[
					-2.5325056443632548,
					2.849050736086042
				],
				[
					-2.5325056443632548,
					3.4821771471769125
				],
				[
					-2.2159243249950578,
					4.115303558267726
				],
				[
					-1.5828099897860284,
					4.74842996935854
				],
				[
					-0.633114335208802,
					6.014670715658383
				],
				[
					0.6331143352090294,
					6.964366370235609
				],
				[
					1.2662286704180588,
					7.914049948930938
				],
				[
					1.8993430056268608,
					9.180290695230724
				],
				[
					1.2662286704180588,
					10.446543517412465
				],
				[
					0.3165330158408324,
					11.396227096107793
				],
				[
					-0.9496956545772264,
					12.345910674803122
				],
				[
					-2.2159243249950578,
					12.345910674803122
				],
				[
					-2.2159243249950578,
					11.396227096107793
				],
				[
					-1.2662769739454234,
					9.180290695230724
				],
				[
					0.3165330158408324,
					6.964366370235609
				],
				[
					2.532505644363482,
					4.431860725872184
				],
				[
					3.7987343147813135,
					2.849050736086042
				],
				[
					4.431848649990343,
					1.8993671573906568
				],
				[
					3.7987343147813135,
					2.849050736086042
				],
				[
					3.165619979572284,
					3.7987463906632684
				],
				[
					3.165619979572284,
					3.7987463906632684
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.001953125,
				0.38671875,
				0.3994140625,
				0.3935546875,
				0.390625,
				0.3876953125,
				0.3828125,
				0.3759765625,
				0.380859375,
				0.39453125,
				0.427734375,
				0.4345703125,
				0.4345703125,
				0.4345703125,
				0.4326171875,
				0.4296875,
				0.4248046875,
				0.416015625,
				0.4052734375,
				0.3984375,
				0.361328125,
				0.140625,
				0.001953125,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 203,
			"versionNonce": 1067841212,
			"isDeleted": false,
			"id": "rFsBa6l11wpjbx6QgBzOh",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1382.1626523655023,
			"y": 495.5785507556509,
			"strokeColor": "#862e9c",
			"backgroundColor": "transparent",
			"width": 4.1153156341495105,
			"height": 9.49685993871708,
			"seed": 1718518391,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.9496715028133167,
					-0.6331143352089725
				],
				[
					1.2662286704178314,
					-0.6331143352089725
				],
				[
					1.5828099897862558,
					-0.6331143352089725
				],
				[
					1.899367157390543,
					0
				],
				[
					1.5828099897862558,
					1.8993792332725548
				],
				[
					0.9496715028133167,
					3.4821892230587252
				],
				[
					-0.6331384869727117,
					4.74842996935854
				],
				[
					-1.5828099897862558,
					4.431872801754054
				],
				[
					-2.2159484767589674,
					3.4821892230587252
				],
				[
					-1.8993913091544528,
					1.8993792332725548
				],
				[
					-1.266252822181741,
					0.31656924348635584
				],
				[
					-0.6331384869727117,
					-0.6331143352089725
				],
				[
					0,
					-0.9496835786953284
				],
				[
					0.3165571676045147,
					-0.6331143352089725
				],
				[
					0.3165571676045147,
					0.949695654577198
				],
				[
					0.3165571676045147,
					3.1656199795723694
				],
				[
					0.3165571676045147,
					6.0146827915402525
				],
				[
					0.6331143352090294,
					7.914049948930909
				],
				[
					0.9496715028133167,
					8.547176360021751
				],
				[
					1.2662286704178314,
					8.547176360021751
				],
				[
					1.2662286704178314,
					8.547176360021751
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0078125,
				0.2373046875,
				0.4326171875,
				0.51953125,
				0.6025390625,
				0.6171875,
				0.6142578125,
				0.5986328125,
				0.5634765625,
				0.5478515625,
				0.5341796875,
				0.5078125,
				0.5068359375,
				0.509765625,
				0.515625,
				0.517578125,
				0.5185546875,
				0.5185546875,
				0.453125,
				0.25390625,
				0.1474609375,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 195,
			"versionNonce": 1860625156,
			"isDeleted": false,
			"id": "SzV8XG7XxDe6MWsTyNld8",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1376.4645267415665,
			"y": 515.205397044176,
			"strokeColor": "#862e9c",
			"backgroundColor": "transparent",
			"width": 3.7987343147813135,
			"height": 8.230607116535396,
			"seed": 818618905,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.3165571676045147,
					0.31656924348635584
				],
				[
					0.9496956545772264,
					-0.31655716760448627
				],
				[
					1.5828099897862558,
					-0.9496835786953284
				],
				[
					2.215924324995285,
					-1.5828099897861705
				],
				[
					2.849062811967997,
					-1.8993671573906568
				],
				[
					3.1656199795725115,
					-1.5828099897861705
				],
				[
					3.1656199795725115,
					0
				],
				[
					2.849062811967997,
					1.8993792332725548
				],
				[
					2.849062811967997,
					4.431872801754054
				],
				[
					2.849062811967997,
					5.698113548053868
				],
				[
					2.849062811967997,
					6.331239959144739
				],
				[
					3.7987343147813135,
					5.381556380449382
				],
				[
					3.7987343147813135,
					5.381556380449382
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0,
				0.2275390625,
				0.408203125,
				0.4091796875,
				0.4150390625,
				0.421875,
				0.4375,
				0.4560546875,
				0.45703125,
				0.44140625,
				0.3681640625,
				0.2216796875,
				0.00390625,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 191,
			"versionNonce": 28294972,
			"isDeleted": false,
			"id": "MFyKO65WanFVUr_sOfGHV",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1384.6951338581018,
			"y": 514.2557134654807,
			"strokeColor": "#862e9c",
			"backgroundColor": "transparent",
			"width": 5.064987136963055,
			"height": 7.597492781326423,
			"seed": 2082231255,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					3.1656199795725115,
					2.2159364008770126
				],
				[
					3.1656199795725115,
					4.431872801754054
				],
				[
					-0.9496715028133167,
					7.597492781326423
				],
				[
					-1.899367157390543,
					6.0146827915402525
				],
				[
					-1.5828099897862558,
					3.7987463906632115
				],
				[
					-0.9496715028133167,
					2.849062811967883
				],
				[
					-0.6331143352090294,
					2.849062811967883
				],
				[
					0,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0078125,
				0.3232421875,
				0.3671875,
				0.3779296875,
				0.37890625,
				0.310546875,
				0.0908203125,
				0.0205078125,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 195,
			"versionNonce": 26993284,
			"isDeleted": false,
			"id": "QMyjFUSKD8NPXeQHkZsi3",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1377.0976410767755,
			"y": 531.6666233531287,
			"strokeColor": "#862e9c",
			"backgroundColor": "transparent",
			"width": 3.798758466544996,
			"height": 8.863733527626238,
			"seed": 1936779641,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.6331384869727117,
					-0.31655716760448627
				],
				[
					1.5828099897862558,
					-0.9496835786953284
				],
				[
					2.2159484767589674,
					-1.8993671573906568
				],
				[
					2.8490628119677694,
					-2.532493568481499
				],
				[
					3.482201298940481,
					-2.2159364008770126
				],
				[
					3.482201298940481,
					-1.2662528221816842
				],
				[
					3.165619979572284,
					1.2662528221817126
				],
				[
					2.8490628119677694,
					4.115303558267698
				],
				[
					2.532505644363482,
					5.698113548053897
				],
				[
					2.8490628119677694,
					6.331239959144739
				],
				[
					3.482201298940481,
					6.0146827915402525
				],
				[
					3.798758466544996,
					5.698113548053897
				],
				[
					3.798758466544996,
					5.698113548053897
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0,
				0.3623046875,
				0.4130859375,
				0.4150390625,
				0.41796875,
				0.4501953125,
				0.470703125,
				0.490234375,
				0.4970703125,
				0.4775390625,
				0.3271484375,
				0.0498046875,
				0.00390625,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 194,
			"versionNonce": 1617721276,
			"isDeleted": false,
			"id": "Dqofw8t7pKRSFKMJjqxlh",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1384.6951338581018,
			"y": 531.0334969420378,
			"strokeColor": "#862e9c",
			"backgroundColor": "transparent",
			"width": 3.482177147177026,
			"height": 9.180302771112594,
			"seed": 397141623,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.9496956545772264,
					0.31656924348635584
				],
				[
					1.8993671573907704,
					-0.31655716760448627
				],
				[
					2.2159484767589674,
					-0.6331264110908421
				],
				[
					2.849062811967997,
					-0.9496835786953284
				],
				[
					3.1656199795725115,
					-0.6331264110908421
				],
				[
					3.1656199795725115,
					0.6331264110908421
				],
				[
					2.849062811967997,
					2.5324935684815273
				],
				[
					2.532505644363482,
					5.698113548053868
				],
				[
					2.849062811967997,
					6.964366370235581
				],
				[
					3.1656199795725115,
					7.914049948930909
				],
				[
					3.482177147177026,
					8.230619192417265
				],
				[
					3.482177147177026,
					8.230619192417265
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0009765625,
				0.3857421875,
				0.421875,
				0.4208984375,
				0.423828125,
				0.435546875,
				0.443359375,
				0.443359375,
				0.4384765625,
				0.423828125,
				0.205078125,
				0.0498046875,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 196,
			"versionNonce": 75821572,
			"isDeleted": false,
			"id": "uwcBNACbDNiacLaOAdmMk",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1377.7307795637482,
			"y": 544.962229682509,
			"strokeColor": "#862e9c",
			"backgroundColor": "transparent",
			"width": 3.482177147176799,
			"height": 7.5974807054445535,
			"seed": 1763517015,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-0.31656924348638427
				],
				[
					0.3165571676045147,
					-0.31656924348638427
				],
				[
					0.9496715028135441,
					-0.9496835786953284
				],
				[
					1.5828099897862558,
					-1.8993792332725548
				],
				[
					2.2159243249950578,
					-2.5324935684815273
				],
				[
					2.5324814925995724,
					-2.215936400877041
				],
				[
					2.5324814925995724,
					-1.2662528221817126
				],
				[
					2.5324814925995724,
					0.31655716760448627
				],
				[
					2.5324814925995724,
					2.532493568481499
				],
				[
					2.5324814925995724,
					4.431860725872184
				],
				[
					2.5324814925995724,
					5.064987136963026
				],
				[
					2.8490628119677694,
					5.064987136963026
				],
				[
					3.482177147176799,
					4.74842996935854
				],
				[
					3.482177147176799,
					4.74842996935854
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0068359375,
				0.0478515625,
				0.4365234375,
				0.4638671875,
				0.466796875,
				0.4765625,
				0.498046875,
				0.53125,
				0.548828125,
				0.5576171875,
				0.5458984375,
				0.4609375,
				0.1044921875,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 194,
			"versionNonce": 670965820,
			"isDeleted": false,
			"id": "4VT7LwhkaqKM-JFv6Dy_U",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1383.7454623552885,
			"y": 544.3291032714181,
			"strokeColor": "#862e9c",
			"backgroundColor": "transparent",
			"width": 6.014658639776371,
			"height": 6.964366370235581,
			"seed": 27532119,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.5828099897860284,
					-0.6331264110908705
				],
				[
					2.5324814925995724,
					-0.31655716760448627
				],
				[
					2.5324814925995724,
					0.9496835786953284
				],
				[
					2.2159243249950578,
					2.8490628119678547
				],
				[
					1.899367157390543,
					4.431872801754054
				],
				[
					1.5828099897860284,
					5.381556380449382
				],
				[
					1.5828099897860284,
					6.014682791540224
				],
				[
					2.5324814925995724,
					6.33123995914471
				],
				[
					3.7987343147813135,
					6.014682791540224
				],
				[
					5.381544304567569,
					5.381556380449382
				],
				[
					6.014658639776371,
					5.381556380449382
				],
				[
					6.014658639776371,
					5.381556380449382
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0068359375,
				0.2451171875,
				0.302734375,
				0.3232421875,
				0.34765625,
				0.39453125,
				0.421875,
				0.466796875,
				0.48828125,
				0.44140625,
				0.259765625,
				0.05859375,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 194,
			"versionNonce": 1990201732,
			"isDeleted": false,
			"id": "125gT5x9I2LrV5tTvBI7D",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1378.0473367313527,
			"y": 556.6750260221031,
			"strokeColor": "#862e9c",
			"backgroundColor": "transparent",
			"width": 2.8490628119677694,
			"height": 7.5974807054445535,
			"seed": 657167159,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.6331143352090294,
					-0.6331264110908421
				],
				[
					1.266252822181741,
					-0.9496956545772264
				],
				[
					1.899367157390543,
					-1.2662528221817126
				],
				[
					2.2159243249950578,
					-1.582809989786199
				],
				[
					2.5325056443632548,
					-1.2662528221817126
				],
				[
					2.5325056443632548,
					0.31655716760448627
				],
				[
					1.899367157390543,
					2.849050736085985
				],
				[
					1.5828099897862558,
					4.74842996935854
				],
				[
					1.5828099897862558,
					6.0146707156583545
				],
				[
					2.5325056443632548,
					5.698113548053868
				],
				[
					2.8490628119677694,
					5.381544304567512
				],
				[
					2.8490628119677694,
					5.381544304567512
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0048828125,
				0.318359375,
				0.443359375,
				0.46484375,
				0.474609375,
				0.5009765625,
				0.541015625,
				0.541015625,
				0.5283203125,
				0.3896484375,
				0.05859375,
				0.0068359375,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 199,
			"versionNonce": 1346812092,
			"isDeleted": false,
			"id": "t1cnTEei_lFkUJR263zZ3",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1384.0620195228928,
			"y": 555.7253303675259,
			"strokeColor": "#862e9c",
			"backgroundColor": "transparent",
			"width": 4.115291482386056,
			"height": 7.280935613721937,
			"seed": 975349527,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.5828099897862558,
					0
				],
				[
					2.5324814925998,
					0
				],
				[
					2.849062811967997,
					0.6331264110908705
				],
				[
					2.5324814925998,
					1.582809989786199
				],
				[
					2.215924324995285,
					2.532505644363397
				],
				[
					1.8993671573907704,
					2.532505644363397
				],
				[
					2.215924324995285,
					2.849062811967883
				],
				[
					2.5324814925998,
					3.4821892230587252
				],
				[
					3.1656199795725115,
					4.115315634149596
				],
				[
					3.798734314781541,
					4.431872801754082
				],
				[
					4.115291482386056,
					4.748429969358568
				],
				[
					3.798734314781541,
					5.698125623935766
				],
				[
					2.849062811967997,
					6.647809202631095
				],
				[
					1.8993671573907704,
					7.280935613721937
				],
				[
					0.9496715028135441,
					6.964366370235581
				],
				[
					0.6331143352090294,
					6.964366370235581
				],
				[
					0.6331143352090294,
					6.964366370235581
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.001953125,
				0.3291015625,
				0.3837890625,
				0.3974609375,
				0.3994140625,
				0.3984375,
				0.3994140625,
				0.400390625,
				0.3974609375,
				0.39453125,
				0.392578125,
				0.39453125,
				0.392578125,
				0.373046875,
				0.2529296875,
				0.0537109375,
				0.005859375,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 195,
			"versionNonce": 1194017028,
			"isDeleted": false,
			"id": "c0fZb0PAyVZgsjhkRgZYh",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1376.4645267415665,
			"y": 570.9203038542969,
			"strokeColor": "#862e9c",
			"backgroundColor": "transparent",
			"width": 3.7987343147813135,
			"height": 6.647797126749225,
			"seed": 518032825,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-0.6331143352089725
				],
				[
					0.6331143352090294,
					-0.9496715028134588
				],
				[
					1.266252822181741,
					-1.5828099897861705
				],
				[
					2.215924324995285,
					-2.215924324995143
				],
				[
					2.849062811967997,
					-2.8490386602041156
				],
				[
					3.1656199795725115,
					-2.8490386602041156
				],
				[
					3.1656199795725115,
					-1.8993671573906568
				],
				[
					2.849062811967997,
					-0.31655716760448627
				],
				[
					2.532505644363482,
					1.8993913091544243
				],
				[
					2.215924324995285,
					3.4822012989406232
				],
				[
					2.532505644363482,
					3.7987584665451095
				],
				[
					3.7987343147813135,
					2.849062811967883
				],
				[
					3.7987343147813135,
					2.849062811967883
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0029296875,
				0.15234375,
				0.4736328125,
				0.4990234375,
				0.501953125,
				0.50390625,
				0.5087890625,
				0.5244140625,
				0.52734375,
				0.521484375,
				0.419921875,
				0.3544921875,
				0.001953125,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 192,
			"versionNonce": 82329916,
			"isDeleted": false,
			"id": "HSdBWSIs3T3Mvp_JvDx9K",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1385.0116910257063,
			"y": 567.7546838747245,
			"strokeColor": "#862e9c",
			"backgroundColor": "transparent",
			"width": 4.115315634149738,
			"height": 6.964378446117479,
			"seed": 873520695,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-0.6331143352090294,
					1.582809989786199
				],
				[
					-1.2662286704178314,
					3.1656199795723694
				],
				[
					-1.5828099897862558,
					4.748429969358568
				],
				[
					-1.2662286704178314,
					5.698125623935766
				],
				[
					-0.6331143352090294,
					6.964378446117479
				],
				[
					0.316581319368197,
					6.964378446117479
				],
				[
					1.5828099897862558,
					6.647821278512993
				],
				[
					2.532505644363482,
					5.698125623935766
				],
				[
					2.532505644363482,
					5.065011288726794
				],
				[
					2.532505644363482,
					5.065011288726794
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0078125,
				0.359375,
				0.451171875,
				0.494140625,
				0.5068359375,
				0.50390625,
				0.447265625,
				0.26171875,
				0.0341796875,
				0.0009765625,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 187,
			"versionNonce": 1302626436,
			"isDeleted": false,
			"id": "5YCPwe7V6VT7CK7uX3ISt",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1388.493892324647,
			"y": 568.3878223616972,
			"strokeColor": "#862e9c",
			"backgroundColor": "transparent",
			"width": 0.9496956545772264,
			"height": 8.547164284139882,
			"seed": 82348279,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-0.316581319368197,
					0.9496715028134588
				],
				[
					-0.6331384869727117,
					2.849062811967883
				],
				[
					-0.9496956545772264,
					8.230607116535396
				],
				[
					-0.316581319368197,
					8.547164284139882
				],
				[
					-0.316581319368197,
					8.547164284139882
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0,
				0.3037109375,
				0.39453125,
				0.1435546875,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 193,
			"versionNonce": 759478716,
			"isDeleted": false,
			"id": "1H8Yct1IVrknk_0xsrfjw",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1378.3638938989573,
			"y": 582.3165551021684,
			"strokeColor": "#862e9c",
			"backgroundColor": "transparent",
			"width": 4.431872801754025,
			"height": 7.597492781326423,
			"seed": 760978585,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					2.21594847675874,
					-1.8993913091544243
				],
				[
					2.8490628119677694,
					-2.2159484767589106
				],
				[
					3.482177147176799,
					-1.582809989786199
				],
				[
					3.482177147176799,
					-0.31658131936825384
				],
				[
					3.482177147176799,
					1.8993671573906568
				],
				[
					3.165619979572284,
					4.1152914823858
				],
				[
					3.165619979572284,
					5.064987136963026
				],
				[
					3.165619979572284,
					5.381544304567512
				],
				[
					3.798758466544996,
					5.064987136963026
				],
				[
					4.431872801754025,
					4.431848649990286
				],
				[
					4.431872801754025,
					4.431848649990286
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0048828125,
				0.43359375,
				0.4619140625,
				0.5400390625,
				0.572265625,
				0.58984375,
				0.59375,
				0.5625,
				0.5166015625,
				0.1279296875,
				0.01171875,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 197,
			"versionNonce": 1103745028,
			"isDeleted": false,
			"id": "1coS8d6sbm2ZZxGqArVfL",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1389.127006659856,
			"y": 579.784049457805,
			"strokeColor": "#862e9c",
			"backgroundColor": "transparent",
			"width": 4.115291482385828,
			"height": 6.647797126749197,
			"seed": 1458704439,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-0.6331143352090294,
					1.2662528221816842
				],
				[
					-1.5828099897862558,
					2.215924324995143
				],
				[
					-2.215924324995285,
					2.849062811967883
				],
				[
					-2.215924324995285,
					3.1656199795723694
				],
				[
					-1.8993671573907704,
					3.1656199795723694
				],
				[
					-1.266252822181741,
					3.1656199795723694
				],
				[
					-0.3165571676045147,
					3.4821771471768272
				],
				[
					0.3165571676042873,
					3.7987343147813135
				],
				[
					0.3165571676042873,
					4.431872801754054
				],
				[
					0,
					5.064987136963026
				],
				[
					-0.6331143352090294,
					5.698125623935738
				],
				[
					-1.8993671573907704,
					6.33123995914471
				],
				[
					-2.849062811967997,
					6.647797126749197
				],
				[
					-3.798734314781541,
					6.647797126749197
				],
				[
					-3.798734314781541,
					6.647797126749197
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.001953125,
				0.2578125,
				0.2763671875,
				0.2783203125,
				0.2822265625,
				0.2822265625,
				0.28125,
				0.2822265625,
				0.2822265625,
				0.2861328125,
				0.2998046875,
				0.30078125,
				0.259765625,
				0.1689453125,
				0.009765625,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 195,
			"versionNonce": 1954423356,
			"isDeleted": false,
			"id": "Dn2Q2qn9mTdIMqfxjzI9N",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1377.4142223961437,
			"y": 598.1446550000302,
			"strokeColor": "#862e9c",
			"backgroundColor": "transparent",
			"width": 4.431848649990343,
			"height": 8.863745603508107,
			"seed": 98986425,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.2662286704180588,
					-0.6331384869727401
				],
				[
					2.215924324995285,
					-1.582809989786199
				],
				[
					2.849038660204087,
					-2.2159484767589106
				],
				[
					3.482177147176799,
					-2.532505644363397
				],
				[
					3.7987343147813135,
					-2.2159484767589106
				],
				[
					3.7987343147813135,
					-1.582809989786199
				],
				[
					3.482177147176799,
					0.31655716760448627
				],
				[
					3.165619979572284,
					2.8490386602041156
				],
				[
					2.849038660204087,
					4.74842996935854
				],
				[
					2.849038660204087,
					6.33123995914471
				],
				[
					3.482177147176799,
					6.33123995914471
				],
				[
					4.431848649990343,
					6.014658639776485
				],
				[
					4.431848649990343,
					6.014658639776485
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0,
				0.4013671875,
				0.51171875,
				0.5185546875,
				0.517578125,
				0.529296875,
				0.5458984375,
				0.572265625,
				0.5810546875,
				0.580078125,
				0.484375,
				0.22265625,
				0.0048828125,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 200,
			"versionNonce": 865677188,
			"isDeleted": false,
			"id": "2UeWZlkmvp8A0uhSrw0tg",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1389.7601209950649,
			"y": 594.6624537010896,
			"strokeColor": "#862e9c",
			"backgroundColor": "transparent",
			"width": 4.74842996935854,
			"height": 10.763112760898792,
			"seed": 2016363063,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-0.3165571676045147,
					0.6331384869727401
				],
				[
					-0.9496715028133167,
					1.8993913091544243
				],
				[
					-1.899367157390543,
					4.115315634149596
				],
				[
					-2.849038660204087,
					6.331239959144739
				],
				[
					-2.849038660204087,
					8.230631268299163
				],
				[
					-2.5324814925995724,
					9.813441258085334
				],
				[
					-1.5828099897860284,
					10.446555593294306
				],
				[
					0,
					10.763112760898792
				],
				[
					1.266252822181741,
					9.813441258085334
				],
				[
					1.8993913091544528,
					8.863745603508136
				],
				[
					1.8993913091544528,
					8.230631268299163
				],
				[
					1.266252822181741,
					7.597492781326423
				],
				[
					0,
					7.914049948930909
				],
				[
					-1.2662286704178314,
					8.230631268299163
				],
				[
					-1.5828099897860284,
					8.230631268299163
				],
				[
					-1.899367157390543,
					7.914049948930909
				],
				[
					-1.5828099897860284,
					7.597492781326423
				],
				[
					-1.5828099897860284,
					7.597492781326423
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.005859375,
				0.416015625,
				0.4853515625,
				0.4931640625,
				0.49609375,
				0.494140625,
				0.466796875,
				0.427734375,
				0.408203125,
				0.400390625,
				0.392578125,
				0.388671875,
				0.3974609375,
				0.416015625,
				0.4287109375,
				0.427734375,
				0.3037109375,
				0.009765625,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 200,
			"versionNonce": 1366719164,
			"isDeleted": false,
			"id": "jvmX34al4gtHMeEgxcIL_",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1384.0620678264206,
			"y": 776.6856266782642,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 4.74842996935854,
			"height": 12.345922750684991,
			"seed": 1387228057,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.9496715028133167,
					2.8490386602041156
				],
				[
					-0.316581319368197,
					4.4318486499903145
				],
				[
					-1.5828099897862558,
					5.064987136963026
				],
				[
					-2.532505644363482,
					4.4318486499903145
				],
				[
					-2.532505644363482,
					2.5324814925996293
				],
				[
					-2.2159484767589674,
					0.9496715028134588
				],
				[
					-1.266252822181741,
					-0.31658131936825384
				],
				[
					-0.6331384869727117,
					-0.6331384869727401
				],
				[
					0.3165571676045147,
					-0.6331384869727401
				],
				[
					0.6331143352090294,
					0.6331143352089725
				],
				[
					0.9496715028133167,
					2.5324814925996293
				],
				[
					0.9496715028133167,
					5.381544304567512
				],
				[
					0.9496715028133167,
					8.230607116535396
				],
				[
					0.9496715028133167,
					9.813417106321566
				],
				[
					1.5828099897860284,
					10.446531441530539
				],
				[
					2.2159243249950578,
					11.396227096107765
				],
				[
					2.2159243249950578,
					11.712784263712251
				],
				[
					2.2159243249950578,
					11.712784263712251
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0048828125,
				0.4501953125,
				0.4599609375,
				0.458984375,
				0.439453125,
				0.392578125,
				0.365234375,
				0.36328125,
				0.365234375,
				0.369140625,
				0.3837890625,
				0.4130859375,
				0.431640625,
				0.43359375,
				0.4130859375,
				0.2314453125,
				0.01171875,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 193,
			"versionNonce": 55615236,
			"isDeleted": false,
			"id": "DfOT-m8J12J_irp31XAYe",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1378.6804993700891,
			"y": 796.6290180585116,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 3.798758466545223,
			"height": 8.863745603508136,
			"seed": 1106800729,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.266252822181741,
					0
				],
				[
					2.532505644363482,
					-0.9496715028134588
				],
				[
					3.1656199795725115,
					-1.582809989786199
				],
				[
					3.798758466545223,
					-0.9496715028134588
				],
				[
					3.798758466545223,
					0.6331384869727117
				],
				[
					3.482177147177026,
					3.4821771471768557
				],
				[
					3.1656199795725115,
					6.014682791540224
				],
				[
					3.1656199795725115,
					6.9643784461174505
				],
				[
					3.482177147177026,
					7.280935613721937
				],
				[
					3.798758466545223,
					7.280935613721937
				],
				[
					3.798758466545223,
					7.280935613721937
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.005859375,
				0.34375,
				0.3818359375,
				0.3857421875,
				0.3935546875,
				0.400390625,
				0.40625,
				0.3896484375,
				0.2705078125,
				0.080078125,
				0.00390625,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 191,
			"versionNonce": 248496956,
			"isDeleted": false,
			"id": "EYhzzsHcGgvYs4fTkn_-J",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1386.5945493190202,
			"y": 797.8952708806934,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 3.798758466544996,
			"height": 6.647797126749225,
			"seed": 92940407,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					2.2159484767589674,
					2.2159243249951714
				],
				[
					2.5325056443632548,
					4.74842996935854
				],
				[
					0,
					6.647797126749225
				],
				[
					-0.9496715028135441,
					5.064987136963026
				],
				[
					-1.266252822181741,
					3.4821771471768557
				],
				[
					-0.9496715028135441,
					2.532505644363397
				],
				[
					-0.9496715028135441,
					2.2159243249951714
				],
				[
					0,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.00390625,
				0.283203125,
				0.3134765625,
				0.3115234375,
				0.3125,
				0.240234375,
				0.068359375,
				0.0009765625,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 194,
			"versionNonce": 1500388996,
			"isDeleted": false,
			"id": "ISaJ5tIjPdGm4izR3pzCj",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1378.3639422024848,
			"y": 813.0902564433462,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 4.74842996935854,
			"height": 8.54718843590365,
			"seed": 1759040217,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.9496956545772264,
					0
				],
				[
					1.899367157390543,
					-0.31658131936825384
				],
				[
					3.165619979572284,
					-1.266252822181741
				],
				[
					3.7987343147813135,
					-1.8993913091544528
				],
				[
					4.431872801754025,
					-1.8993913091544528
				],
				[
					4.74842996935854,
					-0.6331384869727685
				],
				[
					4.431872801754025,
					1.266228670417945
				],
				[
					3.7987343147813135,
					4.115291482385828
				],
				[
					3.482177147176799,
					6.014658639776485
				],
				[
					3.7987343147813135,
					6.647797126749197
				],
				[
					4.431872801754025,
					6.014658639776485
				],
				[
					4.431872801754025,
					6.014658639776485
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0,
				0.359375,
				0.4306640625,
				0.4375,
				0.4384765625,
				0.44140625,
				0.4462890625,
				0.451171875,
				0.453125,
				0.408203125,
				0.20703125,
				0.005859375,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 193,
			"versionNonce": 1391197116,
			"isDeleted": false,
			"id": "jZy20Mru2ydC492EbQfEI",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1387.227687805993,
			"y": 813.0902564433462,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 3.482177147176799,
			"height": 9.180278619348826,
			"seed": 973353209,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.899367157390543,
					-0.6331384869727685
				],
				[
					2.849038660204087,
					-1.266252822181741
				],
				[
					3.165619979572284,
					-1.582809989786199
				],
				[
					3.165619979572284,
					-0.6331384869727685
				],
				[
					3.165619979572284,
					0.6331143352089725
				],
				[
					2.849038660204087,
					2.849038660204087
				],
				[
					2.5324814925995724,
					5.381544304567512
				],
				[
					2.849038660204087,
					7.280911461958169
				],
				[
					3.482177147176799,
					7.597468629562627
				],
				[
					3.482177147176799,
					7.280911461958169
				],
				[
					3.482177147176799,
					7.280911461958169
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0068359375,
				0.2578125,
				0.2646484375,
				0.2666015625,
				0.2919921875,
				0.3095703125,
				0.31640625,
				0.3134765625,
				0.2294921875,
				0.044921875,
				0.00390625,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 192,
			"versionNonce": 514829828,
			"isDeleted": false,
			"id": "JB1dfDV_KJfFJA8l-LOLo",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1378.9970565376937,
			"y": 825.7527363616356,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 4.115315634149738,
			"height": 7.597492781326423,
			"seed": 977648087,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.8993913091544528,
					-1.2662528221816842
				],
				[
					2.849062811967997,
					-1.899391309154396
				],
				[
					3.1656199795725115,
					-1.582809989786142
				],
				[
					3.1656199795725115,
					0
				],
				[
					3.4822012989407085,
					2.2159243249951714
				],
				[
					3.1656199795725115,
					4.115291482385828
				],
				[
					3.4822012989407085,
					5.381544304567512
				],
				[
					3.4822012989407085,
					5.698101472172027
				],
				[
					4.115315634149738,
					5.381544304567512
				],
				[
					4.115315634149738,
					5.381544304567512
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0087890625,
				0.24609375,
				0.263671875,
				0.283203125,
				0.3359375,
				0.375,
				0.3828125,
				0.3623046875,
				0.291015625,
				0.0322265625,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 194,
			"versionNonce": 669852732,
			"isDeleted": false,
			"id": "sk85lY0oyffYB7h42tieC",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1385.3282964968384,
			"y": 825.7527363616356,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 6.647821278512993,
			"height": 6.331239959144739,
			"seed": 216804503,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.266252822181741,
					0.3165571676045147
				],
				[
					2.532505644363482,
					0.3165571676045147
				],
				[
					3.165619979572284,
					0.9496715028134872
				],
				[
					3.4822012989407085,
					2.2159243249951714
				],
				[
					3.165619979572284,
					3.7987343147813704
				],
				[
					2.532505644363482,
					5.381544304567512
				],
				[
					2.532505644363482,
					6.014658639776485
				],
				[
					2.849062811967997,
					6.331239959144739
				],
				[
					4.1153156341495105,
					5.698101472172027
				],
				[
					5.698125623935766,
					5.381544304567512
				],
				[
					6.647821278512993,
					5.381544304567512
				],
				[
					6.647821278512993,
					5.381544304567512
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0078125,
				0.2666015625,
				0.2900390625,
				0.2939453125,
				0.2998046875,
				0.326171875,
				0.349609375,
				0.375,
				0.38671875,
				0.3857421875,
				0.279296875,
				0.07421875,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 195,
			"versionNonce": 1947422084,
			"isDeleted": false,
			"id": "datkWvW4HZJW4xR4e-iXy",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1379.313637857062,
			"y": 837.1489634577434,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 3.798758466545223,
			"height": 8.230631268299135,
			"seed": 1353682039,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-0.3165813193684244,
					-0.3165571676045147
				],
				[
					0.3165571676042873,
					-0.6331384869727685
				],
				[
					1.2662286704178314,
					-1.582809989786199
				],
				[
					2.2159243249950578,
					-2.2159484767589106
				],
				[
					2.849038660204087,
					-1.8993671573906568
				],
				[
					3.165619979572284,
					-0.9496956545772264
				],
				[
					3.165619979572284,
					0.9496715028134304
				],
				[
					2.849038660204087,
					3.4821771471768557
				],
				[
					2.849038660204087,
					5.381544304567512
				],
				[
					2.849038660204087,
					6.014682791540224
				],
				[
					3.165619979572284,
					5.69810147217197
				],
				[
					3.482177147176799,
					5.69810147217197
				],
				[
					3.482177147176799,
					5.69810147217197
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0009765625,
				0.33203125,
				0.4814453125,
				0.515625,
				0.5224609375,
				0.55078125,
				0.56640625,
				0.5673828125,
				0.564453125,
				0.494140625,
				0.3681640625,
				0.0361328125,
				0.0126953125,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 197,
			"versionNonce": 62209212,
			"isDeleted": false,
			"id": "OIKVaMrUWG9DakK8eHZSs",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1385.9614349838112,
			"y": 835.8827106355617,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 4.115291482385828,
			"height": 6.9643542943536545,
			"seed": 830803097,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.5828099897862558,
					0
				],
				[
					1.8993671573907704,
					0.6331143352089157
				],
				[
					1.5828099897862558,
					2.5325056443633684
				],
				[
					1.266252822181741,
					3.165619979572341
				],
				[
					1.266252822181741,
					2.8490628119678263
				],
				[
					2.215924324995285,
					3.165619979572341
				],
				[
					3.165619979572284,
					3.165619979572341
				],
				[
					3.7987343147813135,
					3.7987343147813135
				],
				[
					4.115291482385828,
					4.74842996935854
				],
				[
					3.482177147176799,
					5.698125623935709
				],
				[
					2.5324814925995724,
					6.9643542943536545
				],
				[
					1.266252822181741,
					6.9643542943536545
				],
				[
					0.6331143352090294,
					6.331239959144682
				],
				[
					0.3165571676045147,
					5.698125623935709
				],
				[
					0.3165571676045147,
					5.698125623935709
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0048828125,
				0.2607421875,
				0.314453125,
				0.3193359375,
				0.3154296875,
				0.3134765625,
				0.30078125,
				0.2978515625,
				0.298828125,
				0.3017578125,
				0.306640625,
				0.306640625,
				0.2998046875,
				0.18359375,
				0.009765625,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 193,
			"versionNonce": 718732548,
			"isDeleted": false,
			"id": "8c0ha4chZ5PwRUQqgAH3W",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1376.464575045094,
			"y": 851.0776961982141,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 3.7987343147813135,
			"height": 6.6477971267492535,
			"seed": 692862583,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.266252822181741,
					-0.6331384869727685
				],
				[
					2.2159243249950578,
					-0.6331384869727685
				],
				[
					2.849062811967997,
					-0.6331384869727685
				],
				[
					3.165619979572284,
					-0.31658131936825384
				],
				[
					3.165619979572284,
					1.582809989786142
				],
				[
					2.849062811967997,
					3.7987343147813135
				],
				[
					2.5324814925995724,
					5.381544304567512
				],
				[
					2.5324814925995724,
					6.014658639776485
				],
				[
					3.165619979572284,
					5.381544304567512
				],
				[
					3.7987343147813135,
					4.431848649990286
				],
				[
					3.7987343147813135,
					4.431848649990286
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.001953125,
				0.2421875,
				0.3271484375,
				0.3408203125,
				0.369140625,
				0.41796875,
				0.4267578125,
				0.41796875,
				0.314453125,
				0.056640625,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 194,
			"versionNonce": 1340491068,
			"isDeleted": false,
			"id": "y7rPLEqiqRAiHRoi-7kEt",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1385.9614349838112,
			"y": 847.5954948992738,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 3.4822012989407085,
			"height": 5.381568456331308,
			"seed": 712109111,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					0.31658131936825384
				],
				[
					0,
					0.6331384869727685
				],
				[
					-0.3165571676045147,
					0.9496956545772264
				],
				[
					-0.3165571676045147,
					2.2159484767589106
				],
				[
					-0.6331384869727117,
					3.165619979572398
				],
				[
					-0.6331384869727117,
					4.431872801754082
				],
				[
					-0.3165571676045147,
					5.065011288726794
				],
				[
					0.3165571676045147,
					5.381568456331308
				],
				[
					0.9496715028135441,
					5.381568456331308
				],
				[
					1.8993671573907704,
					4.74842996935854
				],
				[
					2.5324814925995724,
					3.7987584665451095
				],
				[
					2.849062811967997,
					3.4822012989406517
				],
				[
					2.849062811967997,
					3.4822012989406517
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0009765625,
				0.3525390625,
				0.462890625,
				0.4990234375,
				0.5322265625,
				0.541015625,
				0.541015625,
				0.537109375,
				0.4833984375,
				0.3994140625,
				0.2373046875,
				0.0712890625,
				0.021484375,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 188,
			"versionNonce": 1014545540,
			"isDeleted": false,
			"id": "J_jX-6GO0Qmym3V_fu5qR",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1389.1270549633834,
			"y": 848.5451905538511,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 0.3165571676045147,
			"height": 6.964354294353711,
			"seed": 1557909721,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					0.9496956545772264
				],
				[
					0,
					2.2159243249951714
				],
				[
					0,
					3.4821771471768557
				],
				[
					0,
					4.74842996935854
				],
				[
					0,
					6.014682791540224
				],
				[
					0.3165571676045147,
					6.964354294353711
				],
				[
					0.3165571676045147,
					6.964354294353711
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0068359375,
				0.23046875,
				0.3447265625,
				0.3583984375,
				0.3505859375,
				0.2177734375,
				0.0166015625,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 195,
			"versionNonce": 1910652348,
			"isDeleted": false,
			"id": "01A3--Ux9fLsr-ZI9cacQ",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1379.6301950246664,
			"y": 860.257974817563,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 1.8993671573907704,
			"height": 6.9643784461174505,
			"seed": 925708727,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.3165571676045147,
					0
				],
				[
					0.6331143352090294,
					0
				],
				[
					0.9496715028135441,
					0
				],
				[
					1.5828099897862558,
					0
				],
				[
					1.8993671573907704,
					0.31658131936825384
				],
				[
					1.8993671573907704,
					0.9496956545772264
				],
				[
					1.5828099897862558,
					2.5325056443633684
				],
				[
					1.266252822181741,
					4.115315634149567
				],
				[
					0.6331143352090294,
					5.698125623935766
				],
				[
					0.6331143352090294,
					6.331239959144739
				],
				[
					0.6331143352090294,
					6.9643784461174505
				],
				[
					0.9496715028135441,
					6.9643784461174505
				],
				[
					1.8993671573907704,
					6.331239959144739
				],
				[
					1.8993671573907704,
					6.331239959144739
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.00390625,
				0.298828125,
				0.3916015625,
				0.412109375,
				0.4296875,
				0.435546875,
				0.4404296875,
				0.44140625,
				0.4404296875,
				0.4384765625,
				0.423828125,
				0.306640625,
				0.1767578125,
				0.0078125,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 198,
			"versionNonce": 1119259652,
			"isDeleted": false,
			"id": "SXsVp4L002No0uAGMNA4a",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1386.5945493190202,
			"y": 861.5242276397447,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 3.482177147176799,
			"height": 4.115315634149567,
			"seed": 489081527,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.3165571676045147,
					-0.31655716760445785
				],
				[
					0,
					0
				],
				[
					-0.6331143352090294,
					0.3165571676045147
				],
				[
					-0.9496715028135441,
					0.6331384869727685
				],
				[
					-0.9496715028135441,
					0.9496956545772264
				],
				[
					-0.6331143352090294,
					0.9496956545772264
				],
				[
					-0.6331143352090294,
					1.2662528221816842
				],
				[
					-0.3165571676045147,
					1.582809989786199
				],
				[
					0,
					1.8993671573906568
				],
				[
					0,
					2.2159484767589106
				],
				[
					0,
					2.849062811967883
				],
				[
					-0.9496715028135441,
					3.165619979572398
				],
				[
					-1.5828099897862558,
					3.4821771471768557
				],
				[
					-2.2159243249950578,
					3.7987584665451095
				],
				[
					-3.165619979572284,
					3.7987584665451095
				],
				[
					-3.165619979572284,
					3.165619979572398
				],
				[
					-3.165619979572284,
					3.165619979572398
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0009765625,
				0.0458984375,
				0.2041015625,
				0.2333984375,
				0.2431640625,
				0.2666015625,
				0.306640625,
				0.3076171875,
				0.310546875,
				0.3115234375,
				0.3115234375,
				0.3125,
				0.3134765625,
				0.314453125,
				0.30859375,
				0.1865234375,
				0.0029296875,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 193,
			"versionNonce": 1389045308,
			"isDeleted": false,
			"id": "Z455oyIsaYREvPnAZW8lK",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1378.3639422024848,
			"y": 874.5032647256388,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 2.8490628119677694,
			"height": 7.280935613721908,
			"seed": 336971801,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.2662528221815137,
					-0.9496715028134304
				],
				[
					2.2159243249950578,
					-1.582809989786142
				],
				[
					2.5325056443632548,
					-1.582809989786142
				],
				[
					2.8490628119677694,
					-1.266228670417945
				],
				[
					2.5325056443632548,
					0
				],
				[
					2.2159243249950578,
					1.582809989786199
				],
				[
					1.899367157390543,
					3.165619979572398
				],
				[
					1.5828099897860284,
					4.431872801754082
				],
				[
					1.2662528221815137,
					5.381568456331308
				],
				[
					1.899367157390543,
					5.698125623935766
				],
				[
					2.2159243249950578,
					5.381568456331308
				],
				[
					2.2159243249950578,
					5.381568456331308
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0029296875,
				0.2685546875,
				0.302734375,
				0.3046875,
				0.318359375,
				0.349609375,
				0.37109375,
				0.373046875,
				0.3564453125,
				0.24609375,
				0.064453125,
				0.0126953125,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 198,
			"versionNonce": 1871604612,
			"isDeleted": false,
			"id": "eNLVVD50PRnvt4oxWwTAX",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1387.5442449735974,
			"y": 871.6542260654345,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 4.431872801753798,
			"height": 8.547164284139853,
			"seed": 1453690425,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-0.9496956545772264,
					2.2159243249951146
				],
				[
					-1.5828099897862558,
					3.4821771471768557
				],
				[
					-2.532505644363482,
					5.064987136962998
				],
				[
					-2.8490628119677694,
					6.647797126749197
				],
				[
					-2.8490628119677694,
					7.597468629562627
				],
				[
					-1.8993671573907704,
					8.547164284139853
				],
				[
					-0.9496956545772264,
					8.547164284139853
				],
				[
					0,
					7.914049948930881
				],
				[
					1.266252822181741,
					6.647797126749197
				],
				[
					1.5828099897860284,
					6.331239959144739
				],
				[
					1.5828099897860284,
					6.014658639776485
				],
				[
					0.6331143352090294,
					5.69810147217197
				],
				[
					0,
					6.014658639776485
				],
				[
					-1.266252822181741,
					6.014658639776485
				],
				[
					-1.5828099897862558,
					6.014658639776485
				],
				[
					-1.5828099897862558,
					5.69810147217197
				],
				[
					-1.5828099897862558,
					5.69810147217197
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.009765625,
				0.314453125,
				0.341796875,
				0.3447265625,
				0.3427734375,
				0.337890625,
				0.322265625,
				0.3173828125,
				0.31640625,
				0.31640625,
				0.31640625,
				0.3154296875,
				0.32421875,
				0.3291015625,
				0.3271484375,
				0.3046875,
				0.0361328125,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 197,
			"versionNonce": 1736638140,
			"isDeleted": false,
			"id": "2khVdwu_fmIxHgi8XDFDl",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1444.2087991347682,
			"y": 367.370947620911,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 2.849062811967997,
			"height": 7.914049948930938,
			"seed": 160530487,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-0.3165571676042873,
					0.31656320554543527
				],
				[
					-0.633114335208802,
					0.31656320554543527
				],
				[
					-0.9496956545772264,
					0.31656320554543527
				],
				[
					-0.9496956545772264,
					0.6331264110908705
				],
				[
					-0.633114335208802,
					0.6331264110908705
				],
				[
					-0.633114335208802,
					0.31656320554543527
				],
				[
					0,
					0.31656320554543527
				],
				[
					0.6331143352090294,
					-0.31655716760445785
				],
				[
					1.266252822181741,
					-0.9496835786953284
				],
				[
					1.5828099897862558,
					-0.9496835786953284
				],
				[
					1.8993671573907704,
					-0.31655716760445785
				],
				[
					1.8993671573907704,
					0.9496896166363058
				],
				[
					1.5828099897862558,
					3.165619979572398
				],
				[
					1.5828099897862558,
					4.748429969358597
				],
				[
					1.5828099897862558,
					6.014682791540224
				],
				[
					1.266252822181741,
					6.647803164690174
				],
				[
					1.5828099897862558,
					6.964366370235609
				],
				[
					1.8993671573907704,
					6.647803164690174
				],
				[
					1.8993671573907704,
					6.647803164690174
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0,
				0.03515625,
				0.052734375,
				0.1611328125,
				0.2119140625,
				0.466796875,
				0.474609375,
				0.474609375,
				0.4736328125,
				0.4755859375,
				0.4775390625,
				0.48046875,
				0.48046875,
				0.48046875,
				0.478515625,
				0.47265625,
				0.4033203125,
				0.16015625,
				0.0283203125,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 198,
			"versionNonce": 87972612,
			"isDeleted": false,
			"id": "HqMriHfbFCAW6KPL_0QGR",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1443.259103480191,
			"y": 402.19277343414797,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 4.748429969358767,
			"height": 7.280923537840067,
			"seed": 154902393,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-0.31656924348635584
				],
				[
					0.3165813193684244,
					-0.6331264110908137
				],
				[
					0.6331384869729391,
					-1.2662528221816842
				],
				[
					1.266252822181741,
					-1.582809989786199
				],
				[
					2.2159484767589674,
					-1.582809989786199
				],
				[
					2.849062811967997,
					-1.582809989786199
				],
				[
					3.1656199795725115,
					-0.9496835786953284
				],
				[
					2.849062811967997,
					0.31655716760445785
				],
				[
					2.532505644363482,
					1.582809989786199
				],
				[
					1.8993913091544528,
					2.849050736085985
				],
				[
					1.266252822181741,
					4.115303558267726
				],
				[
					0.9496956545772264,
					4.74842996935854
				],
				[
					0.9496956545772264,
					5.38155638044941
				],
				[
					1.266252822181741,
					5.698113548053868
				],
				[
					1.8993913091544528,
					5.698113548053868
				],
				[
					2.849062811967997,
					5.38155638044941
				],
				[
					3.4822012989407085,
					5.064987136962998
				],
				[
					4.115315634149738,
					4.74842996935854
				],
				[
					4.431872801754253,
					4.74842996935854
				],
				[
					4.748429969358767,
					5.064987136962998
				],
				[
					4.748429969358767,
					5.064987136962998
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0,
				0.306640625,
				0.3408203125,
				0.357421875,
				0.3876953125,
				0.41796875,
				0.44140625,
				0.4541015625,
				0.4599609375,
				0.4599609375,
				0.4560546875,
				0.458984375,
				0.462890625,
				0.4833984375,
				0.5048828125,
				0.5087890625,
				0.5068359375,
				0.4921875,
				0.416015625,
				0.1650390625,
				0.005859375,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 196,
			"versionNonce": 950781756,
			"isDeleted": false,
			"id": "zghbjmwtA0TvMdiE3uHwo",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1442.9425463125867,
			"y": 430.9999104179037,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 4.115291482385828,
			"height": 7.280923537840067,
			"seed": 1398234359,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.9496956545772264,
					-0.9496835786953284
				],
				[
					1.5828099897860284,
					-0.9496835786953284
				],
				[
					2.21594847675874,
					-0.9496835786953284
				],
				[
					2.5325056443632548,
					-0.31655716760445785
				],
				[
					2.5325056443632548,
					0.3165692434864127
				],
				[
					2.5325056443632548,
					1.582809989786199
				],
				[
					2.21594847675874,
					2.5324935684815273
				],
				[
					1.899367157390543,
					3.165619979572341
				],
				[
					2.21594847675874,
					3.165619979572341
				],
				[
					2.8490628119677694,
					3.165619979572341
				],
				[
					3.165619979572284,
					3.165619979572341
				],
				[
					3.482177147176799,
					3.7987463906632115
				],
				[
					3.482177147176799,
					4.115303558267726
				],
				[
					2.5325056443632548,
					5.064999212844953
				],
				[
					1.899367157390543,
					6.014682791540224
				],
				[
					0.9496956545772264,
					6.331239959144739
				],
				[
					0,
					6.331239959144739
				],
				[
					-0.6331143352090294,
					6.014682791540224
				],
				[
					-0.6331143352090294,
					6.014682791540224
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0048828125,
				0.2880859375,
				0.328125,
				0.34765625,
				0.3564453125,
				0.3623046875,
				0.3662109375,
				0.3662109375,
				0.3671875,
				0.365234375,
				0.3662109375,
				0.3662109375,
				0.3740234375,
				0.380859375,
				0.3828125,
				0.3828125,
				0.3828125,
				0.3798828125,
				0.3291015625,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 190,
			"versionNonce": 1313102468,
			"isDeleted": false,
			"id": "-eKEuzQ2VQ1LCRoBmQbE5",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1444.2087991347682,
			"y": 464.2389202034136,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 4.1153156341495105,
			"height": 6.964366370235609,
			"seed": 559996601,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-0.3165571676045147
				],
				[
					0,
					0
				],
				[
					-0.633114335208802,
					0.9496835786953284
				],
				[
					-1.2662528221815137,
					2.2159364008770126
				],
				[
					-1.2662528221815137,
					3.7987463906632115
				],
				[
					-1.2662528221815137,
					5.064999212844896
				],
				[
					-0.9496956545772264,
					5.698113548053868
				],
				[
					-0.3165571676042873,
					6.331239959144739
				],
				[
					0.6331143352090294,
					6.647809202631095
				],
				[
					1.5828099897862558,
					6.647809202631095
				],
				[
					2.532505644363482,
					6.647809202631095
				],
				[
					2.849062811967997,
					6.331239959144739
				],
				[
					2.849062811967997,
					6.331239959144739
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0,
				0.2958984375,
				0.47265625,
				0.5556640625,
				0.576171875,
				0.5849609375,
				0.5859375,
				0.583984375,
				0.5693359375,
				0.4873046875,
				0.2841796875,
				0.0595703125,
				0.009765625,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 183,
			"versionNonce": 1789362108,
			"isDeleted": false,
			"id": "LjHfQGnfXVsHGL9gI8O6g",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1448.0075334495498,
			"y": 465.82173019319976,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 0.9496715028135441,
			"height": 8.547176360021808,
			"seed": 451345719,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-0.3165571676045147,
					1.8993792332726116
				],
				[
					-0.6331143352090294,
					3.7987463906632684
				],
				[
					-0.9496715028135441,
					5.698113548053925
				],
				[
					-0.9496715028135441,
					8.230619192417294
				],
				[
					-0.6331143352090294,
					8.547176360021808
				],
				[
					-0.6331143352090294,
					8.547176360021808
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0009765625,
				0.2724609375,
				0.349609375,
				0.3583984375,
				0.046875,
				0.00390625,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 200,
			"versionNonce": 358509060,
			"isDeleted": false,
			"id": "0Q7pCo-41Iod72TmA7U2w",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1449.2737862717315,
			"y": 496.21167716674165,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 5.381544304567569,
			"height": 7.280935613721937,
			"seed": 456075703,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.3165571676042873,
					-1.266228670417945
				],
				[
					0.3165571676042873,
					-1.5828099897861705
				],
				[
					0,
					-1.5828099897861705
				],
				[
					-0.3165571676045147,
					-1.266228670417945
				],
				[
					-0.9496715028135441,
					-0.9496715028134588
				],
				[
					-1.5828099897862558,
					-0.31655716760448627
				],
				[
					-1.5828099897862558,
					0
				],
				[
					-1.8993671573907704,
					0.31658131936825384
				],
				[
					-1.5828099897862558,
					0.9496956545772264
				],
				[
					-1.266252822181741,
					1.2662528221816842
				],
				[
					-0.6331143352090294,
					1.5828099897861705
				],
				[
					0,
					1.8993913091544243
				],
				[
					0.6331384869727117,
					2.2159484767589106
				],
				[
					1.2662528221815137,
					2.532505644363397
				],
				[
					1.5828099897860284,
					3.1656199795723694
				],
				[
					1.5828099897860284,
					3.482201298940595
				],
				[
					0.949695654576999,
					4.115315634149567
				],
				[
					0.3165571676042873,
					4.74842996935854
				],
				[
					-0.9496715028135441,
					5.065011288726794
				],
				[
					-2.215924324995285,
					5.38156845633128
				],
				[
					-3.482177147177026,
					5.698125623935766
				],
				[
					-3.798734314781541,
					5.698125623935766
				],
				[
					-3.798734314781541,
					5.698125623935766
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0,
				0.154296875,
				0.2783203125,
				0.451171875,
				0.5400390625,
				0.5654296875,
				0.568359375,
				0.568359375,
				0.5693359375,
				0.5703125,
				0.5703125,
				0.5673828125,
				0.5615234375,
				0.5615234375,
				0.560546875,
				0.5625,
				0.5625,
				0.560546875,
				0.55859375,
				0.5576171875,
				0.4990234375,
				0.2255859375,
				0.0966796875,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 200,
			"versionNonce": 1167599676,
			"isDeleted": false,
			"id": "nfaav4ESA7CMTIwVuTQQt",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1447.3744191143408,
			"y": 524.069142647684,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 4.74842996935854,
			"height": 9.813417106321594,
			"seed": 876397497,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-0.6331143352090294,
					0.31655716760448627
				],
				[
					-1.266252822181741,
					0.9496956545772264
				],
				[
					-2.215924324995285,
					2.2159243249951714
				],
				[
					-2.849062811967997,
					3.4821771471768557
				],
				[
					-3.482177147176799,
					5.381544304567541
				],
				[
					-3.7987343147813135,
					7.280935613721965
				],
				[
					-3.482177147176799,
					8.547164284139882
				],
				[
					-2.849062811967997,
					9.49685993871708
				],
				[
					-1.8993671573907704,
					9.813417106321594
				],
				[
					-0.6331143352090294,
					9.49685993871708
				],
				[
					0.3165571676045147,
					8.863745603508136
				],
				[
					0.6331143352090294,
					8.230607116535396
				],
				[
					0.9496956545772264,
					7.5974927813264514
				],
				[
					0.9496956545772264,
					6.964354294353711
				],
				[
					0.6331143352090294,
					6.647797126749225
				],
				[
					0,
					6.647797126749225
				],
				[
					-0.6331143352090294,
					6.964354294353711
				],
				[
					-1.266252822181741,
					6.964354294353711
				],
				[
					-1.5828099897862558,
					6.964354294353711
				],
				[
					-1.8993671573907704,
					6.647797126749225
				],
				[
					-1.5828099897862558,
					6.964354294353711
				],
				[
					-1.5828099897862558,
					7.280935613721965
				],
				[
					-1.5828099897862558,
					7.280935613721965
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0009765625,
				0.283203125,
				0.36328125,
				0.416015625,
				0.435546875,
				0.4404296875,
				0.44140625,
				0.439453125,
				0.412109375,
				0.37109375,
				0.3359375,
				0.328125,
				0.3271484375,
				0.3291015625,
				0.33203125,
				0.3369140625,
				0.3642578125,
				0.3740234375,
				0.3759765625,
				0.3759765625,
				0.306640625,
				0.0400390625,
				0.0009765625,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 194,
			"versionNonce": 495618436,
			"isDeleted": false,
			"id": "NWjH16WJM-IXsOrnFgWDw",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1447.3744191143408,
			"y": 563.6393923923387,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 4.115315634149738,
			"height": 7.914049948930881,
			"seed": 512181719,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-0.3165571676045147,
					0.31655716760445785
				],
				[
					-0.3165571676045147,
					-0.3165571676045147
				],
				[
					0,
					-1.2662528221816842
				],
				[
					0,
					-2.849062811967883
				],
				[
					0,
					-4.74842996935854
				],
				[
					0,
					-6.331239959144739
				],
				[
					0,
					-6.964354294353711
				],
				[
					0,
					-7.597492781326423
				],
				[
					-0.6331143352090294,
					-7.597492781326423
				],
				[
					-1.5828099897862558,
					-7.280935613721965
				],
				[
					-2.532505644363482,
					-6.647797126749197
				],
				[
					-3.482177147176799,
					-6.331239959144739
				],
				[
					-3.7987343147813135,
					-6.331239959144739
				],
				[
					-4.115315634149738,
					-5.698125623935766
				],
				[
					-3.7987343147813135,
					-5.381544304567512
				],
				[
					-3.482177147176799,
					-5.381544304567512
				],
				[
					-3.482177147176799,
					-5.381544304567512
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0029296875,
				0.1650390625,
				0.39453125,
				0.423828125,
				0.4296875,
				0.431640625,
				0.431640625,
				0.431640625,
				0.431640625,
				0.435546875,
				0.4384765625,
				0.4375,
				0.43359375,
				0.4169921875,
				0.2431640625,
				0.0576171875,
				0.01171875,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 183,
			"versionNonce": 1029685436,
			"isDeleted": false,
			"id": "OLsF8UOAmWSfFK-jWZ3GQ",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1450.2234819263085,
			"y": 561.7400252349479,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 5.381568456331252,
			"height": 0.9496715028134304,
			"seed": 1782141689,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-1.2662528221815137,
					0
				],
				[
					-2.5325056443632548,
					0.31655716760445785
				],
				[
					-3.482177147176799,
					0.31655716760445785
				],
				[
					-4.74842996935854,
					0.6331143352089725
				],
				[
					-5.381568456331252,
					0.9496715028134304
				],
				[
					-5.381568456331252,
					0.9496715028134304
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0029296875,
				0.1494140625,
				0.2041015625,
				0.220703125,
				0.1904296875,
				0.1025390625,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 202,
			"versionNonce": 436648196,
			"isDeleted": false,
			"id": "WwBX5Ps85LvsbzyzL-1sG",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1450.2234819263085,
			"y": 594.9790350204577,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 6.331239959144796,
			"height": 7.914049948930938,
			"seed": 317689465,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-0.3165571676042873,
					-1.2662528221816842
				],
				[
					-0.3165571676042873,
					-1.8993671573906568
				],
				[
					-0.949695654576999,
					-1.582809989786142
				],
				[
					-1.5828099897860284,
					-1.2662528221816842
				],
				[
					-2.21594847675874,
					-0.6331384869727117
				],
				[
					-2.8490628119677694,
					0
				],
				[
					-3.165619979572284,
					0.3165571676045147
				],
				[
					-2.5325056443632548,
					0.9496715028134872
				],
				[
					-1.899367157390543,
					1.266252822181741
				],
				[
					-0.6331384869727117,
					1.8993671573907136
				],
				[
					0.6331143352090294,
					2.2159243249951714
				],
				[
					1.266252822181741,
					2.849062811967883
				],
				[
					1.5828099897862558,
					3.165619979572398
				],
				[
					1.266252822181741,
					3.7987343147813704
				],
				[
					0.6331143352090294,
					4.748429969358597
				],
				[
					-0.6331384869727117,
					5.698101472172027
				],
				[
					-1.5828099897860284,
					6.014682791540281
				],
				[
					-1.899367157390543,
					5.381544304567512
				],
				[
					-1.5828099897860284,
					4.431872801754082
				],
				[
					-0.3165571676042873,
					2.5324814925996293
				],
				[
					1.266252822181741,
					0.6331143352089725
				],
				[
					2.215924324995285,
					-0.6331384869727117
				],
				[
					3.1656199795725115,
					-0.9496956545771695
				],
				[
					3.1656199795725115,
					-0.6331384869727117
				],
				[
					3.1656199795725115,
					-0.6331384869727117
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0029296875,
				0.1630859375,
				0.298828125,
				0.396484375,
				0.4619140625,
				0.47265625,
				0.4736328125,
				0.47265625,
				0.4599609375,
				0.4501953125,
				0.4462890625,
				0.4423828125,
				0.4443359375,
				0.4404296875,
				0.435546875,
				0.4365234375,
				0.435546875,
				0.435546875,
				0.4345703125,
				0.43359375,
				0.4345703125,
				0.4189453125,
				0.357421875,
				0.10546875,
				0.0087890625,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 201,
			"versionNonce": 2040547644,
			"isDeleted": false,
			"id": "sG-dpI8AV8fkJ5L-MG6qv",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1441.992874809773,
			"y": 650.0608184384582,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 4.431872801754253,
			"height": 12.345922750684991,
			"seed": 1931783223,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.3165571676045147,
					-0.6331264110908421
				],
				[
					0.6331143352090294,
					-0.9496835786953284
				],
				[
					0.9496715028135441,
					-1.2662528221816842
				],
				[
					1.5828099897862558,
					-1.8993792332725263
				],
				[
					2.215924324995285,
					-2.532493568481499
				],
				[
					3.1656199795725115,
					-2.532493568481499
				],
				[
					3.482177147177026,
					-2.2159364008770126
				],
				[
					3.798734314781541,
					-1.5828099897861705
				],
				[
					2.5324814925998,
					-0.31656924348635584
				],
				[
					1.2662286704180588,
					0.31655716760448627
				],
				[
					0,
					-0.31656924348635584
				],
				[
					-0.6331384869727117,
					-0.9496835786953284
				],
				[
					-0.6331384869727117,
					-1.8993792332725263
				],
				[
					0,
					-2.849062811967883
				],
				[
					0.6331143352090294,
					-3.7987463906632115
				],
				[
					1.2662286704180588,
					-3.4821892230587252
				],
				[
					1.8993671573907704,
					-2.532493568481499
				],
				[
					2.215924324995285,
					-0.31656924348635584
				],
				[
					2.215924324995285,
					2.5324935684815273
				],
				[
					2.215924324995285,
					6.014670715658383
				],
				[
					2.215924324995285,
					7.914049948930909
				],
				[
					2.215924324995285,
					8.54717636002178
				],
				[
					2.8490386602043145,
					8.230607116535396
				],
				[
					2.8490386602043145,
					8.230607116535396
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.001953125,
				0.0439453125,
				0.1484375,
				0.212890625,
				0.3447265625,
				0.4716796875,
				0.61328125,
				0.654296875,
				0.6650390625,
				0.6591796875,
				0.6552734375,
				0.64453125,
				0.638671875,
				0.62890625,
				0.6162109375,
				0.6083984375,
				0.6142578125,
				0.6171875,
				0.6201171875,
				0.623046875,
				0.6171875,
				0.498046875,
				0.263671875,
				0.013671875,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 189,
			"versionNonce": 642840708,
			"isDeleted": false,
			"id": "Hz-nMgVW4TlzrV73JYWKn",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1435.6616348506284,
			"y": 685.1991953813587,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 4.115291482385828,
			"height": 8.230607116535396,
			"seed": 1852220119,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.2662286704178314,
					-0.6331264110908421
				],
				[
					2.2159243249950578,
					-1.2662407462998146
				],
				[
					2.849038660204087,
					-1.8993671573906568
				],
				[
					3.165619979572284,
					-1.5828099897861705
				],
				[
					3.165619979572284,
					0
				],
				[
					2.849038660204087,
					2.215936400877041
				],
				[
					2.849038660204087,
					4.431872801754054
				],
				[
					2.849038660204087,
					6.0146827915402525
				],
				[
					2.849038660204087,
					6.331239959144739
				],
				[
					3.482177147176799,
					5.064987136963026
				],
				[
					4.115291482385828,
					4.115315634149596
				],
				[
					4.115291482385828,
					4.115315634149596
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0068359375,
				0.234375,
				0.306640625,
				0.3115234375,
				0.3134765625,
				0.330078125,
				0.34765625,
				0.349609375,
				0.3154296875,
				0.216796875,
				0.037109375,
				0.001953125,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 188,
			"versionNonce": 1572585916,
			"isDeleted": false,
			"id": "fAG0klNLrIHyrdecy_jV3",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1441.992874809773,
			"y": 684.8826382137541,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 4.431872801754025,
			"height": 5.381556380449382,
			"seed": 955878071,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					2.8490386602043145,
					-0.31656924348635584
				],
				[
					3.1656199795725115,
					1.2662407462998146
				],
				[
					2.5324814925998,
					3.4821771471768557
				],
				[
					1.2662286704180588,
					4.74842996935854
				],
				[
					0,
					5.064987136963026
				],
				[
					-1.2662528221815137,
					4.431872801754082
				],
				[
					-1.2662528221815137,
					2.8490507360860136
				],
				[
					-0.9496956545772264,
					0.9496835786953284
				],
				[
					-0.6331384869727117,
					0.31655716760448627
				],
				[
					0,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0,
				0.1533203125,
				0.1826171875,
				0.2265625,
				0.248046875,
				0.2529296875,
				0.2548828125,
				0.2431640625,
				0.0703125,
				0.013671875,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 183,
			"versionNonce": 1042761732,
			"isDeleted": false,
			"id": "NOJl8ANnU7U4b1kdUEKtV",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1441.992874809773,
			"y": 711.7904080401191,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 0.6331384869727117,
			"height": 8.230607116535396,
			"seed": 1216717177,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					3.1656199795723694
				],
				[
					0,
					5.698125623935766
				],
				[
					-0.316581319368197,
					7.597492781326423
				],
				[
					0,
					8.230607116535396
				],
				[
					0.3165571676045147,
					8.230607116535396
				],
				[
					0.3165571676045147,
					8.230607116535396
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0068359375,
				0.2880859375,
				0.31640625,
				0.2412109375,
				0.068359375,
				0.0146484375,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 182,
			"versionNonce": 282339900,
			"isDeleted": false,
			"id": "uR3yapyJ3z7eHjx4T-NeI",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1446.4247234597633,
			"y": 712.7401036946964,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 0.633114335208802,
			"height": 7.5974686295626555,
			"seed": 1667276025,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-0.3165571676042873,
					3.7987343147813135
				],
				[
					-0.633114335208802,
					5.698101472171999
				],
				[
					-0.633114335208802,
					6.964354294353683
				],
				[
					-0.3165571676042873,
					7.5974686295626555
				],
				[
					-0.3165571676042873,
					7.5974686295626555
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.001953125,
				0.2236328125,
				0.2177734375,
				0.099609375,
				0.0009765625,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 182,
			"versionNonce": 898082692,
			"isDeleted": false,
			"id": "kOJLwKEWqEfhjw8BJVsZU",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1441.992874809773,
			"y": 744.7128606580244,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 0.6331143352090294,
			"height": 6.964354294353711,
			"seed": 131051127,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.3165571676045147,
					2.849062811967883
				],
				[
					0.3165571676045147,
					4.431872801754082
				],
				[
					0,
					6.014682791540281
				],
				[
					0.6331143352090294,
					6.964354294353711
				],
				[
					0.6331143352090294,
					6.964354294353711
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.00390625,
				0.3271484375,
				0.353515625,
				0.25,
				0.029296875,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 201,
			"versionNonce": 97223356,
			"isDeleted": false,
			"id": "5h8HIkibZpcan106bajsT",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1446.7413047791317,
			"y": 745.9791134802061,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 4.4318486499901155,
			"height": 5.698101472172027,
			"seed": 1329241881,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.633114335208802,
					-0.6331384869727685
				],
				[
					1.2662286704178314,
					-0.9496956545772264
				],
				[
					1.5828099897860284,
					-1.266252822181741
				],
				[
					1.899367157390543,
					-0.9496956545772264
				],
				[
					1.899367157390543,
					-0.6331384869727685
				],
				[
					1.899367157390543,
					-0.31658131936825384
				],
				[
					1.899367157390543,
					0
				],
				[
					1.899367157390543,
					0.31655716760445785
				],
				[
					1.899367157390543,
					0.6331143352089725
				],
				[
					1.899367157390543,
					0.9496715028134304
				],
				[
					1.899367157390543,
					1.2662286704178882
				],
				[
					1.5828099897860284,
					1.582809989786142
				],
				[
					1.5828099897860284,
					1.8993671573906568
				],
				[
					1.5828099897860284,
					2.5324814925996293
				],
				[
					1.2662286704178314,
					3.165619979572341
				],
				[
					1.2662286704178314,
					3.7987343147813135
				],
				[
					1.5828099897860284,
					4.115291482385771
				],
				[
					1.5828099897860284,
					4.431848649990286
				],
				[
					2.2159243249950578,
					4.431848649990286
				],
				[
					2.8490386602038598,
					4.431848649990286
				],
				[
					3.482177147176799,
					3.7987343147813135
				],
				[
					4.115291482385601,
					3.7987343147813135
				],
				[
					4.4318486499901155,
					3.7987343147813135
				],
				[
					4.4318486499901155,
					3.7987343147813135
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0078125,
				0.193359375,
				0.2412109375,
				0.2705078125,
				0.3056640625,
				0.3515625,
				0.359375,
				0.3662109375,
				0.3798828125,
				0.4130859375,
				0.416015625,
				0.4169921875,
				0.4169921875,
				0.4169921875,
				0.4169921875,
				0.4189453125,
				0.4384765625,
				0.44140625,
				0.4423828125,
				0.439453125,
				0.4326171875,
				0.341796875,
				0.115234375,
				0.0419921875,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 184,
			"versionNonce": 816846596,
			"isDeleted": false,
			"id": "z61sgumcypRzEnd4hxAMI",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1444.8419134699773,
			"y": 772.5703019872032,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 0.6331384869727117,
			"height": 9.49685993871708,
			"seed": 1051018873,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.316581319368197,
					2.2159484767589106
				],
				[
					0,
					4.115315634149567
				],
				[
					-0.3165571676045147,
					6.647821278512936
				],
				[
					-0.3165571676045147,
					8.54718843590365
				],
				[
					0,
					9.49685993871708
				],
				[
					0.316581319368197,
					9.49685993871708
				],
				[
					0.316581319368197,
					9.49685993871708
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0068359375,
				0.3271484375,
				0.3466796875,
				0.341796875,
				0.2734375,
				0.0859375,
				0.0234375,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 196,
			"versionNonce": 54774588,
			"isDeleted": false,
			"id": "OZYchQlN81H6_Le4Ojeri",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1448.9572291041268,
			"y": 773.8365548093847,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 4.431848649990343,
			"height": 7.914049948930881,
			"seed": 1068119575,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.9496956545772264,
					0
				],
				[
					1.5828099897860284,
					0.31655716760445785
				],
				[
					1.899367157390543,
					0.31655716760445785
				],
				[
					1.899367157390543,
					0.9496956545772264
				],
				[
					1.899367157390543,
					1.582809989786199
				],
				[
					1.5828099897860284,
					1.8993671573906568
				],
				[
					1.5828099897860284,
					2.2159484767589106
				],
				[
					1.5828099897860284,
					2.5325056443633684
				],
				[
					1.899367157390543,
					2.5325056443633684
				],
				[
					2.5325056443632548,
					2.849062811967883
				],
				[
					3.482177147176799,
					3.165619979572341
				],
				[
					3.7987343147813135,
					3.7987584665451095
				],
				[
					3.7987343147813135,
					5.064987136963055
				],
				[
					2.8490628119677694,
					6.647797126749197
				],
				[
					1.266252822181741,
					7.597492781326423
				],
				[
					-0.3165571676045147,
					7.914049948930881
				],
				[
					-0.6331143352090294,
					7.597492781326423
				],
				[
					-0.6331143352090294,
					7.280935613721965
				],
				[
					-0.6331143352090294,
					7.280935613721965
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0009765625,
				0.255859375,
				0.296875,
				0.2978515625,
				0.2958984375,
				0.2978515625,
				0.2978515625,
				0.2978515625,
				0.2978515625,
				0.296875,
				0.298828125,
				0.2958984375,
				0.2978515625,
				0.2998046875,
				0.2998046875,
				0.2998046875,
				0.2724609375,
				0.1943359375,
				0.0693359375,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 184,
			"versionNonce": 471766660,
			"isDeleted": false,
			"id": "nxM2ZjSGhmX04RVmsn9e7",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1443.8922419671637,
			"y": 804.8596402698994,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 1.5828099897862558,
			"height": 8.230607116535396,
			"seed": 807407513,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-0.6331384869727117,
					3.4821771471768557
				],
				[
					-0.9496956545772264,
					6.014682791540224
				],
				[
					-1.266252822181741,
					7.280911461958169
				],
				[
					-0.9496956545772264,
					8.230607116535396
				],
				[
					0,
					7.914049948930938
				],
				[
					0.3165571676045147,
					7.914049948930938
				],
				[
					0.3165571676045147,
					7.914049948930938
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.005859375,
				0.2763671875,
				0.28515625,
				0.283203125,
				0.1953125,
				0.0322265625,
				0.0009765625,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 184,
			"versionNonce": 731841468,
			"isDeleted": false,
			"id": "aj6w7G5xREhtKq-oiwf4G",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1448.3241147689178,
			"y": 807.0755645948947,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 2.2159484767589674,
			"height": 3.7987584665450527,
			"seed": 542154487,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-0.6331384869727117,
					2.2159484767589106
				],
				[
					-0.6331384869727117,
					3.165619979572341
				],
				[
					-0.316581319368197,
					3.7987584665450527
				],
				[
					0.3165571676045147,
					3.7987584665450527
				],
				[
					0.9496715028135441,
					3.4821771471768557
				],
				[
					1.5828099897862558,
					3.165619979572341
				],
				[
					1.5828099897862558,
					3.165619979572341
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0029296875,
				0.2744140625,
				0.306640625,
				0.3056640625,
				0.2119140625,
				0.1103515625,
				0.021484375,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 182,
			"versionNonce": 613492228,
			"isDeleted": false,
			"id": "xBAfZtRqXOtpBysB5kItD",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1450.5400390939128,
			"y": 808.0252602494719,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 0.633114335208802,
			"height": 6.9643542943536545,
			"seed": 312863609,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-0.3165571676042873,
					3.482177147176799
				],
				[
					-0.3165571676042873,
					5.69810147217197
				],
				[
					0,
					6.9643542943536545
				],
				[
					0.3165571676045147,
					6.9643542943536545
				],
				[
					0.3165571676045147,
					6.9643542943536545
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.001953125,
				0.2373046875,
				0.23828125,
				0.1396484375,
				0.0478515625,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 191,
			"versionNonce": 83831868,
			"isDeleted": false,
			"id": "x-l53H9R7_Z9Q7AmcamEr",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1442.625964993218,
			"y": 839.9980172127999,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 1.8993671573907704,
			"height": 6.964354294353683,
			"seed": 102299639,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					0.31655716760448627
				],
				[
					0.3165571676045147,
					0
				],
				[
					0.9496956545772264,
					-0.949695654577198
				],
				[
					1.5828099897862558,
					-1.8993671573906568
				],
				[
					1.5828099897862558,
					-2.215924324995143
				],
				[
					1.8993671573907704,
					-1.8993671573906568
				],
				[
					1.5828099897862558,
					-1.2662528221816842
				],
				[
					1.266252822181741,
					0.31655716760448627
				],
				[
					1.266252822181741,
					2.532505644363397
				],
				[
					1.266252822181741,
					4.115315634149596
				],
				[
					0.9496956545772264,
					4.431872801754082
				],
				[
					1.266252822181741,
					4.74842996935854
				],
				[
					1.8993671573907704,
					4.74842996935854
				],
				[
					1.8993671573907704,
					4.74842996935854
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0009765625,
				0.271484375,
				0.3818359375,
				0.3876953125,
				0.388671875,
				0.388671875,
				0.39453125,
				0.392578125,
				0.3916015625,
				0.390625,
				0.373046875,
				0.263671875,
				0.234375,
				0.0078125,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 191,
			"versionNonce": 788907396,
			"isDeleted": false,
			"id": "bUAELi15xLAdaPmqoNDU0",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1450.8565721097536,
			"y": 837.4655115684365,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 4.431872801754253,
			"height": 6.647821278512993,
			"seed": 1261981943,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					0.31658131936825384
				],
				[
					-0.6331143352090294,
					0.9496956545772264
				],
				[
					-0.9496715028135441,
					1.2662528221817126
				],
				[
					-0.9496715028135441,
					1.582809989786199
				],
				[
					-0.9496715028135441,
					1.8993913091544243
				],
				[
					-0.3165571676045147,
					2.2159484767589106
				],
				[
					0.316581319368197,
					2.849062811967883
				],
				[
					0.6331384869727117,
					3.4822012989406232
				],
				[
					0.6331384869727117,
					4.115315634149596
				],
				[
					0,
					4.74842996935854
				],
				[
					-1.5828099897862558,
					5.698125623935766
				],
				[
					-3.1656199795725115,
					6.331239959144739
				],
				[
					-3.798734314781541,
					6.647821278512993
				],
				[
					-3.798734314781541,
					6.647821278512993
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0009765625,
				0.2373046875,
				0.2529296875,
				0.2529296875,
				0.2578125,
				0.2734375,
				0.2734375,
				0.2734375,
				0.2734375,
				0.2734375,
				0.2724609375,
				0.2568359375,
				0.15625,
				0.0087890625,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 184,
			"versionNonce": 21382332,
			"isDeleted": false,
			"id": "Bkpkn55z-md1Fwa4EMTi6",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1445.475027805186,
			"y": 867.8554826937419,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 1.266252822181741,
			"height": 8.230607116535396,
			"seed": 1756277239,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					0.6331143352089725
				],
				[
					-0.6331143352090294,
					2.849038660204087
				],
				[
					-0.9496956545772264,
					5.381544304567512
				],
				[
					-1.266252822181741,
					7.280911461958169
				],
				[
					-0.9496956545772264,
					8.230607116535396
				],
				[
					-0.3165571676045147,
					8.230607116535396
				],
				[
					-0.3165571676045147,
					8.230607116535396
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0009765625,
				0.330078125,
				0.3505859375,
				0.349609375,
				0.283203125,
				0.1337890625,
				0.009765625,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 191,
			"versionNonce": 1354396932,
			"isDeleted": false,
			"id": "Xv7tNPu3KM_g3hfDRD2gF",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1451.8062677643309,
			"y": 869.4382926835282,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 3.165619979572284,
			"height": 6.647797126749197,
			"seed": 830967929,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-0.9496956545772264,
					1.2662286704178882
				],
				[
					-1.8993671573907704,
					2.849038660204087
				],
				[
					-2.849062811967997,
					4.431848649990286
				],
				[
					-2.849062811967997,
					5.69810147217197
				],
				[
					-2.215924324995285,
					6.647797126749197
				],
				[
					-0.9496956545772264,
					6.647797126749197
				],
				[
					0,
					6.014658639776485
				],
				[
					0.3165571676042873,
					5.69810147217197
				],
				[
					0.3165571676042873,
					5.381544304567512
				],
				[
					-0.6331143352090294,
					5.381544304567512
				],
				[
					-1.8993671573907704,
					5.381544304567512
				],
				[
					-2.849062811967997,
					5.381544304567512
				],
				[
					-2.532505644363482,
					5.064987136962998
				],
				[
					-2.532505644363482,
					5.064987136962998
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0029296875,
				0.3095703125,
				0.322265625,
				0.322265625,
				0.322265625,
				0.318359375,
				0.2802734375,
				0.2470703125,
				0.240234375,
				0.240234375,
				0.2646484375,
				0.265625,
				0.189453125,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 183,
			"versionNonce": 102124860,
			"isDeleted": false,
			"id": "-SSk9cq-lymQNiwoOeZaz",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1446.1081421403949,
			"y": 856.4592314458704,
			"strokeColor": "#862e9c",
			"backgroundColor": "transparent",
			"width": 1.2662286704178314,
			"height": 8.230631268299135,
			"seed": 1174718329,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-0.633114335208802,
					2.5325056443634253
				],
				[
					-1.2662286704178314,
					5.698125623935766
				],
				[
					-1.2662286704178314,
					7.597492781326423
				],
				[
					-0.9496715028133167,
					8.230631268299135
				],
				[
					0,
					7.914049948930938
				],
				[
					0,
					7.914049948930938
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0029296875,
				0.396484375,
				0.3916015625,
				0.3017578125,
				0.1416015625,
				0.0068359375,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 190,
			"versionNonce": 1194144900,
			"isDeleted": false,
			"id": "CLfi1E3QbSbabKVpAO69m",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1451.8062677643309,
			"y": 856.1426742782659,
			"strokeColor": "#862e9c",
			"backgroundColor": "transparent",
			"width": 2.532505644363482,
			"height": 6.331239959144682,
			"seed": 219988729,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-0.9496956545772264,
					1.582809989786142
				],
				[
					-1.5828099897862558,
					3.165619979572341
				],
				[
					-2.215924324995285,
					4.74842996935854
				],
				[
					-2.532505644363482,
					5.698125623935709
				],
				[
					-1.8993671573907704,
					6.331239959144682
				],
				[
					-0.9496956545772264,
					6.014682791540224
				],
				[
					-0.3165571676045147,
					5.381568456331252
				],
				[
					0,
					5.064987136962998
				],
				[
					0,
					4.74842996935854
				],
				[
					-0.3165571676045147,
					4.431872801754025
				],
				[
					-1.5828099897862558,
					4.431872801754025
				],
				[
					-1.8993671573907704,
					4.431872801754025
				],
				[
					-1.8993671573907704,
					4.431872801754025
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0009765625,
				0.330078125,
				0.3515625,
				0.3525390625,
				0.3505859375,
				0.318359375,
				0.26953125,
				0.2470703125,
				0.24609375,
				0.24609375,
				0.24609375,
				0.1611328125,
				0.0517578125,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 183,
			"versionNonce": 1959871932,
			"isDeleted": false,
			"id": "-B9LANIebHlJ60icsLQ2_",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1444.2087749830043,
			"y": 821.3208545029703,
			"strokeColor": "#862e9c",
			"backgroundColor": "transparent",
			"width": 0.9496956545772264,
			"height": 7.914049948930909,
			"seed": 219919607,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.3165571676045147,
					1.2662528221817126
				],
				[
					0,
					3.4821771471768557
				],
				[
					0,
					5.698125623935766
				],
				[
					0.3165571676045147,
					7.280935613721937
				],
				[
					0.9496956545772264,
					7.914049948930909
				],
				[
					0.9496956545772264,
					7.914049948930909
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0029296875,
				0.3125,
				0.34375,
				0.322265625,
				0.1865234375,
				0.017578125,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 190,
			"versionNonce": 1880884228,
			"isDeleted": false,
			"id": "ADIrDswMBOCtkZfBYuOnd",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1451.8062677643309,
			"y": 821.6374116705748,
			"strokeColor": "#862e9c",
			"backgroundColor": "transparent",
			"width": 4.115315634149738,
			"height": 6.0146827915402525,
			"seed": 1282015607,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-0.6331143352090294,
					0.6331384869727401
				],
				[
					-1.5828099897862558,
					1.2662528221817126
				],
				[
					-1.8993671573907704,
					1.8993913091544243
				],
				[
					-1.8993671573907704,
					2.2159484767589106
				],
				[
					-1.5828099897862558,
					2.532505644363397
				],
				[
					-0.6331143352090294,
					3.1656199795723694
				],
				[
					0,
					3.7987584665451095
				],
				[
					0,
					4.115315634149596
				],
				[
					-0.3165571676045147,
					4.74842996935854
				],
				[
					-1.8993671573907704,
					5.698125623935766
				],
				[
					-3.482177147177026,
					6.0146827915402525
				],
				[
					-4.115315634149738,
					6.0146827915402525
				],
				[
					-4.115315634149738,
					6.0146827915402525
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0029296875,
				0.2529296875,
				0.2568359375,
				0.2568359375,
				0.259765625,
				0.259765625,
				0.2587890625,
				0.26171875,
				0.2646484375,
				0.279296875,
				0.26953125,
				0.1552734375,
				0.015625,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 185,
			"versionNonce": 848899644,
			"isDeleted": false,
			"id": "1DrW1Gy6OlccMIEZp8wHM",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1444.841913469977,
			"y": 790.6143382859419,
			"strokeColor": "#862e9c",
			"backgroundColor": "transparent",
			"width": 0.6331384869727117,
			"height": 8.54717636002178,
			"seed": 1341966233,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267740,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-0.316581319368197,
					0.31656924348638427
				],
				[
					-0.316581319368197,
					1.582809989786199
				],
				[
					-0.316581319368197,
					3.4821892230587252
				],
				[
					-0.316581319368197,
					5.698125623935766
				],
				[
					-0.316581319368197,
					7.597492781326423
				],
				[
					0,
					8.54717636002178
				],
				[
					0.3165571676045147,
					8.54717636002178
				],
				[
					0.3165571676045147,
					8.54717636002178
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0009765625,
				0.21875,
				0.3232421875,
				0.373046875,
				0.376953125,
				0.2919921875,
				0.1240234375,
				0.017578125,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 187,
			"versionNonce": 1099228036,
			"isDeleted": false,
			"id": "9cGpCH1NAU_GniBVQNxsU",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1449.2737621199674,
			"y": 790.6143382859419,
			"strokeColor": "#862e9c",
			"backgroundColor": "transparent",
			"width": 3.7987343147813135,
			"height": 6.0146827915402525,
			"seed": 1219487737,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267741,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.316581319368197,
					0.9496956545772264
				],
				[
					-0.3165571676045147,
					2.215936400877041
				],
				[
					-0.9496715028135441,
					3.4821892230587252
				],
				[
					-0.9496715028135441,
					4.431872801754082
				],
				[
					-0.3165571676045147,
					5.38155638044941
				],
				[
					0.6331384869727117,
					6.0146827915402525
				],
				[
					1.266252822181741,
					6.0146827915402525
				],
				[
					1.8993913091544528,
					5.698125623935766
				],
				[
					2.8490628119677694,
					5.064999212844924
				],
				[
					2.8490628119677694,
					5.064999212844924
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0,
				0.349609375,
				0.369140625,
				0.37109375,
				0.3720703125,
				0.3720703125,
				0.3671875,
				0.333984375,
				0.1484375,
				0.001953125,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 182,
			"versionNonce": 810550972,
			"isDeleted": false,
			"id": "W1Ig_J739yHNYYHfAU3pV",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1451.8062677643309,
			"y": 792.830274686819,
			"strokeColor": "#862e9c",
			"backgroundColor": "transparent",
			"width": 0.3165571676045147,
			"height": 6.331239959144739,
			"seed": 771348793,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267741,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					2.5324935684815273
				],
				[
					-0.3165571676045147,
					4.74842996935854
				],
				[
					-0.3165571676045147,
					6.0146827915402525
				],
				[
					0,
					6.331239959144739
				],
				[
					0,
					6.331239959144739
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0009765625,
				0.2890625,
				0.271484375,
				0.0966796875,
				0.0078125,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 183,
			"versionNonce": 1101386500,
			"isDeleted": false,
			"id": "G7s1BKX3L6wKkE9jBbNRK",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1444.5253321506088,
			"y": 763.0734541243679,
			"strokeColor": "#862e9c",
			"backgroundColor": "transparent",
			"width": 0.6331384869727117,
			"height": 5.381544304567512,
			"seed": 650341943,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267741,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					1.2662407462998146
				],
				[
					0,
					2.849050736085985
				],
				[
					0,
					4.431860725872156
				],
				[
					0,
					5.381544304567512
				],
				[
					0.6331384869727117,
					5.381544304567512
				],
				[
					0.6331384869727117,
					5.381544304567512
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0,
				0.2177734375,
				0.267578125,
				0.25,
				0.1201171875,
				0.021484375,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 190,
			"versionNonce": 1922551612,
			"isDeleted": false,
			"id": "dPKk54lJXk3_IODyNl1tg",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1447.6909521301811,
			"y": 761.8072013021862,
			"strokeColor": "#862e9c",
			"backgroundColor": "transparent",
			"width": 2.849062811967997,
			"height": 5.698113548053868,
			"seed": 1892358839,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267741,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.9496956545772264,
					0.6331264110908421
				],
				[
					0.9496956545772264,
					1.2662528221817126
				],
				[
					0.6331384869727117,
					1.8993671573906568
				],
				[
					0.6331384869727117,
					2.5324935684815273
				],
				[
					0.6331384869727117,
					3.1656199795723694
				],
				[
					0.9496956545772264,
					3.1656199795723694
				],
				[
					1.266252822181741,
					3.1656199795723694
				],
				[
					2.2159484767589674,
					3.4821771471768557
				],
				[
					2.849062811967997,
					3.7987463906632115
				],
				[
					2.849062811967997,
					4.431872801754054
				],
				[
					0.316581319368197,
					5.698113548053868
				],
				[
					0.6331384869727117,
					5.064987136963026
				],
				[
					0.6331384869727117,
					5.064987136963026
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0029296875,
				0.1484375,
				0.1533203125,
				0.154296875,
				0.1572265625,
				0.158203125,
				0.1591796875,
				0.1591796875,
				0.16796875,
				0.19921875,
				0.224609375,
				0.19921875,
				0.0283203125,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 185,
			"versionNonce": 2130498180,
			"isDeleted": false,
			"id": "4_YaiWuHaVd4k2t3SGd9f",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1442.9425221608226,
			"y": 730.4675586740669,
			"strokeColor": "#862e9c",
			"backgroundColor": "transparent",
			"width": 0.9496956545772264,
			"height": 7.914049948930909,
			"seed": 984775257,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267741,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.316581319368197,
					-0.9496835786953284
				],
				[
					0,
					-0.6331143352089725
				],
				[
					0,
					1.5828099897861705
				],
				[
					0,
					3.4821892230587252
				],
				[
					0,
					5.381556380449382
				],
				[
					0.316581319368197,
					6.647809202631095
				],
				[
					0.9496956545772264,
					6.964366370235581
				],
				[
					0.9496956545772264,
					6.964366370235581
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0,
				0.28515625,
				0.39453125,
				0.4033203125,
				0.40234375,
				0.357421875,
				0.1845703125,
				0.0439453125,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 188,
			"versionNonce": 433227708,
			"isDeleted": false,
			"id": "OOP7yc4f1W6QQvBYOEp8A",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1446.4247234597633,
			"y": 730.4675586740669,
			"strokeColor": "#862e9c",
			"backgroundColor": "transparent",
			"width": 4.74842996935854,
			"height": 6.647809202631095,
			"seed": 96330425,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267741,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.899367157390543,
					0.949695654577198
				],
				[
					1.5828099897860284,
					2.532505644363397
				],
				[
					1.2662286704178314,
					4.115315634149567
				],
				[
					0.9496715028133167,
					5.381556380449382
				],
				[
					0.9496715028133167,
					6.331239959144739
				],
				[
					1.2662286704178314,
					6.647809202631095
				],
				[
					2.2159243249950578,
					6.331239959144739
				],
				[
					3.482177147176799,
					5.698125623935766
				],
				[
					4.431848649990343,
					5.064999212844896
				],
				[
					4.74842996935854,
					5.064999212844896
				],
				[
					4.74842996935854,
					5.064999212844896
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0078125,
				0.2197265625,
				0.22265625,
				0.25390625,
				0.294921875,
				0.341796875,
				0.365234375,
				0.3642578125,
				0.3193359375,
				0.1328125,
				0.0478515625,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 182,
			"versionNonce": 138928644,
			"isDeleted": false,
			"id": "DZoRRwzQt2EFT2BDJw3fp",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1441.3597121710366,
			"y": 701.0272952792205,
			"strokeColor": "#862e9c",
			"backgroundColor": "transparent",
			"width": 1.2662528221815137,
			"height": 3.4821892230587252,
			"seed": 2073842711,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267741,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.316581319368197,
					1.8993792332725405
				],
				[
					0.6331384869727117,
					3.165619979572355
				],
				[
					0.9496956545772264,
					3.4821892230587252
				],
				[
					1.2662528221815137,
					3.4821892230587252
				],
				[
					1.2662528221815137,
					3.4821892230587252
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.00390625,
				0.2197265625,
				0.240234375,
				0.07421875,
				0.0166015625,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 181,
			"versionNonce": 1780625468,
			"isDeleted": false,
			"id": "IFcmKskUuxMY4dIiKtglD",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1444.841913469977,
			"y": 698.4948017107391,
			"strokeColor": "#862e9c",
			"backgroundColor": "transparent",
			"width": 0.6331143352090294,
			"height": 6.964366370235567,
			"seed": 292716409,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267741,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.3165571676045147,
					4.74842996935854
				],
				[
					0.3165571676045147,
					6.647797126749211
				],
				[
					0.6331143352090294,
					6.964366370235567
				],
				[
					0.6331143352090294,
					6.964366370235567
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0,
				0.244140625,
				0.1923828125,
				0.0732421875,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 185,
			"versionNonce": 1686438276,
			"isDeleted": false,
			"id": "Adk0Zvl3dHXFsrXONsX9G",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1438.8272306784368,
			"y": 670.0042218945878,
			"strokeColor": "#862e9c",
			"backgroundColor": "transparent",
			"width": 0.9496715028135441,
			"height": 7.9140499489309235,
			"seed": 1574479385,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267741,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-1.2662467842407636
				],
				[
					0,
					-0.31656320554542106
				],
				[
					0,
					1.5828099897861847
				],
				[
					0.3165571676045147,
					4.431866763813119
				],
				[
					0.6331143352090294,
					6.0146767535993035
				],
				[
					0.9496715028135441,
					6.64780316469016
				],
				[
					0.9496715028135441,
					6.331239959144725
				],
				[
					0.9496715028135441,
					6.331239959144725
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0029296875,
				0.1171875,
				0.3681640625,
				0.4306640625,
				0.453125,
				0.365234375,
				0.115234375,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 186,
			"versionNonce": 1399376060,
			"isDeleted": false,
			"id": "WNrQUV3clBprSZxIGGB70",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1444.5253321506088,
			"y": 668.737975110347,
			"strokeColor": "#862e9c",
			"backgroundColor": "transparent",
			"width": 2.849062811967997,
			"height": 5.381550342508461,
			"seed": 1758508665,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267741,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.8993913091544528,
					3.1656199795723694
				],
				[
					1.2662528221815137,
					4.748429969358554
				],
				[
					0,
					5.381550342508461
				],
				[
					-0.9496715028135441,
					4.748429969358554
				],
				[
					-0.9496715028135441,
					2.5324935684815273
				],
				[
					-0.6331143352090294,
					1.2662467842407636
				],
				[
					-0.3165571676045147,
					0.9496835786953426
				],
				[
					0,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0048828125,
				0.326171875,
				0.333984375,
				0.333984375,
				0.3544921875,
				0.3330078125,
				0.0703125,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 192,
			"versionNonce": 183644420,
			"isDeleted": false,
			"id": "WvlXWpvZTcHhFnNZtNm64",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1445.7915849727904,
			"y": 632.0167821397195,
			"strokeColor": "#862e9c",
			"backgroundColor": "transparent",
			"width": 4.431872801754025,
			"height": 12.029365583080477,
			"seed": 1402137399,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267741,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.3165813193684244,
					3.4821892230587252
				],
				[
					-0.9496715028133167,
					4.431872801754082
				],
				[
					-2.2159243249950578,
					3.7987463906632115
				],
				[
					-2.5324814925995724,
					2.5324935684815273
				],
				[
					-2.5324814925995724,
					1.2662528221817126
				],
				[
					-1.899367157390543,
					0
				],
				[
					-0.9496715028133167,
					-0.6331264110908421
				],
				[
					0,
					0
				],
				[
					0.9496956545772264,
					1.8993792332725548
				],
				[
					1.266252822181741,
					4.431872801754082
				],
				[
					1.266252822181741,
					7.280923537840067
				],
				[
					0.9496956545772264,
					9.813429182203464
				],
				[
					0.9496956545772264,
					11.396239171989635
				],
				[
					1.8993913091544528,
					11.079669928503279
				],
				[
					1.8993913091544528,
					11.079669928503279
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0078125,
				0.28515625,
				0.2919921875,
				0.291015625,
				0.2919921875,
				0.29296875,
				0.2978515625,
				0.3427734375,
				0.423828125,
				0.4765625,
				0.515625,
				0.525390625,
				0.5126953125,
				0.2119140625,
				0.009765625,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 195,
			"versionNonce": 2034782524,
			"isDeleted": false,
			"id": "RdYV56Q_DHG3zeiHcnn3q",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1450.8565721097536,
			"y": 572.8196981824218,
			"strokeColor": "#862e9c",
			"backgroundColor": "transparent",
			"width": 5.698125623935766,
			"height": 9.813429182203464,
			"seed": 556777145,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267741,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-0.31656924348635584
				],
				[
					-0.9496956545772264,
					1.266240746299843
				],
				[
					-2.215924324995285,
					3.4821771471768557
				],
				[
					-2.849062811967997,
					5.381544304567541
				],
				[
					-2.532505644363482,
					6.647797126749225
				],
				[
					-1.5828099897862558,
					7.914049948930909
				],
				[
					-0.6331143352090294,
					8.547164284139882
				],
				[
					0.633114335208802,
					8.863733527626266
				],
				[
					1.266252822181741,
					9.180290695230752
				],
				[
					0.633114335208802,
					9.496859938717108
				],
				[
					0,
					9.180290695230752
				],
				[
					0,
					7.914049948930909
				],
				[
					0.633114335208802,
					5.381544304567541
				],
				[
					1.899367157390543,
					2.5324935684815273
				],
				[
					2.8490628119677694,
					0.6331143352089725
				],
				[
					2.8490628119677694,
					1.266240746299843
				],
				[
					0,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0078125,
				0.376953125,
				0.4208984375,
				0.4580078125,
				0.486328125,
				0.4892578125,
				0.484375,
				0.46875,
				0.45703125,
				0.4560546875,
				0.451171875,
				0.451171875,
				0.45703125,
				0.4580078125,
				0.451171875,
				0.337890625,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 190,
			"versionNonce": 1527607428,
			"isDeleted": false,
			"id": "95h6cr1fTMlzWILyIdXzp",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1446.741256475604,
			"y": 547.4947383458428,
			"strokeColor": "#862e9c",
			"backgroundColor": "transparent",
			"width": 5.381568456331252,
			"height": 7.280935613721937,
			"seed": 696343417,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267741,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-0.31656924348638427
				],
				[
					0.316581319368197,
					-1.5828099897861705
				],
				[
					0.6331384869727117,
					-4.115315634149596
				],
				[
					0.6331384869727117,
					-6.0146827915402525
				],
				[
					0.316581319368197,
					-7.280935613721937
				],
				[
					-0.3165571676045147,
					-7.280935613721937
				],
				[
					-1.5828099897862558,
					-6.33123995914471
				],
				[
					-2.849038660204087,
					-5.698125623935766
				],
				[
					-4.115291482385828,
					-5.064999212844924
				],
				[
					-4.74842996935854,
					-4.431872801754054
				],
				[
					-4.115291482385828,
					-4.115315634149596
				],
				[
					-3.482177147176799,
					-4.115315634149596
				],
				[
					-3.482177147176799,
					-4.115315634149596
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0009765625,
				0.37109375,
				0.443359375,
				0.4541015625,
				0.455078125,
				0.455078125,
				0.4560546875,
				0.4580078125,
				0.4580078125,
				0.431640625,
				0.28125,
				0.0771484375,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 183,
			"versionNonce": 992135612,
			"isDeleted": false,
			"id": "uV0o1RudC2-xQcNcAfdo3",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1447.6909521301811,
			"y": 543.3794227116932,
			"strokeColor": "#862e9c",
			"backgroundColor": "transparent",
			"width": 3.7987343147813135,
			"height": 0.6331264110908421,
			"seed": 245585015,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267741,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-0.3165571676045147,
					0
				],
				[
					-1.899367157390543,
					0.31656924348638427
				],
				[
					-3.482177147176799,
					0.31656924348638427
				],
				[
					-3.7987343147813135,
					0
				],
				[
					-3.7987343147813135,
					-0.31655716760445785
				],
				[
					-3.7987343147813135,
					-0.31655716760445785
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0029296875,
				0.2861328125,
				0.3271484375,
				0.2880859375,
				0.0576171875,
				0.02734375,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 189,
			"versionNonce": 345292804,
			"isDeleted": false,
			"id": "94VxeSC0YEOdPxXeeUUfh",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1447.057837794972,
			"y": 510.14041896412436,
			"strokeColor": "#862e9c",
			"backgroundColor": "transparent",
			"width": 3.482177147176799,
			"height": 8.230607116535396,
			"seed": 1936056567,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267741,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-1.2662528221815137,
					0.6331203731498931
				],
				[
					-1.8993913091544528,
					1.8993671573906568
				],
				[
					-2.8490628119677694,
					4.431866763813105
				],
				[
					-2.8490628119677694,
					6.647797126749197
				],
				[
					-1.8993913091544528,
					8.230607116535396
				],
				[
					-0.9496956545772264,
					8.230607116535396
				],
				[
					0.3165571676045147,
					6.964360332294632
				],
				[
					0.6331143352090294,
					6.331239959144739
				],
				[
					0.6331143352090294,
					6.0146767535993035
				],
				[
					-2.21594847675874,
					6.0146767535993035
				],
				[
					-2.21594847675874,
					6.331239959144739
				],
				[
					-2.21594847675874,
					6.331239959144739
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0078125,
				0.408203125,
				0.4404296875,
				0.4443359375,
				0.4462890625,
				0.4404296875,
				0.41796875,
				0.359375,
				0.3486328125,
				0.34765625,
				0.333984375,
				0.0205078125,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 197,
			"versionNonce": 1008349756,
			"isDeleted": false,
			"id": "a3JYjZlDPFgBiVob5Vpuy",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1448.7989142926792,
			"y": 479.2756120874117,
			"strokeColor": "#862e9c",
			"backgroundColor": "transparent",
			"width": 7.597492781326537,
			"height": 8.863733527626266,
			"seed": 1764162969,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267741,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-0.3165571676045147,
					-0.31655716760445785
				],
				[
					-0.9496956545772264,
					-0.6331203731498931
				],
				[
					-1.266252822181741,
					-0.9496835786953284
				],
				[
					-1.5828099897862558,
					-0.6331203731498931
				],
				[
					-1.8993671573907704,
					0
				],
				[
					-2.532505644363482,
					0.6331264110908705
				],
				[
					-3.1656199795725115,
					1.2662528221817126
				],
				[
					-3.1656199795725115,
					1.582809989786199
				],
				[
					-3.1656199795725115,
					2.215936400877041
				],
				[
					-3.1656199795725115,
					2.849062811967883
				],
				[
					-2.849062811967997,
					3.1656199795723694
				],
				[
					-2.215924324995285,
					3.4821831851178047
				],
				[
					-1.8993671573907704,
					4.115309596208647
				],
				[
					-0.9496956545772264,
					4.74842996935854
				],
				[
					-0.6331143352090294,
					5.38155638044941
				],
				[
					-0.6331143352090294,
					5.698119585994846
				],
				[
					-1.8993671573907704,
					6.647803164690174
				],
				[
					-3.798734314781541,
					7.597492781326423
				],
				[
					-6.014682791540281,
					7.914049948930938
				],
				[
					-7.597492781326537,
					7.597492781326423
				],
				[
					-7.597492781326537,
					7.597492781326423
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.005859375,
				0.1611328125,
				0.1767578125,
				0.2373046875,
				0.3603515625,
				0.388671875,
				0.390625,
				0.3896484375,
				0.3896484375,
				0.3916015625,
				0.3916015625,
				0.392578125,
				0.392578125,
				0.3935546875,
				0.392578125,
				0.396484375,
				0.41015625,
				0.4111328125,
				0.41796875,
				0.41796875,
				0.0029296875,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 185,
			"versionNonce": 1334189956,
			"isDeleted": false,
			"id": "9-yxw6iam0FTREClG2MZi",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1443.417321684584,
			"y": 415.33011627457813,
			"strokeColor": "#862e9c",
			"backgroundColor": "transparent",
			"width": 3.1656199795725115,
			"height": 8.230619192417237,
			"seed": 662740183,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267741,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-0.3165330158408324,
					2.2159364008770694
				],
				[
					-0.3165330158408324,
					3.7987463906632115
				],
				[
					-0.3165330158408324,
					5.38155638044941
				],
				[
					0,
					6.647809202631095
				],
				[
					0.633162638736394,
					7.280935613721965
				],
				[
					1.2662769739454234,
					7.597492781326423
				],
				[
					2.2159726285226498,
					8.230619192417237
				],
				[
					2.849086963731679,
					7.597492781326423
				],
				[
					2.849086963731679,
					7.597492781326423
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0087890625,
				0.384765625,
				0.40234375,
				0.408203125,
				0.453125,
				0.474609375,
				0.4609375,
				0.197265625,
				0.0068359375,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 184,
			"versionNonce": 1796246204,
			"isDeleted": false,
			"id": "27ghjUbEEneuIbm6M94d6",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1445.6332943131067,
			"y": 446.98631607030177,
			"strokeColor": "#862e9c",
			"backgroundColor": "transparent",
			"width": 2.5324573408361175,
			"height": 6.331239959144739,
			"seed": 1279083191,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267741,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-0.9496956545772264,
					4.115315634149567
				],
				[
					-1.5828099897862558,
					5.38155638044941
				],
				[
					-1.5828099897862558,
					5.698125623935766
				],
				[
					-1.5828099897862558,
					6.014682791540224
				],
				[
					-1.2662769739454234,
					6.014682791540224
				],
				[
					-0.633162638736394,
					6.331239959144739
				],
				[
					0.3165330158408324,
					6.331239959144739
				],
				[
					0.9496473510498618,
					6.331239959144739
				],
				[
					0.9496473510498618,
					6.331239959144739
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0009765625,
				0.265625,
				0.296875,
				0.302734375,
				0.333984375,
				0.3427734375,
				0.240234375,
				0.0673828125,
				0.001953125,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 181,
			"versionNonce": 1948225284,
			"isDeleted": false,
			"id": "q_14OYQ07CXjPU9I4Tadc",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1447.5326373187338,
			"y": 447.936011724879,
			"strokeColor": "#862e9c",
			"backgroundColor": "transparent",
			"width": 0.633114335208802,
			"height": 8.54716428413991,
			"seed": 210330777,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267741,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					3.165619979572341
				],
				[
					0.316581319368197,
					4.74842996935854
				],
				[
					0.316581319368197,
					6.9643542943536545
				],
				[
					0,
					7.914049948930881
				],
				[
					0.633114335208802,
					8.54716428413991
				],
				[
					0.633114335208802,
					8.54716428413991
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0078125,
				0.3154296875,
				0.34375,
				0.3076171875,
				0.16015625,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 202,
			"versionNonce": 178770748,
			"isDeleted": false,
			"id": "Wb1kONfYBRQehMReVEfEE",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1439.935168689171,
			"y": 414.38043269588286,
			"strokeColor": "#862e9c",
			"backgroundColor": "transparent",
			"width": 4.74842996935854,
			"height": 9.180302771112565,
			"seed": 609865753,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267741,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					0.31656924348635584
				],
				[
					0.3165330158408324,
					0.31656924348635584
				],
				[
					0.6331143352090294,
					0.31656924348635584
				],
				[
					1.2662286704180588,
					0.31656924348635584
				],
				[
					1.8993430056268608,
					0.6331264110908705
				],
				[
					2.215924324995285,
					0.9496835786953284
				],
				[
					2.532505644363482,
					1.8993792332725548
				],
				[
					2.532505644363482,
					2.849062811967883
				],
				[
					2.215924324995285,
					3.7987463906632115
				],
				[
					1.8993430056268608,
					5.064999212844896
				],
				[
					1.2662286704180588,
					5.38155638044941
				],
				[
					0.6331143352090294,
					6.014682791540281
				],
				[
					0.3165330158408324,
					6.014682791540281
				],
				[
					0.6331143352090294,
					6.014682791540281
				],
				[
					0.9496956545772264,
					6.014682791540281
				],
				[
					1.5828099897862558,
					6.014682791540281
				],
				[
					2.532505644363482,
					6.331239959144739
				],
				[
					3.165619979572284,
					6.331239959144739
				],
				[
					4.1153156341495105,
					6.647809202631095
				],
				[
					4.74842996935854,
					6.9643663702355525
				],
				[
					4.74842996935854,
					7.597492781326423
				],
				[
					4.431848649990343,
					8.230619192417294
				],
				[
					3.4821529954131165,
					8.86373352762621
				],
				[
					2.532505644363482,
					9.180302771112565
				],
				[
					1.2662286704180588,
					9.180302771112565
				],
				[
					0.6331143352090294,
					8.230619192417294
				],
				[
					0.6331143352090294,
					8.230619192417294
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0009765625,
				0.1611328125,
				0.2861328125,
				0.3193359375,
				0.3759765625,
				0.4267578125,
				0.4404296875,
				0.4580078125,
				0.4609375,
				0.4619140625,
				0.4658203125,
				0.466796875,
				0.46484375,
				0.46484375,
				0.466796875,
				0.4677734375,
				0.4697265625,
				0.470703125,
				0.470703125,
				0.470703125,
				0.4755859375,
				0.50390625,
				0.5078125,
				0.5078125,
				0.505859375,
				0.4443359375,
				0.009765625,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 191,
			"versionNonce": 853479044,
			"isDeleted": false,
			"id": "hDkVM4ttUCf79zPcs3MEt",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1442.4676743335344,
			"y": 386.8395364584269,
			"strokeColor": "#862e9c",
			"backgroundColor": "transparent",
			"width": 4.74842996935854,
			"height": 7.914049948930938,
			"seed": 1053560247,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267741,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.8993430056268608,
					-0.9496835786953284
				],
				[
					2.53245734083589,
					-1.2662407462997862
				],
				[
					2.849038660204087,
					-0.31655716760445785
				],
				[
					2.53245734083589,
					1.266252822181741
				],
				[
					1.8993430056268608,
					2.849062811967883
				],
				[
					1.2662286704178314,
					4.431872801754082
				],
				[
					0.633114335208802,
					6.014682791540281
				],
				[
					0.633114335208802,
					6.6478092026311515
				],
				[
					0.9496473510496344,
					6.6478092026311515
				],
				[
					1.2662286704178314,
					6.6478092026311515
				],
				[
					1.8993430056268608,
					6.6478092026311515
				],
				[
					3.165619979572284,
					6.014682791540281
				],
				[
					4.115267330622146,
					5.38155638044941
				],
				[
					4.431848649990343,
					5.064999212844953
				],
				[
					4.74842996935854,
					5.064999212844953
				],
				[
					4.74842996935854,
					5.064999212844953
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0068359375,
				0.3115234375,
				0.333984375,
				0.3388671875,
				0.3466796875,
				0.3740234375,
				0.3955078125,
				0.431640625,
				0.4599609375,
				0.515625,
				0.5341796875,
				0.537109375,
				0.4990234375,
				0.255859375,
				0.08203125,
				0.015625,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 190,
			"versionNonce": 960629692,
			"isDeleted": false,
			"id": "lXgj48CNdxASM_eBGbx97",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1440.2517017050118,
			"y": 352.3342798886763,
			"strokeColor": "#862e9c",
			"backgroundColor": "transparent",
			"width": 4.4318969535177075,
			"height": 9.180296733171701,
			"seed": 1926346711,
			"groupIds": [
				"hXqS_GLIp0s6oqtUmC9eY"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511267741,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.316581319368197,
					0.3165632055453784
				],
				[
					0.633162638736394,
					0.3165632055453784
				],
				[
					1.2662769739454234,
					0
				],
				[
					2.2159726285226498,
					-0.6331203731498931
				],
				[
					3.165619979572284,
					-1.2662467842407636
				],
				[
					3.798782618308678,
					-1.8993671573907136
				],
				[
					4.1153156341495105,
					-1.8993671573907136
				],
				[
					4.4318969535177075,
					-1.582809989786199
				],
				[
					4.1153156341495105,
					0.3165632055453784
				],
				[
					3.798782618308678,
					2.2159364008770126
				],
				[
					3.482201298940481,
					4.74842996935854
				],
				[
					3.482201298940481,
					6.9643663702355525
				],
				[
					3.798782618308678,
					7.280929575780988
				],
				[
					3.798782618308678,
					7.280929575780988
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0009765625,
				0.369140625,
				0.4521484375,
				0.486328125,
				0.490234375,
				0.48828125,
				0.48828125,
				0.4951171875,
				0.5341796875,
				0.5390625,
				0.53515625,
				0.4208984375,
				0.078125,
				0.03515625,
				0
			]
		},
		{
			"type": "image",
			"version": 164,
			"versionNonce": 2011792188,
			"isDeleted": false,
			"id": "cPh4VCYYzjghKfYrZKQOl",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1969.7129417808014,
			"y": -453.3724904321596,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"width": 800,
			"height": 200.55555555555557,
			"seed": 1331875831,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223449,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "cff9d323d9d35f9a6c5ea129c036648eebdfb4c8",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "text",
			"version": 197,
			"versionNonce": 2010144388,
			"isDeleted": false,
			"id": "XTD3ocNM",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2003.2131495586973,
			"y": -240.2917556939227,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1035,
			"height": 35,
			"seed": 641529684,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1662511223449,
			"link": null,
			"locked": false,
			"fontSize": 28,
			"fontFamily": 1,
			"text": "Deben haber 2k palabras posibles (2^11) con salida de palabras de 8 bits.",
			"rawText": "Deben haber 2k palabras posibles (2^11) con salida de palabras de 8 bits.",
			"baseline": 25,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Deben haber 2k palabras posibles (2^11) con salida de palabras de 8 bits."
		},
		{
			"type": "text",
			"version": 312,
			"versionNonce": 1926085564,
			"isDeleted": false,
			"id": "anbNbWym",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2053.139016879035,
			"y": -177.22599089470657,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 509,
			"height": 134,
			"seed": 566487788,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1662511223449,
			"link": null,
			"locked": false,
			"fontSize": 28,
			"fontFamily": 3,
			"text": "\nchar rightShift(char c, int d){\n    return c >> d;\n}",
			"rawText": "\nchar rightShift(char c, int d){\n    return c >> d;\n}",
			"baseline": 128,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "\nchar rightShift(char c, int d){\n    return c >> d;\n}"
		},
		{
			"type": "freedraw",
			"version": 122,
			"versionNonce": 919203332,
			"isDeleted": false,
			"id": "HK-4my25tltCGzp5wFOaW",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2626.8770660994765,
			"y": -123.80316418376094,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 18.824525264345993,
			"height": 55.65503808255835,
			"seed": 985077588,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223449,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.6368880911268207,
					-4.910726716657848
				],
				[
					3.2737761822531866,
					-7.366090074986801
				],
				[
					4.910726716657791,
					-8.18456534218916
				],
				[
					7.366058853348022,
					-11.458372746081352
				],
				[
					10.639897478878993,
					-14.732211371612664
				],
				[
					13.913736104410418,
					-15.55065541717596
				],
				[
					17.18757472994139,
					-14.732211371612664
				],
				[
					18.0060187755048,
					-11.458372746081352
				],
				[
					18.0060187755048,
					-5.729201983860207
				],
				[
					16.369130684378433,
					3.273838625531255
				],
				[
					12.276848013284052,
					12.276848013283711
				],
				[
					7.366058853348022,
					21.279888622675173
				],
				[
					3.2737761822531866,
					28.645978697661974
				],
				[
					0.8184440455634103,
					32.738261368756525
				],
				[
					-0.8185064888411944,
					35.19362472708548
				],
				[
					-0.8185064888411944,
					36.01209999428784
				],
				[
					-0.8185064888411944,
					36.830544039851134
				],
				[
					0,
					36.830544039851134
				],
				[
					0.8184440455634103,
					36.830544039851134
				],
				[
					1.6368880911268207,
					36.830544039851134
				],
				[
					2.4553321366897762,
					37.649019307053436
				],
				[
					3.2737761822531866,
					38.46746335261673
				],
				[
					2.4553321366897762,
					39.28590739818003
				],
				[
					1.6368880911268207,
					39.28590739818003
				],
				[
					1.6368880911268207,
					40.10438266538239
				],
				[
					1.6368880911268207,
					40.10438266538239
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0029296875,
				0.3955078125,
				0.4453125,
				0.4560546875,
				0.462890625,
				0.4658203125,
				0.4619140625,
				0.4619140625,
				0.462890625,
				0.4658203125,
				0.46484375,
				0.462890625,
				0.4619140625,
				0.462890625,
				0.4697265625,
				0.484375,
				0.5,
				0.5458984375,
				0.5615234375,
				0.564453125,
				0.5634765625,
				0.564453125,
				0.55859375,
				0.4970703125,
				0.275390625,
				0.1669921875,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 103,
			"versionNonce": 1704387644,
			"isDeleted": false,
			"id": "Q9rAr_5NzP-0tkfxcrszo",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2625.240115565072,
			"y": -68.96657014676589,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0.8184440455634103,
			"height": 1.6368880911266501,
			"seed": 864941140,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223449,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.8184440455634103,
					0.8184440455633535
				],
				[
					0.8184440455634103,
					0
				],
				[
					0.8184440455634103,
					-0.8184440455632966
				],
				[
					0,
					-0.8184440455632966
				],
				[
					0.8184440455634103,
					0
				],
				[
					0,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.00390625,
				0.3203125,
				0.8212890625,
				0.798828125,
				0.20703125,
				0.0068359375,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 120,
			"versionNonce": 249924996,
			"isDeleted": false,
			"id": "Kfi12jfcKldDrHn-HTWD4",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2653.886094262734,
			"y": -123.80316418376094,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 20.461413355472814,
			"height": 49.92583609869814,
			"seed": 314987756,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223449,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-0.8184440455634103,
					-2.4553633583289525
				],
				[
					0.8184440455634103,
					-4.910726716657848
				],
				[
					0.8184440455634103,
					-6.547646029423504
				],
				[
					2.455394579968015,
					-9.003009387752456
				],
				[
					3.2738386255309706,
					-11.458372746081352
				],
				[
					7.366121296625806,
					-15.55065541717596
				],
				[
					10.639959922157232,
					-18.00604999714392
				],
				[
					14.732242593251613,
					-18.824494042707215
				],
				[
					17.18757472994139,
					-18.00604999714392
				],
				[
					19.642969309909404,
					-15.55065541717596
				],
				[
					19.642969309909404,
					-10.639928700518055
				],
				[
					18.006081218783038,
					-2.4553633583289525
				],
				[
					14.732242593251613,
					5.729201983860207
				],
				[
					11.458403967720642,
					12.276848013283711
				],
				[
					9.821515876593821,
					18.00604999714392
				],
				[
					7.366121296625806,
					22.09833266823847
				],
				[
					5.729233205498986,
					24.553696026567422
				],
				[
					5.729233205498986,
					25.372171293769725
				],
				[
					4.910726716657791,
					26.19061533933302
				],
				[
					4.910726716657791,
					27.009059384896318
				],
				[
					4.910726716657791,
					27.827534652098677
				],
				[
					4.910726716657791,
					29.464453964864333
				],
				[
					4.910726716657791,
					31.101342055990926
				],
				[
					4.910726716657791,
					31.101342055990926
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.001953125,
				0.42578125,
				0.5625,
				0.603515625,
				0.62890625,
				0.6337890625,
				0.640625,
				0.6474609375,
				0.654296875,
				0.6611328125,
				0.6640625,
				0.6640625,
				0.6630859375,
				0.6669921875,
				0.66796875,
				0.669921875,
				0.67578125,
				0.6826171875,
				0.68359375,
				0.6826171875,
				0.64453125,
				0.416015625,
				0.1572265625,
				0.005859375,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 104,
			"versionNonce": 1713831100,
			"isDeleted": false,
			"id": "L4c1avaaQ15JbUKPaylY7",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2654.7045383082973,
			"y": -75.5142161761894,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1.6369505344046047,
			"height": 2.4553633583289525,
			"seed": 795776364,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223449,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.8185064888411944,
					0.8184440455633535
				],
				[
					1.6369505344046047,
					0.8184440455633535
				],
				[
					0.8185064888411944,
					0.8184440455633535
				],
				[
					0,
					0.8184440455633535
				],
				[
					0,
					1.6369193127656558
				],
				[
					0,
					2.4553633583289525
				],
				[
					0,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.00390625,
				0.67578125,
				0.9951171875,
				0.9951171875,
				0.28515625,
				0.0703125,
				0.009765625,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 127,
			"versionNonce": 828456196,
			"isDeleted": false,
			"id": "5LBQsQfLa8delim7pInEP",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1990.9363015454137,
			"y": -113.16323548324283,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 16.36913068437798,
			"height": 50.744311365900444,
			"seed": 940028396,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223449,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-0.8184440455634103,
					8.18456534218916
				],
				[
					-1.6369193127657127,
					13.09532328048607
				],
				[
					-2.4553633583286683,
					18.824525264346278
				],
				[
					-4.092282671094381,
					26.19061533933308
				],
				[
					-5.729201983860094,
					31.101373277629932
				],
				[
					-7.3660900749864595,
					38.46746335261679
				],
				[
					-7.3660900749864595,
					41.741301978148044
				],
				[
					-8.184565342189217,
					46.65202869480589
				],
				[
					-8.184565342189217,
					49.107392053134845
				],
				[
					-8.184565342189217,
					49.92586732033715
				],
				[
					-8.184565342189217,
					50.744311365900444
				],
				[
					-7.3660900749864595,
					50.744311365900444
				],
				[
					-4.910726716657791,
					49.92586732033715
				],
				[
					-1.6369193127657127,
					48.28894800757155
				],
				[
					0.8184752672023023,
					45.833584649242596
				],
				[
					3.2738386255314254,
					42.55974602371134
				],
				[
					4.910757938297138,
					39.28593861981909
				],
				[
					6.547646029423504,
					36.01209999428784
				],
				[
					7.366121296625806,
					33.556736635958885
				],
				[
					7.366121296625806,
					31.101373277629932
				],
				[
					6.547646029423504,
					30.28289801042763
				],
				[
					4.910757938297138,
					29.464453964864333
				],
				[
					1.6369193127657127,
					31.101373277629932
				],
				[
					-1.6369193127657127,
					31.919817323193286
				],
				[
					-4.910726716657791,
					33.556736635958885
				],
				[
					-6.547646029423504,
					34.37518068152218
				],
				[
					-7.3660900749864595,
					34.37518068152218
				],
				[
					-8.184565342189217,
					34.37518068152218
				],
				[
					-8.184565342189217,
					33.556736635958885
				],
				[
					-9.003009387752172,
					32.73826136875658
				],
				[
					-9.003009387752172,
					32.73826136875658
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.00390625,
				0.2294921875,
				0.2919921875,
				0.3505859375,
				0.416015625,
				0.4638671875,
				0.5498046875,
				0.583984375,
				0.6103515625,
				0.6171875,
				0.6171875,
				0.6162109375,
				0.6123046875,
				0.6123046875,
				0.6123046875,
				0.611328125,
				0.611328125,
				0.61328125,
				0.619140625,
				0.625,
				0.6298828125,
				0.6455078125,
				0.677734375,
				0.7041015625,
				0.716796875,
				0.720703125,
				0.7041015625,
				0.6630859375,
				0.48046875,
				0.0419921875,
				0.001953125,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 114,
			"versionNonce": 2116027708,
			"isDeleted": false,
			"id": "hqBCKN97H_asXW67exj8U",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1990.1178574998503,
			"y": -147.53838494312595,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 33.55673663595917,
			"height": 126.0422875367293,
			"seed": 1372293844,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223449,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					5.729201983860548,
					0
				],
				[
					7.366090074986914,
					0.8184440455632966
				],
				[
					9.82148465495493,
					2.4553633583288956
				],
				[
					12.276848013284052,
					6.547646029423504
				],
				[
					14.73221137161272,
					11.458372746081352
				],
				[
					20.46141335547327,
					23.735220759365063
				],
				[
					23.735220759365347,
					33.55670541431982
				],
				[
					28.64597869766203,
					49.10739205313479
				],
				[
					31.919786101554564,
					67.1134108286397
				],
				[
					32.738261368756866,
					83.48254151301796
				],
				[
					30.282898010427743,
					98.21478410626963
				],
				[
					24.55369602656765,
					109.67315685235098
				],
				[
					17.187574729941844,
					117.85772219454014
				],
				[
					9.82148465495493,
					122.768480132837
				],
				[
					4.092282671094836,
					125.22384349116601
				],
				[
					0.8184440455634103,
					126.0422875367293
				],
				[
					-0.8184752672023023,
					123.5869241784003
				],
				[
					-0.8184752672023023,
					123.5869241784003
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.001953125,
				0.4482421875,
				0.5517578125,
				0.6728515625,
				0.744140625,
				0.7802734375,
				0.8720703125,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9951171875,
				0.9365234375,
				0.6318359375,
				0.3583984375,
				0.11328125,
				0.0009765625,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 97,
			"versionNonce": 2008743044,
			"isDeleted": false,
			"id": "Pn1fm0hbiOmW6GxPagBqe",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 2198.0058296801094,
			"y": 147.9244231293609,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 0.0001,
			"height": 0.0001,
			"seed": 1304154580,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223449,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.0001,
					0.0001
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": true,
			"pressures": []
		},
		{
			"type": "image",
			"version": 140,
			"versionNonce": 853802428,
			"isDeleted": false,
			"id": "CB3CEew0EcJRWTlMoPdmp",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1951.7474461517886,
			"y": 63.62339073832106,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"width": 838.3145278775763,
			"height": 441.9665284782134,
			"seed": 1733784940,
			"groupIds": [],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511223449,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "87422d731f16c7219d4fe2378d68bb0468b3158b",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "text",
			"version": 1331,
			"versionNonce": 1538313220,
			"isDeleted": false,
			"id": "VqHqpN3P",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 1981.1147076147204,
			"y": 540.8774015572786,
			"strokeColor": "#000000",
			"backgroundColor": "transparent",
			"width": 1087,
			"height": 372,
			"seed": 895641964,
			"groupIds": [],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1662511223449,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "Como entrada se debe distinguir entre todos los\ncaracteres de ASCII, en este caso 256, lo que \nimplica que seran necesarios 8 bits de entrada.\n\nA  su vez es necesario poder realizar una salida distinta para \ncada combiancion de pixeles que represena una letra,\nesto es 64 bits de salida (8 por cada columna)\n\nb) la rom se construiria conectando \"en paralelo\"\n8 roms de 1k8 de las cuales se ignoraran 2 bits de su entrada.\n\nSi se interpreta que lo que se quiere es tener como input el codigo ACII del caracter Y su columna,\ncaso en el cual la salida serían los 8 bits de la representacion de la columna, se requeririan 11bits de inputs\n(2k inputs) y 8 bits de salida por lo que habria que construir un chip de tipo 2kx8 a partir de dos \nde tipo 1kx8",
			"rawText": "Como entrada se debe distinguir entre todos los\ncaracteres de ASCII, en este caso 256, lo que \nimplica que seran necesarios 8 bits de entrada.\n\nA  su vez es necesario poder realizar una salida distinta para \ncada combiancion de pixeles que represena una letra,\nesto es 64 bits de salida (8 por cada columna)\n\nb) la rom se construiria conectando \"en paralelo\"\n8 roms de 1k8 de las cuales se ignoraran 2 bits de su entrada.\n\nSi se interpreta que lo que se quiere es tener como input el codigo ACII del caracter Y su columna,\ncaso en el cual la salida serían los 8 bits de la representacion de la columna, se requeririan 11bits de inputs\n(2k inputs) y 8 bits de salida por lo que habria que construir un chip de tipo 2kx8 a partir de dos \nde tipo 1kx8",
			"baseline": 365,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "Como entrada se debe distinguir entre todos los\ncaracteres de ASCII, en este caso 256, lo que \nimplica que seran necesarios 8 bits de entrada.\n\nA  su vez es necesario poder realizar una salida distinta para \ncada combiancion de pixeles que represena una letra,\nesto es 64 bits de salida (8 por cada columna)\n\nb) la rom se construiria conectando \"en paralelo\"\n8 roms de 1k8 de las cuales se ignoraran 2 bits de su entrada.\n\nSi se interpreta que lo que se quiere es tener como input el codigo ACII del caracter Y su columna,\ncaso en el cual la salida serían los 8 bits de la representacion de la columna, se requeririan 11bits de inputs\n(2k inputs) y 8 bits de salida por lo que habria que construir un chip de tipo 2kx8 a partir de dos \nde tipo 1kx8"
		},
		{
			"type": "image",
			"version": 116,
			"versionNonce": 1760638084,
			"isDeleted": false,
			"id": "24KvrCgPEx2H3OVacmwoG",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3334.7308734105873,
			"y": -557.8474996783261,
			"strokeColor": "transparent",
			"backgroundColor": "transparent",
			"width": 933.333333333333,
			"height": 123.14814814814811,
			"seed": 1714133764,
			"groupIds": [
				"Ekp0tPHF2zeLqGVQ7i5mE"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511257127,
			"link": null,
			"locked": false,
			"status": "pending",
			"fileId": "bf04731834e2a478e8c1c5002d0d720c51a89e10",
			"scale": [
				1,
				1
			]
		},
		{
			"type": "rectangle",
			"version": 243,
			"versionNonce": 1095583164,
			"isDeleted": false,
			"id": "fLH6VPxf3znlYQNApEjdT",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3938.455684010344,
			"y": -234.86963509499213,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 256,
			"height": 248.80001831054693,
			"seed": 1157711804,
			"groupIds": [
				"Ekp0tPHF2zeLqGVQ7i5mE"
			],
			"strokeSharpness": "sharp",
			"boundElements": [
				{
					"id": "vrGokl0i",
					"type": "text"
				}
			],
			"updated": 1662511257127,
			"link": null,
			"locked": false
		},
		{
			"type": "text",
			"version": 181,
			"versionNonce": 962593796,
			"isDeleted": false,
			"id": "vrGokl0i",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3943.455684010344,
			"y": -122.96962593971867,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 246,
			"height": 25,
			"seed": 174916156,
			"groupIds": [
				"Ekp0tPHF2zeLqGVQ7i5mE"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1662511257127,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "32kx16",
			"rawText": "32kx16",
			"baseline": 18,
			"textAlign": "center",
			"verticalAlign": "middle",
			"containerId": "fLH6VPxf3znlYQNApEjdT",
			"originalText": "32kx16"
		},
		{
			"type": "line",
			"version": 368,
			"versionNonce": 261434940,
			"isDeleted": false,
			"id": "n5rSujEY0vuLz6k0TbcSG",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3276.5444610374466,
			"y": -153.45491713016412,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 655.84833122286,
			"height": 0,
			"seed": 1790006404,
			"groupIds": [
				"Ekp0tPHF2zeLqGVQ7i5mE"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511257127,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					655.84833122286,
					0
				]
			]
		},
		{
			"type": "freedraw",
			"version": 184,
			"versionNonce": 1112073092,
			"isDeleted": false,
			"id": "55_zMoH2F2jWteSYcogPD",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3420.8556473892504,
			"y": -182.46961068092963,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 15.199981689453125,
			"height": 34.399993896484375,
			"seed": 58818620,
			"groupIds": [
				"Ekp0tPHF2zeLqGVQ7i5mE"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511257127,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.79998779296875,
					1.600006103515625
				],
				[
					0.79998779296875,
					0.79998779296875
				],
				[
					0.79998779296875,
					0
				],
				[
					1.5999755859375,
					-0.79998779296875
				],
				[
					2.399993896484375,
					-1.600006103515625
				],
				[
					4,
					-2.399993896484375
				],
				[
					4,
					-3.20001220703125
				],
				[
					5.5999755859375,
					-4
				],
				[
					7.199981689453125,
					-5.600006103515625
				],
				[
					8.79998779296875,
					-7.20001220703125
				],
				[
					10.399993896484375,
					-8.79998779296875
				],
				[
					11.199981689453125,
					-9.600006103515625
				],
				[
					12.79998779296875,
					-11.20001220703125
				],
				[
					13.5999755859375,
					-12
				],
				[
					14.399993896484375,
					-12
				],
				[
					14.399993896484375,
					-12.79998779296875
				],
				[
					15.199981689453125,
					-12.79998779296875
				],
				[
					15.199981689453125,
					-11.20001220703125
				],
				[
					15.199981689453125,
					-8.79998779296875
				],
				[
					13.5999755859375,
					-4
				],
				[
					12.79998779296875,
					0
				],
				[
					12,
					4.79998779296875
				],
				[
					11.199981689453125,
					7.20001220703125
				],
				[
					11.199981689453125,
					10.399993896484375
				],
				[
					10.399993896484375,
					13.600006103515625
				],
				[
					9.5999755859375,
					16
				],
				[
					9.5999755859375,
					18.399993896484375
				],
				[
					8.79998779296875,
					20
				],
				[
					8.79998779296875,
					20.79998779296875
				],
				[
					9.5999755859375,
					20.79998779296875
				],
				[
					9.5999755859375,
					21.600006103515625
				],
				[
					10.399993896484375,
					21.600006103515625
				],
				[
					11.199981689453125,
					21.600006103515625
				],
				[
					11.199981689453125,
					21.600006103515625
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0009765625,
				0.31640625,
				0.3525390625,
				0.4033203125,
				0.4140625,
				0.421875,
				0.4384765625,
				0.4443359375,
				0.4677734375,
				0.4873046875,
				0.501953125,
				0.5087890625,
				0.5126953125,
				0.5146484375,
				0.5146484375,
				0.5166015625,
				0.517578125,
				0.5234375,
				0.5478515625,
				0.576171875,
				0.5986328125,
				0.6064453125,
				0.6142578125,
				0.62109375,
				0.626953125,
				0.6328125,
				0.6318359375,
				0.6103515625,
				0.537109375,
				0.4619140625,
				0.4169921875,
				0.3134765625,
				0.1484375,
				0.0234375,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 197,
			"versionNonce": 231474876,
			"isDeleted": false,
			"id": "weD9DtdsuXv0-zHh7aiTR",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3467.255641285735,
			"y": -189.66962288796088,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 16.79998779296875,
			"height": 21.5999755859375,
			"seed": 554412348,
			"groupIds": [
				"Ekp0tPHF2zeLqGVQ7i5mE"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511257127,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-0.800018310546875,
					0
				],
				[
					-1.600006103515625,
					0.800018310546875
				],
				[
					-2.399993896484375,
					0.800018310546875
				],
				[
					-4,
					0.800018310546875
				],
				[
					-4.800018310546875,
					0
				],
				[
					-5.600006103515625,
					0
				],
				[
					-6.399993896484375,
					-0.79998779296875
				],
				[
					-7.20001220703125,
					-0.79998779296875
				],
				[
					-7.20001220703125,
					-1.5999755859375
				],
				[
					-7.20001220703125,
					-0.79998779296875
				],
				[
					-8,
					-0.79998779296875
				],
				[
					-8,
					0
				],
				[
					-8,
					0.800018310546875
				],
				[
					-8.800018310546875,
					1.600006103515625
				],
				[
					-9.600006103515625,
					3.20001220703125
				],
				[
					-10.399993896484375,
					4
				],
				[
					-10.399993896484375,
					5.600006103515625
				],
				[
					-11.20001220703125,
					6.4000244140625
				],
				[
					-11.20001220703125,
					7.20001220703125
				],
				[
					-12,
					7.20001220703125
				],
				[
					-12,
					8
				],
				[
					-11.20001220703125,
					8
				],
				[
					-10.399993896484375,
					8
				],
				[
					-9.600006103515625,
					8
				],
				[
					-8.800018310546875,
					8
				],
				[
					-7.20001220703125,
					8
				],
				[
					-6.399993896484375,
					8
				],
				[
					-4.800018310546875,
					8
				],
				[
					-3.20001220703125,
					8
				],
				[
					-1.600006103515625,
					8.800018310546875
				],
				[
					-0.800018310546875,
					9.600006103515625
				],
				[
					0,
					10.4000244140625
				],
				[
					0,
					11.20001220703125
				],
				[
					0.79998779296875,
					12.800018310546875
				],
				[
					0,
					13.600006103515625
				],
				[
					0,
					15.20001220703125
				],
				[
					-0.800018310546875,
					16
				],
				[
					-2.399993896484375,
					17.600006103515625
				],
				[
					-4,
					19.20001220703125
				],
				[
					-4.800018310546875,
					19.20001220703125
				],
				[
					-7.20001220703125,
					20
				],
				[
					-8.800018310546875,
					20
				],
				[
					-11.20001220703125,
					20
				],
				[
					-12.800018310546875,
					19.20001220703125
				],
				[
					-14.399993896484375,
					19.20001220703125
				],
				[
					-16,
					19.20001220703125
				],
				[
					-16,
					19.20001220703125
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.001953125,
				0.232421875,
				0.3359375,
				0.3828125,
				0.4287109375,
				0.44140625,
				0.4443359375,
				0.451171875,
				0.4599609375,
				0.478515625,
				0.482421875,
				0.484375,
				0.486328125,
				0.486328125,
				0.4853515625,
				0.4853515625,
				0.484375,
				0.4833984375,
				0.48046875,
				0.4755859375,
				0.470703125,
				0.4638671875,
				0.4296875,
				0.4306640625,
				0.4306640625,
				0.4306640625,
				0.4296875,
				0.4296875,
				0.4306640625,
				0.4365234375,
				0.44921875,
				0.4599609375,
				0.478515625,
				0.4931640625,
				0.515625,
				0.54296875,
				0.55859375,
				0.576171875,
				0.5888671875,
				0.6025390625,
				0.6103515625,
				0.619140625,
				0.623046875,
				0.6201171875,
				0.5947265625,
				0.5439453125,
				0.333984375,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 183,
			"versionNonce": 166318852,
			"isDeleted": false,
			"id": "Vd7gn5yzJVDG_g5GPWGie",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3509.6556656997973,
			"y": -188.869604577414,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 9.5999755859375,
			"height": 25.600006103515625,
			"seed": 126635140,
			"groupIds": [
				"Ekp0tPHF2zeLqGVQ7i5mE"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511257127,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.79998779296875,
					0.79998779296875
				],
				[
					0.79998779296875,
					1.600006103515625
				],
				[
					0,
					2.399993896484375
				],
				[
					0,
					4
				],
				[
					-0.800048828125,
					5.600006103515625
				],
				[
					-1.60003662109375,
					8
				],
				[
					-2.4000244140625,
					9.600006103515625
				],
				[
					-2.4000244140625,
					12
				],
				[
					-3.20001220703125,
					15.199981689453125
				],
				[
					-3.20001220703125,
					17.600006103515625
				],
				[
					-4,
					24
				],
				[
					-4,
					24.79998779296875
				],
				[
					-4,
					25.600006103515625
				],
				[
					-3.20001220703125,
					25.600006103515625
				],
				[
					-2.4000244140625,
					25.600006103515625
				],
				[
					-0.800048828125,
					24.79998779296875
				],
				[
					0.79998779296875,
					24
				],
				[
					1.5999755859375,
					23.199981689453125
				],
				[
					3.199951171875,
					21.600006103515625
				],
				[
					4,
					21.600006103515625
				],
				[
					4.79998779296875,
					20.79998779296875
				],
				[
					5.5999755859375,
					19.199981689453125
				],
				[
					5.5999755859375,
					18.399993896484375
				],
				[
					5.5999755859375,
					17.600006103515625
				],
				[
					4.79998779296875,
					17.600006103515625
				],
				[
					4,
					17.600006103515625
				],
				[
					3.199951171875,
					17.600006103515625
				],
				[
					2.39996337890625,
					17.600006103515625
				],
				[
					1.5999755859375,
					17.600006103515625
				],
				[
					0.79998779296875,
					17.600006103515625
				],
				[
					0.79998779296875,
					18.399993896484375
				],
				[
					1.5999755859375,
					18.399993896484375
				],
				[
					1.5999755859375,
					18.399993896484375
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.00390625,
				0.2626953125,
				0.3642578125,
				0.4052734375,
				0.4453125,
				0.470703125,
				0.5,
				0.51953125,
				0.5390625,
				0.5712890625,
				0.58984375,
				0.59375,
				0.587890625,
				0.578125,
				0.517578125,
				0.5068359375,
				0.486328125,
				0.48046875,
				0.4794921875,
				0.4755859375,
				0.4755859375,
				0.478515625,
				0.4833984375,
				0.48828125,
				0.5009765625,
				0.517578125,
				0.544921875,
				0.5576171875,
				0.5576171875,
				0.5400390625,
				0.3056640625,
				0.0634765625,
				0.0341796875,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 159,
			"versionNonce": 1083428668,
			"isDeleted": false,
			"id": "Y9uer6eqTK3OkyiGJbhAU",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3524.0556290787035,
			"y": -166.46961068092963,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 0.79998779296875,
			"height": 5.600006103515625,
			"seed": 607690300,
			"groupIds": [
				"Ekp0tPHF2zeLqGVQ7i5mE"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511257127,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.79998779296875,
					0
				],
				[
					0.79998779296875,
					-0.79998779296875
				],
				[
					0.79998779296875,
					-1.600006103515625
				],
				[
					0.79998779296875,
					-2.399993896484375
				],
				[
					0.79998779296875,
					-3.20001220703125
				],
				[
					0.79998779296875,
					-4.79998779296875
				],
				[
					0.79998779296875,
					-5.600006103515625
				],
				[
					0,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0009765625,
				0.126953125,
				0.5263671875,
				0.525390625,
				0.494140625,
				0.42578125,
				0.2294921875,
				0.0947265625,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 157,
			"versionNonce": 515953284,
			"isDeleted": false,
			"id": "wdkBiY1Hsw_wrUnrnY4mq",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3525.6556656997973,
			"y": -176.06961678444526,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 1.5999755859375,
			"height": 2.399993896484375,
			"seed": 1703395588,
			"groupIds": [
				"Ekp0tPHF2zeLqGVQ7i5mE"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511257127,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-0.79998779296875
				],
				[
					0,
					-1.600006103515625
				],
				[
					0.79998779296875,
					-1.600006103515625
				],
				[
					0.79998779296875,
					-2.399993896484375
				],
				[
					1.5999755859375,
					-2.399993896484375
				],
				[
					0,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0009765625,
				0.212890625,
				0.2666015625,
				0.126953125,
				0.095703125,
				0.03515625,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 170,
			"versionNonce": 1213106108,
			"isDeleted": false,
			"id": "Ym6RzUs-s70RAJqnAsf_S",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3537.6556656997973,
			"y": -188.869604577414,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 11.20001220703125,
			"height": 22.399993896484375,
			"seed": 12272444,
			"groupIds": [
				"Ekp0tPHF2zeLqGVQ7i5mE"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511257127,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					4
				],
				[
					-0.800048828125,
					5.600006103515625
				],
				[
					-1.60003662109375,
					9.600006103515625
				],
				[
					-2.4000244140625,
					11.199981689453125
				],
				[
					-3.20001220703125,
					14.399993896484375
				],
				[
					-3.20001220703125,
					16
				],
				[
					-3.20001220703125,
					17.600006103515625
				],
				[
					-3.20001220703125,
					19.199981689453125
				],
				[
					-3.20001220703125,
					20
				],
				[
					-2.4000244140625,
					21.600006103515625
				],
				[
					-0.800048828125,
					21.600006103515625
				],
				[
					0,
					22.399993896484375
				],
				[
					1.5999755859375,
					21.600006103515625
				],
				[
					3.199951171875,
					20.79998779296875
				],
				[
					4.79998779296875,
					20
				],
				[
					6.39996337890625,
					19.199981689453125
				],
				[
					7.199951171875,
					18.399993896484375
				],
				[
					7.199951171875,
					17.600006103515625
				],
				[
					8,
					17.600006103515625
				],
				[
					8,
					17.600006103515625
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0029296875,
				0.3095703125,
				0.3818359375,
				0.4912109375,
				0.5302734375,
				0.5693359375,
				0.5869140625,
				0.5966796875,
				0.603515625,
				0.6025390625,
				0.59375,
				0.5595703125,
				0.5146484375,
				0.4189453125,
				0.333984375,
				0.216796875,
				0.1064453125,
				0.0458984375,
				0.021484375,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 158,
			"versionNonce": 260825604,
			"isDeleted": false,
			"id": "EGdOSOhrhjbGJomYcxd6g",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3544.0556290787035,
			"y": -176.06961678444526,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 8.79998779296875,
			"height": 0.800018310546875,
			"seed": 695943356,
			"groupIds": [
				"Ekp0tPHF2zeLqGVQ7i5mE"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511257127,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-2.39996337890625,
					0
				],
				[
					-4,
					0.800018310546875
				],
				[
					-6.39996337890625,
					0.800018310546875
				],
				[
					-8.79998779296875,
					0
				],
				[
					-8,
					0
				],
				[
					-7.20001220703125,
					0
				],
				[
					0,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0,
				0.1953125,
				0.271484375,
				0.314453125,
				0.1884765625,
				0.0546875,
				0.0029296875,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 177,
			"versionNonce": 1763586108,
			"isDeleted": false,
			"id": "DmGs3nl8vSGWZzFXeapGn",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3556.0556290787035,
			"y": -179.26959847389838,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 9.60003662109375,
			"height": 12,
			"seed": 1848593212,
			"groupIds": [
				"Ekp0tPHF2zeLqGVQ7i5mE"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511257127,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-0.79998779296875,
					0.79998779296875
				],
				[
					-1.5999755859375,
					1.5999755859375
				],
				[
					-2.39996337890625,
					1.5999755859375
				],
				[
					-3.20001220703125,
					2.399993896484375
				],
				[
					-4.79998779296875,
					3.199981689453125
				],
				[
					-4.79998779296875,
					4
				],
				[
					-5.5999755859375,
					4
				],
				[
					-4.79998779296875,
					4.79998779296875
				],
				[
					-4,
					5.5999755859375
				],
				[
					-3.20001220703125,
					5.5999755859375
				],
				[
					-2.39996337890625,
					6.399993896484375
				],
				[
					-0.79998779296875,
					6.399993896484375
				],
				[
					0,
					6.399993896484375
				],
				[
					0.79998779296875,
					7.199981689453125
				],
				[
					1.60003662109375,
					7.199981689453125
				],
				[
					1.60003662109375,
					8
				],
				[
					1.60003662109375,
					8.79998779296875
				],
				[
					0.79998779296875,
					8.79998779296875
				],
				[
					-0.79998779296875,
					10.399993896484375
				],
				[
					-1.5999755859375,
					10.399993896484375
				],
				[
					-2.39996337890625,
					10.399993896484375
				],
				[
					-4.79998779296875,
					11.199981689453125
				],
				[
					-5.5999755859375,
					12
				],
				[
					-7.20001220703125,
					12
				],
				[
					-8,
					12
				],
				[
					-8,
					11.199981689453125
				],
				[
					-8,
					11.199981689453125
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.00390625,
				0.23046875,
				0.28125,
				0.3134765625,
				0.328125,
				0.3349609375,
				0.3369140625,
				0.337890625,
				0.33984375,
				0.3447265625,
				0.345703125,
				0.345703125,
				0.345703125,
				0.345703125,
				0.3466796875,
				0.3515625,
				0.3642578125,
				0.388671875,
				0.3974609375,
				0.40625,
				0.408203125,
				0.4091796875,
				0.4033203125,
				0.3701171875,
				0.3095703125,
				0.234375,
				0.0068359375,
				0
			]
		},
		{
			"type": "line",
			"version": 390,
			"versionNonce": 1665728900,
			"isDeleted": false,
			"id": "I--ePgHsnLBkEMP3Gqcm9",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3274.455684010344,
			"y": -54.350571528326824,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 667.8574716748726,
			"height": 0,
			"seed": 858955652,
			"groupIds": [
				"Ekp0tPHF2zeLqGVQ7i5mE"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511257127,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					667.8574716748726,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 470,
			"versionNonce": 316983484,
			"isDeleted": false,
			"id": "h8ys2V23hqCKqC_-zqWxu",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3279.445237932091,
			"y": 1.930352697976673,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 660.244194483977,
			"height": 0,
			"seed": 1162257340,
			"groupIds": [
				"Ekp0tPHF2zeLqGVQ7i5mE"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511257127,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					660.244194483977,
					0
				]
			]
		},
		{
			"type": "freedraw",
			"version": 306,
			"versionNonce": 288764164,
			"isDeleted": false,
			"id": "99p8RI65xVDq1cGpGzCY8",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3305.254058863353,
			"y": -79.09461704360898,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 11.97441527168586,
			"height": 15.167535832922779,
			"seed": 1730012804,
			"groupIds": [
				"Ekp0tPHF2zeLqGVQ7i5mE"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511257127,
			"link": null,
			"locked": false,
			"points": [
				[
					-0.023907462947190733,
					0
				],
				[
					-0.023907462947190733,
					0.798280140309227
				],
				[
					-0.8221876032564162,
					0.798280140309227
				],
				[
					-1.620467743565644,
					0.798280140309227
				],
				[
					-2.4187478838748704,
					0.798280140309227
				],
				[
					-3.2170280241840965,
					0.798280140309227
				],
				[
					-4.015369069364028,
					1.5965907330538047
				],
				[
					-4.813649209673254,
					1.5965907330538047
				],
				[
					-5.611929349982481,
					2.3948708733630317
				],
				[
					-7.208520083036287,
					3.1931510136722614
				],
				[
					-8.006800223345516,
					4.7897417467260635
				],
				[
					-8.805110816090087,
					6.386332479779867
				],
				[
					-9.603390956399323,
					7.184612620089101
				],
				[
					-10.401701549143887,
					8.781203353142907
				],
				[
					-10.401701549143887,
					10.377794086196715
				],
				[
					-11.199981689453125,
					11.974384819250503
				],
				[
					-10.401701549143887,
					12.772664959559734
				],
				[
					-10.401701549143887,
					13.570975552304326
				],
				[
					-10.401701549143887,
					14.36925569261354
				],
				[
					-8.805110816090087,
					15.167535832922779
				],
				[
					-8.006800223345516,
					15.167535832922779
				],
				[
					-6.410239942727058,
					14.36925569261354
				],
				[
					-5.611929349982481,
					13.570975552304326
				],
				[
					-4.015369069364028,
					12.772664959559734
				],
				[
					-3.2170280241840965,
					12.772664959559734
				],
				[
					-1.620467743565644,
					12.772664959559734
				],
				[
					-1.620467743565644,
					13.570975552304326
				],
				[
					-0.8221876032564162,
					14.36925569261354
				],
				[
					-0.023907462947190733,
					14.36925569261354
				],
				[
					0.7744335822327352,
					15.167535832922779
				],
				[
					0.7744335822327352,
					15.167535832922779
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0009765625,
				0.1669921875,
				0.302734375,
				0.3154296875,
				0.3271484375,
				0.3447265625,
				0.3623046875,
				0.37890625,
				0.392578125,
				0.40625,
				0.41015625,
				0.412109375,
				0.412109375,
				0.4130859375,
				0.4130859375,
				0.4130859375,
				0.4130859375,
				0.4140625,
				0.4140625,
				0.412109375,
				0.41015625,
				0.400390625,
				0.3916015625,
				0.3779296875,
				0.3720703125,
				0.3232421875,
				0.302734375,
				0.197265625,
				0.076171875,
				0.0224609375,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 302,
			"versionNonce": 1766084924,
			"isDeleted": false,
			"id": "VInLAW4keO_NC1GYF9n1V",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3322.8114034513837,
			"y": -75.103155437192,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 8.781203353142908,
			"height": 10.377794086196717,
			"seed": 1832803972,
			"groupIds": [
				"Ekp0tPHF2zeLqGVQ7i5mE"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511257127,
			"link": null,
			"locked": false,
			"points": [
				[
					-0.018784439825841284,
					0
				],
				[
					-1.6154056253149986,
					0
				],
				[
					-3.2119659059334547,
					0.7982801403092277
				],
				[
					-4.010246046242681,
					0.7982801403092277
				],
				[
					-4.808526186551908,
					0.7982801403092277
				],
				[
					-5.606867231731843,
					1.5965907330538063
				],
				[
					-6.405147372041066,
					1.5965907330538063
				],
				[
					-5.606867231731843,
					1.5965907330538063
				],
				[
					-4.808526186551908,
					1.5965907330538063
				],
				[
					-4.010246046242681,
					2.394870873363032
				],
				[
					-3.2119659059334547,
					2.394870873363032
				],
				[
					-2.4136857656242268,
					2.394870873363032
				],
				[
					-1.6154056253149986,
					3.193151013672262
				],
				[
					-0.8170645801350688,
					3.9914616064168413
				],
				[
					-0.8170645801350688,
					4.789741746726064
				],
				[
					-0.018784439825841284,
					5.588052339470645
				],
				[
					-0.018784439825841284,
					7.184612620089105
				],
				[
					-0.8170645801350688,
					7.982923212833683
				],
				[
					-1.6154056253149986,
					7.982923212833683
				],
				[
					-3.2119659059334547,
					7.982923212833683
				],
				[
					-4.010246046242681,
					8.78120335314291
				],
				[
					-5.606867231731843,
					8.78120335314291
				],
				[
					-6.405147372041066,
					9.579513945887483
				],
				[
					-8.001707652659526,
					9.579513945887483
				],
				[
					-8.79998779296875,
					9.579513945887483
				],
				[
					-8.79998779296875,
					10.377794086196717
				],
				[
					-8.79998779296875,
					10.377794086196717
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.001953125,
				0.201171875,
				0.25390625,
				0.2646484375,
				0.2685546875,
				0.2705078125,
				0.271484375,
				0.271484375,
				0.271484375,
				0.271484375,
				0.2724609375,
				0.2724609375,
				0.275390625,
				0.27734375,
				0.2783203125,
				0.2822265625,
				0.3037109375,
				0.3095703125,
				0.310546875,
				0.3095703125,
				0.306640625,
				0.2734375,
				0.2265625,
				0.0693359375,
				0.013671875,
				0.001953125,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 301,
			"versionNonce": 2026991748,
			"isDeleted": false,
			"id": "zD8GPrqUwkukcwB2TsSvq",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3300.4557787230415,
			"y": -27.20561616018999,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 11.176074226505952,
			"height": 13.570975552304327,
			"seed": 1810360196,
			"groupIds": [
				"Ekp0tPHF2zeLqGVQ7i5mE"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511257127,
			"link": null,
			"locked": false,
			"points": [
				[
					-0.015369069364016403,
					0
				],
				[
					3.177812396743606,
					1.5965907330538058
				],
				[
					3.9760925370528253,
					3.19315101367226
				],
				[
					3.9760925370528253,
					4.7897417467260635
				],
				[
					3.9760925370528253,
					5.588052339470643
				],
				[
					3.9760925370528253,
					7.184612620089107
				],
				[
					2.379532256434369,
					8.781203353142908
				],
				[
					1.5812521161251463,
					10.377794086196717
				],
				[
					-0.015369069364016403,
					11.974384819250504
				],
				[
					-0.8136492096732463,
					12.77266495955974
				],
				[
					-2.4102399427270544,
					13.570975552304327
				],
				[
					-4.006830675780862,
					13.570975552304327
				],
				[
					-5.6034214088346745,
					12.77266495955974
				],
				[
					-6.401701549143898,
					11.974384819250504
				],
				[
					-7.199981689453125,
					10.377794086196717
				],
				[
					-7.199981689453125,
					9.57951394588748
				],
				[
					-6.401701549143898,
					7.184612620089107
				],
				[
					-5.6034214088346745,
					4.7897417467260635
				],
				[
					-4.805110816090092,
					3.19315101367226
				],
				[
					-3.2085200830362837,
					1.5965907330538058
				],
				[
					-1.6119598024178257,
					1.5965907330538058
				],
				[
					-0.8136492096732463,
					1.5965907330538058
				],
				[
					0.7829110709452091,
					1.5965907330538058
				],
				[
					2.379532256434369,
					2.3948708733630317
				],
				[
					-0.015369069364016403,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0048828125,
				0.21484375,
				0.30078125,
				0.3427734375,
				0.357421875,
				0.3701171875,
				0.3818359375,
				0.390625,
				0.4033203125,
				0.408203125,
				0.4150390625,
				0.4169921875,
				0.41796875,
				0.4189453125,
				0.419921875,
				0.419921875,
				0.4189453125,
				0.4150390625,
				0.40625,
				0.3740234375,
				0.3349609375,
				0.2783203125,
				0.15625,
				0.01171875,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 291,
			"versionNonce": 1268697532,
			"isDeleted": false,
			"id": "9YzBR1Dtz1qWEaJxku_uX",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3314.8148188869927,
			"y": -24.012465146517798,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 2.3949013257983847,
			"height": 15.167566285358133,
			"seed": 502534460,
			"groupIds": [
				"Ekp0tPHF2zeLqGVQ7i5mE"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511257127,
			"link": null,
			"locked": false,
			"points": [
				[
					-0.00512308826411571,
					0
				],
				[
					-0.00512308826411571,
					3.9914616064168396
				],
				[
					-0.00512308826411571,
					5.588052339470645
				],
				[
					-0.8034032285733419,
					7.184643072524446
				],
				[
					-0.8034032285733419,
					8.78123380557826
				],
				[
					-1.6017442737532726,
					10.377824538632051
				],
				[
					-1.6017442737532726,
					11.974384819250508
				],
				[
					-2.4000244140625,
					12.772695411995088
				],
				[
					-2.4000244140625,
					13.570975552304326
				],
				[
					-2.4000244140625,
					14.369286145048893
				],
				[
					-2.4000244140625,
					15.167566285358133
				],
				[
					-1.6017442737532726,
					15.167566285358133
				],
				[
					-1.6017442737532726,
					14.369286145048893
				],
				[
					-0.00512308826411571,
					12.772695411995088
				],
				[
					-0.00512308826411571,
					11.974384819250508
				],
				[
					-0.00512308826411571,
					11.974384819250508
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0,
				0.3603515625,
				0.4052734375,
				0.443359375,
				0.451171875,
				0.4541015625,
				0.453125,
				0.4453125,
				0.4384765625,
				0.416015625,
				0.2978515625,
				0.232421875,
				0.19921875,
				0.0322265625,
				0.001953125,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 288,
			"versionNonce": 1507377156,
			"isDeleted": false,
			"id": "4yVDOPBSbAJYpEiFcRD4_",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3325.2028284367107,
			"y": -24.012465146517812,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 7.982923212833683,
			"height": 1.5965907330538058,
			"seed": 379710596,
			"groupIds": [
				"Ekp0tPHF2zeLqGVQ7i5mE"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511257127,
			"link": null,
			"locked": false,
			"points": [
				[
					-0.01536900422125017,
					0
				],
				[
					0.7829720409586828,
					0
				],
				[
					-0.01536900422125017,
					0
				],
				[
					-0.813649144530476,
					0
				],
				[
					-1.6119292848397047,
					0
				],
				[
					-2.410209425148932,
					0
				],
				[
					-4.006830610638089,
					0.7983105927445789
				],
				[
					-4.80511075094732,
					0.7983105927445789
				],
				[
					-5.603390891256545,
					0.7983105927445789
				],
				[
					-6.401671031565774,
					0.7983105927445789
				],
				[
					-7.199951171875,
					1.5965907330538058
				],
				[
					-0.01536900422125017,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0078125,
				0.2255859375,
				0.279296875,
				0.345703125,
				0.3701171875,
				0.3798828125,
				0.3857421875,
				0.384765625,
				0.380859375,
				0.34765625,
				0.2587890625,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 284,
			"versionNonce": 1561735740,
			"isDeleted": false,
			"id": "uqU7O5UgMnyflq03JcpND",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3323.6079759390304,
			"y": -17.62610221430255,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 7.982923212833683,
			"height": 3.9914616064168413,
			"seed": 1734732036,
			"groupIds": [
				"Ekp0tPHF2zeLqGVQ7i5mE"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511257127,
			"link": null,
			"locked": false,
			"points": [
				[
					-0.017076787166317456,
					0
				],
				[
					-1.61363706778477,
					1.5965602806184558
				],
				[
					-2.411978112964703,
					2.394870873363032
				],
				[
					-3.210258253273931,
					2.394870873363032
				],
				[
					-5.605098674201612,
					3.193151013672263
				],
				[
					-6.403439719381544,
					3.193151013672263
				],
				[
					-7.201719859690774,
					3.9914616064168413
				],
				[
					-8,
					3.9914616064168413
				],
				[
					-8,
					3.9914616064168413
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.005859375,
				0.16796875,
				0.173828125,
				0.1767578125,
				0.169921875,
				0.162109375,
				0.123046875,
				0.0771484375,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 286,
			"versionNonce": 1279926148,
			"isDeleted": false,
			"id": "-8qgIqRQlilpYixM2Umgq",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3324.407963731999,
			"y": -8.84489886115962,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 8.781203353142908,
			"height": 2.3948708733630326,
			"seed": 939509380,
			"groupIds": [
				"Ekp0tPHF2zeLqGVQ7i5mE"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511257127,
			"link": null,
			"locked": false,
			"points": [
				[
					-0.018784439825841284,
					0
				],
				[
					-0.018784439825841284,
					1.5965907330538067
				],
				[
					-1.615344720444297,
					1.5965907330538067
				],
				[
					-3.2119659059334547,
					1.5965907330538067
				],
				[
					-4.010246046242681,
					2.3948708733630326
				],
				[
					-5.606806326861135,
					1.5965907330538067
				],
				[
					-6.405086467170364,
					1.5965907330538067
				],
				[
					-8.001707652659526,
					2.3948708733630326
				],
				[
					-8.001707652659526,
					1.5965907330538067
				],
				[
					-8.79998779296875,
					1.5965907330538067
				],
				[
					-8.79998779296875,
					1.5965907330538067
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0029296875,
				0.1572265625,
				0.2548828125,
				0.3056640625,
				0.3203125,
				0.32421875,
				0.30859375,
				0.19921875,
				0.111328125,
				0.037109375,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 149,
			"versionNonce": 210537148,
			"isDeleted": false,
			"id": "tOca4xEm023Zts-0uvpQR",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3945.6556962173754,
			"y": -114.4696411985077,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 8.800048828125,
			"height": 20,
			"seed": 1704475908,
			"groupIds": [
				"Ekp0tPHF2zeLqGVQ7i5mE"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511257127,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					0.800018310546875
				],
				[
					0.800048828125,
					0.800018310546875
				],
				[
					1.5999755859375,
					0
				],
				[
					2.4000244140625,
					-0.79998779296875
				],
				[
					3.2000732421875,
					-2.399993896484375
				],
				[
					4,
					-3.199981689453125
				],
				[
					4.800048828125,
					-4
				],
				[
					5.5999755859375,
					-5.600006103515625
				],
				[
					7.2000732421875,
					-6.399993896484375
				],
				[
					8,
					-7.199981689453125
				],
				[
					8,
					-8
				],
				[
					8.800048828125,
					-8
				],
				[
					8.800048828125,
					-8.79998779296875
				],
				[
					8.800048828125,
					-8
				],
				[
					8.800048828125,
					-8.79998779296875
				],
				[
					8.800048828125,
					-8
				],
				[
					8.800048828125,
					-7.199981689453125
				],
				[
					8.800048828125,
					-5.600006103515625
				],
				[
					8.800048828125,
					-4.79998779296875
				],
				[
					8,
					0
				],
				[
					8,
					6.399993896484375
				],
				[
					8,
					8
				],
				[
					8,
					8.800018310546875
				],
				[
					8,
					9.600006103515625
				],
				[
					7.2000732421875,
					9.600006103515625
				],
				[
					7.2000732421875,
					10.399993896484375
				],
				[
					7.2000732421875,
					11.20001220703125
				],
				[
					8,
					11.20001220703125
				],
				[
					8.800048828125,
					11.20001220703125
				],
				[
					8.800048828125,
					11.20001220703125
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0009765625,
				0.298828125,
				0.5439453125,
				0.56640625,
				0.5732421875,
				0.5751953125,
				0.576171875,
				0.5751953125,
				0.578125,
				0.5791015625,
				0.578125,
				0.578125,
				0.578125,
				0.5771484375,
				0.5771484375,
				0.5810546875,
				0.6025390625,
				0.611328125,
				0.6123046875,
				0.6123046875,
				0.619140625,
				0.62109375,
				0.6162109375,
				0.609375,
				0.5517578125,
				0.5283203125,
				0.4755859375,
				0.2783203125,
				0.08984375,
				0.0146484375,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 155,
			"versionNonce": 946048772,
			"isDeleted": false,
			"id": "JqewgIWWABW2SqKM7Wbu7",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3974.4557450455004,
			"y": -121.66962288796083,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 13.5999755859375,
			"height": 14.399993896484375,
			"seed": 1317924996,
			"groupIds": [
				"Ekp0tPHF2zeLqGVQ7i5mE"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511257127,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					1.5999755859375,
					0.79998779296875
				],
				[
					1.5999755859375,
					1.5999755859375
				],
				[
					0.7999267578125,
					1.5999755859375
				],
				[
					0.7999267578125,
					0.79998779296875
				],
				[
					0,
					0.79998779296875
				],
				[
					-0.800048828125,
					0.79998779296875
				],
				[
					-1.5999755859375,
					0.79998779296875
				],
				[
					-2.4000244140625,
					0.79998779296875
				],
				[
					-3.2000732421875,
					0.79998779296875
				],
				[
					-3.2000732421875,
					1.5999755859375
				],
				[
					-3.2000732421875,
					2.399993896484375
				],
				[
					-3.2000732421875,
					3.199981689453125
				],
				[
					-3.2000732421875,
					4
				],
				[
					-3.2000732421875,
					4.79998779296875
				],
				[
					-3.2000732421875,
					5.5999755859375
				],
				[
					-4,
					6.399993896484375
				],
				[
					-4,
					7.199981689453125
				],
				[
					-3.2000732421875,
					7.199981689453125
				],
				[
					-2.4000244140625,
					7.199981689453125
				],
				[
					-1.5999755859375,
					7.199981689453125
				],
				[
					-0.800048828125,
					7.199981689453125
				],
				[
					0,
					7.199981689453125
				],
				[
					1.5999755859375,
					7.199981689453125
				],
				[
					2.4000244140625,
					7.199981689453125
				],
				[
					3.199951171875,
					7.199981689453125
				],
				[
					4,
					8
				],
				[
					4.7999267578125,
					8.79998779296875
				],
				[
					5.5999755859375,
					8.79998779296875
				],
				[
					5.5999755859375,
					9.5999755859375
				],
				[
					5.5999755859375,
					10.399993896484375
				],
				[
					5.5999755859375,
					11.199981689453125
				],
				[
					4.7999267578125,
					12.79998779296875
				],
				[
					3.199951171875,
					13.5999755859375
				],
				[
					1.5999755859375,
					14.399993896484375
				],
				[
					0,
					14.399993896484375
				],
				[
					-0.800048828125,
					14.399993896484375
				],
				[
					-3.2000732421875,
					14.399993896484375
				],
				[
					-4.800048828125,
					14.399993896484375
				],
				[
					-5.5999755859375,
					13.5999755859375
				],
				[
					-6.4000244140625,
					12.79998779296875
				],
				[
					-7.2000732421875,
					12
				],
				[
					-8,
					12
				],
				[
					-8,
					12
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0048828125,
				0.20703125,
				0.4453125,
				0.541015625,
				0.541015625,
				0.541015625,
				0.541015625,
				0.541015625,
				0.5419921875,
				0.54296875,
				0.5517578125,
				0.55078125,
				0.5458984375,
				0.544921875,
				0.5458984375,
				0.5419921875,
				0.5341796875,
				0.53125,
				0.529296875,
				0.529296875,
				0.52734375,
				0.52734375,
				0.52734375,
				0.52734375,
				0.52734375,
				0.52734375,
				0.52734375,
				0.5283203125,
				0.5283203125,
				0.5283203125,
				0.5244140625,
				0.5234375,
				0.5263671875,
				0.52734375,
				0.52734375,
				0.533203125,
				0.533203125,
				0.5283203125,
				0.5263671875,
				0.521484375,
				0.49609375,
				0.3447265625,
				0.294921875,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 143,
			"versionNonce": 480498492,
			"isDeleted": false,
			"id": "gCVRPDfPozjSOzMSVgOzA",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3958.4557450455004,
			"y": -97.66962288796083,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 8,
			"height": 21.5999755859375,
			"seed": 1331680444,
			"groupIds": [
				"Ekp0tPHF2zeLqGVQ7i5mE"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511257127,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.7999267578125,
					2.399993896484375
				],
				[
					0,
					4
				],
				[
					-0.800048828125,
					4.79998779296875
				],
				[
					-1.5999755859375,
					6.399993896484375
				],
				[
					-3.2000732421875,
					8.79998779296875
				],
				[
					-4,
					12
				],
				[
					-4,
					14.399993896484375
				],
				[
					-4.800048828125,
					17.5999755859375
				],
				[
					-4,
					19.199981689453125
				],
				[
					-4,
					20
				],
				[
					-3.2000732421875,
					20.79998779296875
				],
				[
					-2.4000244140625,
					21.5999755859375
				],
				[
					-1.5999755859375,
					21.5999755859375
				],
				[
					-0.800048828125,
					20.79998779296875
				],
				[
					0.7999267578125,
					20
				],
				[
					1.5999755859375,
					19.199981689453125
				],
				[
					2.4000244140625,
					18.399993896484375
				],
				[
					3.199951171875,
					17.5999755859375
				],
				[
					3.199951171875,
					16.79998779296875
				],
				[
					2.4000244140625,
					16.79998779296875
				],
				[
					1.5999755859375,
					16.79998779296875
				],
				[
					0.7999267578125,
					16.79998779296875
				],
				[
					-0.800048828125,
					16
				],
				[
					-2.4000244140625,
					16
				],
				[
					-3.2000732421875,
					16
				],
				[
					-4,
					16
				],
				[
					-4.800048828125,
					16
				],
				[
					-4,
					16
				],
				[
					-2.4000244140625,
					15.199981689453125
				],
				[
					-2.4000244140625,
					16
				],
				[
					-2.4000244140625,
					16
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0068359375,
				0.279296875,
				0.2939453125,
				0.296875,
				0.2978515625,
				0.30078125,
				0.314453125,
				0.3359375,
				0.3515625,
				0.3544921875,
				0.3564453125,
				0.357421875,
				0.357421875,
				0.357421875,
				0.357421875,
				0.357421875,
				0.3564453125,
				0.357421875,
				0.3564453125,
				0.3544921875,
				0.3544921875,
				0.357421875,
				0.357421875,
				0.3564453125,
				0.3544921875,
				0.345703125,
				0.31640625,
				0.2646484375,
				0.09375,
				0.013671875,
				0.001953125,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 119,
			"versionNonce": 1319308932,
			"isDeleted": false,
			"id": "Xzq7dLKuifWwLsBJ-S3Xt",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3963.255671803313,
			"y": -76.86963509499208,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 1.60009765625,
			"height": 5.600006103515625,
			"seed": 903175428,
			"groupIds": [
				"Ekp0tPHF2zeLqGVQ7i5mE"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511257127,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					-0.79998779296875
				],
				[
					0,
					-1.600006103515625
				],
				[
					0,
					-3.20001220703125
				],
				[
					0.800048828125,
					-4.79998779296875
				],
				[
					1.60009765625,
					-5.600006103515625
				],
				[
					0,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0078125,
				0.3056640625,
				0.298828125,
				0.1962890625,
				0.06640625,
				0.01171875,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 116,
			"versionNonce": 733875132,
			"isDeleted": false,
			"id": "UgYxn2_7OWGDkN6A5u-rx",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3966.4557450455004,
			"y": -88.86963509499208,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 0.7999267578125,
			"height": 0.79998779296875,
			"seed": 1383294780,
			"groupIds": [
				"Ekp0tPHF2zeLqGVQ7i5mE"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511257127,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					0.79998779296875
				],
				[
					0.7999267578125,
					0.79998779296875
				],
				[
					0,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0078125,
				0.138671875,
				0.0283203125,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 126,
			"versionNonce": 2143723012,
			"isDeleted": false,
			"id": "bz-g8rYFndgVCUVqJcEQd",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3974.4557450455004,
			"y": -90.4696411985077,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 6.4000244140625,
			"height": 15.20001220703125,
			"seed": 348872892,
			"groupIds": [
				"Ekp0tPHF2zeLqGVQ7i5mE"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511257127,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-0.800048828125,
					2.399993896484375
				],
				[
					-0.800048828125,
					4
				],
				[
					-1.5999755859375,
					6.399993896484375
				],
				[
					-2.4000244140625,
					7.20001220703125
				],
				[
					-2.4000244140625,
					8.800018310546875
				],
				[
					-2.4000244140625,
					10.399993896484375
				],
				[
					-2.4000244140625,
					12
				],
				[
					-2.4000244140625,
					13.600006103515625
				],
				[
					-1.5999755859375,
					14.399993896484375
				],
				[
					-0.800048828125,
					14.399993896484375
				],
				[
					0.7999267578125,
					15.20001220703125
				],
				[
					3.199951171875,
					14.399993896484375
				],
				[
					4,
					13.600006103515625
				],
				[
					4,
					13.600006103515625
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0,
				0.1865234375,
				0.2568359375,
				0.3271484375,
				0.34375,
				0.3515625,
				0.357421875,
				0.359375,
				0.3544921875,
				0.3115234375,
				0.283203125,
				0.1357421875,
				0.03125,
				0.0009765625,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 117,
			"versionNonce": 1006449724,
			"isDeleted": false,
			"id": "TczsbGldav7A1I-ptFG09",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3978.4557450455004,
			"y": -85.66962288796083,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 8.800048828125,
			"height": 1.600006103515625,
			"seed": 2064770236,
			"groupIds": [
				"Ekp0tPHF2zeLqGVQ7i5mE"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511257127,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-4.800048828125,
					-0.800018310546875
				],
				[
					-6.4000244140625,
					-0.800018310546875
				],
				[
					-7.2000732421875,
					-1.600006103515625
				],
				[
					-8.800048828125,
					-1.600006103515625
				],
				[
					-8.800048828125,
					-1.600006103515625
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0009765625,
				0.158203125,
				0.1630859375,
				0.1611328125,
				0.130859375,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 134,
			"versionNonce": 1959542148,
			"isDeleted": false,
			"id": "GUlzVsmh5kNbJcPrAX3PL",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3988.855769459563,
			"y": -86.4696411985077,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 12.800048828125,
			"height": 12.800018310546875,
			"seed": 199181188,
			"groupIds": [
				"Ekp0tPHF2zeLqGVQ7i5mE"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511257127,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-4,
					1.600006103515625
				],
				[
					-5.60009765625,
					2.399993896484375
				],
				[
					-6.4000244140625,
					2.399993896484375
				],
				[
					-6.4000244140625,
					3.20001220703125
				],
				[
					-7.2000732421875,
					3.20001220703125
				],
				[
					-6.4000244140625,
					4
				],
				[
					-5.60009765625,
					4.800018310546875
				],
				[
					-4.800048828125,
					5.600006103515625
				],
				[
					-3.2000732421875,
					5.600006103515625
				],
				[
					-1.60009765625,
					6.399993896484375
				],
				[
					-0.800048828125,
					8
				],
				[
					0,
					8.800018310546875
				],
				[
					0,
					9.600006103515625
				],
				[
					0,
					10.399993896484375
				],
				[
					-0.800048828125,
					11.20001220703125
				],
				[
					-2.4000244140625,
					11.20001220703125
				],
				[
					-4.800048828125,
					12
				],
				[
					-7.2000732421875,
					12.800018310546875
				],
				[
					-9.60009765625,
					12.800018310546875
				],
				[
					-12,
					12.800018310546875
				],
				[
					-12.800048828125,
					12
				],
				[
					-12.800048828125,
					12
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.00390625,
				0.14453125,
				0.15625,
				0.1572265625,
				0.1572265625,
				0.1572265625,
				0.158203125,
				0.158203125,
				0.1572265625,
				0.1572265625,
				0.158203125,
				0.158203125,
				0.16015625,
				0.166015625,
				0.1748046875,
				0.1826171875,
				0.2001953125,
				0.220703125,
				0.2353515625,
				0.2216796875,
				0.1708984375,
				0.0625,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 139,
			"versionNonce": 994266300,
			"isDeleted": false,
			"id": "ncPGzXs8a5B2yVFsRuuht",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 4128.855769459563,
			"y": -127.26962899147645,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 13.5999755859375,
			"height": 16,
			"seed": 2077400452,
			"groupIds": [
				"Ekp0tPHF2zeLqGVQ7i5mE"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511257127,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					0.79998779296875
				],
				[
					-0.800048828125,
					0.79998779296875
				],
				[
					0,
					0.79998779296875
				],
				[
					0.7999267578125,
					0
				],
				[
					1.5999755859375,
					-0.800018310546875
				],
				[
					2.39990234375,
					-1.600006103515625
				],
				[
					3.199951171875,
					-2.399993896484375
				],
				[
					4.7999267578125,
					-4
				],
				[
					5.5999755859375,
					-4.800018310546875
				],
				[
					6.39990234375,
					-6.399993896484375
				],
				[
					7.199951171875,
					-6.399993896484375
				],
				[
					7.199951171875,
					-7.20001220703125
				],
				[
					7.199951171875,
					-6.399993896484375
				],
				[
					8,
					-6.399993896484375
				],
				[
					8,
					-5.600006103515625
				],
				[
					8,
					-3.20001220703125
				],
				[
					8,
					-0.800018310546875
				],
				[
					7.199951171875,
					0.79998779296875
				],
				[
					7.199951171875,
					3.199981689453125
				],
				[
					7.199951171875,
					5.600006103515625
				],
				[
					6.39990234375,
					7.199981689453125
				],
				[
					7.199951171875,
					8.79998779296875
				],
				[
					8,
					8.79998779296875
				],
				[
					8.7999267578125,
					8.79998779296875
				],
				[
					11.199951171875,
					8
				],
				[
					12.7999267578125,
					8
				],
				[
					12.7999267578125,
					8
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0048828125,
				0.140625,
				0.2998046875,
				0.458984375,
				0.52734375,
				0.568359375,
				0.587890625,
				0.6005859375,
				0.6064453125,
				0.6064453125,
				0.607421875,
				0.607421875,
				0.607421875,
				0.6162109375,
				0.62109375,
				0.6416015625,
				0.6640625,
				0.673828125,
				0.67578125,
				0.671875,
				0.6455078125,
				0.5986328125,
				0.4306640625,
				0.193359375,
				0.1494140625,
				0.0224609375,
				0,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 141,
			"versionNonce": 116518148,
			"isDeleted": false,
			"id": "BbJEk2QmQsHz6DWB9NKGI",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 4153.655696217375,
			"y": -134.4696411985077,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 10.4000244140625,
			"height": 14.399993896484375,
			"seed": 1065923516,
			"groupIds": [
				"Ekp0tPHF2zeLqGVQ7i5mE"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511257127,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-1.5999755859375,
					1.600006103515625
				],
				[
					-3.199951171875,
					3.20001220703125
				],
				[
					-4,
					4.800018310546875
				],
				[
					-5.5999755859375,
					7.20001220703125
				],
				[
					-6.4000244140625,
					8.800018310546875
				],
				[
					-6.4000244140625,
					10.399993896484375
				],
				[
					-6.4000244140625,
					11.20001220703125
				],
				[
					-6.4000244140625,
					12
				],
				[
					-5.5999755859375,
					12.800018310546875
				],
				[
					-4,
					13.600006103515625
				],
				[
					-3.199951171875,
					14.399993896484375
				],
				[
					-2.4000244140625,
					14.399993896484375
				],
				[
					-1.5999755859375,
					13.600006103515625
				],
				[
					-0.7999267578125,
					13.600006103515625
				],
				[
					0,
					12.800018310546875
				],
				[
					0.800048828125,
					12
				],
				[
					0.800048828125,
					11.20001220703125
				],
				[
					0,
					11.20001220703125
				],
				[
					0,
					10.399993896484375
				],
				[
					-0.7999267578125,
					10.399993896484375
				],
				[
					-2.4000244140625,
					10.399993896484375
				],
				[
					-4.7999267578125,
					10.399993896484375
				],
				[
					-6.4000244140625,
					10.399993896484375
				],
				[
					-8,
					10.399993896484375
				],
				[
					-8.7999267578125,
					10.399993896484375
				],
				[
					-9.5999755859375,
					10.399993896484375
				],
				[
					-8.7999267578125,
					11.20001220703125
				],
				[
					-8,
					12
				],
				[
					-8,
					12
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0078125,
				0.177734375,
				0.251953125,
				0.279296875,
				0.3095703125,
				0.318359375,
				0.3203125,
				0.3203125,
				0.3203125,
				0.3193359375,
				0.30859375,
				0.2998046875,
				0.287109375,
				0.2822265625,
				0.27734375,
				0.2724609375,
				0.271484375,
				0.2724609375,
				0.271484375,
				0.271484375,
				0.26953125,
				0.275390625,
				0.2890625,
				0.29296875,
				0.2919921875,
				0.2646484375,
				0.19921875,
				0.0888671875,
				0.0068359375,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 136,
			"versionNonce": 187847996,
			"isDeleted": false,
			"id": "oZfyEb5iYfS1CWxu9GwD4",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 4136.055720631438,
			"y": -100.86963509499208,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 5.60009765625,
			"height": 18.399993896484375,
			"seed": 703749764,
			"groupIds": [
				"Ekp0tPHF2zeLqGVQ7i5mE"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511257127,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0.800048828125,
					0
				],
				[
					0,
					1.600006103515625
				],
				[
					-0.800048828125,
					4.79998779296875
				],
				[
					-1.5999755859375,
					7.20001220703125
				],
				[
					-2.4000244140625,
					10.399993896484375
				],
				[
					-2.4000244140625,
					12.79998779296875
				],
				[
					-3.199951171875,
					14.399993896484375
				],
				[
					-3.199951171875,
					17.600006103515625
				],
				[
					-3.199951171875,
					18.399993896484375
				],
				[
					-2.4000244140625,
					18.399993896484375
				],
				[
					-1.5999755859375,
					17.600006103515625
				],
				[
					-0.800048828125,
					16.79998779296875
				],
				[
					0,
					16.79998779296875
				],
				[
					0,
					16
				],
				[
					0.800048828125,
					15.20001220703125
				],
				[
					0.800048828125,
					14.399993896484375
				],
				[
					0,
					14.399993896484375
				],
				[
					-0.800048828125,
					13.600006103515625
				],
				[
					-1.5999755859375,
					13.600006103515625
				],
				[
					-2.4000244140625,
					12.79998779296875
				],
				[
					-4,
					12.79998779296875
				],
				[
					-4.800048828125,
					12.79998779296875
				],
				[
					-4,
					13.600006103515625
				],
				[
					-4,
					13.600006103515625
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.005859375,
				0.2333984375,
				0.3310546875,
				0.3642578125,
				0.3720703125,
				0.376953125,
				0.3779296875,
				0.3779296875,
				0.37890625,
				0.37890625,
				0.375,
				0.3681640625,
				0.3642578125,
				0.3642578125,
				0.3642578125,
				0.36328125,
				0.3623046875,
				0.361328125,
				0.3583984375,
				0.3515625,
				0.328125,
				0.2431640625,
				0.169921875,
				0.0458984375,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 119,
			"versionNonce": 934653060,
			"isDeleted": false,
			"id": "cw8iDrLKcpWMNIPU4enmM",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 4142.4557450455,
			"y": -81.66962288796083,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 2.4000244140625,
			"height": 8,
			"seed": 600016900,
			"groupIds": [
				"Ekp0tPHF2zeLqGVQ7i5mE"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511257127,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-0.800048828125,
					-0.800018310546875
				],
				[
					-0.800048828125,
					-1.600006103515625
				],
				[
					-0.800048828125,
					-3.20001220703125
				],
				[
					-0.800048828125,
					-4.800018310546875
				],
				[
					0,
					-6.4000244140625
				],
				[
					1.5999755859375,
					-8
				],
				[
					1.5999755859375,
					-8
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0087890625,
				0.14453125,
				0.1611328125,
				0.162109375,
				0.142578125,
				0.0693359375,
				0.005859375,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 128,
			"versionNonce": 153898428,
			"isDeleted": false,
			"id": "A0T2cuM0L6J7xAiAI4W_C",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 4152.855769459563,
			"y": -100.06964730202333,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 8,
			"height": 16.800018310546875,
			"seed": 1147595836,
			"groupIds": [
				"Ekp0tPHF2zeLqGVQ7i5mE"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511257127,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					0,
					2.4000244140625
				],
				[
					0,
					4
				],
				[
					-0.800048828125,
					6.4000244140625
				],
				[
					-0.800048828125,
					8
				],
				[
					-0.800048828125,
					9.600006103515625
				],
				[
					-0.800048828125,
					11.20001220703125
				],
				[
					0,
					13.600006103515625
				],
				[
					0,
					14.4000244140625
				],
				[
					0.7999267578125,
					16
				],
				[
					1.5999755859375,
					16
				],
				[
					2.39990234375,
					16.800018310546875
				],
				[
					4,
					16
				],
				[
					4.7999267578125,
					15.20001220703125
				],
				[
					5.5999755859375,
					15.20001220703125
				],
				[
					7.199951171875,
					13.600006103515625
				],
				[
					7.199951171875,
					13.600006103515625
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0048828125,
				0.27734375,
				0.357421875,
				0.3974609375,
				0.4140625,
				0.4189453125,
				0.4208984375,
				0.4208984375,
				0.419921875,
				0.3994140625,
				0.3857421875,
				0.3115234375,
				0.19140625,
				0.103515625,
				0.076171875,
				0.0048828125,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 118,
			"versionNonce": 685079556,
			"isDeleted": false,
			"id": "351W1eM8ZWfXsdLnG518i",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 4158.4557450455,
			"y": -89.66962288796083,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 7.2000732421875,
			"height": 1.600006103515625,
			"seed": 337152188,
			"groupIds": [
				"Ekp0tPHF2zeLqGVQ7i5mE"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511257127,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-4,
					-0.800018310546875
				],
				[
					-5.5999755859375,
					-1.600006103515625
				],
				[
					-6.4000244140625,
					-1.600006103515625
				],
				[
					-7.2000732421875,
					-0.800018310546875
				],
				[
					0,
					0
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.001953125,
				0.1474609375,
				0.154296875,
				0.154296875,
				0.134765625,
				0
			]
		},
		{
			"type": "freedraw",
			"version": 136,
			"versionNonce": 374552124,
			"isDeleted": false,
			"id": "m0wuPCobWEyyzaC1WxXsu",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 4167.255671803313,
			"y": -94.4696411985077,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 8.7999267578125,
			"height": 13.600006103515625,
			"seed": 1977633468,
			"groupIds": [
				"Ekp0tPHF2zeLqGVQ7i5mE"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511257127,
			"link": null,
			"locked": false,
			"points": [
				[
					0,
					0
				],
				[
					-4,
					2.399993896484375
				],
				[
					-5.5999755859375,
					3.20001220703125
				],
				[
					-5.5999755859375,
					4
				],
				[
					-6.39990234375,
					4.800018310546875
				],
				[
					-6.39990234375,
					5.600006103515625
				],
				[
					-6.39990234375,
					6.399993896484375
				],
				[
					-5.5999755859375,
					7.20001220703125
				],
				[
					-4.7999267578125,
					8
				],
				[
					-3.199951171875,
					8.800018310546875
				],
				[
					-2.39990234375,
					9.600006103515625
				],
				[
					-1.5999755859375,
					10.399993896484375
				],
				[
					-0.7999267578125,
					11.20001220703125
				],
				[
					-0.7999267578125,
					12
				],
				[
					-1.5999755859375,
					12.800018310546875
				],
				[
					-2.39990234375,
					13.600006103515625
				],
				[
					-3.199951171875,
					13.600006103515625
				],
				[
					-4.7999267578125,
					13.600006103515625
				],
				[
					-5.5999755859375,
					13.600006103515625
				],
				[
					-7.199951171875,
					13.600006103515625
				],
				[
					-8,
					13.600006103515625
				],
				[
					-8.7999267578125,
					12.800018310546875
				],
				[
					-8,
					12
				],
				[
					-8,
					11.20001220703125
				],
				[
					-8,
					11.20001220703125
				]
			],
			"lastCommittedPoint": null,
			"simulatePressure": false,
			"pressures": [
				0.0029296875,
				0.154296875,
				0.162109375,
				0.162109375,
				0.1640625,
				0.1640625,
				0.1640625,
				0.1640625,
				0.1630859375,
				0.1630859375,
				0.1640625,
				0.1689453125,
				0.1826171875,
				0.189453125,
				0.1953125,
				0.2060546875,
				0.2158203125,
				0.232421875,
				0.2373046875,
				0.23828125,
				0.2265625,
				0.173828125,
				0.060546875,
				0.0087890625,
				0
			]
		},
		{
			"type": "line",
			"version": 737,
			"versionNonce": 340745092,
			"isDeleted": false,
			"id": "XtL6ABqXMeaP2utvoXB1q",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 3302.055552784758,
			"y": -315.66965340553895,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 1329.0256487980487,
			"height": 0,
			"seed": 100670908,
			"groupIds": [
				"Ekp0tPHF2zeLqGVQ7i5mE"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511257127,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					1329.0256487980487,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 201,
			"versionNonce": 529075900,
			"isDeleted": false,
			"id": "1qUJ4TmwNq-e-4d2m9Ntq",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 4192.855555836516,
			"y": -192.46961068092963,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 292.63412097990476,
			"height": 0,
			"seed": 1228311684,
			"groupIds": [
				"Ekp0tPHF2zeLqGVQ7i5mE"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511257127,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					292.63412097990476,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 308,
			"versionNonce": 1147226884,
			"isDeleted": false,
			"id": "PkIW6UiJIGW8Z4JxA4-jt",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 4196.055568043547,
			"y": -45.26959847389833,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 286.2813203604892,
			"height": 0,
			"seed": 584892348,
			"groupIds": [
				"Ekp0tPHF2zeLqGVQ7i5mE"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511257127,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					286.2813203604892,
					0
				]
			]
		},
		{
			"type": "text",
			"version": 59,
			"versionNonce": 628086588,
			"isDeleted": false,
			"id": "hKcmbsHe",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 4231.2555802505785,
			"y": -217.46961068092963,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 163,
			"height": 25,
			"seed": 1217639740,
			"groupIds": [
				"Ekp0tPHF2zeLqGVQ7i5mE"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1662511257127,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "\"primeros\" 8 bits",
			"rawText": "\"primeros\" 8 bits",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "\"primeros\" 8 bits"
		},
		{
			"type": "text",
			"version": 57,
			"versionNonce": 193546884,
			"isDeleted": false,
			"id": "5i2DUwFQ",
			"fillStyle": "cross-hatch",
			"strokeWidth": 0.5,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 4240.855555836516,
			"y": -72.66962288796083,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 172,
			"height": 25,
			"seed": 331281084,
			"groupIds": [
				"Ekp0tPHF2zeLqGVQ7i5mE"
			],
			"strokeSharpness": "sharp",
			"boundElements": [],
			"updated": 1662511257127,
			"link": null,
			"locked": false,
			"fontSize": 20,
			"fontFamily": 1,
			"text": "\"segundos\" 8 bits",
			"rawText": "\"segundos\" 8 bits",
			"baseline": 18,
			"textAlign": "left",
			"verticalAlign": "top",
			"containerId": null,
			"originalText": "\"segundos\" 8 bits"
		},
		{
			"type": "line",
			"version": 123,
			"versionNonce": 1147768764,
			"isDeleted": false,
			"id": "EkqaoMYcYqmRK8hi0krwB",
			"fillStyle": "cross-hatch",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 100,
			"angle": 0,
			"x": 4444.85549480136,
			"y": -317.0696778196015,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 219.7598669170868,
			"seed": 1257825468,
			"groupIds": [
				"Ekp0tPHF2zeLqGVQ7i5mE"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511257127,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					219.7598669170868
				]
			]
		},
		{
			"type": "line",
			"version": 461,
			"versionNonce": 1015372292,
			"isDeleted": false,
			"id": "eW2g48aKXSo8mfaE-bkwK",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 6.283185307179586,
			"x": 4447.577210499138,
			"y": -96.54273370309589,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 44.7090599531498,
			"height": 0,
			"seed": 695780612,
			"groupIds": [
				"1YplRAFzNzf09N3EsN3Qa",
				"Ekp0tPHF2zeLqGVQ7i5mE"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511257127,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					44.7090599531498,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 439,
			"versionNonce": 1016608828,
			"isDeleted": false,
			"id": "GrYe0tKdJqtF80KKJzKBe",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 6.283185307179586,
			"x": 4491.840378445126,
			"y": -119.28280304986906,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 44.7090599531498,
			"seed": 1529150780,
			"groupIds": [
				"1YplRAFzNzf09N3EsN3Qa",
				"Ekp0tPHF2zeLqGVQ7i5mE"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511257127,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					44.7090599531498
				]
			]
		},
		{
			"type": "line",
			"version": 513,
			"versionNonce": 575895940,
			"isDeleted": false,
			"id": "xliaPEwULtYCaLYra8zM9",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 6.283185307179586,
			"x": 4492.292393603851,
			"y": -119.29933952029005,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 44.7090599531498,
			"height": 22.3545299765749,
			"seed": 329352324,
			"groupIds": [
				"1YplRAFzNzf09N3EsN3Qa",
				"Ekp0tPHF2zeLqGVQ7i5mE"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511257127,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					44.7090599531498,
					22.3545299765749
				]
			]
		},
		{
			"type": "line",
			"version": 435,
			"versionNonce": 2044580028,
			"isDeleted": false,
			"id": "spQ5LzSANWyvYRl1mQtlB",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 6.283185307179586,
			"x": 4492.405690667535,
			"y": -74.42622587799923,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 44.7090599531498,
			"height": 22.3545299765749,
			"seed": 344585660,
			"groupIds": [
				"1YplRAFzNzf09N3EsN3Qa",
				"Ekp0tPHF2zeLqGVQ7i5mE"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511257127,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					44.7090599531498,
					-22.3545299765749
				]
			]
		},
		{
			"type": "line",
			"version": 540,
			"versionNonce": 2016520452,
			"isDeleted": false,
			"id": "swPZYlFVJyz8lNcDGgTW5",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 6.283185307179586,
			"x": 4547.8356425810125,
			"y": -96.45295758251409,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 22.559811998454578,
			"height": 0,
			"seed": 1233540100,
			"groupIds": [
				"1YplRAFzNzf09N3EsN3Qa",
				"Ekp0tPHF2zeLqGVQ7i5mE"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511257127,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					22.559811998454578,
					0
				]
			]
		},
		{
			"type": "ellipse",
			"version": 426,
			"versionNonce": 467425596,
			"isDeleted": false,
			"id": "k05Tyde9Q47tFNP68be45",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 6.283185307179586,
			"x": 4537.2825216798865,
			"y": -101.62052440009653,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 10.293689424810792,
			"height": 10.293689424810792,
			"seed": 935059004,
			"groupIds": [
				"1YplRAFzNzf09N3EsN3Qa",
				"Ekp0tPHF2zeLqGVQ7i5mE"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511257127,
			"link": null,
			"locked": false
		},
		{
			"type": "line",
			"version": 540,
			"versionNonce": 1637738628,
			"isDeleted": false,
			"id": "oDd36JoQuk-7SG48ReZgr",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 4712.234066815715,
			"y": -594.150057116827,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 35.41836789001383,
			"height": 0,
			"seed": 2069514428,
			"groupIds": [
				"mKP99DnXm7OHGweHcq23G",
				"Ekp0tPHF2zeLqGVQ7i5mE"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511257127,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					35.41836789001383,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 551,
			"versionNonce": 2113262012,
			"isDeleted": false,
			"id": "cYmBRsOLku6b2cgT0unQs",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 4618.0553849380785,
			"y": -606.0635582413547,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 47.22449052001845,
			"height": 0,
			"seed": 886616324,
			"groupIds": [
				"mKP99DnXm7OHGweHcq23G",
				"Ekp0tPHF2zeLqGVQ7i5mE"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511257127,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					47.22449052001845,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 553,
			"versionNonce": 1649817604,
			"isDeleted": false,
			"id": "jKUknoBHXMUSlWTcCwyRg",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 4617.655302758645,
			"y": -582.2020599808516,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 47.22449052001845,
			"height": 0,
			"seed": 654954812,
			"groupIds": [
				"mKP99DnXm7OHGweHcq23G",
				"Ekp0tPHF2zeLqGVQ7i5mE"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511257127,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					47.22449052001845,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 604,
			"versionNonce": 1061960252,
			"isDeleted": false,
			"id": "G7grBfVqPs9G5FwEUb8W6",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 4664.983897710841,
			"y": -617.8696808713594,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 47.22449052001845,
			"seed": 69464196,
			"groupIds": [
				"mKP99DnXm7OHGweHcq23G",
				"Ekp0tPHF2zeLqGVQ7i5mE"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511257127,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					47.22449052001845
				]
			]
		},
		{
			"type": "line",
			"version": 667,
			"versionNonce": 1448646532,
			"isDeleted": false,
			"id": "r96ZXmOEKmdaPHc4jD4JM",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 4665.003074298155,
			"y": -617.9209536797058,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 23.612245260009225,
			"height": 0,
			"seed": 884230588,
			"groupIds": [
				"mKP99DnXm7OHGweHcq23G",
				"Ekp0tPHF2zeLqGVQ7i5mE"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511257127,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					23.612245260009225,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 609,
			"versionNonce": 1254199996,
			"isDeleted": false,
			"id": "bB8afxMPKu-9ZxmBSAi7-",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 4664.980521629348,
			"y": -570.5074667738446,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 23.612245260009225,
			"height": 0,
			"seed": 1457209348,
			"groupIds": [
				"mKP99DnXm7OHGweHcq23G",
				"Ekp0tPHF2zeLqGVQ7i5mE"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511257127,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					23.612245260009225,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1336,
			"versionNonce": 1776486148,
			"isDeleted": false,
			"id": "MGSN8xWnn2CXRNgVeHAp1",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 4688.867878157364,
			"y": -617.9209536797058,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 22.560037635979,
			"height": 47.22449052001845,
			"seed": 125547068,
			"groupIds": [
				"mKP99DnXm7OHGweHcq23G",
				"Ekp0tPHF2zeLqGVQ7i5mE"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511257127,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					17.08839691828896,
					4.650879774390092
				],
				[
					22.560037635979,
					24.475086454633626
				],
				[
					15.804626047735054,
					42.99449803399659
				],
				[
					0,
					47.22449052001845
				]
			]
		},
		{
			"type": "line",
			"version": 601,
			"versionNonce": 1593301820,
			"isDeleted": false,
			"id": "Lcg-bFNu_YKZaDJs7EsCM",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 4716.235558607543,
			"y": -536.405564382505,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 35.41836789001383,
			"height": 0,
			"seed": 150911036,
			"groupIds": [
				"Aag-bxplJIL-CVyYTl9d-",
				"Ekp0tPHF2zeLqGVQ7i5mE"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511257127,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					35.41836789001383,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 612,
			"versionNonce": 292783748,
			"isDeleted": false,
			"id": "U1StYrbhXGrlTqXa-nglR",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 4622.056876729908,
			"y": -548.3190655070327,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 47.22449052001845,
			"height": 0,
			"seed": 362084740,
			"groupIds": [
				"Aag-bxplJIL-CVyYTl9d-",
				"Ekp0tPHF2zeLqGVQ7i5mE"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511257127,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					47.22449052001845,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 614,
			"versionNonce": 374412220,
			"isDeleted": false,
			"id": "xdQBZ8bhDUY7TpzBbLTiF",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 4621.656794550474,
			"y": -524.4575672465296,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 47.22449052001845,
			"height": 0,
			"seed": 1970557116,
			"groupIds": [
				"Aag-bxplJIL-CVyYTl9d-",
				"Ekp0tPHF2zeLqGVQ7i5mE"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511257127,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					47.22449052001845,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 665,
			"versionNonce": 29890052,
			"isDeleted": false,
			"id": "wJ44tRANjt226ESlzcaUQ",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 4668.98538950267,
			"y": -560.1251881370374,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 0,
			"height": 47.22449052001845,
			"seed": 121841924,
			"groupIds": [
				"Aag-bxplJIL-CVyYTl9d-",
				"Ekp0tPHF2zeLqGVQ7i5mE"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511257127,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					0,
					47.22449052001845
				]
			]
		},
		{
			"type": "line",
			"version": 728,
			"versionNonce": 1861172284,
			"isDeleted": false,
			"id": "fVqfRVNsGoHlDjK1kHLxO",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 4669.004566089985,
			"y": -560.1764609453837,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 23.612245260009225,
			"height": 0,
			"seed": 1621285180,
			"groupIds": [
				"Aag-bxplJIL-CVyYTl9d-",
				"Ekp0tPHF2zeLqGVQ7i5mE"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511257127,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					23.612245260009225,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 670,
			"versionNonce": 668906884,
			"isDeleted": false,
			"id": "Iy3R6tXcPToJs5zR8ZO1-",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 4668.982013421177,
			"y": -512.7629740395225,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 23.612245260009225,
			"height": 0,
			"seed": 310339716,
			"groupIds": [
				"Aag-bxplJIL-CVyYTl9d-",
				"Ekp0tPHF2zeLqGVQ7i5mE"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511257127,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					23.612245260009225,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 1397,
			"versionNonce": 1387549884,
			"isDeleted": false,
			"id": "q_whtNSwZxdoMy3s845jZ",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 4692.869369949192,
			"y": -560.1764609453837,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 22.560037635979,
			"height": 47.22449052001845,
			"seed": 1709986236,
			"groupIds": [
				"Aag-bxplJIL-CVyYTl9d-",
				"Ekp0tPHF2zeLqGVQ7i5mE"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511257127,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					17.08839691828896,
					4.650879774390092
				],
				[
					22.560037635979,
					24.475086454633626
				],
				[
					15.804626047735054,
					42.99449803399659
				],
				[
					0,
					47.22449052001845
				]
			]
		},
		{
			"type": "line",
			"version": 592,
			"versionNonce": 552953092,
			"isDeleted": false,
			"id": "ss8hj2Ol27_sggwEdogPH",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 4717.234873746787,
			"y": -478.2777954908768,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 35.41836789001383,
			"height": 0,
			"seed": 727927100,
			"groupIds": [
				"b_Zw0c3fbd3pVDQ-8Zrv0",
				"Ekp0tPHF2zeLqGVQ7i5mE"
			],
			"strokeSharpness": "round",
			"boundElements": [],
			"updated": 1662511257127,
			"link": null,
			"locked": false,
			"startBinding": null,
			"endBinding": null,
			"lastCommittedPoint": null,
			"startArrowhead": null,
			"endArrowhead": null,
			"points": [
				[
					0,
					0
				],
				[
					35.41836789001383,
					0
				]
			]
		},
		{
			"type": "line",
			"version": 603,
			"versionNonce": 524442940,
			"isDeleted": false,
			"id": "VQdoXXNNdi3w9R1LOBF7X",
			"fillStyle": "hachure",
			"strokeWidth": 1,
			"strokeStyle": "solid",
			"roughness": 1,
			"opacity": 90,
			"angle": 0,
			"x": 4623.056191869149,
			"y": -490.1912966154046,
			"strokeColor": "#c92a2a",
			"backgroundColor": "transparent",
			"width": 47.22449052001845,
			"height": 0,
			"seed": 641595524,
			"groupIds": [
				"b_Zw0c3fbd3pVDQ-8Zrv0",
				"Ekp0tPHF2zeLqGVQ7i5mE"
			],
			"boundElements": [],
		{