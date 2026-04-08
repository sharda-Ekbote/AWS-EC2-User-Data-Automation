AWS-EC2-User-Data-Automation


To use AWS EC2 User Data to automate the configuration of a web server during the initial launch.
By passing a shell script to the instance, you can automatically update the system, install a web stack (Apache/PHP),
and deploy code from a remote repository (GitHub) without manual intervention.

Architecture Components
->Amazon EC2: The virtual server (t2.micro) being provisioned.

->User Data: A script that runs with root privileges during the first boot of the instance.

->Apache & PHP: The software stack installed automatically.

->GitHub: The source for the web application code being cloned.
