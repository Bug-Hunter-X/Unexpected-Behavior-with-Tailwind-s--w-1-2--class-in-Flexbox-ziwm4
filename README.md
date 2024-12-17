# Tailwind CSS Flexbox Width Issue

This repository demonstrates a common issue encountered when using Tailwind CSS's fractional width classes (`w-1/2`, `w-1/3`, etc.) within a flexbox container.  The expected behavior is for the divs to occupy 50% of the available width each. However, due to the default flexbox behavior, this doesn't always happen.

The `bug.html` file shows the problem: The divs don't evenly split the width, and instead, they wrap onto the next line.

The solution (`bugSolution.html`) demonstrates how to fix this issue using `flex-grow` or `w-full`.