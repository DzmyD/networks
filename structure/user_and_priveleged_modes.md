# Пользовательские режимы в маршрутизаторах и коммутаторах Cisco

Данный режим служит для разграничения прав пользователей. 

## User execute mode

Обычный пользовательский режим, его признаком является символ `>`.

```cisco
Router>
```

## Priveleged execute mode

Расширенный режим, предоставляющий большие возможности для взаимодействия с **Cisco IOS**. Признаком этого режима является символ `#`.

```cisco
Router#
```

Для перехода в привелегированный режим нужно выполнить команду `enable` либо ее скоращенную версию `en`.

```cisco 
Router>enable
Router#
```

Для выхода из него в **User execute mode** используется команда `disable`.

```cisco
Router#disable
Router>
```
