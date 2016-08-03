### Download and install Packer

[https://www.packer.io/downloads.html](https://www.packer.io/downloads.html)

[https://www.packer.io/intro/getting-started/setup.html](https://www.packer.io/intro/getting-started/setup.html)

### Clone the Chef Bento project
`git clone https://github.com/chef/bento.git`

`cd bento`

### Build a CentOS 7.2 Virtualbox Box
`packer build -only=virtualbox-iso centos-7.2-x86_64.json`
