# pygifconv_thj

## Table of Contents
  * [Installation](#installation)
  * [Quick start](#quick-start)
  * [Features](#features)
  
## Installation

Download using pip via pypi.

```bash
$ pip install 'package' --upgrade
  or
$ pip install git+'repository'
```
(Mac/homebrew users may need to use ``pip3``)


## Quick start
```python
 >>> from pygifconv_thj.converter import GIFConverter
 >>> c = GIFConverter("your original images path", 'your gif output path', (320,240))
 >>> c.convert()
```

## Features
  * Python library to convert single oder multiple frame gif images
  * OpenCV does not support gif images.