# ardrive-downloader
Downloads content from ArDrive

_Note: For use with decrypt_concat_script (https://github.com/SpawnID0000/decrypt_concat_script)_

Before running this script, install or upgrade the following:
```
brew install git

curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash

brew install node

npm install -g ardrive-cli
npm update -g ardrive-cli
```

Run the script using the following command line format:
```
python3 ardrive-downloader.py [-h] m3u_path ardrive_wallet_path [--music-path MUSIC_PATH]
```
