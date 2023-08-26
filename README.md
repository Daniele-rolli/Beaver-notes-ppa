# Beaver-notes-ppa

```
curl -s --compressed https://daniele-rolli.github.io/Beaver-notes-ppa/KEY.gpg | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/Beaver-notes-ppa.gpg >/dev/null
sudo curl -s --compressed -o /etc/apt/sources.list.d/Beaver_notes_file.list https://daniele-rolli.github.io/Beaver-notes-ppa/Beaver_notes_file.list
sudo apt update
```
