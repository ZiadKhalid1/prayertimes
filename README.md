# prayertimes
command-line utility for retrieving and displaying prayer timings based on the user's location, supporting multiple languages.

# Usage

```
$ prayertimes
📅 06-Jumādá al-ūlá-1445
Fajr: 4:50 AM
Sunrise: 6:18 AM
Dhuhr: 11:41 AM
Asr: 2:43 PM
Maghrib: 5:03 PM
Isha: 6:21 PM

$ prayertimes --help
usage: 
  prayertimes [OPTION]

options:
  -p  --prayers              Display Day's praysers
  -pa --prayers-ar           Display prayers in Arabic
  -pg --prayers-gui          Display in gui(using yad)
  -n  --next-prayer          Display the next prayer
  -c  --current-prayer       Display current prayer
  -N  --notify               Runs the notifications service
  -h  --help                 Display this message
```
