Website: https://karihug.github.io/


Setup: 
* Download `jemdoc.py` from [here](http://jemdoc.jaboc.net/download.html) and run `sudo cp jemdoc.py /usr/local/bin/jemdoc`. 
* Run `chmod +x jemdoc.py`.
* Make sure you have `virtualenv` installed (run `pip install virtualenv` if not). Run once: `virtualenv -p /usr/bin/python2.7 temp-python`. 
* To access the virtual environment, run `source temp-python/bin/activate`. To exit, run `deactivate`. 
* In the virtual environment, run `python jemdoc.py index.jemdoc` to update `index.html`. 


Useful links: http://www-personal.umich.edu/~wylguan/using-jemdoc.html
