# Angelscript VSCode Remote Debugger

This is a debug adapter for Angelscript language which allows for remote debugging of scripts. It requires specific setup on
application side. I'm using RakNet TCPServer and Node.js net library for communication between adapter and the running program,
but this can be customized.

## Using debugger

* Install the **Angelscript RemoteDebugger** extension in VS Code.
* Configure remote host and port where application is running
* Attach to running application and start debugging
