# Fotos verticais do modal

Para adicionar um link no código, abra `index.html` e procure `const modalPhotos`
perto do fim do array de espécies. Cole o endereço direto da imagem entre as
aspas ao lado da espécie desejada. Exemplo:

```js
"traira": "https://exemplo.com/foto-vertical-traira.jpg",
```

Use o link direto para o arquivo da foto, não o endereço da página que a contém.
Se o valor ficar vazio (`""`), o guia procura o arquivo local abaixo. Se essa
foto não carregar, usa a foto do card e depois uma imagem genérica de reserva.

Nomes de arquivos locais esperados:

| Espécie | Arquivo |
|---|---|
| Traíra | `traira.jpg` |
| Robalo-flecha | `robalo-flecha.jpg` |
| Robalo-peva | `robalo-peva.jpg` |
| Tainha | `tainha.jpg` |
| Tilápia-do-nilo | `tilapia.jpg` |
| Jundiá | `jundia.jpg` |
| Bagre-branco / bagre-marinho | `bagre-branco.jpg` |
| Saicanga / dentição | `saicanga.jpg` |
| Cará / acará | `cara.jpg` |
| Lambari | `lambari.jpg` |
| Carpa | `carpa.jpg` |
| Corvina | `corvina.jpg` |
