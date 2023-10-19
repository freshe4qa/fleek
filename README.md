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

Добавьте Fleek Network в качестве пользовательской сети в Metamask.
Имя сети: Fleek Network
RPC URL: https://rpc.testnet.fleek.network/rpc/v0
ID сети: 59330
Символ валюты: tFLK 

Перейдите на страницу https://faucet.testnet.fleek.network/ и нажмите кнопку Connect wallet.
Убедитесь, что в качестве выбранной сети выбрана сеть Fleek Network.

Минтим токены. Эту транзакцию не нужно будет подписывать в кошельке.
Подождите, пока баланс счета в кошельке увеличится.

Нажмите кнопку Stake Testnet FLK, появится окно, скопируйте и вставьте в форму ключи. Введите свой IP в поле домена и нажмите кнопку stake.

Посмотреть ключи:
```
lgtn keys show
```

Подтвердите транзакцию в Metamask.

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

