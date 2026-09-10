# Ramires TV — Downloads oficiais

Repositório público usado apenas para distribuição e catálogo remoto do **Ramires TV**.

## Versão estável
- Versão atual: **2.2.0**
- APK versionada: `RamiresTV-2.2-release.apk`
- APK permanente: `RamiresTV-latest.apk`
- URL permanente para Downloader: `https://github.com/accesschatgptv2-arch/RamiresTV-Downloads/releases/latest/download/RamiresTV-latest.apk`
- Metadados e SHA-256 atual: `latest.json`

A URL permanente deve ser usada para criar o código do Downloader/AFTVnews. Em futuras versões, a URL continua igual e o asset `RamiresTV-latest.apk` passa a apontar para a versão estável mais recente.

## Novidades da 2.2
- nova identidade visual e ícone do Ramires TV;
- novo banner para Google TV;
- cards visuais para os serviços;
- indicação `INSTALADO` / `INSTALAR`;
- atalho para a Google Play Store oficial;
- catálogo remoto revisão 22;
- mesma identidade criptográfica da V2.1 para permitir atualização normal.

## Estrutura
- `catalog/catalog-v2.json`: catálogo remoto validado pelo app.
- `latest.json`: metadados da versão pública mais recente.
- Releases: APK release assinada + SHA-256.

## Segurança
- O código-fonte principal permanece no repositório privado `RamiresTV`.
- Este repositório não contém chave privada de assinatura, senhas ou secrets.
- O app aceita apenas pacotes Android e hosts previamente permitidos no código.
- O catálogo remoto não instala APKs nem executa código.
- Idade da Conta Google e controles parentais são gerenciados pelo Google TV/Google e não são alterados pelo Ramires TV.
