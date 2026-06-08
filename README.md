# Site estático sobre reconhecimento de vínculo empregatício

Site gratuito, estático, responsivo e leve, criado em HTML, CSS e JavaScript simples.

## Como publicar gratuitamente

### GitHub Pages

1. Crie um repositório no GitHub.
2. Envie todos os arquivos desta pasta para o repositório.
3. No GitHub, acesse `Settings > Pages`.
4. Em `Build and deployment`, escolha `Deploy from a branch`.
5. Selecione a branch `main` e a pasta `/root`.
6. Salve e aguarde a URL pública.

### Cloudflare Pages

1. Acesse o Cloudflare Pages.
2. Conecte o repositório do GitHub.
3. Use as configurações:
   - Framework preset: `None`
   - Build command: deixe vazio
   - Output directory: `/`
4. Publique.

### Vercel

1. Importe o repositório na Vercel.
2. Use framework `Other`.
3. Não configure build command.
4. Publique.

## Ajustes importantes antes de publicar

1. Troque `https://seu-dominio.com` pelo domínio real em `sitemap.xml`, `robots.txt` e nas tags `canonical`.
2. Revise o nome profissional, OAB, endereço e política de privacidade conforme a necessidade.
3. O conteúdo é informativo e não substitui análise individual do caso concreto.

## Estrutura

- `index.html`: página inicial
- `pages/`: páginas internas
- `style.css`: estilos responsivos
- `script.js`: menu mobile
- `sitemap.xml`: mapa do site
- `robots.txt`: instruções para buscadores
