# YARIX- Learning Diary

###　What are YARA rules?

YARA rules are used to classify and identify malware samples by creating descriptions of malware families based on textual or binary patterns.

### How to use YARA rules function?

YARA rules are like a piece of programming language, they work by defining a number of variables that contain patterns found in a sample of malware. If some or all of the conditions are met, depending on the rule, then it can be used to successfully identify a piece of malware.

### YARA rules contain these elements

- Metadata

- Strings 

- Conditions

- Imports

## How to install Yarix?
Click here to download Yarix on GitHub
https://github.com/Yara-Rules/rules

### Download Ubuntu

![Ubuntu](C:\Users\Tommy\Downloads\Ubuntu.png)

###　Preparation

```javascript
apt-get install cmake curl flex bison g++ gcc make python3 python3-dev python3-venv zlib1g zlib1g-dev wget
python3 -m venv YarIx
source YarIx/bin/activate
python3 -m pip install pip==21.0.1
make -C src/
pip install -r requirements.txt
```

![In(1)](C:\Users\Tommy\Downloads\In(1).png)

### Create an Index

```javascript
mkdir idx1
./buildindex -r samples1.txt -w idx1
```

### Merge Two Indexes

```javascript
./merge.py idx3 24 idx1 100000 idx2 100000
```

### How to collect malware
https://resources.infosecinstitute.com/topic/top-7-malware-sample-databases-and-datasets-for-research-and-training/
### Get the malware sample from VirusShare 

![In(3)](C:\Users\Tommy\Downloads\In(3).png)

![In(2)](C:\Users\Tommy\Downloads\In(2).png)

## Reference

https://ithelp.ithome.com.tw/articles/10209898

https://www.varonis.com/blog/yara-rules

https://amingosec.blog/yara-%E6%98%AF%E4%BB%80%E9%BA%BC%EF%BC%9F/

https://github.com/jeFF0Falltrades/yarix

https://blog.malwarebytes.com/security-world/technology/2017/09/explained-yara-rules/

https://www.usenix.org/conference/usenixsecurity21/presentation/brengel