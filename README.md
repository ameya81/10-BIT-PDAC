# 10-BIT-PDAC

The aim of the project is to design a 10 Bit Potentiometric Digital to Analog Converter using open-source EDA tools.The ususal approach is to use a resistor string to divide the voltages but that wouls take upto 1024 resistors for a 10-bit DAC. so ,here we have tried to reduce the number of resistors by implementing the dac in two stages of 5 bits each.

## MSB 5-Bit output
https://github.com/ameya81/10-BIT-PDAC/blob/master/out1.JPG
## Tools Used

Ngspice-ngspice is the open source spice simulator for electric and electronic circuits. Such a circuit may comprise of JFETs, bipolar and MOS transistors, passive elements like R, L, or C, diodes, transmission lines and other devices, all interconnected in a netlist.

Magic VLSI-Magic stands for Manhattan Artwork Generator for Integrated Circuits. It is a vlsi layout tool. As free and open-source software magic continuesto be a popular layout tool as it is easy to and expand for specilised tasks.

Esim - eSim (previously known as Oscad / FreeEDA) is a free/libre and open source EDA tool for circuit design, simulation, analysis and PCB design. It is an integrated tool built using free/libre and open source software such as KiCad, Ngspice and GHDL. eSim is released under GPL.

## Steps to install ```Esim``` on Linux

	i.      After downloading eSim, extract it using: 
  
   		       $ unzip eSim-2.1.zip

   	ii.     Now change directories in to the top-level eSim directory (where this INSTALL file can be found).

   	iii.    To install eSim and other dependencies, run the following command :

   		       $ chmod +x install-eSim.sh
   		       $ ./install-eSim.sh --install

   	iv.     To uninstall eSim and all of its components, run the following command :

   		       $ ./install-eSim.sh --uninstall
    
## Steps to install ```Esim``` on Windows OS

    i.      Download eSim for Windows OS from "https://esim.fossee.in/". Disable the antivirus (if any).

    ii.     Now double click on eSim installer and then follow the instruction to install eSim.

    iii.    To uninstall eSim and all of its components, run the uninstaller "uninst-eSim.exe" located at 
            top-level eSim directory (where this INSTALL file can be found).    
    

# #Steps to install ```Ngspice``` on LINUX

Run update command to update package repositories and get latest package information :
``` 
sudo apt-get update -y
``` 
Run the install command with -y flag to quickly install the packages and dependencies :
``` 
sudo apt-get install -y ngspice
``` 
Check the system logs to confirm that there are no related errors.

## Steps to install ```Ngspice``` on WINDOWS

Click on [ngspice](http://ngspice.sourceforge.net/download.html) and go to ```Downloads->Download Latest Version```.

> ```ngspice``` is now downloaded and ready to use

# Steps to clone the IP onto UNIX based systems
Cloning a github repository creates a local copy of a remote repo and this allows us to make any changes to the files locally without affecting the main repository. To clone the IP onto your system copy paste the commands given below one after the other.

```
$  sudo apt install -y git
$  git clone https://github.com/ameya81/10-BIT-PDAC.git
$  cd 
```

## Contact Information

- Ameya Deshpande ,BTech ,NIT Karnataka ,ameyadeshpande81@gmail.com
- Kunal Ghosh, Director, VSD Corp. Pvt. Ltd. kunalghosh@gmail.com
- Philipp Gühring, Software Architect, LibreSilicon Assocation pg@futureware.at
