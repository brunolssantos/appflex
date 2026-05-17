# Calculadora Flex

A small web-based fuel comparison app built with HTML and JavaScript.

## What it does

This project helps a user decide whether ethanol or gasoline is more economical based on a simple price ratio rule:

- If the ethanol price is less than 70% of the gasoline price, ethanol is the better choice.
- Otherwise, gasoline is the better choice.

## Files

- `index.html` — page layout and form inputs.
- `calcflex.js` — comparison logic and image updates.
- `etanol.png` — image shown when ethanol is recommended.
- `gasolina.png` — image shown when gasoline is recommended.
- `neutro.png` — neutral image shown before any calculation.

## How to use

1. Open `index.html` in a browser.
2. Enter the ethanol price in the first field.
3. Enter the gasoline price in the second field.
4. Click the `Vantagem` button to calculate the recommendation.
5. Use the `Limpar` button to reset the recommendation image.

## Notes

- The app expects numeric input and accepts decimal values with either `.` or `,` as the decimal separator.
- This is a simple demonstration of JavaScript form handling and DOM updates.