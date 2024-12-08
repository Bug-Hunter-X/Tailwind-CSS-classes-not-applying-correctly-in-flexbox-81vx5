# Tailwind CSS Flexbox Issue

This repository demonstrates a common issue encountered when using Tailwind CSS with flexbox.  The problem involves unexpected behavior of flex items, even when using what appears to be correct Tailwind class names.

The `bug.js` file contains the problematic code.  The `bugSolution.js` file provides a solution and explanation.

## Problem
The expected outcome is two divs, each taking up half of the parent container width, side-by-side. However, due to a hidden conflict or incorrect understanding of Tailwind's class interaction, the divs may overlap, be incorrectly sized or not fill the container as intended. This often stems from unexpected interactions between flexbox properties and other Tailwind classes. 

## Solution
The solution involves a careful review of the Tailwind CSS documentation for flexbox, and potentially a more explicit approach to specifying sizing and alignment for flexbox containers and items.