### Anshar-s-Cysec-Tools

### Setup :

I recommend create a virtual environment, because requests module sometimes problem in windows

#### Create virtual environment:

In linux :  
```
python3 -m venv environment_name
```

In windows / macOS :

```
python -m venv environment_name
```

Activate venv in linux terminal, macOS terminal and git bash:
```
source environment_name/Scripts/activate
```

Activate venv in cmd and powershell:
```
environment_name/Scripts/activate
```


#### Install module requirements :

```
pip install -r requirements.txt
```

# Information Gathering

How to use information gathering:

In linux :  
`python3 main.py [-h] [-v] [-D DICT] [-u URL] [-i {1,2,3}] [-gl]`

In windows / macOS :  
`python main.py [-h] [-v] [-D DICT] [-u URL] [-i {1,2,3}] [-gl]`

Example if u will use option 2 of information gathering :

```
python3 main.py -u facebook.com -i 2 -gl
```

should use -u <URL> or --url <URL> for add url or domain,  
and should use -i <YOUR_OPTION> or --information <YOUR_OPTION> for choose  
type of information gathering you want, there are options:

1. Ip Checker
2. Whois Checker
3. Admin Page Checker

options:  
 -h, --help show this help message and exit  
 -v, --version See version from Information Gathering  
 -D DICT, --dict DICT Add file dictionary txt  
 -u URL, --url URL Add url or domain  
 -i {1,2,3}, --information {1,2,3} Options for Information Gathering  
 -gl, --geoloc Add geo location each ipv4 address, this works if use information gathering number two

# Attack Analysis

I haven't add opt parse for this, so for run this file as usual:  
python3 file.py

# Malware

This malware using for learn malware behaviour and know how it is made.  
I haven't write good malware yet

For learn cyber security
