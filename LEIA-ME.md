# Landing page — Dr. Cid Scarpa

Site estático (HTML, CSS e JavaScript). Não precisa de instalação nem de servidor especial.

## Estrutura
- `index.html` — a página completa (estilos e scripts incluídos no próprio arquivo)
- `assets/dr-cid.jpg` — foto do médico

## Como ver no computador
Abra o `index.html` com duplo clique no navegador (precisa de internet para carregar fontes e bibliotecas).

## Como publicar
Envie a pasta inteira para qualquer hospedagem estática: Hostinger/HostGator (via Gerenciador de Arquivos, dentro de `public_html`), Netlify (arraste a pasta em app.netlify.com/drop), Vercel ou GitHub Pages.

## Bibliotecas usadas (via CDN)
- GSAP 3.12.5 — animações de entrada
- Lucide 0.453.0 — ícones
- Google Fonts — Instrument Serif, Hanken Grotesk, JetBrains Mono

## Onde editar
- **WhatsApp:** procure `5569981118059` no `index.html` (aparece em vários pontos).
- **Endereço:** procure `Afonso Pena` (confirmar se é Av., nº 50, sala 06).
- **Áreas de atuação do mapa:** objeto `ORGANS` no script, no final do arquivo.
- **Motivos de consulta:** lista `MOTIVOS` no script.
- **Cores e fontes:** variáveis no topo do `<style>` (`--azul`, `--ink` etc.).
- **Foto:** troque `assets/dr-cid.jpg` por uma imagem maior (ideal: 1200 px ou mais, vertical) com o mesmo nome.

## Antes de publicar
- Confirmar endereço e convênios aceitos.
- Revisão médica dos textos (ThuLEP, mitos, rastreamento de próstata).
- Adicionar o domínio final no `og:image` (URL completa) para a prévia no WhatsApp aparecer com foto.
