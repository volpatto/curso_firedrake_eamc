# Introdução ao Firedrake

## Visão Geral

Neste curso, iremos aprender a utilizar o [Firedrake](https://www.firedrakeproject.org/index.html), um sistema automatizado para solucionar equações diferenciais parciais (EDPs) numericamente com o método de Elementos Finitos. O Firedrake torna a implementação de métodos de Elementos Finitos bastante facilitada e rápida, provendo uma linguagem de domínio específico que se assemelha à forma que as formulações de elementos finitos são escritas matematicamente. Além disso, o Firedrake é um framework composto por várias bibliotecas e disponível em linguagem Python, possibilitando a combinação de diversas e poderosas bibliotecas científicas acessíveis por essa linguagem.

Esse curso é indicado para aqueles que tenham conhecimentos básicos de métodos numéricos para EDPs. O método de Elementos Finitos será introduzido de forma básica, sendo qualquer conhecimento prévio desejável. Caso você deseje aprender uma forma de solucionar equações diferenciais parciais com métodos de elementos finitos sem muito sofrimento para implementações, esse curso é para você.

## Pré-requisitos

Abaixo, seguem recomendações de pré-requisitos para melhor proveito do curso.

### Recomendável

Conhecimentos básicos:

1. Métodos numéricos para solução de sistemas lineares e não-lineares;
2. Métodos numéricos para solução de equações diferenciais parciais.

### Desejável (opcional)

1. Conhecimentos básicos de Método de Elementos Finitos;
2. Básico de linguagem de programação Python.

## Objetivos específicos

Introduzir, de forma simples e prática, a solução numérica de EDPs por métodos de elementos finitos com exemplos utilizando o Firedrake.

## Conteúdo

1. Introdução ao Firedrake
    * O que é Firedrake?
    * Instalação
    * Formas de utilização

2. Introdução prática ao Método de Elementos Finitos usando o Firedrake
    * Um primeiro exemplo 1D: Poisson
    * Resolvendo o problema de Poisson
    * Solucionando o problema da Elasticidade Linear

3. Formulações de Elementos Finitos Mistas
    * Problema de Poisson misto

4. Problemas Transientes
   * Equação do Calor
   * Sistemas reativos: Modelo de Gray-Scott

5. (Opcional) Utilizando a PETSc com Firedrake
   * Métodos de subespaço de Krylov
   * Configurando Solvers
   * Pré-condicionadores
   * Acessando objetos da PETSc construídos pelo Firedrake
