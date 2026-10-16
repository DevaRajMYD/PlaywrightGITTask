# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: Dropdown.spec.js >> Native Dropdown
- Location: tests\Dropdown.spec.js:5:5

# Error details

```
Error: browserType.launch: Target page, context or browser has been closed
Browser logs:

<launching> C:\Users\DEVARAJ\AppData\Local\ms-playwright\webkit-2370\Playwright.exe --inspector-pipe --disable-accelerated-compositing --headless --no-startup-window
<launched> pid=28620
Call log:
  - <launching> C:\Users\DEVARAJ\AppData\Local\ms-playwright\webkit-2370\Playwright.exe --inspector-pipe --disable-accelerated-compositing --headless --no-startup-window
  - <launched> pid=28620
  - [pid=28620] <gracefully close start>
  - [pid=28620] <kill>
  - [pid=28620] <will force kill>
  - [pid=28620] <process did exit: exitCode=3236495362, signal=null>
  - [pid=28620] starting temporary directories cleanup
  - [pid=28620] finished temporary directories cleanup
  - [pid=28620] <gracefully close end>

```