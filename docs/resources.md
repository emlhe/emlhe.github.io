---
layout: page
title: Tools
---

### Visualisation
<table>
  <tr>
    <td>Tool</td>
    <td>Descr</td>
    <td>Data</td>
    <td>Link</td>
  </tr>
  <tr>
    <td>ITK-SNAP</td>
    <td>Visualisation and semi-automatic segmentation</td>
    <td>Nifti</td>
    <td><a href="https://www.itksnap.org/pmwiki/pmwiki.php">ITK-SNAP link</a></td>
  </tr>
  <tr>
    <td>FreeSurfer freeview</td>
    <td>Volumetric and surface visualisation</td>
    <td>Nifti, mgz</td>
    <td><a href="https://surfer.nmr.mgh.harvard.edu/">FreeSurfer link</a></td>
  </tr>
  <tr>
    <td>3D Slicer</td>
    <td>Volumetric visualisation and semi-automatic segmentation</td>
    <td>Nifti</td>
    <td><a href="https://www.slicer.org/">3D Slicer link</a></td>
  </tr>
</table>

### Segmentation
<table>
  <tr>
    <td>Tool</td>
    <td>Descr</td>
    <td>Modality</td>
    <td>Population</td>
    <td>Link</td>
  </tr>
  <tr>
    <td>nnU-Net</td>
    <td>Framework for medical imaging segmentation</td>
    <td>Any modality</td>
    <td>Any population</td>
    <td><a href="https://github.com/MIC-DKFZ/nnUNet">nnU-Net Github</a></td>
  </tr>
  <tr>
    <td>Synthseg</td>
    <td>Method for synthetic brain generation from labels, can be used within TorchIO for the image generation, or FreeSurfer integration for trained models</td>
    <td>Any modality</td>
    <td>Any Population, however FreeSurfer integration does not work well on brains with stroke lesions or distortions</td>
    <td><a href="https://github.com/BBillot/SynthSeg">Synthseg Github</a>, <a href="https://docs.torchio.org/transforms/augmentation.html#randomlabelstoimage">TorchIO RandomLabelToImage</a>, <a href="https://surfer.nmr.mgh.harvard.edu/fswiki/SynthSeg">FreeSurfer Synthseg</a></td>
  </tr>
   <tr>
    <td>Synthstrip</td>
    <td>Skull-stripping for any brain image integration in FreeSurfer</td>
    <td>Any modality</td>
    <td>Any Population, works well on children with stroke or other brain distortions</td>
    <td><a href="https://surfer.nmr.mgh.harvard.edu/docs/synthstrip/">Synthstrip Link</a></td>
  </tr>
  <tr>
    <td>nnInteractive</td>
    <td>3D promptable (points, scribbles, boxes, lasso) segmentation method, available through Napari, 3D-Slicer, ITK-SNAP...</td>
    <td>Any modality</td>
    <td>Any population</td>
    <td><a href="https://github.com/MIC-DKFZ/nnInteractive">nnInteractive GitHub</a></td>
  </tr>
  <tr>
    <td>MoME</td>
    <td>Foundation model for lesion segmentation</td>
    <td>Any modalities</td>
    <td>Mostly adults</td>
    <td><a href="https://github.com/ZhangxinruBIT/MoMELink">MoME Github</a></td>
  </tr>
  <tr>
    <td>Med-SAM</td>
    <td>Foundation model for medical imaging segmentation</td>
    <td>Any modality</td>
    <td>Any population</td>
    <td>Link</td>
  </tr>
</table>

### Morphometry

<table>
  <tr>
    <td>Tool</td>
    <td>Descr</td>
    <td>Modality</td>
    <td>Population</td>
    <td>Link</td>
  </tr>
  <tr>
    <td>FreeSurfer recon-all-clinical</td>
    <td>Surface and volume analysis, cortical surface reconstruction and analysis using synthetic models</td>
    <td>Structural imaging</td>
    <td>Mostly adults</td>
    <td><a href="https://surfer.nmr.mgh.harvard.edu/">FreeSurfer link</a>, <a href="https://surfer.nmr.mgh.harvard.edu/fswiki/recon-all-clinical">recon-all-clinical link</a></td>
  </tr>
  <tr>
    <td>dHCP</td>
    <td>Cortical surface extraction</td>
    <td>T2w, (T1w optional)</td>
    <td>Neonatal</td>
    <td><a href="https://github.com/BioMedIA/dhcp-structural-pipeline/tree/master">dhcp-structural-pipeline Github</a></td>
  </tr>
   <tr>
    <td>SPM12</td>
    <td>Software package for statistical analysis of brain functional imaging</td>
    <td>Functional imaging</td>
    <td>Mostly adult, can be adapted to paediatric brains / brains with stroke</td>
    <td><a href="https://www.fil.ion.ucl.ac.uk/spm/software/spm12/">SPM12 link</a></td>
  </tr>
  <tr>
    <td>CAT12</td>
    <td>Suite of tools for voxel, surface and deformation-based morphometry. Compatible with SPM12.</td>
    <td>T1w</td>
    <td>Mostly adult, can be adapted to paediatric brains / brains with stroke</td>
    <td><a href="https://neuro-jena.github.io/cat12-help/">CAT12 link</a></td>
  </tr>
</table>


