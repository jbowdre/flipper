# Flipper Zero Stuff

A collection of Flipper signals, codes, payloads, playlists, and remotes. 

Most of these files were shamelessly borrowed from [UberGuidoZ's massive repo](https://github.com/UberGuidoZ/Flipper), which is a great one-stop-shop for all things Flipper. But I wanted a trimmed-down set of folders that were ready for direct use on a Flipper device.

So that's what I've assembled here - just the BadUSB, Infrared, NFC, and Sub-GHz files that make sense for direct ingestion into your pocket dolphin's brain. 

I've removed all the various PDFs, images, zips, and associated documentation (though I did preserve the sample `.ps1`, `.bat`, and `.sh` scripts for the BadUSB payloads). I also reorganized the folders to match the layout used by the [Xtreme Firmware](https://github.com/Flipper-XFW/Xtreme-Firmware) (which includes putting the remotes and playlists inside the `subghz` directory). Everything is also nested one level deeper (ex: `subghz/_import/`) to make it safe/easy to drop this over the top of your existing files. The remotes and playlists have been updated to account for that. 

I'll be doing more cleanup on this as I go to remove duplicates and such. But here we are for now.
