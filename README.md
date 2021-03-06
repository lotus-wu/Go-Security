# My Go Security Projects

<!-- MarkdownTOC -->

- [SSH Harvester](#ssh-harvester)
- [pcap Tutorial](#pcap-tutorial)
- [Go-Fuzz Adventures](#go-fuzz-adventures)
    - [iprange](#iprange)
    - [goexif2](#goexif2)
- [CLI Package Tests](#cli-package-tests)
    - [urfave/cli](#urfavecli)
    - [spf13/cobra](#spf13cobra)
- [Base64 Stream Decoder](#base64-stream-decoder)
- [PNG Tests](#png-tests)

<!-- /MarkdownTOC -->

<a id="ssh-harvester"></a>
## [SSH Harvester](ssh-harvester)
Initial version of tool written in Go that harvests SSH certificates. For explanation of code please see the blog post [Simple SSH Harvester in Go][go-sshharvester].

<a id="pcap-tutorial"></a>
## [pcap Tutorial](pcap-tutorial)
Code for the blog post [Go and pcaps][go-pcap] which explains how to use Go to extract ICMP echo payloads from a pcap file.

<a id="go-fuzz-adventures"></a>
## [Go-Fuzz Adventures](go-fuzz)
Learning how to use [Go-Fuzz][go-fuzz-github].

<a id="iprange"></a>
### [iprange](go-fuzz/iprange)
Test code for fuzzing the [iprange][iprange-github] package. See blog post [Learning Go-Fuzz 1: iprange][iprange-blog].

<a id="goexif2"></a>
### [goexif2](go-fuzz/goexif2)
Code and accompanying material for blog post [Learning Go-Fuzz 2: goexif2][goexif2-blog] discussing fuzzing the [goexif2][goexif2-github] package.

<a id="cli-package-tests"></a>
## [CLI Package Tests](cli-package-tests)
Sample programs and notes while learning urfave-cli and Cobra packages for creating CLI applications.

<a id="urfavecli"></a>
### [urfave/cli](cli-package-tests/urfave-cli)

<a id="spf13cobra"></a>
### [spf13/cobra](cli-package-tests/spf13-cobra)

<a id="base64-stream-decoder"></a>
## [Base64 Stream Decoder](base64-stream-decoder/b64-stream-decoder.go)
Code for blog post [Decoding Large Base64 Files with Go][go-base64-decoder] showing how to use base64 stream decoder on large files.

<a id="png-tests"></a>
## [PNG Tests](png-tests)
Reading and writing PNG files. Includes some test scripts and code for blog post [Extracting PNG Chunks with Go][go-png-chunk].

<!-- Links -->

[go-pcap]: https://parsiya.net/blog/2017-12-03-go-and-pcaps/
[go-sshharvester]: https://parsiya.net/blog/2017-12-28-simple-ssh-harvester-in-go/
[go-base64-decoder]: https://parsiya.net/blog/2018-01-19-decoding-large-base64-files-with-go/
[go-png-chunk]: https://parsiya.net/blog/2018-02-25-extracting-png-chunks-with-go/
[go-fuzz-github]: https://github.com/dvyukov/go-fuzz
[iprange-github]: https://github.com/malfunkt/iprange
[iprange-blog]: https://parsiya.net/blog/2018-04-29-learning-go-fuzz-1-iprange/
[goexif2-github]: https://github.com/xor-gate/goexif2
[goexif2-blog]: https://parsiya.net/blog/2018-05-05-learning-go-fuzz-2-goexif2/
