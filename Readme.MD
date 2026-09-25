# Leap Year Lab

A simple leap-year project created by **Zafar**.

The project includes a welcome landing page and an interactive checker that tells users whether a year is a leap year.

## Features

- Responsive welcome page
- Interactive year input
- Leap-year result for any positive whole year
- February day count
- Previous and next leap year details
- Eid al-Fitr and Eid al-Adha dates for nearby past and future years
- Ramadan start, end, and duration for the entered year
- US federal holiday dates for the entered year
- Full 12-month year calendar with Ramadan and Eid highlights
- Clear button to reset the checker
- Python version of the leap-year checker

## Run in the Browser

1. Open `index.html` in a web browser.
2. Select **Try the leap-year checker**.
3. Enter a year, then select **Check year**.

You can also open `checker.html` directly to use the checker.

The Eid and Ramadan dates use the browser's Umm al-Qura calendar calculation. Local moon-sighting announcements may differ by one day.

## Public Links

- [GitHub repository](https://github.com/ms12871/Calendar)
- [Welcome landing page](https://ms12871.github.io/Calendar/)
- [Leap-year checker](https://ms12871.github.io/Calendar/checker.html)

## US Federal Holidays

The checker displays these nationwide US federal holidays for the entered year:

- New Year's Day
- Martin Luther King Jr. Day
- Washington's Birthday
- Memorial Day
- Juneteenth National Independence Day
- Independence Day
- Labor Day
- Columbus Day
- Veterans Day
- Thanksgiving Day
- Christmas Day

State and local public holidays may be different. Observed days can also change when a holiday falls on a weekend.

## Run the Python Version

Open a terminal in the project folder and run:

```bash
python3 test.py
```

Enter a year when prompted.

## Project Files

| File | Description |
| --- | --- |
| [`index.html`](index.html) | Welcome landing page for the project |
| [`checker.html`](checker.html) | Browser-based leap-year checker |
| [`test.py`](test.py) | Python leap-year checker |

## Leap-Year Rule

A year is a leap year when it is divisible by 400, or when it is divisible by 4 but not by 100.

Examples:

- `2024` is a leap year.
- `2023` is not a leap year.
- `2000` is a leap year.
- `1900` is not a leap year.

## Creator

Created by **Zafar**.