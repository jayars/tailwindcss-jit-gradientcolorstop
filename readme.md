# @tailwind/jit gradientColorStop bug

## Steps

1. Build using `npm run build:css`
2. Open `index.html` in the browser
   * **Expect:** custom gradient to work
   * **Actual:** custom gradient doesn't work
3. edit `postconfig.config.js`
4. comment `@tailwindcss/jit`
5. uncomment `tailwindcss`
6. Save and rebuild
7. Open in browser again:
    * **Actual:** custom gradient works

## Demo

see [tailwind-jit-gradient-bug.mp4](tailwind-jit-gradient-bug.mp4) for behaviour.