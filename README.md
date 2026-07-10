# TimeStream

A dead-simple **flowtime** timer: you work as long as you're in flow, then take a
break equal to your work time divided by 5 (adjustable).

- **Work** counts up. The break you've earned is shown live.
- **Take Break** freezes the worked time and counts down `work ÷ divisor`.
- A chime + notification fire when the break ends.
- Spacebar cycles the phases.

## Run it

- **Desktop:** open `index.html` in any browser (or use the `TimeStream.bat` / desktop
  shortcut to launch it as a standalone Chrome app window).
- **Installed app / Android:** served over HTTPS it's a PWA — open the page and choose
  *Install* (desktop) or *Add to Home Screen* (Android).

Single self-contained file, no build step, no dependencies.
