# Borealis Engenharia

Site institucional para uma empresa de engenharia elétrica voltada a energias
renováveis (solar, eólica e armazenamento), construído com HTML, CSS e
JavaScript puros (sem frameworks). Seções: Início, Quem Somos, Serviços,
Portfólio de Projetos e Contato.

## Estrutura

- `index.html` — estrutura da página (hero, quem somos, serviços, projetos, contato)
- `style.css` — identidade visual azul técnico + ciano (inspirada na aurora boreal), tema claro/escuro e responsividade
- `script.js` — alternância de tema, menu mobile, animações ao rolar, contador animado nos números e formulário de contato

## Como usar

Abra o `index.html` diretamente no navegador, ou sirva a pasta com um servidor estático:

```bash
python3 -m http.server
```

Depois acesse `http://localhost:8000`.

## Personalização

Edite os textos em `index.html` (nome da empresa, sobre, serviços, projetos, dados de contato) para deixar o site com o conteúdo real da empresa.

## Domínio

O site está publicado no domínio padrão do GitHub Pages:
https://dgn09.github.io/meu-site/

Quando o domínio `borealisengenharia.com` estiver registrado, basta criar um
arquivo `CNAME` na raiz do repositório com esse endereço e configurar no
registrador do domínio:

- Registros **A** apontando `borealisengenharia.com` para:
  - 185.199.108.153
  - 185.199.109.153
  - 185.199.110.153
  - 185.199.111.153
- (opcional) Registro **CNAME** para `www` apontando para `dgn09.github.io`

Depois, em Settings → Pages do repositório, confirme o domínio customizado e
aguarde o certificado HTTPS ser emitido automaticamente (pode levar algumas
horas após a propagação do DNS).