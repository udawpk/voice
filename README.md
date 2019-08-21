# voice_assistant
### To install on Python 3.6 
please install requirements from requirements.txt
```bash
pip install -r requirements.txt
```

### Install RHVoice on Ubuntu 16.04 - 18.04
```bash
sudo apt -y update && sudo apt -y upgrade
sudo apt install gcc g++ git pkg-config scons libao4 libao-common libao-dev
cd /usr/src/
sudo git clone https://github.com/Olga-Yakovleva/RHVoice
cd RHVoice/
sudo scons
sudo scons install
sudo ldconfig
echo "test" | RHVoice-test
```
