<project xmlns="http://maven.apache.org/POM/4.0.0" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xsi:schemaLocation="http://maven.apache.org/POM/4.0.0 https://maven.apache.org/xsd/maven-4.0.0.xsd">
  <modelVersion>4.0.0</modelVersion>

<groupId>MavenProject</groupId>
  <artifactId>MavenProject</artifactId>
  <version>0.0.1_SNAPSHOT</version>
 
  <dependencies>
 
<dependency>
    <groupId>org.seleniumhq.selenium</groupId>
    <artifactId>selenium-java</artifactId>
    <version>3.141.59</version>
</dependency>

 
<dependency>
    <groupId>org.testng</groupId>
    <artifactId>testng</artifactId>
    <version>6.14.3</version>
    <scope>test</scope>
</dependency>

 
<dependency>
    <groupId>org.apache.poi</groupId>
    <artifactId>poi</artifactId>
    <version>3.17</version>
</dependency>

   
<dependency>
    <groupId>commons-io</groupId>
    <artifactId>commons-io</artifactId>
    <version>2.4</version>
</dependency>

    </dependencies>
    <build>
 <plugins>
 <plugin>
 <groupId>Org.apache.maven.plugins</groupId>
 <artifactId>maven-SureFire-plugin</artifactId>
 <version>2.21.0</version>
 <configuration>
 <SuitexmlFiles>
 <SuitexmlFile>testng.xml</SuitexmlFile>
 </SuitexmlFiles>
 </configuration>
 </plugin>
 </plugins>
 </build>
 
  
