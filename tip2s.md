# Tips

## Reinstall Grub

Boot from USB or CD/DVD
`Try Ubuntu without installing`
```sh
sudo add-apt-repository ppa:yannubuntu/boot-repair
sudo apt-get update
sudo apt-get -y install boot-repair && boot-repair
```

`Recommended repair`


## `apt-get update` fails

```sh
sudo rm /var/lib/apt/lists/* -vf
sudo apt-get update
sudo apt-get upgrade
```
