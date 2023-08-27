> [!WARNING]  
> This isn't the official Vencord, but just an updated Vencord guide on how you can update the code.
> There will be no updates or support for this so if you want that download from [the official github](https://github.com/Vendicated/VencordInstaller#usage) instead.    

## Dependencies

-   Install Git from here: https://git-scm.com/download
-   Install pnpm from here: https://pnpm.io/installation
-   Install Node.JS LTS from here: https://nodejs.dev/

## Have fun with source code!
You can now add your own badges, add your own plugins, add your own tabs and anything you want, but for some you need to understand TypeScript and JavaScript programming languages.
However to add your own badges you can go to `src/plugins/_api/badges.tsx` and on line 57 you will see a raw github content file, simply change the raw and make your own raw in github and just copy that raw link and replace.

## Installing Vencord

Follow the commands from here on, everything must be executed from Git bash.

Clone the git rep:

```shell
git clone https://github.com/queenophrenia/i-love-myself-and-everything-around-me/
cd i-love-myself-and-everything-around-me
```

Install the dependencies: (This will install any needed modules for the build to work and it is necessary!)

```shell
pnpm install --frozen-lockfile
```

Build Vencord: (Builds files)

```shell
pnpm build
```

Download installer and inject (Downloads the installer from offical Vencord and allows you to install your own code)

```shell
pnpm inject
```

## Uninstalling Vencord

Simply run this command in Git Bash:

```shell
pnpm uninject
```

> [!WARNING]  
> DO NOT claim this as your own client as everything is on you, the entire source code is already on there this is just in bigger explanation on how to add or edit more features if you're new to everything.
> Feel free to edit whatever you want as it will not affect the original client and simply have fun with it, besides it's never too learn to read the code and understand it, right?
