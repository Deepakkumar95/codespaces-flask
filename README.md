##End to End ML Project

#Created a new environment:

~~~
conda create -p venv python==3.8

conda activate venv/

~~~

##Install all necessary library in requirements.txt

~~~
pip install -r requirements.txt
~~~

##Run requirements.py 
~~~
python requirements.py
~~~


##Run setup.py independently
~~~
python setup.py install
~~~

##check the list of file in current directory

ls -a

#Forcefully remove the other origin
~~~
git remote rm origin
git status
git add  .
git commit -m "First Commit"
git push -u origin main
~~~