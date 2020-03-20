# etc-hosts-manager

etc-hosts-manager is a shell script that offer a simple way to add/remove entries in your /etc/hosts file.
It's based on [justqyx/manage-etc-hosts.sh](https://gist.github.com/justqyx/38a54135fdcccd11a0e9b75ba7417df8).

## Installation
```bash
$ git clone https://github.com/benjamin-feron/etc-hosts-manager.git
$ cd etc-hosts-manager
$ ln -s $PWD/etc-hosts-manager.sh /usr/bin/etc-hosts-manager
````

## Usage

Add entry :

```bash
$ sudo etc-hosts-manager add "host_name ip_address"
````

Remove entry :

```bash
$ sudo etc-hosts-manager remove "host_name ip_address"
````

