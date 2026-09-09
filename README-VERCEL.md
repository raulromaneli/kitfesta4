# Versão estática pronta para Vercel

Esta pasta já contém o site compilado. Não precisa instalar Node, executar build ou configurar framework.

## Como publicar pelo GitHub

1. Crie um repositório novo e vazio.
2. Abra esta pasta `kit-festas-viva-vercel-static`.
3. Envie **os arquivos que estão dentro dela** diretamente para a raiz do repositório.
4. Confira se `index.html` aparece na raiz do GitHub.
5. Importe o repositório na Vercel.
6. Em **Build and Deployment**, deixe:
   - Framework Preset: `Other`
   - Build Command: deixe vazio
   - Output Directory: `.`
   - Install Command: deixe vazio
7. Faça o deploy.

## Atenção

O arquivo `index.html` precisa aparecer diretamente na raiz do repositório, e não dentro de `kit-festas-viva-vercel-static/` ou `dist/public/`.
