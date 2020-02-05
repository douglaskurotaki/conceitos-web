# R023 - HTTPs
**HTTP Seguro**
- HTTP + TLS(Transport Layer Scurity Protocol) - Evolução do SSL
- HTTP + SSL (Secure Sockets Layer Protocol)

Certificado <> Protocolo **porém são usados juntos**

- Dados são criptografados usando os protocolos TLS ou SSL
- Protege contra interceptação(MITM)
- Criptografia todas as informações: URL, cookies e headers
- Usa certificados digitais

### Autoridade Certificadora
- Organização e emissão de certificado para habilitar o https entre o servidor web e o browser
- Browser precisar **criptografar** e o servidor **descriptografar**
- Browser precisa ter **instalado** também o certificado para **validar**
- Let's Encrypt + certbot (Automatização da instação do certificado)
- HTTPs gera overhead, porém não é isso que deixa a aplicação lenta