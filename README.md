# Reviewing-Unallocated-Space-Extracting-Data-with-Tools-Digital-Investigation-Processes
## AIM:
To review unallocated space in a disk image, extract data using forensic tools, and understand the digital investigation process.

## DESIGN STEPS:
### Step 1:
Use tools like Autopsy or Sleuth Kit (blkls, icat) to identify and analyze unallocated space.

### Step 2:
Extract data from unallocated space and examine for hidden or deleted content.

### Step 3:
Document and interpret findings as part of the digital investigation process.

## PROGRAM:
Data Extraction and Investigation Tool Usage
```
lsblk
```
```
sudo dd if=/dev/sda of=/home/kali/disk.img bs=512
```
```
mmls ~/disk.img
```
```
sudo ls -lh disk.img
```
```
strings disk.img | less
```
## OUTPUT:

![435671756-83a427da-d372-4b72-8e54-c874c8e31f37](https://github.com/user-attachments/assets/bb40bcf1-898c-43f8-a6b0-8899e0966be9)

![435673271-4ed4a4a3-542d-42b8-af06-9c1eedaec949](https://github.com/user-attachments/assets/f259b9f6-ef78-470b-9b48-c5827fdb0351)

![435672929-1fc8e81f-12c1-4927-92ca-a4a0a500950e](https://github.com/user-attachments/assets/2d12be68-f4d9-41bb-8097-739cbc63750b)

![435676152-d2beee48-5fee-4476-84fd-ab24954f077d](https://github.com/user-attachments/assets/86defe17-de28-4f4b-82a8-d6836a3c3084)

![435676562-4aff8fc4-e59c-475e-bdb2-658f15c67c50](https://github.com/user-attachments/assets/bbdbd2fd-0a7b-48d2-941f-71085f29b688)


## RESULT:
The unallocated space was successfully analyzed, data was extracted, and the digital investigation process was followed effectively.
