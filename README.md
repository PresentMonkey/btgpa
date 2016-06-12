Bergen Tech GPA Calculator
======================================

Download and install latest version of [Oracle Java](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html).

Install [Homebrew](http://brew.sh) package manager by launching Terminal application and entering:

    $ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

Install [Apache Maven](https://maven.apache.org/): 

    $ brew install maven

Clone the github repository:

    $ git clone https://github.com/rachelluuu/btgpa.git
    $ cd btgpa
    
Comppile the Java sources:

    $ mvn clean package

Run [jetty](http://www.eclipse.org/jetty/) application server:

    $ java -cp target/gpa-2-SNAPSHOT/WEB-INF/lib/*:target/gpa-2-SNAPSHOT/WEB-INF/classes com.bt.gpa.Main

Open your web browser to:

    http://localhost:8080/  

To stop Jetty:

  use <kbd>CTRL</kbd>+<kbd>C</kbd>


Team Members
----------------
*	Rachel Lu
*	Jennifer He
*	Gabe Wehrle
