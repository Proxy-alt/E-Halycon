# E-Halcyon

![The Mercury Workshop logo](./static/img/mercury.png)

## Defog Your Chromebook

E-Halcyon is a bypass for "The Fog," which is Google's mitigation for the unenrollment and downgrading of Chrome OS devices. It allows you to downgrade and bypass enterprise enrollment on Chromebooks, even if they've received the update that patched downgrading and enrollment escape.

E-Halcyon is developed by Mercury Workshop, the same developers behind SH1MMER.

[Defog Me](#instructions)

---

## Instructions:

### Step 1:
First of all, you'll need a Linux PC or VM. **WSL is not guaranteed to work**.

### Step 2:
Now, you'll need to boot into [SH1MMER](https://sh1mmer.me), and press the **Un-Enroll** option. It won't truly unenroll you if you've received the 112 update patching unenrollment and downgrading, but it is still a necessary step for the rest of this. If you've never used SH1MMER before or don't have an image lying around, make sure to follow all the instructions on [sh1mmer.me](https://sh1mmer.me) for unenrollment before proceeding with the rest of the tutorial here.

### Step 3:
Next, you need a version 107 recovery image corresponding to your board, which you can pick up from [chrome100.dev](https://chrome100.dev). Once you've downloaded the right image for your board and have confirmed it's for version 107, unzip it and save it to a safe place. Now open up a terminal and type in the following commands (make sure to replace `/path/to/recovery/image.bin` with the actual path):

