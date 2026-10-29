---
layout: post
title: "How to clean up photos and videos on a USB drive or SSD from your iPhone"
description: "Plug a flash drive or SSD into your iPhone and go through its photos and videos without a computer: the adapter and format you need, and how to delete what you do not."
lang: en
ref: external-disk
app: limina
image: /assets/img/limina/en-disk.jpg
cta: "Plug in the drive and go through it with the same swipes as your library: all of it or one folder, with the longest videos and repeated photos first."
permalink: /en/blog/clean-usb-ssd-from-iphone/
---

Moving photos to a drive to free up your iPhone works… until the drive fills
up with the same things: bursts, videos nobody will watch again, and copies of
copies. You do not need a computer to clean it up. Since iPhone 15, with
USB-C, the drive plugs straight in, and an iPhone with Lightning works too
with an adapter.

## 1. What you need

- **iPhone with USB-C** (iPhone 15 and later): plug the flash drive or SSD
  into the charging port, directly or with a USB-C cable.
- **iPhone with Lightning**: you need Apple's **Lightning to USB 3 Camera
  Adapter**.
- **Spinning hard drives**: they often need more power than the iPhone
  supplies. With USB-C, use a powered USB hub. With Lightning, plug the USB 3
  adapter into a charger.

The drive must have **a single partition** and one of these formats: APFS,
APFS (encrypted), macOS Extended (HFS+), exFAT, FAT32 or FAT.

<p class="note">If your drive uses NTFS, the usual Windows format, it is not
on Apple's list. exFAT works on iPhone, Mac and Windows alike. Reformatting
erases the whole drive, though, so copy its contents somewhere else first.</p>

## 2. Open it in Files

Open the **Files** app, tap **Browse**, then tap the drive's name below
**Locations**. If you do not see Locations, tap Browse again.

From there you can open each photo or video, sort a folder by size, and delete
what you do not want by touching and holding it.

<p class="note">Depending on the drive, what you delete may go to its Trash or
disappear for good. If there is anything you cannot afford to lose, copy it
somewhere else first.</p>

## 3. Where Files falls short

Files is fine for moving things around, but not for going through thousands
of photos:

- It shows file names and small thumbnails, not the photo full screen with its
  date and size.
- It sorts by size one folder at a time, not across the whole drive.
- It does not tell you which photos are near-identical or copies of another.

## The shortcut: Limina

[Limina](https://apps.apple.com/app/id6804942727) is an app I made for
cleaning up your library with a swipe, and it reads external drives too. In
**External disk** you choose the drive, all of it or just one folder, and go
through it with the same swipes: one way to keep, the other to delete.

- **Photos**: the oldest first.
- **Videos**: the longest first, which is where the gigabytes are.
- **Similar**: near-identical shots and copies of the same photo, grouped so
  you keep just one.
- **Biggest files**: photos and videos, the biggest first.

<figure class="shots wide">
  <img src="/assets/img/limina/en-disk.jpg" width="800" height="660" loading="lazy" alt="Limina on an iPad with an SSD named Travel SSD: 47 files, a notice that the disk has no Trash, and the Photos, Videos, Similar and Biggest files modes">
  <figcaption>An SSD plugged into an iPad: its modes, and the notice that this disk has no Trash.</figcaption>
</figure>

Before deleting, it tells you where things will go: to the drive's Trash or,
if the drive has none, that they cannot be recovered. If you unplug it
halfway, everything you marked stays marked. And **Forget Disk** only makes
Limina stop reading it: nothing on the drive is deleted.

It all happens on your iPhone or iPad: no account and nothing uploaded
anywhere. The external disk is part of Limina Pro.
