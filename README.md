If your system is not "broken", you may be successful with this sequence:

1. sudo apt-get update 
2. sudo apt-get upgrade 
3. sudo apt-get install portaudio19-dev 
4. sudo pip install pyaudio

If your system still complains of broken packages and such, try this sequence:

1. sudo apt-get update 
2. sudo apt-get upgrade 
3. sudo apt-get dist-upgrade
4. sudo apt-get install portaudio19-dev 
5. sudo pip install pyaudio

!!important!! 

1.sudo apt-get install flac

after that
1. pip install SpeechRecognition

Note:
   1. python2  -> pip
   2. python3  -> pip3

***Windows*** 
   1.install swigwin




