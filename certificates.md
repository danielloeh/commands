Show certificate list for certain page
openssl s_client -showcerts -connect mail.google.com:443          


Convert crt to pem
openssl x509 -inform DER -in from.crt -out to.pem  -text

Read certificate
openssl x509 -in cert.pem -text -noout
