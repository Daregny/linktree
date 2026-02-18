# Linktree Moderno — Yenny Delgado

Uma página de links pessoal, responsiva, multilíngue e minimalista.

## Funcionalidades

- Design moderno e minimalista
- Paleta de cores fixa e harmônica
- Suporte a 3 idiomas: Português, Inglês e Espanhol (seletor no topo)
- Modo claro/escuro (toggle ☾/☀ no topo)
- Ícones sociais customizáveis
- Totalmente responsivo (mobile/desktop)

## Como editar

1. **Foto de perfil:**
	- Substitua `img/yenny.jpeg` pela sua imagem (mantenha o nome ou ajuste o caminho em `index.html`).

2. **Links sociais:**
	- Edite os links e ícones na seção `<nav class="social">` do `index.html`.
	- Para trocar ícones, substitua os arquivos em `img/` e ajuste o `src` das imagens.

3. **Botões de links principais:**
	- Edite os textos e URLs na lista `<ul class="list-links">`.
	- Os textos são traduzidos automaticamente pelo seletor de idioma.

4. **Cores:**
	- As cores principais estão em `css/style.css` nas variáveis CSS (`:root`).
	- Para mudar, altere os valores de `--bg-1`, `--bg-2`, `--accent`, `--card-bg`, `--text-on-card`, `--muted`.

5. **Textos e traduções:**
	- Os textos principais (título, descrição, subtítulo, botões) são definidos no script de traduções no final do `index.html`.
	- Para personalizar, edite o objeto `translations`.

## Como rodar localmente

1. Basta abrir o arquivo `index.html` no navegador (clique duplo ou arraste para o Chrome/Edge/Firefox).
2. Não é necessário servidor local, mas se quiser testar como site real:
	- No terminal, execute:
	  ```powershell
	  # Windows PowerShell
	  Start-Process "http://localhost:8000"; python -m http.server 8000
	  ```
	- Ou use qualquer servidor estático de sua preferência.

## Deploy

- Pode ser hospedado no GitHub Pages, Vercel, Netlify, etc. Basta apontar para a pasta do projeto.

## Licença

MIT. Livre para uso pessoal e comercial.