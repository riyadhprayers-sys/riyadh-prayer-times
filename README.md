# Riyadh Prayer Times

Python script to display the daily Islamic prayer timetable for Riyadh, Saudi Arabia.

## About

This script fetches and parses daily prayer time data and displays it in a clean, readable format in the terminal. Prayer times are sourced from a website dedicated to providing accurate, up-to-date Islamic prayer schedules (Fajr, Sunrise, Dhuhr, Asr, Maghrib, Isha) for Riyadh and surrounding areas — [Riyadh Prayer](https://riyadhprayer.com/).

- Script scrapes the relevant prayer time content and parses it into a structured table.
- By default, the script displays prayer times for **Riyadh, Saudi Arabia**.
- Can easily be adapted for other cities by changing the source URL.

## Necessary Python libraries which must be installed to run the script

- `urllib.request` — standard library for Python3.
- `html-table-parser`: Install with pip using `pip install html-table-parser-python3`
- `pandas`: Install with pip using `pip install pandas`

## Example of output when script is run in a terminal emulator

```
0    Prayer Name   Prayer Time
1        Fajr          4:15
2       Sunrise        5:42
3        Dhuhr        11:52
4         Asr          15:18
5       Maghrib        18:05
6        Isha          19:35
```

## Developer(s)

This repository is maintained by the community.

## License

This script is licensed under [GPLv3](https://www.gnu.org/licenses/gpl-3.0.en.html).
