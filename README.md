setup.git
=========
Setup for a new EC2 instance running Ubuntu 12.04.2 LTS with node.js to
configure both the machine and your individual development environment. Install for user "ubuntu" with:

```sh
#!/bin/bash
curl https://raw.github.com/GlobalN0mad/setup/master/setup.sh | sudo -H -i -u ubuntu sh
```
The above shell script can be used as the user-data (text) parameter when starting an Ubuntu AWS instance to initialize the environment for user "ubuntu".

See also http://github.com/startup-class/dotfiles and
[Startup Engineering Video Lectures 4a/4b](https://class.coursera.org/startup-001/lecture/index)
for more details.





