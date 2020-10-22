# Jenkins-Test
Jenkins-Pipeline
## Integración Continua – JENKINS<br/>
  Primero verificamos que tenemos instalado el jdk de java en el path:
  <pre><code>java -version </code></pre>
  ![texto cualquiera por si no carga la imagen](https://github.com/JoseCcari/Test_Gradle/blob/main/JAVA-VERSION.PNG)
  Descargamos Jenkins.war de la página oficial y corremos en nuestra consola dentro del directorio del archivo:
  <pre><code>java -jar jenkins.war --httpPort=8080 </code></pre>
  ![texto cualquiera por si no carga la imagen](https://github.com/JoseCcari/Test_Gradle/blob/main/GRADLE.PNG)  
  Una vez verificado que está corriendo bien entramos al localhost:8080 
  <pre><code>gradle -q help --task init </code></pre>
  ## Una visión general de lo que nos construyó la tarea init con el type basic.
Nos creó dos archivos en la raíz del proyecto con los nombres build.gradle y settings.gradle. Estos archivos son utilizados por Gradle para la configuración de construcción del proyecto.
