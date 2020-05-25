# i3tools
Useful tools for i3

## i3weather
### Requirements:
`curl` and `jq`
```
apt-get install curl jq
```
### Use:
In `i3blocks` config file add a block for weather:

```
[weather]
command=i3tools/weather paris london
interval=1
color=#A4C2F4
```

## i3windows
### Requirements:
### Use:
In `i3` config file append a new bar:
```
bar {
    font pango:Ubuntu Mono, FontAwesome 10
    status_command i3tools/windows
    tray_output none
    workspace_buttons no
    height 22
}
```
