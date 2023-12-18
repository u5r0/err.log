### [Forever-pending requests to dev server](https://github.com/vitejs/vite/issues/5310)
- **Problem:** Chromium-based browsers on Linux
- **Fix:** Switch to LibreWolf 
- [vite troubleshooting](https://vitejs.dev/guide/troubleshooting.html#dev-server)
- [related thread](https://github.com/vitejs/vite/issues/11468)

### [JavaScript heap out of memory](https://github.com/vitejs/vite/issues/2433)
- **Problem:** [Rollup issue](https://rollupjs.org/troubleshooting/#error-javascript-heap-out-of-memory)
- **Temp Fix:** `export NODE_OPTIONS=--max-old-space-size=32768` to the terminal

