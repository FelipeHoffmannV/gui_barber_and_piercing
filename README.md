# Estúdio Gui

<p>
  <strong>Site institucional responsivo</strong> para o Estúdio Gui, especializado
  em barbearia, piercing e tatuagem.
</p>

<p>
  <img src="https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/GitHub%20Pages-222222?logo=github&logoColor=white" alt="GitHub Pages" />
  <img src="https://img.shields.io/badge/licença-MIT-green" alt="Licença MIT" />
</p>

> Projeto estático criado para apresentar os serviços, o ambiente e as
> informações de localização do Estúdio Gui.

---

## Sobre o projeto

O site reúne em uma experiência simples e visualmente consistente os principais
serviços do estúdio:

- apresentação institucional;
- página dedicada à barbearia;
- página dedicada ao piercing;
- página dedicada à tatuagem;
- localização e avaliações no Google;
- acesso direto ao contato pelo WhatsApp.

O projeto não utiliza framework nem backend: as páginas podem ser abertas
diretamente no navegador ou publicadas em qualquer serviço de hospedagem estática.

## Funcionalidades

- navegação entre páginas;
- layout responsivo para desktop, tablet e celular;
- identidade visual consistente;
- páginas individuais para cada serviço;
- imagens otimizadas em arquivos locais;
- links externos com abertura segura;
- integração direta com WhatsApp;
- links para Google Maps e avaliações no Google;
- metadados e descrição básica para SEO.

## Tecnologias

| Tecnologia | Utilização |
| --- | --- |
| HTML5 | Estrutura semântica das páginas |
| CSS3 | Layout, responsividade e identidade visual |
| WhatsApp | Canal direto de contato |
| Google Maps | Localização do estúdio |
| GitHub Pages | Hospedagem estática |

## Páginas

| Arquivo | Conteúdo |
| --- | --- |
| [`index.html`](index.html) | Página inicial e apresentação dos serviços |
| [`barbearia.html`](barbearia.html) | Serviços e informações sobre barbearia |
| [`piercing.html`](piercing.html) | Serviços e informações sobre piercing |
| [`tatuagem.html`](tatuagem.html) | Serviços e informações sobre tatuagem |
| [`localizacao.html`](localizacao.html) | Endereço, rota e avaliações no Google |
| [`style.css`](style.css) | Estilos compartilhados por todas as páginas |

## Estrutura do projeto

```text
.
├── index.html
├── barbearia.html
├── piercing.html
├── tatuagem.html
├── localizacao.html
├── style.css
├── img/
│   ├── Gui.png
│   ├── tatto.png
│   └── ...
├── LICENSE
└── README.md
```

## Executando localmente

Não há instalação de dependências ou configuração de servidor necessária.

### Opção 1: abrir diretamente

Abra [`index.html`](index.html) no navegador.

### Opção 2: servidor local

Na raiz do projeto, execute:

```bash
python3 -m http.server 4173
```

Depois, acesse:

<http://localhost:4173>



### WhatsApp

Os links de contato estão configurados diretamente nas páginas HTML. Para alterar
o número, substitua `51955440022` pelo número desejado no formato internacional,
sem espaços, símbolos ou o `+`:

```text
https://wa.me/51955440022
```

Para incluir uma mensagem pré-definida:

```text
https://wa.me/51955440022?text=Olá!%20Gostaria%20de%20agendar.
```

### Google Maps e avaliações

Os links do Google estão definidos em [`localizacao.html`](localizacao.html).
Atualize a busca caso o nome ou a localização do estabelecimento seja alterado.

### Identidade visual

Cores, tipografia, espaçamento e regras responsivas estão centralizados em
[`style.css`](style.css).

## Compatibilidade

O site pode ser visualizado nos navegadores modernos com suporte a HTML5 e CSS3,
incluindo Chrome, Edge, Firefox e Safari.

## Licença

Este projeto está licenciado sob a licença **MIT**. Consulte o arquivo
[LICENSE](LICENSE) para os termos completos.

## Autor

**Felipe Hoffmann Viana**

- [GitHub](https://github.com/FelipeHoffmannV)
- [LinkedIn](https://www.linkedin.com/in/felipe-hoffmann-viana-13061b427/)
