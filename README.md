## 0. References
<ul>
  <li><a href="https://www.geeksforgeeks.org/difference-between-web-server-and-application-server/">Difference Between Web server and Application server</a></li>
  <li><a href="https://knowm.org/set-tomcats-default-locale/">Set Tomcat’s Default Locale</a></li>
  <li><a href="https://www.baeldung.com/tomcat-utf-8">Making Tomcat UTF-8-Ready</a></li>
</
</ul> 


## 1. Overview


## 2. Tomcat Manager Application
<ul>
  <li><a href="https://tomcat.apache.org/tomcat-9.0-doc/manager-howto.html">Manager App How-To - Apache Tomcat 9 (9.0.31)</a></li>
</ul>

<h4>Configure App Manager and Roles: tomcat-users.xml</h4>
<kbd>
  <img src="https://github.com/Blackdog-Programmer/ApacheTomcat-Bootstrap/blob/master/reference/application_manager/manaer_gui_configuration.png" alt="make and configure tomcat manage user and role">
</kbd>

<kbd>
  <img src="https://github.com/Blackdog-Programmer/ApacheTomcat-Bootstrap/blob/master/reference/application_manager/app_manager.png" alt="Tomcat App Manager Section">
</kbd>


## 3. Configuration files and binaries walk through
<h4>Configuration Files: Tomcat 9.0\conf</h4>
<kbd>
  <img src="https://github.com/Blackdog-Programmer/ApacheTomcat-Bootstrap/blob/master/reference/configuration_files_and_binaries/configuration_files.png" alt="configuration files tomcat">
</kbd>

<h4>Library Files: Tomcat 9.0\lib</h4>
<kbd>
  <img src="https://github.com/Blackdog-Programmer/ApacheTomcat-Bootstrap/blob/master/reference/configuration_files_and_binaries/library_files.png" alt="library files">
</kbd>


## 4. Security
<ul>
  <li><a href="https://tomcat.apache.org/tomcat-9.0-doc/security-howto.html">Security Considerations - Apache Tomcat 9</a></li>
</ul>

### 4-1. Enabling SSL
<ul>
  <li><a href="https://www.digicert.com/ssl/">What is SSL(Secure Socket Layer)</a></li>
</ul>

<h4>SSL Key Geneartion: keytool.exe(JDK)</h4>
<kbd>
  <img src="https://github.com/Blackdog-Programmer/ApacheTomcat-Bootstrap/blob/master/reference/SSL/ssl_key_generation_jdk_keytool.png" alt="SSL Key Generation">
</kbd>

<h4>Enabling SSL: server.xml</h4>
<kbd>
  <img src="https://github.com/Blackdog-Programmer/ApacheTomcat-Bootstrap/blob/master/reference/SSL/enable_ssl_configuration.png" alt="enabling SSL">
</kbd>

<h4>Make Confidential on Tomcat App Manager: web.xml</h4>
<kbd>
  <img src="https://github.com/Blackdog-Programmer/ApacheTomcat-Bootstrap/blob/master/reference/SSL/make_confidental_protect_app_manager.png" alt="make_confidental_to_protect_app_manager">
</kbd>
  
  
## 5. Virtual Host
<ul>
  <li><a href="https://tomcat.apache.org/tomcat-9.0-doc/virtual-hosting-howto.html">Virtual Hosting and Tomcat</a></li>
</ul>

<kbd>
  <img src="https://github.com/Blackdog-Programmer/ApacheTomcat-Bootstrap/blob/master/reference/virtual_host/virtual_host_benefits.png" alt="Benefits of VirtualHost">
</kbd>

<h4>Add Virtual Host Websites: server.xml</hr>
  <kbd>
    <img src="https://github.com/Blackdog-Programmer/ApacheTomcat-Bootstrap/blob/master/reference/virtual_host/add_virtual_host.png" alt="add virtual host website in server.xml files">
  </kbd>

<h4>Virtual Host Redirection: host file(C:\Windows\System32\drivers\etc)</hr>
  <kbd>
    <img src="https://github.com/Blackdog-Programmer/ApacheTomcat-Bootstrap/blob/master/reference/virtual_host/add_virtualhost_in_host_file.png" alt="host file configuation">
  </kbd>

## 6. Clustering
<ul>
  <li><a href="https://tomcat.apache.org/tomcat-9.0-doc/config/cluster.html">Cluster - Apache Tomcat - Apache Software</a></li>
  <li><a href="https://svrtechnologies.com/what-is-horizontal-and-vertical-clustering/">Horizontal vs Vertical Clustering</a></li>
</ul>

<h4>Horizontal Clustring Infographic</h4>
<kbd>
  <img src="https://github.com/Blackdog-Programmer/ApacheTomcat-Bootstrap/blob/master/reference/Clustering/horizontal_cluster.png" alt="Horizontal Clustering Image">
</kbd>

<h4>Verticsl Clustering Infographic</h4>
<kbd>
  <img src="https://github.com/Blackdog-Programmer/ApacheTomcat-Bootstrap/blob/master/reference/Clustering/verticla_cluster.png" alt="Vertical Clustering Image">
</kbd>
