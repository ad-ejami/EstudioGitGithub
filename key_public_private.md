# llaves publicas y privadas

## problema:

Tu deseas enviar un mensaje a una persona en especial, supongamos que a tu enamorado/enamorada, por internet
pero deseas que solo esa persona lea tu mensaje, y que ningun otro cibernauta pueda leer ese mensaje.
¿como hacer para que nadie mas que tu enamorad@ pueda leer ese mensaje?

## respuesta 
Lo que se hace es cifrar el mensaje, enviarlo a tu enamorad@ y por medio de la contraseña 
descifrarlo y leerlo, listo, tenemos la solucion pero hay un detalle importante
**¿COMO LE ENVIAMOS LA CONTRASEÑA?**
¡si alguien mas lee esa contraseña entonces podra descifrar tus mensajes!

## solucion 
Hay un sistema llamado **llaves publicas y llaves privadas** el cual permite enviar esta contraseña de forma 
segura y tener una comunicacion de cifrado con una persona o varias(si deseas compartir tu llave con mas
de una persona)

# como funcionan las llaves publicas y privadas?

Vamos a crearnos dos tipos de llaves, una llave **publica** y una llave **privada** las cuales tienen un vinculo matematico, entonces si yo cifro un mensaje con mi llave **publica** solo se puede descifrar con mi llave **privada**. (Supongamos que ya tenemos creado estas llaves)
Muy bien, ahora como te comparto estas llaves?
- pues para empezar eviale tu **llave publica** a tu enamorad@,
espera, ¿Que pasa si alguien mas lo intercepta?
no te preocupes que por eso enviamos la **llave publica**, es decir todos pueden poseer esta llave,
de hecho puedes publicarla en tu facebook, pagina web, o en otros sitios que se te ocurran.
Esta llave esta conectada matematicamente a la **llave privada**, y aqui lo fundamental es que nadie conozca a esta llave. (una vez captada esta idea podemos continuar)
- entonces lo siguiente es que tu enamorad@ copia tu **lave publica** y realiza un proceso matematico (es decir que debe cifrar el mensaje con la llave publica que tu generaste) y tenemos un nuevo mensaje (este es uno cifrado que no importa cuanto lo intenten otros no podran descifrarlo a menos que tengan tu llave privada) lo siguiente es enviartela
- por ultimo solo necesitas descifrar el mensaje con tu **lave privada**

listo!!! tienes un sistema de envio de mensajes cifrado con llaves publicas y privadas