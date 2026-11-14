# Lunetta Ótica · Provador 3D (protótipo)

Site de ótica com provador virtual de óculos em tempo real e 3D, direto no navegador.

- Rastreamento do rosto ao vivo (MediaPipe Face Landmarker, 478 pontos) e armações 3D (three.js) com oclusão da cabeça.
- Distância pupilar estimada pela íris, tamanho ideal da armação, formato do rosto e subtom da pele.
- Tudo roda no aparelho do usuário; nenhuma imagem é enviada.

Nome, endereço, telefone, modelos e preços são exemplos provisórios.

A câmera só funciona em `https` (ou `localhost`). Para testar localmente: `python3 -m http.server` e abrir `http://localhost:8000`.
