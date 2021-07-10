# windows-activation
Windows 10 activation https://docs.microsoft.com/en-us/windows-server/get-started/kmsclientkeys

@echo off
START /WAIT slmgr /ipk <serial-number>
START /WAIT slmgr /skms kms8.msguides.com
START /WAIT slmgr /ato
