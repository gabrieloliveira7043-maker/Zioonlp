# Zioon LP

Landing page de captação de leads da Zioon (CRM com WhatsApp e IA).

- `index.html`: página única (HTML, CSS e JS no mesmo arquivo).
- `zioon-192.png`: logo.

## Antes de publicar
1. Em `index.html`, troque `WA_NUMBER` pelo número do WhatsApp da Zioon (55 + DDD + número, só dígitos).
2. Pixel da Meta (ID 1764175301471520) já instalado no `<head>`. Eventos: PageView ao abrir, InitiateCheckout ao abrir o formulário e Lead quando o envio dá certo.
3. O formulário envia o lead para o CRM da Zioon pelo endereço `INBOUND_URL` (chave "LP Zioon anúncios", em Integrações). Para desativar, desligue a chave no CRM.

## Publicar no GitHub Pages
Settings > Pages > Deploy from a branch > `main` / root.
