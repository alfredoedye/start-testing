install:
	echo "⚠️  Assuming you have Python, pip and brew installed..."
	pip install robotframework
	pip install robotframework-seleniumlibrary
	pip install robotframework-requests
	brew cask install chromedriver
	brew cask install geckodriver

clean:
	rm -rf Results
	mkdir Results

test: clean
	# robot -d Results Tests
	robot -d Results Tests/AmazonRefactored.robot
