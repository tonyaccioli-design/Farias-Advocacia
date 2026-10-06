# Farias Advocacia

Site institucional estatico da Farias Advocacia, pronto para publicacao em GitHub e Vercel.

## Estrutura principal

- `dist/index.html`: pagina principal.
- `dist/styles.css`: estilos do site.
- `dist/assets/`: imagens WebP, favicon e marca usados pelo site.
- `vercel.json`: configura o Vercel para publicar a pasta `dist`.

## Publicacao no Vercel

1. Suba este repositorio para o GitHub.
2. Importe o repositorio no Vercel.
3. Mantenha o preset como projeto estatico/sem framework.
4. O `vercel.json` ja define `dist` como diretorio de saida.
5. Nao e necessario comando de build.

## Conferencia local

Para conferir localmente, sirva a pasta `dist` com qualquer servidor estatico. Exemplo:

```bash
cd dist
python -m http.server 8000
```

Depois abra `http://localhost:8000`.

## Observacoes

- Os arquivos e pastas de trabalho do Sites, pacotes `.zip` e imagens temporarias estao listados no `.gitignore`.
- O site nao depende de backend, banco de dados ou variaveis de ambiente.
