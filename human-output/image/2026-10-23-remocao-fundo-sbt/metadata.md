# Remoção de fundo — sbt Kids / O Picapau Amarelo vol. 6

- Data: 2026-10-23
- Entradas: logo sbt Kids (900x900 JPG) e capa "O Picapau Amarelo – Volume 6" (600x600 JPG), enviadas no chat.
- sbt Kids: Adobe Photoshop API (`image_remove_background`, via conector Adobe) -> PNG transparente.
- Capa Picapau: seleção por prompt da Adobe falhou nos títulos; recorte feito localmente (Python/PIL/scipy):
  letras de madeira por cor + contorno branco refeito (3 px), "volume 6" por desmistura contra branco,
  logo sbt MUSIC por flood-fill do branco externo. Bota do personagem entre "L" e "O" apagada manualmente.
- Saídas: PNG RGBA recortados (trim com 4 px de margem). O logo do Picapau (`picapau-amarelo-vol6-logo.png`) sai sem o sbt MUSIC, a pedido; o sbt MUSIC fica só no arquivo próprio.
