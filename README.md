## Simple Adblock Detector
Detect ad blockers with 1 line of code

**Currently detects:**
- [AdBlock](https://chromewebstore.google.com/detail/gighmmpiobklfepjocnamgkkbiglidom)
- [Adblock Plus](https://chromewebstore.google.com/detail/adblock-plus-free-ad-bloc/cfhdojbkjhnklbpkdaibdccddilifddb)
- [Brave](https://brave.com/learn/category/ad-blocker/)
- [AdBlocker Ultimate](https://chromewebstore.google.com/detail/adblocker-ultimate/ohahllgiabjaoigichmmfljhkcfikeof)
- [AdGuard AdBlock](https://chromewebstore.google.com/detail/adguard-adblocker/bgnkhhnnamicmpeenaelnjfhikgbkllg)
- [1Block](https://chromewebstore.google.com/detail/adblock-1block/jajikjbellknnfcomfjjinfjokihcfoi)
- [Ghostery](https://chromewebstore.google.com/detail/ghostery-tracker-ad-block/mlomiejdfkolichcflejclcbmpeaniij)
- [Anti Adblock Detector](https://chromewebstore.google.com/detail/anti-adblock-detector/kjhdffcfinhkdfbbhjlfoadcdfgihmlp) (w/ [AdBlock](https://chromewebstore.google.com/detail/adblock-%E2%80%94-best-ad-blocker/gighmmpiobklfepjocnamgkkbiglidom))

## Try it out:
<img src="https://github.com/OddDevelopment/Simple-Adblock-Detector/assets/135460135/0810f962-8fae-4f93-9e45-7a3424c2211a" alt="demo" width="500">

Demo: https://odddevelopment.github.io/Simple-Adblock-Detector/

## How to Setup Right Now

1. **Add Detector Code:**
   - Create a JavaScript file with a random name.
   - Make the content of the file [simpleblocker.js](https://github.com/OddDevelopment/Simple-Adblock-Detector/blob/main/simpleblocker.js)'s code.
   - Avoid mentioning "ad block" in the file name to prevent it from being blocked by ad blockers.

2. **Integrate into Your Site:**
   - Add the following code on page where ad blockers should be detected:
     ```html
     <script src="myrandomfilename.js"></script>
     ```
   - Replace "myrandomfilename.js" with your file name.

3. **Configure Redirect Page:**
   - Setup the page people get directed to.
   - Users are redirected to `./disable-adblock` (ex. `https://example.com/disable-adblock`) on this page you can put what you want people with ad blockers to see.

4. **Testing:**
   - Test it out!
   - If you have any issues/feedback, get help on the [issues](https://github.com/OddDevelopment/Simple-Adblock-Detector/issues) page.

5. **Support Us:** (its free <3)
   - If you find this project helpful, consider leaving a ⭐Star as a token of appreciation.

![star](https://github.com/OddDevelopment/Simple-Adblock-Detector/assets/135460135/4f613e15-23a2-4099-99b6-55e9a0cce3f8)
