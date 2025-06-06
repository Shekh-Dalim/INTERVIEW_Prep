🟢 Beginner (Easy)
Q1. What is Tailwind CSS?
```
Tailwind CSS is a utility-first CSS framework used for rapidly building custom user interfaces. Instead of writing custom CSS, you use pre-defined classes to style your HTML elements.
```

Q2. How do you install Tailwind CSS?
```
You can install it via npm: `npm install -D tailwindcss` and then generate the config using `npx tailwindcss init`.
```

Q3. What is the purpose of the tailwind.config.js file?
```
It is used to customize Tailwind’s default configuration such as colors, breakpoints, fonts, spacing, and more.
```

Q4. What is utility-first CSS?
```
It means styling elements using pre-defined single-purpose classes instead of writing custom CSS rules.
```

Q5. How do you apply margin in Tailwind CSS?
```
Using the `m` (all sides), `mt`, `mb`, `ml`, `mr` (top, bottom, left, right) classes. Example: `mt-4`, `ml-2`.
```

🟡 Intermediate
Q6. How do responsive breakpoints work in Tailwind CSS?
```
You use prefixes like `sm:`, `md:`, `lg:`, and `xl:` before utility classes to apply styles at different screen sizes. Example: `md:text-lg`.
```

Q7. What is the difference between hidden and invisible in Tailwind?
```
hiddenremoves the element from the layout, whileinvisible` keeps it in the layout but hides it visually.
```

Q8. How can you customize colors in Tailwind CSS?
```
You can add or override colors inside the `extend` section of `tailwind.config.js` under the `theme.colors` object.
```

Q9. What is JIT (Just-in-Time) mode in Tailwind CSS?
```
JIT mode compiles styles on-demand as you use them, leading to faster builds and smaller CSS files.
```

Q10. How do you center a div using Tailwind?
```
Use `flex`, `justify-center`, and `items-center` to center it both horizontally and vertically. Also `mx-auto` can be used for horizontal centering.
```

🔴 Advanced (Hard)
```
Q11. How do you create a custom plugin in Tailwind CSS?
You can use the `addUtilities`, `addComponents`, or `addBase` APIs inside the `plugins` array in `tailwind.config.js` to define reusable styles.
```

Q12. How do variants like hover:, focus: work?
```
They allow you to apply styles under specific conditions. Example: `hover:bg-blue-500` applies a background color on hover.
```

Q13. What are purge settings in Tailwind and why are they important?
```
Purge removes unused styles from your final CSS file, helping reduce file size. It is configured under the `content` array in `tailwind.config.js`.
```

Q14. Explain the concept of @apply directive.
```
It lets you use Tailwind utility classes inside a custom CSS file. Example: `.btn { @apply px-4 py-2 bg-blue-500 text-white; }`.
```

Q15. How would you handle dark mode in Tailwind CSS?
```
Enable `darkMode: 'class'` or `'media'` in `tailwind.config.js`. Use `dark:` prefix to apply styles in dark mode. Example: `dark:bg-black`.
```

