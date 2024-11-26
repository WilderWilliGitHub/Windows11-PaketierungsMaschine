# Windows11-PaketierungsMaschine
Es wird eine Windows 11 Maschine aufgesetzt die zum Paketieren geeignet ist. Windows 11 wird automatisch installiert und danach werden die wichtigsten Programme installiert

Der Befehl zum erstellen der ISO
"C:\Program Files (x86)\Windows Kits\10\Assessment and Deployment Kit\Deployment Tools\amd64\Oscdimg\oscdimg.exe" -m -o -u2 -udfver102 -bootdata:2#p0,e,bC:\Win11_ISO_Extracted\boot\etfsboot.com#pEF,e,bC:\Win11_ISO_Extracted\efi\microsoft\boot\efisys.bin C:\Win11_ISO_Extracted C:\Win11_Custom02.iso
