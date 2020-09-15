# EngHaw
Junção dos projetos `web`, `api` e `crawler` sobre Engenheiros do Hawaii / Pouca Vogal / Humberto Gessinger.

---
## Configuração do Ambiente
A configuração do ambiente é feita via `docker` utilizando `docker-compose`.

O `docker` possui os seguintes containers:

- `enghaw-enghaw-api-php-fpm` => Container do PHP na versão `7.4 (FPM)` (Esse container já dispõe de `Composer` na versão `latest`)
- `enghaw-enghaw-api-nginx` => Container do Nginx na versão `1.16`
- `enghaw-enghaw-api-elasticsearch` => Container do ElasticSearch na versão `7.6.2`
- `enghaw-enghaw-crawlers-php-fpm` => Container do PHP na versão `7.4 (FPM)` (Esse container já dispõe de `Composer` na versão `latest`)
- `enghaw-enghaw-web-node` => Container do Node na versão `12` 

Para executar todos os containers, utilizar `docker-compose up -d`

---
## Configuração da Aplicação:
- Copiar `.env.example` para `.env`

---
## Servindo a Aplicações
Ler os `README.md` das aplicações dentro de seus respectivos submódulos para entender seu funcionamento e configuração
