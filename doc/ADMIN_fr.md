* Le mode multijoueur nécessite les clés API Liveblocks (Public et Secret)
     * Vous pouvez en obtenir gratuitement sur liveblocks.io
     * Soyez **très prudent** cependant et gardez à l'esprit qu'en procédant ainsi, toutes les données de vos salles multijoueurs seront stockées sur les serveurs SaaS de animals.io, et **PAS** sur votre serveur.
     * Le mode multijoueur est totalement facultatif et vous n'êtes pas obligé de l'utiliser
     * Si les clés API ne sont pas fournies, elles seront automatiquement désactivées

* TLDraw offre toutes les fonctionnalités (y compris le multijoueur) gratuitement sur tldraw.com
     * Cependant, ils ont restreint l'utilisation du mode multijoueur au sein d'un iFrame, ce qui pourrait poser problème
     * L'application TLDraw YunoHost corrige cette restriction afin que vous puissiez utiliser le mode multijoueur dans un iFrame comme avant.

* Il pourrait être possible d'auto-héberger une couche multijoueur à l'avenir. Certains projets ont été lancés, basés sur la bibliothèque YJS, comme https://github.com/nimeshnayaju/yjs-tldraw, mais malheureusement aucun d'entre eux n'est suffisamment mature pour être inclus ici.
     * Évidemment, dès que le multijoueur pourra être activé sans passer par les serveurs SaaS Liveblocks, l'application sera mise à jour en conséquence