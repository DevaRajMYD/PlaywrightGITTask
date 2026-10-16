# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: FrameHandling.spec.js >> SingleFrame
- Location: tests\FrameHandling.spec.js:7:5

# Error details

```
Error: browserType.launch: Target page, context or browser has been closed
Browser logs:

<launching> C:\Users\DEVARAJ\AppData\Local\ms-playwright\webkit-2370\Playwright.exe --inspector-pipe --disable-accelerated-compositing --headless --no-startup-window
<launched> pid=22136
Call log:
  - <launching> C:\Users\DEVARAJ\AppData\Local\ms-playwright\webkit-2370\Playwright.exe --inspector-pipe --disable-accelerated-compositing --headless --no-startup-window
  - <launched> pid=22136
  - [pid=22136] <gracefully close start>
  - [pid=22136] <kill>
  - [pid=22136] <will force kill>
  - [pid=22136] <process did exit: exitCode=3236495362, signal=null>
  - [pid=22136] starting temporary directories cleanup
  - [pid=22136] finished temporary directories cleanup
  - [pid=22136] <gracefully close end>

```