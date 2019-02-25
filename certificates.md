## Manage Certificates

### Display certificates
* Show cert graph `openssl s_client -showcerts -connect mail.google.com:443`
* Show cert `openssl x509 -in cert.pem -text -noout`

### Conversions
* Convert crt to pem `openssl x509 -inform DER -in from.crt -out to.pem  -text`

