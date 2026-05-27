# Essência Spa

Landing page de **nível premium** para clínica de estética e spa localizada em **Bragança Paulista**, São Paulo.

---

## Sobre o Projeto

O **Essência Spa** é um site de demonstração que apresenta o potencial de experiências digitais imersivas para o nicho de **bem-estar, estética e spa**.

O projeto combina um design refinado de inspiração editorial com animações fluidas, glassmorphism e micro-interações, criando uma atmosfera de tranquilidade e luxo — single-file, sem build, sem frameworks pesados.

---

## Tecnologias Utilizadas

| Tecnologia | Descrição |
|-----------|-----------|
| **HTML5** | Estrutura semântica, landmarks e acessibilidade (WCAG AA) |
| **Tailwind CSS (CDN)** | Utilitários + customizações em `@layer base/components/utilities` |
| **JavaScript Vanilla** | Sem framework (sem React/Vue) — toda a lógica em ~1 arquivo |
| **IntersectionObserver** | Scroll reveal com *stagger*, contadores animados e *scrollspy* |
| **GSAP + ScrollTrigger (CDN)** | *Parallax* suave com `scrub` — degrada para fallback se não carregar |
| **Lucide Icons** | Ícones modernos e leves |
| **Google Fonts** | **Cormorant Garamond** (display serif) + **Jost** (sans) |

---

## Seções do Site

1. **Hero** — Imagem com *parallax*, headline fluida e prova social
2. **Marquee** — Faixa rolante com as especialidades do spa
3. **Destaques + Estatísticas** — Diferenciais e contadores animados
4. **Serviços** — 6 rituais com imagens reais, preço e duração
5. **O Espaço** — Galeria com reveal escalonado e *image zoom*
6. **Pacotes** — Três jornadas de bem-estar em cards de preço (com destaque)
7. **Faixa parallax** — CTA de vale-presente e rituais a dois
8. **Depoimentos** — Avaliações de clientes
9. **FAQ** — Acordeão acessível de dúvidas frequentes
10. **Contato / CTA** — Agendamento via WhatsApp e telefone
11. **Footer** — Navegação, tratamentos e contato

---

## Destaques de UI/UX

- **Design premium** — glassmorphism, gradientes sutis, sombras em camadas
- **Tipografia fluida** com `clamp()` e hierarquia editorial
- **Animações sofisticadas** — scroll reveal, stagger, parallax (GSAP), sheen em botões
- **Micro-interações** — botões magnéticos, tilt 3D, cursor customizado, hover states
- **Bordas com gradiente fino** (`mask-composite`) e *skeleton shimmer* no carregamento das imagens
- **Menu mobile** com hambúrguer animado e painel deslizante
- **Scrollspy** — link de navegação ativo conforme a seção visível
- **Barra de progresso** de scroll e botão "voltar ao topo"

---

## Performance

- `loading="lazy"` nativo nas imagens (e `fetchpriority="high"` + `preload` no hero)
- `preconnect` / `dns-prefetch` para fonts, CDNs e Pexels
- Animações em `transform`/`opacity` (GPU-accelerated) com `requestAnimationFrame`
- Libs externas com `defer`; observers desconectam após disparar (`unobserve`)

---

## Acessibilidade

- Contraste WCAG AA, *skip link* e landmarks semânticas (`header`/`main`/`nav`/`footer`)
- `aria-label`, `aria-expanded` e `aria-hidden` em elementos interativos (nav, menu, FAQ)
- *Focus states* visíveis e suporte completo a `prefers-reduced-motion`
- Acordeão de FAQ navegável por teclado com `aria-expanded` sincronizado

---

## Identidade Visual

- **Paleta:** Rosa terroso (`#B0503C`) + Lavanda suave (`#8B7AB0`) + base linen/areia + acento dourado
- **Estilo:** Editorial / Soft UI / Glassmorphism / Luxo / Relaxamento
- **Sensações:** Tranquilidade, cuidado, sofisticação

---

## Desenvolvido por

**Akamine Web Studio** — Bragança Paulista, SP

Site: [https://akaminewebstudio.com.br](https://akaminewebstudio.com.br)

GitHub: [@JulioAkaminee](https://github.com/JulioAkaminee)

---

## Licença

Projeto de uso exclusivo para demonstração de portfólio. Todos os direitos reservados © 2026 Akamine Web Studio.
