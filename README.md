# advanced_computer_network@pknu 2020
 * Assignment supplements for lecture **Advanced Computer Network@PKNU 2020 Autumn**.
 * Author: 201955277 **Jongmin Kim <[jmkim@pukyong.ac.kr](mailto:jmkim@pukyong.ac.kr)>**

### Host A: Alice
 * Hostname: `alice.vaai`
 * IP address: `192.168.149.11`
 * Purpose:
    - **DNS server** for `.vaai` domain
    - **Web server** (`http://192.168.149.11` or `http://alice.vaai`)
    - **Mail server** for `@alice.vaai` (eg. `username@alice.vaai`)
 * Configuration files
    - [**Base**](alice-base) `Linux alice 5.8.0-2-amd64 #1 SMP Debian 5.8.10-1 (2020-09-19) x86_64 GNU/Linux`
    - [**DNS server**](alice-dns) `BIND 9.16.6-Debian (Stable Release) <id:25846cf>`
    - [**HTTP web server**](alice-http) `nginx version: nginx/1.18.0`
    - [**Mail server**](alice-mailer) `Postfix 3.5.6`

### Host B: Bob
 * Hostname: `bob.vaai`
 * IP address: `192.168.149.12`
 * Purpose:
    - **Mail server** for `bob.vaai` (eg. `username@bob.vaai`)
 * Configuration files
    - [**Base**](bob-base) - `Linux bob 5.8.0-2-amd64 #1 SMP Debian 5.8.10-1 (2020-09-19) x86_64 GNU/Linux`
    - [**Mail server**](bob-mailer) `Postfix 3.5.6`
