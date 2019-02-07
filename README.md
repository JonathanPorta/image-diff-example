# OpenCV

First, I installed it globally using some instructions I found online.

Then, I manually symlinked it into the local env:
`ln -s /usr/local/opt/opencv@3/lib/python3.6/site-packages/cv2.cpython-36m-darwin.so ./env/lib/python3.6/site-packages/`

```
(env) ➜  image_diff python
Python 3.6.5 (default, Apr 25 2018, 14:23:58)
[GCC 4.2.1 Compatible Apple LLVM 9.1.0 (clang-902.0.39.1)] on darwin
Type "help", "copyright", "credits" or "license" for more information.
>>> import cv2
>>> cv2.__version__
'3.4.1'
```

# Diffing

I followed this tutorial to get started: https://www.pyimagesearch.com/2017/06/19/image-difference-with-opencv-and-python/
