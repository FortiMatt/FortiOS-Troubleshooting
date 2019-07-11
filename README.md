# FortiOS Troubleshooting

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

## Navigation/Structure:

This repo is laid out via specific FortiOS troubleshooting topics. Within each topic/section, there is info, debug and in some cases TAC commands.

- info = What does FortiOS think about the topic and/or how is FortiOS configured
- debug = View real-time debug within FortiOS on a specific topic
- TAC = A summary of info/debug commands helpful for when creating a support ticket

Each file also contains a "Help Alias" to support/guide you as an engineer as to what each line/command does.

## Notice

Please note that this repo is not publically endorsed/supported by Fortinet. I am just a sales engineer trying to make my life easier.
