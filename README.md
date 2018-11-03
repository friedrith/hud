# HUD

This project is about HUDs to see if HUDs like in science-fiction would be efficient in real life.

## Introduction

HUDs, also called Head-Up Displays are a way to enhance the user vision by placing piece of information
direcly in his vision field. HUDs may be performed using VR or AR. HUDs are made to facilitate the user
experience since the user doesn't need anymore to move his head to get the information on a dedicated
widget. Everything is displayed directly in his field of view.

![hud](assets/hud.png)

HUDs are composed of two parts. First of all, there are peripheral information about
the user state or the global environment. These elements are fixed on the periphery of the user
point of view. Then they are contextual information layered directly on the screen next to the
real element they are related to. These second ones move relatively to their target.

## Plan

The research protocol will be splitted in several parts:

* General state of the art study
* General list of the science-fiction movies/novels using HUDs
* Definition of the problematic
* Technical prototype
* Ux evaluation of efficiency
* optimizations and other Ux evaluations

During the several iterative studies, we will try several technologies from the more basic ones to
the more powerful ones. We will begin with VR because it is easier to create a
environment to evaluate the prototype. Then we will switch to AR depending of the progress of the
technologies.

## General state of the art

* [HUD challenge in 2018 organized by the US governement](https://www.nist.gov/ctl/pscr/funding-opportunities/prizes-challenges/2018-virtual-reality-heads-display-navigation)
* [HUD driving car simulator (2013)](https://www.gcu.ac.uk/media/gcalwebv2/business/Virtual%20Driving%20Simulator.pdf)
* [TSSG laboratory](https://www.tssg.org/research/units/ar-vr/arvr-research-themes/)
* [VR to train drill workers in mining industry](https://www.sciencedirect.com/science/article/pii/S2095268617303439)
* [Comparison between several VR platforms/support](http://www.indjst.org/index.php/indjst/article/viewFile/97234/71205)
* [HUD for vehicles](https://www.researchgate.net/publication/262635892_Human_Machine_Interface_for_Prototype_Head_Up_Display_Comparative_study_between_2D_and_VR_Simulation_Results)

> Conclusion: Most of research studies on VR deals only with the capacity of the user to see the display
without more questions about the ergonomy. Several of them discuss about the angle of vision. Few others
talk about the HUD in vehicle.

## Science-fiction analyze

In user experience research, science-fiction has always been a source of inspiration. So it may be
very useful to list science-fiction masterpiece.

### Movies

* Iron Man ([Iron man case study](https://scifiinterfaces.com/2015/07/01/iron-man-hud-a-breakdown/)), [Iron man HUDs](http://www.tartvfx.com/avengersageofultron/)
* Oblivion
* The 5th element
* Robocop
* https://scifiinterfaces.com/tag/hud/

* [analyze of HUD in movies](https://www.hudsandguis.com/)
* [Build HUD for movie](http://jayse.tv/v2/?portfolio=hud)

### Novels

* The Expanse (mars marines)

## Video games

It is also useful to study video games since the ergonomy is a very strong part of video game.

* Crysis

## Definition of the problematic

The hypothesis is: **Detailed HUDs can increase efficiency.**

The whole goal of this project will be validate or invalidate this hypothesis. In fact the answer
may be not totally binary and the purpose will be to find how to optimize the HUDs to make them as
efficient as possible and to check if they are more efficient that current ways of displaying information

**Head Up Display** describes various display devices.
In this project, we will focus on HUDs fixed from a user point of view called Head Mounted Display (HMD).
It gathers glasses (like Intel's Vaunt), contact lens, headsets (like Hololens or HTC Vive) and
helmets. But it excludes driving HUDs projected on the windshield for example.

Moreover, we will focus on the peripheral element fixed on the user field of view.

Finally, this project will be focused on HUD for hight productivity at work or event in daily life but not for
gaming.

## Technical prototype

First of all, we need to create a first prototype of the HUD.

* [How to prototype HUDs?](doc/01-how-to-prototype-huds.md) using web technologies and Google cardboards
* [Optimize development setup ?](doc/01-optimize-development-setup.md) using web technologies and Google cardboards


## Ux evaluation


## More links

* https://unity3d.com/fr/learn/tutorials/topics/virtual-reality/user-interfaces-vr
* https://www.marxentlabs.com/ar-trends-2014/
* https://www.businesswire.com/news/home/20160601005825/en/Augmented-Reality-Virtual-Reality-HMD-HUD-Handheld
* http://realityshift.io/blog/ui-ux-design-patterns-in-virtual-reality
* https://www.researchgate.net/publication/303519177_Immersion_in_Cardboard_VR_Compared_to_a_Traditional_Head-mounted_Display
* [very abstract course about VR/AR](https://medium.com/@michaelnaimark/vr-ar-fundamentals-prologue-b7aa3d119087)
* http://www.olednet.com/en/hud-and-hmd-meet-virtual-reality-and-soar/
* [HUD resources](https://www.rocketstock.com/video-packs/interface-hud-video-elements/?utm_source=premiumbeat&utm_campaign=2017-premiumbeat-video&utm_medium=video&utm_content=under-post-interface)
* http://jov.arvojournals.org/article.aspx?articleid=2389539
