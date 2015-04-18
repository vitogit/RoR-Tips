
## Generador de aplicaciones en rails
http://railsapps.github.io/rails-composer/ 
Basicamente creas una aplicacion de rails asi: 
<pre> rails new myapp -m https://raw.github.com/RailsApps/rails-composer/master/composer.rb </pre>

##Shortcuts de rubymine
<pre>
ctrl + tab : switch entre las tabs
ctrl+shift+f10 : corre el test en el que estas parado
ctrl + shift +r : busca el contrller, model, pagina
ctrl +h : busqueda de texto global
</pre>


## CSS en ruby on rails
En la carpeta app/assets/stylesheets estan los css, tienen extension scss. Al inicio se carga el application.css.scss
Cada vez que se accede a una pagina de un controller especifico se carga un css particular para cada uno, es decir si entramos a /tasks va a cargar tasks.css.scss. 
