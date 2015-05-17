---
title: "Hackeo"
bg: purple    #defined in _config.yml, can use html color like '#010101'
color: black  #text color
style: left
fa-icon: crosshairs
---

<h2 class="text-white">Protege tus cuentas digitales.</h2>

Tus cuentas digitales son puntos de acceso para tu vida, tanto en linea y en la vida. Desde email, hasta las redes sociales, a compras, tus cuentas son cruciales para casi todo lo que haces a través del internet. Entre todas las cuentas que usas hay un tesoro de información personal, datos de tus tarjetas, y hasta la posibilidad de ser “tu” en espacios virtuales. Desafortunadamente, hackers y violentos consideran muy valioso poder acceder estas cuentas: robar esta información es unas de los ciber-crimenes más comunes. Esta sección de la guía te muestra varias formas de hacer más difícil el hackeo de tus cuentas. <strong>Como con cualquier dispositivo electrónico, no hay una forma 100% segura de protegerte contra un hacker con vocación (y no debes confiar en quien te dice que sí)</strong>, pero agregando capas de seguridad te brinda mucho más control sobre tu identidad virtual y puede acotar muchas de las formas más comunes del hackeo. 

Lo más importante recordar mientras delineamos las mejores practicas, tecnologías útiles y servicios recomendado es es el nivel de riesgo de cada contexto. Una de las mejores preguntas que nos hacemos es “¿si esta cuenta fuera hackeada, como me impactaría en la vida diaria? Pensando así significa que TU dictas el nivel de seguridad y privacidad de tu vida digital. Puedes decidir agregar más medidas de seguridad, o menos. Puedes elegir un servicio más seguro o quedarte con lo que tienes. ¡Es tu decisión!  

<hr>
<div id="phishing">
<p>
	<h3 class="text-white">Ingeniería Social y <strong>Phishing (pesca de datos)</strong></h3>
</p>
</div>
Aunque no lo creas, la mayoría de los hackeos no necesitan de habilidades técnicas avanzadas. Hay trucos muy simples que utilizan muchxs hackers malvados, desde los trolls más patéticos hasta los espiás gubernamentales los utilizan para conocer tus contraseñas, mails y otra información sensible. <strong>Ingeniería Social es una forma de manipulación psicológica de una persona para lograr que revele información sensible.</strong> Un ejemplo común es un hacker que llama a un centro de ayuda al cliente o apoyo técnico de un sitio web: se hacen pasar por un empleado o cliente y con mentiras y convicción logran conseguir información vital de un cliente real. Otro caso común es simplemente llamar a la persona elegida, haciéndose pasar por representante de una empresa o de un servicio: un hacker puede decirse ser un personal de servicio que necesita saber información sobre tu departamento, o personal de salud que necesita saber sobre tu obra social, entre numerosos otros roles, para robarte información. <strong>Phishing, o la pesca de datos a través de emails falsos que aparentan ser de un servicio real y te piden seguir un link, es una forma muy común de ingeniería social.</strong> Cuando sigues el link, aparentan llevarte a un sitio legitimo, que te pide tu contraseña o PIN de tarjeta bancaria, o otros datos. ¡En realidad, el sitio es falso y recolecta todos los datos privados que le entregas sin querer!


¿Cómo te puedes entonces proteger de este tipo de ataques? Tenemos un par de ideas que te pueden ayudar. 


<div class="recommend">
<h5 class="text-white">No entres a sitios web desde un link en un email.</h5>
<br>
Como regla general, si un email te lleva directo a una pantalla de acceso, deberías sospechar. Es mejor ir directamente al sitio desde el navegador, acceder normalmente, y buscar la página que el mail te sugería. Una excepción a la regla es cuando has pedido cambiar tu contraseña para un sitio (el sitio necesita proveerte con un link personalizado para que puedas cambiar tu contraseña). En este caso, solo asegurate que realmente has pedido un cambio de contrasela. ¡Y usa una <a href="#strongpasswords">contraseña única</a> para mayor seguridad!

</div>

<div class="recommend">
<h5 class="text-white">Evita usar Facebook, Twitter o Google para acceder a otros sitios</h5>
<br>
Muchos sitios ofrecen la oportunidad de acceder con tu cuenta de red social, en vez de tener que registrarte con el sitio de cero. Aunque parece conveniente, en realidad presenta un gran riego a tu seguridad virtual: ¿cómo sabes que el sitio es legitimo? Es mucho más seguro crear una nueva cuenta para el sitio. Al alentarte para acceder con una cuenta de red social, un sitio malintencionado puede fácilmente recolectar información valiosa como nombres de usuario y contraseñas. 

</div>

<div class="recommend">
<h5 class="text-white">No confíes en emails que piden tu información privada, datos de encuestas o lo que sea que pueda revelar información sobre tu persona, sin importar lo profesional que parezcan. </h5>
<br>
La mayoría de los sitios web no necesitan de tus datos personales para proveerte sus servicios, por lo cual puedes sospechar si te los piden (¿De todos modos, que importa lo que quieren? No es tu responsabilidad darles <em>nada</em>). Si realmente crees que el pedido es legitimo, no siguas el link que te proveen en el mail: deberías poder hacer lo que te piden desde su página en tu navegador. Si no lo puedes hacer, claramente tienen muy malas practicas de seguridad y deberías sospechar igual.

</div>

<div class="recommend">
<h5 class="text-white">Usa conexiones con HTTPS en lo posible </h5>
<br>
En la <a href="#anonymity">sección de Anonimato</a>, hablamos sobre lo valioso que es usar la extensión <a href="#httpseverywhere">HTTPS Everywhere</a>. Cuando te conectas a un sitio usando HTTPS, el navegador certifica la legitimidad del sitio usando un certificado de seguridad. 
Por que sitios falsos no pueden replicar el certificado de HTTPS esperado, tu navegado te devuelve un aviso que el sitio es inseguro. <strong> ¡Confía en tu Navegador! </strong> Al instalar la extensión <a href="#httpseverywhere">HTTPS Everywhere</a>, tu navegador intentara utilizar una conexión HTTPS en lo posible, dándote una protección de primer grado contra las estafas de pesca de datos. 


</div>

<div class="recommend">
<h5 class="text-white">Cuidado del wi-fi público</h5>
<br>

Cuando estas usando una red de wi-fi, cualquier personas compartiendo la misma red puede mirar tu actividad o intervenir tu actividad (aún cuando la red esta protegida con contraseña), Un fácil plan de pesca de datos es sentarse en un café y intervenir todas los pedidos a facebook.com, usando un sitio falso, y recolectando muchos datos de acceso. La mejor forma de protección es usar una <a href="#vpn">Red Virtual Privada o VPN (Virtual Private Network)</a> que cifra tu trafico de web sin interrupciones para que no se pueda intervenir. Una alternativa genial es usar siempre el <a href="#tor">Navegador de Tor</a> para enviar tus datos a través de la red Tor, que cifra tus datos y te brinda anonimato (aunque será más lento que tu navegador común). Si estas usando tu celular, trata de usar solo las aplicaciones regulares en vez de usar un navegador de teléfono para acceder a los sitios (ya que navegar por teléfono es <a href="#phones">mucho menos seguro</a>).


</div>

<hr>
<div id="fakeemail">
<p>
	<h3 class="text-white">Entonces... ¿En que instancias necesito dar mi información personal? (...nunca)</h3>
</p>
</div>
Muchas veces, un sitio o un servicio quiere más información tuya que solo un mail y una contraseña. Quieren saber tu nombre completo, tu información geográfica, y otra información jugosa para el marketing. Bueno... ¡Que se vayan al diablo! <strong> Una buena regla general es solo entregar información general si solo es crucial. ¡No temas inventar tus datos! </strong> Podes inventar tu nombre, dirección, y todo tipo de información falseada. A no ser que estés comprando algo, muy pocas veces esta información es realmente necesaria. Al proveerles con data falsa, bajas el riesgo de que una cuenta hackeada pueda vincularse a otras cuentas a través de datos conectados, ademas de bajar los riesgos de que una persona malintencionada obtenga más datos tuyos en la vida real. 

<br>
<br>

(<em>Por supuesto, una dirección de email tampoco necesita ser real. Si solo te estás registrando para usar un sitio una o dos veces, puedes usar una dirección de email descartable. Esto es más útil aún cuando necesitas hacer algo anonimamente. Nos gusta usar <a href="https://www.sharklasers.com/">Sharklasers.com</a> por que los tiburones son geniales, pero hay muchos servicios similares.</em>)


<hr>
<div id="strongpasswords">
<h3 class="text-white">Buenas Contraseñas: <strong>“Uf”</strong></h3>
</div>
Como dice la revista xkcd, “Despues de 20 años de esfuerzo, hemos logrado que todo el mundo use contraseñas que a los humanos les cuesta recordar, pero que son fáciles de adivinar para las computadoras.”

La mayoría de los sitios y cuentas se acceden usando una contraseña y dirección de email/nombre de usuario. Como ya sabemos, una buena contraseña es esencial para asegurarse que hackers no pueden entrar en nuestras cosas. De todos modos, las formas que creamos y nos acordamos de las contraseñas son fáciles de hackear: frases y palabras comunes pueden ser explotadas usando programas que repiten intentos hasta ingresar a tu cuenta. Ya que son la primera y muchas veces única defensa para acceder a tus cuentas, las buenas contraseñas son clave. 


Aquí hay unas reglas generales para crear buenas y fuertes contraseñas: 

<div>
<br>
<ol>
	<li>Una mezcla aleatoria de letras, numeros y caracteres especiales es lo mejor. </li>
	<li>Cuanto más largas, mejore. ¡Intenta usar más de 12 caracteres, siempre! </li>
	<li>Sí  vas a usar palabras reales en tu contraseña, trata de usar palabras y referencias poco conocidas o mal escritas. Palabras de diccionario o de cultura popular no son una buena idea. </li>
	<li>NO REPITAS LA MISMA CONTRASEÑA EN MULTIPLES SITIOS.</li>
	<li>NO REPITAS LA MISMA CONTRASEÑA EN MULTIPLES SITIOS.</li>
</ol>
</div>

<hr>
<div id="passwordmanager">
<h3 class="text-white">Administrador de Claves: <strong>“¡Genial!”</strong></h3>
</div>
Como podes adivinar, hacer contraseñas fuertes es difícil. Cuando tenes decenas de cuentas atravesando muchos sitios, es casi imposible ser impecable al crear y recordar todas las claves únicas. Ni hablar de que hay sitios que no son confiables en guardar tus claves: los hackean, pero -tu- debes cambiar tu contraseña. Por suerte, hay muchas herramientas que te pueden ayudar. Un administrador de claves es un servicio que puede generar y guardar todas tus contraseñas para que no tengas que memorizarlas. 

El sitio Lifehacker tiene una <a href="http://lifehacker.com/5529133/five-best-password-managers">guía en inglés </a>que demuestra los administradores de claves más populares. Aún si no conoces inglés, puedes chusmear cuales son los programas sugeridos. 

Probablemente tengas algunas dudas: ¿No será peligroso guardar todas tus contraseñas en un solo lugar? Y tienes razón. ¡Lo es! Por eso es importante evaluar como cada administrador de claves realmente administra las claves y que protecciones implementa. Finalmente, tendras ue medir los riesgos de tener contraseñas malas que se guardan por separado en cada sitio, o contraseñas buenas que se guardan en un solo lugar. 


<div class="recommend">
<h5 class="text-white"><strong>LastPass</strong></h5>
<br>
Al considerar lo difícil que es recordar contraseñas seguras y únicas, seguimos recomendando un administrador de contraseñas. Específicamente el servicio <strong>LastPass</strong>.

<br>

LastPass usa una combinación de extensiones de navegador, aplicaciones de celular, cifrado, autenticación doble, y una multitud de otras tecnologías para asegurar que tus contraseñas son guardadas seguramente y accesiblemente (pero solo para tí). También puede generar azarosamente contraseñas – extremadamente – fuertes para tu uso. Nos gusta LastPass por que todas tus contraseñas son cifradas al guardarlas en la nube de Last Pass. Así que aún si se hackean los servidores, hackers no pueden usarlas a no ser que tengan tu contraseña de LastPass (que no se guarda en LastPass). Así que si decides usar LastPass, asegurate que la contraseña de LastPass es la más fuerte de todas las que has usado. No necesitaras recordar todas tus contraseñas, por lo cual esto último es más factible. 

<br>
<br>
Puedes arrancar con LastPass en su <a href="https://lastpass.com/">sitio oficial</a>.<br>
<br>
Como pensamos siempre en mitigar riesgos, recomendamos que no uses LastPass para tus contraseñas de email, de home banking, o de obras sociales. Aunque LastPass es un servicio extremadamente seguro, sigue siendo una empresa sujeta a vulnerabilidades. Al separar tus contraseñas más cruciales, tenes un poco más de protección al no jugartelo poner todos los huevos en una sola canasta. ¡Los huevos más importante necesitan de su propia canasta!

<br>
<br>
Algunas reglas generales al usar LastPass: 
<br>
<br>
<ul>
	<li>Usa generación de claves, para generar claves largas y complicadas. Las mejores tienen por lo menos 16 caracteres y van con letras, numeros y simbolos. </li>
	<li>Siempre utiliza la autenticación doble para LastPass.</li>
	<li>Configuralo para que siempra te pida tu contraseña maestra al ingresar en cuentas importantes. </li>
	<li>Una vez que accediste a LastPass en tu celular o tablet, desde la página de despósito en el sitio de LastPass, vaya a configuración y bajo “dipositivos mobiles” asegurate de que este seleccionada “Restringir dispositivos mobiles a UUIDs espeficados”. De esta manera solo los dipositivos especificados pueden acceder a tu LastPass. </li>
</ul>
</div>

<hr>
<div id="twofactor">
<h3 class="text-white">Autenticación Doble: <strong>“¡Si!”</strong></h3>
</div>
Una de lo mejor que puedes hacer para tus cuentas en linea es habilitar la autenticación doble (2FA), adonde lo sea posible. Esencialmente, antes de entrar, necesitas no solo una contraseña sino también un dato más. Es generalmente un código enviado por email, SMS o generado por una aplicación celular. 2FA es una forma maravillosa de asegurar tus cuentas por que significa que aunque se puedan hackear tus contraseñas, hackers tendrían que necesitar acceso a otras cuentar de email, o tu celular o las aplicaciones para poder acceder a tu cuenta. 

Para las cuentas más importantes, definitavamente te recomendamos que habilites 2FA. La mayoría de las companías grandes, como Google, Facebook, Dropbox y Twitter tienen esta opción, y también la ofrecen administradores de claves como LastPass.  Tipicamente tenes que buscar en las opciones para encontrar las instrucciones de como habilitarla. <a href="https://www.google.com/landing/2step/">Aquí</a> una guía útil si quieres saber más de como funciona  Autenticación Doble. 


<div class="recommend">
<h5 class="text-white"><strong>Authy</strong></h5>
<br>
Cuando usas un sitio o servicio que ofrece Autenticacion Doble (2FA) muchas veces tenes la opción de generar un codigo QR o numerico que luego lo agregas a una aplicación de 2FA en tu celular. 
Desde ese momento en adelante, cuando accedes a un sitio y servicio y te piden un codigo 2FA, solo necesitas buscar en la aplicación para el código asociado con esa cuenta. Esta forma es más segura que recibir un codigo a un SMS o email, ya que es más dificil acceder por hackeo o vigilancia. Hay varias aplicaciones que ofrecen esta funcionalidad, pero te recomendamos Authy. 

<br>
<br>
Authy es una aplicación que directamente genera codigos fuera de linea, donde sea que la tengas instalada. Authy se puede instalar en tu computadora, o cualquier celular, con todos tus códigos 2FA guardados en una cuenta Authy.  Esto significa que si pierdes tu celular, o compras una nueva notebook, puedes instalar Authy de nuevo y acceder con tu información de cuenta (¡debes tener una contraseña fuerte!), y tus códigos 2FA se agregan sin interrupciones. Tus cuentas son cifradas en la nube, lo cual significa que si se hackean los servidores de Authy ¡Tu información no les sirve! Y como los códigos son generados fuera de linea, no necesitas internet o datos mobiles para poder accederlos. 

<br>
<br>
Authy se puede bajar gratuitamente desde iTunes y Google Play, y también como extanción de Chrome<br>
Guías de instalación se pueden encontrar en <a href="https://www.authy.com/users">el sitio de Authy</a>
</div>

<hr>
<h3 class="text-white">Y... Cómo se si me han <strong>Hackeado</strong>?</h3>
Las empresas privadas tienen algunas de las peores practicas de seguridad imaginables. Tus contraseñas pueden estar guardadas en una base de datos en texto simple, asociadas a tus cuentas de mail y dirección real, a veces hasta con la información bancaria. <strong>No hay reglamentaciones existentes para que las empresas tomen en serio tu información privada, entonces muy pocas empresas lo hacen. Por consecuencia, hackeos corporativos y filtraciónes de información son cada vez más comunes, y solo continuarán como la minería de datos y la venta masiva de datos personales.</strong> Seguramente ya sabes de los hackeos corporativos en los noticieros, pero pocas veces marcan tendencias y se olvidan rapidamente. Desafortunadamente, estos datos personales filtrados no desaparecen con el tiempo: se acumulan por internet y se guardan indefinitivamente, filtrando tus datos, a veces por hackers, o por profesionales de seguridad. Por ende, si no te enteras de que una empresa ha filtrado tu información, o simplemente lo olvidas, ya eres vulnerable a la exposición de tus datos personales (despues de todo, ya tienen tu información personal)



<code>Fijate en el sitio<a href="https://haveibeenpwned.com/">haveibeenpwned</a> para ver si tu email o nombre de usuario alguna vez se ha filtrado en una infracción de datos importante.   Tu único curso de acción es usar <strong><a href="strongpasswords">claves fuertes, únicas</a></strong> y <strong><a href="#twofactor">autenticación doble</a></strong> para todas tus cuentas importantes.</code>