## Fixes:
- Keychron keyboard fn keys fix (linux)
```console
echo "options hid_apple fnmode=0" | sudo tee -a /etc/modprobe.d/hid_apple.conf
```