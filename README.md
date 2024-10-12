# Vagrant-стенд c VLAN и LACP
## Что нужно сделать? 
###  В Office1 в тестовой подсети появляется сервера с доп интерфейсами и адресами в internal сети testLAN:
   - testClient1 - 10.10.10.254
   - testClient2 - 10.10.10.254
   - testServer1- 10.10.10.1
   - testServer2- 10.10.10.1
###  Равести вланами:
   - testClient1 <-> testServer1
   - testClient2 <-> testServer2
### Между centralRouter и inetRouter "пробросить" 2 линка (общая inernal сеть) и объединить их в бонд, проверить работу c отключением интерфейсов
## Схема сети
![изображение](https://github.com/user-attachments/assets/0a32ff0e-a49e-4e27-9786-ac80e4522a11)
