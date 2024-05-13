# Topological Validation of GBM Subregion
**Topological validation of imaging-based tumor subregions in isocitrate dehydrogenase–wild type glioblastoma using MRI, pathology, and RNA sequencing.**

### Summary statement
- Identification of the most aggressive cellular tumor portion in contrast-enhancing lesion, and infiltrative tumor portion in non-enhancing lesion using non-invasive imaging can be achieved using physiologic parameters-based MRI tumor habitats based on topological biologic validation with pathologic slides.

### Key results
- Six tumor habitats were correlated: hypervascular, hypovascular cellular, and hypovascular hypocellular habitats for CEL and NEL.
- CT was strongly correlated with hypovascular cellular habitat in CEL (C2, r = 0.238, p =.005).
- IT was strongly correlated with hypovascular cellular habitat in NEL (C5, r = 0.294, p =.017).
- CThypervascular was correlated with hypervascular habitat in NEL (r = 0.195, p = .023).
- CTperinecrotic was correlated with imaging necrosis (r = 0.199, p =.005).
- Astrocyte-like subtypes were positively correlated with IT (r = 0.256, p <.001), while mesenchymal-like subtypes were positively correlated with CTperinecrotic area (r = 0.246, p <.001)

### Citation
- Public data with a comprehensive pathology-molecular map of glioblastoma with en bloc resection is available in the Ivy Glioblastoma Atlas (http://glioblastoma.alleninstitute.org/).
- This provides an en-block specimen, comprehensive pathologic map supplied by pathologists, RNA sequencing, and multiparametric MRI of diffusion-weighted and dynamic susceptibility contrast imaging.

## Dataset
This folder contains co-registered MRI and pathologic slides data.  
There are three subfolders : MRI, MRI_habitat, and Pathology

### MRI
- MRI folder includes Nifti format of contrast-enhanced T1 (_0000.nii) and FLAIR (_0001.nii).  
For example, W1 patient has both W1_0000.nii and W1_0001.nii.

### MRI habitat
- MRI habitat folder includes results of tumor habitat analysis (voxel-wised clustering of ADC and CBV maps) as Nifti format per patient.  
If this file is overlayed to anatomical image files (load as segmentation), the tumor habitats of C1-6 will be shown. 

### Pathology
- Pathology folder includes co-registered pathologic slides per patient as Nifti format.  
If this file is overlayed to anatomical image files (load as segmentation), the co-registered results will be shown. 
- The actual pathologic pictures and slide numbers can be all downloaded in IvyGAP data site (https://glioblastoma.alleninstitute.org/). We do not have rights for uploading or sharing pathologic data.

If you want to request ADC and CBV maps per each patient, please contact jieunp@gmail.com
