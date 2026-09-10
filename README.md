# Ramires TV — Downloads oficiais

Repositório público usado apenas para distribuição e catálogo remoto do **Ramires TV**.

## Estrutura
- `catalog/catalog-v2.json`: catálogo remoto validado pelo app.
- `latest.json`: metadados da versão pública mais recente.
- Releases futuras: APK release assinada + SHA-256.

## Segurança
- O código-fonte principal permanece no repositório privado `RamiresTV`.
- Este repositório não contém chave privada de assinatura, senhas ou secrets.
- O app aceita apenas pacotes Android e hosts previamente permitidos no código.
- O catálogo remoto não instala APKs nem executa código.

## Instalação na TV
Quando a primeira release assinada for publicada, a URL HTTPS direta da APK será cadastrada no Downloader/AFTVnews para gerar o código numérico de instalação.

> Status atual: infraestrutura pública criada; release assinada pendente da configuração da chave privada no GitHub Actions.
