# Info for developers

## Test addon

1. Make changes to local checkout.
2. Zip the project:
```bash
    zip -r -FS disable-yt-numberkeys-except-0.zip disable-yt-numberkeys-except-0 manifest.json
```
3. Go to: about:debugging#/runtime/this-firefox
4. Click "Load Temporary Add-on" and select disable-yt-numberkeys-except-0.zip

This website can be used to test embedded youtube videos:
https://www.cookietractor.com/youtube-and-vimeo-without-cookies

## Upload new version

1. Bump version in manifest.json
2. Test following directions above
3. Upload new version:
   https://addons.mozilla.org/en-US/developers/addon/disable-yt-numberkeys-except-0/edit
4. Add git tag: `git tag v1.x`
5. Upload git tag: `git push origin v1.x`
