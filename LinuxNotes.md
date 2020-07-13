# NOTES

## Linux Itself

Either run a Linux Distribution on its own VM or within a Docker Container on a Windows machine
Sarah will start a customized kali image via Docker, each session:  
    `docker run -ti --rm -v $HOME/kali_root:/root my-kali`
    
## Github

Repository access (GitHub account - sign up here: <https://github.com/join>)

## Tools

nmap

'nmap -v -A www.securenetwork.tech > ~/results.txt'

-v means verbose
-A detects the operating systems and services that are running on that address
">" means output data in plain text
"~/" is the home dir
results.txt is the output file name.

updated nmap script contents:

put the full path into the below ~/<path>/file.names 

nmap -v -A -iL ips.txt -oN output_nmap.txt

-iL means interactive list (then name of text file list in Kali_root dir)
-oN means normal output (see nmap.org) then supply a name of the output file

## Editors

    Visual Studio Code - Best Text Editor for working on Windows machine
    
    VI, subsumed by VIM is another editor, see <https://vim.rtorr.com/>
    To use it, at the root user home prompt, type `vi <<filename>>`

    Fireeye scanner for Citrix: <https://github.com/fireeye/ioc-scanner-CVE-2019-19781/releases/download/v1.4/ioc-scanner-CVE-2019-19781-v1.4.sh>
