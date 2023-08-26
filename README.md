# Beaver-notes-ppa

```
curl -s --compressed "https://raw.githubusercontent.com/Daniele-rolli/Beaver-notes-ppa/main/beaver-ppa/KEY.gpg?token=GHSAT0AAAAAACGZGYDIAVSDVJWROPXNUFX6ZHKNNDQ" | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/Beaver-notes-ppa.gpg >/dev/null
sudo curl -s --compressed -o /etc/apt/sources.list.d/Beaver_notes_file.list "https://github.com/Daniele-rolli/Beaver-notes-ppa/blob/main/beaver-ppa/Beaver_notes_file.list"
sudo apt update
```
