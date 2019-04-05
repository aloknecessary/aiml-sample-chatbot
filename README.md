# aiml-sample-chatbot
An chat bot created using AIML, for demo purpose.

These are the requirements for running this application on your system. 
	## Step 1 - Set up Java Development Kit (JDK)

You can download the latest version of SDK from Oracle's Java site −  [Java SE Downloads](https://www.oracle.com/technetwork/java/javase/downloads/index.html). You will find instructions for installing JDK in downloaded files, follow the given instructions to install and configure the setup. Finally set PATH and JAVA_HOME environment variables to refer to the directory that contains java and javac, typically java_install_dir/bin and java_install_dir respectively.

If you are running Windows and installed the JDK in C:\jdk1.7.0_75, you would have to put the following line in your C:\autoexec.bat file.

    set PATH = C:\jdk1.7.0_75\bin;%PATH%
    set JAVA_HOME = C:\jdk1.7.0_75

Alternatively, on modern Windows systems you could also right-click on My Computer, select Properties, then Advanced, then Environment Variables. Then, you would update the PATH value and press the OK button. Also you can create a new variable for JAVA_HOME in same way.

On Unix (Solaris, Linux, etc.), if the SDK is installed in /usr/local/jdk1.7.0_75 and you use the C shell, you would put the following into your .cshrc file.

    setenv PATH /usr/local/jdk1.7.0_75/bin:$PATH
    setenv JAVA_HOME /usr/local/jdk1.7.0_75

**After installation plz run a sample command to endure java is installed correctly.**

## Step 2 - Set up Program AB

Now if everything is fine, then you can proceed to setup your Program AB. Following are the simple steps to download and install the library on your machine.

-   Make a choice whether you want to install AIML on Windows, or Unix and then proceed to the next step to download .zip file
    
-   Download the latest version of Program AB binaries from  [https://code.google.com/p/program-ab/](https://code.google.com/p/program-ab/)  using its  [program-ab-0.0.4.3.zip](https://code.google.com/p/program-ab/downloads/detail?name=program-ab-0.0.4.3.zip&can=1&q=)  link.
    
-   At the time of creating this demo, I downloaded  **program-ab-0.0.4.3.zip**  on my Windows machine and when you unzip the downloaded file it will give you directory structure inside C:\ab as follows.
	
| S.No. | Folder & Description |
|--|--|
| 1 |  **c:/ab/bots** <br> Stores AIML bots|
| 2 |  **c:/ab/lib** <br>Stores Java libraries|
| 3 |  **c:/ab/out**<br>Java class file directory|
| 4 |  **c:/ab/run.bat** <br> batch file for running Program AB|

Once you are done with this last step, you are ready to proceed with running this AIML Example
