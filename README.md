# attack-relay
## vision
* To provide the pentester with an accessory to help with relaying information.
* To avoid new type of attacks that would allow targets to attack the attackers. by implementing a layer between the attacker and the target.
* To help with faster and easier reporting, auditing and log(writeups) the attacks
* To use Open Source tools and scripts without sacrificing the ease of POSIX commands
* To automate and replay attacks on machines already visited (continues attacks)
* To co-operate attacks on machines with teams

### Inspiration
    I hate using the normal `python3 -m http.server` and I'm sure safer alternatives to transfer files and information both from and to the machine could be made easier.
    

### Main Sections
* Connection - helps setup the connection information ( ip-ranges, ports, stealthy, tasks, jobs, timeout, wait time, etc..
* Commands - Send commands
* Scripts - Use scripts to automate some operations
* Filesystem - View of the filesystem
* Scanner - Scripts to scan and report back
* Logs - Show commands ran on the remote machine, allows for selective reporting.


## Architecture
* pythonic ,easy to write, django front-backend
* would be installed on an instance of kali( in docker ), along with the webserver. this would allow an attacker to use all of kali tools.

#Development
