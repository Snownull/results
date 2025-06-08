[+] PostgreSQL Privilege Escalation
[+] Time: 2025-06-08 03:31:52

[*] Trying PostgreSQL connections...

[*] Creating PostgreSQL extension exploit...

[*] Looking for PostgreSQL config files...

[*] Attempting to become postgres user...
sh: su: command not found

[*] Checking for created SUID files...

[+] PostgreSQL exploitation complete.
[!] Try: /tmp/pgbash -p


---------------------------------------------------

[+] SUID Binary Exploitation

[*] Checking SUID binaries...
-rwsr-sr-x 1 igsbmzes igsbmzes 18200 Jun  8 05:26 /home/igsbmzes/.cagefs/tmp/suid
-rwsr-sr-x 1 igsbmzes igsbmzes 18200 Jun  8 05:26 /tmp/suid

[*] Executing /tmp/suid...
sh: /tmp/suid: Permission denied

[*] Trying with different methods...
Array
(
)
/tmp/run_suid.sh: line 2: /tmp/suid
: No such file or directory

[*] Checking current privileges...
uid=1067(igsbmzes) gid=1072(igsbmzes) groups=1072(igsbmzes)
igsbmzes

[*] Creating additional SUID exploits...

[*] Exploiting LiteSpeed SUID binaries...
[+] Found: /usr/local/lsws/bin/lscgid
2025-06-08 05:29:28.128753 lscgid: secret is not set properly!
[+] Found: /usr/local/lsws/bin/lscgid.6.1.2
2025-06-08 05:29:28.133476 lscgid: secret is not set properly!
[+] Found: /usr/local/lsws/bin/lscgid.6.2
2025-06-08 05:29:28.137458 lscgid: secret is not set properly!
[+] Found: /usr/local/lsws/bin/lscgid.6.2.1
2025-06-08 05:29:28.141875 lscgid: secret is not set properly!
[+] Found: /usr/local/lsws/bin/lscgid.6.2.2
2025-06-08 05:29:28.146701 lscgid: secret is not set properly!
[+] Found: /usr/local/lsws/bin/lscgid.6.3
2025-06-08 05:29:28.167209 lscgid: secret is not set properly!
[+] Found: /usr/local/lsws/bin/lscgid.6.3.1
2025-06-08 05:29:28.171784 lscgid: secret is not set properly!
[+] Found: /usr/local/lsws/bin/lscgid.6.3.2
2025-06-08 05:29:28.174740 lscgid: secret is not set properly!

------------------------------------------------------------------------------

[+] Kernel 4.18.0 CloudLinux Exploit

/tmp/kernel_exploit.c:1:1: error: stray '\212' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
 ^
/tmp/kernel_exploit.c:1:3: error: expected '=', ',', ';', 'asm' or '__attribute__' before '%' token
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
   ^
/tmp/kernel_exploit.c:1:4: error: stray '\271' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
    ^
/tmp/kernel_exploit.c:1:5: error: stray '\327' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
     ^
/tmp/kernel_exploit.c:1:6: error: stray '\254' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
      ^
/tmp/kernel_exploit.c:1:7: error: stray '\265' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
       ^
/tmp/kernel_exploit.c:1:8: error: stray '\330' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
        ^
/tmp/kernel_exploit.c:1:9: error: stray '\250' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
         ^
/tmp/kernel_exploit.c:1:10: error: stray '\206' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
          ^
/tmp/kernel_exploit.c:1:12: error: stray '\334' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
            ^
/tmp/kernel_exploit.c:1:13: error: stray '\226' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
             ^
/tmp/kernel_exploit.c:1:14: error: stray '\347' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
              ^
/tmp/kernel_exploit.c:1:16: error: stray '\262' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
                ^
/tmp/kernel_exploit.c:1:17: error: stray '\327' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
                 ^
/tmp/kernel_exploit.c:1:19: error: stray '\211' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
                   ^
/tmp/kernel_exploit.c:1:20: error: stray '\270' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
                    ^
/tmp/kernel_exploit.c:1:22: error: stray '\235' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
                      ^
/tmp/kernel_exploit.c:1:23: error: stray '\311' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
                       ^
/tmp/kernel_exploit.c:1:26: error: stray '\353' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
                          ^
/tmp/kernel_exploit.c:1:28: error: stray '\256' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
                            ^
/tmp/kernel_exploit.c:1:30: error: stray '\340' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
                              ^
/tmp/kernel_exploit.c:1:31: error: stray '\206' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
                               ^
/tmp/kernel_exploit.c:1:33: error: stray '\334' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
                                 ^
/tmp/kernel_exploit.c:1:34: error: stray '\226' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
                                  ^
/tmp/kernel_exploit.c:1:35: error: stray '\347' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
                                   ^
/tmp/kernel_exploit.c:1:37: error: stray '\272' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
                                     ^
/tmp/kernel_exploit.c:1:39: error: stray '\254' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
                                       ^
/tmp/kernel_exploit.c:1:40: error: stray '\265' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
                                        ^
/tmp/kernel_exploit.c:1:41: error: stray '\330' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
                                         ^
/tmp/kernel_exploit.c:1:43: error: stray '\235' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
                                           ^
/tmp/kernel_exploit.c:1:44: error: stray '\311' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
                                            ^
/tmp/kernel_exploit.c:1:47: error: stray '\353' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
                                               ^
/tmp/kernel_exploit.c:1:49: error: stray '\263' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
                                                 ^
/tmp/kernel_exploit.c:1:50: error: stray '\373' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
                                                  ^
/tmp/kernel_exploit.c:1:52: error: stray '\245' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
                                                    ^
/tmp/kernel_exploit.c:1:53: error: stray '\353' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
                                                     ^
/tmp/kernel_exploit.c:1:55: error: stray '\212' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
                                                       ^
/tmp/kernel_exploit.c:1:58: error: stray '\271' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
                                                          ^
/tmp/kernel_exploit.c:1:59: error: stray '\327' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
                                                           ^
/tmp/kernel_exploit.c:1:60: error: stray '\254' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
                                                            ^
/tmp/kernel_exploit.c:1:61: error: stray '\312' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
                                                             ^
/tmp/kernel_exploit.c:1:62: error: stray '\317' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
                                                              ^
/tmp/kernel_exploit.c:1:63: error: stray '\360' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
                                                               ^
/tmp/kernel_exploit.c:1:67: error: stray '\212' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
                                                                   ^
/tmp/kernel_exploit.c:1:70: error: stray '\271' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
                                                                      ^
/tmp/kernel_exploit.c:1:71: error: stray '\327' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
                                                                       ^
/tmp/kernel_exploit.c:1:72: error: stray '\254' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
                                                                        ^
/tmp/kernel_exploit.c:1:73: error: stray '\312' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
                                                                         ^
/tmp/kernel_exploit.c:1:74: error: stray '\317' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
                                                                          ^
/tmp/kernel_exploit.c:1:75: error: stray '\346' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
                                                                           ^
/tmp/kernel_exploit.c:1:76: error: stray '\231' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
                                                                            ^
/tmp/kernel_exploit.c:1:77: error: stray '\251' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
                                                                             ^
/tmp/kernel_exploit.c:1:78: error: stray '\341' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
                                                                              ^
/tmp/kernel_exploit.c:1:79: error: stray '\212' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
                                                                               ^
/tmp/kernel_exploit.c:1:82: error: stray '\271' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
                                                                                  ^
/tmp/kernel_exploit.c:1:83: error: stray '\327' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
                                                                                   ^
/tmp/kernel_exploit.c:1:84: error: stray '\237' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
                                                                                    ^
/tmp/kernel_exploit.c:1:88: error: stray '\207' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
                                                                                        ^
/tmp/kernel_exploit.c:1:89: error: stray '\377' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
                                                                                         ^
/tmp/kernel_exploit.c:1:90: error: stray '\302' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
                                                                                          ^
/tmp/kernel_exploit.c:1:91: error: stray '\226' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
                                                                                           ^
/tmp/kernel_exploit.c:1:92: error: stray '\213' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
                                                                                            ^
/tmp/kernel_exploit.c:1:93: error: stray '\235' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
                                                                                             ^
/tmp/kernel_exploit.c:1:96: error: stray '\356' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
                                                                                                ^
/tmp/kernel_exploit.c:1:97: error: stray '\307' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
                                                                                                 ^
/tmp/kernel_exploit.c:1:98: error: stray '\215' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
                                                                                                  ^
/tmp/kernel_exploit.c:1:100: error: stray '\322' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
                                                                                                    ^
/tmp/kernel_exploit.c:1:102: error: stray '\253' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
                                                                                                      ^
/tmp/kernel_exploit.c:1:103: error: stray '\235' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
                                                                                                       ^
/tmp/kernel_exploit.c:1:104: error: stray '\351' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
                                                                                                        ^
/tmp/kernel_exploit.c:1:106: error: stray '\306' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
                                                                                                          ^
/tmp/kernel_exploit.c:1:107: error: stray '\231' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
                                                                                                           ^
/tmp/kernel_exploit.c:1:109: error: stray '\212' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
                                                                                                             ^
/tmp/kernel_exploit.c:1:110: error: stray '\333' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
                                                                                                              ^
/tmp/kernel_exploit.c:1:111: error: stray '\350' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
                                                                                                               ^
/tmp/kernel_exploit.c:1:112: error: stray '\211' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
                                                                                                                ^
/tmp/kernel_exploit.c:1:113: error: stray '\327' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
                                                                                                                 ^
/tmp/kernel_exploit.c:1:114: error: stray '\261' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
                                                                                                                  ^
/tmp/kernel_exploit.c:1:115: error: stray '\246' in program
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
                                                                                                                   ^
/tmp/kernel_exploit.c:1:117: warning: missing terminating " character
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
                                                                                                                     ^
/tmp/kernel_exploit.c:1:117: error: missing terminating " character
 �w%�׬�ب�)ܖ�^��e��b��nu�-�)��)ܖ�^�x���b��nu�2��r��!�w%�׬���j+a�w%�׬��晩�w%�ןr{e����.)�Ǎ|�G���^ƙh���ױ�Z"���ʖ��&�xT����)�}�)z鮇?�����CY�}�v�^��^�����CY�}�?��ޯ
                                                                                                                     ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
/tmp/kernel_exploit.c:2:1: error: stray '\342' in program
 ��+y�,�����޺{"�w����r�����z�1}��}���V��M4�Ǟ��\��h}��!)!�{"�w���ஊ-r���
 ^
/tmp/kernel_exploit.c:2:2: error: stray '\265' in program
 ��+y�,�����޺{"�w����r�����z�1}��}���V��M4�Ǟ��\��h}��!)!�{"�w���ஊ-r���
  ^
/tmp/kernel_exploit.c:2:3: error: stray '\347' in program
 ��+y�,�����޺{"�w����r�����z�1}��}���V��M4�Ǟ��\��h}��!)!�{"�w���ஊ-r���
   ^
/tmp/kernel_exploit.c:2:6: error: stray '\333' in program
 ��+y�,�����޺{"�w����r�����z�1}��}���V��M4�Ǟ��\��h}��!)!�{"�w���ஊ-r���
      ^
/tmp/kernel_exploit.c:2:8: error: stray '\266' in program
 ��+y�,�����޺{"�w����r�����z�1}��}���V��M4�Ǟ��\��h}��!)!�{"�w���ஊ-r���
        ^
/tmp/kernel_exploit.c:2:9: error: stray '\273' in program
 ��+y�,�����޺{"�w����r�����z�1}��}���V��M4�Ǟ��\��h}��!)!�{"�w���ஊ-r���
         ^
/tmp/kernel_exploit.c:2:10: error: stray '\234' in program
 ��+y�,�����޺{"�w����r�����z�1}��}���V��M4�Ǟ��\��h}��!)!�{"�w���ஊ-r���
          ^
/tmp/kernel_exploit.c:2:11: error: stray '\266' in program
 ��+y�,�����޺{"�w����r�����z�1}��}���V��M4�Ǟ��\��h}��!)!�{"�w���ஊ-r���
           ^
/tmp/kernel_exploit.c:2:12: error: stray '\352' in program
 ��+y�,�����޺{"�w����r�����z�1}��}���V��M4�Ǟ��\��h}��!)!�{"�w���ஊ-r���
            ^
/tmp/kernel_exploit.c:2:13: error: stray '\336' in program
 ��+y�,�����޺{"�w����r�����z�1}��}���V��M4�Ǟ��\��h}��!)!�{"�w���ஊ-r���
             ^
/tmp/kernel_exploit.c:2:14: error: stray '\272' in program
 ��+y�,�����޺{"�w����r�����z�1}��}���V��M4�Ǟ��\��h}��!)!�{"�w���ஊ-r���
              ^
/tmp/kernel_exploit.c:2:16: warning: unknown escape sequence: '\255'
 ��+y�,�����޺{"�w����r�����z�1}��}���V��M4�Ǟ��\��h}��!)!�{"�w���ஊ-r���
                ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
/tmp/kernel_exploit.c:2:65: error: stray '\202' in program
 ��+y�,�����޺{"�w����r�����z�1}��}���V��M4�Ǟ��\��h}��!)!�{"�w���ஊ-r���
                                                                 ^
/tmp/kernel_exploit.c:2:67: error: stray '\235' in program
 ��+y�,�����޺{"�w����r�����z�1}��}���V��M4�Ǟ��\��h}��!)!�{"�w���ஊ-r���
                                                                   ^
/tmp/kernel_exploit.c:2:68: error: stray '\226' in program
 ��+y�,�����޺{"�w����r�����z�1}��}���V��M4�Ǟ��\��h}��!)!�{"�w���ஊ-r���
                                                                    ^
/tmp/kernel_exploit.c:2:69: error: stray '\211' in program
 ��+y�,�����޺{"�w����r�����z�1}��}���V��M4�Ǟ��\��h}��!)!�{"�w���ஊ-r���
                                                                     ^
/tmp/kernel_exploit.c:2:70: error: stray '\340' in program
 ��+y�,�����޺{"�w����r�����z�1}��}���V��M4�Ǟ��\��h}��!)!�{"�w���ஊ-r���
                                                                      ^
/tmp/kernel_exploit.c:2:71: error: stray '\256' in program
 ��+y�,�����޺{"�w����r�����z�1}��}���V��M4�Ǟ��\��h}��!)!�{"�w���ஊ-r���
                                                                       ^
/tmp/kernel_exploit.c:2:72: error: stray '\212' in program
 ��+y�,�����޺{"�w����r�����z�1}��}���V��M4�Ǟ��\��h}��!)!�{"�w���ஊ-r���
                                                                        ^
/tmp/kernel_exploit.c:2:75: error: stray '\267' in program
 ��+y�,�����޺{"�w����r�����z�1}��}���V��M4�Ǟ��\��h}��!)!�{"�w���ஊ-r���
                                                                           ^
/tmp/kernel_exploit.c:2:76: error: stray '\235' in program
 ��+y�,�����޺{"�w����r�����z�1}��}���V��M4�Ǟ��\��h}��!)!�{"�w���ஊ-r���
                                                                            ^
/tmp/kernel_exploit.c:2:77: error: stray '\323' in program
 ��+y�,�����޺{"�w����r�����z�1}��}���V��M4�Ǟ��\��h}��!)!�{"�w���ஊ-r���
                                                                             ^
/tmp/kernel_exploit.c:3:1: error: stray '\342' in program
 ��ݮ�-r���,ޡ���+y�%�ǟw���׫��b�鞶�+-zg����ݴҺ(����ۊ�j�z�?��,�ا�f������
 ^
/tmp/kernel_exploit.c:3:2: error: stray '\265' in program
 ��ݮ�-r���,ޡ���+y�%�ǟw���׫��b�鞶�+-zg����ݴҺ(����ۊ�j�z�?��,�ا�f������
  ^
/tmp/kernel_exploit.c:3:3: error: stray '\347' in program
 ��ݮ�-r���,ޡ���+y�%�ǟw���׫��b�鞶�+-zg����ݴҺ(����ۊ�j�z�?��,�ا�f������
   ^
/tmp/kernel_exploit.c:3:4: error: stray '\335' in program
 ��ݮ�-r���,ޡ���+y�%�ǟw���׫��b�鞶�+-zg����ݴҺ(����ۊ�j�z�?��,�ا�f������
    ^
/tmp/kernel_exploit.c:3:5: error: stray '\256' in program
 ��ݮ�-r���,ޡ���+y�%�ǟw���׫��b�鞶�+-zg����ݴҺ(����ۊ�j�z�?��,�ا�f������
     ^
/tmp/kernel_exploit.c:3:6: error: stray '\212' in program
 ��ݮ�-r���,ޡ���+y�%�ǟw���׫��b�鞶�+-zg����ݴҺ(����ۊ�j�z�?��,�ا�f������
      ^
/tmp/kernel_exploit.c:3:9: error: stray '\267' in program
 ��ݮ�-r���,ޡ���+y�%�ǟw���׫��b�鞶�+-zg����ݴҺ(����ۊ�j�z�?��,�ا�f������
         ^
/tmp/kernel_exploit.c:3:10: error: stray '\235' in program
 ��ݮ�-r���,ޡ���+y�%�ǟw���׫��b�鞶�+-zg����ݴҺ(����ۊ�j�z�?��,�ا�f������
          ^
/tmp/kernel_exploit.c:3:11: error: stray '\262' in program
 ��ݮ�-r���,ޡ���+y�%�ǟw���׫��b�鞶�+-zg����ݴҺ(����ۊ�j�z�?��,�ا�f������
           ^
/tmp/kernel_exploit.c:3:13: error: stray '\336' in program
 ��ݮ�-r���,ޡ���+y�%�ǟw���׫��b�鞶�+-zg����ݴҺ(����ۊ�j�z�?��,�ا�f������
             ^
/tmp/kernel_exploit.c:3:14: error: stray '\241' in program
 ��ݮ�-r���,ޡ���+y�%�ǟw���׫��b�鞶�+-zg����ݴҺ(����ۊ�j�z�?��,�ا�f������
              ^
/tmp/kernel_exploit.c:3:15: error: stray '\372' in program
 ��ݮ�-r���,ޡ���+y�%�ǟw���׫��b�鞶�+-zg����ݴҺ(����ۊ�j�z�?��,�ا�f������
               ^
/tmp/kernel_exploit.c:3:16: error: stray '\350' in program
 ��ݮ�-r���,ޡ���+y�%�ǟw���׫��b�鞶�+-zg����ݴҺ(����ۊ�j�z�?��,�ا�f������
                ^
/tmp/kernel_exploit.c:3:17: error: stray '\242' in program
 ��ݮ�-r���,ޡ���+y�%�ǟw���׫��b�鞶�+-zg����ݴҺ(����ۊ�j�z�?��,�ا�f������
                 ^
/tmp/kernel_exploit.c:3:18: error: stray '\327' in program
 ��ݮ�-r���,ޡ���+y�%�ǟw���׫��b�鞶�+-zg����ݴҺ(����ۊ�j�z�?��,�ا�f������
                  ^
/tmp/kernel_exploit.c:3:21: error: stray '\327' in program
 ��ݮ�-r���,ޡ���+y�%�ǟw���׫��b�鞶�+-zg����ݴҺ(����ۊ�j�z�?��,�ا�f������
                     ^
/tmp/kernel_exploit.c:3:23: error: stray '\242' in program
 ��ݮ�-r���,ޡ���+y�%�ǟw���׫��b�鞶�+-zg����ݴҺ(����ۊ�j�z�?��,�ا�f������
                       ^
/tmp/kernel_exploit.c:3:24: error: stray '\307' in program
 ��ݮ�-r���,ޡ���+y�%�ǟw���׫��b�鞶�+-zg����ݴҺ(����ۊ�j�z�?��,�ا�f������
                        ^
/tmp/kernel_exploit.c:3:25: error: stray '\237' in program
 ��ݮ�-r���,ޡ���+y�%�ǟw���׫��b�鞶�+-zg����ݴҺ(����ۊ�j�z�?��,�ا�f������
                         ^
/tmp/kernel_exploit.c:3:27: error: stray '\377' in program
 ��ݮ�-r���,ޡ���+y�%�ǟw���׫��b�鞶�+-zg����ݴҺ(����ۊ�j�z�?��,�ا�f������
                           ^
/tmp/kernel_exploit.c:3:28: error: stray '\300' in program
 ��ݮ�-r���,ޡ���+y�%�ǟw���׫��b�鞶�+-zg����ݴҺ(����ۊ�j�z�?��,�ا�f������
                            ^
/tmp/kernel_exploit.c:3:29: error: stray '\226' in program
 ��ݮ�-r���,ޡ���+y�%�ǟw���׫��b�鞶�+-zg����ݴҺ(����ۊ�j�z�?��,�ا�f������
                             ^
/tmp/kernel_exploit.c:3:30: error: stray '\327' in program
 ��ݮ�-r���,ޡ���+y�%�ǟw���׫��b�鞶�+-zg����ݴҺ(����ۊ�j�z�?��,�ا�f������
                              ^
/tmp/kernel_exploit.c:3:31: error: stray '\253' in program
 ��ݮ�-r���,ޡ���+y�%�ǟw���׫��b�鞶�+-zg����ݴҺ(����ۊ�j�z�?��,�ا�f������
                               ^
/tmp/kernel_exploit.c:3:32: error: stray '\235' in program
 ��ݮ�-r���,ޡ���+y�%�ǟw���׫��b�鞶�+-zg����ݴҺ(����ۊ�j�z�?��,�ا�f������
                                ^
/tmp/kernel_exploit.c:3:33: error: stray '\253' in program
 ��ݮ�-r���,ޡ���+y�%�ǟw���׫��b�鞶�+-zg����ݴҺ(����ۊ�j�z�?��,�ا�f������
                                 ^
/tmp/kernel_exploit.c:3:35: error: stray '\275' in program
 ��ݮ�-r���,ޡ���+y�%�ǟw���׫��b�鞶�+-zg����ݴҺ(����ۊ�j�z�?��,�ا�f������
                                   ^
/tmp/kernel_exploit.c:3:36: error: stray '\351' in program
 ��ݮ�-r���,ޡ���+y�%�ǟw���׫��b�鞶�+-zg����ݴҺ(����ۊ�j�z�?��,�ا�f������
                                    ^
/tmp/kernel_exploit.c:3:37: error: stray '\236' in program
 ��ݮ�-r���,ޡ���+y�%�ǟw���׫��b�鞶�+-zg����ݴҺ(����ۊ�j�z�?��,�ا�f������
                                     ^
/tmp/kernel_exploit.c:3:38: error: stray '\266' in program
 ��ݮ�-r���,ޡ���+y�%�ǟw���׫��b�鞶�+-zg����ݴҺ(����ۊ�j�z�?��,�ا�f������
                                      ^
/tmp/kernel_exploit.c:3:39: error: stray '\32' in program
 ��ݮ�-r���,ޡ���+y�%�ǟw���׫��b�鞶�+-zg����ݴҺ(����ۊ�j�z�?��,�ا�f������
                                       ^
/tmp/kernel_exploit.c:3:40: error: stray '\35' in program
 ��ݮ�-r���,ޡ���+y�%�ǟw���׫��b�鞶�+-zg����ݴҺ(����ۊ�j�z�?��,�ا�f������
                                        ^
/tmp/kernel_exploit.c:3:41: error: stray '\263' in program
 ��ݮ�-r���,ޡ���+y�%�ǟw���׫��b�鞶�+-zg����ݴҺ(����ۊ�j�z�?��,�ا�f������
                                         ^
/tmp/kernel_exploit.c:3:46: error: stray '\234' in program
 ��ݮ�-r���,ޡ���+y�%�ǟw���׫��b�鞶�+-zg����ݴҺ(����ۊ�j�z�?��,�ا�f������
                                              ^
/tmp/kernel_exploit.c:3:47: error: stray '\206' in program
 ��ݮ�-r���,ޡ���+y�%�ǟw���׫��b�鞶�+-zg����ݴҺ(����ۊ�j�z�?��,�ا�f������
                                               ^
/tmp/kernel_exploit.c:3:48: error: stray '\212' in program
 ��ݮ�-r���,ޡ���+y�%�ǟw���׫��b�鞶�+-zg����ݴҺ(����ۊ�j�z�?��,�ا�f������
                                                ^
/tmp/kernel_exploit.c:3:49: error: stray '\350' in program
 ��ݮ�-r���,ޡ���+y�%�ǟw���׫��b�鞶�+-zg����ݴҺ(����ۊ�j�z�?��,�ا�f������
                                                 ^
/tmp/kernel_exploit.c:3:50: error: stray '\242' in program
 ��ݮ�-r���,ޡ���+y�%�ǟw���׫��b�鞶�+-zg����ݴҺ(����ۊ�j�z�?��,�ا�f������
                                                  ^
/tmp/kernel_exploit.c:3:51: error: stray '\335' in program
 ��ݮ�-r���,ޡ���+y�%�ǟw���׫��b�鞶�+-zg����ݴҺ(����ۊ�j�z�?��,�ا�f������
                                                   ^
/tmp/kernel_exploit.c:3:52: error: stray '\264' in program
 ��ݮ�-r���,ޡ���+y�%�ǟw���׫��b�鞶�+-zg����ݴҺ(����ۊ�j�z�?��,�ا�f������
                                                    ^
/tmp/kernel_exploit.c:3:53: error: stray '\322' in program
 ��ݮ�-r���,ޡ���+y�%�ǟw���׫��b�鞶�+-zg����ݴҺ(����ۊ�j�z�?��,�ا�f������
                                                     ^
/tmp/kernel_exploit.c:3:54: error: stray '\272' in program
 ��ݮ�-r���,ޡ���+y�%�ǟw���׫��b�鞶�+-zg����ݴҺ(����ۊ�j�z�?��,�ا�f������
                                                      ^
/tmp/kernel_exploit.c:3:56: error: stray '\267' in program
 ��ݮ�-r���,ޡ���+y�%�ǟw���׫��b�鞶�+-zg����ݴҺ(����ۊ�j�z�?��,�ا�f������
                                                        ^
/tmp/kernel_exploit.c:3:57: error: stray '\372' in program
 ��ݮ�-r���,ޡ���+y�%�ǟw���׫��b�鞶�+-zg����ݴҺ(����ۊ�j�z�?��,�ا�f������
                                                         ^
/tmp/kernel_exploit.c:3:58: error: stray '\350' in program
 ��ݮ�-r���,ޡ���+y�%�ǟw���׫��b�鞶�+-zg����ݴҺ(����ۊ�j�z�?��,�ا�f������
                                                          ^
/tmp/kernel_exploit.c:3:59: error: stray '\242' in program
 ��ݮ�-r���,ޡ���+y�%�ǟw���׫��b�鞶�+-zg����ݴҺ(����ۊ�j�z�?��,�ا�f������
                                                           ^
/tmp/kernel_exploit.c:3:60: error: stray '\337' in program
 ��ݮ�-r���,ޡ���+y�%�ǟw���׫��b�鞶�+-zg����ݴҺ(����ۊ�j�z�?��,�ا�f������
                                                            ^
/tmp/kernel_exploit.c:3:61: error: stray '\333' in program
 ��ݮ�-r���,ޡ���+y�%�ǟw���׫��b�鞶�+-zg����ݴҺ(����ۊ�j�z�?��,�ا�f������
                                                             ^
/tmp/kernel_exploit.c:3:62: error: stray '\212' in program
 ��ݮ�-r���,ޡ���+y�%�ǟw���׫��b�鞶�+-zg����ݴҺ(����ۊ�j�z�?��,�ا�f������
                                                              ^
/tmp/kernel_exploit.c:3:63: error: stray '\177' in program
 ��ݮ�-r���,ޡ���+y�%�ǟw���׫��b�鞶�+-zg����ݴҺ(����ۊ�j�z�?��,�ا�f������
                                                               ^
/tmp/kernel_exploit.c:3:64: error: stray '\333' in program
 ��ݮ�-r���,ޡ���+y�%�ǟw���׫��b�鞶�+-zg����ݴҺ(����ۊ�j�z�?��,�ا�f������
                                                                ^
/tmp/kernel_exploit.c:3:66: error: stray '\310' in program
 ��ݮ�-r���,ޡ���+y�%�ǟw���׫��b�鞶�+-zg����ݴҺ(����ۊ�j�z�?��,�ا�f������
                                                                  ^
/tmp/kernel_exploit.c:3:67: error: stray '\177' in program
 ��ݮ�-r���,ޡ���+y�%�ǟw���׫��b�鞶�+-zg����ݴҺ(����ۊ�j�z�?��,�ا�f������
                                                                   ^
/tmp/kernel_exploit.c:3:69: error: stray '\327' in program
 ��ݮ�-r���,ޡ���+y�%�ǟw���׫��b�鞶�+-zg����ݴҺ(����ۊ�j�z�?��,�ا�f������
                                                                     ^
/tmp/kernel_exploit.c:3:71: error: stray '\245' in program
 ��ݮ�-r���,ޡ���+y�%�ǟw���׫��b�鞶�+-zg����ݴҺ(����ۊ�j�z�?��,�ا�f������
                                                                       ^
/tmp/kernel_exploit.c:3:72: error: stray '\253' in program
 ��ݮ�-r���,ޡ���+y�%�ǟw���׫��b�鞶�+-zg����ݴҺ(����ۊ�j�z�?��,�ا�f������
                                                                        ^
/tmp/kernel_exploit.c:3:74: error: stray '\301' in program
 ��ݮ�-r���,ޡ���+y�%�ǟw���׫��b�鞶�+-zg����ݴҺ(����ۊ�j�z�?��,�ا�f������
                                                                          ^
/tmp/kernel_exploit.c:3:75: error: stray '\330' in program
 ��ݮ�-r���,ޡ���+y�%�ǟw���׫��b�鞶�+-zg����ݴҺ(����ۊ�j�z�?��,�ا�f������
                                                                           ^
/tmp/kernel_exploit.c:3:76: error: stray '\247' in program
 ��ݮ�-r���,ޡ���+y�%�ǟw���׫��b�鞶�+-zg����ݴҺ(����ۊ�j�z�?��,�ا�f������
                                                                            ^
/tmp/kernel_exploit.c:3:77: error: stray '\266' in program
 ��ݮ�-r���,ޡ���+y�%�ǟw���׫��b�鞶�+-zg����ݴҺ(����ۊ�j�z�?��,�ا�f������
                                                                             ^
/tmp/kernel_exploit.c:3:79: error: stray '\242' in program
 ��ݮ�-r���,ޡ���+y�%�ǟw���׫��b�鞶�+-zg����ݴҺ(����ۊ�j�z�?��,�ا�f������
                                                                               ^
/tmp/kernel_exploit.c:3:80: error: stray '\236' in program
 ��ݮ�-r���,ޡ���+y�%�ǟw���׫��b�鞶�+-zg����ݴҺ(����ۊ�j�z�?��,�ا�f������
                                                                                ^
/tmp/kernel_exploit.c:3:81: error: stray '\232' in program
 ��ݮ�-r���,ޡ���+y�%�ǟw���׫��b�鞶�+-zg����ݴҺ(����ۊ�j�z�?��,�ا�f������
                                                                                 ^
/tmp/kernel_exploit.c:3:82: error: stray '\342' in program
 ��ݮ�-r���,ޡ���+y�%�ǟw���׫��b�鞶�+-zg����ݴҺ(����ۊ�j�z�?��,�ا�f������
                                                                                  ^
/tmp/kernel_exploit.c:3:83: error: stray '\236' in program
 ��ݮ�-r���,ޡ���+y�%�ǟw���׫��b�鞶�+-zg����ݴҺ(����ۊ�j�z�?��,�ا�f������
                                                                                   ^
/tmp/kernel_exploit.c:3:84: error: stray '\327' in program
 ��ݮ�-r���,ޡ���+y�%�ǟw���׫��b�鞶�+-zg����ݴҺ(����ۊ�j�z�?��,�ا�f������
                                                                                    ^
/tmp/kernel_exploit.c:3:85: error: stray '\376' in program
 ��ݮ�-r���,ޡ���+y�%�ǟw���׫��b�鞶�+-zg����ݴҺ(����ۊ�j�z�?��,�ا�f������
                                                                                     ^
/tmp/kernel_exploit.c:4:4: error: stray '\270' in program
 Z.t����w�{e�+g��h�G讶�y�'v+b�zbv�bu�+�'��?�(b��k�Ǭ��i���{����j�����q�,���5B������ z������ǭ�'t����Қ����k��g�+-zoۊ�j�iz[�����1�Z"�����m�(���mz�ڶ+ޞ̬�鬺�(�j޶��
    ^
/tmp/kernel_exploit.c:4:5: error: stray '\247' in program
 Z.t����w�{e�+g��h�G讶�y�'v+b�zbv�bu�+�'��?�(b��k�Ǭ��i���{����j�����q�,���5B������ z������ǭ�'t����Қ����k��g�+-zoۊ�j�iz[�����1�Z"�����m�(���mz�ڶ+ޞ̬�鬺�(�j޶��
     ^
/tmp/kernel_exploit.c:4:6: error: stray '\273' in program
 Z.t����w�{e�+g��h�G讶�y�'v+b�zbv�bu�+�'��?�(b��k�Ǭ��i���{����j�����q�,���5B������ z������ǭ�'t����Қ����k��g�+-zoۊ�j�iz[�����1�Z"�����m�(���mz�ڶ+ޞ̬�鬺�(�j޶��
      ^
/tmp/kernel_exploit.c:4:7: error: stray '\31' in program
 Z.t����w�{e�+g��h�G讶�y�'v+b�zbv�bu�+�'��?�(b��k�Ǭ��i���{����j�����q�,���5B������ z������ǭ�'t����Қ����k��g�+-zoۊ�j�iz[�����1�Z"�����m�(���mz�ڶ+ޞ̬�鬺�(�j޶��
       ^
/tmp/kernel_exploit.c:4:8: error: stray '\36' in program
 Z.t����w�{e�+g��h�G讶�y�'v+b�zbv�bu�+�'��?�(b��k�Ǭ��i���{����j�����q�,���5B������ z������ǭ�'t����Қ����k��g�+-zoۊ�j�iz[�����1�Z"�����m�(���mz�ڶ+ޞ̬�鬺�(�j޶��
        ^
/tmp/kernel_exploit.c:4:9: error: stray '\256' in program
 Z.t����w�{e�+g��h�G讶�y�'v+b�zbv�bu�+�'��?�(b��k�Ǭ��i���{����j�����q�,���5B������ z������ǭ�'t����Қ����k��g�+-zoۊ�j�iz[�����1�Z"�����m�(���mz�ڶ+ޞ̬�鬺�(�j޶��
         ^
/tmp/kernel_exploit.c:4:11: error: stray '\245' in program
 Z.t����w�{e�+g��h�G讶�y�'v+b�zbv�bu�+�'��?�(b��k�Ǭ��i���{����j�����q�,���5B������ z������ǭ�'t����Қ����k��g�+-zoۊ�j�iz[�����1�Z"�����m�(���mz�ڶ+ޞ̬�鬺�(�j޶��
           ^
/tmp/kernel_exploit.c:4:13: error: stray '\32' in program
 Z.t����w�{e�+g��h�G讶�y�'v+b�zbv�bu�+�'��?�(b��k�Ǭ��i���{����j�����q�,���5B������ z������ǭ�'t����Қ����k��g�+-zoۊ�j�iz[�����1�Z"�����m�(���mz�ڶ+ޞ̬�鬺�(�j޶��
             ^
/tmp/kernel_exploit.c:4:15: error: stray '\242' in program
 Z.t����w�{e�+g��h�G讶�y�'v+b�zbv�bu�+�'��?�(b��k�Ǭ��i���{����j�����q�,���5B������ z������ǭ�'t����Қ����k��g�+-zoۊ�j�iz[�����1�Z"�����m�(���mz�ڶ+ޞ̬�鬺�(�j޶��
               ^
/tmp/kernel_exploit.c:4:18: error: stray '\377' in program
 Z.t����w�{e�+g��h�G讶�y�'v+b�zbv�bu�+�'��?�(b��k�Ǭ��i���{����j�����q�,���5B������ z������ǭ�'t����Қ����k��g�+-zoۊ�j�iz[�����1�Z"�����m�(���mz�ڶ+ޞ̬�鬺�(�j޶��
                  ^
/tmp/kernel_exploit.c:4:19: error: stray '\361' in program
 Z.t����w�{e�+g��h�G讶�y�'v+b�zbv�bu�+�'��?�(b��k�Ǭ��i���{����j�����q�,���5B������ z������ǭ�'t����Қ����k��g�+-zoۊ�j�iz[�����1�Z"�����m�(���mz�ڶ+ޞ̬�鬺�(�j޶��
                   ^
/tmp/kernel_exploit.c:4:21: error: stray '\256' in program
 Z.t����w�{e�+g��h�G讶�y�'v+b�zbv�bu�+�'��?�(b��k�Ǭ��i���{����j�����q�,���5B������ z������ǭ�'t����Қ����k��g�+-zoۊ�j�iz[�����1�Z"�����m�(���mz�ڶ+ޞ̬�鬺�(�j޶��
                     ^
/tmp/kernel_exploit.c:4:23: error: stray '\350' in program
 Z.t����w�{e�+g��h�G讶�y�'v+b�zbv�bu�+�'��?�(b��k�Ǭ��i���{����j�����q�,���5B������ z������ǭ�'t����Қ����k��g�+-zoۊ�j�iz[�����1�Z"�����m�(���mz�ڶ+ޞ̬�鬺�(�j޶��
                       ^
/tmp/kernel_exploit.c:4:24: error: stray '\256' in program
 Z.t����w�{e�+g��h�G讶�y�'v+b�zbv�bu�+�'��?�(b��k�Ǭ��i���{����j�����q�,���5B������ z������ǭ�'t����Қ����k��g�+-zoۊ�j�iz[�����1�Z"�����m�(���mz�ڶ+ޞ̬�鬺�(�j޶��
                        ^
/tmp/kernel_exploit.c:4:25: error: stray '\266' in program
 Z.t����w�{e�+g��h�G讶�y�'v+b�zbv�bu�+�'��?�(b��k�Ǭ��i���{����j�����q�,���5B������ z������ǭ�'t����Қ����k��g�+-zoۊ�j�iz[�����1�Z"�����m�(���mz�ڶ+ޞ̬�鬺�(�j޶��
                         ^
/tmp/kernel_exploit.c:4:26: error: stray '\234' in program
 Z.t����w�{e�+g��h�G讶�y�'v+b�zbv�bu�+�'��?�(b��k�Ǭ��i���{����j�����q�,���5B������ z������ǭ�'t����Қ����k��g�+-zoۊ�j�iz[�����1�Z"�����m�(���mz�ڶ+ޞ̬�鬺�(�j޶��
                          ^
/tmp/kernel_exploit.c:4:28: error: stray '\312' in program
 Z.t����w�{e�+g��h�G讶�y�'v+b�zbv�bu�+�'��?�(b��k�Ǭ��i���{����j�����q�,���5B������ z������ǭ�'t����Қ����k��g�+-zoۊ�j�iz[�����1�Z"�����m�(���mz�ڶ+ޞ̬�鬺�(�j޶��
                            ^
/tmp/kernel_exploit.c:4:29: warning: character constant too long for its type
 Z.t����w�{e�+g��h�G讶�y�'v+b�zbv�bu�+�'��?�(b��k�Ǭ��i���{����j�����q�,���5B������ z������ǭ�'t����Қ����k��g�+-zoۊ�j�iz[�����1�Z"�����m�(���mz�ڶ+ޞ̬�鬺�(�j޶��
                             ^~~~~~~~~~~~~~~
/tmp/kernel_exploit.c:4:44: error: stray '\351' in program
 Z.t����w�{e�+g��h�G讶�y�'v+b�zbv�bu�+�'��?�(b��k�Ǭ��i���{����j�����q�,���5B������ z������ǭ�'t����Қ����k��g�+-zoۊ�j�iz[�����1�Z"�����m�(���mz�ڶ+ޞ̬�鬺�(�j޶��
                                            ^
/tmp/kernel_exploit.c:4:45: error: stray '\211' in program
 Z.t����w�{e�+g��h�G讶�y�'v+b�zbv�bu�+�'��?�(b��k�Ǭ��i���{����j�����q�,���5B������ z������ǭ�'t����Қ����k��g�+-zoۊ�j�iz[�����1�Z"�����m�(���mz�ڶ+ޞ̬�鬺�(�j޶��
                                             ^
/tmp/kernel_exploit.c:4:46: error: stray '\335' in program
 Z.t����w�{e�+g��h�G讶�y�'v+b�zbv�bu�+�'��?�(b��k�Ǭ��i���{����j�����q�,���5B������ z������ǭ�'t����Қ����k��g�+-zoۊ�j�iz[�����1�Z"�����m�(���mz�ڶ+ޞ̬�鬺�(�j޶��
                                              ^
/tmp/kernel_exploit.c:4:48: error: stray '\374' in program
 Z.t����w�{e�+g��h�G讶�y�'v+b�zbv�bu�+�'��?�(b��k�Ǭ��i���{����j�����q�,���5B������ z������ǭ�'t����Қ����k��g�+-zoۊ�j�iz[�����1�Z"�����m�(���mz�ڶ+ޞ̬�鬺�(�j޶��
                                                ^
/tmp/kernel_exploit.c:4:51: error: stray '\225' in program
 Z.t����w�{e�+g��h�G讶�y�'v+b�zbv�bu�+�'��?�(b��k�Ǭ��i���{����j�����q�,���5B������ z������ǭ�'t����Қ����k��g�+-zoۊ�j�iz[�����1�Z"�����m�(���mz�ڶ+ޞ̬�鬺�(�j޶��
                                                   ^
/tmp/kernel_exploit.c:4:52: error: stray '\332' in program
 Z.t����w�{e�+g��h�G讶�y�'v+b�zbv�bu�+�'��?�(b��k�Ǭ��i���{����j�����q�,���5B������ z������ǭ�'t����Қ����k��g�+-zoۊ�j�iz[�����1�Z"�����m�(���mz�ڶ+ޞ̬�鬺�(�j޶��
                                                    ^
/tmp/kernel_exploit.c:4:54: error: stray '\241' in program
 Z.t����w�{e�+g��h�G讶�y�'v+b�zbv�bu�+�'��?�(b��k�Ǭ��i���{����j�����q�,���5B������ z������ǭ�'t����Қ����k��g�+-zoۊ�j�iz[�����1�Z"�����m�(���mz�ڶ+ޞ̬�鬺�(�j޶��
                                                      ^
/tmp/kernel_exploit.c:4:55: error: stray '\307' in program
 Z.t����w�{e�+g��h�G讶�y�'v+b�zbv�bu�+�'��?�(b��k�Ǭ��i���{����j�����q�,���5B������ z������ǭ�'t����Қ����k��g�+-zoۊ�j�iz[�����1�Z"�����m�(���mz�ڶ+ޞ̬�鬺�(�j޶��
                                                       ^
/tmp/kernel_exploit.c:4:56: error: stray '\254' in program
 Z.t����w�{e�+g��h�G讶�y�'v+b�zbv�bu�+�'��?�(b��k�Ǭ��i���{����j�����q�,���5B������ z������ǭ�'t����Қ����k��g�+-zoۊ�j�iz[�����1�Z"�����m�(���mz�ڶ+ޞ̬�鬺�(�j޶��
                                                        ^
/tmp/kernel_exploit.c:4:57: error: stray '\261' in program
 Z.t����w�{e�+g��h�G讶�y�'v+b�zbv�bu�+�'��?�(b��k�Ǭ��i���{����j�����q�,���5B������ z������ǭ�'t����Қ����k��g�+-zoۊ�j�iz[�����1�Z"�����m�(���mz�ڶ+ޞ̬�鬺�(�j޶��
                                                         ^
/tmp/kernel_exploit.c:4:58: error: stray '\354' in program
 Z.t����w�{e�+g��h�G讶�y�'v+b�zbv�bu�+�'��?�(b��k�Ǭ��i���{����j�����q�,���5B������ z������ǭ�'t����Қ����k��g�+-zoۊ�j�iz[�����1�Z"�����m�(���mz�ڶ+ޞ̬�鬺�(�j޶��
                                                          ^
/tmp/kernel_exploit.c:4:60: error: stray '\226' in program
 Z.t����w�{e�+g��h�G讶�y�'v+b�zbv�bu�+�'��?�(b��k�Ǭ��i���{����j�����q�,���5B������ z������ǭ�'t����Қ����k��g�+-zoۊ�j�iz[�����1�Z"�����m�(���mz�ڶ+ޞ̬�鬺�(�j޶��
                                                            ^
/tmp/kernel_exploit.c:4:61: error: stray '\210' in program
 Z.t����w�{e�+g��h�G讶�y�'v+b�zbv�bu�+�'��?�(b��k�Ǭ��i���{����j�����q�,���5B������ z������ǭ�'t����Қ����k��g�+-zoۊ�j�iz[�����1�Z"�����m�(���mz�ڶ+ޞ̬�鬺�(�j޶��
                                                             ^
/tmp/kernel_exploit.c:4:62: error: stray '\255' in program
 Z.t����w�{e�+g��h�G讶�y�'v+b�zbv�bu�+�'��?�(b��k�Ǭ��i���{����j�����q�,���5B������ z������ǭ�'t����Қ����k��g�+-zoۊ�j�iz[�����1�Z"�����m�(���mz�ڶ+ޞ̬�鬺�(�j޶��
                                                              ^
/tmp/kernel_exploit.c:4:64: error: stray '\30' in program
 Z.t����w�{e�+g��h�G讶�y�'v+b�zbv�bu�+�'��?�(b��k�Ǭ��i���{����j�����q�,���5B������ z������ǭ�'t����Қ����k��g�+-zoۊ�j�iz[�����1�Z"�����m�(���mz�ڶ+ޞ̬�鬺�(�j޶��
                                                                ^
/tmp/kernel_exploit.c:4:65: error: stray '\255' in program
 Z.t����w�{e�+g��h�G讶�y�'v+b�zbv�bu�+�'��?�(b��k�Ǭ��i���{����j�����q�,���5B������ z������ǭ�'t����Қ����k��g�+-zoۊ�j�iz[�����1�Z"�����m�(���mz�ڶ+ޞ̬�鬺�(�j޶��
                                                                 ^
/tmp/kernel_exploit.c:4:66: error: stray '\323' in program
 Z.t����w�{e�+g��h�G讶�y�'v+b�zbv�bu�+�'��?�(b��k�Ǭ��i���{����j�����q�,���5B������ z������ǭ�'t����Қ����k��g�+-zoۊ�j�iz[�����1�Z"�����m�(���mz�ڶ+ޞ̬�鬺�(�j޶��
                                                                  ^
/tmp/kernel_exploit.c:4:67: error: stray '\377' in program
 Z.t����w�{e�+g��h�G讶�y�'v+b�zbv�bu�+�'��?�(b��k�Ǭ��i���{����j�����q�,���5B������ z������ǭ�'t����Қ����k��g�+-zoۊ�j�iz[�����1�Z"�����m�(���mz�ڶ+ޞ̬�鬺�(�j޶��
                                                                   ^
/tmp/kernel_exploit.c:4:68: error: stray '\317' in program
 Z.t����w�{e�+g��h�G讶�y�'v+b�zbv�bu�+�'��?�(b��k�Ǭ��i���{����j�����q�,���5B������ z������ǭ�'t����Қ����k��g�+-zoۊ�j�iz[�����1�Z"�����m�(���mz�ڶ+ޞ̬�鬺�(�j޶��
                                                                    ^
/tmp/kernel_exploit.c:4:70: error: stray '\267' in program
 Z.t����w�{e�+g��h�G讶�y�'v+b�zbv�bu�+�'��?�(b��k�Ǭ��i���{����j�����q�,���5B������ z������ǭ�'t����Қ����k��g�+-zoۊ�j�iz[�����1�Z"�����m�(���mz�ڶ+ޞ̬�鬺�(�j޶��
                                                                      ^
/tmp/kernel_exploit.c:4:71: error: stray '\247' in program
 Z.t����w�{e�+g��h�G讶�y�'v+b�zbv�bu�+�'��?�(b��k�Ǭ��i���{����j�����q�,���5B������ z������ǭ�'t����Қ����k��g�+-zoۊ�j�iz[�����1�Z"�����m�(���mz�ڶ+ޞ̬�鬺�(�j޶��
                                                                       ^
/tmp/kernel_exploit.c:4:72: error: stray '\266' in program
 Z.t����w�{e�+g��h�G讶�y�'v+b�zbv�bu�+�'��?�(b��k�Ǭ��i���{����j�����q�,���5B������ z������ǭ�'t����Қ����k��g�+-zoۊ�j�iz[�����1�Z"�����m�(���mz�ڶ+ޞ̬�鬺�(�j޶��
                                                                        ^
/tmp/kernel_exploit.c:4:73: error: stray '\232' in program
 Z.t����w�{e�+g��h�G讶�y�'v+b�zbv�bu�+�'��?�(b��k�Ǭ��i���{����j�����q�,���5B������ z������ǭ�'t����Қ����k��g�+-zoۊ�j�iz[�����1�Z"�����m�(���mz�ڶ+ޞ̬�鬺�(�j޶��
                                                                         ^
/tmp/kernel_exploit.c:4:74: error: stray '\350' in program
 Z.t����w�{e�+g��h�G讶�y�'v+b�zbv�bu�+�'��?�(b��k�Ǭ��i���{����j�����q�,���5B������ z������ǭ�'t����Қ����k��g�+-zoۊ�j�iz[�����1�Z"�����m�(���mz�ڶ+ޞ̬�鬺�(�j޶��
                                                                          ^
/tmp/kernel_exploit.c:4:76: error: stray '\353' in program
 Z.t����w�{e�+g��h�G讶�y�'v+b�zbv�bu�+�'��?�(b��k�Ǭ��i���{����j�����q�,���5B������ z������ǭ�'t����Қ����k��g�+-zoۊ�j�iz[�����1�Z"�����m�(���mz�ڶ+ޞ̬�鬺�(�j޶��
                                                                            ^
/tmp/kernel_exploit.c:4:78: error: stray '\301' in program
 Z.t����w�{e�+g��h�G讶�y�'v+b�zbv�bu�+�'��?�(b��k�Ǭ��i���{����j�����q�,���5B������ z������ǭ�'t����Қ����k��g�+-zoۊ�j�iz[�����1�Z"�����m�(���mz�ڶ+ޞ̬�鬺�(�j޶��
                                                                              ^
/tmp/kernel_exploit.c:4:79: error: stray '\250' in program
 Z.t����w�{e�+g��h�G讶�y�'v+b�zbv�bu�+�'��?�(b��k�Ǭ��i���{����j�����q�,���5B������ z������ǭ�'t����Қ����k��g�+-zoۊ�j�iz[�����1�Z"�����m�(���mz�ڶ+ޞ̬�鬺�(�j޶��
                                                                               ^
/tmp/kernel_exploit.c:4:80: error: stray '\255' in program
 Z.t����w�{e�+g��h�G讶�y�'v+b�zbv�bu�+�'��?�(b��k�Ǭ��i���{����j�����q�,���5B������ z������ǭ�'t����Қ����k��g�+-zoۊ�j�iz[�����1�Z"�����m�(���mz�ڶ+ޞ̬�鬺�(�j޶��
                                                                                ^
/tmp/kernel_exploit.c:4:81: error: invalid suffix "B" on integer constant
 Z.t����w�{e�+g��h�G讶�y�'v+b�zbv�bu�+�'��?�(b��k�Ǭ��i���{����j�����q�,���5B������ z������ǭ�'t����Қ����k��g�+-zoۊ�j�iz[�����1�Z"�����m�(���mz�ڶ+ޞ̬�鬺�(�j޶��
                                                                                 ^~
/tmp/kernel_exploit.c:4:83: error: stray '\313' in program
 Z.t����w�{e�+g��h�G讶�y�'v+b�zbv�bu�+�'��?�(b��k�Ǭ��i���{����j�����q�,���5B������ z������ǭ�'t����Қ����k��g�+-zoۊ�j�iz[�����1�Z"�����m�(���mz�ڶ+ޞ̬�鬺�(�j޶��
                                                                                   ^
/tmp/kernel_exploit.c:4:84: error: stray '\377' in program
 Z.t����w�{e�+g��h�G讶�y�'v+b�zbv�bu�+�'��?�(b��k�Ǭ��i���{����j�����q�,���5B������ z������ǭ�'t����Қ����k��g�+-zoۊ�j�iz[�����1�Z"�����m�(���mz�ڶ+ޞ̬�鬺�(�j޶��
                                                                                    ^
/tmp/kernel_exploit.c:4:85: error: stray '\364' in program
 Z.t����w�{e�+g��h�G讶�y�'v+b�zbv�bu�+�'��?�(b��k�Ǭ��i���{����j�����q�,���5B������ z������ǭ�'t����Қ����k��g�+-zoۊ�j�iz[�����1�Z"�����m�(���mz�ڶ+ޞ̬�鬺�(�j޶��
                                                                                     ^
/tmp/kernel_exploit.c:4:86: error: stray '\353' in program
 Z.t����w�{e�+g��h�G讶�y�'v+b�zbv�bu�+�'��?�(b��k�Ǭ��i���{����j�����q�,���5B������ z������ǭ�'t����Қ����k��g�+-zoۊ�j�iz[�����1�Z"�����m�(���mz�ڶ+ޞ̬�鬺�(�j޶��
                                                                                      ^
/tmp/kernel_exploit.c:4:87: error: stray '\312' in program
 Z.t����w�{e�+g��h�G讶�y�'v+b�zbv�bu�+�'��?�(b��k�Ǭ��i���{����j�����q�,���5B������ z������ǭ�'t����Қ����k��g�+-zoۊ�j�iz[�����1�Z"�����m�(���mz�ڶ+ޞ̬�鬺�(�j޶��
                                                                                       ^
/tmp/kernel_exploit.c:4:88: error: stray '\332' in program
 Z.t����w�{e�+g��h�G讶�y�'v+b�zbv�bu�+�'��?�(b��k�Ǭ��i���{����j�����q�,���5B������ z������ǭ�'t����Қ����k��g�+-zoۊ�j�iz[�����1�Z"�����m�(���mz�ڶ+ޞ̬�鬺�(�j޶��
                                                                                        ^
/tmp/kernel_exploit.c:4:91: error: stray '\332' in program
 Z.t����w�{e�+g��h�G讶�y�'v+b�zbv�bu�+�'��?�(b��k�Ǭ��i���{����j�����q�,���5B������ z������ǭ�'t����Қ����k��g�+-zoۊ�j�iz[�����1�Z"�����m�(���mz�ڶ+ޞ̬�鬺�(�j޶��
                                                                                           ^
/tmp/kernel_exploit.c:4:92: error: stray '\350' in program
 Z.t����w�{e�+g��h�G讶�y�'v+b�zbv�bu�+�'��?�(b��k�Ǭ��i���{����j�����q�,���5B������ z������ǭ�'t����Қ����k��g�+-zoۊ�j�iz[�����1�Z"�����m�(���mz�ڶ+ޞ̬�鬺�(�j޶��
                                                                                            ^
/tmp/kernel_exploit.c:4:93: error: stray '\242' in program
 Z.t����w�{e�+g��h�G讶�y�'v+b�zbv�bu�+�'��?�(b��k�Ǭ��i���{����j�����q�,���5B������ z������ǭ�'t����Қ����k��g�+-zoۊ�j�iz[�����1�Z"�����m�(���mz�ڶ+ޞ̬�鬺�(�j޶��
                                                                                             ^
/tmp/kernel_exploit.c:4:94: error: stray '\333' in program
 Z.t����w�{e�+g��h�G讶�y�'v+b�zbv�bu�+�'��?�(b��k�Ǭ��i���{����j�����q�,���5B������ z������ǭ�'t����Қ����k��g�+-zoۊ�j�iz[�����1�Z"�����m�(���mz�ڶ+ޞ̬�鬺�(�j޶��
                                                                                              ^
/tmp/kernel_exploit.c:4:95: error: stray '\36' in program
 Z.t����w�{e�+g��h�G讶�y�'v+b�zbv�bu�+�'��?�(b��k�Ǭ��i���{����j�����q�,���5B������ z������ǭ�'t����Қ����k��g�+-zoۊ�j�iz[�����1�Z"�����m�(���mz�ڶ+ޞ̬�鬺�(�j޶��
                                                                                               ^
/tmp/kernel_exploit.c:4:96: error: stray '\266' in program
 Z.t����w�{e�+g��h�G讶�y�'v+b�zbv�bu�+�'��?�(b��k�Ǭ��i���{����j�����q�,���5B������ z������ǭ�'t����Қ����k��g�+-zoۊ�j�iz[�����1�Z"�����m�(���mz�ڶ+ޞ̬�鬺�(�j޶��
                                                                                                ^
/tmp/kernel_exploit.c:4:97: error: stray '\350' in program
 Z.t����w�{e�+g��h�G讶�y�'v+b�zbv�bu�+�'��?�(b��k�Ǭ��i���{����j�����q�,���5B������ z������ǭ�'t����Қ����k��g�+-zoۊ�j�iz[�����1�Z"�����m�(���mz�ڶ+ޞ̬�鬺�(�j޶��
                                                                                                 ^
/tmp/kernel_exploit.c:4:98: error: stray '\235' in program
 Z.t����w�{e�+g��h�G讶�y�'v+b�zbv�bu�+�'��?�(b��k�Ǭ��i���{����j�����q�,���5B������ z������ǭ�'t����Қ����k��g�+-zoۊ�j�iz[�����1�Z"�����m�(���mz�ڶ+ޞ̬�鬺�(�j޶��
                                                                                                  ^
/tmp/kernel_exploit.c:4:99: error: stray '\322' in program
 Z.t����w�{e�+g��h�G讶�y�'v+b�zbv�bu�+�'��?�(b��k�Ǭ��i���{����j�����q�,���5B������ z������ǭ�'t����Қ����k��g�+-zoۊ�j�iz[�����1�Z"�����m�(���mz�ڶ+ޞ̬�鬺�(�j޶��
                                                                                                   ^
/tmp/kernel_exploit.c:4:100: error: stray '\307' in program
 Z.t����w�{e�+g��h�G讶�y�'v+b�zbv�bu�+�'��?�(b��k�Ǭ��i���{����j�����q�,���5B������ z������ǭ�'t����Қ����k��g�+-zoۊ�j�iz[�����1�Z"�����m�(���mz�ڶ+ޞ̬�鬺�(�j޶��
                                                                                                    ^
/tmp/kernel_exploit.c:4:101: error: stray '\255' in program
 Z.t����w�{e�+g��h�G讶�y�'v+b�zbv�bu�+�'��?�(b��k�Ǭ��i���{����j�����q�,���5B������ z������ǭ�'t����Қ����k��g�+-zoۊ�j�iz[�����1�Z"�����m�(���mz�ڶ+ޞ̬�鬺�(�j޶��
                                                                                                     ^
/tmp/kernel_exploit.c:4:102: error: stray '\202' in program
 Z.t����w�{e�+g��h�G讶�y�'v+b�zbv�bu�+�'��?�(b��k�Ǭ��i���{����j�����q�,���5B������ z������ǭ�'t����Қ����k��g�+-zoۊ�j�iz[�����1�Z"�����m�(���mz�ڶ+ޞ̬�鬺�(�j޶��
                                                                                                      ^
/tmp/kernel_exploit.c:4:103: warning: missing terminating ' character
 Z.t����w�{e�+g��h�G讶�y�'v+b�zbv�bu�+�'��?�(b��k�Ǭ��i���{����j�����q�,���5B������ z������ǭ�'t����Қ����k��g�+-zoۊ�j�iz[�����1�Z"�����m�(���mz�ڶ+ޞ̬�鬺�(�j޶��
                                                                                                       ^
/tmp/kernel_exploit.c:4:103: error: missing terminating ' character
 Z.t����w�{e�+g��h�G讶�y�'v+b�zbv�bu�+�'��?�(b��k�Ǭ��i���{����j�����q�,���5B������ z������ǭ�'t����Қ����k��g�+-zoۊ�j�iz[�����1�Z"�����m�(���mz�ڶ+ޞ̬�鬺�(�j޶��
                                                                                                       ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
chmod: cannot access '/tmp/kernel_exploit': No such file or directory
[*] Running kernel exploit...
sh: /tmp/kernel_exploit: No such file or directory

[*] Trying alternative exploit...
sh: /tmp/simple: Permission denied
