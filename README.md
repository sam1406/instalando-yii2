# instalando-yii2
1- descargar composer,xampp, atom o sublimetext,git
2- abrir la consola de git y teclear lo siguiente 
  https://github.com/settings/tokens y generar un nuevo token
  composer config --global github-oauth.github.com <TOKEN>
  
  composer create-project --prefer-dist yiisoft/yii2-app-advanced nombre_app
  entramos  a la carpeta nombre_app y le damos php init para inicializar la aplicaciones
