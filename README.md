# WARNING / AVISOS
Por favor, gere um novo número de SMBIOS se você for entrar com alguma conta Icloud utilizando GenSMBIOS e coloque os novos valores no config.plist > PlataformInfo antes de prosseguir com a instalação para que sua conta Icloud não seja banida.

Please generate a new number of SMBIOS using GenSMBIOS and put the new values in config.plist > PlatformInfo before proceeding with the installation so that your Icloud account is not banned.
SMBIOS > MacPro7,1

# TUTORIAL SMBIOS
Get the python standalone installer > https://www.python.org/ftp/python/3.14.5/python-3.14.5-amd64.exe

Install and add to path

<img width="860" height="551" alt="python-install-path" src="https://github.com/user-attachments/assets/a1fd7cbb-48b7-4c10-940a-a3a562fe4bd2" />

Get the Propertree plist editor > https://github.com/corpnewt/propertree

Get the genSMBIOS > https://github.com/corpnewt/gensmbios

extract the zip files from GenSMBIOS-master.zip and run genSMBIOS windows batch file

<img width="976" height="503" alt="{CEC3BFD8-A065-4CA5-8EA0-CAF370DFB01C}" src="https://github.com/user-attachments/assets/09710255-56e1-4f82-8e39-1ab324fac4b3" />
select option 3 (Generate SMBIOS)

<img width="979" height="508" alt="{858020FE-B13D-403D-9221-ECC1E20F018E}" src="https://github.com/user-attachments/assets/2dedce81-8d42-4dab-b5ba-876e008686cc" />
type "MacPro7,1"

# PROPERTREE
extract the zip files from ProperTree-master.zip and run ProperTree windows batch file
<img width="726" height="522" alt="{1CA13049-8CA0-4D3A-AEB3-4AF8CC922B9E}" src="https://github.com/user-attachments/assets/41282ed4-9b40-4e89-93e1-0ebec850bddc" />
File > Open > C:\Users\user\Downloads\Recovery.+.EFI.Tahoe\Recovery + EFI Tahoe\EFI\OC\config.plist

<img width="730" height="524" alt="Untitled" src="https://github.com/user-attachments/assets/2fd5d03e-318a-4373-aefb-0ac239225d1c" />
<img width="730" height="526" alt="Untitled" src="https://github.com/user-attachments/assets/09d6c954-1b9a-4e18-a632-3ca1135b9682" />
<img width="729" height="535" alt="{E4A7CE87-F708-44AE-8B75-6EFC778750F5}" src="https://github.com/user-attachments/assets/cbaa8fe6-5edf-4b74-8a7c-790df5725cef" />



SystemSerialNumber = Serial
MLB = Board Serial
SystemUUID = SmUUID

replace serials according to genSMBIOS numbers, and you ready to install MacOS Tahoe


# BIOS
You will have to flash a new bios to install Tahoe.

Você terá que flashar essa bios para conseguir instalar o Tahoe.

Bios > https://github.com/jwagnervaz/QIYIDA-X99-D4-V2.0/blob/main/V3-TURBO-UNLOCKED/QYX99D4V2-0-V3-UNLOCKED-11-01-2023.rom 


# SETUP:
Qiyida D4 X99

XEON 2680V3

16GB RAM DDR4 2133

RX 6600 ASROCK 8GB

SSD KINGSTON SATA 256GB

LAN > Realtek 8111H

AUDIO > Realtek ALC897


# CREDITS TO:
Gabriel Luchina > EFI BASE

Jwagnervaz > BIOS


# SCREENSHOTS / CAPTURAS DE TELA
<img width="2560" height="1080" alt="Captura de Tela 2026-06-07 às 21 30 11" src="https://github.com/user-attachments/assets/99de5334-f94b-487f-88d1-7785474d8d34" />
<img width="2560" height="1080" alt="Captura de Tela 2026-06-07 às 21 32 46" src="https://github.com/user-attachments/assets/73973575-5acc-4237-883a-d48523791458" />
<img width="2560" height="1080" alt="download" src="https://github.com/user-attachments/assets/b28b6ed4-ea83-4b15-b9dd-b99d6ce2db0e" />






