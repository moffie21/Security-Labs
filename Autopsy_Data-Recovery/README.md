# NetLab+: Using Autopsy for Forensics + Lost Data Recovery

## INTENTION
For educational purposes showcasing my technical security abilities.
  
## WHAT'S THIS?
I learned how digital evidence is acquired and recorded.
  
## GOALS - Proof Data Recovery Was Successfully
- Able to examine evidence of a PDF from the SD card
- Able to view HTML-generated Autopsy Forensic Report 

## TOOLS
- Platform: NDG NetLab+
- Version: Security+ v4 Lab Series
- VM: Windows 10
- Software: Autopsy 4.19.0
  
## PROCEDURE
- Created a new case
- Loaded an evidence image file
- Explore Autopsy
- Examined the evidence image
- Generated a HTML report
  
## CHALLENGES / LESSON(S) LEARNED
- LL: Data source labeled “.Spotlight-V100” is from macOS, “LOST.DIR” is from Android, and “System Volume Information” is from Windows. Knowing this, I could see that the SD card was once plugged into a macOS, Android, and Windows machine. 
- LL: It was fun to see the alpine user system hardware info, "Machine model: Raspberry Pi 3 Model B Rev 1.2" in plain indexed text within the SD card's Linux directory var/log/dmesg file.
- LL: It was fun to learn how to add file tags and comments to image files in Autopsy.
