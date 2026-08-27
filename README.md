# Awesome password-store with stars

[Pass](https://www.passwordstore.org/) is awesome. And these extensions make it even more so! This is a collection of awesome password-store extensions and interfaces.

Additions and improvements are welcome! Please make pull-requests.

## Contents

* [extensions](#extensions)
  * [auditing](#auditing)
  * [clipboard](#clipboard)
  * [output](#output)
  * [import](#import)
  * [generators](#generators)
  * [All other extensions](#all-other-extensions)
* [Interfaces](#interfaces)
* [Import scripts](#import-scripts)
* [Export scripts](#export-scripts)

## Extensions

### Auditing

* **[pass-audit](https://github.com/roddhjav/pass-audit) ⭐ 104 | 🐛 8 | 🌐 Python | 📅 2025-05-14** (by [roddhjav](https://github.com/roddhjav)): A pass extension for auditing your password repository. *(There are two extensions with this name; this one checks Have I Been Pwned and estimates password strength using Dropbox' [zxcvbn](https://blogs.dropbox.com/tech/2012/04/zxcvbn-realistic-password-strength-estimation/) algorithm.)*
* **[pass-pwned](https://github.com/alzeih/pass-pwned/) ⭐ 10 | 🐛 3 | 🌐 Shell | 📅 2019-08-20** (by [alzeih](https://github.com/alzeih)): Password-Store extension for Have I Been Pwned? Pwned Passwords v2 API.
* **[pass-report](https://github.com/Kdecherf/pass-report) ⭐ 8 | 🐛 0 | 🌐 Shell | 📅 2018-04-01**: A pass extension that reports age and length of passwords.
* **[pass-audit](https://github.com/benburwell/pass-audit) ⭐ 6 | 🐛 0 | 🌐 Roff | 📅 2018-02-24** (by [benburwell](https://github.com/benburwell)): A pass extension for checking whether your passwords may be compromised. *(There are two extensions with this name; this one checks Have I Been Pwned as well as a local wordlist file.)*
* **[pass-pwned](https://github.com/jamesridgway/pass-pwned) ⭐ 5 | 🐛 0 | 🌐 Shell | 📅 2019-01-20** (by [jamesridgway](https://github.com/jamesridgway)): Password-Store extension for Have I Been Pwned? Pwned Passwords v2 API or an offline password hash file of your choosing.
* **[pass-age](https://github.com/tijn/pass-age) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2021-08-31** (by [tijn](https://github.com/tijn)): A pass extension to show you how long you are using a certain password. *(There are two extensions with this name; this one shows the last time when the first line in a password file changed.)*
* **[pass-age](https://github.com/taylorskalyo/pass-age) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2018-09-20** (by [taylorskalyo](https://github.com/taylorskalyo)): A simple pass extension for displaying password age. *(There are two extensions with this name; this one shows the time of the last git commit.)*
* **[pass-hibp](https://gitlab.com/moviuro/pass-hibp/)**: A pass extension that queries the haveibeenpwned.com API.

### Clipboard

* **[pass-clip](https://github.com/ibizaman/pass-clip) ⭐ 38 | 🐛 0 | 🌐 Shell | 📅 2024-12-04**: A pass extension that lets you quickly copy to clipboard passwords using fzf or rofi.
* **[pass-extension-wclip](https://github.com/palortoff/pass-extension-wclip) ⭐ 22 | 🐛 1 | 🌐 Shell | 📅 2020-11-23**: a plugin to use wclip on Windows.
* **[select-pass-otp](https://github.com/Konfekt/select-pass-otp) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2025-12-28**: type or copy passwords or OTPs from a menu selector in X11 or Wayland
* **[pass-sclip](https://github.com/Boldewyn/pass-sclip) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2017-05-31**: A pass extension to copy to [screen](https://www.gnu.org/software/screen/)'s paste buffer.
* **[pass-extension-pclip](https://gitlab.com/lbischof/pass-extension-pclip)**: Copies meta data into primary clipboard.
* **[pass-tessen](https://git.sr.ht/~ayushnix/pass-tessen)**: fuzzy data selection and copy-paste from password store

### Output

* **[pass-extension-tail](https://github.com/palortoff/pass-extension-tail) ⭐ 88 | 🐛 1 | 🌐 Shell | 📅 2022-04-28**: A pass extension to avoid printing the password to the console.
* **[pass-extension-meta](https://github.com/rjekker/pass-extension-meta) ⭐ 16 | 🐛 1 | 🌐 Shell | 📅 2021-12-29**: password-store extension to retrieve meta-data properties from password files.
* **[pass-extension-copyq](https://github.com/vy/pass-extension-copyq) ⚠️ Archived**: A pass extension that copies a stored password using copyq.
* **[pass-cl](https://github.com/elcorto/pass-cl) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2026-04-29**: password-store extension to copy metadata from multi-line entries.
* **[pass-csv](https://github.com/lahr/pass-csv) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2021-02-09**: generate a CSV file from specified key-value pairs in the metadata.

### Import

* **[pass-import](https://github.com/roddhjav/pass-import) ⭐ 912 | 🐛 21 | 🌐 Python | 📅 2026-06-07**: a generic importer tool from other password managers.
* **[pass-file](https://github.com/lukrop/pass-file) ⭐ 20 | 🐛 3 | 🌐 Shell | 📅 2024-09-06** (by [lukrop](https://github.com/lukrop)): A pass extension for adding arbitrary files to the password store.
* **[pass-file](https://github.com/dvogt23/pass-file) ⭐ 18 | 🐛 3 | 🌐 Shell | 📅 2024-03-28** (by [dvogt23](https://github.com/dvogt23)): A pass extension that allows to add files to password-store.
* **[pass-import-1pux](https://tangled.org/@hello.j23n.com/pass-import-1pux)**: a tool to import 1password .1pux files.

### Generators

* **[pass-genphrase](https://github.com/congma/pass-genphrase) ⭐ 30 | 🐛 2 | 🌐 Shell | 📅 2021-08-12**: Passphrase generator extension for pass, the password manager.
* **[pass-ssh](https://github.com/ibizaman/pass-ssh) ⭐ 16 | 🐛 2 | 🌐 Shell | 📅 2021-12-19**: A pass extension that lets you quickly create ssh keypairs and output public keys using fzf or rofi.
* **[pass-qr](https://github.com/codekoala/pass-qr) ⭐ 7 | 🐛 1 | 🌐 Shell | 📅 2022-06-08**: A pass extension that lets you quickly generate a QR code for passwords using fzf or rofi.
* **[pass-totp](https://github.com/muteor/pass-totp) ⭐ 3 | 🐛 0 | 🌐 Go | 📅 2017-03-25**: TOTP code generator for pass.
* **[pass-gen](https://passgen.codesections.com/)**: A command-line utility that generates secure, pronounceable passphrases for pass. *(It won't add a new pass command but can be used seamlessly with pass.)*
* **[pass-words](https://gitlab.com/entrez/pass-words)**: generate Diceware-style mnemonic passwords.

### All other extensions

* **[pass-otp](https://github.com/tadfisher/pass-otp) ⭐ 1,485 | 🐛 73 | 🌐 Shell | 📅 2025-08-09**: support for one-time-password (OTP) tokens.
* **[pass-tomb](https://github.com/roddhjav/pass-tomb) ⭐ 436 | 🐛 7 | 🌐 Shell | 📅 2026-04-07**: helps you to keep the whole tree of password encrypted inside a tomb.
* **[pass-update](https://github.com/roddhjav/pass-update) ⭐ 324 | 🐛 7 | 🌐 Shell | 📅 2025-08-16**: an easy flow for updating passwords.
* **[pass-keybase](https://github.com/mbauhardt/pass-keybase) ⭐ 47 | 🐛 1 | 🌐 Shell | 📅 2020-05-15**: A pass extension to re-encrypt and decrypt pass entries via keybase.
* **[pass-backup](https://github.com/8go/pass-backup) ⭐ 17 | 🐛 2 | 🌐 Shell | 📅 2021-10-12**: makes making a time-stamped backup simple and easy.
* **[pass-grave](https://github.com/8go/pass-grave) ⭐ 17 | 🐛 0 | 🌐 Shell | 📅 2021-09-11**: helps you hide all meta-data by placing the whole tree of passwords inside an encrypted grave (like pass-tomb but simpler and more lightweight).
* **[pass-ln](https://github.com/raxod502/pass-ln) ⭐ 16 | 🐛 2 | 🌐 Shell | 📅 2025-11-22**: A pass extension for creating symbolic links.
* **[pass-botp](https://github.com/msmol/pass-botp) ⭐ 9 | 🐛 0 | 🌐 Shell | 📅 2017-08-10**: A pass extension for managing TOTP Backup Codes.
* **[pass-mount](https://github.com/HXR/pass-mount) ⭐ 9 | 🐛 1 | 🌐 Shell | 📅 2023-07-19**: A pass extension for mounting encrypted filesystems.
* **[pass-index](https://github.com/sboesebeck/pass-index.git) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2026-02-23**: Speed up content search
* **[pass-ssh](https://github.com/not-jan/pass-ssh) ⭐ 3 | 🐛 1 | 🌐 Shell | 📅 2022-01-31**: Automatically create an SSH session from a pass entry
* **[pass-extension-inc](https://github.com/diginatu/pass-extension-inc) ⭐ 2 | 🐛 0 | 🌐 Shell | 📅 2019-01-13**: A unix pass extension for incremental search.
* **[pass-open-doc](https://github.com/bergercookie/pass-open-doc) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2022-04-15**: Open a file from your Password Store via xdg
* **[pass-coffin](https://sr.ht/~ayushnix/pass-coffin)**: hide data inside a signed and encrypted coffin

## Interfaces

* **[Pass for iOS](https://github.com/mssun/passforios) ⭐ 1,645 | 🐛 175 | 🌐 Swift | 📅 2026-08-19**: An iOS client.
* **[passforios](https://github.com/mssun/passforios) ⭐ 1,645 | 🐛 175 | 🌐 Swift | 📅 2026-08-19**: Pass for iOS - an iOS client compatible with Pass command line application.
* **[passff](https://github.com/passff/passff) ⭐ 1,291 | 🐛 14 | 🌐 JavaScript | 📅 2026-08-26**: zx2c4 pass manager extension for Firefox, Chrome and Opera.
* **[browserpass](https://github.com/browserpass/browserpass-extension) ⭐ 1,012 | 🐛 44 | 🌐 JavaScript | 📅 2026-08-10**: Chrome & Firefox browser extension for pass.
* **[ripasso](https://github.com/cortex/ripasso) ⭐ 827 | 🐛 31 | 🌐 Rust | 📅 2026-07-27**: A simple password manager written in Rust.
* **[Android-Password-Store](https://github.com/agrahn/Android-Password-Store) ⭐ 438 | 🐛 30 | 🌐 Kotlin | 📅 2026-08-27**: Android application compatible with ZX2C4's Pass command line application.
* **[pass-winmenu](https://github.com/geluk/pass-winmenu) ⭐ 422 | 🐛 14 | 🌐 C# | 📅 2026-08-18**: An easy-to-use Windows interface for pass
* **[pass-git-helper](https://github.com/languitar/pass-git-helper) ⭐ 372 | 🐛 1 | 🌐 Python | 📅 2026-08-26**: A git credential helper interfacing with pass.
* **[prs](https://github.com/timvisee/prs) ⭐ 262 | 🐛 14 | 🌐 Rust | 📅 2026-05-08**: A multi-platform pass client in Rust supporting sync, TOTP, Tombs and more.
* **[gopass](https://github.com/cortex/gopass) ⚠️ Archived**: Simple UI for password-store. (UNMAINTANED)
* **[pass.el](https://github.com/NicolasPetton/pass) ⭐ 198 | 🐛 8 | 🌐 Emacs Lisp | 📅 2026-02-14** A major mode for password-store.
* **[Pass4Win](https://github.com/mbos/Pass4Win) ⚠️ Archived**: An interface for Windows. (inactive)
* **[pass\_rlded](https://github.com/bergercookie/awesome-albert-plugins/tree/master/plugins/pass_rlded) ⚠️ Archived**: [Albert](https://github.com/albertlauncher/albert) ⭐ 7,982 | 🐛 6 | 🌐 C++ | 📅 2026-08-23 integration
* **[upass](https://github.com/Kwpolska/upass) ⚠️ Archived**: Console UI for pass.
* **[Pass for macOS](https://github.com/adur1990/Pass-for-macOS) ⭐ 121 | 🐛 6 | 🌐 Swift | 📅 2021-10-26** macOS wrapper and Safari extension.
* **[gnome-pass-search-provider](https://github.com/jle64/gnome-pass-search-provider) ⭐ 97 | 🐛 0 | 🌐 Python | 📅 2026-04-19**: Pass password manager search provider for gnome-shell.
* **[alfred-pass](https://github.com/CGenie/alfred-pass) ⭐ 89 | 🐛 10 | 🌐 Python | 📅 2022-08-09**: Alfred integration
* **[pass-secret-service](https://github.com/grimsteel/pass-secret-service) ⭐ 77 | 🐛 6 | 🌐 Rust | 📅 2026-07-03**: Implementation of org.freedesktop.secrets (D-Bus Secret Service) using pass.
* **[pass-alfred](https://github.com/MatthewWest/pass-alfred) ⭐ 63 | 🐛 2 | 🌐 Python | 📅 2019-01-28**: Alfred integration
* **[krunner-pass](https://github.com/akermu/krunner-pass) ⭐ 38 | 🐛 5 | 🌐 C++ | 📅 2024-04-24**: Integrates krunner (KDE) with pass.
* **[PassHUD](https://github.com/mnussbaum/PassHUD) ⭐ 36 | 🐛 2 | 🌐 Swift | 📅 2019-02-23**: A HUD-style interface for pass on macOS.
* **[passwordstore-menu.el](https://github.com/rjekker/password-store-menu) ⭐ 28 | 🐛 0 | 🌐 Emacs Lisp | 📅 2026-04-23**: Emacs password-store with friendly user interface.
* **[tmux-pass](https://github.com/rafi/tmux-pass) ⭐ 23 | 🐛 3 | 🌐 Shell | 📅 2025-05-21**: Quick password-store browser with preview using fzf in tmux.
* **[rofi-pass-wayland](https://github.com/Seme4eg/rofi-pass-wayland) ⭐ 20 | 🐛 2 | 🌐 Shell | 📅 2026-01-12**: Rofi frontent for ZX2C4 pass project (wayland only).
* **[gopass-tui](https://github.com/leitzler/gopass-tui) ⭐ 18 | 🐛 0 | 🌐 Go | 📅 2018-01-05**: Terminal UI for pass/gopass.
* **[alfred-pass](https://github.com/chrisgrieser/alfred-pass) ⭐ 17 | 🐛 0 | 🌐 JavaScript | 📅 2026-08-03**: Feature-rich Alfred integration.
* **[Identities](https://github.com/k8ieone/identities) ⭐ 15 | 🐛 23 | 🌐 Python | 📅 2026-07-15**: Modern password-store client made for GNOME.
* **[pass-ulauncher](https://github.com/yannishuber/pass-ulauncher) ⭐ 15 | 🐛 7 | 🌐 Python | 📅 2019-11-12**: Integration for [Ulauncher](https://ulauncher.io/).
* **[gopass-secret-service](https://github.com/nikicat/gopass-secret-service) ⭐ 13 | 🐛 0 | 🌐 Go | 📅 2026-07-15**: D-Bus [Secret Service](https://specifications.freedesktop.org/secret-service/latest/) provider backed by gopass, so desktop apps (browsers, Electron apps, NetworkManager) store their secrets in the password store.
* **[pass-zsh-completion](https://github.com/ninrod/pass-zsh-completion) ⭐ 10 | 🐛 2 | 🌐 Shell | 📅 2022-01-16**: pass zsh completion plugin.
* **[pext\_module\_pass](https://github.com/Pext/pext_module_pass) ⚠️ Archived**: Password management module for Pext.
* **[parcel](https://github.com/parcel-pm/parcel) ⭐ 7 | 🐛 8 | 🌐 JavaScript | 📅 2026-08-24**: [Chrome](https://chromewebstore.google.com/detail/parcel/ciifpadakeohfnnneflckhojbldkkllp) & [Firefox](https://addons.mozilla.org/en-GB/firefox/addon/parcel-pm/) browser extension with no external dependencies.
* **[passman](https://github.com/TheAmazingPT/passman) ⭐ 5 | 🐛 0 | 🌐 Shell | 📅 2018-10-15**: A [dmenu](https://tools.suckless.org/dmenu/) frontend for password-store.
* **[vim-password-store](https://github.com/fourjay/vim-password-store) ⭐ 5 | 🐛 1 | 🌐 Vim script | 📅 2019-04-07**: Vim niceties for password store.
* **[NativePass](https://github.com/li-nd/NativePass) ⭐ 3 | 🐛 7 | 🌐 Swift | 📅 2026-08-24**: Native SwiftUI GUI for the Unix password manager pass on macOS.
* **[pidgin-zx2c4-pass](https://github.com/denimor/pidgin-zx2c4-pass) ⭐ 3 | 🐛 0 | 🌐 C | 📅 2017-03-29**: Plugin that allows to use zx2c4 pass to store passwords (for [pidgin](https://pidgin.im/)).
* **[ob-pass-menu](https://github.com/denimor/ob-pass-menu) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2017-08-16**: [Openbox](http://openbox.org/wiki/Main_Page) pipe-menu script that generates an xml menu based on zx2c4-pass storage.
* **[instantpass](https://github.com/instantos/instantpass) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2025-05-26**: an [instantmenu](https://github.com/instantOS/instantMENU) ⭐ 20 | 🐛 5 | 🌐 Rust | 📅 2026-08-25 frontend with support for pass-opt and pass-file.
* **[awscli-plugin-passtotp](https://github.com/someone-stole-my-name/awscli-plugin-passtotp)**: AWS CLI plugin to directly talk to pass for OATH-TOTP keys.
* **[pass-awscli](https://gitlab.com/mjsir911/pass-awscli)**:  AWS CLI credential integration
* **[pass-companion](https://github.com/kakolisgay/pass-companion)**: Chrome/Chromium browser extension for pass.
* **[pass-simple](https://sourceforge.net/projects/pass-simple/)**: Pass-simple is a multi-platform GUI.
* **[pass-zenity](https://codeberg.org/morus/pass-zenity/)**: A zenity front for pass.
* **[pass.applescript](https://git.zx2c4.com/password-store/tree/contrib/pass.applescript)**: OS X integration
* **[passbar](https://gitlab.com/rperce/passbar)** Password Store integration for awesomewm.
* **[passmenu](https://git.zx2c4.com/password-store/tree/contrib/dmenu)**: Another [dmenu](https://tools.suckless.org/dmenu/)-based interface.
* **[passwordstore.el](https://git.zx2c4.com/password-store/tree/contrib/emacs)**: Emacs password-store.
* **[passwordstore](https://docs.ansible.com/ansible/latest/plugins/lookup/passwordstore.html)**: Ansible lookup plugin to manage passwords with password-store.
* **[qtpass](https://qtpass.org/)**: QtPass is a multi-platform GUI.
* **[rofi-pass](https://git.sr.ht/~mcepl/rofi-pass)**: A bash script to handle Simple Password Store in a convenient way using rofi.
* **[tessen](https://git.sr.ht/~ayushnix/tessen)**: an interactive menu to autotype and copy pass and gopass data.
* **[XMonad.Prompt.Pass](https://hackage.haskell.org/package/xmonad-contrib-0.13/docs/XMonad-Prompt-Pass.html)**: This module provides 3 XMonad.Prompt to ease passwords manipulation.

## Import scripts

These scripts are not extensions but they can be very useful nontheless.

* **[firefox\_decrypt](https://github.com/Unode/firefox_decrypt) ⭐ 2,474 | 🐛 1 | 🌐 Python | 📅 2026-08-25**: Full blown Firefox password interface which supports exporting to pass
* **[1password2pass.rb](https://git.zx2c4.com/password-store/tree/contrib/importers/1password2pass.rb)**: Import 1Password txt or 1pif data
* **[fpm2pass.pl:](https://git.zx2c4.com/password-store/tree/contrib/importers/fpm2pass.pl)**: Import Figaro's Password Manager XML data
* **[gorilla2pass.rb](https://git.zx2c4.com/password-store/tree/contrib/importers/gorilla2pass.rb)**: Import Password Gorilla data
* **[kedpm2pass.py](https://git.zx2c4.com/password-store/tree/contrib/importers/kedpm2pass.py)**: Import Ked Password Manager data
* **[keepass2csv2pass.py](https://git.zx2c4.com/password-store/tree/contrib/importers/keepass2csv2pass.py)**: Import Keepass2 CSV data
* **[keepass2pass.py](https://git.zx2c4.com/password-store/tree/contrib/importers/keepass2pass.py)**: Import Keepass2 XML data
* **[keepassx2pass.py](https://git.zx2c4.com/password-store/tree/contrib/importers/keepassx2pass.py)**: Import KeepassX XML data
* **[kwallet2pass.py](https://git.zx2c4.com/password-store/tree/contrib/importers/kwallet2pass.py)**: Import KWallet data
* **[lastpass2pass.rb](https://git.zx2c4.com/password-store/tree/contrib/importers/lastpass2pass.rb)**: Import Lastpass CSV data
* **[password-exporter2pass.py](https://git.zx2c4.com/password-store/tree/contrib/importers/password-exporter2pass.py)**: Import password-exporter data
* **[pwsafe2pass.py](https://git.zx2c4.com/password-store/tree/contrib/importers/pwsafe2pass.py)**: Import PWSafe data (python version)
* **[pwsafe2pass.sh](https://git.zx2c4.com/password-store/tree/contrib/importers/pwsafe2pass.sh)**: Import PWSafe data
* **[revelation2pass.py](https://git.zx2c4.com/password-store/tree/contrib/importers/revelation2pass.py)**: Import Revelation Password Manager data
* **[roboform2pass.rb](https://git.zx2c4.com/password-store/tree/contrib/importers/roboform2pass.rb)**: Import Roboform data

## Export scripts

* **[pass-export](https://github.com/dvogt23/pass-export) ⭐ 11 | 🐛 1 | 🌐 Shell | 📅 2021-01-21**: Exports data in csv format

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-27._
