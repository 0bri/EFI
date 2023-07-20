# EFI

This repository contains various successful Hackintosh builds using OpenCore. Each branch will contain a different hardware setup that is ideal for the configuration. Easily keep up to date with new macOS and OpenCore versions!

### Requirements

- macOS installer created from the OpenCore guide, refer to specific branches in this repository to see which macOS version you should be using
- Extremely basic command line knowledge
- Git installed

### Installation

(This assumes you already have an EFI partition made and mounted, refer to the OpenCore guide for further info)

1. Find which [branch](https://github.com/adverseaction/EFI/branches) you want for your hardware

2. Open Terminal and clone the branch to your EFI directory. We will need to also clear out the EFI folder to be able to download a repository there:
   ``rm -rf /path/to/EFI/``

   `` git clone --branch <branch-name> git@github.com:adverseaction/EFI.git /path/to/EFI ``

### Updating

Now the EFI can easily be updated via command line, with new OpenCore versions and improvements. Simply run ``git pull`` from your EFI directory. **Updating does come with some risk, as I will be making updates for the specific hardware mentioned in each branch's README.**

