# Convite de formatura – João Pedro

Site estático (HTML, CSS e JavaScript puros, sem instalar nada).

## Abrir no VS Code
1. `Arquivo > Abrir Pasta…` e escolha esta pasta.
2. Instale a extensão **Live Server** e clique em **Go Live** (ou abra o `index.html` direto no navegador).

## Editar dados
No fim do `index.html`, procure `const CONFIG`:
- `data`, `hora`, `local`, `endereco`: texto que aparece na janela "Detalhes.exe".
- `linkConfirmar`: link do botão "Confirmar presença" (ex.: `https://wa.me/55DDDNUMERO?text=Confirmo%20presen%C3%A7a`). Se ficar vazio, o botão avisa que o link ainda não foi adicionado.

## Hospedar no GitHub Pages
1. Crie um repositório no GitHub (ex.: `convite-formatura`) e envie estes arquivos (`index.html` na raiz).
2. No repositório: `Settings > Pages > Build and deployment`, em **Source** escolha `Deploy from a branch`, branch `main` e pasta `/ (root)`, e salve.
3. Em 1 a 2 minutos o site fica em `https://SEU-USUARIO.github.io/convite-formatura/`.
