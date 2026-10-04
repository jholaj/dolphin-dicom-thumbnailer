# dolphin-dicom-thumbnailer

DICOM thumbnails in Dolphin, rendered with dcm2img from DCMTK. Tested with KDE Frameworks 6.24.

## Install

1. Install DCMTK

   ```sh
   sudo apt install dcmtk
   ```

2. Copy the thumbnailer

   ```sh
   mkdir -p ~/.local/share/thumbnailers
   cp dicom.thumbnailer ~/.local/share/thumbnailers/
   ```

3. In Dolphin open Settings, Configure Dolphin, Interface, Previews and check DICOM image

4. Close all Dolphin windows and start it again
