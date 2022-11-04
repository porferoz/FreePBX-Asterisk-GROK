# FreePBX-Asterisk-GROK
Algunos GROKs para Asterisk (Especificamente FreePBX)

El GROK esta enfocado a estructurar el LOG proveniente de FreePBX(FreePBX 15.0.24) y recibido en Graylog (Graylog 4.3.8+8c4705e).

Ejemplo del Mensaje:

message
SECURITY[30993]: res_security_log.c:116 in security_event_stasis_cb: SecurityEvent="SuccessfulAuth",EventTV="2022-11-04T10:26:13.905-0600",Severity="Informational",Service="SIP",EventVersion="1",AccountID="7071",SessionID="0x7ff408020630",LocalAddress="IPV4/UDP/192.168.143.100/5060",RemoteAddress="IPV4/UDP/92.68.15.157/5060",UsingPassword="1"

