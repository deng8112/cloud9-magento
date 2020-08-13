# Cloud 9 IDE Magneto installation

AWS Cloud9 IDE for MAgento is a cloud-based integrated development environment (IDE) that lets you write, run, and debug your Magento code

![Magento Cloud 9](https://github.com/Genaker/cloud9-magento/raw/master/images/AWS_Cloud9_Magento.jpg)

# Benefits
## CODE WITH JUST A BROWSER
AWS Cloud9 gives you the flexibility to run your magento development environment on a managed Amazon EC2 instance or any existing Linux server that supports SSH.
This means that you can write, run, and debug Magento applications with just a browser, without needing to install or maintain a local IDE. 
The Cloud9 code editor and integrated debugger include helpful, time-saving features such as code hinting, code completion, and step-through debugging. 
The Cloud9 terminal provides a browser-based shell experience enabling you to install additional software, do a git push, or enter commands.

## CODE TOGETHER IN REAL TIME
AWS Cloud9 makes collaborating on code easy. You can share your Magento development environment with your team in just a few clicks and pair program together.
While collaborating, your team members can see each other type in real time, and instantly chat with one another from within the IDE.

![](https://github.com/Genaker/cloud9-magento/raw/master/images/C9-Collab-Image.png)

## BUILD SERVERLESS APPLICATIONS WITH EASE
AWS Cloud9 makes it easy to write, run, and debug serverless applications. It preconfigures the development environment with all the SDKs, libraries, and plug-ins needed for serverless development. Cloud9 also provides an environment for locally testing and debugging AWS Lambda functions. This allows you to iterate on your code directly, saving you time and improving the quality of your code.

## DIRECT TERMINAL ACCESS TO AWS
AWS Cloud9 comes with a terminal that includes sudo privileges to the managed MAgento Amazon EC2 instance that is hosting your development environment and a preauthenticated AWS Command Line Interface. This makes it easy for you to quickly run commands and directly access AWS services.

![](https://github.com/Genaker/cloud9-magento/raw/master/images/MAgento_terminal_Cloud9.png)

# Terminal New
## START NEW PROJECTS QUICKLY
AWS Cloud9 makes it easy for you to start new projects. Cloud9’s development environment comes prepackaged with tooling for MAgento and over 40 programming languages, including Node.js, JavaScript, Python, PHP, Ruby, Go, and C++. This enables you to start writing Magento Microdervices code using popular application stacks within minutes by eliminating the need to install or configure files, SDKs, and plug-ins for your development machine. Because Cloud9 is cloud-based, you can easily maintain multiple development environments to isolate your project’s resources.

## There are two types of AWS Cloud9 environments that you can use.

AWS Cloud9 EC2 environment – Enables you to launch a new Amazon EC2 instance that Cloud9 connects to. By default, these instances stop 30 minutes after you close the IDE and start automatically when you open the IDE.
AWS Cloud9 SSH environment – Enables you to connect an existing Linux server with Cloud9. There are certain dependencies that are required on the Linux server that you want to use with Cloud9 SSH environments. 
Please visit AWS documentation for more details.

## Auto Hybernetion feature for the development enviroment 

AWS Cloud9 provides a default auto-hibernation setting of 30 minutes for your Amazon EC2 instances created through Cloud9. With this setting, your Magento2 EC2 instances automatically stop 30 minutes after you close the IDE and restart only when you reopen the IDE. As a result, you typically only incur EC2 instance charges for when you are actively working. When your instance requires a restart, you lose any active terminal sessions in the IDE and can experience some wait time while opening your IDE. Depending on your use case, you can configure the auto-hibernation setting and even elect to keep your EC2 instance “always on”.
