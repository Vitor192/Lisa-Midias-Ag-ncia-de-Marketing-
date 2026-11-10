# LR Mídias

Site institucional da LR Mídias, agência de marketing digital.

Página única e minimalista, com uma cena 3D (Three.js) que acompanha a rolagem: cada seção tem seu próprio modelo 3D e a câmera desce junto com quem rola a página.

## O que tem no site

- Sobre, serviços e resultados
- Portfólio de clientes
- Seção "O que os nossos clientes estão dizendo"
- Localização e "Como chegar"
- Contato (WhatsApp, e-mail e Instagram)

## Recursos

- Cena 3D fixa ao fundo, guiada pela rolagem, com indicador de seção e barra de progresso
- Inclinação 3D nos depoimentos e animações ao passar o mouse
- Responsivo, com ajustes para celular
- Tema claro e escuro automáticos
- Respeita a preferência "reduzir movimento" do aparelho
- Se o WebGL não estiver disponível, a página continua funcionando sem a cena 3D

## Como ver

Abra o `index.html` no navegador. Não precisa instalar nada. O Three.js (r128) e as fontes carregam por CDN, então é preciso estar online.

Para publicar de graça: em **Settings → Pages**, escolha a branch `main` e a pasta `/ (root)`.

## Pendências

- Trocar o destino do mapa em `#localizacao` pelo endereço completo da LR.
- Colocar os links individuais dos depoimentos em vídeo.
