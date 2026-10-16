# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: example.spec.js >> Flipkart
- Location: tests\example.spec.js:25:5

# Error details

```
Error: browserType.launch: Target page, context or browser has been closed
Browser logs:

<launching> C:\Users\DEVARAJ\AppData\Local\ms-playwright\webkit-2370\Playwright.exe --inspector-pipe --disable-accelerated-compositing --headless --no-startup-window
<launched> pid=13852
Call log:
  - <launching> C:\Users\DEVARAJ\AppData\Local\ms-playwright\webkit-2370\Playwright.exe --inspector-pipe --disable-accelerated-compositing --headless --no-startup-window
  - <launched> pid=13852
  - [pid=13852] <gracefully close start>
  - [pid=13852] <kill>
  - [pid=13852] <will force kill>
  - [pid=13852] <process did exit: exitCode=3236495362, signal=null>
  - [pid=13852] starting temporary directories cleanup
  - [pid=13852] finished temporary directories cleanup
  - [pid=13852] <gracefully close end>

```