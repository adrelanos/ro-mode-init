# Detects read-only disks and automatically enables live-boot #

Allows booting the system in live mode. Meaning, no persistent modifications
will be written to the disk. All changes stay in RAM.

No claims are made with regard to anti forensics.
## How to install `ro-mode-init` using apt-get ##

1\. Add [Whonix's Signing Key](https://www.whonix.org/wiki/Whonix_Signing_Key).

```
sudo apt-key --keyring /etc/apt/trusted.gpg.d/whonix.gpg adv --keyserver hkp://ipv4.pool.sks-keyservers.net:80 --recv-keys 916B8D99C38EAF5E8ADC7A2A8D66066A2EEACCDA
```

3\. Add Whonix's APT repository.

```
echo "deb http://deb.whonix.org buster main" | sudo tee /etc/apt/sources.list.d/whonix.list
```

4\. Update your package lists.

```
sudo apt-get update
```

5\. Install `ro-mode-init`.

```
sudo apt-get install ro-mode-init
```

## How to Build deb Package ##

Replace `apparmor-profile-torbrowser` with the actual name of this package with `ro-mode-init` and see [instructions](https://www.whonix.org/wiki/Dev/Build_Documentation/apparmor-profile-torbrowser).

## Contact ##

* [Free Forum Support](https://forums.whonix.org)
* [Professional Support](https://www.whonix.org/wiki/Professional_Support)

## Payments ##

`ro-mode-init` requires [payments](https://www.whonix.org/wiki/Payments) to stay alive!
