# Viralix — Landing Page "Método Amostra"

Landing page da Viralix (viralix.com.br): site, Google e identidade visual para empresas da Região de Campinas, com a oferta "veja o site da sua empresa pronto antes de pagar".

Site estático (HTML + CSS puro, sem build). Pronto para publicar na Vercel.

## Estrutura

```
index.html      → a página inteira (HTML + CSS + animações)
imagens/        → logo e prints do portfólio
vercel.json     → configurações da Vercel (URLs limpas e cache das imagens)
```

## Trocar os links dos botões

Todos os botões apontam para `https://substituaesseconteudo.com.br`.

- **Trocar todos de uma vez:** no editor, Localizar e substituir (Ctrl+H) → `substituaesseconteudo.com.br` → seu link.
- **Um por um:** cada botão tem um comentário acima, no formato `<!-- LINK 02 | Botão principal (primeira dobra) ... -->`.

Sugestão de link do WhatsApp:
`https://wa.me/5519996074320?text=Ol%C3%A1!%20Quero%20ver%20a%20amostra%20do%20site%20da%20minha%20empresa`

## Pendências antes de divulgar

- [ ] Trocar os links `substituaesseconteudo.com.br`
- [ ] Preencher `[INSERIR Nº]` (projetos por mês, bloco "Agenda limitada")
- [ ] Trocar o print da Mirai Company (hoje é o Instagram) pelo print do site
- [ ] Confirmar autorização dos clientes para usar nome e logo
- [ ] Criar a página de Política de privacidade (LGPD)
- [ ] Instalar Pixel da Meta, GA4 e tag do Google Ads

## Publicar na Vercel

1. Suba estes arquivos num repositório do GitHub.
2. Em vercel.com → **Add New → Project** → importe o repositório.
3. Framework Preset: **Other**. Não precisa de Build Command nem Output Directory.
4. Clique em **Deploy**. Cada novo commit no GitHub publica automaticamente.

## Ver no computador

Basta abrir o `index.html` no navegador.
