# Tomacat-Errors
Case 1:
        Invalid Ports/ Already service is running on the port/ Ports are invalid.
Steps:

      * Open command promt (run it as an administrator if required).
     
     * netstat -a -n -o //Listing the serives running with pid.
     
     * netstat -ano | findstr :<PORT> // To search with <PORT> .
     
     * taskkill /PID <PID> /F // Kill the Process.
     
     * Cross Check by Runnning First Command again.
