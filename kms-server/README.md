# kms-server
kms server. View list software compatible

## Run

* Run docker-compose

```
$ docker-compose up -d
```

* Run docker

```
$ docker run -it -d -p 1688:1688 kms-server:v1.0
```

## Client usage:

**Note: run `cmd` with administrator or `powershell` with administrator.**  

- Windows:
```powershell
slmgr /upk
slmgr /ipk XXXXX-XXXXX-XXXXX-XXXXX-XXXXX
slmgr /skms YOUR_IP_OR_HOSTNAME
slmgr /ato
```

- Office 2010, 2013, 2016 and 2019:

```powershell
# Office 2010
CD \Program Files\Microsoft Office\Office14
# Office 2013
CD \Program Files\Microsoft Office\Office15
# Office 2016 and 2019
CD \Program Files\Microsoft Office\Office16 

OR 

CD \Program Files (x86)\Microsoft Office\Office16
cscript ospp.vbs /sethst:YOUR_IP_OR_HOSTNAME

cscript ospp.vbs /inpkey:xxxxx-xxxxx-xxxxx-xxxxx-xxxxx
cscript ospp.vbs /act
cscript ospp.vbs /dstatusall
```

* Donacion:

![Donacion](../.donacion_enzona.png)

o un usd en bitcoin

![Donacion](../.donacion_bitcoin.png)

## 
Numbers|Product names
:-|-
  1 | Windows Server 2019 ARM64
  2 | Windows Server 2019 Azure Core
  3 | Windows Server 2019 Datacenter
  4 | Windows Server 2019 Essentials
  5 | Windows Server 2019 Standard
  6 | Windows Server 2019 Datacenter (Semi-Annual Channel)
  7 | Windows Server 2019 Standard (Semi-Annual Channel)
  8 | Windows 10 Enterprise LTSC 2019
  9 | Windows 10 Enterprise LTSC 2019 N
 10 | Windows 10 Enterprise G
 11 | Windows 10 Enterprise GN
 12 | Windows 10 Enterprise 2016 LTSB
 13 | Windows 10 Enterprise 2016 LTSB N
 14 | Windows 10 Home
 15 | Windows 10 Home Country Specific
 16 | Windows 10 Home N
 17 | Windows 10 Home Single Language
 18 | Windows 10 Education
 19 | Windows 10 Education N
 20 | Windows 10 Enterprise
 21 | Windows 10 Enterprise 2015 LTSB
 22 | Windows 10 Enterprise 2015 LTSB N
 23 | Windows 10 Enterprise N
 24 | Windows 10 Professional Workstation
 25 | Windows 10 Professional Workstation N
 26 | Windows 10 Professional
 27 | Windows 10 Professional Education
 28 | Windows 10 Professional Education N
 29 | Windows 10 Professional N
 30 | Windows 10 Professional Preview
 31 | Windows 10 Enterprise Preview
 32 | Windows 10 Enterprise for Virtual Desktops
 33 | Windows 10 Remote Server
 34 | Windows 10 S (Lean)
 35 | Windows 7 Enterprise
 36 | Windows 7 Enterprise E
 37 | Windows 7 Enterprise N
 38 | Windows 7 Professional
 39 | Windows 7 Professional E
 40 | Windows 7 Professional N
 41 | Windows 7 Embedded POSReady
 42 | Windows 7 Embedded Standard
 43 | Windows 7 ThinPC
 44 | Windows 8 Core
 45 | Windows 8 Core Country Specific
 46 | Windows 8 Core N
 47 | Windows 8 Core Single Language
 48 | Windows 8 Professional WMC
 49 | Windows 8 Embedded Industry Professional
 50 | Windows 8 Embedded Industry Enterprise
 51 | Windows 8 Enterprise
 52 | Windows 8 Enterprise N
 53 | Windows 8 Professional
 54 | Windows 8 Professional N
 55 | Windows 8.1 Core
 56 | Windows 8.1 Core ARM
 57 | Windows 8.1 Core Country Specific
 58 | Windows 8.1 Core N
 59 | Windows 8.1 Core Single Language
 60 | Windows 8.1 Professional Student
 61 | Windows 8.1 Professional Student N
 62 | Windows 8.1 Professional WMC
 63 | Windows 8.1 Core Connected
 64 | Windows 8.1 Core Connected Country Specific
 65 | Windows 8.1 Core Connected N
 66 | Windows 8.1 Core Connected Single Language
 67 | Windows 8.1 Enterprise
 68 | Windows 8.1 Enterprise N
 69 | Windows 8.1 Professional
 70 | Windows 8.1 Professional N
 71 | Windows 8.1 Embedded Industry Professional
 72 | Windows 8.1 Embedded Industry Automotive
 73 | Windows 8.1 Embedded Industry Enterprise
 74 | Windows 10 Enterprise Preview
 75 | Windows 10 Professional Preview
 76 | Windows 10 Professional WMC Preview
 77 | Windows 8.x Preview
 78 | Windows 8.x Preview ARM
 79 | Windows Server 2008 Web
 80 | Windows Server 2008 Compute Cluster
 81 | Windows Server 2008 Standard
 82 | Windows Server 2008 Standard without Hyper-V
 83 | Windows Server 2008 Enterprise
 84 | Windows Server 2008 Enterprise without Hyper-V
 85 | Windows Server 2008 Datacenter
 86 | Windows Server 2008 Datacenter without Hyper-V
 87 | Windows Server 2008 for Itanium
 88 | Windows MultiPoint Server 2010
 89 | Windows Server 2008 R2 Web
 90 | Windows Server 2008 R2 HPC Edition
 91 | Windows Server 2008 R2 Standard
 92 | Windows Server 2008 R2 Enterprise
 93 | Windows Server 2008 R2 Datacenter
 94 | Windows Server 2008 R2 for Itanium Enterprise
 95 | Windows Server 2012 Datacenter
 96 | Windows Server 2012 MultiPoint Premium
 97 | Windows Server 2012 MultiPoint Standard
 98 | Windows Server 2012 Standard
 99 | Windows Server 2012 R2 Cloud Storage
100 | Windows Server 2012 R2 Datacenter
101 | Windows Server 2012 R2 Essentials
102 | Windows Server 2012 R2 Standard
103 | Windows Server 2016 Azure Core
104 | Windows Server 2016 Cloud Storage
105 | Windows Server 2016 Datacenter
106 | Windows Server 2016 Essentials
107 | Windows Server 2016 Standard
108 | Windows Server 2016 ARM64
109 | Windows Server 2016 Datacenter (Semi-Annual Channel)
110 | Windows Server 2016 Standard (Semi-Annual Channel)
111 | Windows Server 2016 Datacenter Preview
112 | Windows Vista Business
113 | Windows Vista Business N
114 | Windows Vista Enterprise
115 | Windows Vista Enterprise N
116 | Office Access 2010
117 | Office Excel 2010
118 | Office Groove 2010
119 | Office InfoPath 2010
120 | Office Mondo 1 2010
121 | Office Mondo 2 2010
122 | Office OneNote 2010
123 | Office OutLook 2010
124 | Office PowerPoint 2010
125 | Office Professional Plus 2010
126 | Office Project Pro 2010
127 | Office Project Standard 2010
128 | Office Publisher 2010
129 | Office Small Business Basics 2010
130 | Office Standard 2010
131 | Office Visio Premium 2010
132 | Office Visio Pro 2010
133 | Office Visio Standard 2010
134 | Office Word 2010
135 | Office Access 2013
136 | Office Excel 2013
137 | Office InfoPath 2013
138 | Office Lync 2013
139 | Office Mondo 2013
140 | Office OneNote 2013
141 | Office OutLook 2013
142 | Office PowerPoint 2013
143 | Office Professional Plus 2013
144 | Office Project Pro 2013
145 | Office Project Standard 2013
146 | Office Publisher 2013
147 | Office Standard 2013
148 | Office Visio Pro 2013
149 | Office Visio Standard 2013
150 | Office Word 2013
151 | Office Access 2013 (Pre-Release)
152 | Office Excel 2013 (Pre-Release)
153 | Office Groove 2013 (Pre-Release)
154 | Office InfoPath 2013 (Pre-Release)
155 | Office Lync 2013 (Pre-Release)
156 | Office Mondo 2013 (Pre-Release)
157 | Office OneNote 2013 (Pre-Release)
158 | Office Outlook 2013 (Pre-Release)
159 | Office PowerPoint 2013 (Pre-Release)
160 | Office Professional Plus 2013 (Pre-Release)
161 | Office Project Pro 2013 (Pre-Release)
162 | Office Project Standard 2013 (Pre-Release)
163 | Office Publisher 2013 (Pre-Release)
164 | Office Visio Pro 2013 (Pre-Release)
165 | Office Visio Standard 2013 (Pre-Release)
166 | Office Word 2013 (Pre-Release)
167 | Office Access 2016
168 | Office Excel 2016
169 | Office Mondo 2016
170 | Office Mondo R 2016
171 | Office OneNote 2016
172 | Office Outlook 2016
173 | Office Powerpoint 2016
174 | Office Professional Plus 2016
175 | Office Project Pro 2016
176 | Office Project Pro 2016 C2R
177 | Office Project Standard 2016
178 | Office Project Standard 2016 C2R
179 | Office Publisher 2016
180 | Office Skype for Business 2016
181 | Office Standard 2016
182 | Office Visio Pro 2016
183 | Office Visio Pro 2016 C2R
184 | Office Visio Standard 2016
185 | Office Visio Standard 2016 C2R
186 | Office Word 2016
187 | Office Professional Plus 2019 C2R Preview
188 | Office Project Pro 2019 C2R Preview
189 | Office Visio Pro 2019 C2R Preview
190 | Office Access 2019
191 | Office Excel 2019
192 | Office Outlook 2019
193 | Office Powerpoint 2019
194 | Office Professional Plus 2019
195 | Office Project Pro 2019
196 | Office Project Standard 2019
197 | Office Publisher 2019
198 | Office Skype for Business 2019
199 | Office Standard 2019
200 | Office Visio Pro 2019
201 | Office Visio Standard 2019
202 | Office Word 2019

- Source Code:
You can download source code on [https://forums.mydigitallife.info/threads/50234-Emulated-KMS-Servers-on-non-Windows-platforms](https://forums.mydigitallife.info/threads/50234-Emulated-KMS-Servers-on-non-Windows-platforms)

- Key:
You can find key on [https://technet.microsoft.com/en-us/library/jj612867.aspx](https://technet.microsoft.com/en-us/library/jj612867.aspx)

* https://docs.microsoft.com/en-us/windows-server/get-started/kmsclientkeys