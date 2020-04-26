# MyAnimeList

Entrar en [https://myanimelist.net/ownlist/style](https://myanimelist.net/ownlist/style "https://myanimelist.net/ownlist/style")

Seleccionar una lista que queremos editar y hacemos clic sobre el estilo que queremos sobreescribir.

Añadimos la siguiente línea donde pone Add Custom CSS: ```@\import "https://xsojo.github.io/MyAnimeList/Sojo.css";```


Si queremos un avatar añadimos lo siguiente:
```:root {
    --avatar: url(https://cdn.myanimelist.net/images/userimages/2637631.jpg);
}```

Si queremos un nombre añadimos lo siguiente: 
```:root {
    --name: "\a   Sojo";
}```
