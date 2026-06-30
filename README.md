# MS Smart — Política de Privacidade (GitHub Pages)

Página estática para a URL exigida pela App Store Connect.

## URL final (após publicar)

```
https://softm9991-lab.github.io/ms-smart-privacidade/
```

Alternativa com nome do arquivo:

```
https://softm9991-lab.github.io/ms-smart-privacidade/ms-smart-privacidade.html
```

Use a **primeira** (mais limpa) no App Store Connect.

## Publicar (uma vez)

1. No GitHub, crie um repositório **público** chamado exatamente:
   `ms-smart-privacidade`
   (organização `softm9991-lab`)

2. Envie o conteúdo desta pasta:

   ```bash
   cd github-pages/ms-smart-privacidade
   git init
   git add index.html ms-smart-privacidade.html README.md
   git commit -m "Add MS Smart privacy policy for App Store"
   git branch -M main
   git remote add origin git@github.com:softm9991-lab/ms-smart-privacidade.git
   git push -u origin main
   ```

3. No repositório: **Settings → Pages**
   - Source: **Deploy from a branch**
   - Branch: **main** / **/ (root)**
   - Save

4. Aguarde 1–3 minutos e abra:
   https://softm9991-lab.github.io/ms-smart-privacidade/

5. Cole essa URL em **App Store Connect → Privacidade do app → URL da Política de privacidade**.
