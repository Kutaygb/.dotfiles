## Mouse Acceleration

[Source](https://wiki.archlinux.org/title/Mouse_acceleration#with_libinput)

```conf
Section "InputClass"
	Identifier "My Mouse"
	MatchIsPointer "yes"
	Option "AccelerationProfile" "-1"
	Option "AccelerationScheme" "none"
	Option "AccelSpeed" "-1"
EndSection
```

## Desktop Menu

[j4-dmenu-desktop](https://github.com/enkore/j4-dmenu-desktop)

## Picom Version

[Picom](https://github.com/yshui/picom)