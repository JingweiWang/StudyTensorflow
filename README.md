# StudyTensorflow

## Environment

### Python 3.+

```bash
$ brew install python3
```

#### if you have any error

[Troubleshooting](http://docs.brew.sh/Troubleshooting.html)

Follow these steps to fix common problems:
* Run `brew update` twice.
* Run `brew doctor` and fix all the warnings (**outdated Xcode/CLT and unbrewed dylibs are very likely to cause problems**).
* Check that **Command Line Tools for Xcode (CLT)** and **Xcode** are up to date.
* If commands fail with permissions errors, check the permissions of `/usr/local`’s subdirectories. If you’re unsure what to do, you can run `cd /usr/local && sudo chown -R $(whoami) bin etc include lib sbin share var Frameworks`.
* Read through the [Common Issues](http://docs.brew.sh/Common-Issues.html).
* If you’re installing something Java-related, make sure you have installed Java (you can run `brew cask install java`).


### tensorflow 1.+

```bash
$ pip3 install tensorflow
```

### test your installation

```bash
$ python3 TestInstallation.py
```
