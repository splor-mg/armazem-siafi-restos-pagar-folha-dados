# armazem-siafi-restos-pagar-folha-dados

[![Updated](https://github.com/splor-mg/armazem-siafi-restos-pagar-folha-dados/actions/workflows/all.yaml/badge.svg)](https://github.com/splor-mg/armazem-siafi-restos-pagar-folha-dados/actions/)

## Pré-requisitos

Esse projeto utiliza Docker para gerenciamento das dependências. Para fazer _build_  da imagem execute:

```bash
docker build --tag armazem-siafi-restos-pagar-folha-dados .
```

## Uso

Para executar o container

```bash
docker run -it --rm --mount type=bind,source=$(PWD),target=/project armazem-siafi-restos-pagar-folha-dados bash
```

Uma vez dentro do container execute os comandos do make

```bash
make all
```

_Gerado a partir de [cookiecutter-datapackage@75bf738](https://github.com/splor-mg/cookiecutter-datapackage/commit/75bf738d0e983bbf728f88b5fda280f5f092fc78)_
