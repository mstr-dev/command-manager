<snippet>
# Server Status
This procedure was created to determine the status of a particular server which could then be grep'd through command line.

One of three values will be returned;
1. Active
1. Paused
1. Stopped

Note that this is a "contains comparison" on the sServerName input. Therefore multiple server's results could be returned if desired.

## Installation
Copy the applicable procedure to your "User Procedures" folder then restart Command Manager.

Example folder path: C:\Program Files (x86)\MicroStrategy\Command Manager\Outlines\Procedure_Outlines\User_Procedures

## How To Use

Steps to use procedures in this repo:

Clone the repo and copy the procedures you like to {Command Manager folder}/Outlines/Procedure_Outlines/User_Procedure.
Re-launch Command Manager.
You'll find the procedure appears in the CM Outline window, under Procedure_Outlines > User_Procedures. The instruction of the procedure will be show in the outline. You can provide parameters according to the Samples and execute the procedure.

You can always refer to the Procedure related topics in Command Manager Help document for more information.

## Execution
EXECUTE PROCEDURE Server_Status("server_name_string_match");

## History
2016-06-27: Initial creation by Jonathan

## Credits
Jonathan Smith

## Disclaimer
We do not guarantee or be responsible for the safety of these procedures. Please evaluate the risk before you use any of them

</snippet>