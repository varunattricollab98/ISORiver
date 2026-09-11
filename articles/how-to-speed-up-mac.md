# How to Speed Up Mac: 12 Easy Fixes for a Slow Mac (2026)

> STATUS: Being published (article #1) | Category: Mac OS | Focus KW: how to speed up mac
> Slug: how-to-speed-up-mac
> SEO Title: How to Speed Up Mac: 12 Easy Fixes for a Slow Mac (2026)
> Meta Description: Is your Mac running slow? Here's how to speed up Mac performance with 12 tested fixes — clear memory, cache, startup items, and more. Simple, real results.
> Featured image alt: A slow Mac being sped up — Activity Monitor open on macOS showing CPU and memory usage

---

My MacBook was fine for about three years. Then one morning it took almost a full minute just to open Safari, the spinning beach ball showed up every time I switched apps, and typing had this weird little lag. Sound familiar?

Here's the good news — a slow Mac is almost never a "your Mac is dying" situation. Nine times out of ten it's clutter: too many things running in the background, a drive that's nearly full, or a cache that's ballooned out of control. I've fixed this on my own machine and on a few friends' Macs too, and the same handful of steps keep working.

So let me walk you through exactly what I do, in the order I actually do it. No jargon dumps, no "buy this cleaner app" nonsense. Just the stuff that works. Either way, I'll show you how to speed up Mac performance step by step.

> **Quick Answer:** To speed up a slow Mac, open Activity Monitor to find apps eating your CPU and memory, restart your Mac, remove unnecessary startup items, free up storage so at least 10–15% of your drive is empty, clear caches, and quit heavy background apps. If it's still slow after that, check your battery health and, as a last resort, reinstall macOS. Most Macs feel noticeably faster after the first four steps.

[SCREENSHOT 1: Activity Monitor CPU tab. Alt: How to speed up Mac using Activity Monitor to check CPU usage]

## Why is my Mac so slow?
Before you start fixing, it helps to know what you're fixing. In my experience, a slow Mac usually comes down to one (or a mix) of these:
- **Not enough free storage.** macOS needs breathing room. Once your drive gets past ~85–90% full, everything drags.
- **Too many background apps.** Stuff you installed months ago is still running at login and quietly hogging RAM.
- **A full cache.** Temporary files pile up and stop being helpful.
- **An old spinning hard drive** (on older Macs) instead of an SSD.
- **A recent macOS update.** After a big update like macOS Tahoe, Spotlight re-indexes your whole drive, which can spike CPU usage for hours. If you just updated and your Mac feels sluggish, give it a bit; it often sorts itself out.

Okay, enough theory. Let's fix it.

## 1. See what's actually slowing it down (Activity Monitor)
Don't guess — look. Activity Monitor is the built-in tool that shows you exactly which apps are eating your Mac alive.
- **Step 1:** Press Command + Space, type Activity Monitor, and hit Return.
- **Step 2:** Click the CPU tab. Click the % CPU column header to sort from highest to lowest.
- **Step 3:** Look at the top of the list. Anything sitting up there using a big chunk of CPU while you're not actively using it is a suspect.
- **Step 4:** Now click the Memory tab and do the same. This shows you what's hogging your RAM.

[SCREENSHOT 2: Activity Monitor Memory tab sorted. Alt: Activity Monitor Memory tab sorted to show which apps use the most RAM on Mac]

If you spot an app you don't even need running, select it and click the ✕ button at the top to quit it. We'll deal with stopping them permanently in Step 3.

> **Tip:** Web browsers and photo/video apps are almost always at the top. That's normal — just don't leave 40 tabs open (guilty).

## 2. Restart your Mac (and install updates)
I know, I know — "have you tried turning it off and on again." But honestly? A restart clears out temporary junk, frees up memory, and closes stuck processes. If your Mac has been on for two weeks straight, this alone can make a real difference.
- **Step 1:** Click the Apple menu () in the top-left corner.
- **Step 2:** Choose Restart. Uncheck "Reopen windows when logging back in" so you get a clean start.

While you're at it, check for updates — Apple regularly patches performance bugs. (optional external link: support.apple.com — new tab ON)
- **Step 3:** Go to Apple menu > System Settings > General > Software Update.
- **Step 4:** If an update is waiting, install it.

[SCREENSHOT 3: Software Update screen. Alt: macOS Software Update screen under System Settings General]

> **Heads up:** If you just installed a major update and things got slower, that's usually temporary re-indexing. Let it finish overnight before you panic.

## 3. Cut down your startup items
Every app that launches when you log in is stealing a little speed at the exact moment you want your Mac to be quick. Trimming this list is one of the biggest, fastest wins.
- **Step 1:** Open Apple menu > System Settings > General > Login Items & Extensions.
- **Step 2:** Under Open at Login, select any apps you don't need starting automatically and click the – (minus) button.
- **Step 3:** Scroll down to Allow in Background. Toggle off anything you don't recognize or don't need running constantly.

[SCREENSHOT 4: Login Items settings. Alt: Mac Login Items settings showing apps that open at startup]

Be a little careful here — don't remove things tied to hardware (like trackpad or audio drivers). But that random app you tried once? Gone.

## 4. Free up storage space
This is the big one. A nearly-full drive is the number one reason Macs slow to a crawl. Aim to keep at least 10–15% of your drive free.
- **Step 1:** Go to Apple menu > System Settings > General > Storage.
- **Step 2:** Wait a few seconds for the bar to load. It breaks down what's using your space.
- **Step 3:** Use the built-in recommendations: Empty Trash Automatically and Review Files.

[SCREENSHOT 5: Storage settings. Alt: Mac Storage settings showing disk space breakdown and cleanup recommendations]

- **Step 4:** Empty the Trash for real — right-click the Trash in your Dock and choose Empty Trash.

Big space hogs to check: old downloads, duplicate photos, iOS device backups, and video files you already uploaded somewhere.

## 5. Clear cache and temporary files
Caches are supposed to speed things up, but over time they bloat and do the opposite.
- **Step 1:** In Finder, click the Go menu while holding the Option key, then choose Library.
- **Step 2:** Open the Caches folder.
- **Step 3:** You can safely delete the contents inside these folders (not the Caches folder itself). Drag them to Trash.

[SCREENSHOT 6: Library Caches folder. Alt: Mac Library Caches folder in Finder showing app cache files]

- **Step 4:** Empty the Trash.

> **Safety note:** Only clear the contents of Caches. Don't delete random system folders. macOS rebuilds caches on its own.

## 6. Force quit apps that are stuck
Sometimes one frozen app drags the whole system down. Force quitting it is quick and harmless.
- **Step 1:** Press Command + Option + Esc to open the Force Quit Applications window.
- **Step 2:** Select the app that's frozen (often says "not responding").
- **Step 3:** Click Force Quit, then confirm.

[SCREENSHOT 7: Force Quit window. Alt: Force Quit Applications window on Mac showing a frozen app]

That's it. Reopen the app fresh and it usually behaves.

## 7. Turn off heavy visual effects
Those smooth animations look nice, but on older Macs they cost real performance.
- **Step 1:** Go to System Settings > Accessibility > Display.
- **Step 2:** Turn on Reduce Motion and Reduce Transparency.

Your Mac will feel snappier almost immediately.

## 8. Ease the memory pressure
RAM is where your Mac keeps whatever it's actively working on. When it fills up, your Mac "swaps" to the slower drive — and everything lags.
- **Step 1:** Open Activity Monitor > Memory tab again.
- **Step 2:** Look at the Memory Pressure graph at the bottom. Green good. Yellow/red = maxed out.

[SCREENSHOT 8: Memory Pressure graph. Alt: Mac Memory Pressure graph in Activity Monitor showing RAM usage]

- **Step 3:** If yellow/red, quit memory-hungry apps, close extra tabs, restart if needed.

You don't need a "RAM cleaner" app — most do more harm than good. Quitting apps + restarting does the same job for free.

## 9. Tame your browser
For most people, the browser is the Mac. And it's usually the biggest single resource hog.
- Close tabs you're not using. Each open tab eats memory.
- Remove extensions you don't need. Safari: Safari > Settings > Extensions. Chrome: three-dot menu > Extensions.
- Clear browsing data now and then.

If your Mac only feels slow while browsing, this section alone might fix everything.

## 10. Check your battery health and power settings
On a MacBook, a worn-out battery can quietly throttle performance to protect itself.
- **Step 1:** Go to System Settings > Battery.
- **Step 2:** Click the info icon next to Battery Health. "Service Recommended" = worn battery may be limiting speed.
- **Step 3:** If plugged in and want max performance, set the energy mode accordingly.

[SCREENSHOT 9: Battery Health. Alt: Mac Battery Health status in System Settings]

## 11. Run basic maintenance
- Restart weekly instead of just closing the lid.
- Keep 15% of your drive free as a habit.
- Uninstall apps you don't use.
- Update macOS and apps when patches come out.

## 12. Last resort: reinstall macOS
If you've tried everything and your Mac is still crawling, a clean reinstall often brings back that "new Mac" feeling. Back up your files first (Time Machine or iCloud).

INTERNAL LINKS (same tab):
- "how to clean install macOS using a USB" → https://isoriver.com/how-to-clean-install-mac-os-using-usb/
- "how to create a bootable macOS USB on Windows" → https://isoriver.com/how-to-create-a-bootable-mac-os-usb-on-windows-pc/

## Slow Mac fixes at a glance
| Fix | Time | Best for |
|-----|------|----------|
| Check Activity Monitor | 2 min | Finding the real culprit |
| Restart + update | 5 min | General sluggishness |
| Trim startup items | 5 min | Slow login / boot |
| Free up storage | 10–20 min | Nearly-full drive |
| Clear cache | 5 min | Bloated temp files |
| Force quit apps | 1 min | One frozen app |
| Reduce visual effects | 2 min | Older Macs |
| Reinstall macOS | 1–2 hours | When nothing else works |

## FAQs
**Why is my Mac so slow all of a sudden?** Usually a full drive, too many background apps, or a recent macOS update still indexing. Open Activity Monitor, free up storage, restart.

**How do I make my MacBook run faster for free?** Everything here is free and built into macOS. Biggest free wins: free up storage, trim startup items, clear caches, restart regularly.

**Does clearing cache speed up a Mac?** It can, especially if caches grew large or your drive is nearly full. Clear the contents of Library Caches. Don't delete unknown system folders.

**How much free storage should a Mac have?** At least 10–15% empty. macOS uses free space for temp files and memory swapping.

**Do I need a Mac cleaner app to speed things up?** No. Most of what they do you can do free with the steps above. Some cleaners even slow things down.

**My Mac got slow right after a macOS update — is that normal?** Yes, temporarily. macOS re-indexes files (Spotlight) after a big update — CPU spikes for a day or so. Leave it overnight.

**Is my Mac slow because it's old?** Maybe, but don't assume that first. Many "old" Macs speed back up after freeing storage + cutting background apps. Else: SSD upgrade or more RAM.

## Final thoughts on how to speed up Mac
A slow Mac is annoying, but it's rarely the end of the road. Start at the top — check Activity Monitor, restart, trim startup items, and free up space — and you'll feel the difference before you even reach the bottom of this list. Most of the time you don't need to spend a rupee or a dollar; you just need to clear out the clutter your Mac's been carrying around.

Try these in order, and if you get all the way to a reinstall, we've got you covered there too. Here's to a Mac that actually keeps up with you.
