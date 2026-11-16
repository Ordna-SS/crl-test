PUBLIC TEST FILES
=================
ca.crt              Test root CA certificate (public)
client-valid.crt    Test certificate signed by the test CA
client-revoked.crt  Test certificate signed by the test CA; listed as revoked in crl.pem
crl.pem             Test Certificate Revocation List, signed by the test CA

These are synthetic test artifacts, not production credentials.
The matching private keys and CA private key are intentionally NOT included.
Upload these public files to your test repository to test HTTPS download and parsing.
