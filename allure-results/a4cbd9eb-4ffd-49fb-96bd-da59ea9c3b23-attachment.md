# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: FrameHandling.spec.js >> MultiFrame
- Location: tests\FrameHandling.spec.js:30:5

# Error details

```
Error: browserType.launch: Target page, context or browser has been closed
Browser logs:

<launching> C:\Users\DEVARAJ\AppData\Local\ms-playwright\webkit-2370\Playwright.exe --inspector-pipe --disable-accelerated-compositing --headless --no-startup-window
<launched> pid=27072
Call log:
  - <launching> C:\Users\DEVARAJ\AppData\Local\ms-playwright\webkit-2370\Playwright.exe --inspector-pipe --disable-accelerated-compositing --headless --no-startup-window
  - <launched> pid=27072
  - [pid=27072] <gracefully close start>
  - [pid=27072] <kill>
  - [pid=27072] <will force kill>
  - [pid=27072] <process did exit: exitCode=3236495362, signal=null>
  - [pid=27072] starting temporary directories cleanup
  - [pid=27072] finished temporary directories cleanup
  - [pid=27072] <gracefully close end>

```