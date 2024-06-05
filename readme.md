# Cobre diretamente por pix

## Uso

```bash
pip install -r requirements.txt
```

```bash
python pixqrcodegen.py
```

```py
Payload('Seu nome Sobrenome', 'Chave Pix', '1 .00', 'Sua Cidade', 'LOJA01').gerarPayload()
```

- **Nome:** Nome e sobrenome (Como estão no app do banco)
- **Chave Pix:** CPF (12345678910)
- **Valor:** R$ 1.00
- **Cidade:** Sao Paulo (Sem acentos)
- **Loja:** LOJA01
