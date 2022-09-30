* TLDraw can't be installed on a subpath, and needs a fully dedicated domain

* The multiplayer mode requires Liveblocks API keys (Public and Secret)
    * You can get some for free at liveblocks.io
    * Be **very careful** though, and keep in mind that by doing so, all your multiplayer rooms data will be stored on livestocks.io SaaS servers, and **NOT** on your server
    * Multiplayer mode is completely optional and you don't have to use it
    * If API keys are not provided, it will be automatically deactivated

* TLDraw will not take a lot of disk or memory space while running.
    * **However**, you will need at least 2.5GB of RAM and 5GB of disk space during installation time
    * The build can be quite long, be patient!

* TLDraw offers all functionnalities (including multiplayer) for free at tldraw.com
    * However, they have restricted the use of multiplayer mode within an iFrame, which could be a problem
    * TLDraw YunoHost app is patching that restriction so that you can use multiplayer mode within an iFrame as before

* It could be possible to self-host a multiplayer layer in the future. Some projects have been launched, based on YJS library, such as https://github.com/nimeshnayaju/yjs-tldraw, but sadly none of them is mature enough to be included here.
    * Obviously, as soon as multiplayer could be enabled without going through Liveblocks SaaS servers, the app will be updated accordingly