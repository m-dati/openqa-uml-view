# UML diagrams for openQA test code #

This project is intended to provide a graphical representation of openQA SUSE test code using a metalanguage for UML diagrams generation, for planning and debugging purposes.

The openqa reference code is in <https://github.com/os-autoinst/os-autoinst-distri-opensuse>

In particular, the initial demo of the UML coding is a reverse engineering of some test routines for Public Cloud, of the Perl module <https://github.com/os-autoinst/os-autoinst-distri-opensuse/blob/master/lib/main_publiccloud.pm>

The *UML diagrams* are used to represent a graphical view of a project, helping to write the code, add changes and even improve the logic of the code or identify bugs.

Here we refer to the https://plantuml.com tool documentation.

- Many **web editor** are available to represent the resulting images, like <https://plantuml.com/plantuml> or <https://www.planttext.com/>

- But also an **offline** version of the UML interpreter is available, using a jar file, available from <https://plantuml.com/download> and used as explained in <https://plantuml.com/faq-install>  and <https://plantuml.com/command-line>

- Finally, a *Visual Studio Code* **plugin** is also available to render the UML code and generate the diagrams. 
To install it: Launch VS Code Quick Open (Ctrl+P), paste the following command, and press enter: <br>
`ext install plantuml` <br>
then click `Alt+D` for the _preview_.

