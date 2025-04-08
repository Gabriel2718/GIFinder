# GIFinder

Um aplicativo desenvolvido com Flutter que permite ao usuário pesquisar e compartilhar GIFs obtidos do site GIPHY.

## Funcionalidades

Ao abrir o aplicativo, será carregada uma lista com os 20 GIFs mais visualizados do GIPHY. 
Através da barra de pesquisa é possível inserir palavras-chave para filtrar a busca. Por exemplo: ao pesquisar por "gatos", o aplicativo mostrará GIFs relacionados a gatos.
Se não houver texto na barra de pesquisa, será carregada uma lista com apenas 20 GIFs. Caso contrário, será carregada uma lista com 19 GIFs relacionados à pesquisa e um botão para atualizar a lista com novos GIFs.
OBS: Não há limite para quantas vezes o usuário pode atualizar a lista.

## Plugins Utilizados

- flutter_lints: ^5.0.0
- share_plus: ^10.1.4
- transparent_image: ^2.0.1
- http: ^1.3.0
- flutter_launcher_icons: ^0.14.3
