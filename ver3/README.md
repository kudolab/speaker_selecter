# speaker_selecter ver3


## usage

```
$ curl http://172.24.184.114/health
```
```
$ curl -X PUT -H "Content-Type: application/json" -d '{"speaker_num":5}' 172.24.184.114/speaker
```
```
$ curl http://172.24.184.114/speaker
```


## setup

```
$ cd ~
$ git clone https://github.com/kudolab/speaker_selecter.git
```



```

$ python3 -m venv venv
$ . ./venv/bin/activate
$ pip3 install -r requirements.txt
```
```
# Library version used in ver3
$ pip3 install RPi.GPIO==0.7.1 Flask==2.2.2 tomli==2.0.1
```

comments
```
cd ~/speaker_selecter/ver3

# for run
python3 -m venv venv
. ./venv/bin/activate
(venv) : 
pip3 install -r requirement.txt

# if Permission denied
chmod a+x app.py
chmod a+x /home/pi/speaker_selecter/ver3/venv/bin
# for systemd

```


