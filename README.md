# Nosso-Cinema

Um catálogo e cronograma de filmes e séries para casais organizarem as sessões de fim de semana — com título vindos de todos os principais streamings (Netflix, Disney+, HBO Max, Prime Video e Apple TV+), cada um estilizado com a identidade visual da sua plataforma.

![status](https://img.shields.io/badge/status-em%20uso-brightgreen)
![stack](https://img.shields.io/badge/stack-HTML%20%7C%20CSS%20%7C%20JavaScript-1e1338)
![licença](https://img.shields.io/badge/licença-MIT-e8637c)

---

## 🎬 Sobre o projeto

Sabe aquele momento de indecisão pra escolher o que assistir no sábado à noite? O **Nosso-Cinema** resolve isso: é uma página única, sem backend, onde o casal monta um catálogo de filmes/séries, agenda o que vai assistir em cada dia e acompanha o que já foi visto — tudo num visual inspirado em cinema, com cada título ganhando as cores do streaming a que pertence.


## ✨ Funcionalidades

- **Catálogo por streaming** — títulos pré-cadastrados da Netflix, Disney+, HBO Max, Prime Video e Apple TV+, cada card com a cor da plataforma correspondente.
- **Busca e filtros** — por plataforma, por tipo (filme ou série) e por nome.
- **Adicionar títulos** — inclua qualquer filme/série que não esteja no catálogo.
- **Cronograma com calendário** — visualize o mês, veja em quais dias há sessão marcada (bolinhas coloridas por streaming) e clique num dia para agendar nele.
- **Status da sessão** — planejado → assistindo → assistido, com um clique.
- **Histórico** — lista de tudo que o casal já assistiu, com a data.
- **Dados compartilhados** — o que um dos dois adiciona ou marca aparece automaticamente para o outro.

## 🛠️ Tecnologias

- HTML5 + CSS3 (sem frameworks)
- JavaScript puro (vanilla)
- Fontes: [Fraunces](https://fonts.google.com/specimen/Fraunces) (títulos) e [Space Grotesk](https://fonts.google.com/specimen/Space+Grotesk) (texto)
- Persistência via `window.storage` (armazenamento chave-valor compartilhado)

Projeto 100% front-end — um único arquivo `index.html`, sem necessidade de instalar dependências ou rodar servidor.

## 🚀 Como usar

1. Baixe ou clone este repositório.
2. Abra o arquivo `index.html` no navegador — ou publique a pasta no GitHub Pages, Netlify, Vercel, etc.
3. Pronto: adicione títulos ao catálogo, agende as sessões da semana e marquem juntos o que já assistiram.

```bash
git clone https://github.com/seu-usuario/noite-nossa.git
cd noite-nossa
# abra o index.html no navegador
```

### Publicando no GitHub Pages

1. Vá em **Settings → Pages** no repositório.
2. Em *Branch*, selecione `main` e a pasta `/root`.
3. Salve — o site ficará disponível em `https://seu-usuario.github.io/noite-nossa/`.

## 📂 Estrutura

```
noite-nossa/
├── index.html   # aplicação completa (HTML + CSS + JS)
└── README.md
```

## 💡 Ideias futuras

- [ ] Avaliação em estrelas/corações para cada sessão assistida
- [ ] Exportar o cronograma da semana em imagem ou PDF
- [ ] Sugestão automática de próximo episódio de séries em andamento
- [ ] Modo "sorteio" para decidir o que assistir quando ninguém escolhe

## 📜 Licença

Distribuído sob a licença MIT. Sinta-se livre para adaptar para o seu próprio casal, família ou grupo de amigos.

---

<p align="center">feito com ♥ para as noites de sábado</p>
