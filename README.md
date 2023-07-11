# ppa
PPA for libboost-dev for MinGW-w64 and glspeaks for Debian-based distros

```bash
wget https://github.com/silkskier/ppa/releases/download/main/B5328C753BB19FDE511F2BCCD0761D1C9CB7AEE3.asc
gpg --dearmor ./B5328C753BB19FDE511F2BCCD0761D1C9CB7AEE3.asc | sudo tee /usr/share/keyrings/silkskier-ppa-archive-keyring.gpg > /dev/null
rm ./B5328C753BB19FDE511F2BCCD0761D1C9CB7AEE3.asc
echo "deb [signed-by=/usr/share/keyrings/silkskier-ppa-archive-keyring.gpg] https://silkskier.github.io/ppa ./" | sudo tee /etc/apt/sources.list.d/silkskier-ppa.list > /dev/null
```
