# Beaver-notes-ppa

```
curl -s --compressed "https://Daniele-rolli.github.io/Beaver-notes-ppa/KEY.gpg" | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/Beaver-notes-ppa.gpg >/dev/null
sudo curl -s --compressed -o /etc/apt/sources.list.d/my_list_file.list "https://Daniele-rolli.github.io/Beaver-notes-ppa/Beaver_notes_file.list"
sudo apt update
```
