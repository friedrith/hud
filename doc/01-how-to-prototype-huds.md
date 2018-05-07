# How to build HUDs ?

The principle is to create a HUD with technologies very polyvalent to work on most of VR and AR
platforms.

For the first project, we will use web technologies, google cardboard and a One Plus 5.

## Virtual world

First of all, we create a virtual world where we move in using cardboards.
[A-frame](https://aframe.io/) seems to be the most robust web technology.

We used the welcome setup of A-Frame in order to get a basic scene to test the HUD.

![Basic scene](../assets/2d-environment.png)

## Mark I.0 : Naive peripheral

* fixed elements
* simple overlay

The main goal of HUDs is to display information in the user field of view so that he doesn't need
to look at a specific device to get the information. To enhance his vision, HUDs are composed of
several elements fixed from a user point of view as they were fixed to the headset.

![Crysis HUD](../assets/crysis-hud.jpg)

We can positionate these elements like this:

* top left
* top
* top right
* right
* bottom right
* bottom
* bottom left
* left

Google Cardboard don't have a very large field of view (90°) in comparison of real field of view (210°)
so we can only put the elements at the maximum top, bottom, left and right.

![HUD prototype mark 1](../assets/hud_mark_01_01.png)

Notice that the element are semi-transparent. These elements overlay a significant part of the screen
so transparency help the user to keep a large field of view. Moreover, the semi-transparency is useful
to avoid to catch the user attention.

Notice also that the components are oriented to created a sphere in front of the user face. The goal
is to simulate the glass of a helmet as a motorcycle or astronaut helmet. The elements are fixed very close
to the user head. It might make the user sick if he looks at the HUD too often. In the future, maybe we will
move back the HUD.

* https://aframe.io/docs/0.8.0/introduction/
* [VR headsets field of view](http://virtualrealitytimes.com/2017/03/06/chart-fov-field-of-view-vr-headsets/)

## Details

The previous section was about the position of the different elements. With a Google cardboard and a
One Plus 5, these elements are quite visible. However since they are in the peripheral vision, the
eye may be not able to really see the details of these components. So we need to try displaying details.

### Text

In order to display details, we will begin by displaying text.

After changing all boxes by a text, I noticed that the labels were not readable since the Google cardboard
deform the image on the borders of the lens.

So I had to close the HUD to the center of the image in all directions.

Concerning the band on the left and the right, I created 2 bands on each side. The blue band is closer to
the center and may be readable even if the numbers are smaller. The red one need bigger number to be readble.

![HUD prototype mark 1](assets/hud_mark_01_03.png)


* [text in A-Frame](https://aframe.io/docs/0.8.0/components/text.html)

### Colors
