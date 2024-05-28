# Componente Contador

Este repositório contém um script em JavaScript que implementa um contador dinâmico e interativo para uma página web. O contador permite incrementar e decrementar valores dentro de limites definidos, atualizando a interface do usuário em tempo real.

## Funcionalidades

- **Incremento e Decremento**: Permite aumentar ou diminuir o valor do contador com base em uma unidade definida.
- **Limites de Valor**: Respeita os valores máximos e mínimos definidos para cada contador.
- **Atualização Dinâmica**: Atualiza o display do contador em tempo real conforme o valor muda.
- **Controle de Botões**: Habilita ou desabilita botões de incremento e decremento com base nos valores atuais.

## Como Funciona

1. **Seleção de Elementos**: Seleciona todas as `div` com o atributo `name="counter"` na página.
2. **Obtenção de Atributos**: Captura os valores máximos (`aria-valuemax`), mínimos (`aria-valuemin`) e a unidade de incremento (`aria-current`).
3. **Interatividade**: Adiciona eventos de clique aos botões de incremento e decremento para modificar o valor do contador.
4. **Gerenciamento de Valores**: Utiliza um objeto `additionals` para gerenciar a lista de valores, assegurar os limites e atualizar a interface.

## Estrutura do Projeto

- `items.html`: Exemplo de uso do contador em uma página web.
- `additional-items.html`: Exemplo de uso de vários contadores em uma página web.

## Como Usar

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/seu-usuario/nome-do-repositorio.git
2. Abra o arquivo **items.html** em um navegador para ver o contador em ação.
3. **Personalize os contadores**: Edite os atributos `aria-valuemax`, `aria-valuemin` e `aria-current` nas `div` para ajustar os valores máximos, mínimos e a unidade de incremento conforme necessário.

## Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests para melhorias e correções.
