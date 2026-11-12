# Edihub

**Editais e vestibulares em um só lugar.**

Protótipo de front-end de uma plataforma que reúne editais de vestibulares e concursos, acompanha prazos e destaca retificações, para o estudante não perder nenhuma data importante.

🔗 **Demo:** https://arthur-moreira95.github.io/edihub/

> Protótipo de interface. Os dados são fictícios e login, checkout e alertas são simulados.

## Funcionalidades

- **Catálogo de editais** com UERJ, UFRJ/SiSU, ENEM, EsPCEx, IME, PUC-Rio, Fuvest e Colégio Naval
- **Busca** por edital (atalho `Ctrl + K`) e **filtros** por categoria (estaduais, federais/ENEM, particulares, militares) e por status (inscrições abertas, período de isenção, aguardando edital, retificação recente)
- **Linha do tempo** de cada certame: pedido de isenção, inscrições, homologação, cartão de confirmação, prova e resultados
- **Calendário de prazos** e destaque dos prazos da semana
- **Retificações** com comparação do que mudou (antes → depois)
- **Alertas** por e-mail e por WhatsApp em cada edital
- **Planos & Preços:** Grátis, Pro e Para Escolas (B2B), com painel de demonstração para coordenação
- **Tema claro/escuro** automático (respeita `prefers-color-scheme`) com alternância manual
- **Responsivo** e com suporte a `prefers-reduced-motion`

## Tecnologias

- HTML5 em arquivo único
- [React 18](https://react.dev/) (UMD, via CDN)
- [Tailwind CSS](https://tailwindcss.com/) (via CDN)

## Como rodar localmente

Não precisa instalar nada. Basta abrir o `index.html` no navegador (é necessária conexão com a internet para carregar React e Tailwind via CDN).

Ou, com um servidor local:

```bash
python -m http.server 8000
# abra http://localhost:8000
```

## Autor

**Arthur Moreira Costa**: [GitHub](https://github.com/Arthur-Moreira95)
