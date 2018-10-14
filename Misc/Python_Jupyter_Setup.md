# Python

Step 1: By default, Python 2 is installed on Apple computers. Confirm your Python version using Terminal using:

```
$ python --version
Python 2.7.10
```

Step 2: Check if Python 3 is already installed: 

```
$ python3 --version
```

Step 3: If you don't have Python 3, or if your Python 3 is not the most updated version, we will install it using Homebrew. Install it using:

```
$ xcode-select --install
$ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
          Check if Homebrew is installed successfully:

$ brew --version
Homebrew 1.7.5
Homebrew/homebrew-core (git revision c44b; last commit 2018-09-20)
```

Step 4: Install Python 3

```
$ brew install python3
         Check if Python3 is installed successfully: 

$ python3 --version
Python 3.7.0
 
$ which python3
/usr/local/bin/python3
```
