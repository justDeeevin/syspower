# Syspower
syspower is a basic power menu and shutdown screen written in gtkmm4<br>

For now this only supports Hyprland.

# Configuration
syspower can be configured in 2 ways<br>
1: By changing config.hpp and recompiling (Suckless style)<br>
2: Using launch arguments<br>
```
arguments:
  -p	Set position (0 = top | 1 = right | 2 = bottom | 3 = left | 4 = center)
```