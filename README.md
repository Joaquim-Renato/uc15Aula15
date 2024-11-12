# CSS `overflow: hidden;`

`overflow: hidden;` é uma propriedade CSS usada para controlar como o conteúdo que ultrapassa os limites de um contêiner é exibido. Quando aplicado, o conteúdo que excede as dimensões do contêiner é ocultado, em vez de gerar barras de rolagem ou transbordar para fora do contêiner.

## Quando Usar `overflow: hidden;`

1. **Impedir Deslocamento de Conteúdo Além do Contêiner**
   Se o conteúdo dentro de um elemento excede as dimensões especificadas, ele será cortado:
   ```css
   .container {
     width: 200px;
     height: 200px;
     overflow: hidden;
   }
``
-----------

## Outras Opções do overflow para Comparação:
visible: conteúdo excedente é visível.
scroll: adiciona barras de rolagem para permitir a visualização do conteúdo.
auto: adiciona barras de rolagem apenas se necessário.