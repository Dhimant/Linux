Linux
============

Sometimes when using dual boot, if there is issue shutting down windown properly, windows drives are not accessible in linux. Use following commands to fix it

```
sudo ntfsfix /dev/sda3
sudo ntfsfix /dev/sda2
```
