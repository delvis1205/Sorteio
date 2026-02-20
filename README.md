# n8n no Render.com

Este repositório foi limpo e configurado para rodar o **n8n** oficialmente no **Render.com** com o subdomínio `n8n.recargas.shop`.

## Como usar

1.  Acesse o painel do [Render](https://dashboard.render.com/).
2.  Clique em **"New +"** e selecione **"Blueprint"**.
3.  Conecte este repositório (`delvis1205/Sorteio`).
4.  O Render lerá o arquivo `render.yaml` e criará automaticamente o Web Service e o Banco de Dados Postgres.
5.  Após o deploy, configure o subdomínio `n8n.recargas.shop` no painel do Render e no seu provedor de DNS.

## Configurações Incluídas

-   **Imagem Oficial:** `n8nio/n8n:latest`
-   **Banco de Dados:** Render Postgres (Free)
-   **Domínio:** `n8n.recargas.shop`
-   **Protocolo:** HTTPS
