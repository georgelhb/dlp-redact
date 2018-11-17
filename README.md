#### The code shows how to use Cloud Data Loss Prevention API to redact sensitive information.
---
1) Install pip and virtualenv if you do not already have them: <br/>
```
https://pip.pypa.io/en/stable/
https://virtualenv.pypa.io/en/latest/
```
2) Create a virtualenv. Samples are compatible with Python 2.7 and 3.4+.: <br/>
```
$ virtualenv env
$ source env/bin/activate
```
3) Install the dependencies needed to run the samples: <br/>
```
$ pip install -r requirements.txt
```
4) Replace the PROJECT_ID and redact the sensitive information in the sample file using the DLP API: <br/>
```
python redact.py --project [PROJECT_ID] sample_1.png ./output_1.png
```
5) You should find the sensitive information has been redacted in the output_1.png. <br/>
