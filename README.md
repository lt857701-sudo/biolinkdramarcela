# Marcela Fontes — Link da Bio

Landing page mobile-first em formato vertical para Marcela Fontes, especialista em Estética Avançada, com atendimento em Santa Cruz da Serra • Barra da Tijuca. Página única, sem rolagem, focada no agendamento de avaliação pelo WhatsApp e em conteúdos selecionados.

## Estrutura (raiz do projeto)

```text
.
├── index.html           ← Página única estática (HTML + CSS embutido)
├── foto-de-fundo.png    ← Imagem principal (hero background)
├── vercel.json          ← Configuração de deploy na Vercel
├── .gitignore           ← Arquivos ignorados pelo Git
└── README.md            ← Este arquivo
```

## Rodar localmente

Abra o `index.html` diretamente no navegador, ou sirva com qualquer servidor estático:

```bash
# com Python
python -m http.server 8000

# com Node (npx serve)
npx serve .
```

A aplicação ficará disponível em `http://localhost:8000`.

## Links configurados

- **WhatsApp:** 5521975063169
- **Instagram:** @dra.marcelafontes
- **Conteúdos:** Harmonização Facial, Congresso Bodyscience, Tratamentos a Laser

Para alterar qualquer destino, edite diretamente o `index.html`.

## Deploy na Vercel

1. Crie um repositório vazio no GitHub.
2. Envie os arquivos da raiz para o repositório.
3. Acesse [vercel.com/new](https://vercel.com/new).
4. Importe o repositório.
5. A Vercel detecta o site estático automaticamente (não há build step).
6. Confirme o deploy.

O `vercel.json` já está configurado para servir o `index.html` de fallback e cachear a imagem.
