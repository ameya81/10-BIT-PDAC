# 10-BIT-PDAC
The aim of the project is to design a 10 Bit Potentiometric Digital to Analog Converter using open-source EDA tools.

# Tools Used

Ngspice-ngspice is the open source spice simulator for electric and electronic circuits. Such a circuit may comprise of JFETs, bipolar and MOS transistors, passive elements like R, L, or C, diodes, transmission lines and other devices, all interconnected in a netlist.

Magic VLSI-Magic stands for Manhattan Artwork Generator for Integrated Circuits. It is a vlsi layout tool. As free and open-source software magic continuesto be a popular layout tool as it is easy to and expand for specilised tasks.

Esim - eSim (previously known as Oscad / FreeEDA) is a free/libre and open source EDA tool for circuit design, simulation, analysis and PCB design. It is an integrated tool built using free/libre and open source software such as KiCad, Ngspice and GHDL. eSim is released under GPL.

# Steps to install ```Esim``` on Linux
1. Go to Downloads section of esim.fossee.in and download eSim for Ubuntu.

2. Type Ctrl+Alt+t to open command terminal.

3. Change the directory where zip files is downloaded using 
```
cd . command. cd path-to-zipfile
```

4. unzip the zip file using below command
```
. unzip zip-file-name
```

5. Change to eSim folder using cd command

6. Type below command to install eSim. 
```
./install-linux.sh --install
```

7. Above script will install eSim along with dependencies.
# Steps to install ```Ngspice``` on LINUX
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

# Contact Information
- Ameya Deshpande ,BTech ,NIT Karnataka ,ameyadeshpande81@gmail.com
- Kunal Ghosh, Director, VSD Corp. Pvt. Ltd. kunalghosh@gmail.com
- Philipp Gühring, Software Architect, LibreSilicon Assocation pg@futureware.at
