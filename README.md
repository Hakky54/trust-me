[![Apache2 license](https://img.shields.io/badge/license-Aache2.0-blue.svg)](https://github.com/Hakky54/sslcontext-kickstart/blob/master/LICENSE)

# Trust Me 🔐
A proof-of-concept GUI for prompting an user when a certificate is not trusted yet. 

This GUI app demonstrates the feature of [Trusting additional new certificates at runtime](https://github.com/Hakky54/sslcontext-kickstart?tab=readme-ov-file#trust-additional-new-certificates-at-runtime) from the library [sslcontext-kickstart](https://github.com/Hakky54/sslcontext-kickstart)
It might occur that your truststore has outdated certificates and is not easy to maintain or it just calls servers which has recently updated their certificates. 
This option demonstrates how to integrate it in your GUI app, and it will prompt when the certificate is not trusted yet, which gives the option to the end-user to either trust or reject it.

## Demo
![alt text](https://github.com/Hakky54/trust-me/blob/master/images/demo.gif?raw=true)

## Running locally

### Minimum requirements
- JDK 21
- Maven
- Terminal

Run the following commands in your terminal:

```bash
mvn clean package
mvn spring-boot:run
```

## Contributing

There are plenty of ways to contribute to this project:

* Give it a star
* Submit a PR
