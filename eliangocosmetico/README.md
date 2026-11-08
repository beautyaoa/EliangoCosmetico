# Eliango Cosmético — Site

Site estático do salão Eliango Cosmético (Elizabeth Raimundo).

## Design
**Minimalist Luxury** — linhas finas, espaço generoso, tipografia leve, rosa suave.

- Fonte: Montserrat (alinhada com o logo)
- Header: barra de anúncio + transparente no hero → sólido no scroll + drawer mobile à esquerda
- Homepage: hero com vídeo, sobre, serviços, card da loja, formações, depoimentos, galeria
- Footer: signup WhatsApp + redes sociais + navegação

## Stack
- HTML / CSS / JS puro
- Carrinho em `localStorage` (`js/cart.js`)
- Pronto para GitHub + Cloudflare Pages
- Mobile first
- Português (padrão) + toggle Inglês

## Páginas
| Ficheiro | Conteúdo |
|----------|----------|
| `index.html` | Homepage completa |
| `produtos.html` | Loja |
| `checkout.html` | Checkout do carrinho |
| `inscricao.html` | Ficha de inscrição nas formações |

## Formações
- Formação 1 Semana — 15.000 Kz
- Formação 2 Semanas — 30.000 Kz
- Formação 3 Semanas — 45.000 Kz
- Formação 4 Semanas — 60.000 Kz
- Formação de Maquiagem — 35.000 Kz (3 semanas · Seg, Ter, Qua)

## Deploy

### GitHub + Cloudflare Pages
1. Cria repo no GitHub e faz push desta pasta
2. Cloudflare Pages → Create project → Connect Git
3. Build command: (vazio)
4. Output directory: `/`
5. Deploy

### Upload direto
Zip da pasta → Cloudflare Pages → Upload assets

## Contacto no site
- WhatsApp: +244 938 720 335
- Instagram: @eliangocosmetico
- Facebook: profile id 100077515462072
- Local: Benfica, Via Expressa (frente AngoMart), Talatona, Luanda

## Estrutura
```
eliangocosmetico/
├── index.html
├── produtos.html
├── checkout.html
├── inscricao.html
├── css/style.css
├── js/
│   ├── main.js
│   └── cart.js
├── images/
├── media/
│   └── hero.mp4
└── README.md
```

## Notas
- Signup no footer envia número para WhatsApp (novidades).
- Texto de consentimento sob o formulário de novidades.
- Preços de produtos: confirmar/atualizar quando houver lista definitiva.
- Galeria: preferir fotos reais do Instagram quando possível.
