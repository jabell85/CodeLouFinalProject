# CodeLouFinalProject
Code Louisville Python Final Project

Overview:
   Build an application that will scan a local Google Drive for harmful software (i.e. Malware ) using the Virus Total API. Scans will happen every "X" day, once scan has been completed that infomation will be stored into a location on the machine and uploaded to Virus Total API. Between each scan, we will log NEW malware detections as well as show previously "passed" software that now scan as Malware via Virus Total. Any offset between previously passed scans and current failures will show the "lag" between when Virus Scanners both detect a malicious piece of software and the time to upload to various virus definition files.
  
Program Languages:
  Python
  SQLLite 

MileStones:
 1. Create Repo and Have README flie completed.
 2. Have application be able to scan local Google Drive.
 3. Once 2 is compelted have it connect to Total Virus API to compare information 
 4. Retreive infomration from mulitple scans and run them against Total Virus API and graphic results.
