# OS Starters 
Different starter scripts and configurations for various operating systems

* Mac OSX
* Ubuntu/Linux
* Kali Linux
* Raspberry Pi


### Purpose of this repo

Quick download kit when you're working with a fresh install. Each install script targets a specific OS in particular, but all of them accomplish the following:

1. Update the OS
2. Run preflight install script (package managers, etc) 
3. Create user group, add to sudoers
4. Create user, add to group, set password
5. Git setup
6. SSH key & agent setup
7. Download OS specific packages (brew, apt)
8. Install all runtime packages (node, ruby, etc)
9. Download OS mainstream apps (App store, DMGs, .apps)
10. Download user dotfiles & run ./install.sh



---

Overall approach:

1. Update system core
2. Install runtime environments
3. Install runtime-specific packages
4. Install dotfiles
5. Download additional software packages
6. OS-specific requirements (Xcode, terminal install, etc)
7. Configure AWS and download any additional resources

---
