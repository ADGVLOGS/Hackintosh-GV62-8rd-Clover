<div>
<img src="https://www.svgrepo.com/show/148371/clover.svg" height=85px>
<img src="https://www.svgrepo.com/show/7385/apple.svg" height=85px>
</div>

# Hackintosh-GV62-8rd-Clover
<img src="https://asset.msi.com/resize/image/global/product/product_2_20180212152735_5a8141e7cd029.png62405b38c58fe0f07fcef2367d8a9ba1/1024.png" height="250px">
 

#### Ashlin Darius Govindasamy

# Table of contents
1. [Problem Statement](#problem) <br>
1.1 [What is my specifications and requirements?](#problem) <br>
1.2 [Laptop](#laptop) <br>
2. [Issues](#issues) <br>
2.1 [Project Status](#status) <br>
3. [GPU Support](#gpu)<br>


### Problem Statement
<p><a name="problem"></a>
I need to code Objective C to create iOS/macOS native applications. <br>
Problem with Apple's ecosystem prices are rediculous. I am not paying top dollar for piece of shit hardware. My MSi GV62-8rd will be a strong contester in this battle.
  
<br>
  
What is my specifications and requirements? <a name="specs"></a><br>
  
<br>
  
 
<h4>Specs of Laptop</h4>
<pre>
CPU	Up to 8th Gen. Intel® Core™ i7 Processor
OS	Windows 10 Home
DISPLAY	15.6" FHD (1920x1080), Wide-View
15.6" FHD (1920x1080), IPS-Level
CHIPSET	Intel® HM370
GRAPHICS	GeForce® GTX 1050 Ti with 4GB GDDR5
MEMORY	DDR4-2400
DDR4-2666, 2 Slots, Max 32GB,
STORAGE CAPABILITY	1x M.2 SSD Combo (NVMe PCIe Gen3 / SATA ) SSD 1x 2.5" SATA HDD HDD
WEBCAM	HD type (30fps@720p)
KEYBOARD	Backlight Keyboard (Single-Color, Red)
COMMUNICATION	Gb LAN
802.11 ac Wi-Fi + Bluetooth v5
AUDIO JACK	1x Mic-in
1x Headphone-out (SPDIF)
I/O PORTS	1x Type-A USB2.0
1x RJ45
1x SD (XC/HC)
1x (4K @ 30Hz) HDMI
1x Mini-DisplayPort
1x Type-C USB3.1 Gen1
2x Type-A USB3.1 Gen1
BATTERY	41 Whr
AC ADAPTER	150W adapter
DIMENSION (WXDXH)	383 x 260 x 22~29 mm
WEIGHT (W/ BATTERY)	2.2 kg
</pre>

Requirements <br>  
- my NVME SSD needs to work <br>
- Needs to duel boot with Windows <br>
- My GTX 1050ti needs to work<br>
- My sound/bluetooth needs to be working<br>

If i comply with the above i can proudly say the project was a success.

</p>

#### This is my laptop i am using. <a name="laptop"></a>
<a href="https://www.msi.com/Laptop/GV62-8RD/Specification" >My MSi laptop</a>

#### Status on kexts and bootloader.<a name="issues"></a>
````
Bluetooth driver, Bluetooth, wireless available
Existence problem (Voice waiting perfection, Mingten re-drumming one bottom) 2020.08.23
Voice card ok, Bluetooth wireless public association
````

## Project Status - On going <a name="status"></a>
#### Currently experimenting with macOS versions

![image](https://user-images.githubusercontent.com/45560312/132132436-1017714f-691d-4991-bc05-5e9a5ec15c2c.png)


## GPU SUPPORT <a name="gpu"></a>

<table border="1">
  
<tr><th>Nvidia Kepler Cards that are Natively Supported: (GT 630 - GTX 660 specific models may have issues)</th></tr>

<tr><td>GTX Titan (GK110)</td></tr>

<tr><td>GTX Titan Black (GK110)</td></tr>

<tr><td>GTX Titan Z</td></tr>

<tr><td>GTX 780/Ti</td></tr>

<tr><td>GTX 770</td></tr>

<tr><td>GTX 760/Ti</td></tr>

<tr><td>GT 740 (Avoid OEM versions)</td></tr>

<tr><td>GT 730 (GK208 core)</td></tr>

<tr><td>GT 720</td></tr>

<tr><td>GT 710 (GK208 core versions)</td></tr>

<tr><td>GTX 690</td></tr>

<tr><td>GTX 680</td></tr>

<tr><td>GTX 670</td></tr>

<tr><td>GTX 660/Ti (Avoid GK106 models)</td></tr>

<tr><td>GTX 650/Ti (Avoid GK106 models)</td></tr>

<tr><td>GT 640 (Kepler edition GK107/208 core)</td></tr>

<tr><td>GT 630 (Kepler edition GK208 core)</td></tr>

<tr><td>Quadro 410</td></tr>

<tr><td>Quadro K420</td></tr>

<tr><td>Quadro K600</td></tr>

<tr><td>Quadro K2000/D</td></tr>

<tr><td>Quadro K4200</td></tr>

<tr><td>Quadro K5000</td></tr>

<tr><td>Quadro K5200</td></tr>

<tr><td>Quadro K6000</td></tr>

<tr><td>Quadro NVS510</td></tr>

</table>

<table border="1">
<tr><th>Nvidia: Ampere; Turing Pascal and Maxwell Cards (These are Not Supported in Mojave - Catalina or Big Sur)</th></tr>
<tr><td>RTX 3090</td></tr>
<tr><td>RTX 3080</td></tr>
<tr><td>RTX 3070</td></tr>
<tr><td>RTX 3060 Ti</td></tr>
<tr><td>Titan RTX</td></tr>
<tr><td>RTX 2080 Ti</td></tr>
<tr><td>RTX 2080 Super</td></tr>
<tr><td>RTX 2080</td></tr>
<tr><td>RTX 2070 Super</td></tr>
<tr><td>RTX 2070</td></tr>
<tr><td>RTX 2060 Super</td></tr>
<tr><td>RTX 2060</td></tr>
<tr><td>GTX 1660 Ti</td></tr>
<tr><td>GTX 1660 Super</td></tr>
<tr><td>GTX 1650</td></tr>
<tr><td>GTX 1080/Ti</td></tr>
<tr><td>GTX 1070/Ti</td></tr>
<tr><td>GTX 1060</td></tr>
<tr><td>GTX 1050/Ti</td></tr>
<tr><td>GT 1030</td></tr>
<tr><td>GTX Titan X (GM200 Maxwell core)</td></tr>
<tr><td>GTX 980/Ti</td></tr>
<tr><td>GTX 970</td></tr>
<tr><td>GTX 960</td></tr>
<tr><td>GTX 950</td></tr>
<tr><td>GTX 750/Ti</td></tr>
<tr><td>GTX 745</td></tr>
<tr><td>Quadro 600</td></tr>
<tr><td>Quadro K620</td></tr>
<tr><td>Quadro K1200</td></tr>
<tr><td>Quadro K220</td></tr>
<tr><td>Quadro M (all models)</td></tr>
<tr><td>Quadro P (all models)</td></tr>
<tr><td>Fermi cards (GF) (all models)</td></tr>
</table>
