---
layout: ../../layouts/BlogLayout.astro
title: The Quest for the perfect editor
date: November 30, 2023
intro: "From basic beginnings to powerful tools: My journey through text editors."
image: "nvim.png"
---

## Whoami

Hi, I'm Allan, I'm 20 and I'm studying computer science at Louvain-La-Leuve University in Belgium. I'm currently in my second year of bachelor. I'm coding since the age of 8, and I tried a lot of languages, tools and text editors.

I’m very curious, I love installing and trying out new things to make up my own mind.

## My first experience with a text editor

The first program I've ever wrote was a present for my mom, I made a simple Windows application that displayed message boxes with text. I've followed the instructions found in a book (that I still have today), and I've used the good old Visual Studio (which is an IDE, I know but let's pretend these are all text editors). I honestly don't remember much of this experience.

## The journey continues

Fast-forward a few years, I used a bit Notepad to write Windows scripts, Brackets for HTML/CSS, the Unity editor for games dev and also the default text editor shipped with python on Windows. Then a few years later I've found Atom (rip) and finally, I discovered VSCode.

VSCode was awesome, it was beautiful, it had a lot of extensions, it was "customisable", it was everything I wanted. I've used it for a long time, I've used it for my school projects and for my personal projects. I've also used it for a lot of languages and frameworks. I was in love with it, i recommended it to everyone, even my old teachers that didn't understand that I wasn't speaking about Visual Studio...

![My teachers trying to understand the difference between VS and VSCode](/articles/vscode.png)
My teachers trying to understand the difference between VS and VSCode

## Meeting with vim

I've once bought a VPS to host one of the discord bots I made on my beloved VSCode, I was following a youtube tutorial on how to deploy my bot on this server and as a perfect script kiddie, I copied everything he was doing. He proceeded to open a config file using vim and I tried to do the same things... It was horrible and I had to close my terminal to exit vim (very unique story I know). Then, I returned to the classic nano editor and stuck to it for config files edition.

## VSCode love falling

As I love trying a lot of technologies, languages and frameworks, I had a LOT of extensions in my editor. For example, for web dev, I had an extension for angular, react, vuejs, nuxtjs, scss, prettier, javascript code snippets, css peak, auto close tag, auto rename tag, better comments, live server, ... And those were only for web dev, I had plenty more for everything... With this many extensions my editor was so damn slow, it was a pain even on my M1 macbook.

Even though it was painful, I wasn't actively searching for an alternative. The only solution that I though about, was this pending issue on the VSCode Github repository suggesting a "profiles" system that would only load the extensions required for the profile.

At the same time, I watched a video of Fireship on Youtube where he tried 10 different code editors, it's the first time I heard about Neovim. I was a bit intrigued but I remembered the pain of that last vim experience so I didn't pay much attention.

## Changing my Vim opinion

Few months later, I discovered ThePrimeagen on Twitch, who's the best ad possible for vim motions and neovim. As I was watching him everyday, I slowly changed my mind on vim and decided to try Neovim. I didn't know anything about neovim, vim motions and lua but I decided to fully dive in.

So I made multiple research on neovim and discovered that there are multiple distributions available and a lot of people were saying that it was the best way to get started. I didn't know nothing about this universe so I picked the distribution with the most attractive name "NvChad".

I was learning vim motions while learning NvChad default keybindings by working on a personal project. The experience was again painful: vim motions are hard and make you so slow at typing and moving, I hated the keybindings of NvChad and I didn't understand how to change those (skill issue).

## Back to VSCode

After 2 months, I was in love with vim motions, I understood how useful they are and I was convinced that I wouldn't code again without them. However, my opinion on Neovim/NvChad wasn't the same, so I moved back to my VSCode (with profiles that were added in the meantime). Of course, I added the vim motions extension to all my profiles and I was happy with it. I was still watching ThePrimeagen stream everyday.

## Fresh start

Shortly afterwards, VSCode started to feel slow again, this time i don't know exactly why except that I had more that 15 different profiles, I hated that I needed to switch manually between profiles when changing my workspace. In addition, when I needed a new global extension for all my profiles I had to install it individually on each profile... Again there was a solution on their issues tracker but I would have to wait.

I decided to give Neovim back a try, I backed up my previous config and, this time, chose another distribution that I heard from Prime and Teej on their stream: "LazyVim". Before installing LazyVim I also tried kickstart.nvim but it was a bit too much for me even if i'm sure that I'll use it in my future config updates.

LazyVim installation was much easier (I've gained experience from previous time, learned a bit of lua. NvChad wasn't so much harder, I just didn't read enough documentation). There are less default plugins and I loved the config structure (which is strict, like angular project structure, I like it). The default keybindings were simpler and more logical to me, and the few I didn't like were very simple to change (again due to experience gain).

LazyVim really felt less overwhelming and more beginner-friendly while being still complete for me.

## Conclusion

Is NvChad awful and LazyVim the best thing in the universe ? Not at all... I still think that LazyVim is easier to start with and more focused on simplicity but I could have managed with NvChad.

If I can give you a piece of advice to avoid making the same errors as me, learn vim motions in your current editor, Vim plugin for VSCode worked well for me as well as IdeaVim for Intellij. If you're satisfied with you setup, you're not required to move to Neovim. If you want to try something new, way faster, much more configurable and you feel at ease with the motions, learn a little bit a lua and try the LazyVim distribution for Neovim. This way, you will learn gradually without loosing too much productivity and you won't be overwhelmed. Finally, check out tmux which is the next game changer move and go subscribe to ThePrimeagen on Youtube and Twitch!
