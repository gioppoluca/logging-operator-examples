The Flow used collect logs and errors.

# Log example

```
[Fri Mar 08 08:34:28.171058 2024] [security2:error] [pid 16:tid 140648904652480] [client 127.0.0.1:57184] [client 127.0.0.1] ModSecurity: collections_remove_stale: Failed to access DBM file "/var/cache/modsecurity/daemon-ip": Permission denied [hostname "127.0.0.1"] [uri "/server-status"] [unique_id "ZerNlO25_uKU-0S3UK5FFgAAAJc"]
2024-03-08T09:34:41.012954021+01:00 [Fri Mar 08 08:34:41.012844 2024] [security2:error] [pid 12:tid 140650112612032] [client 10.42.4.222:36570] [client 10.42.4.222] ModSecurity: collections_remove_stale: Failed to access DBM file "/var/cache/modsecurity/daemon-global": Permission denied [hostname "10.42.4.28"] [uri "/server-status"] [unique_id "ZerNoYh-MDq70gQs-QaODQAAAAI"]
2024-03-08T09:34:41.060708454+01:00 [Fri Mar 08 08:34:41.060595 2024] [security2:error] [pid 12:tid 140650112612032] [client 10.42.4.222:36570] [client 10.42.4.222] ModSecurity: collections_remove_stale: Failed to access DBM file "/var/cache/modsecurity/daemon-ip": Permission denied [hostname "10.42.4.28"] [uri "/server-status"] [unique_id "ZerNoYh-MDq70gQs-QaODQAAAAI"]
2024-03-08T09:46:01.013780543+01:00 [Fri Mar 08 08:46:01.013667 2024] [security2:error] [pid 14:tid 140649936430784] [client 10.42.4.222:37062] [client 10.42.4.222] ModSecurity: collections_remove_stale: Failed to access DBM file "/var/cache/modsecurity/daemon-global": Permission denied [hostname "10.42.4.28"] [uri "/server-status"] [unique_id "ZerQSYQ-RKtgvkJyHVIn5wAAAEc"]
[Fri Mar 08 08:46:01.013706 2024] [security2:error] [pid 14:tid 140649936430784] [client 10.42.4.222:37062] [client 10.42.4.222] ModSecurity: collections_remove_stale: Failed to access DBM file "/var/cache/modsecurity/daemon-ip": Permission denied [hostname "10.42.4.28"] [uri "/server-status"] [unique_id "ZerQSYQ-RKtgvkJyHVIn5wAAAEc"]
2024-03-08T09:46:27.560843134+01:00 10.81.200.242 - - [08/Mar/2024:08:46:27 +0000] "GET / HTTP/1.1" 304 -
2024-03-08T09:46:27.560871017+01:00 [08/Mar/2024:08:46:27 +0000] 10.81.200.242 TLSv1.3 TLS_AES_256_GCM_SHA384 "GET / HTTP/1.1" -
2024-03-08T09:46:27.794011543+01:00 10.81.200.242 - - [08/Mar/2024:08:46:27 +0000] "GET /styles.ef46db3751d8e999.css HTTP/1.1" 304 -
2024-03-08T09:46:27.794045122+01:00 [08/Mar/2024:08:46:27 +0000] 10.81.200.242 TLSv1.3 TLS_AES_256_GCM_SHA384 "GET /styles.ef46db3751d8e999.css HTTP/1.1" -
2024-03-08T09:46:27.806924677+01:00 10.81.200.242 - - [08/Mar/2024:08:46:27 +0000] "GET /polyfills.e923bc47f4506ddd.js HTTP/1.1" 304 -
[08/Mar/2024:08:46:27 +0000] 10.81.200.242 TLSv1.3 TLS_AES_256_GCM_SHA384 "GET /polyfills.e923bc47f4506ddd.js HTTP/1.1" -
2024-03-08T09:46:27.960946243+01:00 10.81.200.242 - - [08/Mar/2024:08:46:27 +0000] "GET /runtime.ca506f8f1ce94090.js HTTP/1.1" 304 -
[08/Mar/2024:08:46:27 +0000] 10.81.200.242 TLSv1.3 TLS_AES_256_GCM_SHA384 "GET /runtime.ca506f8f1ce94090.js HTTP/1.1" -
2024-03-08T09:46:27.963247310+01:00 10.81.200.242 - - [08/Mar/2024:08:46:27 +0000] "GET /main.0d4e5d53ee50cfeb.js HTTP/1.1" 304 -
2024-03-08T09:46:27.963264202+01:00 [08/Mar/2024:08:46:27 +0000] 10.81.200.242 TLSv1.3 TLS_AES_256_GCM_SHA384 "GET /main.0d4e5d53ee50cfeb.js HTTP/1.1" -
2024-03-08T09:46:28.161480914+01:00 10.81.200.242 - - [08/Mar/2024:08:46:28 +0000] "GET /favicon.ico HTTP/1.1" 304 -
[08/Mar/2024:08:46:28 +0000] 10.81.200.242 TLSv1.3 TLS_AES_256_GCM_SHA384 "GET /favicon.ico HTTP/1.1" -
```
