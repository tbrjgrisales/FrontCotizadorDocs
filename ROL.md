# Cotizador Docs

## Usuarios

### Ubicación Componentes Roles

<img src="./Images/Administration.png" alt="Roles Estructura" style="height: 40em; width: 100%;"/>

---

<details>
<summary><h2>Crear Rol</h2></summary>
<br>

<details>
<summary><h2>Creacion Rol</h2></summary>
<br>

### Metodo GET

- `https://transborderuat.eastus.cloudapp.azure.com/msusuarios/api/v1/rol/?nombre={nombreRol}`
  > ***Note***: Parametro de la url nombreRol (string)

**Response**:

<strong>No retorna ninguna respuesta</strong>

</details>

---

<details>
<summary><h2>Permisos</h2></summary>
<br>

### Metodo GET

- `https://transborderuat.eastus.cloudapp.azure.com/msusuarios/api/v1/permiso/`
  > ***Note***: Parametro de la url nombreRol (string)

**Response**:

~~~
[
	{
		"id": 1,
		"nombre": "Crear y Editar rol",
		"codigo": "001"
	},
	{
		"id": 2,
		"nombre": "Consultar roles",
		"codigo": "002"
	},
	{
		"id": 3,
		"nombre": "Crear y Editar usuario",
		"codigo": "003"
	},
	{
		"id": 4,
		"nombre": "Consultar usuarios",
		"codigo": "004"
	},
	{
		"id": 5,
		"nombre": "Administrar sistema",
		"codigo": "005"
	},
	{
		"id": 6,
		"nombre": "Cargar tarifarios",
		"codigo": "006"
	},
	{
		"id": 7,
		"nombre": "Registrar tarifas seguro",
		"codigo": "007"
	},
	{
		"id": 8,
		"nombre": "Consultar tarifarios",
		"codigo": "008"
	},
	{
		"id": 9,
		"nombre": "Crear cotización",
		"codigo": "009"
	},
	{
		"id": 10,
		"nombre": "Clonar cotización",
		"codigo": "010"
	},
	{
		"id": 11,
		"nombre": "Aceptar cotización",
		"codigo": "011"
	},
	{
		"id": 12,
		"nombre": "Versionar cotización",
		"codigo": "012"
	},
	{
		"id": 13,
		"nombre": "Preparar instrucción de embarque",
		"codigo": "013"
	},
	{
		"id": 14,
		"nombre": "Clonar instrucción de embarque",
		"codigo": "014"
	},
	{
		"id": 15,
		"nombre": "Modificar instrucción de embarque",
		"codigo": "015"
	},
	{
		"id": 16,
		"nombre": "Consultar cotizaciones",
		"codigo": "016"
	},
	{
		"id": 17,
		"nombre": "Intervenir tarifas por Pricing",
		"codigo": "017"
	},
	{
		"id": 18,
		"nombre": "Consultar intervenciones pricing",
		"codigo": "018"
	},
	{
		"id": 19,
		"nombre": "Intervenir tarifas por Tier",
		"codigo": "019"
	},
	{
		"id": 20,
		"nombre": "Parametrizar tarifas específicas",
		"codigo": "020"
	},
	{
		"id": 21,
		"nombre": "Parametrizar etapas logísticas por incoterm",
		"codigo": "021"
	},
	{
		"id": 23,
		"nombre": "Parametrizar otros conceptos país",
		"codigo": "022"
	},
	{
		"id": 24,
		"nombre": "Generar reporte SPOT",
		"codigo": "050"
	},
	{
		"id": 25,
		"nombre": "Ver todas las cotizaciones",
		"codigo": "055"
	}
]
~~~

</details>

---

<details>
<summary><h2>Permisos</h2></summary>
<br>

### Metodo POST

- `https://transborderuat.eastus.cloudapp.azure.com/msusuarios/api/v1/rol/`

**Resquest**:

~~~
{
	"activo": true,
	"nombre": "pruebaDocs",
	"permisosRol": [
		{
			"codigo": "001",
			"id": 1,
			"nombre": "Crear y Editar rol",
			"selectedItem": true
		},
		{
			"codigo": "002",
			"id": 2,
			"nombre": "Consultar roles",
			"selectedItem": true
		},
		{
			"codigo": "003",
			"id": 3,
			"nombre": "Crear y Editar usuario",
			"selectedItem": true
		},
		{
			"codigo": "004",
			"id": 4,
			"nombre": "Consultar usuarios",
			"selectedItem": true
		},
		{
			"codigo": "005",
			"id": 5,
			"nombre": "Administrar sistema",
			"selectedItem": true
		},
		{
			"codigo": "006",
			"id": 6,
			"nombre": "Cargar tarifarios",
			"selectedItem": true
		},
		{
			"codigo": "007",
			"id": 7,
			"nombre": "Registrar tarifas seguro",
			"selectedItem": true
		},
		{
			"codigo": "008",
			"id": 8,
			"nombre": "Consultar tarifarios",
			"selectedItem": true
		},
		{
			"codigo": "009",
			"id": 9,
			"nombre": "Crear cotización",
			"selectedItem": true
		},
		{
			"codigo": "010",
			"id": 10,
			"nombre": "Clonar cotización",
			"selectedItem": true
		},
		{
			"codigo": "011",
			"id": 11,
			"nombre": "Aceptar cotización",
			"selectedItem": true
		},
		{
			"codigo": "012",
			"id": 12,
			"nombre": "Versionar cotización",
			"selectedItem": true
		},
		{
			"codigo": "013",
			"id": 13,
			"nombre": "Preparar instrucción de embarque",
			"selectedItem": true
		},
		{
			"codigo": "014",
			"id": 14,
			"nombre": "Clonar instrucción de embarque",
			"selectedItem": true
		},
		{
			"codigo": "015",
			"id": 15,
			"nombre": "Modificar instrucción de embarque",
			"selectedItem": true
		},
		{
			"codigo": "016",
			"id": 16,
			"nombre": "Consultar cotizaciones",
			"selectedItem": true
		},
		{
			"codigo": "017",
			"id": 17,
			"nombre": "Intervenir tarifas por Pricing",
			"selectedItem": true
		},
		{
			"codigo": "018",
			"id": 18,
			"nombre": "Consultar intervenciones pricing",
			"selectedItem": true
		},
		{
			"codigo": "019",
			"id": 19,
			"nombre": "Intervenir tarifas por Tier",
			"selectedItem": true
		},
		{
			"codigo": "020",
			"id": 20,
			"nombre": "Parametrizar tarifas específicas",
			"selectedItem": true
		},
		{
			"codigo": "021",
			"id": 21,
			"nombre": "Parametrizar etapas logísticas por incoterm",
			"selectedItem": true
		},
		{
			"codigo": "022",
			"id": 23,
			"nombre": "Parametrizar otros conceptos país",
			"selectedItem": true
		},
		{
			"codigo": "050",
			"id": 24,
			"nombre": "Generar reporte SPOT",
			"selectedItem": true
		},
		{
			"codigo": "055",
			"id": 25,
			"nombre": "Ver todas las cotizaciones",
			"selectedItem": true
		}
	]
}
~~~

**Response**:

~~~
{
	"id": 10,
	"nombre": "pruebaDocs",
	"permisosRol": [
		{
			"id": 5,
			"nombre": "Administrar sistema",
			"codigo": "005"
		},
		{
			"id": 7,
			"nombre": "Registrar tarifas seguro",
			"codigo": "007"
		},
		{
			"id": 11,
			"nombre": "Aceptar cotización",
			"codigo": "011"
		},
		{
			"id": 13,
			"nombre": "Preparar instrucción de embarque",
			"codigo": "013"
		},
		{
			"id": 8,
			"nombre": "Consultar tarifarios",
			"codigo": "008"
		},
		{
			"id": 4,
			"nombre": "Consultar usuarios",
			"codigo": "004"
		},
		{
			"id": 21,
			"nombre": "Parametrizar etapas logísticas por incoterm",
			"codigo": "021"
		},
		{
			"id": 24,
			"nombre": "Generar reporte SPOT",
			"codigo": "050"
		},
		{
			"id": 15,
			"nombre": "Modificar instrucción de embarque",
			"codigo": "015"
		},
		{
			"id": 16,
			"nombre": "Consultar cotizaciones",
			"codigo": "016"
		},
		{
			"id": 1,
			"nombre": "Crear y Editar rol",
			"codigo": "001"
		},
		{
			"id": 9,
			"nombre": "Crear cotización",
			"codigo": "009"
		},
		{
			"id": 10,
			"nombre": "Clonar cotización",
			"codigo": "010"
		},
		{
			"id": 19,
			"nombre": "Intervenir tarifas por Tier",
			"codigo": "019"
		},
		{
			"id": 23,
			"nombre": "Parametrizar otros conceptos país",
			"codigo": "022"
		},
		{
			"id": 25,
			"nombre": "Ver todas las cotizaciones",
			"codigo": "055"
		},
		{
			"id": 14,
			"nombre": "Clonar instrucción de embarque",
			"codigo": "014"
		},
		{
			"id": 20,
			"nombre": "Parametrizar tarifas específicas",
			"codigo": "020"
		},
		{
			"id": 6,
			"nombre": "Cargar tarifarios",
			"codigo": "006"
		},
		{
			"id": 17,
			"nombre": "Intervenir tarifas por Pricing",
			"codigo": "017"
		},
		{
			"id": 18,
			"nombre": "Consultar intervenciones pricing",
			"codigo": "018"
		},
		{
			"id": 3,
			"nombre": "Crear y Editar usuario",
			"codigo": "003"
		},
		{
			"id": 12,
			"nombre": "Versionar cotización",
			"codigo": "012"
		},
		{
			"id": 2,
			"nombre": "Consultar roles",
			"codigo": "002"
		}
	],
	"activo": true,
	"usuarioCreacion": "jgrisales@transborderaduat.onmicrosoft.com",
	"fechaCreacion": "2023-11-27T21:31:22.278+00:00",
	"usuarioModificacion": null,
	"fechaModificacion": null
}
~~~

</details>

</details>

<details>
<summary><h2>Consultar Rol</h2></summary>
<br>

### Metodo GET

- `https://transborderuat.eastus.cloudapp.azure.com/msusuarios/api/v1/rol/?nombre=pruebaDocs&activo=true`

**Response**:

~~~
[
	{
		"id": 10,
		"nombre": "pruebaDocs",
		"permisosRol": [
			{
				"id": 5,
				"nombre": "Administrar sistema",
				"codigo": "005"
			},
			{
				"id": 7,
				"nombre": "Registrar tarifas seguro",
				"codigo": "007"
			},
			{
				"id": 11,
				"nombre": "Aceptar cotización",
				"codigo": "011"
			},
			{
				"id": 13,
				"nombre": "Preparar instrucción de embarque",
				"codigo": "013"
			},
			{
				"id": 8,
				"nombre": "Consultar tarifarios",
				"codigo": "008"
			},
			{
				"id": 4,
				"nombre": "Consultar usuarios",
				"codigo": "004"
			},
			{
				"id": 21,
				"nombre": "Parametrizar etapas logísticas por incoterm",
				"codigo": "021"
			},
			{
				"id": 24,
				"nombre": "Generar reporte SPOT",
				"codigo": "050"
			},
			{
				"id": 15,
				"nombre": "Modificar instrucción de embarque",
				"codigo": "015"
			},
			{
				"id": 16,
				"nombre": "Consultar cotizaciones",
				"codigo": "016"
			},
			{
				"id": 1,
				"nombre": "Crear y Editar rol",
				"codigo": "001"
			},
			{
				"id": 9,
				"nombre": "Crear cotización",
				"codigo": "009"
			},
			{
				"id": 10,
				"nombre": "Clonar cotización",
				"codigo": "010"
			},
			{
				"id": 19,
				"nombre": "Intervenir tarifas por Tier",
				"codigo": "019"
			},
			{
				"id": 23,
				"nombre": "Parametrizar otros conceptos país",
				"codigo": "022"
			},
			{
				"id": 25,
				"nombre": "Ver todas las cotizaciones",
				"codigo": "055"
			},
			{
				"id": 14,
				"nombre": "Clonar instrucción de embarque",
				"codigo": "014"
			},
			{
				"id": 20,
				"nombre": "Parametrizar tarifas específicas",
				"codigo": "020"
			},
			{
				"id": 6,
				"nombre": "Cargar tarifarios",
				"codigo": "006"
			},
			{
				"id": 17,
				"nombre": "Intervenir tarifas por Pricing",
				"codigo": "017"
			},
			{
				"id": 18,
				"nombre": "Consultar intervenciones pricing",
				"codigo": "018"
			},
			{
				"id": 3,
				"nombre": "Crear y Editar usuario",
				"codigo": "003"
			},
			{
				"id": 12,
				"nombre": "Versionar cotización",
				"codigo": "012"
			},
			{
				"id": 2,
				"nombre": "Consultar roles",
				"codigo": "002"
			}
		],
		"activo": true,
		"usuarioCreacion": "jgrisales@transborderaduat.onmicrosoft.com",
		"fechaCreacion": "2023-11-27T21:31:22.277+00:00",
		"usuarioModificacion": null,
		"fechaModificacion": null
	}
]
~~~

</details>

