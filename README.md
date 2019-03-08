# CVE_Assessment_05_2019

Description: This is a review of Abloy Key Manager (version 7.14301.0.0). The software has suspicious files that can allow adversaries to launch attacks that can allow privilege escalation, load malicious files (hooking ), among others.  

In this software three components were found compromised: KM7Setup.exe  sHJdnkvV.exe and ECOCIhtx.exe. These files were labeled as malicious. The main aspects explored included: the capacity to drop executable files, network weakness, and the elevation privilege  through weaknesses in the system security (SeChangeNotifyPrivilege).

The software open connections through Google and Amazon services, however one network connection seemed suspicious. The network analysis observed that multiple malicious artifacts were in transit through the software and those connections . 

Another security risk is related to an expired certificate that prevents the validation of the software source .


References

1) https://www.symantec.com/avcenter/reference/windows.rootkit.overview.pdf
2) https://www.virustotal.com/#/file/2c8d49b7ef16aec4c984664b87713b300d8a06bf82b8967499674397b1565029/details
3) https://docs.microsoft.com/en-us/windows-hardware/drivers/ifs/elevation-of-privilege 
4) https://www.hybrid-analysis.com/sample/2c8d49b7ef16aec4c984664b87713b300d8a06bf82b8967499674397b1565029/5c7d416903883820949f1f1d
5) https://comodosslstore.com/resources/how-to-avoid-code-signing-certificate-expired-issues/
6) https://www.trendmicro.com/vinfo/us/threat-encyclopedia/search/lz32.dll 
7) https://docs.microsoft.com/en-us/windows/desktop/api/lzexpand/nf-lzexpand-lzinit 
8) https://docs.microsoft.com/en-us/windows/desktop/api/lzexpand/nf-lzexpand-lzcopy 
9) https://www.malwares.com/report/host?host=ocsp.pki.goog
10) https://docs.microsoft.com/en-us/previous-versions/windows/desktop/secrcw32prov/setsecuritydescriptor-method-in-class-win32-logicalfilesecuritysetting 
11) https://docs.microsoft.com/en-us/windows/desktop/WmiSdk/executing-privileged-operations 
12) https://docs.netapp.com/ontap-9/index.jsp?topic=%2Fcom.netapp.doc.cdot-famg-cifs%2FGUID-B188F6D1-253B-49C5-925F-53488BF1A31B.html 
