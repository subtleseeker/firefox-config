`about:config` (Mac-only)
```
  browser.gesture.pinch.in         cmd_fullZoomReduce
  browser.gesture.pinch.in.shift   cmd_fullZoomReset
  browser.gesture.pinch.out        cmd_fullZoomEnlarge
  browser.gesture.pinch.out.shift  cmd_fullZoomReset
  findbar.highlightAll             true
```
---
`Profile/id/chrome/userChrome.css`
```
.tabbrowser-tab {
min-width: initial !important;
}
.tab-content {
overflow: hidden !important;
}
```
