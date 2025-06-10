# Windows-10-Keyboard-Shortcuts

To recreate the exact HTML5 page with the aesthetic design and Windows 10 keyboard shortcuts as provided in the previous artifact, you can use the following prompt. This prompt is crafted to ensure the output matches the structure, styling, and content of the provided index.html, including the animated gradient background, glassmorphism cards, fixed bugs, and responsive layout using Tailwind CSS.

Prompt:

Create an HTML5 page that lists all Windows 10 keyboard shortcuts in an aesthetic, modern design. The page should use Tailwind CSS (via CDN) for styling and include the following features:

Content: Include a comprehensive list of Windows 10 keyboard shortcuts, organized into the following sections: General Shortcuts, Windows Key Shortcuts, Window Management, File Explorer Shortcuts, Accessibility Shortcuts, System Shortcuts, Command Prompt Shortcuts, Edge Browser Shortcuts, and Miscellaneous Shortcuts. Ensure the shortcuts match the standard Windows 10 key bindings (e.g., Ctrl + C for copy, Win + D for show/hide desktop, etc.), with accurate descriptions.
Design:
Background: Use an animated gradient background that transitions smoothly between dark colors (#1a202c, #2d3748, #4a5568, #2d3748) using CSS keyframes. Add a semi-transparent overlay (rgba(0, 0, 0, 0.2)) to ensure text readability.
Header: Include a centered header with a bold, blue (text-blue-400) title ("Windows 10 Keyboard Shortcuts") and a subtitle in gray (text-gray-400).
Navigation: Create a sticky navigation bar with a blurred background (backdrop-filter: blur(12px)) and semi-transparent dark color (rgba(31, 41, 55, 0.8)). Include links to each section with hover effects (change to text-blue-400) and ARIA labels for accessibility.
Shortcut Cards: Display shortcuts in a responsive grid (1 column on mobile, 2 on medium screens, 3 on large screens) using glassmorphism-style cards (background: rgba(255, 255, 255, 0.05), backdrop-filter: blur(10px), subtle border). Each card should have a hover effect (slight scale, translateY, and blue glow shadow).
Typography: Use a clean sans-serif font, with section headings in text-blue-300 and card content in text-gray-300 (titles) and text-gray-400 (descriptions).
Footer: Include a simple footer with a centered message ("Created by Grok | Powered by xAI | © 2025") in text-gray-400.
Bug Fixes:
Ensure all HTML is valid, with no malformed tags (e.g., no incorrect <p> attributes or unclosed tags).
Use consistent formatting for shortcut cards, avoiding redundant nesting or typos (e.g., use Win + PrtSc consistently, not Win + PrtScn).
Ensure navigation links have consistent styling (e.g., all start as text-gray-300).
Accessibility:
Add ARIA labels to navigation links for screen reader compatibility.
Ensure sufficient contrast ratios for text readability.
Responsive Design: Use Tailwind CSS classes to make the layout responsive across mobile, tablet, and desktop devices.
Output: Provide the complete HTML5 code in a single file, ready to be saved as index.html and opened in a browser. Do not include external dependencies beyond the Tailwind CSS CDN.
This prompt should guide the generation of an HTML5 page identical to the provided artifact, including all aesthetic enhancements, bug fixes, and content accuracy. If you need to tweak specific elements (e.g., different colors or additional features), you can modify the prompt accordingly. Let me know if you need further assistance!
