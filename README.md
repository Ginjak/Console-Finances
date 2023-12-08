# Console-Finances

## Description

This repository contains a JavaScript code designed for financial analysis on a dataset containing date-wise information about profits and losses. The analysis outputs the following key metrics to the console.

## Metrics:

1. **Total Number of Months:**

   - Calculates and displays the total number of months included in the dataset.

2. **Net Total Amount of Profit/Losses:**

   - Calculates and displays the overall sum of Profit/Losses over the entire period.

3. **Average Change in Profit/Losses:**

   - Tracks the changes in Profit/Losses from month to month and calculates the average change.

4. **Greatest Increase in Profit/Losses:**

   - Identifies and displays the date and amount of the largest increase in Profit/Losses over the entire period.

5. **Greatest Decrease in Profit/Losses:**
   - Identifies and displays the date and amount of the largest decrease in Profit/Losses over the entire period.

![](/images/screenshot.jpg)

## Instalation

n/a

## Usage

To view the data output for financial analysis when the webpage is open:

1. Open the webpage.
2. Press `Ctrl + Shift + I` on Windows or `Option + ⌘ + J` on macOS to open the developer tools.
3. Select the "Console" tab.

In the console, you will see the results of the Financial Analysis script. You can customize the financial dataset by modifying the "finances" data array in the `index.js` file. Ensure that the first element of each array entry is the Date, and the second element is the corresponding Profit/Loss number.

Example usage in `index.js`:

```javascript
var financesData = [
  ["2022-01-01", 1000],
  // Add more data entries...
];
```

## Credits

n/a

## License

This project is licensed under the [MIT License](./LICENSE)
