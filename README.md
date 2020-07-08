# newRepository

## Showing Ron Some Linux Stuff

### Environment

You will either need to run a Linux Distribution on its own VM or run Ubuntu or Kali within a Docker Container on a Windows machine

Repository access (GitHub account - sign up here: <https://github.com/join>)

### Tools

nmap

'nmap -v -A www.securenetwork.tech > ~/results.txt'

-v means verbose
-A detects the operating systems and services that are running on that address
">" means output data in plain text
"~/" is the home dir
results.txt is the file name.

updated nmap script contents:

cd $HOME
nmap -v -A -iL ips.txt -oN output_nmap.txt

-iL means interactive list (then name of text file list in Kali_root dir)
-oN means normal output (see nmap.org) then supply a name of the output file

#### Editors

    Visual Studio Code - Best Text Editor for working on Windows machine
    VI, subsumed by VIM is another editor, see <https://vim.rtorr.com/>
