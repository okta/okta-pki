# Description
This repository contains all of Okta's public facing certificates. Customers that require a copy of these certificates prior to their deployment can subscribe to release notifications.

# Certificates
|Certificate Name | Endpoint Type | Environment | Cells |  
|--|--|--|--|
| [*.okta.com](https://github.com/okta/okta-pki/blob/master/certificates/*.okta.com/*.okta.com.crt) | TLS1.2 | Production | OK1-OK16 |
| [*.oktapreview.com](https://github.com/okta/okta-pki/blob/master/certificates/*.oktapreview.com/*.oktapreview.com.crt) | TLS1.2 | Preview | OP1-OP3 |
| [*.okta-emea.com](https://github.com/okta/okta-pki/blob/master/certificates/*.okta-emea.com/*.okta-emea.com.crt) | TLS1.2 | EMEA | EU1 |
| [*.oktacdn.com](https://github.com/okta/okta-pki/blob/master/certificates/*.oktacdn.com/*.oktacdn.com.crt) | TLS1.2 | Global | Global |
| [*.mtls.okta.com](https://github.com/okta/okta-pki/blob/master/certificates/*.mtls.okta.com/*.mtls.okta.com.crt) | mTLS | Production | OK1-OK16 |
| [*.mtls.oktapreview.com](https://github.com/okta/okta-pki/blob/master/certificates/*.mtls.oktapreview.com/*.mtls.oktapreview.com.crt) | mTLS | Preview | OP1-OP3 |
| [*.mtls.okta-emea.com](https://github.com/okta/okta-pki/blob/master/certificates/*.mtls.okta-emea.com/*.mtls.okta-emea.com.crt) | mTLS | EMEA | EU1 |
| [*.kerberos.okta.com](https://github.com/okta/okta-pki/blob/master/certificates/*.kerberos.okta.com/*.kerberos.okta.com.crt) | Kerberos | Production | OK1-OK16 |
| [*.kerberos.oktapreview.com](https://github.com/okta/okta-pki/blob/master/certificates/*.kerberos.oktapreview.com/*.kerberos.oktapreview.com.crt) | Kerberos | Preview | OP1-OP3 |
| [*.kerberos.okta-emea.com](https://github.com/okta/okta-pki/blob/master/certificates/*.kerberos.okta-emea.com/*.kerberos.okta-emea.com.crt) | Kerberos | EMEA | EU1 |
| [*.ldap.okta.com](https://github.com/okta/okta-pki/blob/master/certificates/*.ldap.okta.com/*.ldap.okta.com.crt) | LDAP | Production | OK1-OK16 |
| [*.ldap.oktapreview.com](https://github.com/okta/okta-pki/blob/master/certificates/*.ldap.oktapreview.com/*.ldap.oktapreview.com.crt) | LDAP | Preview | OP1-OP3 |
| [*.ldap.okta-emea.com](https://github.com/okta/okta-pki/blob/master/certificates/*.ldap.okta-emea.com/*.ldap.okta-emea.com.crt) | LDAP | EMEA | EU1 |

# HTTP Public Key Pinning
[HTTP Public Key Pinning](https://en.wikipedia.org/wiki/HTTP_Public_Key_Pinning) (HPKP) is a deprecated standard that is highly advised against by multiple authoritative bodies and certificate authorities. Okta stands with other industry leaders in advising against the use of HPKP

https://www.digicert.com/blog/certificate-pinning-what-is-certificate-pinning  
https://developer.mozilla.org/en-US/docs/Web/HTTP/Public_Key_Pinning

# Disclaimer
Okta reserves the right to revoke, reissue, and/or renew any certificates at any time without prior notification in order to maintain the safety and security of our customers and services.
