<snippet>
# Using file for input
Recently the community has had a lot of questions about "How do I use an external file in Command Manager"?

Challenge Accepted!

The purpose of this release was to create two script shells that could be used to loop through files and execute Command Manager commands using their values.

If a script is being executed as a one-off I would recommend using a different approach; however if you are building a recurring process; I hope this is helpful


## Installation
Download the JExcelAPI
    https://sourceforge.net/projects/jexcelapi/files/jexcelapi/
    Most people will want to install this jar in their Java directory; however that is up to you
Copy the applicable procedure to your "User Procedures" folder then restart Command Manager.
Then, edit the file (through Command Manager or your favorite editor (Notepadd++))

If you are using the jExcelAPI (Excel Version of procedure);
    You will need to point classpath to jxl.jar from the procedure editor in Command Manager (right hand side under Properties)
    Currently defaulted to C:/Temp/jexcelapi/jxl.jar

If you are using Text (Text | CSV Version of procedure);
    You do not need to add any classpaths
    
NOTE about classpaths;
    Command Manager does not allow the "import" command. Instead you point to the .jar file through classpath. It will import everything, however you need to give the full path when calling anything. There is no aliasing.

Example User Procedures folder path: C:\Program Files (x86)\MicroStrategy\Command Manager\Outlines\Procedure_Outlines\User_Procedures

## How To Use

Steps to use procedures in this repo:

Clone the repo and copy the procedures you like to {Command Manager folder}/Outlines/Procedure_Outlines/User_Procedure.
Re-launch Command Manager.
You'll find the procedure appears in the CM Outline window, under Procedure_Outlines > User_Procedures. The instruction of the procedure will be show in the outline. You can provide parameters according to the Samples and execute the procedure.

You can always refer to the Procedure related topics in Command Manager Help document for more information.

## History
2016-07-01: Initial creation by Jonathan

## Credits
Jonathan Smith - jonathanofsmith@gmail.com

## Disclaimer
We do not guarantee or be responsible for the safety of these procedures. Please evaluate the risk before you use any of them

</snippet>