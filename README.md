# Technica
Hack for Technica 2016

####Natural Language Toolkit Trials

#####install NTLK
	sudo pip install -U nltk
#####install numpy
	sudo pip install -U numpy




####Python speech recognition example on Mac OXS

#####install home-brew
	http://docs.python-guide.org/en/latest/starting/install/osx/
	$ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
	cd  /etc
	sudo nano profile
	export PATH=/usr/local/bin:/usr/local/sbin:$PATH
#####install python
	brew install python
#####install pyaudio
	brew install portaudio && brew link portaudio
	pip install pyaudio
#####run example
	python -m speech_recognition
