# shieldXL-PiSugar3-Plus-Case
![20231105_095703](https://github.com/cavalopazzo/shieldXL-PiSugar3-Plus-Case/assets/149902852/bacc6f90-e9de-473c-a988-0cc26494d5e4)

## **Parts**

(1) Raspberry Pi 3B+ (not tested with 3B nor 4)

[(1) Pisugar3 Plus](https://www.amazon.com/dp/B09MJ876FW?psc=1&ref=ppx_yo2ov_dt_b_product_details)

[(4) M2.5x11 male to female standoff](https://www.amazon.com/dp/B09R97DVZY?ref=ppx_yo2ov_dt_b_product_details&th=1)

[(4) M2.5x10 female to female standoff](https://www.amazon.com/gp/product/B09F9GMP4W/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1)

(8) M2.5x6 screw

(1) M2.5x10 screw

(1) M2.5x16 screw

(3) M2.5x8 male to female standoff

[(2) M2.5x6 heat set inserts (optional)](https://www.amazon.com/dp/B0B46YBNV4?ref=ppx_yo2ov_dt_b_product_details&th=1)




## **Printing**

Two version of the main case file are included - one meant for heat set inserts on the two leftmost screw holes and one with plain holes meant to be threaded by a screw. 

For the non-heat set version, the original case file has been altered to have 2.25mm diameter holes instead of printing M2.5 threads. Forming/cutting threads with a 
metal M2.5 screw will likely produce more robust threads than FDM printing.

Also included is the power switch (required) and some knobs (optional). 

Due to the tight tolerances and depending on many variables, the power switch may be too tall or tooo short. The fusion360 file is provided to 
allow for the quick addition or subtraction of a tenth of a millimeter to the lower, wider section.

There are two knob models, one meant for the right two encoders and one 'lower' one meant for the left encoder which may sit higher than the others.

The case shown here was printed in PLA at a layer height of 0.15mm with a brim. Cura's fuzzy skin option was used to add the texture - thickness of 0.15mm, point distance of 0.4mm.



## **Assembly**

### **Check power switch fitment**

It's best to ensure the power switch is the right size before proceding with the full installation.

Install the 11mm and 10mm standoffs on the pisugar. The pisugar may arrive with small orange stickers covering the threads. Remove them.
![Screenshot 2023-11-05 114402](https://github.com/cavalopazzo/shieldXL-PiSugar3-Plus-Case/assets/149902852/f5c0d302-cf5d-4c71-bd54-20affcdffe9f)

Put the power switch in the case and install the pisugar with battery attached. 
![Screenshot 2023-11-05 114913](https://github.com/cavalopazzo/shieldXL-PiSugar3-Plus-Case/assets/149902852/3f356ed7-07be-4574-a15f-3a3c775cad88)
![Screenshot 2023-11-05 114350](https://github.com/cavalopazzo/shieldXL-PiSugar3-Plus-Case/assets/149902852/dfb323ac-1f85-4556-b98d-49b20a1c1656)

After installing a few of the mounting screws, check that the power switch functions well.
![Screenshot 2023-11-05 114802](https://github.com/cavalopazzo/shieldXL-PiSugar3-Plus-Case/assets/149902852/c5b3ad02-c2a1-4c74-b551-c3168a85b70a)


### **Install pisugar/pi**

Attach the pisugar to the pi with the 11mm standoffs and add the 10mm standoffs to the pisugar side.
![Screenshot 2023-11-05 115015](https://github.com/cavalopazzo/shieldXL-PiSugar3-Plus-Case/assets/149902852/977773a5-32e5-4471-bd84-3c1473679aaa)
![Screenshot 2023-11-05 115004](https://github.com/cavalopazzo/shieldXL-PiSugar3-Plus-Case/assets/149902852/73114198-fbff-4db3-8e72-3e3caff8a685)

Remove the battery's magnet and attach to the pisugar. The magnet adhesive tape disk may be used later.
![Screenshot 2023-11-05 114952](https://github.com/cavalopazzo/shieldXL-PiSugar3-Plus-Case/assets/149902852/cbc7b717-9284-434e-81bb-79ac9534055a)
![Screenshot 2023-11-05 114926](https://github.com/cavalopazzo/shieldXL-PiSugar3-Plus-Case/assets/149902852/a8a67907-d201-43f7-a2c1-8d8129455593)

Now for the first tricky part - insert the power switch into the case and while holding the case upright to keep the power switch in place, insert the combo into the case angled as shown 
with the USB and ethernet ports sticking out.
![Screenshot 2023-11-05 114849](https://github.com/cavalopazzo/shieldXL-PiSugar3-Plus-Case/assets/149902852/b14e19d3-6bcd-464f-9bf3-1583e1247ad1)

Next tricky part - bend/pull the power switch side of the case out while pushing down on the pi/pisugar to get the pi's 3.5mm connector into place without jostling things enough to dislodge the power switch.
Make sure the battery wires aren't between the case and the standoff.
![Screenshot 2023-11-05 114834](https://github.com/cavalopazzo/shieldXL-PiSugar3-Plus-Case/assets/149902852/fee524b5-631a-423c-add0-0a8280af8b58)

Install a couple of the 6mm mounting screws and check that the power switch is seated well and functions.
![Screenshot 2023-11-05 114815](https://github.com/cavalopazzo/shieldXL-PiSugar3-Plus-Case/assets/149902852/f3dae8ba-8024-47b1-924d-b21f75280e50)
![Screenshot 2023-11-05 114802](https://github.com/cavalopazzo/shieldXL-PiSugar3-Plus-Case/assets/149902852/bc514fee-d1a0-41f8-bb67-5da6612e5e4f)

Add some foam on top of the battery (sticking it in place with the magnet's adhesive is a good idea)
![Screenshot 2023-11-05 114747](https://github.com/cavalopazzo/shieldXL-PiSugar3-Plus-Case/assets/149902852/f7386382-3f21-43d5-82d7-1943ac757516)

### **Install shieldXL board**

If using the case version without heated inserts, now would be a good time to slowly and carefully thread one of the longer M2.5 screws into the left case holes.
Slow, steady, and even downward pressure while turning the driver should form good threads.
![Screenshot 2023-11-05 123755](https://github.com/cavalopazzo/shieldXL-PiSugar3-Plus-Case/assets/149902852/f3e845b4-c53e-45f7-a99d-685cab7809ee)


Insert the 1/4-inch jacks of the shieldXL board into the case, leaving the rest angled up.
![Screenshot 2023-11-05 114714](https://github.com/cavalopazzo/shieldXL-PiSugar3-Plus-Case/assets/149902852/02dad570-c4cf-469e-9f47-887cb6623618)

Now for the final tricky part - bend/pull the power switch side of the case enough to allow the 3.5mm midi in jack to start lowering into place.
![Screenshot 2023-11-05 114701](https://github.com/cavalopazzo/shieldXL-PiSugar3-Plus-Case/assets/149902852/8623bedd-f706-4d5c-a664-fe47a025c1bb)
![Screenshot 2023-11-05 114643](https://github.com/cavalopazzo/shieldXL-PiSugar3-Plus-Case/assets/149902852/bc36771c-3c15-4498-b0d2-f7b5639ddefd)

Check that the pi connection header is reasonably well aligned.
![Screenshot 2023-11-05 121929](https://github.com/cavalopazzo/shieldXL-PiSugar3-Plus-Case/assets/149902852/0040adcd-ef2b-4f1c-8cb4-e1114be8acde)

Continue pushing down the shieldXL board while making sure the pi connection header is still aligned.
![Screenshot 2023-11-05 114612](https://github.com/cavalopazzo/shieldXL-PiSugar3-Plus-Case/assets/149902852/257b264a-19be-4661-94e1-bb01242eaf72)
![Screenshot 2023-11-05 114557](https://github.com/cavalopazzo/shieldXL-PiSugar3-Plus-Case/assets/149902852/d82cffb8-648d-4900-aff9-64e9a02536bf)

Insert the SD card, power up the pisugar, and make sure that all this bending and pulling hasn't broken anything.
![Screenshot 2023-11-05 114542](https://github.com/cavalopazzo/shieldXL-PiSugar3-Plus-Case/assets/149902852/11854856-04f2-44f2-a5af-5d9c2f9e4631)
![Screenshot 2023-11-05 114526](https://github.com/cavalopazzo/shieldXL-PiSugar3-Plus-Case/assets/149902852/63f59841-f6a1-44bf-8af8-cdb97bab0b1e)

### **Final assembly**

Install the 8mm standoffs and 6mm and 10mm screws.
![Screenshot 2023-11-05 114458](https://github.com/cavalopazzo/shieldXL-PiSugar3-Plus-Case/assets/149902852/96e497e9-31af-40e3-b03f-46ccf5eb0d82)

Install the four faceplate screws, starting with the 16mm screw in the lower left corner. 
![Screenshot 2023-11-05 114441](https://github.com/cavalopazzo/shieldXL-PiSugar3-Plus-Case/assets/149902852/94dccb11-7e92-4346-b09d-9a8e34c6a885)

Install your favorite knobs and appreciate your newly independant shieldXL.
![20231105_111050](https://github.com/cavalopazzo/shieldXL-PiSugar3-Plus-Case/assets/149902852/51faf2be-2120-42da-8257-2d4275409f74)



