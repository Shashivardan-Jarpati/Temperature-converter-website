# Temperature-converter-website
The user will input a temperature in either Fahrenheit or Celsius and press a "convert" button. The converted temperature will then be displayed with the correct unit.
# Temperature Converter App
Overview
This is a fully functional, responsive temperature converter web application that converts between Celsius (°C), Fahrenheit (°F), and Kelvin (K). Built with HTML, CSS, and vanilla JavaScript, it features a modern gradient design with real-time conversion and input validation.
​
# Features
Three-unit Conversion: Supports Celsius, Fahrenheit, and Kelvin with bidirectional conversion formulas.

Real-time Results: Displays converted values for all units plus the primary conversion in large format.

Input Validation: Checks for valid numbers, shows error messages, and clears on new input.

Interactive UI: Radio buttons for unit selection, animated results with slide-in effect, hover states.

Keyboard Support: Enter key triggers conversion; responsive on mobile devices.

Modern Design: Gradient backgrounds, shadows, smooth transitions, and mobile-first layout.
​

# How It Works
-- Input Unit: Celsius --	
-- Conversion Formulas: °F = °C × 9/5 + 32  
K = °C + 273.15	--
-- Display Priority: Fahrenheit first-- 
​
-- Input Unit: Fahrenheit--	
-- Conversion Formulas: °C = (°F - 32) × 5/9
K = °C + 273.15	--
-- Display Priority: Celsius first --
​
-- Input Unit: Kelvin	--
-- Conversion Formulas: °C = K - 273.15
°F = °C × 9/5 + 32 --	
-- Display Priority: Celsius first-- 
​
Results round to 2 decimal places with animated reveal.
​

# Usage
Save as tempconvert.html and open in any modern browser.

Enter temperature value and select input unit via radio buttons.

Click "Convert Temperature" or press Enter for instant results.

No server or external dependencies required—works offline.
​

# Technologies
HTML5: Semantic structure with form inputs and labels.

CSS3: Flexbox layout, gradients, animations (slideIn), custom radio buttons, media queries (600px breakpoint).

JavaScript: Event listeners, parseFloat validation, dynamic DOM updates, precise math formulas.
​
