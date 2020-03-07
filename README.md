Para este proyecto se necesitara la configuracion de la **API Graph Instagram**, se puede usar la API para obtener y publicar su contenido multimedia, administrar y responder comentarios en ese contenido, identificar contenido multimedia en el que otros usuarios de Instagram los hayan @mencionado, buscar contenido multimedia con hashtags y obtener metadatos y métricas básicos sobre otros creadores y empresas de Instagram. 

En este caso se utiliza para la optencion de los datos multimedia de propio Perfil y optencion multimedia de los tags que el usuario externo realiza. 

Para ello requerimos del token y id de usuario de una cuenta instagram, que tiene que ser de tipo empresa o developer y pública 


Para  la obtención de Token ingresar a tu cuenta facebook donde tienes que tener una pagina de tipo developer previamente creada desde Instagram. 

1. Ingresar a la siguiente url, https://developers.facebook.com/apps/ cear una nueva app. 
2. En el panel al que te manda despues de crear tu app es recomendable darle clic en Configurar Instagram, para que el producto se agregue 
3. Despues nos dirigimos al Explorador de API Graph  https://developers.facebook.com/tools/explorer/.
4. A la derecha seleccionamos el nombre de la app de la cual queremos obtener el token, seleccionamos token de usuario, y agregamos los siguientes permisos: 
                * manage_pages
                * pages_show_list
                * ads_management
                * business_management
                * instagram_basic
                * instagram_manage_comments
                * public_profile
5. Se genera un token temporal, para que el token de larga duración (de 3 meses aproximadamente), seguir las instrucciones del siguiente link: 
