# SoftPlanTest

# Api Gateway Nginx

API gataway criado para subir e centralizar os endpoits das duas APIS criadas durante o desenvolvimento.

Api 1 : Criado para retornar a taxa de juros - https://github.com/RodrigoPrandi/TaxaJurosApi

Api 2 : Criado para calcular a taxa de juros consumindo a API 1 - https://github.com/RodrigoPrandi/TaxaJurosApi

# Executando com docker compose

```bash
docker-compose up
```

Após a execução poderá ser acessado os seguintes endpoint:


http://localhost/taxajuros : será redireconado para o endpoint publicado na API 1

http://localhost/showmethecode : será redireconado para o endpoint publicado na API 2

http://localhost/calculajuros?valorinicial=100&meses=5 : será redireconado para o endpoint publicado na API 2
