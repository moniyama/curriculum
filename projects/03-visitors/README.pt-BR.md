# Projeto de extensão: Registro de Visitantes

## Índice

- [1. Preâmbulo](#1-preâmbulo)
- [2. Resumo do projeto](#2-resumo-do-projeto)
- [3. Considerações gerais](#3-considerações-gerais)
- [4. Objetivos de aprendizagem](#4-objetivos-de-aprendizagem)
- [5. Critérios de aceitação mínimos do projeto](#5-critérios-de-aceitação-mínimos-do-projeto)
- [6. Considerações técnicas](#6-considerações-técnicas)

## 1. Preâmbulo

Devido as medidas de distanciamento social, o co-working mais famoso de sua
cidade precisa modernizar o processo do registro de visitantes. Até agora
este co-working tinha apenas um registro manual de visitantes, o que torna o processo
desagradável no momento de assinar um registro ou falar com um responsável.

Os administradores do co-working se deram conta de que necessitam modernizar a forma
de registrar os visitantes, sem precisar interagir com outra pessoa e
por isso contrataram a sua equipe.

## 2. Resumo do projeto

Este co-working te incentiva a desenvolver um protótipo com a nova funcionalidade
necessária.

<img alt="Recepción" src="recepcion.jpg" width="100%">
Crédito: [Pxfuel](https://pxfuel.com/)

Pesquisando sobre o assunto, eles conheceram uma ferramenta parecida com o que desejam e
lhes compartilharam como [referência](https://envoy.com/content/office-touchless-sign-in/).

A ideia é que com esta referência, possam desenvolver um protótipo [MVP](#o-que-é-um-mvp-minimum-viable-product)
para apresentar após um tempo estimado.

Visto que devem apresentar um protótipo, é recomendado usar um Framework
de CSS para economizar tempo com a parte visual do projeto.

Ao conhecer a metodología ágil, a administração deste co-working também
te pediu para que compartilhe as histórias de usuárix que sua equipe planeja trabalhar.
Para isso poderá usar ferramentas como [GitHub Projects](https://github.com/features/project-management/)
ou [Trello](https://trello.com/), por exemplo.

## 3. Considerações gerais

- Este projeto se deve resolver em equipes de 2 ou mais pessoas.
- Este projeto é "agnóstico" à tecnologia utilizada, ou seja, pode
desenvolver-lo em Vanilla JavaScript ou com algum _framework_ ou biblioteca
de sua escolha.
- Tente pensar em um escopo que, considerando a sua complexidade e a quantidade de
pessoas na equipe, permita terminar o projeto em 3 semanas.

## 4. Objetivos de aprendizagem

- Colocar em prática tudo que aprendeu até agora.
- Desenhar e _testar_ um produto antes de desenvolver-lo.
- Usar Histórias de Usuárix para dividir, comunicar e priorizar as tarefas a
serem feitas.
- Usar um _framework_ de CSS ou um sistema de componentes de interface, como por exemplo:
[Bulma.io](https://bulma.io/), [Tailwindcss.com](https://tailwindcss.com/),
[Bootstrap](https://getbootstrap.com/), etc.

## 5. Critérios de aceitação mínimos do projeto

- Propor e desenvolver uma interface funcional na qual os visitantes podem
se registrar. Esta interface em particular deverá funcionar sem problema em
celulares.
- Esta interface de visitante deverá registrar o nome, email, pessoa a ser
visitada, empresa que representa, data e hora da visita, além de sua duração.
- Propor e desenvolver uma interface funcional de administradora, no qual se pode
visualizar as visitas ativas e as que estão por chegar. Esta interface deverá
funcionar sem problemas em tablet e desktops.
- A interface de administradora deverá estar protegida por nome de usuário e
senha.
- As histórias de usuárix deverão estar disponíveis para ver em alguna ferramenta
online.

### Hacker edition

Se terminar os critérios de aceitação mínimos listados acima,
podem dedicar tempo para agregar novas ideias como as seguintes:

- Registrar uma fotografia da visitante usando a [API web de camera](https://developer.mozilla.org/es/docs/Web/API/MediaDevices/getUserMedia).
- Registrar novas pessoas por empresa no co-working, assim a lista de pessoas
que se pode visitar tem que ser validada.
- Registrar empresas do co-working, para que seja indicada na interface de
visitante.
- Se tiver alguma ideia própria também é bem-vinda.

## 6. Considerações técnicas

- Dado que a informação gerada tem que ser armazenada em algum lugar, será
necessário utilizar uma Base de Dados, sendo recomendado que programe uma API
que realize estas operações; leve em consideração o tempo que levará para
desenvolver com a sua equipe. Se você não lidou com esse conceito, converse com
um coach para ver se este projeto é indicado para você nesse momento.

## O que é um MVP (minimum viable product)?

O MVP ou "Produto mínimo viável" é a representação mais simples
de um projeto, focando todos os esforços em apresentar a funcionalidade
necessária aos usuários para que se possa validar se lhes agrega valor ou não.
De acordo com o feedback recebido após esta apresentação, é importante ir iterando
e priorizando as histórias de usuárix.
