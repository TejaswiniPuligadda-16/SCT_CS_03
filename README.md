# Password Strength Checker

A responsive web application that evaluates the strength of passwords in real-time, providing visual feedback and validation criteria.


## Features

- Real-time password strength evaluation
- Visual strength meter with color indicators
- Detailed criteria validation (length, character types)
- Responsive design that works on all devices
- Clean, modern UI with smooth animations

## Validation Criteria

The checker evaluates passwords based on:
- Minimum 15 characters (recommended for strong passwords)
- Contains uppercase letters (A-Z)
- Contains lowercase letters (a-z)
- Contains numbers (0-9)
- Contains special characters (!@#$%^&*, etc.)

## Strength Levels

1. **Very Weak** (Red) - Meets 0-1 criteria
2. **Weak** (Red/Orange) - Meets 2 criteria
3. **Medium** (Orange) - Meets 3 criteria
4. **Strong** (Green) - Meets 4 criteria
5. **Very Strong** (Dark Green) - Meets all 5 criteria

## Technologies Used

- HTML5
- CSS3 (Flexbox, Gradients, Transitions)
- JavaScript (DOM Manipulation, Regular Expressions)

## Installation

No installation required! Simply open `index.html` in any modern web browser.

## How to Use

1. Type or paste your password into the input field
2. View the strength meter and text feedback
3. Check which password criteria you've met
4. Improve your password until it reaches "Very Strong"

## Customization

To modify the strength criteria or styling:

1. **Change criteria**: Edit the `calculateStrength()` function in the JavaScript
2. **Modify colors**: Update the CSS variables or direct color values
3. **Adjust thresholds**: Change the values in `updateStrengthMeter()` and `updateStrengthText()`

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your improvements.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Inspired by modern password strength meters
- Gradient background from [uiGradients](https://uigradients.com)
- Icons from Unicode characters
