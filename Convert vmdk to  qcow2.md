---

created: [ 2022-12-18 16:06 ]

updated_date: [ 18/12/2022 ]

tags: [ literature, eve-ng ]

---

# Convert vmdk to  qcow2

Modified:: NaN

Convert vmdk to  qcow2


# Notes
- Download the media weather a iso file of 7z file. 
- If a linux image, this is what you should name the directory in `/opt/unetlab/addons/qemu`linux-< image name > 
- Once your directory is made, go  to where your image is and convert for qcow2 using the following syntax. `qemu-img convert -f vmdk -O qcow2 < vmdk name > virtioa.qcow`




# Links