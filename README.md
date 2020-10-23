# Jenkins-Test
Jenkins-Pipeline
## Integración Continua – JENKINS<br/>
  Primero verificamos que tenemos instalado el jdk de java en el path:
  <pre><code>java -version </code></pre>
  ![texto cualquiera por si no carga la imagen](https://github.com/JoseCcari/Test_Gradle/blob/main/JAVA-VERSION.PNG)
  Descargamos Jenkins.war de la página oficial y corremos en nuestra consola dentro del directorio del archivo:
  <pre><code>java -jar jenkins.war --httpPort=8080 </code></pre>
  ![texto cualquiera por si no carga la imagen](https://github.com/JoseCcari/Jenkins-Test/blob/main/runjenkins.PNG)  
  Una vez verificado que está corriendo bien entramos al localhost:8080 y configuramos nuestro jenkis , para probar cargamos un pipeline de un simple hola mundo 
  <pre><code>gradle -q help --task init </code></pre>
   ![texto cualquiera por si no carga la imagen](https://github.com/JoseCcari/Jenkins-Test/blob/main/hola_mundo.PNG) 
   Ahora uno en java:
   ![texto cualquiera por si no carga la imagen](https://github.com/JoseCcari/Jenkins-Test/blob/main/Pipeline-Java.PNG)   
  Como vemos es muy simple hacerlo ;)
