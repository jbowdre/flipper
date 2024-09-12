# John's Flipper Zero Stuff

My collection of Flipper signals, codes, payloads, playlists, and remotes.

Most of these files were shamelessly borrowed from [UberGuidoZ's massive repo](https://github.com/UberGuidoZ/Flipper), which is a great one-stop-shop for all things Flipper. But I wanted a trimmed-down set of folders that were ready for direct use on a Flipper device, without all the extra resources that just take up space on a Flipper's SD card.

So that's what I've assembled here - just the BadUSB, Infrared, NFC, and Sub-GHz files that make sense for direct ingestion into my pocket dolphin's brain.

I've removed all the various PDFs, images, zips, and associated documentation (though I did preserve the sample `.ps1`, `.bat`, and `.sh` scripts for the BadUSB payloads). I also reorganized the folders to match the layout used by the [Momentum Firmware](https://github.com/Next-Flip/Momentum-Firmware) (which includes putting the remotes and playlists inside the `subghz` directory).

Everything is also nested one level deeper (ex: `subghz/_import/`) to make it safe/easy to drop this over the top of my existing files. The existing remotes and playlists have been updated to account for that.

And I've added some of my personal captures/remotes/playlists outside of the `_import` folders to make them easier for me to track/find/use (and so that I'll have a backup the next time my SD card takes a dive).
