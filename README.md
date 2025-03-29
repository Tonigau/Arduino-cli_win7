# Arduino-cli_win7
This is a built executable of Arduino-cli V1.2.0 for use with Windows7. [Arduino-cli_win7]  
Built with 'go-legacy-win7-1.24.1-1' by thongtech from arduino source(2025.03.28).  
https://github.com/arduino/arduino-cli  
https://github.com/thongtech/go-legacy-win7/releases  
## Download and Install
Download **Arduino-cli-win7_v1.20.0.zip** and Etract Arduino-cli.exe to your specific folder.  
To test it works on your win7 system, open a cmd window, navigate to the folder and enter `arduino-cli` & you should see the output to console.  
Enter `arduino-cli version` to see the application version metadata.  

SHA-1 Hash checksum:
  `CDBD867C21096AEF35207BEFB5A98A6BD3FC940A`

## Information
Later versions of Arduino-cli are not win7 compatible due to the golang version, running the application will report runtime exception error.  
This application release is built from Arduino source V1.20.0 using a fork of golang to enable legacy build.  
Tested on Win7p x64 Dell_990 Run direct commands = ok, use with IDE = ok  
If you have an issue please log it for reference.  

### Disclaimer:
There may be issues with this version of Arduino-cli due to various factors, it is provided without any warranty or support whatsoever. 
