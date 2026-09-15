# [Intensity Variance‐Guided Automated Robotic Optical Coherence Tomography System for Ophthalmic Applications](zotero://select/library/items/J6WX68YH)

 **Authors:** Hang Su, Jie Zhang, Maoyuan Qu, Xiru Gao, Hongqin Chen, Congyu Hu, Pengfei Song, Xingchen Ji, Yikai Su
 **Published:** 2026
 **Journal/Conference:** Journal of Biophotonics
**Citekey:** `suIntensityVarianceGuidedAutomated2026`

---
## Abstract
> [!abstract]
>  ```
>  ABSTRACT
            Optical coherence tomography (OCT) enables non‐invasive volumetric retinal imaging. Conventional tabletop and handheld systems rely on skilled operators and patient cooperation. Mobile robot‐assisted OCT (RAOCT) systems can address these challenges, but many depend on complex visual servo modules for low‐latency eye tracking. We present an intensity variance‐guided RAOCT system integrated on a wheeled mobile platform. The system uses one depth camera for coarse eye localization and a single pupil camera for real‐time tracking. By calibrating a lookup table between image variance and distance within the near‐eye region, the pupil camera provides indirect depth estimation for robotic servoing. A motorized reference arm, an electrically tunable lens, and an automated polarization controller further enable image‐quality optimization. Experiments demonstrated 103.50 μm axial and 20.46 μm lateral tracking accuracy. The pupil‐camera response time was 10.53 ms. Automated retinal OCT imaging was achieved, demonstrating the system's potential for point‐of‐care diagnostics in resource‐limited environments.
>  ```

---

%% begin notes %%
## Summary
<!-- claude-summary-start -->
*Pending*
<!-- claude-summary-end -->
%% end notes %%

## Notes & Highlights%% begin obsidian-freeform-notes %%

### Freeform Notes%% end obsidian-freeform-notes %%

### From Zotero

---
> [!note] Key Passage (Page 1)
> Mobile robot-assisted OCT (RAOCT) systems can address these challenges, but many depend on complex visual servo modules for low-latency eye tracking. We present an intensity variance-guided RAOCT system integrated on a wheeled mobile platform.%% begin V326CKAC %%%% end V326CKAC %%

---
> [!info] Methods (Page 1)
> The system uses one depth camera for coarse eye localization and a single pupil camera for real-time tracking. By calibrating a lookup table between image variance and distance within the neareye region, the pupil camera provides indirect depth estimation for robotic servoing.%% begin UXKSEIVW %%%% end UXKSEIVW %%

---
> [!note] Key Passage (Page 2)
> Using retinal OCT B-scan image intensity as the optimization metric,  we automatically adjust these components to enhance image quality.%% begin 6XETDLXE %%%% end 6XETDLXE %%

---
> [!note] Key Passage (Page 2)
> The scanner head has a weight of approximately 5 kg and overall dimensions of 27 × 25 × 17 cm. The system utilizes a collaborative 6-degree-of-freedom robotic arm (UR5, Universal Robots) to precisely track and align the subject during imaging.%% begin YKEUHIZN %%%% end YKEUHIZN %%

---
> [!note] Key Passage (Page 2)
> working distance (WD) of 103 mm.%% begin 2MCUM5KR %%%% end 2MCUM5KR %%

---
> [!note] Key Passage (Page 3)
> As the distance between the scanner and the subject changes, the pupil image alternates between blurred (defocused) and sharp (focused) states, accompanied by variations in the intensity of the LED reflections.%% begin FNIB3VZA %%%% end FNIB3VZA %%

---
> [!note] Key Passage (Page 3)
> Inspired by prior autofocus imaging studies [39], we adopted image variance (VAR) as a metric to characterize the variation of image blur with depth.%% begin LH2KP5CV %%%% end LH2KP5CV %%

---
> [!note] Key Passage (Page 3)
> (x, y) is the coordinate of a pixel in the detected pupil image, I(x, y) is the intensity value at the pixel, and I is the average pixel intensity over the entire ROI.%% begin G3MZS72R %%%% end G3MZS72R %%

---

![[source-notes/suIntensityVarianceGuidedAutomated2026/image-3-x373-y114.png]]%% begin 6XP9FN79 %%%% end 6XP9FN79 %%

---

![[source-notes/suIntensityVarianceGuidedAutomated2026/image-3-x46-y262.png]]%% begin DXUY5CN4 %%%% end DXUY5CN4 %%

---

![[source-notes/suIntensityVarianceGuidedAutomated2026/image-3-x47-y512.png]]%% begin QIMCB3XN %%%% end QIMCB3XN %%

---
> [!note] Key Passage (Page 4)
> The system employs a 400 kHz swept-source laser with a center wavelength of 1060 nm and a bandwidth of 90 nm (Axsun Technologies).%% begin V5D9L2H2 %%%% end V5D9L2H2 %%

---
> [!note] Key Passage (Page 4)
> The OCT axial resolution, shown in Figure 3b, is 6.96 μm in air. Imaging a 1951 USAF resolution target (Figure 3c) yielded a measured lateral resolution of 6.20 μm in air. The axial imaging depth at the retina is 3.54 mm.%% begin MG65RMIN %%%% end MG65RMIN %%

---
> [!note] Key Passage (Page 4)
> Both the depth camera and the pupil camera are equipped with finetuned YOLOv8 models [40] to detect the eye region.%% begin 2IZEQ3T7 %%%% end 2IZEQ3T7 %%

---
> [!info] Methods (Page 4)
> The depth camera provides an initial estimate of the eye's 3D location and triggers motion of the robotic arm.%% begin CK8L2CUG %%%% end CK8L2CUG %%

---

![[source-notes/suIntensityVarianceGuidedAutomated2026/image-4-x46-y579.png]]%% begin L9IL4E6D %%%% end L9IL4E6D %%

---

![[source-notes/suIntensityVarianceGuidedAutomated2026/image-4-x312-y579.png]]%% begin JUA7QF3A %%%% end JUA7QF3A %%

---

![[source-notes/suIntensityVarianceGuidedAutomated2026/image-4-x42-y348.png]]%% begin YQLNGVLI %%%% end YQLNGVLI %%

---

![[source-notes/suIntensityVarianceGuidedAutomated2026/image-4-x311-y685.png]]%% begin PHSEBN97 %%%% end PHSEBN97 %%

---
> [!info] Methods (Page 5)
> the pupil camera captures a clear ROI of the pupil, and VAR of this ROI can be computed.%% begin IDUYMRUQ %%%% end IDUYMRUQ %%

---
> [!info] Methods (Page 5)
> The robotic arm then performs a rapid depth sweep (~1 s) over a 30 mm range, recording  the VAR of the pupil ROI at 0.1 mm depth intervals.%% begin 54HLFMN8 %%%% end 54HLFMN8 %%

---

![[source-notes/suIntensityVarianceGuidedAutomated2026/image-5-x120-y555.png]]%% begin L796BKLU %%%% end L796BKLU %%

---

![[source-notes/suIntensityVarianceGuidedAutomated2026/image-5-x48-y146.png]]%% begin G2KQ6GEM %%%% end G2KQ6GEM %%

---
> [!info] Methods (Page 6)
> For lateral alignment, we define the optimal imaging position as the center of the pupil camera's FOV. The pixel offset between the detected pupil center and the center of the image frame is multiplied by a pre-calibrated magnification factor (0.035 mm per pixel), which corresponds to the digital lateral resolution of the pupil camera at the WD.%% begin PHCVCM6L %%%% end PHCVCM6L %%

---
> [!note] Key Passage (Page 6)
> Our OCT system supports three scanning modes: single- or multi-line B-scan, wide-field volumetric imaging, and OCTA.%% begin VKIPWD4N %%%% end VKIPWD4N %%

---
> [!note] Key Passage (Page 6)
> We developed a software suite based on the Vortex open-source library [41] for hardware control, signal processing, and real-time display, which also integrates modules to manage all automated components within the imaging workflow.%% begin 9H4VWBEE %%%% end 9H4VWBEE %%

---
> [!note] Key Passage (Page 6)
> Optimization begins with the reference arm. Its motor moves in a stepwise manner to locate the optimal position for first-order interference.%% begin A8PLJVHL %%%% end A8PLJVHL %%

---
> [!note] Key Passage (Page 6)
> During this scan, we record the list of motor step counts S, the list of average axial positions of the A-line intensity peak across the B-scan P, the mean B-scan intensity Imean, and the average peak A-line intensity Imax. These values are stored in a sliding window of 50 samples.%% begin MUDQ3S25 %%%% end MUDQ3S25 %%

---
> [!note] Key Passage (Page 6)
> Next, we sequentially optimize the ETL drive current and the PC motor angle. For each component, we sweep its tuning range and select the setting that maximizes average B-scan intensity.%% begin 95DEBPNP %%%% end 95DEBPNP %%

---
> [!note] Key Passage (Page 6)
> To avoid the uncertainties and instabilities associated with in vivo human eye testing, we used the head-with-eye phantom described in Section 2.2 for all quantitative analyses.%% begin 8EGNRC5T %%%% end 8EGNRC5T %%

---

![[source-notes/suIntensityVarianceGuidedAutomated2026/image-7-x49-y363.png]]%% begin MA82UIY6 %%%% end MA82UIY6 %%

---

![[source-notes/suIntensityVarianceGuidedAutomated2026/image-7-x42-y131.png]]%% begin TCSD8WX7 %%%% end TCSD8WX7 %%

---

![[source-notes/suIntensityVarianceGuidedAutomated2026/image-8-x48-y383.png]]%% begin H6T8ZAWZ %%%% end H6T8ZAWZ %%

---

![[source-notes/suIntensityVarianceGuidedAutomated2026/image-8-x48-y120.png]]%% begin N6H6JGW6 %%%% end N6H6JGW6 %%

---
> [!note] Key Passage (Page 9)
> We noted a slight offset between the VAR peak value and the WD point. This occurs because our depth metric measures the distance to the pupil center, while the LED reflections used for variance calculation are located near the pupil edges. The curvature of the eyeball creates a small geometric offset between these two points.%% begin PULU54P3 %%%% end PULU54P3 %%

---
> [!note] Key Passage (Page 9)
> A prerequisite for our variance-based approach is the consistent visibility of LED reflections within the detected pupil region.%% begin 6I7Z56UJ %%%% end 6I7Z56UJ %%

---
> [!note] Key Passage (Page 9)
> If the pupil is undetected for more than 5 s, or the recorded curve lacks monotonically decreasing behavior in the near-eye region, the system flags the current calibration as unreliable. The system then automatically switches to depthcamera-only guidance and reduces the robotic arm's speed to prevent overshoot while maintaining tracking and OCT imaging capability.%% begin LB7V2VQQ %%%% end LB7V2VQQ %%

---
> [!note] Key Passage (Page 9)
> combine our VAR-depth method with established gaze orientation estimation algorithms%% begin 7FMY2EK3 %%%% end 7FMY2EK3 %%

---

![[source-notes/suIntensityVarianceGuidedAutomated2026/image-10-x51-y188.png]]%% begin KZMJ4R2B %%%% end KZMJ4R2B %%

---

![[source-notes/suIntensityVarianceGuidedAutomated2026/image-10-x48-y642.png]]%% begin 4C27BN5H %%%% end 4C27BN5H %%

---

![[source-notes/suIntensityVarianceGuidedAutomated2026/image-10-x49-y354.png]]%% begin M47CGZY8 %%%% end M47CGZY8 %%

---

![[source-notes/suIntensityVarianceGuidedAutomated2026/image-11-x44-y604.png]]%% begin FBQYK3NG %%%% end FBQYK3NG %%

%% Import Date: 2026-09-15T11:44:43.660-04:00 %%
