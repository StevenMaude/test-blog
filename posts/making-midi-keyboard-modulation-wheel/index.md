# Making a MIDI keyboard modulation wheel work with third-party VSTs in FL Studio


Been playing around with third-party VSTs in FL Studio and found I
couldn't get the modulation wheel to work (though it works fine in the
bundled plugins).

Eventually I found the fix
[here](http://music.tutsplus.com/tutorials/quick-tip-how-to-enable-the-mod-wheel-in-fl-studio--audio-10778).

The short version: add a third-party VST to your project. Go to the
browser menu and go to Current Project \> Generators \> Fruity Wrapper.
Next, you should see Modulation Wheel in the list under Fruity Wrapper;
right click it and choose "Link to controller". Enable Omni, make sure
Autodetect is enabled (it is by default for me), then move the wheel.

That link also suggests starting with an empty project, doing this
setup, then deleting the VST and saving the project as a template, which
is handy to avoid repeating this every time you work on a new project.
Just make a sub-directory in one of the existing FL Studio Templates
directories and save the .flp file in there.

