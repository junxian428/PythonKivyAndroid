# PythonKivyAndroid

First Sample Kivy Program


nano main.py


from kivy.app import App

class MainApp(App):
   pass

MainApp().run()



Execution:


python3 main.py

[INFO   ] [Logger      ] Record log in /home/pi/.kivy/logs/kivy_21-01-07_0.txt
[INFO   ] [Kivy        ] v2.0.0
[INFO   ] [Kivy        ] Installed at "/usr/local/lib/python3.7/dist-packages/kivy/__init__.py"
[INFO   ] [Python      ] v3.7.3 (default, Apr  3 2019, 05:39:12) 
[GCC 8.2.0]
[INFO   ] [Python      ] Interpreter at "/usr/bin/python3"
[INFO   ] [Factory     ] 186 symbols loaded
[INFO   ] [ImageLoaderFFPy] Using ffpyplayer 4.3.2
[INFO   ] [Image       ] Providers: img_tex, img_dds, img_sdl2, img_pil, img_ffpyplayer 
[INFO   ] [Window      ] Provider: sdl2(['window_egl_rpi'] ignored)
[INFO   ] [GL          ] Using the "OpenGL" graphics system
[INFO   ] [GL          ] Backend used <sdl2>
[INFO   ] [GL          ] OpenGL version <b'3.1 Mesa 19.2.0-rc1'>
[INFO   ] [GL          ] OpenGL vendor <b'VMware, Inc.'>
[INFO   ] [GL          ] OpenGL renderer <b'llvmpipe (LLVM 8.0, 128 bits)'>
[INFO   ] [GL          ] OpenGL parsed version: 3, 1
[INFO   ] [GL          ] Shading version <b'1.40'>
[INFO   ] [GL          ] Texture max size <8192>
[INFO   ] [GL          ] Texture max units <32>
[INFO   ] [Window      ] auto add sdl2 input provider
[INFO   ] [Window      ] virtual keyboard not allowed, single mode, not docked
[INFO   ] [Base        ] Start application main loop
[INFO   ] [Base        ] Leaving application in progress...




Deploying
---------------------------------------------------------
buildozer init

edit



title = Hello World
package.name = helloworld
source.include_exts = py,png,jpg,kv,atlas,txt
android.logcat_filters = *:S python:D



///////////
sudo apt install -y git zip openjdk-8-jdk autoconf libtool pkg-config zlib1g-dev libncurses5-dev libncursesw5-dev libtinfo5 cmake libffi-dev
pip3 install --user --upgrade cython virtualenv
sudo apt-get install cython 
buildozer android debug deploy run



Learning Resources:
1. https://youtu.be/9JH8r8mz0g4
2. https://youtu.be/EupAeyL8zAo
