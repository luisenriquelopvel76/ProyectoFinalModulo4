# PROYECTO FINAL MODULO 4

## Luis Enrique Lopez Velazquez

### Proyecto relacionado: SQL, JDBC e Hibernate con containers Docker

#### Instrucciones

<ol>
<li>Levantar contenedores en Docker</li>

##### Si los contenedores no existen, usar los siguientes comandos:
 - Para MySQL:
   **docker run --name mysql -d -p 3306:3306 -e MYSQL_ROOT_PASSWORD=root --restart unless-stopped -v mysql:/var/lib/mysql mysql:8**

- Para Redis:
  **docker run -d --name redis-stack -p 6379:6379 -p 8001:8001 redis/redis-stack:latest**

##### Si los contenedores ya existen, usar los siguientes comandos:
- Para MySQL: 
 **docker restart mysql** 

- Para Redis:
 **docker restart redis-stack**<br>
#### 
<li>Crear una conexion a la base de datos en IntelliJ con la fuente de datos MySQL, usando usuario "root" y password "root"</li><br>


<li>Ejecutar comando en IntelliJ: <em><strong>mvn clean install</strong></em></li><br>

<li>Ejecutar el metodo <em><strong>main</strong></em> en la clase <em><strong>Principal</strong></em> </li>
</ol>

## FIN