# Chapter 4: CSS Units

Summary:

- It's better not to use fixed value like PX for font-size, because it'll override user settings on their browser
- You shouldn't set the font-size in the root element (i.e. html{})
- instead use element selector (i.e. p {}) and use rem unit, so it'll use browser default value as it references
- If you don't define the default value, the browser will handle that
- Example, if you use 1 rem, it'll set to browser's default font value/size (usually 16px for p{}) and if you use 2 rem, it'll use browser's default font-size and multiply it by 2
- rem stands for "root em", and meanwhile em has 2 use (when u use it for font-size, it'll reference to the parent, and when u use it for the element margin/padding it'll reference to the element font-size itself)
- ch stands for character, and used to limiting character amount perline in an element
- usually % is better than vw, because it shouldn't overflow element
