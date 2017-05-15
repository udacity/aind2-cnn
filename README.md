# aind2-cnn

### Instructions

1. Clone the repository and navigate to the downloaded folder.
	
	```	
		git clone https://github.com/udacity/aind2-cnn.git
		cd aind2-cnn
	```

2. Install the necessary Python packages.  If you are using a Mac, you need to pick only one of the two options below.

	For __Mac/OSX__ (Option 1):
	```
		pip3 install -r requirements/requirements.txt
		KERAS_BACKEND=tensorflow python -c "from keras import backend"
	```
	
	For __Mac/OSX__ (Option 2):
	```
		conda env create -f requirements/aind-dog-mac.yml
		source activate aind-dog
		KERAS_BACKEND=tensorflow python -c "from keras import backend"
	```

	For __Windows__:
	```
		conda env create -f requirements/aind-dog-windows.yml
		activate aind-dog
		set KERAS_BACKEND=tensorflow 
		python -c "from keras import backend"
	```
	
3. Enjoy!
