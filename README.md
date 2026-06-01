# Manual Operacional da FVP

Repositório do Manual Operacional da Ferramenta de Validação em Produção (FVP), mantido pela estrutura do Open Finance Brasil.

## Acesso à documentação

A versão mais recente do manual está sempre disponível em:

**[ofb-hub.github.io/manual-fvp](https://ofb-hub.github.io/manual-fvp/)**

## Estrutura do projeto

```
manual-fvp/
├── manual-fvp.tex              # Documento principal
├── chapters/
│   ├── 01-ferramenta.tex       # O que é a FVP
│   ├── 02-principios-operacionais.tex
│   ├── 03-ciclos-execucao.tex
│   ├── 04-diretrizes-testes.tex
│   └── 05-informacoes-adicionais.tex
└── imagens/                    # Capturas de tela e figuras
```

## Como atualizar o manual

Qualquer alteração enviada para este repositório gera automaticamente uma nova versão do manual publicada no link acima. Não é necessário compilar nada manualmente.

1. Edite o arquivo `.tex` correspondente ao capítulo desejado
2. Faça commit e push para a branch `main`
3. Aguarde ~2 minutos — o manual será atualizado automaticamente

## Compilação local (opcional)

Para gerar o PDF localmente é necessário ter o [MiKTeX](https://miktex.org/) ou [TeX Live](https://tug.org/texlive/) instalado.

```bash
pdflatex manual-fvp.tex
```

## Sobre

- **Ferramenta:** [FVP – Raidiam](https://gitlab.com/raidiam-conformance/open-finance/certification/-/wikis/home)
- **Referência oficial:** [Guia de Operação da FVP](https://openfinancebrasil.atlassian.net/wiki/spaces/OF/pages/553254913)
