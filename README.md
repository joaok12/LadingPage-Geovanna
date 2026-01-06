# Dra. Rhaissa Rosa - Site Tricologista

Site estático profissional para a Dra. Rhaissa Rosa, especialista em tricologia.

## 📁 Estrutura do Projeto

```
tricologista_rhaissarosa-main/
├── css/                    # Arquivos CSS
├── fonts/                  # Fontes web (Lufga)
├── images/                 # Imagens e assets
├── index.html              # Página principal
├── sitemap.xml             # Sitemap para SEO
├── vercel.json             # Configuração do Vercel
└── README.md               # Este arquivo
```

## 🚀 Deploy no Vercel

### Opção 1: Via Vercel CLI

1. Instale a CLI do Vercel (se ainda não tiver):
```bash
npm i -g vercel
```

2. Faça login:
```bash
vercel login
```

3. Na raiz do projeto, execute:
```bash
vercel
```

4. Para fazer deploy em produção:
```bash
vercel --prod
```

### Opção 2: Via Vercel Dashboard

1. Acesse [vercel.com](https://vercel.com)
2. Clique em "Add New Project"
3. Importe o repositório ou faça upload dos arquivos
4. O Vercel detectará automaticamente como site estático
5. Clique em "Deploy"

## ⚙️ Configurações

O arquivo `vercel.json` inclui:

- **Clean URLs**: URLs sem extensão .html
- **Headers de Segurança**: X-Content-Type-Options, X-Frame-Options, X-XSS-Protection
- **Cache Otimizado**: Cache de 1 ano para assets estáticos (fonts, images, css)

## 🌐 SEO

- Meta tags otimizadas
- Open Graph e Twitter Cards configurados
- Sitemap.xml na raiz
- Schema.org (JSON-LD) implementado

## 📱 Recursos

- Design responsivo
- Performance otimizada
- Imagens em formato WebP
- Fontes web otimizadas (WOFF2)

## 📝 Notas

Este site foi otimizado para ser hospedado no Vercel com a melhor estrutura possível para desempenho e SEO.

