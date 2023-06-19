# Brave extension bug

**Brave:** Version 1.52.126 Chromium: 114.0.5735.133 (Official Build) (64-bit)

The extension blocks all images on https://www.google.com/search?q=test&tbm=isch&gbv=1. But it stops working after Brave restart and needs to be refreshed in `chrome://extensions`.

## How to reproduce?

1. Install the extension

2. Go to https://www.google.com/search?q=test&tbm=isch&gbv=1 - all images should be blocked. If they aren't, try to refresh the extension

3. Restart Brave

4. Go to https://www.google.com/search?q=test&tbm=isch&gbv=1 again - all images are loaded but they should be blocked by the extension rules

## Other browsers

**Microsoft Edge:** Version 114.0.1823.43 (Official build) (64-bit)

Everything works fine after Edge restart
