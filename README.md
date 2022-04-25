# cURL
cURL is a command-line tool for transferring data using various network protocols.

## Examples :
### calling a endpoint : 
``` powershell
curl -X GET "http://localhost:5051/application/1" -H  "accept: text/plain"
```

### callning a endpoint with HTTPS :
``` powershell
cURL --cert C:\Certificates\clientUAT.p12:test123 GET "http://localhost:5051/application/1"
```
