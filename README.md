# Useful scripts repository
A place to store small scripts that may be used by the team. 

## BRCA QC
```
usage: python brca_exon_qc.py [-h] [-f F] run

Quick QC for BRCA samples

positional arguments:
run         Clinical pool run name i.e. CP0379A

optional arguments:
-h, --help  show this help message and exit
-f F        runfolder path if different from /mnt/storage/data/NGS/CP/

```
Jon asked if we can run it in the next few clinical pool runs, if there’s A+B, run it on A and B separately. I have made a folder in /mnt/storage/data/NHS/CP/reports where I have saved the reports to run this. 
