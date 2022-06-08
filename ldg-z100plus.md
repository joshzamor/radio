# LDG Z-100+ Cheat Sheet w/ FT-891

## Cables

1. Feedline to Antenna
1. Coax to Radio
1. Power (to PowerPole block)
1. Radio tuner cable to radio REM-ALC jack (TRS)
1. (optional) Ground

## Tuning

### Before

- Select desired band (press `Band` button).
- Use `Tune` button on tuner, modes set in radio.
- Use `AM mode` (press and hold `Band` button), low power (menu 16-02 set to 5).

### Operation

1. Full-tune:  Press `Tune` and **hold** till `Tuning` light **turn on and then turns off**, then release.
1. Memory tune:  Press `Tune` and **hold** until `Tuning` **turns on*, then release.
1. By-pass toggle:  Brings tuner out of matching (bypass), and into matching (active).
    1. Bypass: Press `Tune` and release.  `SWR` blinks _3 times_.  
    2. Active: Press `Tune` and release. `SWR` blinks _1 time_.

| SWR (from tuning)                     | Meaning                    |
|---------------------------------------|----------------------------|
| Solid                                 | SWR < 1.5                  |
| 5 blinks                              | 1.5 <= SWR <= 3.0          |
| no SWR                                | SWR > 3.0                  |
| no SWR, tuning light blinks 4-5 times | RF lost in middle or no RF |

### After

- Set radio mode back to desired mode.
- Reset power to desired level IFF using AM (menu 16-02).
