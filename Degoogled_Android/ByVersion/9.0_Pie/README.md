
***

# DeGoogled Android phone VM

## DeGoogled Android by version

### Android 9.0 (Pie)

| ![Android logo](/DeGoogled_Android/ByVersion/9.0_Pie/Graphics/Logo/Android_Logo_(2014).svg)
|---|
| Android logo from 2014 to 2019 |

| ![Android Pie logo](/DeGoogled_Android/ByVersion/9.0_Pie/Graphics/Logo/Android_P_logo.svg) |
|---|
| Android Pie logo |

| ![Screenshot unavailable](/DeGoogled_Android/ByVersion/9.0_Pie/Graphics/NOMEDIA) |
|---|
| Screenshot of Android 9.0 running virtualized |

I have an image somewhere, but I will try to virtualize it again sometime soon.

This version is still being DeGoogled, it is the last version of Android that Android x86 currently supports (I am a bit worried, as there hasn't been any activity from them in a little over 2 years) this is also the last Android version to be named after a delicacy, with Android 10 ending the tradition.

As of 2022, March 7th, the system has been unsupported. This rapid drop of support for Android is highly worrying, and this project now has a higher priority.

| Info | Condition |
|---|---|
| **Priority level:** | _extremely high (last Android x86 release, imminent ending support)_ |
| **Status:** | _Guide incomplete_ |

#### System requirements

The system requirements for Android Pie are moderate, it requires a mid-range computer from 2015 or later to virtualize it.

These requirements are not yet verified

| System | Requirement |
|---|---|
| RAM | 2048 megabytes (2 GiB) (4096 (4 GiB) to 8192 (8 GiB) megabytes recommended) |
| Disk space | 10000 megabytes (10 gigabytes) recommended: 32000 megabytes (32 gigabytes) or more, (possible maximum of 2048 gigabytes (2 terabytes)) |
| Processor | Unknown, guess: 1 core, 1.3 GHz (recommended: 2-4 cores, 1.8 GHz) |
| Touchscreen | Highly recommended, not required for some functions |
| Screen resolution | Unknown, at least 1280x720, recommended: 1920x1280 or higher, possible maximum 4320x2160 |
| Network | May be required for installation |
| Bitsize | 64 bit |

#### Loading APKs

No information available.

#### Oracle VM VirtualBox

VirtualBox requires the following configurations:

| Configuration name | Condition |
|---|---|
| Paravirtualization interface (System/Acceleration) | `KVM` |
| Video Memory (Display/Screen) | `128 megabytes (minimum)` |
| Graphics Controller (Display/Screen) | `VBoxSVGA` |
| Other | `Unknown/unlisted` |

The graphics controller requirement will result in the warning `invalid settings detected` please ignore this and proceed. It is a false warning.

#### QEMU

No information available.

#### VMWare

No information available.

#### Hyper-V

No information available.

#### Other

Further DeGoogle instructions are unavailable.

**Legend:**

_Hover over these links to see their definition, click them to read more (Wikipedia links)_

| Legend |
|---|
| [![RC](/Graphics/RC/RC.svg)](https://en.wikipedia.org/wiki/Software_release_life_cycle#Release_candidate "Release Candidate") |
| [![RC1](/Graphics/RC1/RC1.svg)](https://en.wikipedia.org/wiki/Software_release_life_cycle#Release_candidate "Release Candidate 1") |
| [![RC2](/Graphics/RC2/RC2.svg)](https://en.wikipedia.org/wiki/Software_release_life_cycle#Release_candidate "Release Candidate 2") |
| [![R1](/Graphics/R1/R1.svg)](https://en.wikipedia.org/wiki/Software_release_life_cycle#Release "Release 1") |
| [![R2](/Graphics/R2/R2.svg)](https://en.wikipedia.org/wiki/Software_release_life_cycle#Release "Release 2") |
| [![OSDN](/Graphics/OSDN/OSDN.svg)](https://en.wikipedia.org/wiki/OSDN "OSDN.net (Open Source Developers Network)") |
| [![x86](/Graphics/x86/x86.svg)](https://en.wikipedia.org/wiki/32-bit_computing "x86 (32 bit)") |
| [![x64](/Graphics/x64/x64.svg)](https://en.wikipedia.org/wiki/64-bit_computing "x64 (64 bit)") |

**Download links:**

| Provider | Version |
|---|---|
| Android x86 9.0rc1 (404 not found) | ![9.0-rc1](https://osdn.net/projects/android-x86/) |
| Android x86 9.0rc2 (404 not found) | ![9.0-rc2](https://osdn.net/projects/android-x86/) |
| Android x86 9.0r1 (404 not found) | ![9.0-r1](https://osdn.net/projects/android-x86/) |
| Android x86 9.0r2 (via osdn) | ![9.0-r2](https://osdn.net/projects/android-x86/releases/71931) |
<!-- | Android x86 (via archive.org) | ![Many]() | !-->

**Release notes**

| Android x86 link | Android version |
|---|---|
| [Releasenote-9.0-rc1](https://www.android-x86.org/releases/releasenote-9-0-rc1.html) | 9.0-rc1 |
| [Releasenote-9.0-rc2](https://www.android-x86.org/releases/releasenote-9-0-rc2.html) | 9.0-rc2 |
| [Releasenote-9.0-r1](https://www.android-x86.org/releases/releasenote-9-0-r1.html) | 9.0-r1 |
| [Releasenote-9.0-r2](https://www.android-x86.org/releases/releasenote-9-0-r2.html) | 9.0-r2 |

##### Videos that helped me

**#1 resource**

[![Android 9.0 VirtualBox tutorial](/DeGoogled_Android/ByVersion/9.0_Pie/Graphics/Videos/Thumbnails/Android9VirtualBox6.1_Video1_Thumbnail1.jpg)](https://www.youtube.com/watch?v=137jBpJniNs "Android 9.0 in VirtualBox 6.1 by LinuxLeech - YouTube")

**WARNING:** `YouTube link` No other viable alternatives found at the moment. Proceed with caution.

I was able to successfully get an Android virtual machine running through this video guide in the past, managed to install most of my apps, but was unable to actually trick Google into thinking it was an Android device, thus I couldn't get my downloaded apps such as Minecraft or Plants vs. Zombies 2 on it. I still managed to back up most of my phone at the time. This tutorial has worked for me thrice now, twice with Android 9 (Pie) and once with Android 2.3 (Gingerbread)

**Notes:**

1. VirtualBox may claim that there are `invalid settings detected` but you can ignore this, and continue to boot the virtual machine normally.

2. For some reason, the disk image I had caused the device to think it had double the space (I gave it 32 or 64 gigabytes, it reported 64 or 128 gigabytes)

3. Android 5.0 and up are 64 bit operating systems. Despite the name `Android x86` this is not a 32 bit Android release.

***

### File info

<details open><summary><p lang="en"><b><u>Click/tap here to expand/collapse this section</u></b></p></summary>

**File type:** `Markdown (*.md *.mkd *.mdown *.markdown)`

**File version:** `2 (2022, Wednesday, August 24th at 5:58 pm PST)`

**Line count (including blank lines and compiler line):** `217`

**Current article language:** `English (EN_USA)` / `Markdown (CommonMark)` / `HTML5 (HyperText Markup Language 5.3)`

**Encoding:** `UTF-8 (Emoji 12.0 or higher recommended)`

**All times are UTC-7 (PDT/Pacific Time)** `(Please also account for DST (Daylight Savings Time) for older/newer entries up until it is abolished/no longer followed)`

_Note that on 2022, Sunday, March 13th at 2:00 am PST, the time jumped ahead 1 hour to 3:00 am._

**You may need special rendering support for the `<details>` HTML tag being used in this document**

</details>

***

## File history

<details><summary><p lang="en"><b>Click/tap here to expand/collapse the file history section for this project</b></p></summary>

<details><summary><p lang="en"><b>Version 1 (2022, Wednesday, August 24th at 5:31 pm PST)</b></p></summary>

**This version was made by:** [`@seanpm2001`](https://github.com/seanpm2001/)

**View this version separately:** [`Click/tap here`](/DeGoogled_Android/ByVersion/9.0_Pie/!OldVersions/README/English/USA/1/1-100/README_V1.md)

> Changes:

- [x] Started the file
- [x] Added the `title` section
- [x] Added the `System requirements` section
- [x] Added the `Loading APKs` section
- [x] Added the `Oracle VM VirtualBox` section
- [x] Added the `QEMU` section
- [x] Added the `VMWare` section
- [x] Added the `Hyper-V` section
- [x] Added the `Other` section
- - [x] Added the `Legend` subsection
- - [x] Added the `Download links` subsection
- - [x] Added the `Release notes` subsection
- - [x] Added the `Videos that helped me` subsection
- [x] Added the `file info` section
- [x] Added the `file history` section
- [ ] No other changes in version 1

</details>

<details><summary><p lang="en"><b>Version 2 (2022, Wednesday, August 24th at 5:58 pm PST)</b></p></summary>

**This version was made by:** [`@seanpm2001`](https://github.com/seanpm2001/)

**View this version separately:** [`Click/tap here`](/DeGoogled_Android/ByVersion/9.0_Pie/!OldVersions/README/English/USA/1/1-100/README_V2.md)

> Changes:

Side comment: The Internet Archive was down at the time, so I couldn't retrieve some mirror links.

- [x] Started the file
- [x] Updated the `title` section
- [x] Updated the `Other` section
- - [x] Updated the `Legend` subsection
- - - [x] Fixed several links
- - [x] Updated the `Download links` subsection
- - [x] Updated the `Videos that helped me` subsection
- [x] Updated the `file info` section
- [x] Updated the `file history` section
- [ ] No other changes in version 2

</details>

</details>

***
