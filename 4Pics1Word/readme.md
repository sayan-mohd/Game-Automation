# Automate 4 Pics 1 Word Game

**The code shared is certainly not production-ready and provided only as a concept. Code works only on Samsung A7 mobile as the resolutions and coordinates are hardcoded**

#### Demo 

https://www.youtube.com/watch?v=DlCZiAS-50o

#### Resources

[scrcpy](https://github.com/Genymobile/scrcpy) : Control Android device through USB

[Google ngram](https://storage.googleapis.com/books/ngrams/books/datasetsv3.html) : Download word frequency from Google. Definitely worth checking for more information

[Android ADB](https://developer.android.com/studio/command-line/adb) : If you already have Android Studio with SDK installed then probably you will probably have ADB tools also. If not, you can download CLI tools alone. _You can skip this step if scrcpy works without installing ADB CLI tools_

#### Files
1. words_with_freq.txt : I have compiled this list by taking only the word ranges (3-9 words) available in 4Pics1Word and NSFW words removed

#### Python Packages
1. [Pillow](https://pillow.readthedocs.io/en/stable/)
2. [Python-tesseract](https://pypi.org/project/pytesseract/)
3. [NumPy](https://pypi.org/project/numpy/)
4. [Pure Python ADB](https://pypi.org/project/pure-python-adb/)
