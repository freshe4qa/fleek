<p align="center">
  <img height="100" height="auto" src="https://github.com/freshe4qa/fleek/assets/85982863/a82eed93-62fd-47d3-83ce-e7b442798e43">
</p>

# Fleek Testnet

Official documentation:
>- [Validator setup instructions](https://docs.fleek.network/docs/node/Install/)

Explorer:
>- -

### Minimum Hardware Requirements
 - 4+ CPUs;
 - 16GB+ RAM
 - 100GB+ (SSD or NVME)
 - Ubuntu 22.04

## Установка
```
adduser <USERNAME>    
```
## Example:
```
adduser fleek    
```
##
```
usermod -aG sudo <USERNAME>
```

```
su <USERNAME>
```

```
curl https://get.fleek.network | bash
```

```
systemctl start lightning.service
```

Чтобы попасть в тестнет нужно заполнить форму в [Dicord-сервере](https://discord.gg/mhjuTW3w) в ветке [#access-form](https://discord.com/channels/965698989464887386/1148299261713338381) 

Посмотреть ключи:
```
lgtn keys show
```

Статус:
```
systemctl status lightning
```

Логи ноды:
```
tail -f /var/log/lightning/output.log
```

Логи диагностики:
```
tail -f /var/log/lightning/diagnostic.log
```

