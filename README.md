JavaCodeGenerator
=================
UML to Java code. 
A Java code generator template for StarUML


Precondition
------------
1. Install StarUML from https://sourceforge.net/project/showfiles.php?group_id=152825&package_id=169190&release_id=437438


Installation
------------
1. Download the template files includes folder
2. Copy the downloaded files and folder into "StarUML_install_directory\modules\staruml-generator\templates"


Usage
-----
1. Design your software by class diagram. Example: <br>![guide uml](docs/guide_uml1.png)![guide uml](docs/guide_uml2.png)![guide uml](docs/guide_uml3.png)
2. Open menu "Tools->StarUML Generator ..."<br>![guide menu](docs/guide_menu1.png)
3. Select "Java code generator" and configure it by "Opt." button if you want to customize it<br>![guide config](docs/guide_config1.png)<br>![guide config](docs/guide_config2.png)
4. Click the "Next" button and select the directory that you want to store the generated code<br>![guide config](docs/guide_config3.png)
5. Click the "Next" button and press the "Generate" button at the following step<br>![guide config](docs/guide_config4.png)
6. Click the "Finish" button to finish the code generation<br>![guide config](docs/guide_config5.png)
7. Check the generated code in Eclipse<br>![guide sample code](docs/guide_sample_code1.png)<br>![guide sample code](docs/guide_sample_code2.png)


Feature
-------
* Generate the Java code according to the class define in class diagram
* Generate the Java code according to the interface define in class diagram
* Generalization and interface support for class and interface 
* Generate the folder structure according to the package structure in class diagram
* Embed the method implementation code into the document of method with configurable mark line
* Generate the code comment that follow the Javdoc define
