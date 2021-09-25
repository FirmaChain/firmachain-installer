
# `FirmaChain Installer`

Quickly install pre-compiled binaries from Github releases.

Installer is an HTTP server which returns shell scripts. The returned script will detect platform OS and architecture, choose from a selection of URLs, download the appropriate file, un(zip|tar|gzip) the file, find the binary (largest file) and optionally move it into your `PATH`. Useful for installing your favourite pre-compiled programs on hosts using only `curl`.

## Usage

* Get latest release 
```sh
curl https://build.firmachain.org | bash
```

* Get specific `release tag`.

```sh
curl https://build.firmachain.org/@v0.2.4 | bash
```

* or you can use `wget`.

```sh
wget -qO- build.firmachain.org | bash
```





## Examples


    
    $ curl https://build.firmachain.org | bash
    
    	% Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
	100  3590    0  3590    0     0  57903      0 --:--:-- --:--:-- --:--:-- 57903
	Downloading FirmaChain/firmachain v0.2.4.....
	######################################################################## 100.0%
	Downloaded to /Users/donghoon/Desktop/test1/firmachain

    $ ./firmachain version
	0.2.3-603f495a
	

    

