# Beaver-notes-ppa
Welcome to the Official PPA of Beaver Notes. This PPA serves as a milestone in the effort of making Beaver Notes easily accessible for everyone. Starting today (August 27, 2023), Beaver Notes will be available as a package through apt for Debian and Debian-based distributions.

To install Beaver Notes through apt, first uninstall any previous version of Beaver Notes. Don't worry, uninstalling won't delete your notes. Feel free to back them up by exporting them if you want an extra safety net. After that, run the commands below.

| Arch | Support |
| ------------- | ----------- |
| X64_86  |  ✅ |
| Arm64 |  ✅ | 

Fetching Repository GPG Key
```
curl -s --compressed https://daniele-rolli.github.io/Beaver-notes-ppa/KEY.gpg | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/Beaver-notes-ppa.gpg >/dev/null
```
Adding Beaver Notes Repository Source
```
sudo curl -s --compressed -o /etc/apt/sources.list.d/Beaver_notes_file.list https://daniele-rolli.github.io/Beaver-notes-ppa/Beaver_notes_file.list
```
Updating Package Lists
```
sudo apt update
```
Installing Beaver Notes
```
sudo apt install beaver-notes
```
