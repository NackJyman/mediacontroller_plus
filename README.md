# mediacontroller+
This is a modified version of mediacontroller plasma5 widget.

---
## NackJyman's Fork

Intent is to change the desktop's Full Representation Vertical View to be able to remove the media player buttons. I want to display it just the same but without the buttons and not have empty space where they were. I do not require these buttons and would cover them with another widget however I can't figure out how to make that happen nicely so I am opting to do this.

---

It provides the same functionality as the traditional mediacontroller widget, giving you control over every media player in your system (through the MPRIS2 protocol), but it adapts to more factor forms and sizes, allowing you to have a nice media control even on the panel.

You can download it on the [KDE Store](https://store.kde.org/p/1317639/), or use the built-in 'Get New Addons' directly in your plasma desktop.

![mediacontroller+ gallery](screenshot.png)

* Full Representation (_desktop_, _pop-up_):
    - Vertical View (same as in classic mediacontroller)
    - Horizontal View: when the widget gets wider, the album art goes to the left
    - Icon tab bar to select the player in a nicer and quicker way

* Compact Representation (_panel_, _systray_):
    - Different Views:
        - Compact View for panels. It keeps most of the functionallity in a smaller size: icon/album art, track/artist, player controls and progress bar which uses the same style as the taskbar progress jobs.
        - Minimal View for thinner panels, hiding the album art and progress bar
        - Icon View for smaller sizes (same as in classic mediacontroller)
    - Minimum (preferred) / Maximum widths configurable
    - Display options to show/hide progressbar
    
    - Drag and drop any media file or URL to open it
        - on the selected player (the player has to support this option)
        - on default application if no player selected

As a disclaimer, it is one of my first tries on qml and plasmoids, and I just wanted to have a nicer media player applet for my panel, while keeping the most of the classic widget untouched. Of course, my main wish would be for this changes to be integrated in the official mediacontroller applet, which I find kind of visually simple in its current state.
