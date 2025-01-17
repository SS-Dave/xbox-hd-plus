# Installation - XboxHDMI Software
This guide is for the installation of the XboxHDMI software and kernel patch.

## Checklist
- [ ] OpenXenium installed.
  - [ ] Tested and verified that OpenXenium is accessible via network. (Both HTTP and FTP)
- [ ] System is fully working.

### CONTACT SUPPORT IF YOU HAVE ANY QUESTIONS OR CONCERNS!

## Hard Drive Preparation

### Step 1:
Boot console to XeniumOS via the eject button.

![XeniumOS Boot Screen](/manual/images/upgrade/xeniumos.png)

### Step 2:
Download the latest XboxHDMI app release.

[Latest Release](https://github.com/MakeMHz/xbox-hdmi-app/releases/latest)

![FTP BIOS bin file](/manual/images/upgrade/latest_release_hdmi.png)

### Step 3:
Extract the files and FTP over the contents. (Location isn't important, but most people tend to place it inside E:\apps)

### Step 4:
Leave Xbox on and continue to the next section.

## Patching BIOS

### Step 1
Download the latest 'Legacy - XboxHDMI' IPS file for your BIOS of choice.

[BIOS Patches](/patches/README.md#xbox-kernel-patches-legacy---xboxhdmi)

### Step 2
Apply patch to BIOS by following the link to the patching guide for the corresponding BIOS patch. (Due to legal reasons we can not distribute the BIOS files)

![BIOS Guides](/manual/images/upgrade/patches_guide_hdmi.png)

### Step 3
FTP the patched BIOS file over to Xbox. It's recommended to store the BIOS file inside of a folder on the C drive called 'BIOS' for future refrences.

![FTP BIOS bin file](/manual/images/upgrade/ftp_bios.png)

### Step 4
Flash BIOS.

![BIOS Flashing Step 1](/manual/images/upgrade/flash_step1.png)
![BIOS Flashing Step 2](/manual/images/upgrade/flash_step2.png)
![BIOS Flashing Step 3](/manual/images/upgrade/flash_step3.png)
![BIOS Flashing Step 4](/manual/images/upgrade/flash_step4.png)
![BIOS Flashing Step 5](/manual/images/upgrade/flash_step5.png)
![BIOS Flashing Step 6](/manual/images/upgrade/flash_step6.png)
![BIOS Flashing Step 7](/manual/images/upgrade/flash_step7.png)
![BIOS Flashing Step 8](/manual/images/upgrade/flash_step8.png)

### Step 5
Set the newly flashed BIOS as the default BIOS.

![BIOS Flashing Step 9](/manual/images/upgrade/flash_step9.png)
![BIOS Flashing Step 10](/manual/images/upgrade/flash_step10.png)

### Step 6
Ensure that 'Instant Boot' is enabled. This automatically boot the default BIOS on power up.

![BIOS Flashing Step 11](/manual/images/upgrade/flash_step11.png)
![BIOS Flashing Step 12](/manual/images/upgrade/flash_step12.png)
![BIOS Flashing Step 13](/manual/images/upgrade/flash_step13.png)

## Adding Shortcuts
TODO: Add guides for adding launch shortcuts.

## Verification
At this point you can reboot the Xbox. This will boot the patched BIOS.

### Step 1:
Launch the XboxHDMI app. If all went well you should now see the configuration app and text that says the kernel patch version.
![Kernel patch installation verification](/manual/images/Patch-Verification.png)

## All Done
And that's it! Installation of the XboxHDMI kit can now continue.
