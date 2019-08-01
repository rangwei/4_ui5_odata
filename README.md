## Add a Proxy

[Create a local Proxy](https://openui5.hana.ondemand.com/#/topic/5bb388fc289d44dca886c8fa25da466e.html#loio5bb388fc289d44dca886c8fa25da466e__CORSAnywhere)

```
npm install
npm run proxy
```

## Update the odata url

- manifest.json

```
"dataSources": {
	  "invoiceRemote": {
		"uri": "http://localhost:8081/https://services.odata.org/V2/Northwind/Northwind.svc/",
		"type": "OData",
		"settings": {
		  "odataVersion": "2.0"
		}
	  }
	}
```	

## Test Run
