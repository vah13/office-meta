# office-meta
using simple meta-tag im html page (see example for docx, docx.html) in target system IE automatically download and open docx file.

supported file formats:

ms-word

ms-excel

ms-powerpoint

ms-visio

ms-access

ms-publisher

ms-project

```
.text:000000014000A040 sub_14000A040   proc near               ; DATA XREF: .rdata:0000000140317478o
.text:000000014000A040                                         ; .rdata:0000000140317EECo ...
.text:000000014000A040
.text:000000014000A040 var_18          = qword ptr -18h
.text:000000014000A040 arg_0           = qword ptr  8
.text:000000014000A040
.text:000000014000A040                 push    rdi
.text:000000014000A041                 sub     rsp, 30h
.text:000000014000A045                 mov     [rsp+38h+var_18], 0FFFFFFFFFFFFFFFEh
.text:000000014000A04E                 mov     [rsp+38h+arg_0], rsi
.text:000000014000A053                 mov     esi, 7
.text:000000014000A058                 mov     r8d, esi
.text:000000014000A05B                 lea     rdx, aMsWord    ; "ms-word"
.text:000000014000A062                 lea     rcx, unk_1404A5FF0 ; Dst
.text:000000014000A069                 call    sub_140010874
.text:000000014000A06E                 xor     edi, edi
.text:000000014000A070                 mov     cs:dword_1404A6010, edi
.text:000000014000A076                 mov     cs:qword_1404A6028, rdi
.text:000000014000A07D                 mov     cs:qword_1404A6030, rsi
.text:000000014000A084                 mov     cs:word_1404A6018, di
.text:000000014000A08B                 lea     r8d, [rsi+1]
.text:000000014000A08F                 lea     rdx, aMsExcel   ; "ms-excel"
.text:000000014000A096                 lea     rcx, word_1404A6018 ; Dst
.text:000000014000A09D                 call    sub_140010874
.text:000000014000A0A2                 mov     cs:dword_1404A6038, 1
.text:000000014000A0AC                 mov     cs:qword_1404A6050, rdi
.text:000000014000A0B3                 mov     cs:qword_1404A6058, rsi
.text:000000014000A0BA                 mov     cs:word_1404A6040, di
.text:000000014000A0C1                 lea     r8d, [rsi+6]
.text:000000014000A0C5                 lea     rdx, aMsPowerpoint ; "ms-powerpoint"
.text:000000014000A0CC                 lea     rcx, word_1404A6040 ; Dst
.text:000000014000A0D3                 call    sub_140010874
.text:000000014000A0D8                 mov     cs:dword_1404A6060, 2
.text:000000014000A0E2                 mov     cs:qword_1404A6078, rdi
.text:000000014000A0E9                 mov     cs:qword_1404A6080, rsi
.text:000000014000A0F0                 mov     cs:word_1404A6068, di
.text:000000014000A0F7                 lea     r8d, [rsi+1]
.text:000000014000A0FB                 lea     rdx, aMsVisio   ; "ms-visio"
.text:000000014000A102                 lea     rcx, word_1404A6068 ; Dst
.text:000000014000A109                 call    sub_140010874
.text:000000014000A10E                 mov     cs:dword_1404A6088, 4
.text:000000014000A118                 mov     cs:qword_1404A60A0, rdi
.text:000000014000A11F                 mov     cs:qword_1404A60A8, rsi
.text:000000014000A126                 mov     cs:word_1404A6090, di
.text:000000014000A12D                 lea     r8d, [rsi+2]
.text:000000014000A131                 lea     rdx, aMsAccess  ; "ms-access"
.text:000000014000A138                 lea     rcx, word_1404A6090 ; Dst
.text:000000014000A13F                 call    sub_140010874
.text:000000014000A144                 mov     cs:dword_1404A60B0, 5
.text:000000014000A14E                 mov     cs:qword_1404A60C8, rdi
.text:000000014000A155                 mov     cs:qword_1404A60D0, rsi
.text:000000014000A15C                 mov     cs:word_1404A60B8, di
.text:000000014000A163                 lea     r8d, [rsi+5]
.text:000000014000A167                 lea     rdx, aMsPublisher ; "ms-publisher"
.text:000000014000A16E                 lea     rcx, word_1404A60B8 ; Dst
.text:000000014000A175                 call    sub_140010874
.text:000000014000A17A                 mov     cs:dword_1404A60D8, esi
.text:000000014000A180                 mov     cs:qword_1404A60F0, rdi
.text:000000014000A187                 mov     cs:qword_1404A60F8, rsi
.text:000000014000A18E                 mov     cs:word_1404A60E0, di
.text:000000014000A195                 lea     r8d, [rsi+3]
.text:000000014000A199                 lea     rdx, aMsProject ; "ms-project"
.text:000000014000A1A0                 lea     rcx, word_1404A60E0 ; Dst
.text:000000014000A1A7                 call    sub_140010874
.text:000000014000A1AC                 mov     cs:dword_1404A6100, 8
.text:000000014000A1B6                 lea     rcx, sub_140313D50
.text:000000014000A1BD                 mov     rsi, [rsp+38h+arg_0]
.text:000000014000A1C2                 add     rsp, 30h
.text:000000014000A1C6                 pop     rdi
.text:000000014000A1C7                 jmp     sub_1402E4EF0
.text:000000014000A1C7 sub_14000A040   endp
```
