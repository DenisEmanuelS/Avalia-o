# Pokédex (Avalia-o)

Descrição
- Pequena interface de Pokédex feita em HTML/CSS/JS. Permite buscar Pokémon e exibir nome e imagem.

Estrutura do projeto
- pokedex.html — Página principal com layout e referência a `script.js`.
- style.css — (esperado) estilos do projeto.
- script.js — (opcional/esperado) lógica em JavaScript referenciada por `pokedex.html`.
- README.md — (este arquivo) documentação breve.

Como executar
- Método simples: abrir `pokedex.html` diretamente no navegador.
- Recomendado (para evitar problemas de CORS/recursos): servir por um servidor HTTP local:
  - Python 3: `python -m http.server 8000` (abra http://localhost:8000/Avalia-o/pokedex.html)
  - Node (http-server): `npx http-server .` e abra a URL indicada.

Dependências externas
- PokeAPI (https://pokeapi.co/) — usada para buscar dados/imagens dos Pokémon. Requer conexão com a internet.

Observações e dicas
- `pokedex.html` referencia `script.js`. Se este arquivo não existir, crie-o com a lógica de busca ou mova o script inline para o HTML.
- Se a imagem não carregar, verifique a URL retornada pela PokeAPI e o console do navegador (F12).

Resolver erro de merge (caso apareça)
- Verificar estado: `git status`
- Abortar merge (se quiser descartar a tentativa de merge): `git merge --abort`
- Concluir merge (após resolver conflitos): `git add -A && git commit -m "Concluir merge"`
- Listar arquivos em conflito: `git diff --name-only --diff-filter=U`
- Descartar alterações locais (perigoso): `git reset --hard HEAD`

Contato / próximos passos
- Separar `script.js` se preferir manter JS externo.
- Adicionar `style.css` se ainda não existir ou ajustar estilos.
