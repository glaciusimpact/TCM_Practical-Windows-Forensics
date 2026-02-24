# TCM_Practical-Windows-Forensics
Comments on TCM Practical Windows Forensics after its removal.

You will find here good and things to update from Practical Windows Forensics. It just reflects **my** own opinion and yes, I liked the course.

## 1 - Things to keep
- The course does not go too fast which is comfortable and we are taken by the hand for the installation of the platform.
- Interesting tool: RegRipper.
- Secure ID (SID) concept developped.
- Disk Partition is an interesting topic.
- Finding very interesting evidences like "Connection date to a network".
- Volatility: the only course I found at TCM with volatility3. If this course is removed there will be no TCM course with this useful tool.
- For a user "C:\Users\<USER>\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Startup" and for every users "C:\ProgramData\Microsoft\Windows\Start Menu\Programs\StartUp" are startup paths mentioned in PWF. I think this is interesting to keep these locations in TCM courses because they can be as important as the Registry/Service/Scheduler way to create a persistent mechanism.
- VERY interesting topic: detection of a DLL injection on Notepad.
- Good idea to provide computer intensive already generated files; not only does this save time, but it also ensures that the same analysis results are obtained later on. Since log2timeline.py and psort.py just crashed for me so I was blocked at 93%/95% of the course and that saved me.
- Good advices at the end, on the reporting part

## 2 - Things to update
- Windows 2019 is too old now in 2026 (and not supported any longer by Microsoft); it is 7 years old and 2 versions of Windows server have been released since this version.
- Disk forensics: we see MBR (2 TB max) but not GPT whereas this last is very common nowadays.
- Some overlap content with SOC 101 (Windows Registry, Prefetch, UserAssist) but I guess this is due to historical reasons.
- Nothing about ransomware.
- Nothing about Autopsy (which is also not in SOC101, SOC201 and PMAT). But I just heard about it; it might be normal.
- No ending challenges at the end of every chapters like in SOC101 (which is a good idea to validate our understanding).
- I found the part concerning plaso and log2timeline complicated for no good reason (data converted many times).
- Chainsaw? (and I didn't see this useful tool on a TCM security course but I just read the content of SOC101 and Practical Windows Forensics so it might be somewhere else; no sure)
- No bookmarks and... no little reward tune at the end! (What??? he he!)

