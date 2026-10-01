# JPL Segurança Eletrônica — landing page

Site estático (HTML + CSS + JS puro, sem build) cujo objetivo é levar o visitante ao WhatsApp (18) 99655-7234.

## Estrutura

- `index.html` — a página inteira (estilos e script inline)
- `logo-jpl.png` — logo e favicon
- `img/` — fotos dos serviços

## Rodar localmente

```bash
npx serve .
```

Abrir o `index.html` direto no navegador não carrega as imagens, porque os caminhos começam com `/`.

## Deploy no Vercel

Importe o repositório no Vercel com o preset **Other**, sem comando de build e com o diretório de saída na raiz. Cada push na `main` publica uma nova versão.

## Pendências

- As fotos em `img/` são provisórias, recortadas de posts de referência e em baixa resolução. Troque por fotos próprias da JPL ou por imagens dos fabricantes em alta resolução, mantendo os mesmos nomes de arquivo.
- Confirmar se a JPL instala motores de portão PPA e Garen (card "Portão eletrônico").
- Incluir endereço, CNPJ e redes sociais no rodapé.
