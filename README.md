# TWRP-PBRP-Builder
# TWRP/PBRP Action Builder
Compile your first custom recovery from Recovery Recovery Project using Github Action.

# How to Use
1. Fork this repository.

2. Go to `Action` tab > `All workflows` > `Recovery - Build` > `Run workflow`, then fill all the required information:
 * Recovery Name (TWRP, PBRP)
 * Manifest Url (TWRP OR PBRP Minimal Manifest url)
 * Manifest Branch (android-12.1,twrp-12.1)
 * Device Tree (Your device tree repository link)
 * Device Tree Branch (Your device tree repository branch)
 * Device Name (Your device codename)
 * Device Path (device/brand/codename)
 * Build Target (boot, recovery, vendorboot)

 # Note
 * Initially, it only have two default choices for manifest branch branch: android-12.1, twrp-12.1. If there's more to it, feel free to modify the .yml configurations.
Credits:
https://github.com/carlodandan/OrangeFox-Action-Builder
for the wonderful git repo
TWRP AND PBRP
And to all others I forgot to mention .
