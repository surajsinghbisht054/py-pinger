# py-pinger (High-Speed Ping Sweeping Script written in python)

######################################################
			By S.S.B Group							
######################################################

	Suraj Singh
	Admin
	S.S.B Group
	surajsinghbisht054@gmail.com
	https://hackworldwithssb.blogspot.in

	Note: We Feel Proud To Be Indian
######################################################

#	High-Speed Ping Sweeping Script written in python

#Features:
	High-Speed Ping Sweep.
	Stable Script
	Cross-platform Supported
	Result Save as txt
	Unique feature of input:
	In this Script For Providing IP Address Range. You Have To Provide Input Like Example Given Below:

	for e.g: Our Ip Address = 192.168.10.1

	You will Provide input like this = 192:168:10:1  (Change "." into ":")

	First, Split 192.168.10.1 in 4 Sections. 

	Section 1 =  192
	Section 2 =  168
	Section 3 =  10
	Section 4 =  1

	Now, In Each Section, Choose Your Ip Address Digits Sperated by Commas or Provide Range.

	e.g:  section 1 = 100-115,120,130,155-180

	After Thats Join These Number with The Help of This Symbol ":"  Examples: 

	=> 192:168:10:1-15,18,25
	=> 192-195:168:10:1
	=> 192-192,200:168-170:10-5:1-15

example Q.1:

	192.168.10.1,
	192.168.10.2,
	192.168.10.3,
	192.168.10.4,
	192.168.10.5,
	192.168.10.6,
	192.168.10.7,

Ans. 192:168:10:1-7

Example Q.2: 

	112.168.10.1
	113.168.10.1
	114.168.10.1
	155.168.10.1
	196.168.10.1
	197.168.10.1
	198.168.10.1
	199.168.10.1

Ans. 112-114,155,196-199:168:10:1	

Example 3:
	
	192-199,212,250:150-168,173:10-16,19:1-10



#Usage: 
	pypinger.py [options] 

Options:
  --version             show program's version number and exit
  -h, --help            show this help message and exit
  -i TARGET, --target=TARGET
                        Specify IP Addresses Range For Scan. Eg:- 192:168:10:1-7
  -t THREAD, --thread=THREAD
                        Specify Number of Thread For Scanning
  -o OUTPUT, --output=OUTPUT
                        Specify Path For Saving Output in Txt.
  -c TIMEOUT, --timeout=TIMEOUT
                        Specify No. Of Request Per IP


#Usages Example:

	python pypinger.py -i 192:168:10:1-100

More For Information Read Script Readme Txt Files


Thanks For Using My Script
Feel Free For Contribution or
for Joining Our Group
Written By
S.S.B 
surajsinghbisht054@gmail.com


