# karabiner_custom

The custom setting files for Karabiner for Mac.

## Uasage

1.backup old karabiner custom file if it is necessary

```bash
cp ~/Library/Application\ Support/Karabiner/private.xml ~/Library/Application\ Support/Karabiner/private.xml_bac
```

2.just get the file

```bash
curl https://raw.githubusercontent.com/quentin-chen/karabiner_custom/master/private.xml > ~/Library/Application\ Support/Karabiner/private.xml
```

3.Done, reloaded xml in Karabiner

## Instruction 

This setting file includes:

- change `caps lock` to right `control`
- when click `caps lock` only, send `ESC` for vim user :)
- double click left `control` for `CAPSLOCK`
- change right `option` to `F12` for iterm2 system wide hotkey 