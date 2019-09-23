# PYTHON-INSTALLATION-AND-KIVY-INSTALLATION-STEPS
-------------------------------------------------
HOW TO INSTALL PYTHON 3
-----------------------

1)	Open the following link ( https://www.python.org ) 

2)	 Select the Downloads. 

3)	Download the latest version of python 

4)	Install the downloaded .exe file. *NOTE  DON’T forget to click add to PATH OPTION WHILE INSTALLING.

5)	After Installation open cmd .

6)	Type pip –version  It will show the current version of pip and python that is installed in your system.

HOW TO INSTALL KIVY IN YOUR WINDOWS MATCHINE
--------------------------------------------

1)	Open the following link (https://kivy.org/#download) and select your machine. For windows click in the INSTALLATION ON WINDOWS. OR ELSE YOU CAN FOLLOW THE FOLLWING STEPS TO INSTALL KIVY IN YOUR MATCHINE.

2)	OPEN CMD.

3)	Copy and paste the following command to Ensure you have the latest pip, wheel, and virtualenv .If not there it will install the latest version.

   python -m pip install --upgrade pip wheel setuptools virtualenvpython

OPTIONAL STEPS 4 & 5

4)	First create the environment named kivy_venv in your current directory:

 python -m virtualenv kivy_venv

5)	Activate the virtual environment. You’ll have to do this step from the current directory every time you start a new terminal. On windows CMD do:

 kivy_venv\Scripts\activate

MENDITORY STEPS 

6)	Install the dependencies (skip gstreamer (~120MB) if not needed, see Kivy’s dependencies). If you are upgrading Kivy, see Updating Kivy from a previous release:

 python -m pip install docutils pygments pypiwin32 kivy_deps.sdl2==0.1.22 kivy_deps.glew==0.1.12

 python -m pip install kivy_deps.gstreamer==0.1.17

7)	Note
If you encounter a MemoryError while installing, add after pip install the –no-cache-dir option.
For Python 3.5+, you can also use the angle backend instead of glew. This can be installed with:
 
 	python -m pip install kivy_deps.angle==0.1.9
8)	Install KIVY : 

  python -m pip install kivy==1.11.1

9)	There are 3  Kivy Dependencies :
 9.1) getstreamer  for audio and video.
 9.2) glew 
 9.3) sdl2 for control and OpenGL.

10)	Both the python and the Python\Scripts directories must be on the path. They must be on the path every time you recompile kivy.

11)	Ensure you have the latest pip and wheel with :

 python -m pip install --upgrade pip wheel setuptools

12)	Set the environment variables. On windows do:

  set USE_SDL2=1

 set USE_GSTREAMER=1

13)	Install the other dependencies as well as their dev versions (you can skip gstreamer and gstreamer_dev if you aren’t going to use video/audio). we don’t pin the versions of the dependencies like for the stable kivy because we want the latest:

 python -m pip install Cython==0.29.10 docutils pygments pypiwin32 kivy_deps.sdl2 kivy_deps.glew kivy_deps.gstreamer kivy_deps.glew_dev kivy_deps.sdl2_dev kivy_deps.gstreamer_dev

14)	Start installation of Kivy cloned or downloaded and extracted from GitHub. You should be in the root directory where kivy is extracted containing the setup.py file:
 python -m pip install

15)	For Any Quarry, refer 

 https://kivy.org/doc/stable/installation/installation-windows.html

16)	Python Documentation Link 

 https://docs.python.org/3/tutorial/index.html

17)	Kivy PYPI Link 

 https://pypi.org/project/Kivy/
