# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: example.spec.js >> Amazon
- Location: tests\example.spec.js:21:5

# Error details

```
Error: browserType.launch: Target page, context or browser has been closed
Browser logs:

<launching> C:\Users\DEVARAJ\AppData\Local\ms-playwright\webkit-2370\Playwright.exe --inspector-pipe --disable-accelerated-compositing --headless --no-startup-window
<launched> pid=21308
Call log:
  - <launching> C:\Users\DEVARAJ\AppData\Local\ms-playwright\webkit-2370\Playwright.exe --inspector-pipe --disable-accelerated-compositing --headless --no-startup-window
  - <launched> pid=21308
  - [pid=21308] <gracefully close start>
  - [pid=21308] <kill>
  - [pid=21308] <will force kill>
  - [pid=21308] <process did exit: exitCode=3236495362, signal=null>
  - [pid=21308] starting temporary directories cleanup
  - [pid=21308] finished temporary directories cleanup
  - [pid=21308] <gracefully close end>

```