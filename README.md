First Friday Hackathon - March 7, 2014
--------------------------------------

Part two of Missle Defense is tracking a target.  
I went through some of the OpenCV tutorials.  The most interesting
one was meanshift.  It tracks a target by looking at the area with the most
points and then it targets that.  It works best in a well light area with a plain
background.

[Tutorials on OpenCV project site](http://docs.opencv.org/trunk/doc/py_tutorials/py_tutorials.html)

## Requirements

- Pip
- Virtual Env
- Homebrew


## How to Build

```
brew install opencv --version=2.4.8.2
virtualenv tracking
cd tracking
pip install -r requirements.txt
```