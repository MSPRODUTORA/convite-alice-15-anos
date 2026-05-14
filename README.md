# Convite Alice 15 Anos — Landing Page

## Estrutura

- `index.html`: página principal
- `assets/convite-alice.mp4`: coloque aqui o vídeo final de 29 segundos
- `assets/poster.jpg`: imagem inicial antes do play
- `assets/qr-pix.png`: QR Code Pix

## O que editar no index.html

Procure este bloco:

```js
const CONFIG = {
  whatsappNumber: "5586995265289",
  whatsappMessage: "Olá! Recebi o convite dos 15 anos da Alice e confirmo minha presença.",
  googleMapsUrl: "COLE_AQUI_O_LINK_DO_GOOGLE_MAPS",
  pixKey: "COLE_AQUI_A_CHAVE_PIX"
};
```

Troque:
- `whatsappNumber`
- `googleMapsUrl`
- `pixKey`

## Publicar na Vercel

1. Crie uma pasta no computador com estes arquivos.
2. Coloque o vídeo em `assets/convite-alice.mp4`.
3. Coloque o QR Code em `assets/qr-pix.png`.
4. Coloque uma imagem de capa em `assets/poster.jpg`.
5. Envie para um repositório no GitHub.
6. Na Vercel, clique em **Add New Project**.
7. Importe o repositório.
8. Framework Preset: **Other**.
9. Deploy.

## Observação

O vídeo fica sem controles visuais, sem barra de progresso e os botões aparecem somente após o evento `ended` do vídeo.
