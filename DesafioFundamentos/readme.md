# Sistema de Controle de Veículos

## Descrição do Projeto

Este projeto é um sistema simples de cadastro e gerenciamento de veículos, desenvolvido em **C#**, que permite adicionar, remover e listar veículos. O objetivo principal é criar uma ferramenta prática para controle de frota e aprendizado de conceitos de programação, listas e manipulação de strings.

## Funcionalidades

- Adicionar veículos ao sistema.
- Verificar se um veículo já foi cadastrado.
- Remover veículos.
- Listar todos os veículos cadastrados.

## Minha Participação

No projeto, fui responsável por implementar uma **melhoria na validação do cadastro de veículos**. Antes, era possível adicionar o mesmo veículo múltiplas vezes, o que poderia gerar inconsistências na lista.

Minha alteração consistiu em **verificar se o veículo já existe na lista antes de adicioná-lo**, garantindo que não haja duplicações. Para isso, utilizei a conversão para letras maiúsculas (`ToUpper()`) para que a verificação não fosse sensível a diferenças de maiúsculas e minúsculas.
