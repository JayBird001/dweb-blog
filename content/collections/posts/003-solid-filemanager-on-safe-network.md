---
slug: 003-solid-filemanager-on-safe-network
title: 'How to use Solid Filemanager on the SAFE Network'
date: 2019-08-19
author: JayBird
headerhtml: "<div style='text-align: center; font-weight: bold; font-size: +4em;'><img src='/images/safegit-logo-8a31ccf66202d8209de7345c105da82070b22876_2_1380x580.png' description='safegit logo' style='text-flow: left; '>Filemanager</div>"
---

# Solid Filemanager on SAFE

Hello there, brave explorers of the new world! I am about to take you through a basic look at the functionality of the Solid Filemanager which is now working on both the SAFE Browser on their Alpha 2 network and Solid, thanks to some wizardry from [happybeing](https://safenetforum.org/u/happybeing), the gracious host of this blog. I am [Jay-Bird](https://safenetforum.org/u/JayBird) on the forum, in case you've any questions about the whole process described here.

It was my first time installing and using the SAFE Browser from the people building the SAFE Network, first time properly digging into Tim Berners Lee's Solid, first time making a blog, first time consciously using Markdown, first time being exposed to a myriad of bizarre and wonderful computery words in fact... So many abbreviations, how do you all cope. What I'm basically saying is that if I can install and run the SAFE browser, use the Solid Filemanager to check out the bones of the various SAFE sites on there, and then make a blog on the dWeb about it, a monkey typing full-speed on a typewriter going down a steep hill on a unicycle could probably manage it. Anyway, let's get into it.

### Step 1

Install and get going on the SAFE Browser. This is explained clearly [here](https://safenetforum.org/t/the-safe-browser/28031), I got it going on Ubuntu and on Mac, and reports from Windows users seem positive too. If you've any problems just ask on the forum, it's a responsive and friendly place.

### Step 2

Play around on the various [SAFE sites](https://safenetforum.org/t/list-of-websites-safesites-webids-community-resources/25168/101), there are cats, punk videos, wallet mockups, racer games and prototype social networks bubbling away.

### Step 3

Remember to enable experimental APIs in the top right before using the filemanager like so:

<img src="https://previews.dropbox.com/p/thumb/AAgkwI3ctUTB4F_WFD6n27jSfmKu_05K5qjNXuPS_Cw8vca0mTLqLg39VDYYNZxeRP63UPaVrXhJS2aoJgZ8Pn3kQQVXwG8C2P8ncm0lWkwKA7zimrfCFQmlXukQyD1E02HWAuNP645EGO_kbkAk97Fzhs4_EAd89hGp1BboWYjcJWVObqLCrMy6g2_z16UXOAwTI4TbMPaCNkzVFHyjRsN3o1CtHOqIG3Di5njDVuFili4v20Gyh6l89TCMk5ITHwgBixzOhBHczsdvvNDKiWCtV8lFqGKnVVwXNsJmbuXTm5Tl8LTogdix3pF-THGDRAI3XdszrlBDboqVWlvqsRn4kP_6eP6y21N2NI5FswbXHw/p.png?fv_content=true&size_mode=5" alt="experimental API" width="720" height="450"/>

### Step 4

You are now ready to access the [filemanager](safe://solid-filemanager). Either click on this link with the browser open, or copy and paste safe://solid-filemanager into a new tab. A window will pop up after a pause asking you to open the directory of whatever site you want to look at, which looks like this:

<img src="https://previews.dropbox.com/p/thumb/AAgLyvhxQywP2daLhPM-uPiQtZx6v74Ppdgce7ECLaNyw_XpLqA8cmYGE37HF4h7n0kT8X44Y2jIovVlNHi719ISbTVMsW2wGMXc0uGvylLBFv4QwN_pUQROGFRJSZIiL-UJZi2nrLXanpYZZY6Yir_6gjHGysWEcUxX8g9qFcyoP2d0DtVzj1Ggv9WVqkWLumNvCFncmGGhyQ6WXeL2v5BP4m7xFCb0AJIEbrwbUdyvXcVkjxlT6w654lBEU5bWstNoG9B3gmGfL-hmiM1Ey81-RFGXGitEe-bPGpByWZVR4J1h1otZKNvM-o2rOfpjXUi9o6HgkNWJ7lpuHmmYvcQdN8XjhhfBxTwwRbAqkAQPFA/p.png?fv_content=true&size_mode=5" width="720" height="450"/>

### Step 5

If you've gotten to this point you're ready to inspect the structure of the site you've selected. A double-click on a file opens it up in a simple editor, any further directory can be inspected, and you can see basically everything that's going on under the hood. After checking out dweb-blog above you might like to go onto [JAMS](safe://jams.demo), the flagship music player on SAFE.

<img src="https://previews.dropbox.com/p/thumb/AAgKs1xa9ZpedTDxOf6sa809KNTy9eufhH9WmL6aY5ZTAgDQzAKuxf2k5BvgLc4iPRiznrrhY-ZwnYQH41xJBvi9smrGz6B8ZtclzEqm3mOcymMGWo-OPJsK5b1InaZKmfcR2-VCv33HkORRFLEdHORVQmadq1ggM4smigM-8pQXt2MIE9ta3G_RAepfgDRsMdfVPvpSWwmcHPH0e8D65lS_wM-Mf01O3wJbfOkv1syVD7JsA2q3Y5Wf_TuU9r1lbOx9uLwVHIN8cxeBbYbsf8_-kGA05xF-YiAoiIlo8gNL4xZBkNIvsZgmySFcST2Z7kCtDclbjE_nFhrKGEjlhbTvNsJNO79nCEcZ5QMCXfzMmA/p.png?fv_content=true&size_mode=5" width="720" height="450"/>

### Step 6

Have a nice think for yourself about what kind of effects on security and creativity a service like this might have if it became standard practice to have your site fully open, auditable, and copyable. And of course if you're a programmer and would like to see this become a reality faster, get in touch with [happybeing](https://safenetforum.org/u/happybeing) and get involved. He is at the moment a one-man bridge between projects SAFE and Solid, and was very helpful and responsive with me at all stages of getting this blog done showcasing his hard work bringing Solid and SAFE closer together.