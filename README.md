# megaestudante

Descrição
-----

`megaestudante` é um repositório leve para hospedar páginas estáticas de atividades (exercícios, revisões e trabalhos). O objetivo é oferecer um local simples e organizado para estudantes e professores publicarem e acessarem atividades sem necessidade de backend.

Objetivo
-----

- **Propósito:** Armazenar e servir atividades em HTML de forma fácil e compartilhável.
- **Público-alvo:** Estudantes, professores e organizadores que desejam uma página central para publicar materiais.

Estrutura atual
-----

- `atividades/` — pasta onde cada autor, turma ou tema pode ter uma subpasta. Exemplo: `atividades/duda/`.
- Exemplos já presentes: `atividades/duda/rev1.html`, `atividades/duda/rev2.html`.

Como usar localmente
-----

1. Abra os arquivos HTML diretamente no navegador, ou sirva o diretório com um servidor estático:

```bash
python3 -m http.server 8000
```

2. Depois, abra no navegador: `http://localhost:8000/atividades/duda/rev1.html`

Publicação
-----

Opções simples para publicar online:
- **GitHub Pages:** use o branch `gh-pages` ou habilite Pages a partir do `main` nas configurações do repositório.
- **Netlify / Vercel / Surge:** serviços que hospedam sites estáticos com deploys a partir do repositório.

Boas práticas sugeridas
-----

- Organize por subpastas: `atividades/<autor>/...` ou `atividades/<ano>/...`.
- Adicione um `index.html` na raiz ou em `atividades/` com links para as subpastas para facilitar navegação.
- Padronize nomes de arquivos e inclua metadados básicos (título, autor, data) no início dos HTMLs.
- Crie um template de atividade (um `template.html`) para manter consistência.

Próximos passos recomendados
-----

- Adicionar um `index.html` automático que liste as atividades.
- Atualizar este `README.md` com contribuições e regras de nomenclatura (posso fazer isso para você).
- Configurar GitHub Pages para publicação automática.

Quer que eu crie o `index.html` com listagem automática das pastas de `atividades/` ou prefira que eu apenas finalize o `README.md` com mais detalhes de contribuição? Responda com `index` ou `contrib`.
