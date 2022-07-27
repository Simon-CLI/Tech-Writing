## How to reset Wi-Fi using the CLI (Command Line Interface)

#### Environment

- Red Hat Enterprise Linux (RHEL)
- CentOS
- Fedora Linux
- Any Linux distributions that use the RPM.(Red Hat Package Manager)

#### Issue
- How to reset Wi-Fi using the CLI


#### Prerequisite
You need `sudo` access to following the procedure



#### Resolution
The resolution is to resolve the slow Wi-Fi internet connection via CLI by the following procedure: 



**Important**: The Wi-Fi internet connection will be temporarily disconnected and reconnected automatically after step 4

1. Open the CLI and type `sudo -i`

2. Type your sudo password

3. Make sure you are logged-in as a root. You should see this `[root@yourusername ~]` in CLI'

4. Type `systemctl restart NetworkManager`





