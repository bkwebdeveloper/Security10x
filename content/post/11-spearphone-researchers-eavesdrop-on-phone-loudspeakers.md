---
title: "Your Android’s accelerometer could be used to eavesdrop on your calls"
date: 2019-07-23T23:40:50+05:30
draft: false
tags: ["Security10x News"]
---

Just because you don’t give an application access to your microphone doesn’t mean that it can’t listen to you. Researchers have created an attack called [Spearphone](https://arxiv.org/pdf/1907.05972.pdf) that uses the motion sensors in Android phones to listen to phone calls, interactions with your voice assistant, and more.

When you install an Android app, it has to ask your permission if it wants access to your microphone so that it can listen to what you’re saying. However, the researchers discovered a workaround.

Most modern smartphones have accelerometers that are supposed to sense how quickly you’re moving. They’re useful for fitness apps, for example. Android apps don’t need permission to use the phone’s accelerometer, so the researchers used it as a listening device. **The smartphone’s loudspeaker causes the device’s body to vibrate, and they were able to hijack the accelerometer to sample these vibrations.**

**The attack used a combination of signal processing and machine learning to convert the vibration samples into speech.**`

Read the full story on **[NakedSecurity](https://nakedsecurity.sophos.com/2019/07/23/spearphone-researchers-eavesdrop-on-phone-loudspeakers/)**.