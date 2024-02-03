# How to download!

Download Git onto your computer.</br>
[Here](https://git-scm.com/downloads) is the link to download

open your command prompt (either your windows command prompt or the Git Bash one) in your minecraft mods pack file (I recommand [CurseForge](https://download.curseforge.com/))</br>
to change the file that the command prompt to be looking at run
(update the information to fit your directory)

```powershell
cd C:\Users\[user]\Twitch\Minecraft\Instances
```
>replace `[user]` with your username on the devies
>
>If you are using a different path, replace with the path of the minecraft instance is located

to download, run
```powershell
git clone https://github.com/ItsSforSamuel/ShortFilmMods.git
```
</br>
if you don't want to download a software to manage modpacks, still download this as instructed (altho the directory doesn't matter, when doing this), but then rip out the mod files and put them in the correct file

</br>
Side note, the server will let you in if you have an non official Minecraft account.
>i.e using a pirated client (not recommend and you can possibly download malware/spyware)
>The most well known spyware client is the non-legcy tlauncher (TL Legacy is the old one before being bought and is allegedly safe, but is strongly discouraged as it's piracy)
>>The non legacy tlauncher (the one you find as just find on the normal website) is considered by many as spyware and Trojan.
>
>>Both versions are disallowed as explicitly mentioned in Minecraft's end user agreement and is discouraged.
</br></br>

# How to Update
>This will not work if you didn't get it from git cloning, then you would have to redownload from here
>>To clarify, there is a hidden folder when you clone named `.git`, which holds the info of this repo, downloading from the site doesn't contain this file

open git bash

go inside of the dictory that was cloned

for using the CurseForge
```powershell
cd ./ShortFilmMods
```


then type:
```powershell
git fetch
```
all files will be updated, and no files will be overwritten
