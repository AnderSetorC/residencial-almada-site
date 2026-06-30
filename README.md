# Residencial Almada — Landing Page

Landing page direta para o Residencial Almada, com foco em **geração de leads via WhatsApp** (sem formulário). Botões em vários pontos do site abrem direto o WhatsApp da Pleniude Negócios Imobiliários.

## 📂 Estrutura

```
site/
├── index.html            ← Página principal (abrir no navegador)
├── LEIA-ME.md            ← Este arquivo
└── imagens/              ← Pasta com todas as imagens
    ├── fachada-portao.jpg       ← Logo/portão (capa e header)
    ├── logo-pleniude.png        ← Logo Pleniude (header + footer)
    ├── logo-blendi-original.png ← Logo Blendi (header + selos + faixa)
    ├── logo-blendi.jpg          ← Logo Blendi (variação)
    ├── logo-mcmv.png            ← Logo Minha Casa Minha Vida
    ├── logo-cohapar.jfif        ← Logo Cohapar
    ├── render-lazer-aerial.jpg  ← Slide principal do hero
    ├── fachada-noturna.jpg      ← Slide 2 do hero
    ├── piscina.jpg              ← Slide 3 do hero
    ├── sala-apartamento.jpg     ← Slide 4 do hero
    ├── academia.jpg, churrasqueira.jpg, espaco-pet.jpg,
    ├── salao-festas.jpg, playground.jpg, quadra-esportiva.jpg
    ├── render-panoramico.jpg, render-aerial.jpg, render-blocos-aerial.jpg
    ├── blocos-noturna.jpg, fachada-diurna.jpg, vista-externa-blocos.jpg
    ├── sala-jantar.jpg, quarto.jpg, capa-cozinha-sala.jpg
    ├── implantacao.jpg, mapa-localizacao.jpg
    ├── pdf-original/            ← Imagens brutas extraídas do PDF (48 PNGs)
    └── pdf-pages/               ← Páginas do PDF renderizadas (21 PNGs)
```

**Logos em destaque no site:**
- **Header:** logo da Pleniude (imobiliária) + logo da Blendi (incorporadora)
- **Barra de selos (topo):** Blendi + MCMV + Cohapar com selo "Incorporadora responsável", "Benefício MCMV", "Subsídio Cohapar"
- **Seção condição comercial:** faixa com Blendi, MCMV e Cohapar lado a lado
- **Faixa final de parceiros:** 3 cards brancos com Blendi, MCMV e Cohapar + descrição
- **Footer:** logo da Pleniude + selo **🔑 CRECI 9652** em destaque (amarelo)
- **CTA final:** selo **🔑 CRECI 9652** antes da assinatura da Pleniude

## 🚀 Como usar

1. **Hospedagem gratuita mais simples:** arraste a pasta `site/` para o Netlify Drop (https://app.netlify.com/drop) e ganhe um link público em segundos.
2. **Alternativa:** abra o arquivo `index.html` direto no navegador para visualizar localmente.

## ✨ Recursos da página

- **Hero animado** com slideshow automático (4 imagens)
- **Botão flutuante do WhatsApp** com animação de pulse (sempre visível)
- **Botões de CTA** em todas as seções, com mensagens pré-preenchidas diferentes
- **Galeria de lazer** com efeito hover (zoom + label)
- **Cards de benefícios** com animação ao entrar na tela (IntersectionObserver)
- **Cards da condição comercial** (R$ 399, 60x, R$ 75 mil, R$ 500)
- **Seção do apartamento** com 3 fotos internas
- **Seção de localização** com lista de distancias e mapa
- **CTA final** com chamada emocional
- **Responsivo** (mobile-first, ajusta pra celular e tablet)
- **Cores da marca:** verde (Almada) + amarelo (destaque MCMV) + WhatsApp green
- **Animações suaves:** fade-in ao rolar, hover em cards, pulse no WhatsApp

## 🔗 Links de WhatsApp pré-configurados

Todos os botões abrem o WhatsApp da **Pleniude** (43 99858-2436) com mensagens personalizadas:

| Botão | Mensagem |
|---|---|
| Header | "Quero saber mais sobre o Residencial Almada." |
| Hero principal | "Quero conhecer o Residencial Almada e fazer uma simulação." |
| Card do hero | "Quero fazer uma simulação para o Residencial Almada." |
| Condição comercial | "Quero aproveitar as condições do MCMV no Residencial Almada." |
| Galeria lazer | "Quero conhecer o condomínio clube do Residencial Almada." |
| Apartamento | "Quero ver as plantas e o apartamento decorado do Residencial Almada." |
| Localização | "Quero saber mais sobre a localização do Residencial Almada." |
| CTA final | "Olá! Quero conquistar minha casa própria no Residencial Almada." |
| Botão flutuante | "Tenho interesse no Residencial Almada e gostaria de mais informações." |

## 🛠️ Customizações rápidas

- **Mudar número do WhatsApp:** substituir `5543998582436` em todos os `href="https://wa.me/..."` do HTML.
- **Trocar imagens:** basta substituir os arquivos na pasta `imagens/` mantendo o mesmo nome.
- **Ajustar cores:** variáveis CSS no topo do `<style>` (`--verde-escuro`, `--amarelo` etc.).
- **Alterar textos:** todos os textos estão em português direto no HTML, fáceis de localizar.

## 📞 Contato da imobiliária

**Pleniude Negócios Imobiliários**
- Av. Maringá, 745 — Sala 2 · Londrina - PR
- 🔑 **CRECI 9652**
- WhatsApp: (43) 99858-2436
- Instagram: @plenitudedelondrina

**Incorporadora:** Blendi Empreendimentos
**Programas:** Minha Casa Minha Vida + Cohapar

## 📍 Endereço do empreendimento

**Residencial Almada**
Av. Giocondo Maturi, 1000 — Vista Bela
Londrina - PR · CEP 86081-542
[Ver no Google Maps](https://www.google.com/maps/search/?api=1&query=Av.+Giocondo+Maturi,+1000+-+Vista+Bela,+Londrina+-+PR,+86081-542)

---

*Apartamentos registrados no 2º Serviço de Registro de Imóveis da Comarca de Londrina/PR, sob nº R-7/98.612. Descontos válidos conforme programa Minha Casa Minha Vida vigente. Material meramente ilustrativo.*