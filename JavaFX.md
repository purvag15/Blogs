
<!-- Copy and paste the converted output. -->


You all might have heard about JavaFX while developing desktop applications using Java AWT or Java Swing or you might be fairly confused on what tech stack to choose for developing a cool project. Well, one of the emerging software platforms these days is JavaFX. But,

## What is JavaFX?

Let’s dive deeper into the development world and gain insights on JavaFX!

So, JavaFX is a software platform for creating desktop applications and some more RIA[^1]s.

It contains graphics and media packages that help developers to design an application of their own choice across diverse platforms[^2] and provides a hardware-accelerated[^3] and lightweight[^4] Java UI platform for business applications.

It is a Java API which has classes and interfaces written in native Java code.

## Why JavaFX?
Let’s first quickly sum up its key features.

*   **Web view** - WebKitHTML technology allows embedding pages within a JavaFX application.
*   **Rich UI control**
*   **Canvas API** - Allows direct drawing within the area of JavaFX scene.
*   **2D and 3D graphics** support - JavaFX offers smooth graphics that render quickly when used with a supported graphics card or GPU.
*   Styling just like **CSS**
*   **FXML**[^5]** and Scene Builders** - Are you more of a fan of pick-and-drop components rather than coding and replicating the code snippet multiple times for GUI[^6]? JavaFX’s Scene builders come to your rescue! Coders, don’t be disappointed, you have an FXML file for hard coding your features as per your convenience.

    (Note that FXML file can be easily handled even by those who aren’t much aware of programming languages but have some knowledge of HTML)



*   **Swing interoperability** - Existing applications based on Java Swing can be updated with new JavaFX features.

Now, these were some theoretical aspects of JavaFX. Get ready to get your hands dirty with JavaFX in development!

## Beginner’s Guide

Let’s learn some basic steps for a beginner to make a project on JavaFX.



1. Install any IDE[^7] supporting JavaFX. (Netbeans or Intellij preferred for beginners)


2. Also install an external scene-builder[^8] for editing the GUI of your JavaFX application.


3. Install MySQL for the database of your project. Also install a ‘mysql-connector-java’.
4. Now, set the path of the external scene-builder and the mysql-connector-java in your respective IDE.

    (For Intellij Users, go to Files -> Project Structure -> Libraries to set path.)


    You can easily find any tutorial on the internet for the same.

5. Now, you are all set for developing your first JavaFX project! Just open your IDE and create a new project. After doing that, create a new Java file and start coding.
6. For creating the frontend, open the scene builder and create a new FXML file. Then just pick and drop any buttons, text fields, regions, tabs etc into the workspace.
7. Then create a respective controller class in your IDE and link it with the corresponding FXML from scene-builder. Then create an object for each element (button, text field, etc) present in your FXML.
8. Now, you are ready to code the backend and link your frontend to it accordingly.
9. Also, for connection with the database, it is preferable to create a separate connection class and create its object from other classes wherever database connection is needed. You can use XAMPP server or any other server for the same.

After you follow and fully understand each and every step above, you can enhance your project by creating a client-server based application using socket programming, etc. And as far as the front-end is concerned, CSS stylesheets can be used for making it look attractive.

### Some links to guide your way through

*   To install any IDE (Intellij guide) - [https://www.youtube.com/watch?v=EMLTOMdIz4w](https://www.youtube.com/watch?v=EMLTOMdIz4w)
*   For setting up scene-builder with Intellij - [https://www.youtube.com/watch?v=FylHot91Lz8](https://www.youtube.com/watch?v=FylHot91Lz8)
*   How to use scene-builder?   [https://www.youtube.com/watch?v=zvgWgpGZVKc](https://www.youtube.com/watch?v=zvgWgpGZVKc)

For complete reference to JavaFX, you may refer to [JavaFX Java GUI Design Tutorials](https://www.youtube.com/playlist?list=PL6gx4Cwl9DGBzfXLWLSYVy8EbTdpGbUIG).

## References

Since, JavaFX is a relatively new technology, there are only a limited number of tutorials available on the internet for the same. Also, referring to tutorials is useful only till you are learning some technology. Once learnt, you are good to go for creating anything you have in mind! And if it is something unique, then even in the older technologies, the tutorials for the same won’t be available either. Thus, it is advisable to refer to the documentation of the concerned tech stack in use. It gives you the best ‘to-the-point’ answers to your queries. And saying it from my personal experience, you can find literally any functionality or methods present in any library of a tech in its documentation!


<!-- Footnotes themselves at the bottom. -->
## Notes

[^1]:
     **Rich Internet Applications** - web applications which deliver the same features as that of a desktop application.

[^2]:
     Don’t forget the **platform-independent** feature of Java!

[^3]:
     **Hardware acceleration** is the process of assigning a specified hardware to certain applications thus enabling greater efficiency by saving general purpose CPU cycles.

[^4]:
     **Lightweight process (LWP)** - Each process contains one or more LWP, each of which runs one or more user threads.

[^5]:

     **FXML** - FXML is an XML-based declarative markup language for constructing a JavaFX application user interface. A designer can code in FXML or use JavaFX Scene Builder to interactively design the graphical user interface (GUI).

[^6]:
     **GUI** - Graphical User Interface (in layman terms, it is what you see and interact with in the application or front-end of your application).

[^7]:

    **IDE** - Integrated development environment. It normally consists of at least a source code editor, build automation tools and a debugger.

[^8]:

     **Scene Builder** is a visual layout tool that lets users quickly design JavaFX application user interfaces, without coding.

<!--stackedit_data:
eyJoaXN0b3J5IjpbMTYxMDUyODIxOV19
-->