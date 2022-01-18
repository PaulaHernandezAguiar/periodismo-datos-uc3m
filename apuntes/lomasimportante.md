HTML
HTML es el acr nimo de HyperText Markup Language o lenguaje de marcado de hipertexto.
Es uno de los lenguajes, el b sico y principal, que se utiliza en la Web. Es un lenguaje
estructurado de marcas expresado en los signos <>. Dentro de las marcas se sit an los
elementos HTML como por ejemplo p de p rrafo o h1 de header 1, algo as  como el t tulo o
encabezamiento principal. Conviene no confundir marcas con elementos.
HTML es un lenguaje inform tico pero no es un lenguaje de programaci n. En un
navegador (me refiero a Firefox, Chrome o derivados) si pulsamos el atajo de teclado C-u
(Control + u) accedemos al c digo fuente de la p gina. Si pruebas a hacerlo, lo que sale
entre las marcas son comentarios de HTML, es decir, contenido que aunque est  en el
codigo fuente, en el HTML, no se visualiza. Esto es habitual en todos los lenguajes
inform ticos, unos caracteres reservados para que el navegador/visualizador del HTML, no
interprete el contenido que est  a continuaci n.
●  Qu  lenguajes inform ticos conoces? Razona la respuesta.
Los lenguajes inform ticos son todos los que entiende o puede entender el ordenador (a
trav s de software, claro). Dentro de los lenguajes inform ticos est n los lenguajes
estructurados, como puede ser HTML, que sirve para estructurar documentos. Y tambi n
est n los lenguajes de programaci n que sirven para programar acciones que haga el
ordenador. Entre estos se encuentran Java, C, C#, Python o R. En la web se utiliza mucho
JavaScript, es el que aporta la interactividad. Tampoco lo vamos a abordar pero algo
veremos. . .  al menos saber que existe y qu  es lo que hace!
Java: Lenguaje principal para la programaci n de aplicaciones Android y una base
fundamental para el desarrollo de p ginas Web. Un imprescindible.
JavaScript: Lenguaje fundamental para hacer las p ginas web interactivas o crear
interfaces con algunas de sus conocidas plantillas.
C#: Lenguaje primario para el desarrollo de plataformas y servicios de Microsoft. Adem s, el
popular motor de desarrollo Unity game incorpora C# como uno de sus lenguajes
principales.
Python: El m s vers til de todos los lenguajes inform ticos. Sirve para desarrollar desde
aplicaciones web, interfaces de usuario o an lisis de datos hasta estad sticas.
PHP: Muy  til a la hora de desarrollar aplicaciones web que trabajan con datos. De hecho,
PHP es el motor de la mayor a de webs basadas en an lisis de datos.
Ruby: Lenguaje directo y sencillo pero a la vez inmensamente poderoso. Una elecci n
id nea para desarrollar una primera versi n de una aplicaci n o lanzar una start up.
HTTP
HTTP responde a HyperText Transmission Protocol o protocolo de control de la transmisi n.
Es como funciona la web, un protocolo muy simple pero no por ello limitado, al contrario.
Cuenta con 4 acciones posibles:
1. POST, publicar o crear. Es cuando se crea un documento nuevo.
2. GET, obtener o bajarse. Es lo que hacemos cuando vemos una p gina web, solicitamos
una copia de la web al servidor.
3. DELETE, borrar el documento.
4. PUT, actualiza un documento ya existente.
Esta es una de las APIs m s sencillas y conocidas. API significa Access Programming
Interface o interfaz de programaci n de acceso, es algo as  como los c digos para
comunicarse con una web. HTTP es una API universal pero luego cada recurso puede tener
la suya propia. Por ejemplo, Twitter tiene su propia API y as  ocurre con muchos recursos
que tienen muchos contenidos que ofrecen de maneras diversas. Si record is estas cuatro
acciones que permite HTTP os aseguro que ten is mucho ganado en relaci n con el uso
que vais a hacer de la Web.
Github
Os presento a Github. Aunque lo ha comprado Micro$oft y ha perdido mucho de su glamour
es una buena forma de habituarse a trabajar con un software de control de versiones que
permite la colaboraci n y adem s, Github ofrece algunas posibilidades que hacen que lo
vayamos a utilizar bastante.
Se trata de una de las herramientas m s usadas en periodismo de datos.
Github es la suma de git, el software, y hub, el espacio montado por GitHub..
Github es un espacio donde podemos alojar los repositorios o proyectos git.
Empezamos dando por v lido una analog a: es como un Wordpress donde vamos a poner
nuestros contenidos web.
Se pueden crear repositorios, algo as  como una carpeta de nuestro sistema de ficheros del
ordenador. Ahora tambi n se pueden crear proyectos pero, de momento, creamos un
repositorio. Hay que crear una cuenta :abc: En GitHub y en lo que escribamos no
utilizaremos M$Word sino otros programas libres y/o abiertos y la sintaxis simple Markdown.
Herramientas de visualizaci n.
Seguro que veremos Datawrapper que aunque es un servicio de terceros, es gratuita y est 
basada en D3js que es libre. Hay otras similares como Infogram o Flourish. Hay librer as de
visualizaci n de datos de los lenguajes de programaci n Bash, Python y R que veremos si
exploramos o no. Atlas o taxonom as de visualizaci n de datos.
Markdown
En el mundo de los datos, el tama o importa. La Web funciona con HTML, actualmente la
versi n 5: HTML5 HTML est  muy bien pero Dan Gruber pens  que ten a un inconveniente:
era dif cil de leer el texto de un c digo HTML. Por eso invent  Markdown. Markdown es dos
cosas a la vez:
1. Una sintaxis simple. Ver is que es muy, muy simple.
2. Un "parseador" o conversor de esa sintaxis en HTML
As , en Github escribimos Markdown y Github lo muestra como HTML, pero si vemos el
archivo fuente sigue siendo Markdown. Tiene truco, claro. Si le das a "ver c digo fuente" lo
ves en HTML pero ese HTML no es el que modificas para que se vea un HTML u otro sino
que lo que modificas es Markdown y luego se hace la conversi n de nuevo. Markdown es
tan simple que hay sitios donde no llega. Por eso desde el inicio se permite en Markdown
usar tambi n lenguaje HTML si lo necesitamos.
Tambi n hay versiones de Markdown como Markdown BlackFriday o RMarkdown en R.
Manos a la obra: Github
• Entramos en Github
• Creamos un repositorio nuevo
• Lo llamamos, por ejemplo, "uc3m-periodismo-datos". Es importante en este momento que,
si no lo hac ais hasta ahora, empec is a no usar espacios en blanco para los nombres de
archivo y directorios/carpetas :boom:
• S  que inicializamos el repositorio con un archivo que se llamar  "README.md". El ".md"
significa que tiene sintaxis Markdown.
• Finalizamos el proceso.
• Ahora tenemos un archivo README.md que contiene una sola l nea
"# uc3m-periodismo-datos". Esto es porque Github ha tomado el nombre del repositorio y lo
ha convertido en el t tulo o H1 de HTML en este documento.
Editar
Vamos al l piz, pinchamos y editamos. Escribimos: language=markdown,label= ,caption=
,captionpos=b,numbers=none Periodismo de Datos en UC3M
Notas sobre **Periodismo de Datos** en *UC3M*
Qu  es el periodismo de datos - Periodismo - Visualizaci n - Datos
HTTP Es una APIquetienecuatrotareasposibles : 1.POST2.GET3.DELETE4.PUT
• Veis que en el editor hay una pesta a a la derecha para previsualizar el texto en HTML.
• Si estamos de acuerdo, "guardamos".
• En Github, como es software git lo que hay detr s, no se "guarda" el documento sino que
se hace un "commit", una explicaci n simple o extensa de lo que hemos hecho, por si
tuvi ramos que volver a este punto. Ahora s , "comiteamos"
• Si queremos volver a editar para cambiar algo, repetimos la operaci n.
Crear archivo
• Pinchamos en crear archivo y lo nombramos.
• Importante:
– No usar tildes ni espacios en blanco ni caracteres que no sean ASCII, es decir, tampoco
las e es.
– Si se trata de un archivo markdown tendr  una extensi n "md", como el README, es
decir, por ejemplo, "nuevo-archivo.md"
 Qu  es Cywgin?
Un conjunto amplio de herramientas GNU y de c digo abierto que ofrecen una funcionalidad
similar a una distribuci n Linux en Windows.
• Una librer a DLL (Dynamic Link Library) para Windows que ofrece buena parte de las
funcionalidades de la API de POSIX.
• POSIX (Portable Operating System Interface o interfaz portable del sistema operativo) es
una familia de est ndares especificados por la IEEE Computer Society (Institute of Electrical
and Electronics Engineers) para mantener la compatibilidad entre los sistemas operativos.
URL
• URL o Unified Resource Locator o localizador de recursos uniforme es la direcci n web.
• Como dice Mozilla.org, la URL junto con el hipertexto (expresado en el HTML, aunque de
esto exactamente no hemos hablado todav a) y HTTP son los conceptos claves de la Web.
• Tened en cuenta que la Web es una telara a mundial, uno de los servicios de red de
Internet. Sobre esta web lo que encontramos son "recursos", y a eso elude la URL.
• Cada URL valida apunta a un  nico recurso.
• Los recursos que normalmente conocemos son p ginas web, pero tambi n pueden ser
documentos CSS, imagenes, JS, archivos de datos. . . cualquier archivo disponible en un
servidor web.
• En una URL se pueden identificar 3 partes f cilmente. Veamos este ejemplo del The
Guardian:
1. que indica el protocolo usado, https en el dominio que sea. La separaci n entre
protocolo y dominio se realiza con ://.
2. El dominio www.theguardian.com, es decir, lo que va entre :// y la primera /. El
dominio se lee de derecha a izquierda en orden de importancia. .com es el TLD, Top
Level Domain o dominio de primer nivel. Una entidad lo gestiona y esa u otra que
revende el servicio ha alquilado theguardian.com al medio ingl s. La  ltima
(recordad, de derecha a izquierda) www es un subdominio de theguardian.com. A
efectos de la Web o de funcionamiento, dar a igual que no estuviera pero es tambi n
una forma de honrar al proyecto de Tim Berners Lee WWW, World Wide Web o gran
telara a mundial; y es tambi n una forma de organizar contenidos o cosas que
sirves a trav s de tu dominio.
Por ejemplo, si tienen un servidor de correo, quiz s se llame imap.theguardian.com. Estos
subdominios sirven para identificar por los humanos los servicios.
3. La estructura de carpetas del servidor web, todo lo que hay a la derecha de la barra
inclinada despu s de .com, es decir, /world/2021/sep/14/taliban-governor-of-helmands-message-to-west-come-back-with-money-not-guns.
Cuando digo "estructura de carpetas del servidor web" es porque no tienen por qu 
corresponderse con una estructura de carpetas reales. Probablemente solo lo  ltimo,
el nombre del art culo, se corresponda con una carpeta.
localhost
• Os presento a vuestro ordenador, el localhost.
• localhost es el nombre de dominio de ese recurso, vuestro propio
ordenador.
• Una cosa que vimos con los servidores web y las peticiones http desde el navegador como
cliente fue la arquitectura cliente-servidor. Pero no dijimos que esta opera en todo lo que
hace el ordenador.
• Y para ello, se conoce a si mismo como localhost.
• Si localhost es el dominio, su direcci n IP es 127.0.0.1, que es la
direcci n IP reservada para localhost.
6
• Se puede echar un vistazo al archivo /etc/hosts (en GNU/Linux y Mac, en Windows buscad
hosts en el buscador de Windows) y ver qu  sale:
language=bash,label= ,caption= ,captionpos=b,numbers=none cat /etc/hosts
Tipos de formatos de datos
Aunque no hemos empezado por aqu , lo hago as  para que se entienda mejor por parte de
quien lo lea. En este caso no hablamos de las bases de datos y de SQL sino de los tres
tipos de formatos de datos de ficheros que nos vamos a encontrar habitualmente:
1. *SV o valores separados por cualquier valor.
2. JSON o JavaScript Object Notation, notaci n de objetos JS.
3. XML o eXtensible Markup Language, lenguaje de marcas extensible.
XML
Los ficheros XML no los vamos a ver porque:
• Son m s complicados de leer.
• Por tanto, es m s complicado trabajar con ellos
JSON
• Son los ficheros que mejor funcionan con aplicaciones web.
• Utilizan la sintaxis de JS.
• Permiten m s complejidad que los *SV, por eso son m s complejos de leer.
*SV
• Normalmente ser n llamados con terminaci n csv incluso aunque no utilicen comas para
separar los valores.
• Son los m s sencillos, pero tambi n los menos estandarizados.
• Los valores separados por comas se visualizan como una tabla simple con filas y
columnas.
• La mayor a de los recursos disponibles en los cat logos de Datos Abiertos se encuentran
en formato CSV.
El portal de datos europeo dispone de m s de 120 mil conjuntos de datos en formato CSV,
siendo el formato que m s abunda en este cat logo de Datos Abiertos. Por su parte, el
cat logo nacional datos.gob.es cuenta con casi 14 mil datasets en formato CSV, siendo
igualmente, el formato mayoritario.
Aprender a partir de una tabla de datos
• A partir del listado de la clase aprendemos algunas cosas de las
tablas.
• La tabla es una representaci n visual de un *SV, un archivo de valores separados por
comas.
La tabla la leemos de izquierda a derecha y de arriba a abajo.
• La lectura horizontal se corresponde a las filas y la vertical a las columnas.
• Las filas son las "l neas" del archivo.
• A veces, aunque no siempre, la primera l nea es la cabecera de la tabla e indica qu 
informaci n tiene cada columna.
• La informaci n de la columna est  relacionada con el tipo de datos que tiene la tabla.
• Cada intersecci n de fila y columna es una celda.
• Cada variable es una columna
• datos.gob.es ha [[https://datos.gob.es/sites/default/files/doc/ file/guia_csv_vf.pdf
Tipos de datos
- Num ricos
• Cuando una celda tiene n meros es probable que esos datos sean num ricos.
• Pero no siempre ocurre ya que solo son considerados num ricos si queremos realizar
operaciones matem ticas con ellos.
• En nuestro caso, estos n meros corresponden a un identificador, que en este caso est 
compuesto por n meros.
• Por tanto, en este caso estos n meros no son datos num ricos sino string, "cadena de
caracteres" o literales.
• Algunas aplicaciones reconocen autom ticamente o pueden hacerlo los tipos de datos
para realizar operaciones espec ficas con ellos.
• Esto suele mostrarse visualmente de alguna manera destacada, por ejemplo, poniendo
esos datos en color verde.
Tipos de datos num ricos
integer n meros enteros, sin decimales. Atenci n si tienen el separador de millar porque es
distinto en espa ol (punto) que en ingl s (coma). Algunos programas lo entienden seg n tu
codificaci n del programa pero otras veces hay que indicarlo.
decimal n meros con decimales pero –explicaci n corta– pocos decimales y siempre el
mismo n mero de decimales. Por c mo son tratados, son m s lentos de procesar que los
float.
float or double n meros con decimales pero que pueden tener muchos decimales y/o
variable en su longitud. Por c mo son tratados son m s r pidos de procesar que los decimal
date or datetime la forma m s est ndar suele ser la que sigue el esquema YYYY-MM-DD,
donde Y significa Year, y al ser cuatro tienen que ponerse cuatro cifras; M significa Month, y
al ser dos tienen que ponerse dos cifras; y D significa Day y al ser dos tienen que ponerse
dos cifras. F jese que en este tipo de datos num rico se utiliza un gui n para separar las
unidades temporales, aunque hay veces que se separan con /, no es lo m s habitual. Hay
veces que se incluye tambi n la hora time, a continuaci n de la fecha, o bien separada con
una T de Time o, simplemente, con otro gui n, en la forma HH:MM:SS: 2021-09-21-14:30 o
2021-09-21+14:30. Se suelen poner horas y minutos si no se necesitan los segundos, pero
puede haber segundos e incluso d cimas de segundos: 2021-09-21T14:30:00.5. Tambi n
se puede indicar la zona temporal a adiendo una Z al final que indica que se est  en horario
UTC (Universal Time Coordinated. . . en realidad no est  en ingl s exactamente). Madrid
est  en UTC+2 en horario de verano y UTC+1 en horario de invierno por lo que, la fecha
anterior se escribir a en Canarias as : 2021-09-21T14:30:00.5Z pero en Madrid ser a
=2021-09-21T14:30:00.5+2=. El mapa con los husos horarios lo ten is en la Wikipedia. El
tema de las fechas se ha especificado tanto quiz s porque ha generado unos cuantos
problemas inform ticos. V ase, por ejemplo, el problema del a o 2000 que fue bastante
comentado: CCFN TV, NatGeo, The Science Elf. Pero,  puede volver a pasar?  S ! Ya
tenemos el Year 2038 Problem por el registro de hora en 32 bits. La soluci n pasa por
hacerla en 64 bits. Ver formatos de fecha y hora
period Algunas veces (duration data type de XML Schema) se utiliza tambi n el tipo de dato
de tiempo peri dico que obedece al periodo de la muestra del dato, por ejemplo:
• P al inicio indica que se trata de un dato peri dico.
• nY indica el n mero de a os.
• nM indica el n mero de meses.
• nD indica el n mero de d as.
• T indica el comienzo de horas, minutos o segundos, seg n vaya
nH, nM o nS
• En este tipo de dato se pueden dar valores negativos para indicar mediciones
aproximadas. Por ejemplo, si es -P10D indica
un periodo menor a diez d as.
Strings
• Se denomina strings, cadena de caracteres o literales al texto normal.
Booleanos
• Representan dos valores de una l gica binaria.
• "Verdadero o Falso", "True or False", "S  o No", "0 o 1", etc.
• El nombre se debe a George Boole, "desarroll  un sistema de reglas que le permit an
expresar, manipular y simplificar problemas l gicos y filos ficos cuyos argumentos admiten
dos estados (verdadero o falso) por procedimientos matem ticos."
Nombres de archivos y carpetas
• Recordamos que en Github si creamos un archivo hemos de incluir la extensi n md para
que lo trate como un texto markdown y por tanto lo procese correctamente.
• En Github los nombres del primer archivo se llaman README.md para que lo leas
( l eme!) y de alguna forma como homenaje a los archivos del software que se le a en
pantallas en blanco y negro donde se prefer a las may sculas para la mejor lectura.
• En vuestro caso yo optar a por nombrar tanto los archivos como las carpetas en
min sculas y separando las palabras con guiones medios, es decir: esta-es-una-carpeta y
esto-es-un-archivo.md.
• Hay otras formas posibles pero es importante que se is met dicos para que siempre lo
hagamos as  y sepamos por tanto acceder y recuperar nuestros archivos y carpetas.
Windows
- Cygwin
• Se puede descargar en https://www.cygwin.com/
• Emulador de la terminal POSIX en Windows
• Ofrece un conjunto de herramientas y programas que emulan una distribuci n Linux en
Windows.
• Tiene desventajas conocidas: instalaci n, actualizaci n, usabilidad de la instalaci n. . .
•  Atenci n! Una vez que lo descarg is y lo instal is, no tir is el instalador ya que es
necesario para su actualizaci n.
• La primera vez que lo usamos descargamos lynx, un navegador en l nea de comandos.
• Para no tener que correr manualmente el instalador cada vez que queremos actualizar
Cygwin con alg n paquete/programa, usaremos apt-cyg
apt-cyg
• Cygwin es una herramienta muy potente para Windows pero muy tediosa de utilizar.
• apt-cyg es un gestor de paquetes de Cygwin que funciona en l nea de comandos.
• El nombre proviene de ser como un apt para Cygwin.
• Un APT (Advanced Package Tool) es un conjunto de herramientas para manejar los
paquetes –programas– de los sistemas Debian GNU/Linux. Se ha hecho muy popular su
funcionamiento y otros sistemas operativos lo han imitado porque permite:
• Instalar programas.
• Desinstalar programas.
• Actualizar programas.
• Resolver dependencias de los programas de forma autom tica.
• Sin apt-cyg, cada vez que queremos instalar algo hay que abrir el programa de instalaci n
de Cygwin.
• Con apt-cyg conseguimos instalar o actualizar programas que usamos en Cygwin desde la
propia consola de Cygwin
Instalaci n de apt-cyg
Para instalarlo, tal como cuentan en su p gina web, usamos dos l neas de
comandos:
lynx -source rawgit.com/transcode-open/apt-cyg/master/apt-cyg > apt-cyg install apt-cyg /bin
La primera l nea dice que ejecutar  lynx con la opci n -source para descargar el c digo
fuente de la p gina rawgit.com/transcode-open/apt-cyg/master/apt-cyg y ese texto lo env a
con > al archivo apt-cyg.
Lynx es un navegador en l nea de comandos que se puede utilizar para esto.
En este momento y en el directorio/carpeta/ruta donde estemos, creamos un archivo con
nombre apt-cyg que contiene el texto del c digo fuente de esa URL, que es un script para
usar Cygwin e instalar programas sin correr manualmente el instalador.
Para comprobar que est  hacemos un ls, un comando para listar los contenidos de la
carpeta/directorio.
Si est , pasamos a la siguiente l nea. Con install instalamos el archivo apt-cyg, que es un
programa, en la carpeta bin, que son los programas o binarios. Si no ha dado error ser  que
lo tenemos. Para probarlo escribimos apt-cyg install wget, que es la instrucci n para instalar
el programa wget, una herramienta para descargar archivos que usa precisamente apt-cyg.
BASH
• El lenguaje de la terminal se denomina bash. Es un lenguaje de programaci n en s  pero
tambi n un entorno sobre el que trabajamos incluso sin programar.
• Bash es uno de los lenguajes posibles de la Shell, que es como se denominar a a la
terminal. Es el m s popular. Sin embargo, hay otros tambi n muy extendidos como zsh.
• Pod is ver las que ten is disponibles con cat /etc/shell
• No os dir a esto si no fuera porque de un tiempo a esta parte MacOSX ha decidido usar
zsh y eso produce algunos "problemas" curiosos. B sicamente, lo que ocurre es que
aunque hemos instalado brew siguiendo las instrucciones, no parece existir.  Por qu ?
Porque no sabe d nde est  brew o m s bien, no se lo hemos dicho.
• En el caso de Mac podemos hacer dos cosas: o seguir usando zsh, y entonces
configurarlo bien para que sepa d nde este brew; o cambiar a bash.
• Por cierto, esto es algo que nos lleva a explicar lo que son "las variables de entorno" y lo
que son las variables.
Variables
Una de las cosas que tienen los lenguajes de programaci n son las variables, sirven para
definir los datos. Por ejemplo, x = 3 lo que dice es que la variable x tiene el valor de 3. En el
uso de los programas es similar y se llaman "de entorno" porque configuran la relaci n del
programa con su entorno.
- Variables de entorno
• Podemos ver las variables que tiene Bash escribiendo env. Vaya, salen muchas cosas en
la pantalla y no podemos leerlas todas, ser a mejor "paginar" el resultado con less. Tanto
less como more son paginadores de texto, visores.
• Antes hemos visto c mo enviar la salida de un comando a un archivo con el operador >.
• Ahora vamos a ver c mo enviar la salida de un comando a otro comando. Es decir,
queremos que el resultado de env lo utilice el paginador less como datos de entrada: env |
less. El operador es la barra vertical | que se escribe con Alt Gr + 1.
Tambi n podemos ver las variables, si sabemos su nombre, con echo. En este caso me
interesa saber el valor de la variable PATH, as  que echo $PATH, donde el s mbolo del d lar
indica que se trata de una variable.
Cambiar la home en Cygwin
• Queremos cambiar la home de Cygwin.
• Este es un juego divertido que la gente de Mac o GNU/Linux no necesita hacer, en
principio.
• Recordemos que cuando digo home me refiero al directorio del sistema de archivos donde
se encuentran mis archivos personales, es decir, lo que en un Windows o Mac es mi
espacio del ordenador y a partir de ah  cuelgan las carpetas de Escritorio, Descargas, etc.
• Por defecto, la home del usuarix de Cygwin es el directorio de instalaci n del programa
que monta una estructura Unix con ruta /home/nombre-usuarix/. Esto lo vemos cuando
arrancamos el programa y escribimos (le preguntamos) pwd (imprime el directorio de
trabajo) y devuelve una ruta que es esa.
• Para ver el  rbol de directorios de Cygwin o Mac o Linux, pod is hacer tree -L 1 /. El
comando tree muestra el  rbol de directorios y archivos. Con la opci n -L 1 (L de level o
nivel) muestra un nivel del  rbol desde el punto (el argumento /) que le hemos dicho, en
este caso la ra z, principio o n cleo del  rbol de directorio representado por una / barra.
• Cygwin instala, por defecto, el espacio de usuario en una parte del propio programa, en
/home/. Lo que queremos hacer es que tenga como home el espacio de mi usuario de
Windows.
• Para disfrutar de Cygwin y acceder al espacio de quien usa el ordenador de Windows, una
opci n es modificar la variable db_home en /etc/nsswitch.conf con nuestro editor nano.
• Pero antes. . .
- Antes de cambiar la home
En la home de Unix se crean unos archivos por defecto:
• .bashrc, donde se encuentra la configuraci n de BASH.
• .bash_profile, donde se encuentra la informaci n del perfil de lxs usuarixs de BASH.
• .bash_history, donde se almacenan los comandos que utilizamos.
Tanto si estos archivos contienen informaci n  til como si no, antes de cambiar la home,
c pialos al directorio que va a ser el nuevo directorio de trabajo, es decir:
cp .bash* /cygdrive/c/Documents and Settings/usuarix/.
Listar archivos, opciones
ls listamos archivos y directorios
ls -a listamos archivos y directorios ocultos
ls -la listamos archivos y directorios ocultos con detalle.
Copiar archivos y/o directorios
• Para copiar est  el comando cp
• Su comportamiento es cp OPCIONES ruta/s-origen ruta-destino. Es decir, admite copia
una cosa o varias a un destino final.
• Tened en cuenta siempre eso que os dec a que cuando ponemos el nombre de los
archivos o las carpetas en realidad estamos poniendo su ruta en el sistema de ficheros.
Si copiamos un directorio y tiene contenido hemos de poner la opci n -r que significa "copia
recursiva".
Mover archivos y/o directorios
• Para mover archivos, es decir, cortar y pegar algo en un destino determinado, est  el
comando mv.
• Su comportamiento es mv OPCIONES ruta/s-origen ruta-destino. Admite, tambi n, mover
una o varias cosas a un destino final.
• Se puede usar tambi n para renombrar archivos o carpetas. Es decir, si hacemos mv
hola.txt adios.txt lo que hacemos es mover el archivo hola.txt al archivo adios.txt, es decir,
borrar hola.txt y crea adios.txt; y si existiera, lo sobreescribe.
Wildcards o comodines
• A la hora de listar, copiar, mover y otras operaciones se pueden usar las wildcards o
comodines.
• Imaginad que ten is una carpeta en vuestro Escritorio de nombre data y dentro de ella
ten is archivos csv, json y xls, todos en la misma carpeta. Y quer is organizar eso un poco
por tipo de archivo.
• Entonces creamos unas carpetas que se llamar n csv, json y xls dentro de data.
• Nos situamos en el directorio data con el comando cd: cd ~/Escritorio/data
• Creamos las carpetas con mkdir: mkdir csv json xls.
• Movemos los archivos con mv: mv *.json json/, y luego con los otros dos tipos de archivos.
Data Journalism is the New Punk
• As  defini  Simon Rogers al periodismo de datos en el TEDxPanth onSorbonne en
noviembre de 2012 https://www.youtube.com/watch?v=h2zbvmXskSE
• Define el punk como algo muy importante para la juventud porque les permit a formar una
banda solo con tener una guitarra y con tres acordes se pod a hacer una canci n.
• Lo que fue importante para la juventud de los 1970’ puede representar ahora los datos:
tienes tres conjuntos de datos y ya puedes hacer una historia interesante.
• Rogers quer a escribir y ser periodista cuando ten a 6 a os. Pero ten a miedo a las
matem ticas. Sin embargo en el periodismo de datos necesitas tener conocimientos
matem ticos, t cnicos.
• Hay portales de datos abiertos, proyectos de liberaci n de datos, filtraciones como
Wikileaks. . .
• Tambi n herramientas libres o abiertas como Datawrapper para crear visualizaciones.
• Con UK Riots se volvi  a revisar el inicio del periodismo de precisi n de Philip Meyer y sus
Detroit Riots.
• Open Journalism
• Joe Strummer: "people can do anything".
Git y Github
- El repositorio de pontedatos
• Ya tenemos un repositorio en la organizaci n a la que pertenecemos como clase,
https://github.com/pontedatos/uc3m-periodismo-datos
• Lo que vamos a hacer es o bien descargarlo si no lo hemos hecho o bien actualizarlo si ya
lo hab amos descargado.
• Cuando digo "descargarlo" en realidad digo "clonarlo", es decir, voy a la carpeta de mi
elecci n con el comando cd y escribo git clone
https://github.com/pontedatos/uc3m-periodismo-datos.git.
• Esto crear  una carpeta por debajo de donde me encuentro con el nombre
uc3m-periodismo-datos. Esa carpeta es un repositorio git en nuestro ordenador, en
localhost, que tiene el mismo contenido que el de la direcci n desde donde me lo he
clonado.
• Si ya hubiera hecho esto alguna vez tendr a que ponerme dentro de la carpeta y actualizar
con git pull.
- Nuestro repositorio
• Es probable que teng is un repositorio vuestro cuyos contenidos solo est n en github.
• Vamos a descargarnos los datos de la misma manera que antes.
• Nos situamos en la carpeta elegida y clonamos con git clone seguido de la direcci n de
nuestro repositorio git en github.
• Luego con cd nos situamos dentro del repositorio.
• Ahora con nano o nuestro editor favorito cambiamos algo, guardamos,
cerramos y seguimos tres pasos para actualizar los cambios en github:
– git add nombre-archivo-cambiado
– git commit -m "comentario del cambio"
– git push main origin
- No tenemos un repositorio
• Si no tuvi ramos un repositorio podr amos crear uno nuevo.
• Primero creamos una carpeta con el nombre que queramos aunque lo suyo es que sea el
nombre del repositorio.
• Luego con cd nos situamos dentro de la carpeta.
• Y entonces creamos un repositorio en Github y, cuando llegue el caso, seguimos en la
terminal estos pasos que indican:
echo "# Proyecto de ..." >> README.md
git init
git add README.md
git commit -m "primer commit"
git remote add origin https://github.com/cuenta/nombre-repositorio
git push -u origin main
:new: Tokens
• Para anticipar el pr ximo "desaf o" con que os vais a encontrar os cuento que Github
cambi  hace poco la forma de relacionarse con Github y ahora hay que generar una clave
para subir los contenidos, para hacer el git push.
• Antes hab a que poner la contrase a de github, ahora hay que generar una clave.
• Esto se hace yendo a https://github.com/settings/tokens y generando un nuevo token.
• Hay que darle un nombre, elegir una fecha de caducidad (puede ser "nunca" aunque, ya
que est is aprendiendo, mejor ponerle una caducidad para que teng is que volver a ese
paso en alg n momento) y seleccionar un  mbito de actuaci n o "scopes".
• Para lo que vamos a hacer basta con que marqu is "repo" y los que cuelgan de  l:
– repo
– repo:status
– repo_deployment
– public_repo
– repo:invite
– security_events
• Una vez marcado esto y creado el token os genera un "hash", un c digo que conviene que
copi is en alguna parte –:warning: cuidado: no en los apuntes p blicos– y que ser  el que
teng is que poner cuando hag is git push en vez de la contrase a.
OpenRefine
• Naci  como un proyecto de Google de software libre, Google Refine.
• Cuando Google decidi  dejarlo, la comunidad de usuarixs y desarrolladorxs hicieron un
"fork" del proyecto y comenz  Open Refine, que es la evoluci n "natural" de Google Refine.
• Por eso hay quien se refiere a el software como Google Refine, Open Refine o,
directamente, Refine.
- Funciones
• Sirve para limpiar y analizar datos.
• Hay que tener en cuenta que la visualizaci n de datos tambi n se refiere a esta etapa en
la que el an lisis de ciertas cantidades de datos se va a apoyar en herramientas visuales
que favorecer n ese an lisis.
• Se le considera la "navaja suiza" del periodismo de datos por todo lo que se puede hacer
"limpiando datos".
- Primeros pasos:
1. Cargar archivos
2. Editar columnas
3. Transformaciones comunes
4. Ordenar columnas
5. Facetas (num ricas, temporales y de texto)
6. Borrar filas
7. Exportar proyecto
C mo utilizar el conteo de las facetas value.facetCount("value","Column 3")
Crear una columna con los valores de otra columna
value = value.strip().lower()
if "trump" in value:
return "Donald Trump"
C mo sumar todos los valores de un registro row.record.cells["FelipeVI"].value.sum()
Pandoc
● Pero tenemos todo el manual con man pandoc. Quien no tenga este comando disponible
debe instalarse el paquete man-db. En el caso de Cygwin, apt-cyg install man-db
● Pandoc Se descarga de pandoc.org
● Una vez instalado, se puede usar desde la terminal. Ten en cuenta que si tienes la
terminal abierta mientras lo instalas no se actualizar n las rutas de la variable PATH por lo
que conviene cerrar la terminal y volver a abrirla.
● Recuerda que para ver la variable PATH puedes hacer echo $PATH.
● Y si no te lo ha incluido, puedes a adir la ruta a la variable con export
PATH=$PATH:/ruta/absoluta/a/directorio/binario/pandoc/. Esto funcionar  para la sesi n. Si
quieres que sea un cambio permanente debes a adirlo a .bashrc o .zshrc seg n tu shell.
● Puedes comprobar qu  shell tienes con echo $SHELL.
● Comprueba que tienes pandoc con pandoc --version.
Plantilla HTML: Bootstrap
Aunque ya se hab a presentado en clase se hace una demostraci n de c mo se debe
operar con esta plantilla para construir la web del trabajo final.
Seg n la Wikipedia, Bootstrap es Bootstrap "biblioteca multiplataforma o conjunto de
herramientas de c digo abierto para dise o de sitios y aplicaciones web".
De todos los ejemplos que ofrece Bootstrap, vamos a utilizar Sticky Footer Navbar que es
un tema muy sencillo que consiste en una cabecera con un men , un espacio central donde
situar el contenido y un pie donde situar otro contenido.
