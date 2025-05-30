# DNS-Autoregistration
How to create virtual machines with automatic dns registration using NetBox

Something I recognised right away when creating my homelab is that every vm I created only had the host ip in the dns config file. This meant that I had to manualy go to my dns config file and add ```8.8.8.8``` to be able to do updates and grab repos from github.
