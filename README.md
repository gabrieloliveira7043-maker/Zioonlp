# Zioon LP

Landing page de captação de leads da Zioon (CRM com WhatsApp e IA).

- `index.html`: página única (HTML, CSS e JS no mesmo arquivo).
- `zioon-192.png`: logo.

## Antes de publicar
1. Em `index.html`, troque `WA_NUMBER` pelo número do WhatsApp da Zioon (55 + DDD + número, só dígitos).
2. Cole o código do pixel da Meta no comentário `META PIXEL` dentro do `<head>`.
3. O formulário envia o lead para o CRM da Zioon pelo endereço `INBOUND_URL` (chave "LP Zioon anúncios", em Integrações). Para desativar, desligue a chave no CRM.

## Publicar no GitHub Pages
Settings > Pages > Deploy from a branch > `main` / root.
