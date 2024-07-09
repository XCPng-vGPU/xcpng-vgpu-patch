# XCP-ng vGPU Patch

This repository contains a script to apply a patch on XCP-ng hypervisor versions 8.2 and 8.3 to enable vGPU support. The script checks the XCP-ng version and applies the appropriate patch.

## Disclaimer
- This script is provided "as is" without any warranty of any kind.
- Use at your own risk. The authors and distributors of this script are not responsible for any damage or issues that may arise from using it.
- No support will be provided for this script.

## One-liner to Download and Run the Script
To quickly download and run the script from this repository, use the following in the shell on the XCP-ng host:

```sh
bash <(curl -s https://raw.githubusercontent.com/XCPng-vGPU/xcpng-vgpu-patch/patch.sh)
```

## Notes
- This script only supports XCP-ng versions 8.2 and 8.3.
- If the script detects an unsupported version, it will terminate with an error message.

###### Any use, copying, distribution, modification, or redistribution of this software is strictly prohibited. This software is provided "as is," without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose, and noninfringement. In no event shall the authors be liable for any claim, damages, or other liability, whether in an action of contract, tort, or otherwise, arising from, out of, or in connection with the software or the use or other dealings in the software. Users of this software should not expect or request any form of support, assistance, or any other form of service as none will be provided under any circumstances.
