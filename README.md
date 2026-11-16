
# SSL Certificate Generator

Aplicativo desktop para geração de certificados SSL/TLS
autoassinados utilizando OpenSSL.

## Funcionalidades

- Geração de certificados X.509.
- Identificação de servidores por endereço IP.
- Configuração de Subject Alternative Name (SAN).
- Geração de chave privada (.key).
- Exportação de certificado (.crt).
- Exportação opcional para PKCS#12 (.pfx).
- Configuração de validade.
- Interface gráfica para Windows.

## Tecnologias

- Python
- CustomTkinter
- OpenSSL
- PyInstaller

## Desenvolvimento

Clone o repositório:

```bash
git clone URL_DO_REPOSITORIO
cd ssl-certificate-generator
```

Crie o ambiente virtual:

```bash
python -m venv .venv
```

Instale as dependências:

```bash
pip install -r requirements.txt
```

Execute:

```bash
python main.py
```

## Segurança

As chaves privadas geradas são armazenadas localmente.
Nunca compartilhe arquivos .key ou .pfx sem proteção.

## License

MIT