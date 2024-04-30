# Simple Adblock Detector
Detect ad blockers with 1 line of code

Tested with:
- [AdBlock](https://chromewebstore.google.com/detail/gighmmpiobklfepjocnamgkkbiglidom)
- [Adblock Plus](https://chromewebstore.google.com/detail/adblock-plus-free-ad-bloc/cfhdojbkjhnklbpkdaibdccddilifddb)
- [Brave](https://brave.com/learn/category/ad-blocker/)
- [AdBlocker Ultimate](https://chromewebstore.google.com/detail/adblocker-ultimate/ohahllgiabjaoigichmmfljhkcfikeof)
- [AdGuard AdBlock](https://chromewebstore.google.com/detail/adguard-adblocker/bgnkhhnnamicmpeenaelnjfhikgbkllg)
- [1Block](https://chromewebstore.google.com/detail/adblock-1block/jajikjbellknnfcomfjjinfjokihcfoi)
- [Ghostery](https://chromewebstore.google.com/detail/ghostery-tracker-ad-block/mlomiejdfkolichcflejclcbmpeaniij)
- [Anti Adblock Detector](https://chromewebstore.google.com/detail/anti-adblock-detector/kjhdffcfinhkdfbbhjlfoadcdfgihmlp) (w/ [AdBlock](https://chromewebstore.google.com/detail/adblock-%E2%80%94-best-ad-blocker/gighmmpiobklfepjocnamgkkbiglidom))

## How to setup right now
1. Add the detectors code by making a js file with a ranodm name that has [simpleblocker.js](https://github.com/OddDevelopment/Simple-Adblock-Detector/blob/main/simpleblocker.js)'s code in it should be something like random numbers do not mention ad block in the file name or it could get blocked by ad blockers
2. Add it to your site, On the page you want to block ad blockers add the following code **MAKE SURE to replace the file name with yours**:

```
<script src="myrandomfilename.js"></script>
```

3. Setup the page it redirects the user to. This one is up to you, When an adblock is detected it redirects the user to `./disable-adblock` (ex. `https://example.com/disable-adblock`) you can put whatever you want here, The users with ad block on to see whats on this page.
4. Now test it out! If you have any issues get help on the [issues](https://github.com/OddDevelopment/Simple-Adblock-Detector/issues) page
5. Leave a ⭐ star if this helped you out <3

![star](https://github.com/OddDevelopment/Simple-Adblock-Detector/assets/135460135/4f613e15-23a2-4099-99b6-55e9a0cce3f8)
