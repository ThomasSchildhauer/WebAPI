# WebAPI
Tests with WebAPI: SSL with IIS, SSL with OWIN, ...



SSLwithIIS

Pluralsight:
WebAPI V2 security
HTTP Security Primer
Demo Command LIne Tools and self hosting

command shell:
netsh http add urlacl:
This adds an URL reservation entry. Without it the WebAPI is blocked by Windows


netsh http add sslcert:
Adds a association between the urlacl port for the WebAPI and the certificate


httpconfig:
is a commandline tool that does both (urlacl and sslcert) with a small ui


Article from Microsoft to "working with SSL in WebAPI"
https://docs.microsoft.com/de-de/aspnet/web-api/overview/security/working-with-ssl-in-web-api