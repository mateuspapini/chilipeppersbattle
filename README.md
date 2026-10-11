# Chili Peppers Battle

Site de fã do Red Hot Chili Peppers para descobrir a música e o álbum favoritos em duelos (Top 10 e Top 20), em português, inglês e espanhol.

Endereço: https://chilipeppersbattle.mapasolucoesdigitais.com.br/

Desenvolvido por [MAPA Soluções Digitais](https://mapasolucoesdigitais.com.br/).

## Arquivos

- `index.html`: o site inteiro (textos nos 3 idiomas, dados dos álbuns, lados B e lógica das batalhas)
- `assets/img/`: logo do site, logo da MAPA, favicons, ícone para celular e imagem de compartilhamento (`og-image.jpg`)
- `assets/fotos/`: fotos da seção "De fã para fã"
- `assets/icons/`: ícones do Spotify, Deezer, YouTube e Wikipédia
- `CNAME`: o subdomínio usado pelo GitHub Pages
- `robots.txt` e `sitemap.xml`: para o Google

## Publicação (GitHub Pages)

1. Crie um repositório novo (por exemplo `chilipeppersbattle`) e suba todos os arquivos desta pasta pela interface web, incluindo `CNAME` e `.nojekyll`.
2. Em **Settings > Pages**, escolha **Deploy from a branch**, branch `main`, pasta `/ (root)`.
3. Na Hostinger, na zona de DNS de `mapasolucoesdigitais.com.br`, crie um registro **CNAME**:
   - Nome: `chilipeppersbattle`
   - Aponta para: `mateuspapini.github.io`
4. Volte em **Settings > Pages**, confirme o domínio `chilipeppersbattle.mapasolucoesdigitais.com.br` e marque **Enforce HTTPS** assim que a opção liberar.

## Links por idioma

O site abre no idioma do navegador. Para abrir direto em um idioma:

- Português: `/#pt`
- English: `/#en`
- Español: `/#es`

## Pendências

- Capas oficiais e trechos de 30 segundos via API do Deezer: aguardando a autorização pedida ao Deezer. Quando aprovada, cada álbum recebe a URL da capa no campo `cover` e a faixa do topo da página do álbum passa a usar as cores da capa automaticamente.
