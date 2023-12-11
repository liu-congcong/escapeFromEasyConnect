# escapeFromEasyConnect

Escape from EasyConnect (解除EasyConnect劫持的额外地址).

开启EasyConnect会将大量目标IP转发到其指定的接口，可能造成卡顿。

如果在使用EasyConnect连接内部服务器时看视频卡顿、玩游戏卡顿，使用这个程序就对了！

escapeFromEasyConnect会重新释放被EasyConnect过度转发的目标IP。

escapeFromEasyConnect的运行需要管理员权限。

## Usage

```shell
escapeFromEasyConnect.exe IP ... IP

Escape from EasyConnect. (https://github.com/liu-congcong/escapeFromEasyConnect)
Usage:
    C:\Users\liucongcong\OneDrive\Documents\c\escapeFromEasyConnect.exe ip ... ip
Options:
    ip: <xxx.xxx.xxx.xxx> IP to be forwarded (这个IP是希望被EasyConnect转发的IP,通常是服务器IP等).
```
