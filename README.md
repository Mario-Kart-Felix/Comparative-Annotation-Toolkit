# Comparative-Annotation-Toolkit
I have a self-signed certificate for a SSL Web browser named shttpd.pem My Problem is certificate expired and need renew expiry date

Validity Not Before: Sep 16 03:21:22 2008 GMT Not After : Sep 16 03:21:22 2009 GMT

I need renew certificate for ten years

this is a capture of certificate

openssl x509 -text -in shttpd.pem
Certificate:
    Data:
        Version: 3 (0x2)
        Serial Number:
            86:22:84:0d:ba:09:d4:ca
    Signature Algorithm: sha1WithRSAEncryption
        Issuer: C=PL, ST=Some-State, O=Mini Webservice Ltd
        Validity
            Not Before: Sep 16 03:21:22 2008 GMT
            Not After : Sep 16 03:21:22 2009 GMT
        Subject: C=PL, ST=Some-State, O=Mini Webservice Ltd
        Subject Public Key Info:
            Public Key Algorithm: rsaEncryption
                Public-Key: (1024 bit)
                Modulus:
                    00:de:7e:0a:69:69:c7:06:f1:4b:3d:03:8b:45:dc:
                    ab:63:39:f6:44:30:9b:7c:a8:c0:ff:1c:b9:4f:29:
                    b1:1d:6b:ba:3d:16:7c:b1:bf:e8:67:d6:93:a4:f1:
                    68:b9:2c:44:e7:91:54:0c:cb:b2:ff:af:80:c3:83:
                    aa:84:84:a7:f9:b9:d8:1d:1a:b2:42:72:2d:2f:fe:
                    71:0c:4a:02:0c:35:34:12:d5:2a:bc:de:e1:a3:4f:
                    3c:7b:9c:12:32:56:71:ae:af:bc:76:b6:e4:55:f4:
                    2f:df:ff:eb:c7:43:87:b0:40:81:80:1e:1d:d3:77:
                    c9:66:50:ce:32:f2:f9:fa:a1
                Exponent: 65537 (0x10001)
        X509v3 extensions:
            Netscape Cert Type: 
                SSL Server
    Signature Algorithm: sha1WithRSAEncryption
         38:9e:5e:01:95:0c:7c:5c:4a:cd:57:e5:62:ee:50:90:7a:69:
         9e:4a:6f:74:f5:ad:7b:7a:63:b6:ad:94:1a:c1:ff:23:f9:8d:
         01:16:6c:62:c7:2d:bd:bb:54:ac:d5:43:a1:fe:60:8f:83:6a:
         20:7a:05:57:6f:54:0e:a5:bc:3a:9c:b9:e4:36:75:33:30:fd:
         b3:66:7d:ff:06:01:df:bf:e6:62:a6:d8:d0:e1:ba:d5:0f:4f:
         eb:df:99:27:2f:5d:63:1b:0d:15:b3:69:90:63:20:ed:ce:4b:
         b4:ad:db:e8:3c:67:5f:ed:39:44:e2:4c:c3:a3:c2:92:b9:f6:
         8c:a5
-----BEGIN CERTIFICATE-----
MIICEzCCAXygAwIBAgIJAIYihA26CdTKMA0GCSqGSIb3DQEBBQUAMEAxCzAJBgNV
BAYTAlBMMRMwEQYDVQQIEwpTb21lLVN0YXRlMRwwGgYDVQQKExNNaW5pIFdlYnNl
cnZpY2UgTHRkMB4XDTA4MDkxNjAzMjEyMloXDTA5MDkxNjAzMjEyMlowQDELMAkG
A1UEBhMCUEwxEzARBgNVBAgTClNvbWUtU3RhdGUxHDAaBgNVBAoTE01pbmkgV2Vi
c2VydmljZSBMdGQwgZ8wDQYJKoZIhvcNAQEBBQADgY0AMIGJAoGBAN5+Cmlpxwbx
Sz0Di0Xcq2M59kQwm3yowP8cuU8psR1ruj0WfLG/6GfWk6TxaLksROeRVAzLsv+v
gMODqoSEp/m52B0askJyLS/+cQxKAgw1NBLVKrze4aNPPHucEjJWca6vvHa25FX0
L9//68dDh7BAgYAeHdN3yWZQzjLy+fqhAgMBAAGjFTATMBEGCWCGSAGG+EIBAQQE
AwIGQDANBgkqhkiG9w0BAQUFAAOBgQA4nl4BlQx8XErNV+Vi7lCQemmeSm909a17
emO2rZQawf8j+Y0BFmxixy29u1Ss1UOh/mCPg2ogegVXb1QOpbw6nLnkNnUzMP2z
Zn3/BgHfv+ZiptjQ4brVD0/r35knL11jGw0Vs2mQYyDtzku0rdvoPGdf7TlE4kzD
o8KSufaMpQ==
-----END CERTIFICATE-----
