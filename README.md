# My version for the unattend file of [Chris Titus Tech's Bypass NRO on STEROIDS!?!?!](https://github.com/ChrisTitusTech/bypassnro)

What i changed:
1. Teams, Outlook and another 1 or 2 apps are still installed
2. In the oobe you are prompted to create an local user account

From the OOBE Screen press Shift + F10

```
curl -L https://bltz.ro/bypass.cmd -o skip.cmd
skip.cmd
```

This will skip the entire OOBE process including microsoft account and ANY questions during the setup process. It still allows you to select your language, region, and keyboard layout.


