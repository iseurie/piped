# Applying simplicity

The premise of `piped` is that while Electron is fairly portable to all PC architectures and user frontends which maintain a host environment capable of supporting a browser, not everybody wants or needs such a thing in a machine, especially one with weak hardware capabilities -- think of something like a raspberry pi. Even if your computer hardware is on par with the industry standard in desktop computing, it's sometimes more desirable to adopt a solely textual mode of operation; one example of this would be when you shell into a machine remotely. 

In these contexts, the remote use-case in particular, it's less serviceable to have a GUI. And yet you may occasionally still find yourself want to put word into or follow discussion, despite that integrated solutions for your chosen instant-messenging platform are lackluster in a number of areas; usability, configurability, and their editing capacities, to name a few.

## The UNIX Solution

To account for these contingencies, we propose an application built on the minimalist, modular design philosophy of UNIX, the favored tool of those invested in minimizing their processor cycles and round-trips. `piped`: A `d`iscord client, which you correspond on a per-channel basis, by using a simple selector GUI to choose a singular channel from some guild or DM and simply.. opening a pipe. One in, through which your messages are sent, once per FD write; one out. The pipe is named, so you can open each of them in any editor you so choose, effortlessly. 

## Just `|`.

And in true UNIX fashion, all limitations on how you apply these principles fall away. Swap your GUI. Swap out your GUI's syntax highlighting. It's all the same to the oldest, most flexible technology in computing. Pipes. No more, no less. Use your editor's native markdown support and all the techniques to which you're accustomed to display or edit prose, no questions asked, no holds barred. Just `|`.
