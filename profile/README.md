# ZionCodes

**ZionCodes é o estúdio independente de José Fernando para criar software sob medida.**

O projeto existe para transformar problemas de negócio em sistemas web, APIs e automações que chegam ao ar com clareza, segurança e acompanhamento direto de quem os desenvolveu.

> Software sob medida. Atendimento direto comigo.

## O que a ZionCodes faz

- desenvolve sistemas web e plataformas internas;
- cria APIs, integrações e automações;
- conduz o projeto inteiro, da conversa inicial ao deploy e à evolução;
- trabalha com contrato, nota fiscal e comunicação direta com o responsável técnico.

A presença pública reúne a oferta, as áreas de atuação, projetos, depoimentos, currículo e canais de contato. O painel administrativo em `/admin/` permite manter esse conteúdo, acompanhar mensagens recebidas e gerar propostas em PDF.

## Identidade

A linguagem da ZionCodes é direta, técnica e humana. A marca fala com clareza sobre o problema e o trabalho necessário, sem promessas grandiosas ou jargão desnecessário. O atendimento é pessoal, mas a entrega é profissional e organizada.

O visual segue a ideia de uma **prancha de projeto e memorial descritivo**:

- composição editorial, com bastante espaço e hierarquia tipográfica;
- linhas finas de 1 px para organizar o conteúdo;
- cantos discretamente arredondados (`rounded-sm`), sem sombras decorativas;
- títulos em **Saira** e textos em uma pilha de fontes do sistema;
- azul como cor de ação, foco, seleção e marcação;
- marfim e grafite no tema claro, grafite azulado no tema escuro;
- suporte a tema claro/escuro e aos idiomas português e inglês;
- acessibilidade como parte do sistema: foco visível, alvos de toque amplos, navegação por teclado e respeito a movimento reduzido.

### Paleta de referência

| Uso | Claro | Escuro |
| --- | --- | --- |
| Ação da marca | `#1e4fd6` | `#6b95ff` |
| Fundo | `#f5f0e6` | `#0d1016` |
| Superfície | `#fbf8f2` | `#141821` |
| Texto principal | `#1c1f24` | `#ede8dd` |
| Texto secundário | `#5a5f68` | `#a3a9b4` |

Os tokens e a implementação visual vivem no frontend de referência em [`../zioncodes`](../zioncodes), especialmente em [`theme/static_src/src/styles.css`](../zioncodes/theme/static_src/src/styles.css), [`templates/components/brand.html`](../zioncodes/templates/components/brand.html) e [`home/templates/index.html`](../zioncodes/home/templates/index.html).

## Princípios de comunicação

1. **Direto:** explicar o que será feito e por quê.
2. **Próximo:** mostrar que o cliente fala diretamente com José Fernando.
3. **Concreto:** valorizar projetos, resultados e decisões reais.
4. **Responsável:** comunicar limites, prazos e escopo com honestidade.
5. **Cuidadoso:** manter a experiência acessível, rápida e legível em qualquer tela.

## Projeto de referência

O frontend em `../zioncodes` é a fonte de verdade da identidade aplicada: um site público renderizado pelo Django e um painel administrativo para conteúdo e leads.

Principais tecnologias do frontend:

- Django 6.1 com templates renderizados no servidor;
- Tailwind CSS via `django-tailwind`;
- HTMX e JavaScript próprio para interações pontuais;
- temas claro e escuro persistidos por cookie;
- WhiteNoise e Gunicorn para servir a aplicação.

Para executar ou alterar a aplicação, consulte o [`README.md`](../zioncodes/README.md) e o [`AGENTS.md`](../zioncodes/AGENTS.md) do projeto de referência.

## Contato

- Site: [zioncodes.com](https://zioncodes.com)
- Instagram: [@zioncodes](https://www.instagram.com/zioncodes)
- LinkedIn: [José Fernando](https://www.linkedin.com/in/ze-fernando)

