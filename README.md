# Troubleshooting

Ever get tired of running the same old debug/troubleshooting commands?

Me too!

Well, I decided to create alias commands for standard FortiOS configuration and debug information. Please note that this repo is not publically endorsed/supported by Fortinet. I am just a sales engineer trying to make my life easier.

## FortiOS Alias Command:
```
config system alias
  edit {name}
    set name {string}   Alias command name. size[35]
    set command {string}   Command list to execute. size[255]
  next
end
```
For more information on the alias command [CLICK HERE](https://docs.fortinet.com/document/fortigate/6.0.5/cli-reference/991461/system-alias)
