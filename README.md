<p align="center">
  <br>
  <img alt="Logo" src="https://i-cdn.phonearena.com/images/articles/246655-image/025Pikachu-OS-anime-5.png" width="200">
  <br><br>
  <a href="https://github.com/HUCTF/JSCrypt/raw/master/release-builds/JSCript-win32-ia32.rar" target="_blank"><img alt="undefined" src="https://badgen.net/badge/Download/Windows/?color=blue&icon=windows&label"></a>
  <a href="https://github.com/HUCTF/JSCrypt/raw/master/release-builds/JSCript-win32-ia32/JSCript.exe" target="_blank"><img alt="undefined" src="https://badgen.net/badge/Download/macOS/?color=grey&icon=apple&label"></a>
  <a href="https://github.com/HUCTF/JSCrypt/raw/master/release-builds/JSCript-win32-ia32/JSCript.exe" target="_blank"><img alt="undefined" src="https://badgen.net/badge/Download/Linux64/?color=orange&icon=terminal&label"></a>
  <br><br><br>
</p>


 JSCrypt is an Electron App based on the crypto-js and StatiCrypt.


## Features

- JSCrypt generates a password protected HTML file that can be decrypted in-browser: just send or upload the generated page to a place serving static content (github pages, for example) and that's all: the javascript will prompt users for password, decrypt the page and load the HTML file.

- JSCrypt uses open source AES-256 military grade encryption to encrypt user input with encryption key and embed it in a HTML file with a password prompt that can decrypted in-browser (client side).

- Basically JSCript encrypts the entire page and packs everything with a user-friendly way to use a password in the new file.

## DIY Build

- 'npm i' to install dep
