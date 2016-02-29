## Troubleshouting

## Проблема

После обновления ОС (`sudo yum update -y`), ломаются Virtual Box Guest Additions

### Как починить Guest Additions

* `cd /opt/VBoxGuestAdditions-*/init`

* `sudo yum install -y gcc kernel-devel`

* `sudo ./vboxadd setup`
