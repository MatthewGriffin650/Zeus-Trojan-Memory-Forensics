Microsoft Windows \[Version 10.0.26300.9550]

(c) Microsoft Corporation. All rights reserved.



C:\\Users\\DatTw>cd C:\\Users\\DatTw\\Downloads\\volatility\_2.6\_win64\_standalone\\volatility\_2.6\_win64\_standalone



C:\\Users\\DatTw\\Downloads\\volatility\_2.6\_win64\_standalone\\volatility\_2.6\_win64\_standalone>dir

&#x20;Volume in drive C is Windows-SSD

&#x20;Volume Serial Number is 1232-84DB



&#x20;Directory of C:\\Users\\DatTw\\Downloads\\volatility\_2.6\_win64\_standalone\\volatility\_2.6\_win64\_standalone



10/11/2026  05:07 PM    <DIR>          .

10/11/2026  05:07 PM    <DIR>          ..

10/11/2026  05:07 PM               778 AUTHORS.txt

10/11/2026  05:07 PM             3,917 CREDITS.txt

10/11/2026  05:07 PM               698 LEGAL.txt

10/11/2026  05:07 PM            15,127 LICENSE.txt

10/11/2026  05:07 PM            31,879 README.txt

10/11/2026  05:07 PM        15,794,079 volatility\_2.6\_win64\_standalone.exe

&#x20;              6 File(s)     15,846,478 bytes

&#x20;              2 Dir(s)  190,023,589,888 bytes free



C:\\Users\\DatTw\\Downloads\\volatility\_2.6\_win64\_standalone\\volatility\_2.6\_win64\_standalone>volatility\_2.6\_win64\_standalone.exe -h

Volatility Foundation Volatility Framework 2.6

Usage: Volatility - A memory forensics analysis platform.



Options:

&#x20; -h, --help            list all available options and their default values.

&#x20;                       Default values may be set in the configuration file

&#x20;                       (/etc/volatilityrc)

&#x20; --conf-file=.volatilityrc

&#x20;                       User based configuration file

&#x20; -d, --debug           Debug volatility

&#x20; --plugins=PLUGINS     Additional plugin directories to use (semi-colon

&#x20;                       separated)

&#x20; --info                Print information about all registered objects

&#x20; --cache-directory=C:\\Users\\DatTw/.cache\\volatility

&#x20;                       Directory where cache files are stored

&#x20; --cache               Use caching

&#x20; --tz=TZ               Sets the (Olson) timezone for displaying timestamps

&#x20;                       using pytz (if installed) or tzset

&#x20; -f FILENAME, --filename=FILENAME

&#x20;                       Filename to use when opening an image

&#x20; --profile=WinXPSP2x86

&#x20;                       Name of the profile to load (use --info to see a list

&#x20;                       of supported profiles)

&#x20; -l LOCATION, --location=LOCATION

&#x20;                       A URN location from which to load an address space

&#x20; -w, --write           Enable write support

&#x20; --dtb=DTB             DTB Address

&#x20; --shift=SHIFT         Mac KASLR shift address

&#x20; --output=text         Output in this format (support is module specific, see

&#x20;                       the Module Output Options below)

&#x20; --output-file=OUTPUT\_FILE

&#x20;                       Write output in this file

&#x20; -v, --verbose         Verbose information

&#x20; -g KDBG, --kdbg=KDBG  Specify a KDBG virtual address (Note: for 64-bit

&#x20;                       Windows 8 and above this is the address of

&#x20;                       KdCopyDataBlock)

&#x20; --force               Force utilization of suspect profile

&#x20; --cookie=COOKIE       Specify the address of nt!ObHeaderCookie (valid for

&#x20;                       Windows 10 only)

&#x20; -k KPCR, --kpcr=KPCR  Specify a specific KPCR address



&#x20;       Supported Plugin Commands:



&#x20;               amcache         Print AmCache information

&#x20;               apihooks        Detect API hooks in process and kernel memory

&#x20;               atoms           Print session and window station atom tables

&#x20;               atomscan        Pool scanner for atom tables

&#x20;               auditpol        Prints out the Audit Policies from HKLM\\SECURITY\\Policy\\PolAdtEv

&#x20;               bigpools        Dump the big page pools using BigPagePoolScanner

&#x20;               bioskbd         Reads the keyboard buffer from Real Mode memory

&#x20;               cachedump       Dumps cached domain hashes from memory

&#x20;               callbacks       Print system-wide notification routines

&#x20;               clipboard       Extract the contents of the windows clipboard

&#x20;               cmdline         Display process command-line arguments

&#x20;               cmdscan         Extract command history by scanning for \_COMMAND\_HISTORY

&#x20;               connections     Print list of open connections \[Windows XP and 2003 Only]

&#x20;               connscan        Pool scanner for tcp connections

&#x20;               consoles        Extract command history by scanning for \_CONSOLE\_INFORMATION

&#x20;               crashinfo       Dump crash-dump information

&#x20;               deskscan        Poolscaner for tagDESKTOP (desktops)

&#x20;               devicetree      Show device tree

&#x20;               dlldump         Dump DLLs from a process address space

&#x20;               dlllist         Print list of loaded dlls for each process

&#x20;               driverirp       Driver IRP hook detection

&#x20;               drivermodule    Associate driver objects to kernel modules

&#x20;               driverscan      Pool scanner for driver objects

&#x20;               dumpcerts       Dump RSA private and public SSL keys

&#x20;               dumpfiles       Extract memory mapped and cached files

&#x20;               dumpregistry    Dumps registry files out to disk

&#x20;               editbox         Displays information about Edit controls. (Listbox experimental.)

&#x20;               envars          Display process environment variables

&#x20;               eventhooks      Print details on windows event hooks

&#x20;               evtlogs         Extract Windows Event Logs (XP/2003 only)

&#x20;               filescan        Pool scanner for file objects

&#x20;               gahti           Dump the USER handle type information

&#x20;               gditimers       Print installed GDI timers and callbacks

&#x20;               gdt             Display Global Descriptor Table

&#x20;               getservicesids  Get the names of services in the Registry and return Calculated SID

&#x20;               getsids         Print the SIDs owning each process

&#x20;               handles         Print list of open handles for each process

&#x20;               hashdump        Dumps passwords hashes (LM/NTLM) from memory

&#x20;               hibinfo         Dump hibernation file information

&#x20;               hivedump        Prints out a hive

&#x20;               hivelist        Print list of registry hives.

&#x20;               hivescan        Pool scanner for registry hives

&#x20;               hpakextract     Extract physical memory from an HPAK file

&#x20;               hpakinfo        Info on an HPAK file

&#x20;               idt             Display Interrupt Descriptor Table

&#x20;               iehistory       Reconstruct Internet Explorer cache / history

&#x20;               imagecopy       Copies a physical address space out as a raw DD image

&#x20;               imageinfo       Identify information for the image

&#x20;               impscan         Scan for calls to imported functions

&#x20;               joblinks        Print process job link information

&#x20;               kdbgscan        Search for and dump potential KDBG values

&#x20;               kpcrscan        Search for and dump potential KPCR values

&#x20;               ldrmodules      Detect unlinked DLLs

&#x20;               lsadump         Dump (decrypted) LSA secrets from the registry

&#x20;               machoinfo       Dump Mach-O file format information

&#x20;               malfind         Find hidden and injected code

&#x20;               mbrparser       Scans for and parses potential Master Boot Records (MBRs)

&#x20;               memdump         Dump the addressable memory for a process

&#x20;               memmap          Print the memory map

&#x20;               messagehooks    List desktop and thread window message hooks

&#x20;               mftparser       Scans for and parses potential MFT entries

&#x20;               moddump         Dump a kernel driver to an executable file sample

&#x20;               modscan         Pool scanner for kernel modules

&#x20;               modules         Print list of loaded modules

&#x20;               multiscan       Scan for various objects at once

&#x20;               mutantscan      Pool scanner for mutex objects

&#x20;               notepad         List currently displayed notepad text

&#x20;               objtypescan     Scan for Windows object type objects

&#x20;               patcher         Patches memory based on page scans

&#x20;               poolpeek        Configurable pool scanner plugin

&#x20;               printkey        Print a registry key, and its subkeys and values

&#x20;               privs           Display process privileges

&#x20;               procdump        Dump a process to an executable file sample

&#x20;               pslist          Print all running processes by following the EPROCESS lists

&#x20;               psscan          Pool scanner for process objects

&#x20;               pstree          Print process list as a tree

&#x20;               psxview         Find hidden processes with various process listings

&#x20;               qemuinfo        Dump Qemu information

&#x20;               raw2dmp         Converts a physical memory sample to a windbg crash dump

&#x20;               screenshot      Save a pseudo-screenshot based on GDI windows

&#x20;               servicediff     List Windows services (ala Plugx)

&#x20;               sessions        List details on \_MM\_SESSION\_SPACE (user logon sessions)

&#x20;               shellbags       Prints ShellBags info

&#x20;               shimcache       Parses the Application Compatibility Shim Cache registry key

&#x20;               shutdowntime    Print ShutdownTime of machine from registry

&#x20;               sockets         Print list of open sockets

&#x20;               sockscan        Pool scanner for tcp socket objects

&#x20;               ssdt            Display SSDT entries

&#x20;               strings         Match physical offsets to virtual addresses (may take a while, VERY verbose)

&#x20;               svcscan         Scan for Windows services

&#x20;               symlinkscan     Pool scanner for symlink objects

&#x20;               thrdscan        Pool scanner for thread objects

&#x20;               threads         Investigate \_ETHREAD and \_KTHREADs

&#x20;               timeliner       Creates a timeline from various artifacts in memory

&#x20;               timers          Print kernel timers and associated module DPCs

&#x20;               truecryptmaster Recover TrueCrypt 7.1a Master Keys

&#x20;               truecryptpassphrase     TrueCrypt Cached Passphrase Finder

&#x20;               truecryptsummary        TrueCrypt Summary

&#x20;               unloadedmodules Print list of unloaded modules

&#x20;               userassist      Print userassist registry keys and information

&#x20;               userhandles     Dump the USER handle tables

&#x20;               vaddump         Dumps out the vad sections to a file

&#x20;               vadinfo         Dump the VAD info

&#x20;               vadtree         Walk the VAD tree and display in tree format

&#x20;               vadwalk         Walk the VAD tree

&#x20;               vboxinfo        Dump virtualbox information

&#x20;               verinfo         Prints out the version information from PE images

&#x20;               vmwareinfo      Dump VMware VMSS/VMSN information

&#x20;               volshell        Shell in the memory image

&#x20;               windows         Print Desktop Windows (verbose details)

&#x20;               wintree         Print Z-Order Desktop Windows Tree

&#x20;               wndscan         Pool scanner for window stations

&#x20;               yarascan        Scan process or kernel memory with Yara signatures



C:\\Users\\DatTw\\Downloads\\volatility\_2.6\_win64\_standalone\\volatility\_2.6\_win64\_standalone>volatility\_2.6\_win64\_standalone.exe -f zeus.vmem imageinfo

Volatility Foundation Volatility Framework 2.6

INFO    : volatility.debug    : Determining profile based on KDBG search...

&#x20;         Suggested Profile(s) : WinXPSP2x86, WinXPSP3x86 (Instantiated with WinXPSP2x86)

&#x20;                    AS Layer1 : IA32PagedMemoryPae (Kernel AS)

&#x20;                    AS Layer2 : FileAddressSpace (C:\\Users\\DatTw\\Downloads\\volatility\_2.6\_win64\_standalone\\volatility\_2.6\_win64\_standalone\\zeus.vmem)

&#x20;                     PAE type : PAE

&#x20;                          DTB : 0x319000L

&#x20;                         KDBG : 0x80544ce0L

&#x20;         Number of Processors : 1

&#x20;    Image Type (Service Pack) : 2

&#x20;               KPCR for CPU 0 : 0xffdff000L

&#x20;            KUSER\_SHARED\_DATA : 0xffdf0000L

&#x20;          Image date and time : 2010-08-15 19:17:56 UTC+0000

&#x20;    Image local date and time : 2010-08-15 15:17:56 -0400



C:\\Users\\DatTw\\Downloads\\volatility\_2.6\_win64\_standalone\\volatility\_2.6\_win64\_standalone>volatility\_2.6\_win64\_standalone.exe -f zeus.vmem connscan

Volatility Foundation Volatility Framework 2.6

Offset(P)  Local Address             Remote Address            Pid

\---------- ------------------------- ------------------------- ---

0x02214988 172.16.176.143:1054       193.104.41.75:80          856

0x06015ab0 0.0.0.0:1056              193.104.41.75:80          856



C:\\Users\\DatTw\\Downloads\\volatility\_2.6\_win64\_standalone\\volatility\_2.6\_win64\_standalone>volatility\_2.6\_win64\_standalone.exe -f zeus.vmem pstree

Volatility Foundation Volatility Framework 2.6

Name                                                  Pid   PPid   Thds   Hnds Time

\-------------------------------------------------- ------ ------ ------ ------ ----

&#x20;0x810b1660:System                                      4      0     58    379 1970-01-01 00:00:00 UTC+0000

. 0xff2ab020:smss.exe                                 544      4      3     21 2010-08-11 06:06:21 UTC+0000

.. 0xff1ec978:winlogon.exe                            632    544     24    536 2010-08-11 06:06:23 UTC+0000

... 0xff255020:lsass.exe                              688    632     21    405 2010-08-11 06:06:24 UTC+0000

... 0xff247020:services.exe                           676    632     16    288 2010-08-11 06:06:24 UTC+0000

.... 0xff1b8b28:vmtoolsd.exe                         1668    676      5    225 2010-08-11 06:06:35 UTC+0000

..... 0xff224020:cmd.exe                              124   1668      0 ------ 2010-08-15 19:17:55 UTC+0000

.... 0x80ff88d8:svchost.exe                           856    676     29    336 2010-08-11 06:06:24 UTC+0000

.... 0xff1d7da0:spoolsv.exe                          1432    676     14    145 2010-08-11 06:06:26 UTC+0000

.... 0x80fbf910:svchost.exe                          1028    676     88   1424 2010-08-11 06:06:24 UTC+0000

..... 0x80f60da0:wuauclt.exe                         1732   1028      7    189 2010-08-11 06:07:44 UTC+0000

..... 0x80f94588:wuauclt.exe                          468   1028      4    142 2010-08-11 06:09:37 UTC+0000

..... 0xff364310:wscntfy.exe                          888   1028      1     40 2010-08-11 06:06:49 UTC+0000

.... 0xff217560:svchost.exe                           936    676     11    288 2010-08-11 06:06:24 UTC+0000

.... 0xff143b28:TPAutoConnSvc.e                      1968    676      5    106 2010-08-11 06:06:39 UTC+0000

..... 0xff38b5f8:TPAutoConnect.e                     1084   1968      1     68 2010-08-11 06:06:52 UTC+0000

.... 0xff22d558:svchost.exe                          1088    676      7     93 2010-08-11 06:06:25 UTC+0000

.... 0xff218230:vmacthlp.exe                          844    676      1     37 2010-08-11 06:06:24 UTC+0000

.... 0xff25a7e0:alg.exe                               216    676      8    120 2010-08-11 06:06:39 UTC+0000

.... 0xff203b80:svchost.exe                          1148    676     15    217 2010-08-11 06:06:26 UTC+0000

.... 0xff1fdc88:VMUpgradeHelper                      1788    676      5    112 2010-08-11 06:06:38 UTC+0000

.. 0xff1ecda0:csrss.exe                               608    544     10    410 2010-08-11 06:06:23 UTC+0000

&#x20;0xff3865d0:explorer.exe                             1724   1708     13    326 2010-08-11 06:09:29 UTC+0000

. 0xff374980:VMwareUser.exe                           452   1724      8    207 2010-08-11 06:09:32 UTC+0000

. 0xff3667e8:VMwareTray.exe                           432   1724      1     60 2010-08-11 06:09:31 UTC+0000



C:\\Users\\DatTw\\Downloads\\volatility\_2.6\_win64\_standalone\\volatility\_2.6\_win64\_standalone>volatility\_2.6\_win64\_standalone.exe -f zeus.vmem pstree | findstr 856

Volatility Foundation Volatility Framework 2.6

.... 0x80ff88d8:svchost.exe                           856    676     29    336 2010-08-11 06:06:24 UTC+0000



C:\\Users\\DatTw\\Downloads\\volatility\_2.6\_win64\_standalone\\volatility\_2.6\_win64\_standalone>volatility\_2.6\_win64\_standalone.exe -f zeus.vmem printkey -K "Microsoft\\Windows NT\\CurrentVersion\\Winlogon

Volatility Foundation Volatility Framework 2.6

Legend: (S) = Stable   (V) = Volatile



\----------------------------

Registry: \\Device\\HarddiskVolume1\\WINDOWS\\system32\\config\\software

Key name: Winlogon (S)

Last updated: 2010-08-15 19:17:23 UTC+0000



Subkeys:

&#x20; (S) GPExtensions

&#x20; (S) Notify

&#x20; (S) SpecialAccounts

&#x20; (V) Credentials



Values:

REG\_DWORD     AutoRestartShell : (S) 1

REG\_SZ        DefaultDomainName : (S) BILLY-DB5B96DD3

REG\_SZ        DefaultUserName : (S) Administrator

REG\_SZ        LegalNoticeCaption : (S)

REG\_SZ        LegalNoticeText : (S)

REG\_SZ        PowerdownAfterShutdown : (S) 0

REG\_SZ        ReportBootOk    : (S) 1

REG\_SZ        Shell           : (S) Explorer.exe

REG\_SZ        ShutdownWithoutLogon : (S) 0

REG\_SZ        System          : (S)

REG\_SZ        Userinit        : (S) C:\\WINDOWS\\system32\\userinit.exe,C:\\WINDOWS\\system32\\sdra64.exe,

REG\_SZ        VmApplet        : (S) rundll32 shell32,Control\_RunDLL "sysdm.cpl"

REG\_DWORD     SfcQuota        : (S) 4294967295

REG\_SZ        allocatecdroms  : (S) 0

REG\_SZ        allocatedasd    : (S) 0

REG\_SZ        allocatefloppies : (S) 0

REG\_SZ        cachedlogonscount : (S) 10

REG\_DWORD     forceunlocklogon : (S) 0

REG\_DWORD     passwordexpirywarning : (S) 14

REG\_SZ        scremoveoption  : (S) 0

REG\_DWORD     AllowMultipleTSSessions : (S) 1

REG\_EXPAND\_SZ UIHost          : (S) logonui.exe

REG\_DWORD     LogonType       : (S) 1

REG\_SZ        Background      : (S) 0 0 0

REG\_SZ        AutoAdminLogon  : (S) 0

REG\_SZ        DebugServerCommand : (S) no

REG\_DWORD     SFCDisable      : (S) 0

REG\_SZ        WinStationsDisabled : (S) 0

REG\_DWORD     HibernationPreviouslyEnabled : (S) 1

REG\_DWORD     ShowLogonOptions : (S) 0

REG\_SZ        AltDefaultUserName : (S) Administrator

REG\_SZ        AltDefaultDomainName : (S) BILLY-DB5B96DD3



C:\\Users\\DatTw\\Downloads\\volatility\_2.6\_win64\_standalone\\volatility\_2.6\_win64\_standalone>mkdir evidence



C:\\Users\\DatTw\\Downloads\\volatility\_2.6\_win64\_standalone\\volatility\_2.6\_win64\_standalone>volatility\_2.6\_win64\_standalone -f zeus.vmem malfind -p 856 --dump-dir evidence/

Volatility Foundation Volatility Framework 2.6

Process: svchost.exe Pid: 856 Address: 0xb70000

Vad Tag: VadS Protection: PAGE\_EXECUTE\_READWRITE

Flags: CommitCharge: 38, MemCommit: 1, PrivateMemory: 1, Protection: 6



0x00b70000  4d 5a 90 00 03 00 00 00 04 00 00 00 ff ff 00 00   MZ..............

0x00b70010  b8 00 00 00 00 00 00 00 40 00 00 00 00 00 00 00   ........@.......

0x00b70020  00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00   ................

0x00b70030  00 00 00 00 00 00 00 00 00 00 00 00 d0 00 00 00   ................



0x00b70000 4d               DEC EBP

0x00b70001 5a               POP EDX

0x00b70002 90               NOP

0x00b70003 0003             ADD \[EBX], AL

0x00b70005 0000             ADD \[EAX], AL

0x00b70007 000400           ADD \[EAX+EAX], AL

0x00b7000a 0000             ADD \[EAX], AL

0x00b7000c ff               DB 0xff

0x00b7000d ff00             INC DWORD \[EAX]

0x00b7000f 00b800000000     ADD \[EAX+0x0], BH

0x00b70015 0000             ADD \[EAX], AL

0x00b70017 004000           ADD \[EAX+0x0], AL

0x00b7001a 0000             ADD \[EAX], AL

0x00b7001c 0000             ADD \[EAX], AL

0x00b7001e 0000             ADD \[EAX], AL

0x00b70020 0000             ADD \[EAX], AL

0x00b70022 0000             ADD \[EAX], AL

0x00b70024 0000             ADD \[EAX], AL

0x00b70026 0000             ADD \[EAX], AL

0x00b70028 0000             ADD \[EAX], AL

0x00b7002a 0000             ADD \[EAX], AL

0x00b7002c 0000             ADD \[EAX], AL

0x00b7002e 0000             ADD \[EAX], AL

0x00b70030 0000             ADD \[EAX], AL

0x00b70032 0000             ADD \[EAX], AL

0x00b70034 0000             ADD \[EAX], AL

0x00b70036 0000             ADD \[EAX], AL

0x00b70038 0000             ADD \[EAX], AL

0x00b7003a 0000             ADD \[EAX], AL

0x00b7003c d000             ROL BYTE \[EAX], 0x1

0x00b7003e 0000             ADD \[EAX], AL



Process: svchost.exe Pid: 856 Address: 0xcb0000

Vad Tag: VadS Protection: PAGE\_EXECUTE\_READWRITE

Flags: CommitCharge: 1, MemCommit: 1, PrivateMemory: 1, Protection: 6



0x00cb0000  b8 35 00 00 00 e9 cd d7 c5 7b 00 00 00 00 00 00   .5.......{......

0x00cb0010  00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00   ................

0x00cb0020  00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00   ................

0x00cb0030  00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00   ................



0x00cb0000 b835000000       MOV EAX, 0x35

0x00cb0005 e9cdd7c57b       JMP 0x7c90d7d7

0x00cb000a 0000             ADD \[EAX], AL

0x00cb000c 0000             ADD \[EAX], AL

0x00cb000e 0000             ADD \[EAX], AL

0x00cb0010 0000             ADD \[EAX], AL

0x00cb0012 0000             ADD \[EAX], AL

0x00cb0014 0000             ADD \[EAX], AL

0x00cb0016 0000             ADD \[EAX], AL

0x00cb0018 0000             ADD \[EAX], AL

0x00cb001a 0000             ADD \[EAX], AL

0x00cb001c 0000             ADD \[EAX], AL

0x00cb001e 0000             ADD \[EAX], AL

0x00cb0020 0000             ADD \[EAX], AL

0x00cb0022 0000             ADD \[EAX], AL

0x00cb0024 0000             ADD \[EAX], AL

0x00cb0026 0000             ADD \[EAX], AL

0x00cb0028 0000             ADD \[EAX], AL

0x00cb002a 0000             ADD \[EAX], AL

0x00cb002c 0000             ADD \[EAX], AL

0x00cb002e 0000             ADD \[EAX], AL

0x00cb0030 0000             ADD \[EAX], AL

0x00cb0032 0000             ADD \[EAX], AL

0x00cb0034 0000             ADD \[EAX], AL

0x00cb0036 0000             ADD \[EAX], AL

0x00cb0038 0000             ADD \[EAX], AL

0x00cb003a 0000             ADD \[EAX], AL

0x00cb003c 0000             ADD \[EAX], AL

0x00cb003e 0000             ADD \[EAX], AL





C:\\Users\\DatTw\\Downloads\\volatility\_2.6\_win64\_standalone\\volatility\_2.6\_win64\_standalone>certUtil -hashfile evidence/process.0x80ff88d8.0xb70000.dmp SHA256

SHA256 hash of evidence/process.0x80ff88d8.0xb70000.dmp:

8e3be5dc65aa35d68fd2aba1d3d9bf0f40d5118fe22eb2e6c97c8463bd1f1ba1

CertUtil: -hashfile command completed successfully.



C:\\Users\\DatTw\\Downloads\\volatility\_2.6\_win64\_standalone\\volatility\_2.6\_win64\_standalone>volatility\_2.6\_win64\_standalone -f zeus.vmem mutantscan

Volatility Foundation Volatility Framework 2.6

Offset(P)              #Ptr     #Hnd Signal Thread           CID Name

\------------------ -------- -------- ------ ---------- --------- ----

0x00000000000962c0        1        1      1 0x00000000

0x00000000007c0840        1        1      1 0x00000000

0x00000000009d86e0        1        1      1 0x00000000

0x00000000009d90d8        1        1      1 0x00000000

0x0000000000eda878        1        1      1 0x00000000

0x0000000000edae88        1        1      1 0x00000000

0x000000000105a278        1        1      1 0x00000000

0x000000000105a2e8        1        1      1 0x00000000

0x000000000105aa38        7        6      1 0x00000000           \_!MSFTHISTORY!\_

0x000000000105acf0        2        1      0 0xff3ba880   888:912 wscntfy\_mtx

0x000000000105e900        1        1      1 0x00000000

0x0000000001061fe0        2        1      1 0x00000000           542B5ABE01CB391B000003A82

0x00000000010633b8        2        1      1 0x00000000           msgina: InteractiveLogonRequestMutex

0x0000000001066480        2        1      1 0x00000000           PerfOS\_Perf\_Library\_Lock\_PID\_684

0x00000000010669d0        2        1      1 0x00000000           winlogon: Logon UserProfileMapping Mutex

0x0000000001066bd0        2        1      1 0x00000000           PerfProc\_Perf\_Library\_Lock\_PID\_684

0x00000000010676d8        2        1      1 0x00000000           RemoteAccess\_Perf\_Library\_Lock\_PID\_684

0x0000000001067d60        1        1      1 0x00000000

0x0000000001069fa8        2        1      1 0x00000000           WmiApRpl\_Perf\_Library\_Lock\_PID\_684

0x000000000106fb60        3        2      1 0x00000000           WininetProxyRegistryMutex

0x0000000001070380        2        1      1 0x00000000           Spooler\_Perf\_Library\_Lock\_PID\_684

0x00000000010719b0        2        1      1 0x00000000           ContentFilter\_Perf\_Library\_Lock\_PID\_684

0x0000000001071e40        1        1      1 0x00000000

0x000000000107a2b0        2        1      1 0x00000000           54D23F5A01CB391B0000047C2

0x000000000107b290        2        1      1 0x00000000           c:!windows!system32!config!systemprofile!cookies!

0x000000000107c200        1        1      1 0x00000000

0x000000000108af60        1        1      1 0x00000000

0x0000000001093568        1        1      1 0x00000000

0x0000000001093c10        1        1      1 0x00000000

0x0000000001093c90        4        3      1 0x00000000           ZonesLockedCacheCounterMutex

0x00000000010af880        1        1      1 0x00000000

0x00000000010b7f68        1        1      1 0x00000000

0x00000000010bb748        1        1      1 0x00000000

0x00000000010bb7b8        1        1      1 0x00000000

0x00000000010bbf10        2        1      1 0x00000000           Tcpip\_Perf\_Library\_Lock\_PID\_684

0x00000000010bc140        2        1      1 0x00000000           MSDTC\_Perf\_Library\_Lock\_PID\_684

0x00000000010bc550        2        1      1 0x00000000           PerfDisk\_Perf\_Library\_Lock\_PID\_684

0x00000000010bc750        2        1      1 0x00000000           PerfNet\_Perf\_Library\_Lock\_PID\_684

0x00000000010bc7f8        1        1      1 0x00000000

0x00000000010bcc38        2        1      1 0x00000000           TapiSrv\_Perf\_Library\_Lock\_PID\_684

0x00000000010bed60        2        1      1 0x00000000           TermService\_Perf\_Library\_Lock\_PID\_684

0x00000000010c2c60        1        1      1 0x00000000

0x00000000010c2cd0        1        1      1 0x00000000

0x00000000010c46f0        1        1      1 0x00000000

0x00000000010c7cf0        1        1      1 0x00000000

0x00000000010c9898        4        3      1 0x00000000           ZonesCounterMutex

0x00000000010d4030        2        1      1 0x00000000           ISAPISearch\_Perf\_Library\_Lock\_PID\_684

0x00000000010d61e8        2        1      1 0x00000000           userenv: User Registry policy mutex

0x00000000010d7de8        1        1      1 0x00000000

0x00000000010d9a50        2        1      1 0x00000000           53AF607601CB391B000002A42

0x00000000010dd398        2        1      1 0x00000000           ContentIndex\_Perf\_Library\_Lock\_PID\_684

0x000000000110c530        1        1      1 0x00000000

0x0000000001113cc8        1        1      1 0x00000000

0x0000000001116218        1        1      1 0x00000000

0x0000000001119730        2        1      1 0x00000000           RAS\_MO\_02

0x000000000111bfe0        1        1      1 0x00000000

0x000000000111eb40        2        1      1 0x00000000           c:!windows!system32!config!systemprofile!local settings!history!history.ie5!

0x00000000011211a8        4        3      1 0x00000000           ZonesCacheCounterMutex

0x000000000112cad0        1        1      1 0x00000000

0x000000000112d0e0        1        1      1 0x00000000

0x000000000112da78        2        1      1 0x00000000           5C9DCF9C01CB391B000007B02

0x000000000112f388        3        2      1 0x00000000           SRDataStore

0x000000000112f688        2        1      1 0x00000000           55319D6A01CB391B000005982

0x0000000001130ef8        3        2      1 0x00000000           c:!documents and settings!administrator!cookies!

0x0000000001133f48        1        1      1 0x00000000

0x000000000113f1b8        2        1      1 0x00000000           c:!windows!system32!config!systemprofile!local settings!temporary internet files!content.ie5!

0x000000000113fd28        1        1      1 0x00000000

0x00000000011465c8        3        2      1 0x00000000           c:!documents and settings!administrator!local settings!temporary internet files!content.ie5!

0x000000000114e9c0        2        1      1 0x00000000           userenv: Machine Registry policy mutex

0x0000000001152150        1        1      1 0x00000000

0x0000000001159760        1        1      1 0x00000000

0x000000000115e988        1        1      1 0x00000000

0x000000000115ed38        2        1      1 0x00000000           SingleSesMutex

0x000000000115f628        2        1      0 0xff398638  1732:680 Instance0:  ESENT Performance Data Schema Version 40

0x00000000011627c8        1        1      1 0x00000000

0x00000000011633c0        2        1      1 0x00000000           839553D201CB391B000006C42

0x0000000001163898        2        1      1 0x00000000           C1EA8C7801CB391B000006BC2

0x0000000001166e20        1        1      1 0x00000000

0x00000000011875d8        1        1      1 0x00000000

0x000000000118b330        1        1      1 0x00000000

0x000000000118c228        1        1      1 0x00000000

0x000000000118d2d0        1        1      1 0x00000000

0x000000000118d640        1        1      1 0x00000000

0x0000000001190288        1        1      1 0x00000000

0x000000000211a230        5        4      1 0x00000000           TpVcW32ListMutex

0x00000000024c9ef8        2        1      1 0x00000000           PSched\_Perf\_Library\_Lock\_PID\_684

0x0000000002ae49b0        1        1      1 0x00000000

0x0000000002e2c4b0        1        1      1 0x00000000

0x00000000043d21b8        2        1      1 0x00000000           53EAFB4001CB391B0000034C2

0x00000000043d62a0        2        1      1 0x00000000           0CADFD67AF62496dB34264F000F5624A

0x00000000043d6e18        1        1      1 0x00000000

0x000000000441a380        2        1      1 0x00000000           C3CCBBD401CB391B000001C42

0x000000000445c2c8        1        1      1 0x00000000

0x000000000445cec8        1        1      1 0x00000000

0x000000000485e548        1        1      1 0x00000000

0x0000000004861550        1        1      1 0x00000000

0x0000000004866dc8        2        1      1 0x00000000           c:!documents and settings!networkservice!local settings!history!history.ie5!

0x000000000486b0f8        1        1      1 0x00000000

0x00000000048f8fb0        2        1      1 0x00000000           543E6D8E01CB391B000004402

0x000000000493faa8        1        1      1 0x00000000

0x0000000004a064f8        9        8      1 0x00000000           ShimCacheMutex

0x0000000004a06c00        2        1      1 0x00000000           5A50EAC601CB391B000006842

0x0000000004a4ad70        2        1      1 0x00000000           647C72AE01CB391B0000043C2

0x0000000004a50740        1        1      1 0x00000000

0x0000000004a97110        1        1      1 0x00000000

0x0000000004b58900        2        1      1 0x00000000           6303BF2201CB391B000003782

0x0000000004b5c608        1        1      1 0x00000000

0x0000000004b5c668        2        1      1 0x00000000           HGFSMUTEX00000000000242b4

0x0000000004be2778        1        1      1 0x00000000

0x0000000004be4410        2        1      1 0x00000000           userenv: user policy mutex

0x0000000004c2d6b8        2        1      1 0x00000000           5C2B5EBC01CB391B000006FC2

0x00000000052af290        1        1      1 0x00000000

0x00000000052af2d0        1        1      1 0x00000000

0x00000000054707e0        2        1      1 0x00000000           238FAD3109D3473aB4764B20B3731840

0x00000000054714b0        3        2      1 0x00000000           c:!documents and settings!localservice!local settings!temporary internet files!content.ie5!

0x00000000054716f8        2        1      1 0x00000000           4FCC0DEFE22C4f138FB9D5AF25FD9398

0x00000000054b2a48        1        1      1 0x00000000

0x00000000054b2ab8        1        1      1 0x00000000

0x00000000054f30c0        1        1      1 0x00000000

0x0000000005534f48        1        1      1 0x00000000

0x00000000055379d8        2        1      1 0x00000000           WPA\_LICSTORE\_MUTEX

0x0000000005537a28        2        1      1 0x00000000           WPA\_HWID\_MUTEX

0x0000000005537a78        2        1      1 0x00000000           WPA\_LT\_MUTEX

0x0000000005537ac8        2        1      1 0x00000000           WPA\_RT\_MUTEX

0x00000000055fe480        2        1      1 0x00000000           WPA\_PR\_MUTEX

0x00000000055fe538        1        1      1 0x00000000

0x00000000058020d0        1        1      1 0x00000000

0x00000000058021f0        1        1      1 0x00000000

0x00000000058022d0        1        1      1 0x00000000

0x00000000058024f0        1        1      1 0x00000000

0x0000000005802868        1        1      1 0x00000000

0x0000000005b949a0        1        1      1 0x00000000

0x0000000005c16378        2        1      1 0x00000000           c:!documents and settings!networkservice!cookies!

0x0000000005c18f08        3        2      1 0x00000000           MidiMapper\_modLongMessage\_RefCnt

0x0000000005c9f978        2        1      1 0x00000000           C70DD0D201CB391B000001D42

0x0000000005c9fb30        2        1      1 0x00000000           5CE2F3CE01CB391B000000D82

0x0000000005ca17e8        2        1      1 0x00000000           \_AVIRA\_2108

0x0000000005ce3e60        2        1      1 0x00000000           C39837F001CB391B000001B02

0x0000000005ce5dd0        2        1      1 0x00000000           \_SHuassist.mtx

0x0000000005d281f0        2        1      1 0x00000000           746bbf3569adEncrypt

0x0000000005d2a258        1        1      1 0x00000000

0x0000000005d2a440        1        1      1 0x00000000

0x0000000005e32020        1        1      1 0x00000000

0x0000000005e320f0        1        1      1 0x00000000

0x0000000005e36c08        1        1      1 0x00000000

0x0000000005e7ffe0        3        2      1 0x00000000           MidiMapper\_Configure

0x0000000005f01c68        2        1      1 0x00000000           ExplorerIsShellMutex

0x0000000005f02378        1        1      1 0x00000000

0x0000000005f024d8        2        1      1 0x00000000           RAS\_MO\_01

0x0000000005f45148        7        6      1 0x00000000           SHIMLIB\_LOG\_MUTEX

0x0000000005f45528        1        1      1 0x00000000

0x0000000005f45908        1        1      1 0x00000000

0x0000000005f45e48        2        1      1 0x00000000           msgina: InteractiveLogonMutex

0x0000000005f48ba8        2        1      1 0x00000000           DBWinMutex

0x0000000005f8aec8        1        1      1 0x00000000

0x0000000005fd0b38        3        2      1 0x00000000           c:!documents and settings!localservice!cookies!

0x0000000005fd4eb0        3        2      1 0x00000000           c:!documents and settings!administrator!local settings!history!history.ie5!

0x00000000060152d8        1        1      1 0x00000000

0x0000000006016b88        2        1      1 0x00000000           VMwareGuestCopyPasteMutex

0x0000000006017ee8        3        2      1 0x00000000           ThinPrint-L

0x0000000006017fe0        2        1      1 0x00000000           c:!documents and settings!networkservice!local settings!temporary internet files!content.ie5!

0x000000000605ff40        1        1      1 0x00000000

0x0000000006124810        1        1      1 0x00000000

0x0000000006126908        1        1      1 0x00000000

0x00000000061682e8        1        1      1 0x00000000

0x000000000616ad30        1        1      1 0x00000000

0x00000000061ab388        1        1      1 0x00000000

0x00000000061ad0e0        1        1      1 0x00000000

0x00000000061ee258        2        1      1 0x00000000           PnP\_Init\_Mutex

0x00000000061efc38        1        1      1 0x00000000

0x0000000006231bd0        1        1      1 0x00000000

0x0000000006231e28        1        1      1 0x00000000

0x0000000006233a98        1        1      1 0x00000000

0x0000000006234b58        2        1      1 0x00000000           5434E42601CB391B000004042

0x0000000006234bc8        1        1      1 0x00000000

0x0000000006234ec0        1        1      1 0x00000000

0x00000000062354d8        2        1      1 0x00000000           VMToolsHookQueueLock

0x00000000062363a0        2        1      1 0x00000000           53B1C2D001CB391B000002B02

0x0000000006238c38        1        1      1 0x00000000

0x00000000062392e8        1        1      1 0x00000000

0x000000000627e0e0        1        1      1 0x00000000

0x000000000627f960        1        1      1 0x00000000

0x0000000006381678        1        1      1 0x00000000

0x0000000006381aa0        1        1      1 0x00000000

0x0000000006381de8        1        1      1 0x00000000

0x0000000006383150        2        1      1 0x00000000           userenv: machine policy mutex

0x00000000063c6678        1        1      1 0x00000000

0x00000000063c6aa0        1        1      1 0x00000000

0x00000000063c7908        1        1      1 0x00000000

0x0000000006408950        1        1      1 0x00000000

0x00000000064093e8        1        1      1 0x00000000

0x0000000006409c38        1        1      1 0x00000000

0x000000000640aa70        1        1      1 0x00000000

0x000000000640aec0        1        1      1 0x00000000

0x000000000644c7e8        1        1      1 0x00000000

0x000000000644e898        3        2      1 0x00000000           c:!documents and settings!localservice!local settings!history!history.ie5!

0x000000000644eeb0        5        4      1 0x00000000           WindowsUpdateTracingMutex

0x0000000006453bc8        1        1      1 0x00000000

0x0000000006453c38        1        1      1 0x00000000

0x0000000006453e48        1        1      1 0x00000000

0x00000000064951d0        3        2      1 0x00000000           WininetStartupMutex

0x00000000064995c0        1        1      1 0x00000000

0x000000000651a720        1        1      1 0x00000000

0x0000000006560db0        1        1      1 0x00000000

0x0000000006560e20        1        1      1 0x00000000

0x00000000065c05a8        1        1      1 0x00000000

0x00000000065e6810        1        1      1 0x00000000

0x00000000066290f8        1        1      1 0x00000000

0x000000000666c678        1        1      1 0x00000000

0x00000000066ad9a8        1        1      1 0x00000000

0x00000000066add28        1        1      1 0x00000000

0x00000000066f68b0        5        4      1 0x00000000           RasPbFile

0x00000000066f6cd0        1        1      1 0x00000000

0x00000000067358a8        2        1      1 0x00000000           RSVP\_Perf\_Library\_Lock\_PID\_684

0x0000000006735dc0        2        1      1 0x00000000           \_AVIRA\_2109

0x00000000067790f8        1        1      1 0x00000000

0x0000000006779d48        1        1      1 0x00000000

0x000000000687f0f8        1        1      1 0x00000000

0x0000000006901208        1        1      1 0x00000000

0x0000000006944ba0        1        1      1 0x00000000

0x0000000006945830        1        1      1 0x00000000

0x0000000006945a30        1        1      1 0x00000000

0x0000000006946678        1        1      1 0x00000000

0x0000000006b1a460        2        1      1 0x00000000           VMwareGuestDnDDataMutex

0x0000000006b400f8        1        1      1 0x00000000

1. https://www.ipvoid.com/scan/193.104.41.75/
2. https://www.virustotal.com/gui/file/8e3be5dc65aa35d68fd2aba1d3d9bf0f40d5118fe22eb2e6c97c8463bd1f1ba1/detection
3. https://www.fortiguard.com/encyclopedia/virus/894653
