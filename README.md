# Tailwind CSS Classes Not Applying on Hover

This repo demonstrates a bug where Tailwind CSS classes are not applied correctly on hover.  The expected behavior is for the div to change background color to blue when hovered over, but it remains red.

## Bug

The `hover:bg-blue-700` class doesn't seem to work.

## Solution

The issue was resolved by ensuring the correct order of Tailwind directives and verifying the Tailwind configuration is set up correctly.