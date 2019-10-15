# bashFindInPdf
bash script that searches text in all pdfs inside a folder

## Usage
- `findInPdf [folderPath] stringToSearch`

Step by step guide:
- Download the script
if you do not have root permissions:
- `cd <script-folder-path>`
- first time only: `sudo chmod u+x findInPdf`
- `./findInPdf <folderPath> <stringToSearch>`
if you have root permissions, install it in the `/usr/bin` folder:
- `cd <script-folder-path>`
- `sudo mv findInPdf /usr/bin/findInPdf`
- `sudo chmod 755 /usr/bin/findInPdf`
- the script is installed, `cd` into the folder containing pdf files and use the command `findInPdf <searchString>` to search among all the pdf files in the folder
