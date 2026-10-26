# POST checks and beep codes

When a PC won't boot, note the beep pattern or diagnostic LEDs before swapping parts - the pattern is the motherboard reporting which check failed.

Common patterns (boards vary by vendor - always confirm against the board maker's manual):

| Pattern | Usually points to |
| --- | --- |
| 1 short beep | Normal POST, all checks passed |
| No beep, no display | Power supply, CPU seating, or a short - check the PSU switch and the 24-pin and CPU power cables first |
| Repeated short beeps / 2-3 short | Memory - reseat the RAM, then try one stick in the primary slot |
| 1 long, 2 short | Video - reseat the GPU and its power cable, or test with integrated graphics |
| Continuous long beeps | Memory not detected - reseat or swap sticks |

Rule I follow: write the pattern down in the service ticket before touching anything, and change one variable at a time.
