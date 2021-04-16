クローン直後
```
./setup.sh
./set-disk.sh
```

シェル立ち上げごと
```
cd $HOME/osbook/devenv;source buildenv.sh;cd -
cd $HOME/edk2;source edksetup.sh ;cd -
```

実行
```
./link.sh
./qemu.sh
```
Host
```
xhost +
```