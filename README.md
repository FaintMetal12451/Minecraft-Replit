## Minecraft on Replit [![Run on Repl.it](https://repl.it/badge/github/SrEvelio/Minecraft-Replit)](https://repl.it/github/SrEvelio/Minecraft-Replit)

As the title says, Run a minercraft server on Replit.com in a few minutes.


### How to enter the server

To be able to enter the server you will need a Ngrok key (It is totally free and you can obtain one at its [official site](https://ngrok.com/)).

Once you have your key simply put it in the Secrets section, after that simply choose the software and version of your choice in config.json. The server's ip and port will be displayed in the console as soon as you press start.

### Softwares
In this new version, I thought, why not put more server types and versions, so now you can choose between Purpur (1.20.1 - 1.14.1), Paper (1.20.1 - 1.8.8) and Vanilla (1.20.1 - 1.7.10).

Now you are wondering how to select the type and version, well it is simple, basically edit the config.json file and in each value simply put the one of your preference, by default it will come with Vanilla 1.8.9 (I think it is the version that works best).

```js
{
    "software": "vanilla", // Purpur, paper, vanilla
    "version": "1.8.9",
    "ngrokregion": "us" // us, eu, au, ap, sa, jp, in
}
```

### Notes
To try to optimize the project more we started to use replit's own java but this led to the fact that versions higher than 1.16.5 cannot be started, so to be able to start higher versions you must use a different java, so to start them simply edit the .replit file to start the start17.sh file instead of start.sh.

By the way, because replit is not designed to run minecraft servers (although it is possible) these may have a questionable performance so it will not always keep 20 Ticks per second or even reach it, so this is more for curiosity and to know the limits of replit.

### ScreenShots

![Minecraft on Replit #1](https://github.com/SrEvelio/Minecraft-Replit/blob/main/screenshots/2023-08-28_16.01.46.png)

![Minecraft on Replit #2](https://github.com/SrEvelio/Minecraft-Replit/blob/main/screenshots/2023-08-28_16.11.45.png)