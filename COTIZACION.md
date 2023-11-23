# Cotizador Docs

## Cotizaciones

### Consultar cotizaciones

Al cargar la pantalla de consulta coticiones creadas se cargan las siguientes APIS:

 - `https://transborderuat.eastus.cloudapp.azure.com/msadministracion/api/v1/puerto/ (GET)` Lista puertos hasta el id ***1307***

    ***Response***:
    ~~~
    [
        {
            "id": 302,
            "nombre": "DURRËS",
            "pais": {
                "id": 240,
                "nombre": "ALBANIA",
                "codigo": "AL",
                "requiereCodigoZip": false
            },
            "ciudad": {
                "id": 58841,
                "nombre": "DURRËS",
                "pais": {
                    "id": 240,
                    "nombre": "ALBANIA",
                    "codigo": "AL",
                    "requiereCodigoZip": false
                },
                "codigo": "DRZ"
            }
        },
        {
            "id": 303,
            "nombre": "ALGER (ALGIERS)",
            "pais": {
                "id": 241,
                "nombre": "ALGERIA",
                "codigo": "DZ",
                "requiereCodigoZip": false
            },
            "ciudad": {
                "id": 58874,
                "nombre": "ALGER (ALGIERS)",
                "pais": {
                    "id": 241,
                    "nombre": "ALGERIA",
                    "codigo": "DZ",
                    "requiereCodigoZip": false
                },
                "codigo": "ALG"
            }
        }
    ]
    ~~~
    - `https://transborderuat.eastus.cloudapp.azure.com/msclientes/api/v1/cliente/apiExterna/1 (GET)` Obtiene un objeto json con datos como se muestran a continuación, el cual trae los clientes: 
  
    ***Response***:

  ~~~
  [
    {
        "id": null,
        "idLotus": "84816D82896D8B2605257EE4006DB0E5",
        "numeroIdentificacion": "",
        "digitoVerificacion": "",
        "razonSocial": "",
        "direccion": "",
        "telefono": "",
        "tipoIdentificacion": "NIT",
        "vinculado": "Si",
        "tierLotus": "",
        "tier": null
    },
    {
        "id": null,
        "idLotus": "26DF25A8401C547F0525842400785193",
        "numeroIdentificacion": "900743775",
        "digitoVerificacion": "2",
        "razonSocial": "\tPUBLILEDS COLOMBIA S.A.S.",
        "direccion": " TRANSVERSAL 3 B 23 200 TORRE 2\r\nPUERTO COLOMBIA\r\nATLANTICO",
        "telefono": "3212107906",
        "tipoIdentificacion": "NIT",
        "vinculado": "Si",
        "tierLotus": "3",
        "tier": null
    },
    {
        "id": null,
        "idLotus": "180A2C6BFCB5E166052589C2006E1360",
        "numeroIdentificacion": "901191324",
        "digitoVerificacion": "8",
        "razonSocial": "\r\nNEMOOTECH SAS\r\n",
        "direccion": "Carrera  48 # 10 - 45 Medellin",
        "telefono": "3244233311 ",
        "tipoIdentificacion": "NIT",
        "vinculado": "Si",
        "tierLotus": "3",
        "tier": null
    }
  ]
  ~~~

  - `https://transborderuat.eastus.cloudapp.azure.com/msadministracion/api/v1/listas?id=19 (GET)` 
  
  ***Response***:

  ~~~
    [
        {
            "idLista": 19,
            "identificador": "EN_CREACION",
            "valor": "En creación",
            "atributos": null
        },
        {
            "idLista": 19,
            "identificador": "EN_ESPERA_SPOT",
            "valor": "En espera spot",
            "atributos": null
        },
        {
            "idLista": 19,
            "identificador": "CREADA",
            "valor": "Creada",
            "atributos": null
        },
        {
            "idLista": 19,
            "identificador": "PENDIENTE_ACEPTACION",
            "valor": "Pendiente de Aceptación",
            "atributos": null
        },
        {
            "idLista": 19,
            "identificador": "ACEPTADA",
            "valor": "Aceptada",
            "atributos": null
        },
        {
            "idLista": 19,
            "identificador": "PREP_INST_EMBARQ_ENV",
            "valor": "Preparación de instrucción de embarque enviada",
            "atributos": null
        },
        {
            "idLista": 19,
            "identificador": "VENCIDA",
            "valor": "Vencida",
            "atributos": null
        },
        {
            "idLista": 19,
            "identificador": "ANULADA",
            "valor": "Anulada",
            "atributos": null
        }
    ]
  ~~~

  - `https://transborderuat.eastus.cloudapp.azure.com/msadministracion/api/v1/listas?id=3 (GET)`
  
  ***Response***:

  ~~~
  [
        {
            "idLista": 3,
            "identificador": "EXW",
            "valor": "Exworks",
            "atributos": null
        },
        {
            "idLista": 3,
            "identificador": "FCA",
            "valor": "Free Carrier",
            "atributos": null
        },
        {
            "idLista": 3,
            "identificador": "FAS",
            "valor": "Free Alongside Ship",
            "atributos": null
        },
        {
            "idLista": 3,
            "identificador": "FOB",
            "valor": "Free On Board",
            "atributos": null
        },
        {
            "idLista": 3,
            "identificador": "CFR",
            "valor": "Cost & Freight",
            "atributos": null
        },
        {
            "idLista": 3,
            "identificador": "CIF",
            "valor": "Cost, Insurance & Freight",
            "atributos": null
        },
        {
            "idLista": 3,
            "identificador": "CPT",
            "valor": "Cost Paid To",
            "atributos": null
        },
        {
            "idLista": 3,
            "identificador": "CIP",
            "valor": "Carrier & Insurance Paid to",
            "atributos": null
        },
        {
            "idLista": 3,
            "identificador": "DPU",
            "valor": "Delivered at Place Unloaded",
            "atributos": null
        },
        {
            "idLista": 3,
            "identificador": "DAP",
            "valor": "Delivered At Place",
            "atributos": null
        },
        {
            "idLista": 3,
            "identificador": "DDP",
            "valor": "Delivered Duty Paid",
            "atributos": null
        }
    ]
  ~~~

  - `https://transborderuat.eastus.cloudapp.azure.com/msadministracion/api/v1/listas?id=1 (GET)` 

  ***Response***:

  ~~~
    [
        {
            "idLista": 1,
            "identificador": "FCL",
            "valor": "Full Container Load",
            "atributos": null
        },
        {
            "idLista": 1,
            "identificador": "LCL",
            "valor": "Less Container Load",
            "atributos": null
        }
    ]
  ~~~

  - `https://transborderuat.eastus.cloudapp.azure.com/msusuarios/api/v1/grupocomercial/getUsuariosComercialesAsociados/jgrisales@transborderaduat.onmicrosoft.com (GET)`
  
  - `https://transborderuat.eastus.cloudapp.azure.com/msadministracion/api/v1/listas?id=4 (GET)`
  
  ***Response***:

  ~~~
    [
        {
            "idLista": 4,
            "identificador": "COMPRADOR",
            "valor": "Comprador",
            "atributos": null
        },
        {
            "idLista": 4,
            "identificador": "VENDEDOR",
            "valor": "Vendedor",
            "atributos": null
        }
    ]
  ~~~

---

### Consultar por Numero Cotizacion

 - `https://transborderuat.eastus.cloudapp.azure.com/cpcotizaciones/api/v1/cotizacionCP/findCotizacion/ (POST)`

***Request***:

~~~
{
	"numeroCotizacion": "1-050523-000039",
	"pagina": 1
}
~~~

***Response***:

~~~
[
	{
		"idCotizacion": 43,
		"numeroCotizacion": "1-050523-000039",
		"nombreEmpresa": "JADASH S A S",
		"fechaCreacion": "2023-05-05T16:29:00.000+00:00",
		"estado": "PREP_INST_EMBARQ_ENV",
		"spotPorConfirmar": "No",
		"tipoOperacion": null,
		"puertoOrigen": "HAMBURG",
		"puertoDestino": "BARRANQUILLA",
		"incoterm": "EXW",
		"tipoEmbarque": "FCL",
		"numeroInstruccionEmbarque": "1 - 152084",
		"count": 1,
		"numDocCliente": "900875640",
		"idCotizacionEnCreacion": null,
		"origenVersion": null,
		"origenClonacion": null,
		"respuestaProductoEnEsperaSpot": false,
		"versionada": false,
		"reporteGastosPorConfirmarVencidos": false,
		"creadaConEsperaSpot": false,
		"formaGeneracion": "DESGLOSADA",
		"idiomaPdf": "ESPAÑOL",
		"respuestaProductoSpotPorConfirmar": false,
		"ciudadOrigen": "HAMBURG, GERMANY",
		"ciudadDestino": "BARRANQUILLA, COLOMBIA",
		"perspectiva": "COMPRADOR",
		"tarifasActualizadas": true,
		"vencidaInstruccionada": false
	}
]
~~~

---

### Consultar por Cliente

 - `https://transborderuat.eastus.cloudapp.azure.com/cpcotizaciones/api/v1/cotizacionCP/findCotizacion/ (POST) `

***Request***:
~~~
    {
        "digitoVerificacionCliente": "2",
        "numeroIdentificacionCliente": "900743775",
        "pagina": 1,
        "tipoIdentificacionCliente": "NIT"
    }
~~~

***Response***:
~~~
    [
        {
            "idCotizacion": 44,
            "numeroCotizacion": "1-050523-000040",
            "nombreEmpresa": "PARTEQUIPOS S.A.S",
            "fechaCreacion": "2023-05-05T16:42:00.000+00:00",
            "estado": "PREP_INST_EMBARQ_ENV",
            "spotPorConfirmar": "No",
            "tipoOperacion": null,
            "puertoOrigen": "HAMBURG",
            "puertoDestino": "BARRANQUILLA",
            "incoterm": "FOB",
            "tipoEmbarque": "LCL",
            "numeroInstruccionEmbarque": "1 - 152085",
            "count": 2,
            "numDocCliente": "830080641",
            "idCotizacionEnCreacion": null,
            "origenVersion": null,
            "origenClonacion": 42,
            "respuestaProductoEnEsperaSpot": false,
            "versionada": false,
            "reporteGastosPorConfirmarVencidos": false,
            "creadaConEsperaSpot": false,
            "formaGeneracion": "SEMIDESGLOSADA",
            "idiomaPdf": "ESPAÑOL",
            "respuestaProductoSpotPorConfirmar": false,
            "ciudadOrigen": "HAMBURG, GERMANY",
            "ciudadDestino": "BARRANQUILLA, COLOMBIA",
            "perspectiva": "COMPRADOR",
            "tarifasActualizadas": null,
            "vencidaInstruccionada": false
        },
        {
            "idCotizacion": 42,
            "numeroCotizacion": "1-050523-000038",
            "nombreEmpresa": "PARTEQUIPOS S.A.S",
            "fechaCreacion": "2023-05-05T16:21:00.000+00:00",
            "estado": "PREP_INST_EMBARQ_ENV",
            "spotPorConfirmar": "No",
            "tipoOperacion": null,
            "puertoOrigen": "HAMBURG",
            "puertoDestino": "BARRANQUILLA",
            "incoterm": "EXW",
            "tipoEmbarque": "LCL",
            "numeroInstruccionEmbarque": "1 - 152083",
            "count": 2,
            "numDocCliente": "830080641",
            "idCotizacionEnCreacion": null,
            "origenVersion": null,
            "origenClonacion": null,
            "respuestaProductoEnEsperaSpot": false,
            "versionada": false,
            "reporteGastosPorConfirmarVencidos": false,
            "creadaConEsperaSpot": false,
            "formaGeneracion": "DESGLOSADA",
            "idiomaPdf": "ESPAÑOL",
            "respuestaProductoSpotPorConfirmar": false,
            "ciudadOrigen": "HAMBURG, GERMANY",
            "ciudadDestino": "BARRANQUILLA, COLOMBIA",
            "perspectiva": "COMPRADOR",
            "tarifasActualizadas": null,
            "vencidaInstruccionada": false
        }
    ]
~~~