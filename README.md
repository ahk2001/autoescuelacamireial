# Autoescuela Camí Reial — Torrent (Valencia)

Portal institucional e plataforma de conversão da **Autoescuela Camí Reial**, centro oficial de formação de condutores em Torrent (Valencia).

🌐 **Domínio de Produção:** [https://autoescuelacamireial.com/](https://autoescuelacamireial.com/)  
📍 **Localização:** C/ de les Germanies, 68, 46900 Torrent, Valencia, Espanha  
📞 **Contato:** +34 961 29 05 55  
⭐ **Avaliação Google:** 4.8 / 5.0 (+120 resenhas)

---

## 🚀 Destaques do Projeto

- **Arquitetura High-Performance:** Construído em HTML5 Semântico, CSS3 Moderno com variáveis nativas e Vanilla JavaScript ultrarrápido sem dependências pesadas.
- **Mobile-First & Responsivo:** Design fluido adaptado para smartphones, tablets e desktops de alta resolução.
- **SEO & Open Graph:** Metadados estruturados, Open Graph, Twitter Cards, Schema.org LocalBusiness, `sitemap.xml` e `robots.txt`.
- **Segurança & Headers:** Configuração de cabeçalhos de segurança contra Clickjacking, MIME-Sniffing e XSS via `vercel.json`.
- **Acessibilidade:** Padrões WCAG, contraste rigoroso, navegação acessível e foco visual aprimorado.

---

## 📁 Estrutura de Diretórios

```
autoescuelacamireial/
├── assets/                  # Imagens otimizadas, logotipos e favicon
│   ├── aluna-aprovada-2.png
│   ├── aluna-aprovada-4.png
│   ├── aluno-aprovado-1.png
│   ├── aluno-aprovado-3.png
│   ├── aula-tablets.png
│   ├── aula-teorica-mural.png
│   ├── fachada-autoescuela.png
│   ├── favicon.png
│   ├── hero-desktop.png
│   ├── hero-mobile.png
│   ├── logo.png
│   ├── logobranca.png
│   ├── profesor-juan-carlos-1.png
│   └── profesor-juan-carlos-2.png
├── docs/                    # Dossiê de pesquisa, dados e especificações técnicas
│   ├── dados.txt
│   └── dossie_autoescola.md
├── index.html               # Página principal do site (One-Page Institucional)
├── robots.txt               # Diretivas de indexação para buscadores
├── sitemap.xml              # Mapa do site para motores de busca
├── vercel.json              # Configurações de segurança e cache para Vercel
├── .gitignore               # Arquivos e diretórios ignorados pelo Git
└── README.md                # Documentação técnica do projeto
```

---

## 🛠️ Tecnologias Utilizadas

- **HTML5 Semântico**
- **CSS3 Moderno** (CSS Grid, Flexbox, Custom Properties, Backdrop Filter)
- **Vanilla JavaScript** (Sem dependências externas desnecessárias para velocidade máxima)
- **Google Fonts** (Inter Tight, Plus Jakarta Sans, JetBrains Mono)

---

## 🔒 Segurança & Performance

- Proteção contra Clickjacking (`X-Frame-Options: SAMEORIGIN`)
- Proteção contra MIME-type sniffing (`X-Content-Type-Options: nosniff`)
- Política de Referrer restrita (`Referrer-Policy: strict-origin-when-cross-origin`)
- HSTS ativado para comunicação 100% HTTPS segura
- Cache imutável de 1 ano para arquivos estáticos (`/assets/`)
