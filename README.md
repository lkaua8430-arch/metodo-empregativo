# 💼 O Método Completo Para Conseguir Seu Primeiro Emprego

Landing page de alta conversão para o curso **"O Método Completo Para Conseguir Seu Primeiro Emprego"** — um método estruturado em 9 módulos e 177 slides que transforma candidatos em profissionais contratados.

---

## 🚀 Deploy no GitHub Pages

1. Faça fork deste repositório ou crie um novo
2. Vá em **Settings → Pages** no seu repositório
3. Em **Source**, selecione **Deploy from a branch**
4. Escolha a branch `main` e pasta `/ (root)`
5. Clique em **Save**
6. Seu site estará disponível em: `https://seuusuario.github.io/nomedorepositorio/`

---

## 📦 Estrutura do Projeto

```
.
├── index.html          # Landing page completa (HTML + CSS + JS inline)
├── README.md           # Este arquivo
└── (opcional)
    ├── og-image.jpg    # Imagem 1200x630 para compartilhamento social
    └── manifest.json   # Manifesto PWA
```

---

## ✨ Funcionalidades

| Recurso | Descrição |
|---------|-----------|
| 🎨 **Design Dark Premium** | Paleta escura com dourado, transmitindo exclusividade |
| ✨ **Partículas Animadas** | Fundo interativo com partículas flutuantes |
| 📊 **Contadores Animados** | Números que sobem ao rolar a página |
| 📝 **Módulos Accordion** | Cards expansíveis com conteúdo dos 9 módulos |
| ❓ **FAQ Interativo** | Accordion com perguntas frequentes |
| 💬 **Depoimentos Carousel** | Slider automático de depoimentos |
| ⏱️ **Countdown Timer** | Urgência com contador regressivo |
| 📱 **Social Proof Popup** | Notificações simuladas de compras recentes |
| 🔒 **Sticky CTA** | Botão de compra fixo ao rolar |
| 📈 **Scroll Progress** | Barra de progresso no topo |
| 🎯 **Reveal on Scroll** | Animações ao entrar na viewport |
| 📱 **100% Responsivo** | Funciona em mobile, tablet e desktop |

---

## 🎨 Personalização

### Alterar o link de checkout

Localize no `index.html`:
```html
href="https://SEU_LINK_KIWIFY_AQUI"
```

Substitua por seu link real da Kiwify, Hotmart, Monetizze, etc.

### Alterar preços

Busque por:
- `R$ 97,00` → novo preço atual
- `R$ 497,00` → novo preço original
- `12x de R$ 9,74` → novo parcelamento

### Alterar dados do curso

- **9 módulos** → busque por `data-target="9"`
- **177 slides** → busque por `data-target="177"`
- **Tempo de leitura** → edite dentro de cada `.module-meta`

---

## 🖼️ Imagem de Compartilhamento (OG Image)

Para o link aparecer com preview no WhatsApp, Facebook e LinkedIn, crie uma imagem `og-image.jpg` (1200×630 pixels) e coloque na raiz do repositório.

Atualize esta meta tag no `<head>`:
```html
<meta property="og:image" content="https://seuusuario.github.io/seurepositorio/og-image.jpg">
```

---

## 📱 Instalação como App (PWA)

A página já possui meta tags para Progressive Web App. Para completar, crie um arquivo `manifest.json`:

```json
{
  "name": "Método Primeiro Emprego",
  "short_name": "1º Emprego",
  "start_url": ".",
  "display": "standalone",
  "background_color": "#0B0F1A",
  "theme_color": "#0B0F1A",
  "icons": [
    {
      "src": "icon-192.png",
      "sizes": "192x192",
      "type": "image/png"
    },
    {
      "src": "icon-512.png",
      "sizes": "512x512",
      "type": "image/png"
    }
  ]
}
```

---

## 🛡️ Garantia de 7 Dias

Este produto oferece garantia incondicional de 7 dias. Se o aluno não ficar satisfeito, o dinheiro é devolvido sem perguntas.

---

## 📄 Licença

© 2026 — Todos os direitos reservados.
Este material é destinado exclusivamente para fins educacionais.

---

> **Nota:** Este site não é afiliado ao Facebook, Instagram, LinkedIn ou qualquer outra rede social. Os resultados apresentados são de alunos reais, mas não garantimos resultados iguais para todos.
