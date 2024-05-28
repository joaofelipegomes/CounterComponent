# Counter Component

This repository contains a JavaScript script that implements a dynamic and interactive counter for a web page. The counter allows you to increment and decrement values within defined limits, updating the user interface in real-time.

## Features

- **Increment and Decrement**: Allows increasing or decreasing the counter value based on a defined unit.
- **Value Limits**: Respects the maximum and minimum values defined for each counter.
- **Dynamic Update**: Updates the counter display in real-time as the value changes.
- **Button Control**: Enables or disables increment and decrement buttons based on the current values.

## How It Works

1. **Element Selection**: Selects all `div` elements with the attribute `name="counter"` on the page.
2. **Attribute Retrieval**: Captures the maximum (`aria-valuemax`), minimum (`aria-valuemin`), and increment unit (`aria-current`) values.
3. **Interactivity**: Adds click events to the increment and decrement buttons to modify the counter value.
4. **Value Management**: Uses an `additionals` object to manage the list of values, ensure limits are respected, and update the interface.

## Project Structure

- `items.html`: Example of counter usage on a web page.
- `additional-items.html`: Example of multiple counters usage on a web page.

## How to Use

1. **Clone the repository**:
   ```bash
   git clone https://github.com/joaofelipegomes/CounterComponent.git
2. Open the **items.html** file in a browser to see the counter in action.
3. **Customize the counters**: Edit the `aria-valuemax`, `aria-valuemin` and `aria-current` attributes in the `div` elements to adjust the maximum, minimum values, and the increment unit as needed.

## Contributions
Contributions are welcome! Feel free to open issues or submit pull requests for improvements and fixes.
