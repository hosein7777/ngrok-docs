<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Request

```bash
curl \
-X PUT \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"enabled":true,"inbound":[{"actions":[{"config":{"metadata":{"edgeId":"edgtls_2fKmdItkUN3OyJKyACXlvmNAE1Y","message":"Invalid TLS Version"}},"type":"log"},{"type":"deny"}],"expressions":["conn.TLS.Version.contains('1.3')"],"name":"AllowTLS1.3"}]}' \
https://api.ngrok.com/edges/tls/edgtls_2fKmdItkUN3OyJKyACXlvmNAE1Y/policy
```
