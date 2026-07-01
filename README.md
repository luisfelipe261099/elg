# ELG Telas Fachadeiras — Landing Page

Landing page de captação de clientes para a **ELG Telas Fachadeiras**, empresa de instalação e manutenção de telas fachadeiras para obras verticais em Curitiba e região.

Site estático de um arquivo só (`index.html`). Sem build, sem dependências. Abre direto no navegador e sobe em qualquer host.

> 🔗 **Demo:** _adicione o link do deploy aqui depois de publicar_

## ✨ Destaques

- Hero com prédio "envelopado" pela tela fachadeira (SVG animado) e régua de pavimentos.
- Identidade visual roxo→laranja da marca, fundo roxo-abismo.
- Tipografia técnica: Archivo Expanded (display), Manrope (corpo), JetBrains Mono (dados).
- Foco em conversão: WhatsApp com mensagem pré-preenchida, botão flutuante, CTAs no hero e no rodapé.
- 100% responsivo, acessível (foco de teclado, `prefers-reduced-motion`) e com SEO básico.

## 📁 Estrutura

```
.
├── index.html      # a página inteira (HTML + CSS + JS inline)
└── fotos/          # fotos das obras (obra-1.jpg, obra-2.jpg, obra-3.jpg)
```

## 🖼️ Trocar as fotos das obras

Coloque 3 fotos na pasta `fotos/` com estes nomes: `obra-1.jpg`, `obra-2.jpg`, `obra-3.jpg`.
As fotos aparecem sozinhas. Enquanto não existirem, fica um placeholder texturizado — o site nunca quebra.

## 💬 Editar depoimentos e contato

No `index.html`, busque por `DEPOIMENTOS` para colar as avaliações reais do Google.
Para trocar contato, substitua: `5541998869272` (WhatsApp), `comercial@elgtelasfachadeira.com.br`, `elg.telasfachadeira` (Instagram), `Guilherme Marconcin` (endereço).

## 🚀 Deploy

**Netlify (drag & drop):** arraste a pasta do projeto em https://app.netlify.com/drop
**Vercel:** `npm i -g vercel && vercel --prod`
**GitHub Pages:** Settings → Pages → branch `main` / pasta `/root`

---

Feito com ❤️ em Curitiba · _Segurança para sua obra._

---

## 🔎 SEO incluído

- **Schema `LocalBusiness`/`GeneralContractor`** (JSON-LD) na home, com endereço, telefone, área atendida e nota do Google.
- **`robots.txt`** liberando indexação + **`sitemap.xml`**.
- **Páginas de conteúdo** que capturam busca de intenção:
  - `/tela-fachadeira-preco-curitiba/` — o que define o preço por m²
  - `/tela-fachadeira-nr18/` — obrigatoriedade e a NR-18
  - `/tela-fachadeira-ou-andaime-fachadeiro/` — diferença entre os dois
- Cada página de conteúdo tem `FAQPage` + `BreadcrumbList` (elegível a rich results).
- Veja `MARKETING.md` para o guia de avaliações do Google.

**Pós-deploy:** cadastre o site no [Google Search Console](https://search.google.com/search-console) e envie o `sitemap.xml`.
