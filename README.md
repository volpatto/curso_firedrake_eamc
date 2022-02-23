# Curso de Introdução ao Firedrake

Bem-vindo(a) ao repositório do curso de Introdução ao Firedrake. Aqui você irá encontrar todo o material utilizado nas aulas e como reproduzir o mesmo ambiente. Dessa forma, você será capaz de replicar todos os resultados apresentados.

## Ementa

Para uma visão mais detalhada do curso, por favor verificar a [ementa](https://github.com/volpatto/curso_firedrake_eamc/blob/main/EMENTA.md).

## Aulas

As aulas estão elaboradas em [Jupyter Notebooks](https://jupyter.org/). Dessa forma, todas as aulas são interativas e é recomendável que o participante reproduza as mesmas sempre que houver demonstrações com códigos. O material está todo disponibilizado no diretório `notebooks`.

## Pré-requisitos para utilizar esse repositório

Para utilizar o conteúdo presente nesse repositório, é necessário que você tenha instalado o Firedrake com sucesso em sua máquina. Para isso, por favor [siga as instruções disponibilizadas aqui](https://www.firedrakeproject.org/download.html).

Após a correta instalação do Firedrake, é necessário a instalação de dependências adicionais desse curso. Para isso, faça os seguintes passos:

1. Ative o ambiente virtual do Firedrake:

```shell
source {path_to_firedrake}/firedrake/bin/activate
```

O `path_to_firedrake` é o caminho na sua máquina para o diretório do `firedrake`. Por exemplo, se você instalou na sua pasta de usuário no Ubuntu, ele simplesmente é `path_to_firedrake=~`, de forma que o comando para ativar o ambiente ficaria `source ~/firedrake/bin/activate`.

2. Instale as dependências adicionais listadas em `requirements.txt`:

```terminal
pip install -r requirements.txt
```

Pronto, seu ambiente já possui tudo que é necessário para a execução do material em sua máquina.

## Executando o material

Com os requisitos adicionais e esse reprositório, ative o ambiente do Firedrake:

```shell
source {path_to_firedrake}/firedrake/bin/activate
```

Entre na pasta do repositório do curso:

```shell
cd {path_to_curso}/curso_firedrake_eamc
```

Iniciei o `jupyter notebook`:

```shell
jupyter notebook
```

Com isso, deve ser aberta uma aba no seu navegador referente ao `jupyter`. Nesse ambiente, navegue até a pasta `notebooks` e escolha a aula de seu interesse.

## Sobre mim

* Nome: Diego Volpatto;
* Email: [dtvolpatto@gmail.com](dtvolpatto@gmail.com).

Sou desenvolvedor numérico na [ESSS](https://github.com/ESSS) desde 2018, trabalhando com desenvolvimento e aplicações numéricas na indústria de Óleo e Gás.

No momento que apresento este curso, sou aluno de doutorado no [LNCC](http://www.lncc.br/) em estado final.

Qualquer dúvida sobre o curso, por favor entre em contato comigo.
