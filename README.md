# DecompilerDemon
An app which automates the process of the infamous dnSpy DLL Hijacking Exploit. Main features:

- Force a Blue Screen of Death when attempted to decompile your file.
- Open a Jumpscare when attempted to decompile your file.
- Open many messageboxes with threats of your PC getting fucked, scaring the average skid.

## How it Works
This lets you insert your file, then, when clicked the protect button, will move the runtime protections to the same directory your file is in.
Then it will rename the runtime to Microsoft.DiaSymReader.Native.amd64.dll which is needed for the dll hijacking process.

## Credits
[Washi](https://blog.washi.dev/posts/popping-calcs-in-dnspy/) - Discovering the DLL Hijacking Exploit, along with [Ellie](https://github.com/Elliesaur)
