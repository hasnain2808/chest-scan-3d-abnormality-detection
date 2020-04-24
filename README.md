# chest-scan-3d-abnormality-detection
1. The 3d chest CT scans are in .tiff per slide<br>
2. There are different number of slides per patient which were normalized to 128 per patient<br>
3. They are used to create a 128*128*128 vector for each patient<br>
4. The scans are then sent to unet model that gives 3d masks as the output<br>
