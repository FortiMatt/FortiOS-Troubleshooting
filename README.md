# Troubleshooting

Ever get tired of running the same old debug/troubleshooting commands? **Me too!**

Well, I decided to create **alias** commands for standard FortiOS configuration and debug information. 

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

## Current Alias'

- High Availablity
  - Debug
  - Info
- OSPF
  - Debug
  - Info
- Web Filtering
  - Debug
  - Info
- GUI
  - Debug
   
## Delete Alias'

In the event, you would like to delete the alias' off of your FortiOS device I have included a Delete Alias command/page as well.

- Delete Debug Alias -- Notes
- Delete Debug Alias
- Delete Info Alias -- Notes
- Delete Info Alias

**Please note that this repo is not publically endorsed/supported by Fortinet. I am just a sales engineer trying to make my life easier.**
