# quectel-support

* Conf file:
```
/opt/support/QLog_Linux_and_Android_V1.5.26/conf/default_adpl_1e1e.cfg
```

* Qlog command:
```
/opt/support/QLog_Linux_and_Android_V1.5.26/out/QLog -s /opt/support/logs &>/opt/support/Qlog.out
```

* AT Commands issued using at the `minicom -D /de v/ttyUSB3` terminal:
```
AT+QGMR
RM520NGLAAR01A08M4G_01.204.01.204

OK
AT+CSUB
SubEdition: V01

OK
AT+CFUN=0
OK

+CFUN: 0

AT+CFUN=1
+CME ERROR: 0

at+qcfg="aprstlevel",0
OK
at+qcfg="modemrstlevel",0
OK
at+qcfg="dbgctl",0
OK
at+qtest="dump",1
RDY

+QUSIM: 1

+QIND: SMS DONE
AT
OK

+QIND: PB DONE
AT
OK
AT
OK
AT
OK

OK
ATE
OK
```
