# ppa
PPA for libboost-dev for MinGW-w64 and glspeaks for Debian-based distros


## Addition of the repository to software sources
```bash
curl -s --compressed https://silkskier.github.io/ppa/KEY.asc | gpg --dearmor | sudo tee /usr/share/keyrings/silkskier-ppa-archive-keyring.gpg > /dev/null
echo "deb [signed-by=/usr/share/keyrings/silkskier-ppa-archive-keyring.gpg] https://silkskier.github.io/ppa ./" | sudo tee /etc/apt/sources.list.d/silkskier-ppa.list > /dev/null
```
### Software installation
#### [libboost-dev](https://www.boost.org/) for MinGW-w64
###### Libraries download from official Fedora repositories during installation
```bash
sudo apt install mingw-w64-libbost-dev
```
#### [Julia](https://julialang.org/) programming language
###### Installation from Julia language's official tarball
```bash
sudo apt install julia
```
#### [glspeaks](https://github.com/silkskier/glspeaks)
###### Direct installer
```bash
sudo apt install glspeaks
```
