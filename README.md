
# *Millie Multi-Device*

<div align="left">

## DEPLOY   
- Create an Account on Github if you don't have already
- Fork the Repo [Click Here](https://github.com/HMser/Millie-MD/fork)
- Scan QR by Clicking [Here](https://lizaqr.onrender.com)
- Copy this code and paste it on your vps shell<br>
```
    sudo apt -y update &&  sudo apt -y upgrade
  sudo apt -y install git ffmpeg curl
```  
```
curl -fsSl https://deb.nodesource.com/setup_lts.x | sudo bash - && sudo apt -y install nodejs
```
```
  curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -
  echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list
  sudo apt -y update && sudo apt -y install yarn
```
```
  sudo yarn global add pm2
```
```
  git clone https://github.com/HMser/Millie-MD
  cd Millie-MD
  yarn install --network-concurrency 1
```


</div>

  

