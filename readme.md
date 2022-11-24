# Office 2019 VOL Install

## Config

Modify the office_vol.xml file according to your needs.

Support for installing Access, Excel, Groove, Lync, OneDrive, OneNote, Outlook, PowerPoint, Publisher, Teams, Word, Visio.

You can use [this](https://config.office.com/deploymentsettings) to generate a new configuration file, or manually modify the `Office2019VL-Std.xml \ OfficeProPlus2019-VL.xml` file, the default installation word, excel and PowerPoint...

## Download & Install

```
setup.exe /download Office2019VL-Std.xml
setup.exe /configure Office2019VL-Std.xml
```

## KMS Activtion

**open cmd as admin**

```
cd /d "%ProgramFiles%\Microsoft Office\Office16"
cscript ospp.vbs /sethst:KMS_SERVER
```
and enter genuine volume license key
```
cscript ospp.vbs /inpkey:NMMKJ-6RK4F-KMJVX-8D9MJ-6MWKP 
```
^^^^ for OfficeProPlus 2019 ...OR
```
cscript ospp.vbs /inpkey:6NWWJ-YQWMR-QKGCB-6TMB3-9D9HK
```
^^^^ for Standart 2019 and finally...
```
cscript ospp.vbs /act
```
## More



Deploy docs : https://docs.microsoft.com/en-us/deployoffice/office2019/deploy
