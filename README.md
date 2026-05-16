# libimobiledevice

build of libimobiledevice v1.4.0 for Windows x64.

Compiled using:
- MSYS2 UCRT64
- GCC
- OpenSSL 3

Includes:
- idevicepair
- ideviceinfo
- idevicebackup
- idevicebackup2
- idevicesyslog
- afcclient
- required DLLs

## Compatibility

- Windows 10
- Windows 11
- Modern iOS versions

## Usage

```powershell
.\idevice_id.exe -l

.\idevicepair.exe pair

.\ideviceinfo.exe
```

## Pairing Record Location

After pairing:

```text
C:\ProgramData\Apple\Lockdown\
```

## Credits

Original project:
https://github.com/libimobiledevice/libimobiledevice
