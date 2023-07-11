# ppa
PPA for libboost-dev for MinGW-w64 and glspeaks for Debian-based distros

```bash
curl -s --compressed https://silkskier.github.io/ppa/KEY.gpg | gpg --dearmor | sudo tee /usr/share/keyrings/silkskier-ppa-archive-keyring.gpg > /dev/null
echo "deb [signed-by=/usr/share/keyrings/silkskier-ppa-archive-keyring.gpg] https://silkskier.github.io/ppa ./" | sudo tee /etc/apt/sources.list.d/silkskier-ppa.list > /dev/null
```
