---
title: Home
layout: home
---

   /bin/bash based SSL/TLS tester: testssl.sh

![testssl icon](testssl-icon.png)

# Testing TLS/SSL encryption

  

## testssl.sh

is a [free](LICENSE.txt "GPL v2") command line tool which checks a server's service on any port for the support of TLS/SSL ciphers, protocols as well as recent cryptographic flaws and more.  
  

| [Name](?sort=name&order=desc) | [Last Modified](?sort=modtime) | [Size](?sort=size) | [Type](?sort=file_type) |
| --- | --- | --- | --- |
| [2.6](2.6)/ | 2018-Nov-15 22:02:23 | \-- | Directory |
| [2.8](2.8)/ | 2018-Nov-15 22:46:12 | \-- | Directory |
| [2.9.5](2.9.5)/ | 2020-Jan-23 22:04:09 | \-- | Directory |
| [bin](bin)/ | 2022-Nov-22 16:48:47 | \-- | Directory |
| [bleichenbacher](bleichenbacher)/ | 2018-Feb-23 18:00:33 | \-- | Directory |
| [doc](doc)/ | 2022-Nov-22 16:50:07 | \-- | Directory |
| [etc](etc)/ | 2022-Nov-22 16:49:13 | \-- | Directory |
| [openssl-1.0.2i-chacha.pm.ipv6.contributed](openssl-1.0.2i-chacha.pm.ipv6.contributed)/ | 2020-Sep-17 09:55:59 | \-- | Directory |
| [openssl-1.0.2k-bad](openssl-1.0.2k-bad)/ | 2022-Sep-01 19:39:34 | \-- | Directory |
| [utils](utils)/ | 2022-Nov-22 16:49:53 | \-- | Directory |
|     |     |     |     |
| [CHANGELOG.md](CHANGELOG.md) | 2022-Sep-29 08:40:32 | 17.20KB | MD File |
| [CONTRIBUTING.md](CONTRIBUTING.md) | 2022-Sep-29 08:40:32 | 728.00B | MD File |
| [CREDITS.md](CREDITS.md) | 2022-Sep-29 08:40:32 | 3.90KB | MD File |
| [Dockerfile](Dockerfile) | 2022-Sep-29 08:40:32 | 585.00B | Unknown File |
| [Dockerfile.git](Dockerfile.git) | 2022-Sep-29 08:40:32 | 681.00B | GIT File |
| [Dockerfile.md](Dockerfile.md) | 2022-Sep-29 08:40:32 | 1.53KB | MD File |
| [LICENSE.txt](LICENSE.txt) | 2014-May-03 11:04:22 | 17.59KB | TXT Type Document |
| [Readme.md](Readme.md) | 2022-Nov-10 15:42:27 | 6.25KB | MD File |
| [openssl-iana.mapping.html](openssl-iana.mapping.html) | 2024-Aug-26 15:30:31 | 60.80KB | HTML File |
| [testssl.sh](testssl.sh) | 2022-Sep-29 08:40:32 | 997.07KB | SH File |
| [testssl.sh-3.0.6.tar.gz](testssl.sh-3.0.6.tar.gz) | 2021-Oct-03 19:07:15 | 8.82MB | GZ Compressed Archive |
| [testssl.sh-3.0.6.tar.gz.asc](testssl.sh-3.0.6.tar.gz.asc) | 2021-Oct-03 19:07:15 | 488.00B | ASC File |
| [testssl.sh-3.0.7.tar.gz](testssl.sh-3.0.7.tar.gz) | 2022-Feb-19 14:59:59 | 8.79MB | GZ Compressed Archive |
| [testssl.sh-3.0.7.tar.gz.asc](testssl.sh-3.0.7.tar.gz.asc) | 2022-Feb-19 14:59:59 | 488.00B | ASC File |
| [testssl.sh-3.0.8.tar.gz](testssl.sh-3.0.8.tar.gz) | 2022-Sep-29 08:46:37 | 17.59MB | GZ Compressed Archive |
| [testssl.sh-3.0.8.tar.gz.asc](testssl.sh-3.0.8.tar.gz.asc) | 2022-Sep-29 08:46:32 | 488.00B | ASC File |
| [testssl.sh-3.0.9.tar.gz](testssl.sh-3.0.9.tar.gz) | 2024-Jun-13 19:02:46 | 8.95MB | GZ Compressed Archive |
| [testssl.sh-3.0.9.tar.gz.asc](testssl.sh-3.0.9.tar.gz.asc) | 2024-Jun-13 19:04:07 | 488.00B | ASC File |
| [testssl.sh.asc](testssl.sh.asc) | 2021-Oct-03 19:07:15 | 488.00B | ASC File |
| [testssl\_german\_owasp\_day.pdf](testssl_german_owasp_day.pdf) | 2018-Nov-18 13:53:38 | 1.11MB | PDF Type Document |

  
document.writeln("<img src='testssl-standard50.jpg' alt='Standard call: testssl.sh &lt;hostname&gt;' id='img1' style='float:right' onmouseover='mouseOverImage1()' onmouseout='mouseOutImage1()'>"); function mouseOverImage1() { document.getElementById("img1").src = "testssl-standard.jpg"; } function mouseOutImage1() { document.getElementById("img1").src = "testssl-standard50.jpg"; }

![Standard call: testssl.sh](/testssl-standard.png)

### Key features

*   Clear output: you can tell easily whether anything is good or bad
*   Ease of installation: Works for Linux, Mac OSX, FreeBSD, NetBSD and WSL/MSYS2/Cygwin out of the box: no need to install or configure something, no gems, CPAN, pip or the like. OpenBSD only needs bash to be postinstalled.
*   Alternatively a [Dockerfile](https://testssl.sh/Dockerfile) is provided or you can just use docker run --rm -ti drwetter/testssl.sh
*   Flexibility: You can test any SSL/TLS enabled and STARTTLS service, not only webservers at port 443
*   Toolbox: Several command line options help you to run _your_ test and configure _your_ output
*   Reliability: features are tested thoroughly
*   Verbosity: If a particular check cannot be performed because of a missing capability on your client side, you'll get a warning
*   Privacy: It's only you who sees the result, not a third party
*   Freedom: It's 100% open source. You can look at the code, see what's going on and you can change it. Heck, even the development is open (github)
*   Documentation: In [HTML](/doc/testssl.1.html), markdown or groff format

### License

`testssl.sh` is free and open source software. You can use it under the terms of GPLv2, please review the [License](LICENSE.txt "GPLv2") before using it.  
  
Attribution is important for the future of this project -- also in the internet. Thus if you're offering a scanner based on testssl.sh as a public and/or paid service in the internet you are strongly encouraged to mention to your audience that you're using this program and where to get this program from. That helps us to get bugfixes, other feedback and more contributions.  
  

### Donations

If you like this software, you or your company uses it a lot or even your company makes money from any service around testssl.sh, why not support the project with a donation? It helps keeping the project alive and kicking.  
  
Dirk setup a paypal account for it, keeps track of the money and makes sure it is spend on project related activities.  
  

   ![Donate with PayPal](https://testssl.sh/paypal-testssl.QR-Code.png "PayPal - The safer, easier way to pay online!")

  
  
If you want a deductable commercial invoice in return please [get in touch with me](https://drwetter.eu/kontakt "contact form with OpenPGP encryption on my business web site (sorry, it's in German. Fields should be self-explanatory)") **before** using paypal.  
  

### Development

[![github](GitHub-Mark-64px.png)](https://github.com/drwetter/testssl.sh) Development takes place at [github](https://github.com/drwetter/testssl.sh). We're now @ 3.2rc2 and 3.0.9 (stable). As of 2019, **you should use the latest 3.0.x version as 2.9.5 is not supported anymore**. As I do releases on github you can pull the zip for a stable release from there.  

  

#### Support status

Supported will always be the current dev version and the version before (n-1 rule). As soon as the dev version becomes the stable release, this will be the n-1 version and receives bugfixes only. The dev version has historically not delivered really broken software (no facebook paradigm). Consider it like a rolling release: It'll definitely change-- that is the point of development-- things might break for you if you e.g. expect the output or features all to be the same. But other than that: The dev version itself won't break (TM).

3.2 is now the version which we'll focus on. There may or maybe not a 3.0.10 release. We'll focus on 3.2 which evolved from 3.1dev. After the final release of 3.2 this will also formally become the stable, last supported version. Development will take place in 3.3dev then.

  
  
**Jun 13,2024:** Version 3.0.9, see [3.0.9 @ github](https://github.com/drwetter/testssl.sh/releases/tag/v3.0.9) or [here](testssl.sh-3.0.9.tar.gz)([signature](testssl.sh-3.0.9.tar.gz.asc)) .  
  
**Oct 10,2023:** After several non-tagged and not labelled rc versions a now version 3.2rc3 was released, see [3.2rc3 @ github](https://github.com/drwetter/testssl.sh/releases/tag/v3.2rc3)  
  
**Sep 19,2022:** Version 3.0.8, see [3.0.8 @ github](https://github.com/drwetter/testssl.sh/releases/tag/v3.0.8) or [here](testssl.sh-3.0.8.tar.gz)([signature](testssl.sh-3.0.8.tar.gz.asc)) .  
  
**Feb 19,2022:** Version 3.0.7, see [3.0.7 @ github](https://github.com/drwetter/testssl.sh/releases/tag/v3.0.7) or [here](testssl.sh-3.0.7.tar.gz)([signature](testssl.sh-3.0.7.tar.gz.asc)) .  
\[..\]  
**Jan 23,2020:** Version 3.0 release, see [3.0 @ github](https://github.com/drwetter/testssl.sh/releases/). It's been a long rolling release candidate phase since the first 3.0 RC version.  
  
**Dec 12, 2017:** ROBOT / Bleichenbacher check has been implemented. . Read more about this old+new attack @ [robotattack.org](https://robotattack.org). Please checkout [2.9dev @ github](https://github.com/drwetter/testssl.sh/). I compiled also some info [here](/bleichenbacher), including an Alexa Top 10k scan and some background information.  
  
**Sep 19,2017:** Version 2.9.5 has been released. Please checkout [2.9.5 @ github](https://github.com/drwetter/testssl.sh/tree/2.9.5) or download it from [here](testssl.sh), you need the [etc tar ball](etc+doc.tar.gz) as well.  
  

### Screenshots /Pictures here

The pictures are still from an older version of testssl.sh. This will be updated later. It should suffice to get a picture though.  
  

### Longer read

`testssl.sh` is pretty much portable/compatible. It is working on every Linux, Mac OS X, FreeBSD distribution, on MSYS2/Cygwin (slow). It is supposed also to work on any other unixoid systems. A newer OpenSSL version (1.0) is recommended though. `/bin/bash` is a prerequisite – otherwise there would be no sockets.  
  
Speaking of it: Since version 2.4 some of the checks were done with bash sockets. This improved gradually and from 2.9.5 on almost every check is done with bash sockets. Still OpenSSL is needed for some core functions like `openssl <verify|ocsp|pkey>` . In principle any OpenSSL or even LibreSSL can be used as a helper. It's recommended to use the one supplied as it makes sure special tests or features like IPv6, proxy support, STARTTLS MySQL or PostgreSQL are supported. (The one supplied stems originally from [github.com/PeterMosmans/openssl](https://github.com/PeterMosmans/openssl). _openssl-1.0.2k-chacha.pm.ipv6.Linux+FreeBSD.tar.gz_ is a Linux- and FreeBSD-only tarball. The directory _openssl-1.0.2i-chacha.pm.ipv6.contributed/_ contains contributed builds for ARM7l and Darwin binaries).  

#### Download shortcuts

Note the following features are supported by the webserver configuration:

*   `curl -L https://testssl.sh` or  `wget -O - https://testssl.sh` pulls the current stable code from here
*   `curl -L https://testssl.sh/dev/` or  `wget -O - https://testssl.sh/dev/` pulls the current development code from github

– each to standard output. Please note however that from 2.9dev on you need the _mandatory_ files in etc/ though, see [https://github.com/drwetter/testssl.sh/tree/3.0/etc](https://github.com/drwetter/testssl.sh/tree/3.0/etc).  
  

#### Usage

The normal use case is probably just testssl.sh <hostname>, see first picture right hand above (a deliberately bad configuration).  
  
Starting testssl.sh with no params will give you a general idea how to use it:

userid@**somehost**:~ % testssl.sh

     "testssl.sh \[options\] <URI>"    or    "testssl.sh <options>"


"testssl.sh <options>", where <options> is:

     --help                        what you're looking at
     -b, --banner                  displays banner + version of testssl.sh
     -v, --version                 same as previous
     -V, --local                   pretty print all local ciphers
     -V, --local <pattern>         which local ciphers with <pattern> are available? If pattern is not a number: word match

     <pattern>                     is always an ignore case word pattern of cipher hexcode or any other string in the name, kx or bits

"testssl.sh <URI>", where <URI> is:

     <URI>                         host|host:port|URL|URL:port   port 443 is default, URL can only contain HTTPS protocol)

"testssl.sh \[options\] <URI>", where \[options\] is:

     -t, --starttls <protocol>     Does a default run against a STARTTLS enabled <protocol,
                                   protocol is <ftp|smtp|lmtp|pop3|imap|xmpp|telnet|ldap|nntp|postgres|mysql>
     --xmpphost <to\_domain>        For STARTTLS enabled XMPP it supplies the XML stream to-'' domain -- sometimes needed
     --mx <domain/host>            Tests MX records from high to low priority (STARTTLS, port 25)
     --file/-iL <fname>            Mass testing option: Reads one testssl.sh command line per line from <fname>.
                                   Can be combined with --serial or --parallel. Implicitly turns on "--warnings batch".
                                   Text format 1: Comments via # allowed, EOF signals end of <fname>
                                   Text format 2: nmap output in greppable format (-oG), 1 port per line allowed
     --mode <serial|parallel>      Mass testing to be done serial (default) or parallel (--parallel is shortcut for the latter)
     --warnings <batch|off>        "batch" doesn't continue when a testing error is encountered, off continues and skips warnings
     --connect-timeout <seconds>   useful to avoid hangers. Max <seconds> to wait for the TCP socket connect to return
     --openssl-timeout <seconds>   useful to avoid hangers. Max <seconds> to wait before openssl connect will be terminated

single check as <options>  ("testssl.sh URI" does everything except -E and -g):
     -e, --each-cipher             checks each local cipher remotely
     -E, --cipher-per-proto        checks those per protocol
     -s, --std, --standard         tests certain lists of cipher suites by strength
     -p, --protocols               checks TLS/SSL protocols (including SPDY/HTTP2)
     -g, --grease                  tests several server implementation bugs like GREASE and size limitations
     -S, --server-defaults         displays the server's default picks and certificate info
     -P, --server-preference       displays the server's picks: protocol+cipher
     -x, --single-cipher <pattern> tests matched <pattern> of ciphers
                                   (if <pattern> not a number: word match)
     -c, --client-simulation       test client simulations, see which client negotiates with cipher and protocol
     -h, --header, --headers       tests HSTS, HPKP, server/app banner, security headers, cookie, reverse proxy, IPv4 address

     -U, --vulnerable              tests all (of the following) vulnerabilities (if applicable)
     -H, --heartbleed              tests for Heartbleed vulnerability
     -I, --ccs, --ccs-injection    tests for CCS injection vulnerability
     -T, --ticketbleed             tests for Ticketbleed vulnerability in BigIP loadbalancers
     -BB, --robot                  tests for Return of Bleichenbacher's Oracle Threat (ROBOT) vulnerability
     -R, --renegotiation           tests for renegotiation vulnerabilities
     -C, --compression, --crime    tests for CRIME vulnerability (TLS compression issue)
     -B, --breach                  tests for BREACH vulnerability (HTTP compression issue)
     -O, --poodle                  tests for POODLE (SSL) vulnerability
     -Z, --tls-fallback            checks TLS\_FALLBACK\_SCSV mitigation
     -W, --sweet32                 tests 64 bit block ciphers (3DES, RC2 and IDEA): SWEET32 vulnerability
     -A, --beast                   tests for BEAST vulnerability
     -L, --lucky13                 tests for LUCKY13
     -F, --freak                   tests for FREAK vulnerability
     -J, --logjam                  tests for LOGJAM vulnerability
     -D, --drown                   tests for DROWN vulnerability
     -f, --pfs, --fs, --nsa        checks (perfect) forward secrecy settings
     -4, --rc4, --appelbaum        which RC4 ciphers are being offered?

tuning / connect options (most also can be preset via environment variables):
     --fast                        omits some checks: using openssl for all ciphers (-e), show only first preferred cipher.
     -9, --full                    includes tests for implementation bugs and cipher per protocol (could disappear)
     --bugs                        enables the "-bugs" option of s\_client, needed e.g. for some buggy F5s
     --assume-http                 if protocol check fails it assumes HTTP protocol and enforces HTTP checks
     --ssl-native                  fallback to checks with OpenSSL where sockets are normally used
     --openssl <PATH>              use this openssl binary (default: look in $PATH, $RUN\_DIR of testssl.sh)
     --proxy <host:port|auto>      (experimental) proxy connects via <host:port>, auto: values from $env ($http(s)\_proxy)
     -6                            also use IPv6. Works only with supporting OpenSSL version and IPv6 connectivity
     --ip <ip>                     a) tests the supplied <ip> v4 or v6 address instead of resolving host(s) in URI
                                   b) arg "one" means: just test the first DNS returns (useful for multiple IPs)
     -n, --nodns <min|none>        if "none": do not try any DNS lookups, "min" queries A, AAAA and MX records
     --sneaky                      leave less traces in target logs: user agent, referer
     --ids-friendly                skips a few vulnerability checks which may cause IDSs to block the scanning IP
     --phone-out                   allow to contact external servers for CRL download and querying OCSP responder
     --add-ca <cafile>             path to <cafile> or a comma separated list of CA files enables test against additional CAs.
     --basicauth <user:pass>       provide HTTP basic auth information.

output options (can also be preset via environment variables):
     --quiet                       don't output the banner. By doing this you acknowledge usage terms normally appearing in the banner
     --wide                        wide output for tests like RC4, BEAST. PFS also with hexcode, kx, strength, RFC name
     --show-each                   for wide outputs: display all ciphers tested -- not only succeeded ones
     --mapping <openssl|           openssl: use the OpenSSL cipher suite name as the primary name cipher suite name form (default)
                iana|rfc             -> use the IANA/(RFC) cipher suite name as the primary name cipher suite name form
                no-openssl|          -> don't display the OpenSSL cipher suite name, display IANA/(RFC) names only
                no-iana|no-rfc>      -> don't display the IANA/(RFC) cipher suite name, display OpenSSL names only
     --color <0|1|2|3>             0: no escape or other codes,  1: b/w escape codes,  2: color (default), 3: extra color (color all ciphers)
     --colorblind                  swap green and blue in the output
     --debug <0-6>                 1: screen output normal but keeps debug output in /tmp/.  2-6: see "grep -A 5 '^DEBUG=' testssl.sh"

file output options (can also be preset via environment variables)
     --log, --logging              logs stdout to '${NODE}-p${port}${YYYYMMDD-HHMM}.log' in current working directory (cwd)
     --logfile|-oL <logfile>       logs stdout to 'dir/${NODE}-p${port}${YYYYMMDD-HHMM}.log'. If 'logfile' is a dir or to a specified 'logfile'
     --json                        additional output of findings to flat JSON file '${NODE}-p${port}${YYYYMMDD-HHMM}.json' in cwd
     --jsonfile|-oj <jsonfile>     additional output to the specified flat JSON file or directory, similar to --logfile
     --json-pretty                 additional JSON structured output of findings to a file '${NODE}-p${port}${YYYYMMDD-HHMM}.json' in cwd
     --jsonfile-pretty|-oJ <jsonfile>  additional JSON structured output to the specified file or directory, similar to --logfile
     --csv                         additional output of findings to CSV file '${NODE}-p${port}${YYYYMMDD-HHMM}.csv' in cwd or directory
     --csvfile|-oC <csvfile>       additional output as CSV to the specified file or directory, similar to --logfile
     --html                        additional output as HTML to file '${NODE}-p${port}${YYYYMMDD-HHMM}.html'
     --htmlfile|-oH <htmlfile>     additional output as HTML to the specified file or directory, similar to --logfile
     --out(f,F)ile|-oa/-oA <fname> log to a LOG,JSON,CSV,HTML file (see nmap). -oA/-oa: pretty/flat JSON.
                                   "auto" uses '${NODE}-p${port}${YYYYMMDD-HHMM}'. If fname if a dir uses 'dir/${NODE}-p${port}${YYYYMMDD-HHMM}'
     --hints                       additional hints to findings
     --severity <severity>         severities with lower level will be filtered for CSV+JSON, possible values <LOW|MEDIUM|HIGH|CRITICAL>
     --append                      if (non-empty) <logfile>, <csvfile>, <jsonfile> or <htmlfile> exists, append to file. Omits any header
     --outprefix <fname\_prefix>    before  '${NODE}.' above prepend <fname\_prefix>


Options requiring a value can also be called with '=' e.g. testssl.sh -t=smtp --wide --openssl=/usr/bin/openssl <URI>.
<URI> always needs to be the last parameter.


userid@**somehost**:~ % 

  
Details are in the [man page](/doc/testssl.1.html "picture").  
  
You are free to check any port – supposed there's any SSL enabled service (TCP) listening. For the service HTTP you can also supply a full URL. STARTTLS services are those which are plaintext and need some kind of an upgrade command to speak TLS. This is very protocol (see difference between IMAP and SMTP) specific. A STARTTLS check with testssl.sh would be invoked with testssl.sh -t pop3 pop.o2online.de:110. Other examples:

testssl.sh --starttls smtp <smtphost>.<tld>:587 
testssl.sh --starttls ftp <ftphost>.<tld>:21
testssl.sh -t xmpp <jabberhost>.<tld>:5222 
testssl.sh -t xmpp --xmpphost <XMPP domain> <jabberhost>.<tld>:5222 
testssl.sh --starttls imap <imaphost>.<tld>:143

The ports in those examples above are just the standard ports. Also here you're free to check any port. //refactor those, see e.g. https://content-security-policy.com/unsafe-hashes/ or just drop tis shit document.writeln("<img src='/testssl-mx50.png' alt='mail exchanger check with system openssl binary' id='img2' style='float:left' onmouseover='mouseOverImage2()' onmouseout='mouseOutImage2()'>"); function mouseOverImage2() { document.getElementById("img2").src = "/testssl-mx.png"; } function mouseOutImage2() { document.getElementById("img2").src = "/testssl-mx50.png"; }

![mail exchanger check with system openssl binary](/testssl-mx.png)

  
If you just want to check the mail exchangers of a domain, do it like this: testssl.sh --mx google.com (make sure port 25 outbound is not blocked by your firewall) – see left hand side picture.  
  
With the output option \--wide you get where possible a wide output with hexcode of the cipher, OpenSSL cipher suite name, key exchange (with DH size), encryption algorithm, encryption bits size and maybe the RFC cipher suite name.  
  
If you have the file mapping-rfc.txt in the same directory as testssl.sh it [displays](https://twitter.com/drwetter/status/456126567547039744/photo/1 "picture") in the wide outputs also the corresponding RFC style cipher name. If you don't want this, you need to move mapping-rfc.txt away. Another thing: If you want to find out what local ciphers you have and print them pretty, use testssl.sh -V. Ever wondered what hexcode a cipher is? testssl.sh -V x14 lets you search for the hexcode x14. For hexcodes: If you just specify 14 instead of x14 you will get all ciphers returned which have 14 as a low, middle or high byte. For ciphers: You can also supply a word case pattern, e.g. testssl.sh -V CBC puts out every locally available cipher having the Cipher Block Chaining mode in its name.  
  
testssl.sh -x <pattern> <URI> does the same as testssl.sh -V, it only checks the matched pattern at the server, so e.g. testssl.sh -x ECDH google.com checks google.com for ECDH ciphers (and lists also not available ones at the target), testssl.sh -x DHE smtp.posteo.de:465 does a similar thing for the TLS enabled SMTP service.  
  
testssl.sh --file <myfile> let you do mass testing. The [syntax of the file](https://twitter.com/drwetter/status/627619848344989696 "example of 'myfile'") is very easy: one cmdline per line. Use comment signs # as you like, blank lines will be skipped, EOF signals the end of the file – what else? ;-). document.writeln("<img src='/testssl-x33.png' alt='check ECDHE cipher @ gmail's TLS SMTP port' id='img3' style='float:right' onmouseover='mouseOverImage3()' onmouseout='mouseOutImage3()'>"); function mouseOverImage3() { document.getElementById("img3").src = "/testssl-x.png"; } function mouseOutImage3() { document.getElementById("img3").src = "/testssl-x33.png"; }

![mail exchanger check with system openssl binary](/testssl-x.png)

  
  
You can also specify a proxy since version 2.6: testssl.sh --proxy=<proxyhost>:<proxyport> <your\_other\_cmds\_here> will sneak the openssl and bash sockets requests e.g. out of our corporate environment. Proxy authentication is not supported and the port and protocol has to be allowed in the proxy. document.writeln("<img src='/testssl-h1-50.png' alt='header check on https://testssl.sh' id='img4' style='float:right' onmouseover='mouseOverImage4()' onmouseout='mouseOutImage4()'>"); function mouseOverImage4() { document.getElementById("img4").src = "/testssl-h1.png"; } function mouseOutImage4() { document.getElementById("img4").src = "/testssl-h1-50.png"; }

![header check on https://testssl.sh](/testssl-h1.png)

  
  
Another neat feature: testssl.sh --header <URI> gives you some information on the HTTP header and marks security features in green (see upper black picture on the right hand side), not so good headers range from yellow over brown to red. It also allows you to fingerprint proxies, see lower black picture. document.writeln("<img src='/testssl-h2-50.png' alt='header check on https://www.varnish-cache.org' id='img5' style='float:right' onmouseover='mouseOverImage5()' onmouseout='mouseOutImage5()'>"); function mouseOverImage5() { document.getElementById("img5").src = "/testssl-h2.png"; } function mouseOutImage5() { document.getElementById("img5").src = "/testssl-h2-50.png"; }

![header check on https://www.varnish-cache.org](/testssl-h2.png)

  
  
  

### Changes

3.2

  
  
  
       ... branch is a rolling release which is @ [github only](https://github.com/drwetter/testssl.sh). Changes relative to 3.0 see [changelog](https://github.com/drwetter/testssl.sh/blob/3.2/CHANGELOG.md).

3.0

  
  

*   ► Full support of TLS 1.3, shows also drafts supported
*   ► Extended protocol downgrade checks
*   ► ROBOT check
*   ► Better TLS extension support
*   ► Better OpenSSL 1.1.1 and higher versions support as well as LibreSSL >
*   ► More robustness for OpenBSD
*   ► DNS over Proxy and other proxy improvements
*   ► Decoding of unencrypted BIG IP cookies
*   ► Initial client certificate support
*   ► Warning of 825 day limit for certificates issued after 2018/3/1
*   ► Socket timeouts (--connect-timeout)
*   ► IDN/IDN2 servername/URI + emoji support, supposed libidn/idn2 is installed and DNS resolver is recent) support
*   ► Initial support for certificate compression
*   ► Better JSON output: renamed IDs and findings shorter/better parsable, also includes certficate
*   ► JSON output now valid also for non-responding servers
*   ► Testing now per default 370 ciphers
*   ► Further improving the robustness of TLS sockets (sending and parsing)
*   ► Support of supplying timeout value for -- useful for batch/mass scanning
*   ► File input for serial or parallel mass testing can be also in nmap grep(p)able (-oG) format
*   ► LOGJAM: now checking also for DH and FFDHE groups (TLS 1.2)
*   ► PFS: Display of elliptical curves supported, DH and FFDHE groups (TLS 1.2 + TLS 1.3)
*   ► Check for session resumption (Ticket, ID)
*   ► TLS Robustness check GREASE and more
*   ► Server preference distinguishes between TLS 1.3 and lower protocols
*   ► Mark TLS 1.0 and TLS 1.1 as deprecated
*   ► Does a few startup checks which make later tests easier and faster (determine\_optimal\_\\\*())
*   ► Expect-CT Header Detection
*   ► \--phone-outdoes certificate revocation checks via OCSP (LDAP+HTTP) and with CRL
*   ► \--phone-outchecks whether the private key has been compromised via https://pwnedkeys.com/
*   ► Missing SAN warning
*   ► Added support for private CAs
*   ► Way better handling of connectivity problems (counting those, if threshold exceeded -> bye)
*   ► Fixed TCP fragmentation
*   ► Added \--ids-friendly switch
*   ► Exit codes better: 0 for running without error, 1+n for small errors, >240 for major errors.
*   ► Better error msg suppression (not fully installed OpenSSL)
*   ► Better parsing of HTTP headers & better output of longer HTTP headers
*   ► Display more HTTP security headers
*   ► HTTP Basic Auth support for HTTP header
*   ► experimental eTLS detection
*   ► Dockerfile and repo @ docker hub with that file (see above)
*   ► Java Root CA store added
*   ► Better support for XMPP via STARTTLS & faster
*   ► Certificate check for to-name in stream of XMPP
*   ► Support for NNTP and LMTP via STARTTLS, fixes for MySQL and PostgresQL
*   ► Support for SNI and STARTTLS
*   ► More robustness for any STARTTLS protocol (fall back to plaintext while in TLS caused problems)
*   ► Renegotiation checks improved, also no false potive for Node.js anymore
*   ► Major update of client simulations with self-collected up-to-date data
*   ► Update of CA certificate stores
*   ► Lots of bug fixes
*   ► More travis/CI checks -- still place for improvements
*   ► Man page reviewed

[2.9.5 Features (Sep 2017)](#2.9.5)*   ► Way better coverage of ciphers as most checks are done via sockets, using bash sockets where ever possible
*   ► Further tests via TLS sockets and improvements (handshake parsing, completeness, robustness)
*   ► Testing 359 default ciphers (testssl.sh -e/-E) with a mixture of sockets and openssl.
*   ► Same speed as with openssl only but additional ciphers such as post-quantum ciphers, new CHAHA20/POLY1305, CamelliaGCM etc.
*   ► TLS 1.2 protocol check via sockets in production
*   ► Finding more TLS extensions via sockets
*   ► TLS Supported Groups Registry (RFC 7919), key shares extension
*   ► Non-flat JSON output support
*   ► File output (CSV, JSON flat, JSON non-flat) supports a minimum severity level (only above supplied level there will be output)
*   ► Native HTML support instead going through 'aha'
*   ► LUCKY13 and SWEET32 checks
*   ► Ticketbleed check
*   ► LOGJAM: now checking also for known DH parameters
*   ► Support of supplying timeout value for openssl connect -- useful for batch/mass scanning
*   ► Parallel mass testing
*   ► Check for CAA RR
*   ► Check for OCSP must staple
*   ► Check for Certificate Transparency
*   ► Check for session resumption (Ticket, ID)
*   ► Better formatting of output (indentation)
*   ► Choice showing the RFC naming scheme only
*   ► File input for mass testing can be also in nmap grep(p)able (-oG) format
*   ► Postgres und MySQL STARTTLS support
*   ► Man page in different formats (roff, HTML, markdown)

  
  
  

[2.8 Features (May 2017)](#2.8)*   ► Trust chain check against certificate stores from Apple (OS), Linux (OS), Microsoft (OS), Mozilla (Firefox Browser)
*   ► Works now on servers requiring a x509 certificate for authentication
*   ► Extensive CN+SAN <--> hostname check
*   ► SSL Session ID check
*   ► Avahi/mDNS based name resolution
*   ► HTTP2/ALPN protocol check
*   ► IPv6 support via \-6 argument (except IPv6 proxy)
*   ► Logging to a file / dir
*   ► Logging to (flat) JSON + CSV
*   ► HPKP checks now also for Root and intermediate SPKIs
*   ► Check for multiple server certificates
*   ► Browser cipher simulation: what client will connect with which cipher + protocol
*   ► GOST cipher+certificate improvements
*   ► Assistance for color-blind users
*   ► Even more compatibility improvements for FreeBSD, NetBSD, Gentoo, RH-ish, F5 and Cisco systems
*   ► Considerable speed improvements for each cipher runs (\-e/-E)
*   ► More robust SSLv2 + TLS socket interface
*   ► separate check for curves
*   ► OpenSSL 1.1.0 compliant
*   ► Check for DROWN
*   ► Whole number of bugs squashed

  
  
  

[2.6 Features (Sep 2015)](#2.6)*   ► LOGJAM: check of DHE\_EXPORT ciphers, displays DH(/ECDH) bits in wide mode on negotiated ciphers
*   ► (HTTP) proxy support! Via sockets and openssl -- Thx @jnewbigin
*   ► TLS\_FALLBACK\_SCSV check – Thx @JonnyHightower
*   ► TLS 1.0-1.1 as socket checks per default in production
*   ► TLS time and HTTP time stamps for architecture fiingerprinting
*   ► support of sockets also for STARTTLS protocol checks
*   ► TLS time displayed also for STARTTLS
*   ► binary directory provides out of the box better suited binaries (with up to 195 ciphers), besides Linux static binaries
*       (OS X binaries (new builds from @jpluimers), FreeBSD binary, ARM binary (@f-s)
*   ► Extended validation certificate detection
*   ► "wide mode" option for checks like RC4, BEAST. PFS: Displays hexcode, kx, strength, DH bits, RFC cipher name
*   ► will test multiple IP adresses in one shot, \--ip= restricts it accordingly
*   ► runs in default mode through all ciphers at the end of a default run
*   ► new mass testing file option \--file option where `testssl.sh` commands are being read from, see [here](https://twitter.com/drwetter/status/627619848344989696)
*   ► displays matching host key (HPKP)
*   ► further detection of security relevant headers (reverse proxy, IPv4 addresses) as well as proprietary banners (OWA, Liferay etc.)
*   ► can scan STARTTLS+XMPP by also supplying the XMPP domain (to-option in XML streams).
*   ► quite some fixes when using LibreSSL, still not recommended to use though (see above)
*   ► lots of fixes, code improvements, even more robust

  
  
  

[2.4 Features (May, 2015)](#2.4)*   ► "only one cmd line option at a time" is completely gone
*   ► several tuning parameters on the cmd line (only available through environment variables b4): \--assuming-http,
*   \--ssl-native, \--sneaky, \--warnings, \--color, \-- debug, \--long
*   ► certificate information
*   ► more HTTP header infos (cookies+security headers)
*   ► protocol check via bash sockets for SSLv2+v3
*   ► debug handling significantly improved (verbosity/each function leaves files in $TEMPDIR)
*   ► BEAST check
*   ► FREAK check
*   ► HeartBleed check
*   ► check for Secure Client-Initiated Renegotiation
*   ► lots of cosmetic and maintainability code cleanups
*   ► bugfixing

  
  
  

[2.2 Features (Dec 2014)](#2.2)*   ► works fully under BSD (openssl >=1.0)
*   ► cipher check (-x) with pattern of hexcode/cipher
*   ► check for POODLE SSL
*   ► HPKP check
*   ► OCSP stapling
*   ► GOST and CHACHA20/POLY1305 cipher support
*   ► service detection (HTTP, IMAP, POP, SMTP)
*   ► runs now with all colors, b/w screen, no escape codes at all
*   ► protocol check better
*   ► job control removes stalling
*   ► RFC ↔ OpenSSL name space mapping of ciphers everywhere

  
  
  

[2.0 Features (June 2014)](#2.0)*   ► SNI
*   ► STARTTLS
*   ► server preferences for protocols and ciphers
*   ► checks for: RC4, PFS, SPDY
*   ► web and app server banner, HSTS
*   ► server key size
*   ► TLS session tickets
*   ► TLS server extensions
*   ► heartbleed check from [bash-heartbleed.sh](https://testssl.sh/bash-heartbleed.sh) with shell only SSL handshake!
*   ► CCS check from [ccs-injection.sh](https://testssl.sh/ccs-injection.sh) with shell only SSL handshake!
*   ► somewhat smart check for BREACH vulnerability
*   ► check for CRIME
*   ► tests now for renegotiation vulnerabity
*   ► prelease of cipher suites name space mapping OpenSSL ↔ RFC
*   ► aaand: neat output
*   ► supplying URL, hostname, port with hostname is fine
*   ► sanity check for servce and SSL enabled service is listening at all
*   ► major code cleanups
*   \[..\]
*   More see [CHANGELOG](CHANGELOG.txt).

  
  
  
  

### Misc

Feedback, bugs and contributions are welcome! Currently there's one git repo at [https://github.com/drwetter/testssl.sh](https://github.com/drwetter/testssl.sh). Here @ [https://testssl.sh](https://testssl.sh) you will always find the latest stable version. At [github](https://github.com/drwetter/testssl.sh) in the 2.9dev branch is the latest'n'greatest development version.  
  
Bugs (and fixes) as well as other PRs can by filed at the git repo or send me a mail to _dirk aet testssl dot sh_.  
  
I post all significant updates on [Mastodon](https://infosec.exchange/@testssl). Twitter ([drwetter](http://twitter.com/drwetter "@drwetter")) is deprecated.    
  

- - -

Services:  If you need a scanning service or consulting [get in touch with me.](https://drwetter.eu/kontakt "contact form with OpenPGP encryption on my business web site (sorry, German. Fields should be self-explanatory)")

  

- - -

[Imprint](http://drwetter.eu/impressum)
