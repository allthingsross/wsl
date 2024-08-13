# wsl
All things WSL (Windows Subsystem for Linux)

1. Backups - wslbackup.bat
   - Save wslbackup.bat file to somewhere on windows system %PATH%
   - Backups are written to %HOMEPATH%\wsl\backups\wsl-ubuntu.backup.tar
   - There is just one backup, which is overwritten each time wslbackup.bat file is executed
   - Execute wslbackup.bat in either of the following ways: -
     - Windows GUI: Double click wslbackup.bat (or any shortcut to wslbackup.bat)
     - CMD prompt:  cmd> wslbackup.bat

   - Please note that the WSL instance will be stopped before backup and then restarted upon completion!
   - Please note that the WSL instance "Ubuntu" is hard-coded in the .bat file!
   - Future enhancements
     - backup versioning and housekeeping
     - specifying backup name and location as an argument to wslbackup.bat
     - specifying WSL instance name to be backed-up or backup all WSL instances on the WSL
