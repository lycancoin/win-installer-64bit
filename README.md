# win-installer-64bit

Official Lycancoin Windows 64 bit installer that has been scanned for viruses and whitelisted by Windows Defender.

Virustotal.com security scan:
https://www.virustotal.com/gui/file/c69782698f53320acf1c29d41ec92f4e22c82dbe4b9bc706251095c5d2baca04

Windows Defender:
This official Lycancoin installer was submitted to Microsoft and approved as not containing malicious code. Please follow the steps below to clear cached detections and obtain the latest malware definitions:

1. Open command prompt as administrator and change directory to c:\Program Files\Windows Defender
2. Run “MpCmdRun.exe -removedefinitions -dynamicsignatures”
3. Run "MpCmdRun.exe -SignatureUpdate"

You may also resubmit the file to Microsoft for analysis: https://www.microsoft.com/en-us/wdsi/filesubmission
