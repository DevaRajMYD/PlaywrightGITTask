# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: Locators.spec.js >> LoginLogoutCheckOrangeHRM
- Location: tests\Locators.spec.js:22:5

# Error details

```
Error: browserType.launch: Target page, context or browser has been closed
Browser logs:

<launching> C:\Users\DEVARAJ\AppData\Local\ms-playwright\webkit-2370\Playwright.exe --inspector-pipe --disable-accelerated-compositing --headless --no-startup-window
<launched> pid=28244
Call log:
  - <launching> C:\Users\DEVARAJ\AppData\Local\ms-playwright\webkit-2370\Playwright.exe --inspector-pipe --disable-accelerated-compositing --headless --no-startup-window
  - <launched> pid=28244
  - [pid=28244] <gracefully close start>
  - [pid=28244] <kill>
  - [pid=28244] <will force kill>
  - [pid=28244] <process did exit: exitCode=3236495362, signal=null>
  - [pid=28244] starting temporary directories cleanup
  - [pid=28244] finished temporary directories cleanup
  - [pid=28244] <gracefully close end>

```