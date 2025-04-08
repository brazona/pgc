# Nome do Repositório

__[descrição do repositório: ]__ Repositório que compartilha fluxos de trabalho do github com os demais repositórios/projetos.

## Versões

__[relação das versões de aplicativos externos: ]__ A aplicação utiliza as seguintes versões: *NÃO SE APLICA.*

## Estrutura do projeto

__[descrição da estrutura do diretório: ]__

``` text

├── .github
│   └── workflows
│       └── script
│           └── manifest.sh
│       └── identifier.yml
│       └── pipeline-deploy.yml
│       └── tag.yml
│   └── branch_default_rule.json
│   └── dependabot.yml
│   └── tag_default_rule.json
├── docs
│   └── CONTRIBUTING.md
│   └── CODE_OF_CONDUCT.md
│   └── PULL_REQUEST_TEMPLATE.md
└── README.md
```

## Deploy da Aplicação

__[descrição do processo de deploy em ambiente cloud: ]__ *NÃO SE APLICA.*

### Tabela Branch x Ambiente

| Branch | Ambiente |
| --- | --- |
| develop | Aplica no ambiente __DSV__ |
| release/** | Aplica no ambiente __HMG__ |
| pre-release/** | Aplica no ambiente __STG__ |
| main | Aplica no ambiente __PRD__ |


## Licença

> [!IMPORTANT]
> *O código fonte neste projeto não possui licença de uso.*

É terminantemente proibido reproduzir, distribuir, alterar, utilizar engenharia reversa ou valer-se de qualquer tentativa de reverter ao seu código-fonte qualquer dos componentes que compõem o SOFTWARE, bem como utilizar subterfúgios para burlar a quantidade de usuários licenciados.
