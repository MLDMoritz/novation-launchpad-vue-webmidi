# Novation Launchpad Vue Webmidi
A demo of a soundboard made with vuejs and webmidi using the novation launchpad mini mk3 as input device.

[Launch Demo](https://mldmoritz.github.io/novation-launchpad-vue-webmidi/index.html)

You should have your launchpad already plugged in before opening the demo.

# Sounds

![keys](https://user-images.githubusercontent.com/46711821/72685185-ced2cf80-3ae7-11ea-8e64-5c800f2fc5d4.png)

This is a representation of the note ids on the launchpad mini mk3.


The sounds are stored in the `sounds/` directory.
The first digit of the note ids in the image above represents the directory, the second digit the filename.

Ex. ID 45 would be directory `4` and in this directory a file named `5.mp3`.


## Play a sound

You can play sounds by pressing a button on the launchpad and keeping it pressed.
You can toggle play-along mode by pressing ⬇️ button (2nd, top left), this will play the complete sound on one press.

## Stop a playing sound

Press the Stop button and keep it pressed while pressing the playing sound button.