# Setup ubuntu 20.04 headless cudo-miner

## HOW TO USE

Clone the repo, cd into the dir, run the makefile

```
$ git clone https://github.com/Afrikantahti/cudo-miner-ubuntu.git
$ cd ./cudo-miner-ubuntu
$ make setup_machine
```

note: a reboot / relog might be required for the gnome-extensions to load

### Single role

To run i.e. only apt in- or uninstall use tags for the specific roles

```
# run a single role, i.e. apt-packages, inside the setup-pop_os dir:
$ make run_role tag=radeon
```

### TODO

[ ] amd GRUB_CMDLINE_LINUX_DEFAULT
[ ] nvidia cuda
[ ] ssh server
[ ] zerotier

Modified from https://github.com/kevinjelnl/setup-pop_os.git
