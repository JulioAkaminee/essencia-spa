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
| **JavaScript Vanilla** | Sem dependências de framework (sem React/Vue/GSAP) |
| **IntersectionObserver** | Scroll reveal com efeito *stagger* e contadores animados |
| **Lucide Icons** | Ícones modernos e leves |
| **Google Fonts** | **Cormorant Garamond** (display serif) + **Jost** (sans) |

---

## Seções do Site

1. **Hero** — Imagem com *parallax*, headline fluida e prova social
2. **Destaques + Estatísticas** — Diferenciais e contadores animados
3. **Serviços** — 6 rituais com imagens reais, preço e duração
4. **O Espaço** — Galeria com reveal escalonado e *image zoom*
5. **Rituais** — Faixa com *parallax* e CTA
6. **Depoimentos** — Avaliações de clientes
7. **Contato / CTA** — Agendamento via WhatsApp e telefone
8. **Footer** — Navegação, tratamentos e contato

---

## Destaques de UI/UX

- **Design premium** — glassmorphism, gradientes sutis, sombras em camadas
- **Tipografia fluida** com `clamp()` e hierarquia editorial
- **Animações sofisticadas** — scroll reveal, stagger, parallax, sheen em botões
- **Micro-interações** — hover states elegantes, glow, cursor customizado
- **Menu mobile** com hambúrguer animado e painel deslizante
- **Barra de progresso** de scroll e botão "voltar ao topo"

---

## Performance

- `loading="lazy"` nativo nas imagens (e `fetchpriority="high"` no hero)
- `preconnect` para fonts, CDNs e Pexels
- Animações em `transform`/`opacity` (GPU-accelerated) com `requestAnimationFrame`

---

## Acessibilidade

- Contraste WCAG AA, *skip link* e landmarks semânticas (`header`/`main`/`nav`/`footer`)
- `aria-label`, `aria-expanded` e `aria-hidden` em elementos interativos
- *Focus states* visíveis e suporte a `prefers-reduced-motion`

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
