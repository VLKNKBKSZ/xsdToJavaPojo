# xsdToJavaPojo
Sample project for creating a java pojo from a xsd [xml file should be converted to a xsd]

Steps :
1-You can use this website for creating a xsd from a plain xml ,
 https://www.freeformatter.com/xsd-generator.html
 
2- Create a xsd in a maven resources folder.

3- add the jaxb api as a dependency.

4- add jaxb2-maven-plugin as a build plugin and configure settings.

5- specify in which package/folder you want the pojo's to be generated.

6- mvn clean install.

The generated pojo's will contain the xml annatotions, for this u need the jaxb api otherwise,
the annotations will not be generated.
Now you can add a xml messageConverter in you'r restTemplate so, the mapping to a pojo will be
easy as breathing :P

