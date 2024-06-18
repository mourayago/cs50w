Basicamente a ideia do Sass é deixar mais fácil e mais prático de lidar com os códigos CSS.


Fiz a instalação dele no meu pc usando o seguiente tutorial:
- https://www.youtube.com/watch?v=u7Ud-kxG10A

A ideia é que sempre que for fazer uma estilização a gente crie um arquivo .scss

E dentro desse arquivo fazemos toda a estilização.

Depois que essa estilização é feita a gente tem que compilar oa arquivo .scss para um arquivo .css e temos duas formas de fazer isso:

1- abrindo a pasta que está o arquivo pelo prompt de comando e digitando:

 `sasss nome_arquivo.scss:nome_arquivo.css`

dessa primeira forma após cada mudança temos que compilar novamente o arquivo scss

2- Dessa segunda forma não precisamos ficar compilando o arquivo toda hora, podemos fazer as mudanças ewm modo "live"

`sass --watch nome_arquivo.scss:nome_arquivo.css`

o sass vai ficar monitorando as mudanças e aplicar após as edições são feitas
