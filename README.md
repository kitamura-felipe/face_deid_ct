# face_deid_ct
Function to de-identify the face of patients in head CTs


# Drown Volume Python Function

The `drown_volume` function is a Python function designed to process DICOM files from a specified directory. The function performs several operations including binarization, retrieving the largest connected component, dilation, and applying a mask. Following these operations, random values are applied to the dilated volume based on a unique values list which is obtained from the masked volume.

## Usage

```python
drown_volume(in_path, out_path=None, replacer='face')

