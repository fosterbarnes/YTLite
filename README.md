# YouTube Plus (YTweaks Fork)
[YouYube Plus](https://github.com/dayanch96/YTLite) with added plugins.

This fork focuses on adding more tweak options when building with GitHub actions, specificially [YTweaks](https://github.com/fosterbarnes/YTweaks) No changes are made to the YouTube Plus .deb itself, just the tweaks that get packaged with it. 

YTweaks added settings:
- **Fullscreen to the right or left:** Locks fullscreen orientation.
- **Disable floating miniplayer:** Restores the old miniplayer by disabling the floating miniplayer.
- **Virtual fullscreen bezels:** Adds invisible touch-safe zones on black bars to prevent accidental taps and skips.


Added tweaks:
- [YTweaks](https://github.com/fosterbarnes/YTweaks)
- [YTABConfig](https://github.com/PoomSmart/YTABConfig)
- [YTIcons](https://github.com/PoomSmart/YTIcons)
- [YouGroupSettings](https://github.com/fosterbarnes/YouGroupSettings)

Original repo: https://github.com/dayanch96/YTLite

## How to build a YTPlusTweaked using Github actions
> [!NOTE]
> If this your first time, complete following steps before starting:
>
> 1. Fork this repository using the fork button on the top right
> 2. On your forked repository, go to **Repository Settings** > **Actions**, enable **Read and Write** permissions.

<details>
  <summary>How to build YTPlusTweaked app</summary>
  <ol>
    <li>Fork this repo if you haven't already. Sync if your branch is out of date.</li>
    <li>Go to the "Actions" tab of your new repo.</li>
    <li>Select "Build YTPlusTweaked".</li>
    <li>Click "Run workflow".</li>
    <li>Select bundled tweaks.</li>
    <li>Prepare a decrypted .ipa file <em>(we cannot provide this due to legal reasons)</em>, then upload it to a file provider (e.g., https://litterbox.catbox.moe, or Dropbox is recommended). Paste the URL of the decrypted IPA file in the provided field.
    <strong>NOTE:</strong> Make sure to provide a direct download link to the file, not a link to a webpage. Otherwise, the process will fail.</li>
    <li>Click "Run workflow".</li>
    <td><img src="Resources/scr15.jpg" alt="Screenshot 15" /></td>
    <li>Wait for the build to finish. You can download the YouTube Plus app from the releases section of your forked repo. (If you can't find the releases section, go to your forked repo and add /releases to the URL, i.e., github.com/user/YTPlusYTweaks/releases.)</li>
  </ol>
</details>

<details>
  <summary>How to build .debs</summary>
  <ol>
    <li>Fork this repo if you haven't already. Sync if your branch is out of date.</li>
    <li>Go to the "Actions" tab of your new repo.</li>
    <li>Select "Build .deb packages".</li>
    <li>Click "Run workflow".</li>
    <li>Select tweaks.</li>
    <li>Click "Run workflow".</li>
    <td><img src="Resources/scr10.jpg" alt="Screenshot 10" /></td>
    <li>Wait for the build to finish. You can download the YouTube Plus app from the releases section of your forked repo. (If you can't find the releases section, go to your forked repo and add /releases to the URL, i.e., github.com/user/YTPlusYTweaks/releases.)</li>
  </ol>
</details>

## Table of Contents
- [Screenshots](#screenshots)
- [Main Features](#main-features)
- [FAQ](#faq)
- [How to build a YouTube Plus app using GitHub Actions](#how-to-build-a-youtube-plus-app-using-github-actions)
- [Supported YouTube Version](#supported-youtube-version)
- [Tweak Integration Details](#tweak-integration-details)

## Screenshots
<table>
   <tr>
      <td><img src="Resources/scr11.jpg" alt="Screenshot 1" /></td>
      <td><img src="Resources/scr13.jpg" alt="Screenshot 2" /></td>
      <td><img src="Resources/scr14.jpg" alt="Screenshot 3" /></td>
   </tr>
</table>

<details>
  <summary>More screenshots</summary>
  <table>
    <tr>
      <td><img src="Resources/scr4.jpg" alt="Screenshot 4" /></td>
      <td><img src="Resources/scr5.jpg" alt="Screenshot 5" /></td>
      <td><img src="Resources/scr6.jpg" alt="Screenshot 6" /></td>
    </tr>
    <tr>
      <td><img src="Resources/scr7.jpg" alt="Screenshot 7" /></td>
      <td><img src="Resources/scr8.jpg" alt="Screenshot 8" /></td>
      <td><img src="Resources/scr9.jpg" alt="Screenshot 9" /></td>
    </tr>
  </table>
</details>

## Main Features
<li>Download videos, audio (including audio track selection), thumbnails, posts, and profile pictures</li>
<li>Copy video, comment, and post information</li>
<li>Interface customization: Remove feed elements, reorder tabs, enable OLED mode, and as use Shorts-only mode</li>
<li>Player settings: Gestures, default quality, preferred audio track</li>
<li>Save, Load and Restore settings. Clear cache once or automatically on app startup</li>
<li>Built-in SponsorBlock</li>
<li>And much, much more</li>
<br>


**YouTube Plus preferences can be found in the YouTube Settings**

**All contributors are listed in the Contributors section**
**Used open-source libraries are listed in the Open Source Libraries section**

## FAQ
- [🇺🇸 English FAQ](FAQs/FAQ_EN.md)
- [🇷🇺 ЧаВо на Русском](FAQs/FAQ_RU.md)
- [🇮🇹 FAQ in Italiano](FAQs/FAQ_IT.md)
- [🇵🇱 FAQ po polsku](FAQs/FAQ_PL.md)

## Supported YouTube Version
<ul>
   <li><strong>Latest confirmed:</strong> <em>20.50.6</em></li>
   <li><strong>Date tested:</strong> <em>Dec 18, 2025</em></li>
   <li><strong>YouTube Plus:</strong> <em>5.2 beta 4</em></li>
</ul>

## Tweak Integration Details
<details>
  <summary>YouPiP</summary>
  <p>YouPiP is a tweak developed by <a href="https://github.com/PoomSmart">PoomSmart</a> that enables the native Picture-in-Picture feature for videos in the iOS YouTube app.</p>
  <p><strong>YouPiP preferences</strong> are available in the <strong>YouTube settings</strong>.</p>
  <p>Source code and additional information are available <a href="https://github.com/PoomSmart/YouPiP">in PoomSmart's GitHub repository</a>.</p>
</details>

<details>
  <summary>YTUHD</summary>
  <p>YTUHD is a tweak developed by <a href="https://github.com/PoomSmart">PoomSmart</a> that unlocks 1440p (2K) and 2160p (4K) resolutions in the iOS YouTube app.</p>
  <p><strong>YTUHD preferences</strong> are available in the <strong>Video quality preferences</strong> section under <strong>YouTube settings</strong>.</p>
  <p>Source code and additional information are available <a href="https://github.com/PoomSmart/YTUHD">in PoomSmart's GitHub repository</a>.</p>
</details>

<details>
  <summary>Return YouTube Dislikes</summary>
  <p>Return YouTube Dislikes is a tweak developed by <a href="https://github.com/PoomSmart">PoomSmart</a> that brings back dislikes on the YouTube app.</p>
  <p><strong>Return YouTube Dislikes preferences</strong> are available in the <strong>YouTube settings</strong>.</p>
  <p>Source code and additional information are available <a href="https://github.com/PoomSmart/Return-YouTube-Dislikes">in PoomSmart's GitHub repository</a>.</p>
</details>

<details>
  <summary>YouQuality</summary>
  <p>YouQuality is a tweak developed by <a href="https://github.com/PoomSmart">PoomSmart</a> that allows to view and change video quality directly from the video overlay.</p>
  <p><strong>YouQuality can be enabled</strong> in the <strong>Video overlay</strong> section under <strong>YouTube settings</strong>.</p>
  <p>Source code and additional information are available <a href="https://github.com/PoomSmart/YouQuality">in PoomSmart's GitHub repository</a>.</p>
</details>

<details>
  <summary>DontEatMyContent</summary>
  <p>DontEatMyContent is a tweak developed by <a href="https://github.com/therealFoxster">therealFoxster</a> that prevents the Notch/Dynamic Island from munching on 2:1 video content in the iOS YouTube app.</p>
  <p><strong>DontEatMyContent preferences</strong> are available in the <strong>YouTube settings</strong>.</p>
  <p>Source code and additional information are available <a href="https://github.com/therealFoxster/DontEatMyContent">in therealFoxster's GitHub repository</a>.</p>
</details>

<details>
  <summary>YTABConfig</summary>
  <p>YTABConfig is a tweak developed by <a href="https://github.com/PoomSmart">PoomSmart</a> that configures A/B settings in the iOS YouTube app.</p>
  <p><strong>YTABConfig preferences</strong> are available in the <strong>YouTube settings</strong>.</p>
  <p>Source code and additional information are available <a href="https://github.com/PoomSmart/YTABConfig">in PoomSmart's GitHub repository</a>.</p>
</details>

<details>
  <summary>YTIcons</summary>
  <p>YTIcons is a tweak developed by <a href="https://github.com/PoomSmart">PoomSmart</a> that displays all usable icons in the iOS YouTube app.</p>
  <p><strong>YTIcons</strong> are available in the <strong>YouTube settings</strong>.</p>
  <p>Source code and additional information are available <a href="https://github.com/PoomSmart/YTIcons">in PoomSmart's GitHub repository</a>.</p>
</details>

<details>
  <summary>YTweaks</summary>
  <p>YTweaks is a tweak developed by <a href="https://github.com/fosterbarnes">fosterbarnes</a> that adds a few extra settings like "Fullscreen to Right" and "Fullscreen to Left"</p>
  <p><strong>YTweaks</strong> preferences are available in the <strong>YouTube settings</strong>.</p>
  <p>Source code and additional information are available <a href="https://github.com/fosterbarnes/YTweaks">in fosterbarnes's GitHub repository</a>.</p>
</details>

<details>
  <summary>YouGroupSettings</summary>
  <p>YouGroupSettings is a tweak developed by <a href="https://github.com/PoomSmart">PoomSmart</a> that allows custom settings (made by tweaks) to be displayed when the grouped settings experiment is active. Forked by <a href="https://github.com/FosterBarnes">FosterBarnes</a> to support YTweaks</p>
  <p>Source code and additional information are available <a href="https://github.com/fosterbarnes/YouGroupSettings">in fosterbarnes's GitHub repository</a>.</p>
</details>

