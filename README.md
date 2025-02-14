# Tailwind CSS Gradient Rendering Issue

This repository demonstrates a potential issue with Tailwind CSS gradients not rendering correctly in older browsers that lack support for the `linear-gradient` CSS function.

## Bug Description

The `bg-gradient-to-r` utility in Tailwind CSS creates a linear gradient. However, if the browser doesn't support `linear-gradient`, the gradient won't render correctly, resulting in a plain background color instead.

## Solution

The solution involves adding a fallback style to handle browsers that don't support `linear-gradient`.  This can be accomplished by using a CSS vendor prefix or a conditional style.