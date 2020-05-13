## How to use it

### 1.Set up [qmk_firmware](https://github.com/qmk/qmk_firmware)

```
git clone https://github.com/qmk/qmk_firmware.git
```

### Make a directory and copy files in IrisKeymap

```
mkdir qmkdir qmk_firmware/keyboards/keebio/iris/${YOUR_DIRIRECTORY_NAME} | cp IrisKeymap/* qmk_firmware/keyboards/keebio/iris/${YOUR_DIRIRECTORY_NAME}
```

### 2.Build keymap

```
make keebio/iris/rev2:${YOUR_DIRIRECTORY_NAME}
```

### 3.Flash keymap to your keyboard

```
make keebio/iris/rev2:${YOUR_DIRIRECTORY_NAME}:flash
```
