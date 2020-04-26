# WIP
#### Estamos trabajando en ello

------------

Entrar en [https://myanimelist.net/ownlist/style](https://myanimelist.net/ownlist/style "https://myanimelist.net/ownlist/style")

Seleccionar una lista que queremos editar y hacemos clic sobre el estilo que queremos sobreescribir.

Añadimos la siguiente línea donde pone Add Custom CSS:
```css
@\import "https://xsojo.github.io/MyAnimeList/Sojo.css";
```


Si queremos un nombre, un avatar, un banner o un personaje, o un fondo añadimos lo siguente en el Custom CSS:

```css
:root {
    --name: "\a   Sojo";
    --avatar: url(https://cdn.myanimelist.net/images/userimages/2637631.jpg);
    --banner: url(https://i.imgur.com/VoPJz2S.jpg);
    --character: url(https://i.imgur.com/6IPyngH.png);
    --background: #000000;
}
```


Si queremos que la etiqueta de coronavirus destaque añadimos la siguiente línea:
```css
@\import "https://xsojo.github.io/MyAnimeList/Coronavirus.css";
```

Si queremos que los tags tengan colores para los días de la semana y para Crunchyroll y Selecta Visión:
```css
@\import "https://xsojo.github.io/MyAnimeList/develop/Tags.css";
```

Si queremos que las valoraciones estén ocultas si no están valoradas y que tengan valoraciones dependiendo de la puntuación (1-4 malo, 5-7 normal, 8-10 bueno):
```css
@\import "https://xsojo.github.io/MyAnimeList/develop/Score.css";
```

Si queremos unir las columnas de Progress y Premiered:
```css
@\import "https://xsojo.github.io/MyAnimeList/develop/ProgressPremiered.css";
```