# Tuned-Colors-TotK
Tuned Colors vkBasalt Tears of the Kingdom

[Comparison 1](https://imgsli.com/MTgwNDY4)

[Comparison 2](https://imgsli.com/MTgwNDcw)

[Comparison 3](https://imgsli.com/MTgwNDcx)

[Comparison 4](https://imgsli.com/MTgwNDcy)

[Comparison 5](https://imgsli.com/MTgwNDcz)

[Comparison 6](https://imgsli.com/MTgwNDc0)

Obviously with Linux, you'll need vkBasalt installed, figure this out for your distro, I'm not helping you there. Secondly, you'll need to know how to enable vkBasalt for whatever emulator you're using, doesn't really matter which one, it should apply to any and all, as always [documentation is your friend](https://github.com/DadSchoorse/vkBasalt). 

Once you have those two basic things handled, download the zip, and you'll want to go to ~/.config, and likely will need to create the vkBasalt folder, if it exists, just extract it there, if not, extract it there after creating it.

After it's extracted, you'll want to edit the vkBasalt.conf, and swap out the word "user" for whatever your username is, basically so it points to the correct folder. 

Launch yuzu/Ryujinx/whatever, and launch the game with either, and so long as you're running something that uses vulkan, the preset will just work. 

To clarify, yes, you should be able to use this preset with anything ultimately, so long as it uses vulkan as the renderer, it'll work as long as vkBasalt is enabled on the process, this includes everything from steam games to opengl games running through zink for example, this preset just happens to be geared towards TotK.
