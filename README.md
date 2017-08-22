# Send micro-input voice to Facebook Messenger.
The microphone outputs the speech recognition result as text and sends it 
to the specified Facebook account.  
Speech recognition used Google Cloud Platform (GCP) example code.
This is a part where costs are incurred.

## Prerequisite

Authentication
```bash
$ pip install fbchat
$ pip install google-cloud-speech
$ pip install --global-option='build_ext' --global-option='-I/usr/local/include' --global-option='-L/usr/local/lib' pyaudio
```

Install Dependencies
```bash
$ gcloud auth application-default login
```

## Usage
Fix your Facebook ID and password in the #FIXME section.
```bash
$ python msg_to_fb.py
```

## License
[MIT](LICENSE)
