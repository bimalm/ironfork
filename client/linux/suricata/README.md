#Suricata Linux Installation steps

#Manual installation by Source Code compile

Requirements:
* Suricata Latest stable version: (5.0.1) 
* Linux Compile Environment 

Below example is tested at ubuntu 18.044

##Download Software

$wget https://www.openinfosecfoundation.org/download/suricata-5.0.1.tar.gz

## Prerequisites

apt-get install libyaml-dev libjansson-dev libpcap-dev rustc cargo libz-dev python python-yaml clang gcc pkg-config libpcre3-dev

$ tar -zxf suricata-5.0.1.tar.gz

$ cd suricata-5.0.1

$ ./configure --prefix=/usr/local/suricata

$ make & make install-full

