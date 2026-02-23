# 🚀 PROGRESSAR — Guia de Deploy Completo

## 📁 Estrutura de arquivos necessária

```
progressar/
├── index.html          ← renomear o progressar.html para index.html
├── manifest.json       ← arquivo deste pacote
├── service-worker.js   ← arquivo deste pacote
└── icons/
    ├── icon-72.svg
    ├── icon-96.svg
    ├── icon-128.svg
    ├── icon-192.svg
    └── icon-512.svg
```

---

## PASSO 1 — Criar conta no GitHub (grátis)

1. Acesse: https://github.com
2. Clique em "Sign up"
3. Crie sua conta (pode usar qualquer e-mail)

---

## PASSO 2 — Criar o repositório

1. Após logar, clique no "+" no topo direito → "New repository"
2. Nome do repositório: `progressar` (exatamente assim, minúsculo)
3. Marque como **Public**
4. Clique em "Create repository"

---

## PASSO 3 — Fazer upload dos arquivos

1. Na página do repositório, clique em "uploading an existing file"
2. Arraste TODOS os arquivos:
   - `index.html` (o progressar.html renomeado)
   - `manifest.json`
   - `service-worker.js`
   - A pasta `icons/` com os 5 arquivos SVG
3. Clique em "Commit changes"

---

## PASSO 4 — Ativar o GitHub Pages

1. No repositório, clique em **Settings** (engrenagem)
2. No menu lateral esquerdo, clique em **Pages**
3. Em "Branch", selecione **main** e pasta **/ (root)**
4. Clique em **Save**
5. Aguarde ~2 minutos

Seu app estará disponível em:
👉 `https://SEU_USUARIO.github.io/progressar`

---

## PASSO 5 — Testar o PWA

1. Abra o link no Chrome do Android
2. Um banner vai aparecer: **"Adicionar PROGRESSAR à tela inicial"**
3. Aceite — o app instala como se fosse da Play Store

---

## PASSO 6 — Publicar na Play Store via TWA (opcional, U$ 25)

Após o PWA funcionando:

1. Acesse: https://bubblewrap.glitch.me
2. Cole a URL do seu GitHub Pages
3. O site gera o APK automaticamente
4. Crie conta de desenvolvedor em: https://play.google.com/console
   - Taxa única: U$ 25 (~R$ 130)
5. Faça upload do APK → preencha a ficha do app → publique

Tempo de aprovação do Google: **2 a 7 dias úteis**

---

## 🔗 Landing Page

A landing page (`progressar-landing.html`) fica separada do app:

**Opção gratuita:** sobe também no GitHub Pages
- Renomeie para `landing.html`
- Acesse em: `https://SEU_USUARIO.github.io/progressar/landing.html`

**Opção profissional:** use o Carrd.co (R$ 0 ou R$ 19/ano)
- Mais fácil de editar, domínio personalizado disponível

**Futuramente com domínio próprio:**
- Compre `progressar.app` ou `progressar.com.br` (~R$ 50-80/ano no Registro.br)
- Aponte para o GitHub Pages nas configurações DNS

---

## 📱 Fluxo completo do usuário

```
Stories/Bio Instagram
        ↓
Landing Page (progressar-landing.html)
        ↓
Botão "Abrir o App Grátis"
        ↓
App (index.html no GitHub Pages)
        ↓
Banner automático: "Instalar na tela inicial"
        ↓
Ícone PROGRESSAR na tela do celular 🎉
```

---

## 💰 Custos totais

| Item | Custo |
|------|-------|
| GitHub Pages (hospedagem) | GRÁTIS |
| PWA (instalável) | GRÁTIS |
| Conta Google Play | U$ 25 (uma vez) |
| Domínio .com.br (opcional) | ~R$ 50/ano |
| **Total mínimo** | **R$ 0** |
| **Total com Play Store** | **~R$ 130** |

