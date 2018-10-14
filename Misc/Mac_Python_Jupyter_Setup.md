# Python

**Step 1:** By default, Python 2 is installed on Apple computers. Confirm your Python version using Terminal using:

```
$ python --version
Python 2.7.10
```

We want to get the most updated version of Python. Check if Python 3 is already installed: 

```
$ python3 --version
```

**Step 2:** If you don't have Python 3, or if your Python 3 is not the most updated version, we will install it using Homebrew. Install it using:

```
$ xcode-select --install
$ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

Check if Homebrew is installed successfully:

```
$ brew --version
Homebrew 1.7.5
Homebrew/homebrew-core (git revision c44b; last commit 2018-09-20)
```

**Step 3:** Install Python 3

```
$ brew install python3
```

Check if Python3 is installed successfully: 

```
$ python3 --version
Python 3.7.0
 
$ which python3
/usr/local/bin/python3
```

# Jupyter Notebook, Jupyter Lab 

**Step 1:** Ensure that you have the latest pip; older versions may have trouble with some dependencies:

```
$ pip3 install --upgrade pip
```

**Step 2:** Install Jupyter Notebook using:

```
$ pip3 install jupyter
```

Check if Jupyter is installed successfully: 

```
$ jupyter --version
4.4.0
```

Open Jupyter Notebook:

```
$ jupyter notebook
```

**Step 3 (optional):** Install Jupyer Lab 

```
$ pip3 install jupyterlab
```

Open Jupyter Lab:

```
$ jupyter lab
```


