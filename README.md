# Multi-step Progress Bar

A clean and interactive multi-step progress indicator built with HTML, CSS, and JavaScript. This component visualizes progress through a sequence of steps using social media platform icons as markers.

## Features

- Animated progress bar that fills as users advance through steps
- Interactive navigation with Previous and Next buttons
- Social media platform icons representing each step
- Responsive design that works across different screen sizes
- Disabled button states to prevent invalid navigation
- Visual feedback for completed and current steps

## Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla)
- Font Awesome 6.5.1 for icons

## Usage

1. Open `index.html` in a web browser
2. Use the "Previous" and "Next" buttons to navigate through the steps
3. The progress bar will automatically update to show completion status
4. Each step is represented by a social media icon (Facebook, LinkedIn, Instagram, Twitter)

## Component Structure

- **Progress Bar**: A dynamic bar that fills from left to right
- **Step Indicators**: Circular markers with social media icons
- **Navigation Buttons**: Previous and Next buttons for user interaction
- **Labels**: Platform names displayed below each icon

## Customization

### Colors
The following CSS variables can be modified in `style.css`:

- Background color: `#ddd`
- Progress bar background: `#9f0404`
- Progress indicator: `rgb(240, 255, 32)`
- Step indicator background: `rgb(97, 1, 135)`
- Button background: `rgba(32, 32, 236, 0.923)`

### Icons
To change the icons, modify the Font Awesome classes in `index.html`:

```html
<i class="fa-brands fa-[platform-name]"></i>
```

## Browser Support

This component works in all modern browsers that support:
- Flexbox
- CSS Transitions
- ES6 JavaScript

