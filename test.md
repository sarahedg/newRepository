# Test

user@win-304:~/src/devopsbydan$ get status
user@win-304:~/src/devopsbydan$ git config --list
user@win-304:~/src/devopsbydan$ git config --remote.origin.url=git@github.com:danjferguson/devopsbydan.git
user@win-304:~/src/devopsbydan$ code how-to/start-git.md 
user@win-304:~/src/devopsbydan$ cd ..
user@win-304:~/src$ rm -rf devopsbydan/
user@win-304:~/src$ git clone git@github.com:danjferguson/devopsbydan.git
user@win-304:~/src$ cd devopsbydan/
user@win-304:~/src/devopsbydan$ code how-to/start-git.md 
user@win-304:~/src/devopsbydan$ git commit -a -m "added ssh stuff"
user@win-304:~/src/devopsbydan$ git push
