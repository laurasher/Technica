# Technica
Hack for Technica 2016

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
