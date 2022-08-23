# MyCloverThemes
A simple script to download my uploaded Clover themes from https://sourceforge.net/p/cloverefiboot/themes.

### How to Use:
1. Clone the repository with: `git clone https://github.com/avinashperera-ops/MyCloverThemes.git`
2. Run the script:
<br>`cd MyCloverThemes`
<br>`chmod +x MyCloverThemes.sh`
<br>`./MyCloverThemes.sh`

All downloaded themes are placed on <b>~/Desktop/themes</b>, move your choosen theme to <b>/EFI/CLOVER/themes</b>.
<br>Then activate it from <b>config.plist > GUI > Theme</b> or using Terminal: $ <b>sudo nvram Clover.Theme="Name"</b>.