### Janus WebRTC

Janus is an open source, general purpose, WebRTC server designed and developed by Meetecho. This version of the server is tailored for Linux systems, although it can be compiled for, and installed on, MacOS machines as well. Windows is not supported, but if that's a requirement, Janus is known to work in the "Windows Subsystem for Linux" on Windows 10: do NOT trust repos that provide .exe builds of Janus, they are not official and will not be supported.

Website - https://janus.conf.meetecho.com/

Github - https://github.com/meetecho/janus-gateway

CVE ID | Score | Description
-------|-------|-------------
[CVE-2020-13898](https://nvd.nist.gov/vuln/detail/CVE-2020-13898) | **7.5 HIGH** | An issue was discovered in janus-gateway (aka Janus WebRTC Server) through 0.10.0. janus_sdp_process in sdp.c has a NULL pointer dereference.
[CVE-2020-13899](https://nvd.nist.gov/vuln/detail/CVE-2020-13899) | **7.5 HIGH** | An issue was discovered in janus-gateway (aka Janus WebRTC Server) through 0.10.0. janus_process_incoming_request in janus.c discloses information from uninitialized stack memory.
[CVE-2020-13900](https://nvd.nist.gov/vuln/detail/CVE-2020-13900) | **7.5 HIGH** | An issue was discovered in janus-gateway (aka Janus WebRTC Server) through 0.10.0. janus_sdp_preparse in sdp.c has a NULL pointer dereference.
[CVE-2020-13901](https://nvd.nist.gov/vuln/detail/CVE-2020-13901) | **9.8 CRITICAL** | An issue was discovered in janus-gateway (aka Janus WebRTC Server) through 0.10.0. janus_sdp_merge in sdp.c has a stack-based buffer overflow.