# Bahn

Publicación open-source de diseño web en español.


## ¿Cómo envío un post?

¿Ya tenés un tema interesante que querés compartir? Ok, ahora tenés que seguir estos muy simples pasos:

1. Hace fork de este repositorio y clona tu fork a tu computadora. 
2. Duplica el archivo _posts/2012-12-13-la-base.markdown. Cambiale el nombre (es importante que utilizes el mismo formato pero cambiando fecha y nombre) y editalo a tu gusto, utilizando Markdown o puro html para el formato. Si no sabes Markdown, no te preocupes que el archivo por defecto ya tiene todos los elementos que podes utilizar en tu post. No cambies el campo status en la parte superior del archivo, ese cambio lo hacemos nosotros justo antes de publicar tu post.
3. Si es la primera vez que escribís para Bahn, abri el archivo _config.yml y sumate a la lista de autores siguiendo el mismo formato que tienen los demás.
4. Hace commit de todos tus cambios y luego desde la interfaz de GitHub, activa un pull request hacia el repositorio original de Bahn.
5. Revisamos el pull request, charlamos de si hacen falta cambios o hay errores, y una vez que esta todo ok, se acepta la acción. Finalmente nosotros hacemos algún cambio final si es necesario, ¡y tu post es publicado!

Como te anticipé, ¡es muy fácil! Y de bonus aprendés algo nuevo para aplicar en tus projectos de Git.


## ¿Como puedo hacer preview local de como se ve mi post?

Para eso necesitas instalar jekyll, que es el encargado de generar el sitio final. Si ya tenés Ruby, es muy sencillo:

1. Instalás Jekyll: gem install jekyll
2. Corres Jekyll con update automatico de cambios: jekyll --server --auto
3. Vas a localhost:4000 y ves el sitio, si a eso le agregas el nombre de tu post a la url ¡ya podés hacer preview de tu nuevo post!


## Quiero participar pero me parece medio complicado todo esto, ¿qué hago?

Escribinos a hola@leobahn.com o en Twitter en @leobahn, y contentos te ayudaremos a que ¡publiques tus ideas!


## Encontre un bug en el sitio, y no me gusta como se ve.

El código fuente de todo el sitio esta disposible en GitHub, por ende con el mismo modus operandi que se utiliza para publicar nuevos posts, también se pueden hacer para sugerencias de mejoras en el sitio. No le tenemos miedo a aceptar que debe haber muchísimos mejores diseñadores y programadores que nosotros, asi que ¡son más que bienvenidas las ideas con código que soporten a las mismas!