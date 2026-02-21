# PURE BALANCE - Landing Page

Projeto dinâmico e responsivo, trazendo mais eficiência para o cliente conseguir moldar o site da forma que desejar e criação de uma landing page para uma marca de loções.

## Estrutura
- `assets`: Onde fica todos os arquivos que utilizam JS, CSS3, Icons e imagens 
- `blocks`: Armazena todos os arquivos, cada um com seu próprio schema, permitindo a edição de configurações especificas, como cores e adição de widgets.
- `config`: recebe as configurações da loja e do tema.
- `layout/theme.liquid`: É aqui que fica todo o esqueleto HTML e body
- `sections/lp-lotion.liquid`: Possui os elementos modulaveis e reutilizaveis da landing page, como Banners, grade de produtos e depoimentos. 
- `snippets`: Guarda pequenos pedaços de código Liquid que são repetidos em vários lugares, como ícones de redes sociais, botões específicos ou badges de produtos.
- `templates/page.lotion-lp.json`: Define a estrutura de cada tipo de página (Home, Produto, Carrinho). Atualmente, a maioria usa arquivos .json para permitir que as sections sejam configuradas dinamicamente.
- `locales`: contèm a tradução dos arquivos json;

## Como executar
1. **Clone o repositório:**
   git clone [https://github.com/BORGES-GRU/-semana-2-lp-lotions.git]
2. **Entre na Pasta:**
cd -semana-2-lp-lotions
3. **Instale as dependências:**
npm install
4. **Conecte à sua loja Shopify:**
shopify login --store [sua-loja].myshopify.com
5. **Inicie o servidor de desenvolvimento:**
npm run dev
## Observacoes
[x] Design totalmente responsivo (Mobile First).

[x] Otimização de imagens para carregamento rápido.

[x] Seções editáveis via painel administrativo.

## Video Explicativo
[text](https://drive.google.com/file/d/1N436D7vhn4nGGSvOVjhTbnytKQ9MSsHc/view?usp=drive_link)