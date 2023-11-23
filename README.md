

# Cotizador Docs

  

### Singing In

  

 - `Carga el inicio de sesion para ingresar con el usuario registrado previamente` [Singin in with user Faber Grisales.](%3CmxGraphModel%3E%3Croot%3E%3CmxCell%20id%3D%220%22%2F%3E%3CmxCell%20id%3D%221%22%20parent%3D%220%22%2F%3E%3CmxCell%20id%3D%222%22%20value%3D%22https%3A%2F%2Flogin.microsoftonline.com%2F1483316d-130f-4b72-a09e-3fb01c930c6d%2Foauth2%2Fv2.0%2Fauthorize%3Fclient_id%3Da2b8102f-0b84-4810-9d46-cae3e2a8f29f%26amp%3Bamp%3Bscope%3Duser.read%2520openid%2520profile%2520offline_access%26amp%3Bamp%3Bredirect_uri%3Dhttps%253A%252F%252Ftransborderuat.eastus.cloudapp.azure.com%252F%26amp%3Bamp%3Bclient-request-id%3D6c3ab0a8-24a7-4c91-9758-b5db21e81212%26amp%3Bamp%3Bresponse_mode%3Dfragment%26amp%3Bamp%3Bresponse_type%3Dcode%26amp%3Bamp%3Bx-client-SKU%3Dmsal.js.browser%26amp%3Bamp%3Bx-client-VER%3D2.38.3%26amp%3Bamp%3Bclient_info%3D1%26amp%3Bamp%3Bcode_challenge%3Dq37GBTsvBNMzWMIBvBncEL-XoElDGj2910adtUSk1kk%26amp%3Bamp%3Bcode_challenge_method%3DS256%26amp%3Bamp%3Bnonce%3D575cd5c1-ea93-4cd0-b297-280ad4fd0ee0%26amp%3Bamp%3Bstate%3DeyJpZCI6ImFhMDYyN2VkLWRhOTAtNGQxZS1hMDVmLWJhZDRlYTFkZTNlYyIsIm1ldGEiOnsiaW50ZXJhY3Rpb25UeXBlIjoicmVkaXJlY3QifX0%253D%22%20style%3D%22text%3Bhtml%3D1%3BstrokeColor%3Dnone%3BfillColor%3Dnone%3Balign%3Dcenter%3BverticalAlign%3Dmiddle%3BwhiteSpace%3Dwrap%3Brounded%3D0%3B%22%20vertex%3D%221%22%20parent%3D%221%22%3E%3CmxGeometry%20x%3D%22440%22%20y%3D%22210%22%20width%3D%22160%22%20height%3D%2260%22%20as%3D%22geometry%22%2F%3E%3C%2FmxCell%3E%3C%2Froot%3E%3C%2FmxGraphModel%3E)

- `API GET CREDENTIAL` [API](https://login.microsoftonline.com/common/GetCredentialType?mkt=es-ES)
Solicitud post que envia la siguiente data 
~~~
{
	"checkPhones": false,
	"country": "CO",
	"federationFlags": 0,
	"flowToken": "AQABAAEAAAAmoFfGtYxvRrNriQdPKIZ-ehyWAZgh8VgEnaNCxIr35dj-PUvw_6beF8e8hIuZmPpOFmdlYAxos4Dmgxwn6WAt6qfYb3DQ9872KcsT3HBIDan0tDaSEXP8ryDT9Fk8srxhgEidA10Gr_HD4I8-3dHauUqMaKGhqRxM5O5Q3sIQOTBMX-WeRZD07jdlTlrylCIpyVz3GOK3h4djXvvRE19YxP63WSLp2wYmq5p9mV-Sv5o5c1LlpAWeU_Zg51LRj0_ANbgxMAyvHn2PTXED5Q613GzzSf3odV9lp9CFaXJ-wI26J2aas55yKYSZmtRCOseoSl3aDsUR4I1WbW13ef14it8LTvajzoZUN9KOvKGcCv6civGTcyRQ0ydB3BORjvYmEuedkRbupIwbheAb4ntCP26IGsx_Vv7xURlBDQ-XJ5mK10MjlRfA5U7MrNoJPVBnIUGEOd6Lh0NgYW8rvEjU7QssBfK_bTl0UqiPOzKSujrXgnKv6HqMWx_1Lcd-2EFeEZfu7RzGNNoJs_jFA4RayjZ28vYbxSKPDgb97Cn2zyYzzeEGDzr-0DUNpw2DnbGEaLpLCtK2OTB_KmvRY9AXN6YDE9iJzf3Lgr6w-2i6qFRURXno9adDdxoUCeqmq3XJWm0T0VYjA7QZhGK4KzHhIAA",
	"forceotclogin": false,
	"isAccessPassSupported": true,
	"isCookieBannerShown": false,
	"isExternalFederationDisallowed": false,
	"isFidoSupported": true,
	"isOtherIdpSupported": false,
	"isRemoteConnectSupported": false,
	"isRemoteNGCSupported": true,
	"isSignup": false,
	"originalRequest": "rQQIARAAlZHPa9NgHMabZqu1oCsKsmMPZYozaX43KezQrWtNt7VzXdc0F3nz5k2bLGmyJF233vS0g4eJF5F58aJUkKEg04N4EISedpSBNwUdCOJp4MWOsT_A5_DhOX2_D8-TiDEkK5LsTZwhqVwaMJpIU4xBUJrIEdzIE5LOCQQEiEUMEA1GMvwrieTe2r2fB6928k9TsPD53XB6gNHtMPSCXCYT-qATaK6vI78LQhKBIOwGJLTdrg48jwT9ro9I6DqZAww7xLAfGDaIpoEoUEDSRYIzeEBwDC0RAEJ99FfMijQvZXVBOIpOVPPdsM2cwvXNPvoTjRs-aDmoEz7BPbRd9tQ5WZCtFq9akGs2yubiqtqurNbDSmF9q1mj-EpD5hcba-2mU7QqTJ1WC7BfmZMD2aFtvTRvVjuBCRo8pSrldpNd8TSGryNl1pYt14TO2jpQynaTvWMaCjUzwNPUmVjilGeA5-5cr_E0zYksSws6QbOUQXBaliEAJSGCNTSKhhJLQUEf4te7AfJJHwE95XqoY-opz3cN00Yp1zBss4PujipBQfAFxw7HsOOxa_FocmoST0VuTFF4Lh5PJCOTkVTkZAx7Nj6aCLfefKo_3Fu8_-ho99vz75HheMZQEbUEN2xLy2735J4FN1dqGUOQ4FKj1tKLxnqLLuvTmY2eWp-hc_RuDNuNXR3GJpwA2KQVkJrv9kYZf8ewnQuR9xf_f_LHCWyQmBb1hW2lu-oyG3qxulX3-z5nUYWGsgBrqhvMdrh5GSCmpJiBu5_APl6KnFx--fXthxcP_v66fTxxq03Jsy12U6Bl3qyzjr1cVQE3ulAyilkp31HyGixVheWe027N7Ccj_wA1",
	"username": "jgrisales@transborderaduat.onmicrosoft.com"
}
~~~
El response es el siguiente:
~~~
{
	"Username": "jgrisales@transborderaduat.onmicrosoft.com",
	"Display": "jgrisales@transborderaduat.onmicrosoft.com",
	"IfExistsResult": 0,
	"IsUnmanaged": false,
	"ThrottleStatus": 0,
	"Credentials": {
		"PrefCredential": 1,
		"HasPassword": true,
		"RemoteNgcParams": null,
		"FidoParams": null,
		"SasParams": null,
		"CertAuthParams": null,
		"GoogleParams": null,
		"FacebookParams": null,
		"OtcNotAutoSent": false
	},
	"EstsProperties": {
		"UserTenantBranding": [
			{
				"Locale": 0,
				"BannerLogo": "https://aadcdn.msftauthimages.net/dbd5a2dd-oibn8aahvqzuk9axjezt8gipakuxvaklx7dra8ibacg/logintenantbranding/0/bannerlogo?ts=638100893668399336",
				"Illustration": "https://aadcdn.msftauthimages.net/dbd5a2dd-oibn8aahvqzuk9axjezt8gipakuxvaklx7dra8ibacg/logintenantbranding/0/illustration?ts=637690390735308014",
				"BoilerPlateText": "<p><strong>Transborder UAT</strong></p>\n",
				"KeepMeSignedInDisabled": true,
				"UseTransparentLightBox": false
			}
		],
		"DomainType": 3
	},
	"FlowToken": "AQABAAEAAAAmoFfGtYxvRrNriQdPKIZ-7T6GoCJAh6k1skiQv1N2DoiBL58USTKikGgjurJ-foQldh5Os6jGXlfSPjWCxNUrKHN6kmy83Cqd2enpi9FanuGLrvDgEmpEveYVe79i9hWiGRS9-j5_vECe66yQdpMVFZYXoKDlzW6gnQorhNnfLgZes25pZQd4YUR361h7TLmE8DCuwYwWiqcIR0oeO4l17wgSilsR01NNbiyJHEN2uEVSGtknHbxDM0QCkMssUU9n2memjF9aCEn4trBGBlVNrm61N_Asl9uzPrJtPXSssjoBOHhsWeS06B4yF7deKylXqaHguvJ9gXH9uFKw-zc3xKEh0UhKDsScN9_S_IXiVDdrum9bnP10CfOyP_CCe9ee-sCNmXjjLby4OiXn15KYYJ_fyrDUdBCjwAs1kbG18CMingp74kmzIaCzmauZvcY0D4FWl7w-0W1j77hiHXS6IknWpKzkA5eGjIgYy14SYl7oNo7uWIFNjb-y1EHu6s0g4F2y6RrhKBgjzqKc_ZgKw3ZpJitdX9flWjhMhlwq23elA1N3yLwBZ1E8LJGgzSmNu7PdBrnF6gjWjigBEGIcr5P93i4vB1NVgsMi7YaEdwNKAtSoVWaMcQURRw_4894K6slpOlGCTWbABeSqNuLgIAA",
	"IsSignupDisallowed": true,
	"apiCanary": "PAQABAAEAAAAmoFfGtYxvRrNriQdPKIZ-RoTp1507GE4VzOH0rQqDKreMB5hZFMLf15wlcW7twnO1rw_kvRgziVSTE6NdrdGVeyMWslJgFMbc_UohQY5zMBwtvY69CZVBXtl3PSEKV-JPp04YXDNbGgLWNsmOmyXAu_uN5QGBSBBIuu9A0R94ge4PqWMq8AIZtbth0EPw6DXelUr3cHPkwxNMIhBGB26Sa0GVkUKZVNnK7AH1aD5wZSAA"
}
~~~ 
- Despues de esto, al iniciar sesión e ingresar el usuario correctamente, se carga se llaman a los siguientes endpoints:
`https://transborderuat.eastus.cloudapp.azure.com/config/app.config.json (GET) `
***Response***:
~~~
{
	"production": false,
	"clientId": "a2b8102f-0b84-4810-9d46-cae3e2a8f29f",
	"authority": "https://login.microsoftonline.com/1483316d-130f-4b72-a09e-3fb01c930c6d/",
	"redirectUrl": "https://transborderuat.eastus.cloudapp.azure.com/",
	"APIEndpoint": "https://transborderuat.eastus.cloudapp.azure.com/",
	"protectedResourceMap": "https://transborderADUAT.onmicrosoft.com/c436622e-2e79-4eb8-ace8-e953ebf50989/apiscope",
	"APIAdministracionMSEndpoint": "https://transborderuat.eastus.cloudapp.azure.com/msadministracion/api/v1/",
	"APIClientesMSEndpoint": "https://transborderuat.eastus.cloudapp.azure.com/msclientes/api/v1/",
	"APICotizacionesMSEndpoint": "https://transborderuat.eastus.cloudapp.azure.com/mscotizaciones/api/v1/",
	"APICotizacionesCPEndpoint": "https://transborderuat.eastus.cloudapp.azure.com/cpcotizaciones/api/v1/",
	"APITarifasMSEndpoint": "https://transborderuat.eastus.cloudapp.azure.com/mstarifas/api/v1/",
	"APITarifasCPEndpoint": "https://transborderuat.eastus.cloudapp.azure.com/cptarifas/api/v1/",
	"APIUsuariosMSEndpoint": "https://transborderuat.eastus.cloudapp.azure.com/msusuarios/api/v1/",
	"APIUsuariosCPEndpoint": "https://transborderuat.eastus.cloudapp.azure.com/cpusuarios/api/v1/",
	"APIArchivosMSEndpoint": "https://transborderuat.eastus.cloudapp.azure.com/msarchivos/api/v1/",
	"APIGraph": "https://graph.microsoft.com/v1.0/me",
	"firstLogin": "extension_a2b8102f0b8448109d46cae3e2a8f29f_firstLogin",
	"acceptedConditions": "extension_a2b8102f0b8448109d46cae3e2a8f29f_acceptedConditions"
}
~~~
`https://login.microsoftonline.com/common/discovery/instance?api-version=1.1&authorization_endpoint=https%3A%2F%2Flogin.microsoftonline.com%2F1483316d-130f-4b72-a09e-3fb01c930c6d%2Foauth2%2Fv2.0%2Fauthorize  (GET)`
***Response***:
~~~
{
	"tenant_discovery_endpoint": "https://login.microsoftonline.com/1483316d-130f-4b72-a09e-3fb01c930c6d/v2.0/.well-known/openid-configuration",
	"api-version": "1.1",
	"metadata": [
		{
			"preferred_network": "login.microsoftonline.com",
			"preferred_cache": "login.windows.net",
			"aliases": [
				"login.microsoftonline.com",
				"login.windows.net",
				"login.microsoft.com",
				"sts.windows.net"
			]
		},
		{
			"preferred_network": "login.partner.microsoftonline.cn",
			"preferred_cache": "login.partner.microsoftonline.cn",
			"aliases": [
				"login.partner.microsoftonline.cn",
				"login.chinacloudapi.cn"
			]
		},
		{
			"preferred_network": "login.microsoftonline.de",
			"preferred_cache": "login.microsoftonline.de",
			"aliases": [
				"login.microsoftonline.de"
			]
		},
		{
			"preferred_network": "login.microsoftonline.us",
			"preferred_cache": "login.microsoftonline.us",
			"aliases": [
				"login.microsoftonline.us",
				"login.usgovcloudapi.net"
			]
		},
		{
			"preferred_network": "login-us.microsoftonline.com",
			"preferred_cache": "login-us.microsoftonline.com",
			"aliases": [
				"login-us.microsoftonline.com"
			]
		}
	]
}
~~~