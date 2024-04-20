# freecode


this is the link for download : 

https://sfl.gl/jeayask

installation :

Make sure you have installed python (version >= 3.7) in your pc first. Run the following line in the terminal to install musicpy by pip.

pip install musicpy
Note 1: On Linux, you need to make sure the installed pygame version is older than 2.0.3, otherwise the play function of musicpy won't work properly, this is due to an existing bug with newer versions of pygame. You can run pip install pygame==2.0.2 in terminal to install pygame 2.0.2 or any version that is older than 2.0.3. You also need to install freepats to make the play function works on Linux, you can run sudo apt-get install freepats (on Ubuntu).

Note 2: If you cannot hear any sound when running the play function, this is because some IDE won't wait till the pygame's playback ends, they will stops the whole process after all of the code are executed without waiting for the playback. You can set wait=True in the parameter of the play function, which will block the function till the playback ends, so you can hear the sounds.

In addition, I also wrote a musicpy editor for writing and compiling musicpy code more easily than regular python IDE with real-time automatic compilation and execution, there are some syntactic sugar and you can listen to the music generating from your musicpy code on the fly, it is more convenient and interactive. I strongly recommend to use this musicpy editor to write musicpy code. You can download this musicpy editor at the repository musicpy_editor, the preparation steps are in the README.

Musicpy is all compatible with Windows, macOS and Linux.

Musicpy now also supports reading and writing musicxml files, note that you need to install partitura to use the functionality by pip install partitura.
