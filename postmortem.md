# Post Mortem

馃挕 En este documento se detalla una retrospectiva de lo que fue el desarrollo de Spotifiuby en los 煤ltimos meses.


## A Gian no le gust贸 React Native

Empezar una nueva app usando React Native es super sencillo y para toda la familia, te miras un par de tutoriales y sale al toque, eso es hasta que queres empezar a meterle cosas un poco mas complejas, algo tan sencillo como un selector multiple que en React web haces en 2 clicks, llevo a utilizar una libreria de algun buen samaritano de internet que ya ni tiene support.

Al principio parece hermosa la idea de desarrollar con un 煤nico c贸digo (y un poquito de configuraci贸n) para varias plataformas, pero en seguida te das cuenta que IOS es horrible y que mejor desarrollo solo en android.

Expo es hermoso, te permite facilmente deployar tu app a una apk, pero ni se te ocurra que llegue un bug a producci贸n que no ocurre en tu ambiente local, porque vas a tener que gastar 2 horas de tu vida trantando de resolverlo, y de esas 2 horas, 1 y media es esperar a que deployee la apk.

La pr贸xima que tenga que hacer una app mobile, intentar茅 ver que onda Kotlin, o mejor, hacer directo una web en React apta para mobile y empaquetarla a una apk.