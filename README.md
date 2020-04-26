# MyAnimeList

Entrar en [https://myanimelist.net/ownlist/style](https://myanimelist.net/ownlist/style "https://myanimelist.net/ownlist/style")

Seleccionar una lista que queremos editar y hacemos clic sobre el estilo que queremos sobreescribir.

Añadimos la siguiente línea donde pone Add Custom CSS: ```@\import "https://xsojo.github.io/MyAnimeList/Sojo.css";```


Si queremos un nombre, un avatar, un banner o un personaje, o un fondo añadimos lo siguente en el Custom CSS:

```:root {
    --name: "\a   Sojo";
    --avatar: url(https://cdn.myanimelist.net/images/userimages/2637631.jpg);
    --banner: url(https://i.imgur.com/VoPJz2S.jpg);
    --character: url(https://i.imgur.com/6IPyngH.png);
    --background: #000000;
}```