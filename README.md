# COS2614 Organization

Welcome to the COS2614 organization on GitHub! This organization is aimed at university students studying "COS2614: Programming: Contemporary concepts" and is dedicated to helping students learn C++ and the Qt framework.

The purpose of this organization is to encourage student participation and facilitate learning by providing a platform where students can access various resources, including code examples, solutions to programming challenges, and discussion forums where they can seek and provide help. 

Most of the code examples provided in this organization are based on the book "An Introduction to Design Patterns in C++ with Qt, 2nd Edition" by Alan Ezust and Paul Ezust. We have attempted to port the code written for Qt4 to Qt6, so students can practice coding in a more recent version of Qt.

## First off
This organization is run by students and it is a work in progress (as of March 2023). The *study objectives* for this organization are listed below. Contributions to this organization will be made over time, so check back for updates.
If there is something in particular you would like help with, please see the *contact us* section below and get in touch.

## How to use these repositories

These repositories contain various resources to help students learn C++ and the Qt framework. Here's a quick overview of what you can find in this repository:

- Code examples: These repositories contain code examples that cover various topics related to C++ and Qt programming. You can use these examples to practice coding and to get a better understanding of how C++ and Qt work.
- Programming challenges: We have included programming challenges in this repository to help you practice your programming skills. These challenges are designed to test your knowledge of C++ and Qt, and to help you apply the concepts you have learned in class.
- Discussions: We encourage students to participate in discussions on the discussion forums to ask and answer questions, share tips and best practices, and help each other learn.

## Contributing to this repository

We welcome contributions from students and anyone interested in C++ and the Qt framework. If you would like to contribute to these repositories, you can do so by submitting a [pull request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request) for a particular repository. We also encourage you to submit bug reports, feature requests, and feedback to help us improve this repository.

## Acknowledgements

We would like to acknowledge Alan Ezust and Paul Ezust for their book "An Introduction to Design Patterns in C++ with QtTM, 2nd Edition," which has provided much of the code examples used in this organization. We also acknowledge the Qt Company for their continued support and development of the Qt framework.

## Contact us

If you have any questions or feedback, please feel free to contact us through the discussion forums or by emailing us at [tide.mute_06@icloud.com] We look forward to hearing from you and hope that you find this repository helpful in your studies of C++ and the Qt framework.

## COS2614 Objectives

### Chapter 1: Introduction to C++
- Write simple Qt programs that uses QTextStream, QString and QFile. 
- Write a program that uses Qt dialog classes for input and output. 
- Write a program that uses command line arguments. 
- Understand the difference between and the uses of the unary operators & and * to work with pointers and addresses. 

### Chapter 2: Classes
- Write a class, putting the class definition with the declaration of its member functions in a header file, and the implementation of its member functions in a source file. 
- Use the #include pre-processor directive to include the header files of all necessary classes used in a header or source file. 
- Use the pre-processor directives #ifndef, #define and #endif to ensure that a header file containing a class definition is not included more than once in the source code files of a project. 
- Distinguish which members of a class (data members and member functions) should have public, private or protected access specifiers, and which member functions should be const. 
- Draw UML class diagrams to specify the data members and member functions of classes and possible composition relationships with other classes. 
- Write multiple classes that have a composition relationship with one another. 
- Use static data members and static member functions correctly in a class. 
- Explain, detect and resolve circular dependencies among classes. 
- Implement a destructor for a class, particularly when the class has a pointer data member. 
- Implement a copy constructor and assignment operator for a class, particularly when the class has a pointer data member. 
- Know in what situations copy constructors are called.

### Chapter 3: Introduction to Qt
- Write Qt programs that comply with the style guidelines explained in Section 3.1. 
- Write console applications that declare an instance of QTextStream (called cout) for outputting. 
- Use the QDate class to convert dates to different formats.

### Chapter 4: Lists
- Write programs that use the QList and QStringList classes. 
- Write classes that have data members which are instances of the QList or QStringList classes. 
- Make use of iterators in your programs 
- Write classes that inherit from QList. 
- Draw UML class diagrams that indicate aggregation, composition and association relationship between classes. 
- Understand the difference between aggregation and composition relationships between classes.

### Chapter 5: Functions
- Overload functions as appropriate. 
- Use default parameter values to allow optional arguments for functions. 
- Use pass-by-value, pass-by-reference, and pass-by-const-reference parameters as appropriate for functions and member functions. 
- Use return-by-value and return-by-const-reference as appropriate in functions and member functions.

### Chapter 6: Inheritance and Polymorphism
- Draw UML class diagrams that indicate which members of classes are private, public and protected, and that indicate inheritance relationships with other classes. 
- Write multiple classes that have an inheritance relationship. 
- Write client code that utilises multiple classes in an inheritance hierarchy, using polymorphism when appropriate. 
- Overload member functions within a class as appropriate. 
- Override and hide member functions derived from a superclass and use partial overriding as appropriate in classes. 
- Decide when abstract base classes are appropriate, and design and implement class hierarchies that use them. 
- Decide when it is appropriate to implement the Big Three for a class that contains a collection of other objects, and do so. 
- Understand how the ArgumentList class can be used to process command-line arguments and switches. 
- Understand what associative containers are and how they differ from the other Qt containers; understand what assignable data types are and use them appropriately with associative containers. 
- Understand the differences between managed and value (i.e. unmanaged) containers, and use them appropriately in programs.

### Chapter 8: QObject, QApplication, Signals and Slots
- Write a class that inherits from the QObject class, and write a program that creates a tree of objects of that class to use the child management capability of QObject to avoid memory leaks. 
- Understand the Composite design pattern, and how the QObject class is a simplified application of this pattern. 
- Understand the event handling model that the Qt framework provides, implemented by means of signals and slots. 
- Understand Qt’s support for unit-based testing. 

### Chapter 9: Widgets and Designer
- Write programs that use dialog boxes with varying numbers of buttons, to provide messages to the user, and to react appropriately to the button the user clicks on. 
- Write programs that use input dialogs to allow the user to respond in a richer way (e.g. select an item from a combo box or choose a value using a spin edit) and to react appropriately to the user choice. 
- Understand the advantages of using resource files when displaying images in an application. 
- Use multiple layouts to arrange widgets on an application window, and use spaces, stretches and struts to ensure that they move appropriately when the window is resized. 
- Program graphical user interfaces manually. 
- Write programs that listen and respond to low level events 
- Make use of timers in your programs 
- Understand the role of paint events in widgets 

### Chapter 10: Main Windows and Actions
- Write programs that use dialog boxes with varying numbers of buttons, to provide messages to the user, and to react appropriately to the button the user clicks on. 
- Write programs that use input dialogs to allow the user to respond in a richer way (e.g. select an item from a combo box or choose a value using a spin edit) and to react appropriately to the user choice. 
- Use menus, menu bars and toolbars together with actions and action groups to allow users to perform the same action in a program in different ways. 
- Write programs that use the QSettings class to allow persistence of the program state from one execution to the next. 
- Understand the Monostate pattern. 
- Understand the QSettings class and how it can be used to preserve the settings of an application. 
- Understand the Command pattern. 
- Understand that Qt supports Internationalization.

### Chapter 11: Generics and Containers
- Write programs that use function templates, and make sure that the types that you want to use with a function template overload the required operators. 	
- Understand functors. 
- Understand what implicit sharing is and how this is employed in Qt container classes to save copying managed containers when it isn't necessary. 
- Understand the Flyweight pattern. 



