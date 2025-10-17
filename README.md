# Dishy-Tracker
An open source satellite tracker platform




# Matériel

| Composant | Référence / Détail |
|------------|--------------------|
| Microcontrôleur | Raspberry Pi Pico |
| Driver moteur | A4988  |
| Moteur pas à pas | NEMA 17 |
| Alimentation | 12V / 2A minimum |
| Structure | Pièces imprimées 3D (Fusion 360 ) |
| Divers | Câbles , roulements, visserie M3 

# Wiring
Here is the wiring.


| Signal | Driver (A4988) | Raspberry Pico | Description |
|--------|------------------------|------|--------------|
| STEP   | STEP   | GP3 | step pulse input |
| DIR    | DIR    | GP2 | rotation direction  |
| EN     | EN     | GP9 | enable (active low) |
| SLEEP  | SLP    | GP7 | puts driver to sleep (LOW = sleep) |
| RESET  | RST    | GP8 | resets driver (LOW = reset) |
| VMOT   | 12V    | —    | motor power supply |
| GND    | GND    | GND  | ground  |
| 1A/1B//2A/2B | Moteur | — | motor coils |


