# Boxstarter
To quickly get up and running with a new Windows box with a minimum of manual intervention needed

#  How to use
- Install Windows 10 and go through the OOBE
  - Select Region
  - Select Keyboard Layout
  - SKIP Secondary keyboard layout
  - Network connection
  - ENABLE Allow PC to be discoverable
  - Setup = For personal use
  - Account = Offline account
    - like old times - a completely standalone PC
  - Sign in = Limited experience
    - ignore the nudging to make an online account
  - User account = <my initials>
    - as this gets used for the name of the home folder and I don't want my full name for that
  - No password
    - to avoid the nonsense socalled "security questions"). Password will be set later *after* completing the installation
  - Location usage = No
  - Find my device = No
  - Diagnostic data = Required only
  - Improve inking = No
  - Tailored experience = No
  - Advertising ID = No
  - Customise experience = Skip
  - Set a password for the account
  
- Launch boxstarter
  - Either via PowerShell (Win x, i), then paste the following command
    - `start https://boxstarter.org/package/url/?https://raw.githubusercontent.com/tveyben/boxstarter/main/boxstarter-win10.txt`
  - Or paste the URL into a MS browser (not Chrome)
    - `https://boxstarter.org/package/url/?https://raw.githubusercontent.com/tveyben/boxstarter/main/boxstarter-win10.txt`
  - Then
    - Select "Open" to open this file
    - Select "Run" to execute the script
  - Select "Yes" to allow Boxstarter.WebLaunch to make changes...
  - Enter your account password so BoxStarter can reboot and login in again
    - If you don't trust the script change your password after installation (eg. use a "throw away one time password")
    - NB.: Password cannot be `blank`  :-)
  
- Sit back and enjoy the "working smart - not hard"
    - There will be a few reboots
    - Some installers require GUI response to complete the installation
      - ncap (wireshark)
  - Other launch to allow configuration
    - Discord    
    - PowerToys
    - Samsung Magician
  
  
- Complete the WSL2/Ubuntu installation
    - Launch "Ubuntu 20.04 LTS"
    - Provide a "UNIX username" and a password

# TODO
  - Add user based configuration (aka dotfiles)
  
  - Complete the WSL setup
    - Configure vcxsrv (for WSL2 GUI)
    - Link to my *nix dotfiles repo
  
  
  
  

  
  
  

  
  
