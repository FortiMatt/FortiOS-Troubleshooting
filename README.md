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

One of the key things to point out when creating an alias is the command character limit of 255. To get around this limitation, you can "nest" alias inside each other. Thus allowing you to create endless possibilities/command strings.

For more information on the alias command [CLICK HERE](https://docs.fortinet.com/document/fortigate/6.0.5/cli-reference/991461/system-alias)

## How to Import Alias'

There are two options for uploading the alias scripts into **FortiOS**.

1. Via CLI
   - Copy/Paste
2. Via Configuration Scripts Upload
   - System> Advanced > Configuration Scripts

## How to Use after Import

Once the commands have been entered into FortiOS type "alias ?". A list of the available troubleshooting commands will be available for you to choose from. Additionally, you have the option to TAB through the options for ease of use.

## Navigation/Structure:

This repo is laid out via specific FortiOS troubleshooting topics. Within each topic/section, there is info, debug and in some cases TAC commands.

- **info** = What does FortiOS think about the topic and/or how is FortiOS configured
- **debug** = View real-time debug within FortiOS on a specific topic
- **TAC** = A summary of info/debug commands helpful for when creating a support ticket

Each file also contains **"Help Alias'"** to support/guide you as an engineer as to what each line/command does.

## Notice

Please note that this repo is not publically endorsed/supported by Fortinet. I am just a sales engineer trying to make my life easier.
