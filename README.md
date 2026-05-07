# CHAK PLAST - site institucional e comercial

Site estatico para uma empresa de reciclagem industrial B2B, com foco em venda de materiais reciclados e servicos de reciclagem para industrias.

Endereco comercial: Rua Altino Arantes 745, Jardim das Bandeiras, Campinas - SP 13051-110.

## Como abrir localmente

Abra o arquivo `index.html` diretamente no navegador:

`D:\Codex\2026-05-07\crie-um-site-seguindo-este-prompt\index.html`

Nao e necessario instalar dependencias ou iniciar servidor local.

## Estrutura

- `index.html`: estrutura semantica, conteudo, SEO, informacoes de contato e links de CTA.
- `styles.css`: layout responsivo mobile-first, paleta, tipografia, estados de foco e microinteracoes.
- `app.js`: menu mobile acessivel e animacoes suaves por intersecao.
- `assets/chak-plast-logo.png`: logo da CHAK PLAST usada no cabecalho.
- `.github/workflows/pages.yml`: workflow para publicar o site no GitHub Pages.
- `.gitignore`, `.gitattributes` e `.nojekyll`: arquivos de suporte para GitHub.

## Publicacao no GitHub

1. Crie um repositorio no GitHub.
2. Instale o Git no computador, caso o comando `git` ainda nao esteja disponivel no terminal.
3. No terminal, entre na pasta do projeto:

```powershell
cd "D:\Codex\2026-05-07\crie-um-site-seguindo-este-prompt"
```

4. Inicialize o repositorio local e envie para o GitHub:

```powershell
git init
git branch -M main
git add .
git commit -m "Publica site institucional CHAK PLAST"
git remote add origin https://github.com/SEU-USUARIO/SEU-REPOSITORIO.git
git push -u origin main
```

5. No GitHub, acesse `Settings > Pages` e selecione `GitHub Actions` como fonte de publicacao.
6. A cada push na branch `main`, o workflow `.github/workflows/pages.yml` publica o site automaticamente.

## Pontos implementados

- Hero com imagem real de operacao de reciclagem industrial.
- Destaque dos dois fluxos comerciais: venda de materiais reciclados e servico de reciclagem industrial.
- Secoes solicitadas: Nossos Servicos, Processo Sustentavel, Quem Confia em Nos e Entre em Contato.
- SEO com titulo, meta description, headings claros e alt text em imagem informativa.
- Acessibilidade com skip link, foco visivel, contraste alto e navegacao por teclado.
- Performance com site estatico, CSS/JS enxutos, imagens responsivas e lazy loading onde cabe.
