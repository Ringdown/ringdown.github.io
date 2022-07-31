# Windows 11

Microsoft heard Kylo Ren talk about killing the past and thought that sounded fun. Yes, this page is full of cynical language.

![Windows 11 Desktop](https://i.pcmag.com/imagery/articles/07jULW1s5eZwbYwAgF4Zhtz-6..v1628259809.jpg)

## What happened?

In true publicly-traded company fasion, Microsoft has decided that Windows 10, the ['last version of Windows'](https://www.theverge.com/2015/5/7/8568473/windows-10-last-version-of-windows) is no longer the final Windows. Now there's Windows 11, which takes the UI of the [rumored Sun Valley update for Windows 10](https://www.windowslatest.com/2021/06/09/microsoft-accidentally-confirms-windows-sun-valley-update/) and mashes it together with mostly-arbitrary, macOS-inspired planned obsolescence.

Since it's been a while since a new version of Windows was released (Windows 10 came out in *2015* folks) some of us undoubtedly need a refresher. Microsoft maintains a rolling list of supported Windows versions that it cycles through over time. When Windows 10 came out, Windows XP reached End-of-life the next year. Windows Vista soon followed, and most recently in 2020 went Windows 7. Windows 8 and 8.1 have been slated to faze out in January of 2023 (not that anyone really *uses* either at this point), and when Windows 11 was announced, it came with the death toll for Windows 10 of October 14, 2025. Since Windows 11 is only compatible with a small number of the devices currently on Windows 10, this death toll will come with a huge increase of unsupported (and unsafe) devices out in the wild.

While 2025 does seem a while away, I'd like to remind you that COVID started over two *years* ago at this point. We are one pandemic plus 6 months from Windows 10's demise.

## What is compatible with Windows 11?

The easy answer is anything that runs Windows 11 out of the box is a safe bet to go on. That being said, there are lots of PCs out there that can run Windows 11, and you may want to know if you have one.

There are a lot of things people talk about, but it boils down to 
[three](https://docs.microsoft.com/en-us/windows-hardware/design/minimum/supported/windows-11-supported-amd-processors) 
[different](https://docs.microsoft.com/en-us/windows-hardware/design/minimum/supported/windows-11-supported-intel-processors) 
[lists](https://docs.microsoft.com/en-us/windows-hardware/design/minimum/supported/windows-11-supported-qualcomm-processors) 
of processors that have been passed Microsoft's stability tests, and are therefore worthy of being kept out of the landfills. The list totals just under 1,000 processors as of August 2022, out of which less than half are ones you'll find in standard desktops and laptops.

>If you are wondering about a good way to tell if the processor is in the list, the general rule is anything newer than about 2018 stands a good chance of being there, but there are exceptions both ways, so it's important to cross-reference if the device isn't already running Windows 11.

>When it comes to the most common CPUs, here are some more specific rules you can follow:

>>For Intel, any Core i3, i5, i7, or i9 processor from 8th Gen and up. Celeron, Pentium, and Atom are safest on the 5000 and 6000 generations.

>>For AMD, any Ryzen CPU from the 3000 series and up is probably on the list. Exeptions include the Ryzen 5 2600 and Ryzen 7 2700, along with their E, X, and PRO variants.

## What's this talk about TPM?

Well if you're PC already has Windows 11 on it, this doesn't matter, as it's already doing what it needs to.

In summary, there's a little chip that's been getting put on (most) motherboards for quite a few years now that holds security keys. It's a very powerful security feature, so it has become a requirement for running Windows 11. The reason it's talked about so much is that older computers that *can* run Windows 11 may be unable to install or update to it because the TPM chip was disabled by default, so for some users wanting to run Windows 11, it becomes necessary to reconfigure the computer's [UEFI](https://en.wikipedia.org/wiki/UEFI) to enable to TPM functionality, which can be a little intimidating for the average user.