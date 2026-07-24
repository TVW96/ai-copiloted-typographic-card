# ai-copiloted-typographic-card
<img width="1008" height="499" alt="Screenshot 2026-07-24 at 2 06 37 PM" src="https://github.com/user-attachments/assets/e5c79c8a-c335-4517-b671-2a2556089a71" />

### Initial Prompt: 
“Using purely CSS and HTML create an article card with: 
- An image,
- A category badge,
- A headline,
- A short description paragraph,
- And a “Read Article” button.
…using these set rules. All CSS styling must adhere to modern cascade & inheritance ruling and policies, utilize perceptual coloring use the oklch() color space for all background, text, and accent styling (including dark mode toggle). Use the clamp() function to create fluid typography scaling dynamically between mobile and desktop viewports without relying on rigid media queries. Utilize cutting-edge ‘text-box’ shorthand to eliminate invisible font margins (half-leading) on the button and badge. “

### Code Audit
1. DOCTYPE declaration tag not capitalized. 
2. Used closing tag styles for tags which do not require closing tags for syntax completion. Example: <meta />  should be <meta>, <link />  should be <link>, <input />  should be <input>, <img />  should be <img>.
3. Inline-size, block-size, border, outline, outline-offset, border-radius, margin, and padding are all using non relative sizing. The later mentioned are using px sizing. 
4. Two light-theme text states fall below WCAG AA’s 4.5:1 requirement for normal-sized text. I made a fix for this by updating the accent variable. 

### Video Demo


https://github.com/user-attachments/assets/f874a51a-21b4-417f-bd1a-bb94a2b84ced




