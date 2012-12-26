---
type: text
state: queue
tags: Enseñanzas, Filosofía Lean, Aprendizaje, Experiencia Personal, text
slug: la-filosofia-lean-startup-aplicada-a-tu-pagina-personal
tweet: "La filosofía Lean Startup aplicada a tu página personal – @LeanStartMadrid [URL]"
---

![Lean Startup Circle](http://media.tumblr.com/758aacb2f074e01b52f3c35014dba6aa/tumblr_inline_mfm25mDc5C1rcrrs5.jpg)

Hace unos meses (concretamente en Agosto de 2012) decidí que sería una buena idea comenzar a preparar mi desembarcamiento de manera seria en Internet. Acababa de terminar mi Ingeniería Informática en Junio y era un buen momento para comenzar los nuevos proyectos que tenía (y que sigo teniendo) en mente. Te preguntarás, ¿y qué significa desembarcar de manera seria en Internet?, ¿acaso no tienes perfiles en Facebook, Twitter, GitHub (por no decir 800 redes más)? Pues resulta ser que [si][1], [si][2], [si][3] (y [800 veces si][4]).

Pero yo, con lo de desembarcar de manera seria en la red, me estoy refiriendo a *crear una buena imagen* en la misma. Significa depurar las cosas que no merecen la pena ser contadas de ti y resaltar las que si. El motivo de todo esto es simple (aunque no sólo está este, para mi hay otros más importantes): aumentar mis *probabilidades* de encontrar empleo. [Hay estudios que indican que cada vez se realizan más búsquedas en la Web][5] en la caja de Google con tu nombre y apellidos. Y créeme, hay demasiada información sobre ti en la red (te recomiendo que lo pruebes, te acabarás sorprendiendo con lo que puedes llegar a ver).

Pero a lo que iba (ya tocaré el tema anterior más detenidamente en otra entrada, [considera subscribirte al feed RSS para estar enterado](http://aldoborrero.com/rss)), en Agosto, aparte de querer resaltar mis "bondades", también decidí que sería una buena idea abrir mi propia página personal con su respectivo blog. Los motivos por los que debes tener un blog son claros: conoces mucha gente nueva, hablas de lo que más te gusta y, de paso, ayudas a otras personas que tienen dudas sobre alguna temática en concreto (o las entretienes, según sobre lo que escribas).

Así pues, los objetivos principales ya estaban claros y definidos. Ahora tocaba saber el cómo lo iba a lograr, lo que se conoce en informática como el "backend".

Para la parte de "limpiar" mi imagen en la red es simple (aunque hay más miga, como he mencionado antes volveré a tocar este tema más detenidamente): borra todas las cuentas que no quieras tener abiertas y ya Google se encargará de ir cambiando la posición de los enlaces al cabo de unos días (o meses). Así mismo, para las redes sociales, lo que quieras que se haga público, lo haces público y lo que no, lo haces privado (sentido común, pero que muchas veces no lo aplicamos, triste pero cierto).

Sin embargo, para la parte de crear mi blog quería no optar por el camino fácil. Actualmente para crear uno podemos abrir una cuenta en [Wordpress.com][6], [Blogger][7], [Tumblr][8] y 20.000 lugares más y tenemos un blog, que por lo general tiene algunas limitaciones (ya sean en aspecto gráfico, como en características capadas), pero que funciona.

Yo, a lo **Macho Man**, deseché todas esas posibilidades. ¿Usar una plantilla hecha por defecto y que encima se ve en muchos sitios? ¿Hospedar mi página web en un servidor externo y aceptar por coj\*\*\*s las limitaciones impuestas por dicho servicio? ¿No controlar temas de optimización de [HTTP][9], de [PHP][10] y de conexiones a la base de datos?

¡Ni en broma!

Así pues me enfrasqué en la noble tarea de "alquilar" un servidor propio en [Linode][11] y comencé a montar desde cero todo el "stack" de tecnologías que iba a llevar mi página (si, eso incluía desde el sistema operativo del servidor, hasta la configuración más óptima que le puedes realizar a Varnish para que sirva la caché lo más rápido posible).

### Y es ahí cuándo comenzó la espiral infinita…

A principios de Septiembre, un mes después de comenzar con el proyecto, logré lanzar la primera versión de mi página web. ¡Lo habría logrado! Ya tenía una página personal en Internet y estaba contento con mi hazaña. Había estado todo el mes anterior aprendiendo muchas tecnologías (y, en algunos casos, mejorando mis conocimientos sobre cosas que ya sabía anteriormente). Así que me puse a escribir unos cuantos artículos. Y los publiqué.

Pero…

a mi juicio lo que había producido era un despropósito. No estaba todo controlado bien. Observaba fallos por todos lados. Veía el diseño que había aplicado (la parte que el usuario visualiza al navegar en mi página) y no estaba conforme del todo. Por otra parte, en temas más internos, tenía que mejorar mucho la configuración del servidor, tenía que mejorar mis conocimientos sobre seguridad de servidores, tenía que esto, tenía que lo otro…

Así pues, comencé con cada una de las cosas de la lista de cosas por mejorar, y me puse a aprenderlas. La lista era demasiado larga, aunque te puedo comentar que las lecciones que he sacado de este aprendizaje han sido bastante interesantes ya que he tocado muchas tecnologías diferentes (sin un orden en particular y que me acuerde a bote pronto: [CSS][12] junto con [SASS][13], [Wordpress][14], [PHP][10], [iptables][16], [Nginx][17], [Varnish][18], [Jekyll][19], [SSH][20], [SSHGUARD][21], [SNORT][22], [port knocking][15], parches en el kernel del sistema operativo para mejorar la seguridad del sistema, [Capistrano][23], [Chef][24]…).

Y fue así, liado entre tantas tecnologías y bastante seducido por ellas, cuando llegué a 22 de Diciembre de 2012. Habían pasado casi cinco meses desde que lancé mi página y ahí estaba la pobre sin un mísero nuevo artículo. Estaba tan enfrascado en sacar una "segunda versión" más mejorada, con más novedades, con más perfección tipográfica, con mayor optimización y demás historias… ¡qué me había olvidado por completo de cuál era el objetivo principal: el blog inicialmente se creó con la idea de escribir sobre los temas que me interesaban!

### Filosofía Lean Startup al rescate

Cuando me di cuenta de en el lio que me había metido yo solo, pensé: ¿y he montado todo esto para mejorar mi propia página? ¿Necesitaba tanta perfección? ¿Tanto incluso que me ha quitado de lo que de verdad importa que es escribir? ¿Qué sucederá cuándo decida hacer un proyecto que sea más importante? ¿Durará años? ¿Décadas? ¿Siglos?

En el mundo actual en el que vivimos hay una cosa muy clara: hay que moverse muy rápido (eso si, sin estrés por favor). Nada ni nadie espera por ti. Como decían en una película:

> Time waits for no one (El tiempo no espera a nadie).

¡Ojo! Moverse rápido no significa hacer las cosas mal. Significa pensar con cabeza cuál es el objetivo principal, grabartelo en la cabeza a fuego, y gastar las mínimas energías para alcanzarlo. No importa si la primera versión que produces es imperfecta, ya irás recogiendo la suficiente información para darte cuenta de que necesitas lanzar otro pequeño cambio que mejore lo anterior. Y así sucesivamente: ¡se trata de convertir la idea en un circulo infinito que se retroalimenta de la experiencia previa!

¡Eso es [Lean Startup][25]!

### Resultado

Aplicando esta filosofía he conseguido montar mi página web en menos de 24 horas reales de tiempo dedicado (he estado varios días pero también tenía otras cosas distintas por hacer).

Te preguntarás: ¿y cómo?

Muy fácil: quité el servidor en el que estaba trabajando (mentira, lo sigo usando para otros proyectos personales), me registré en Tumblr, compré una plantilla que cumpliese una serie de requisitos mínimos (que fuera minimalista, con tipografía elegante y amigable para los móviles), la adapté a mi gusto, migré los artículos del anterior servidor a aquí y ya está. Se acabó. La sencillez al rescate.

No me tengo que preocupar por administrar el servidor. No me tengo que preocupar por saber si todo está optimizado o no. Sólo me dedico a la idea principal: escribir haciéndolo de la manera *más simple*, *más económica* y *rápida* posible (eso es lo que se conoce en Lean Startup como el *[Minimum Viable Product][26]*, Producto Mínimo Viable).

Y si, es posible que la página tenga algunas deficiencias: quizá la navegación la encuentres pobre, o quizá no se ven fácilmente los enlaces a mi currículo, correo o redes sociales que utilizo… Pero no me preocupa. Tú, querido lector, serás el que me vaya dando las pistas necesarias ya que, para eso, poseo [herramientas de análisis][27] que me indican si las diferentes partes de mi web son óptimas o no. En cuanto detecte una deficiencia, actuaré para modificar la página en consecuencia. Y se volverá a reiniciar el ciclo otra vez. Iterando e iterando.

Lo bueno de la filosofía Lean Startup es que puede ser aplicado a cualquier cosa que hagas en la vida, ya sea en temas personales o en temas profesionales.

Mi consejo... [¡agárrate una copia del libro y no lo sueltes hasta que seas capaz de recitarlo de memoria!][28]

Y recuerda:

> Comienza simple. Luego ya conquistarás el mundo.

[1]: https://facebook.com/aldoborrero "Mi perfil personal en Facebook"
[2]: https://twitter.com/aldoborrero "Mi perfil personal en Twitter"
[3]: https://github.com/aldoborrero "Mi perfil personal en GitHub"
[4]: http://media.tumblr.com/e54dac300327a291511c79d7bd8f7136/tumblr_inline_mfm2ooLabE1rcrrs5.gif "Mmmm"
[5]: http://business.time.com/2012/07/09/how-recruiters-use-social-networks-to-make-hiring-decisions-now/ "How recruiters use social networks to make hiring decisions now"
[6]: http://wordpress.com "Wordpress.com"
[7]: http://blogger.com "Blogger"
[8]: http://tumblr.com "Tumblr"
[9]: http://es.wikipedia.org/wiki/Hypertext_Transfer_Protocol "Protocolo HTTP"
[10]: http://es.wikipedia.org/wiki/PHP "PHP"
[11]: http://linode.com "Linode"
[12]: http://es.wikipedia.org/wiki/CSS "Cascading Style Sheets"
[13]: http://en.wikipedia.org/wiki/Sass_(stylesheet_language) "SASS"
[14]: http://wordpress.org "Wordpress"
[15]: http://en.wikipedia.org/wiki/Port_knocking "Port Knocking"
[16]: http://en.wikipedia.org/wiki/Iptables "Iptables"
[17]: http://nginx.org "Nginx Web Server"
[18]: https://www.varnish-cache.org/ "Varnish Cache"
[19]: https://github.com/mojombo/jekyll "Jekyll"
[20]: http://en.wikipedia.org/wiki/Secure_Shell "SSH"
[21]: http://www.sshguard.net/ "SSHGUARD"
[22]: http://en.wikipedia.org/wiki/Snort_(software) "Snort"
[23]: http://en.wikipedia.org/wiki/Capistrano "Capistrano"
[24]: http://www.opscode.com/chef/ "Chef"
[25]: http://theleanstartup.com/ "Lean Startup"
[26]: http://en.wikipedia.org/wiki/Minimum_viable_product "Minimum Viable Product"
[27]: http://getclicky.com "Clicky"
[28]: http://www.amazon.co.uk/The-Lean-Startup-Innovation-Successful/dp/0670921602/ref=sr_1_1?ie=UTF8&qid=1356484125&sr=8-1 "Libro de Lean Startup"