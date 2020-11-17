# HW2: Preprocessing & GLM
[1] Preprocessing and GLM
(a) Perform preprocessing and GLM using `afni_proc.py` script. Following steps should be included
1. despiking
2. slice timing correction
3. motoin correction
4. spatial normalization to the MNI space with 3 mm isotropic voxel size
5. scaling of the voxel intensity to an average of 100
6. temporal detrending
Use subjects' EPI and anatomoical files for alignment
```plaintext
Let's do this with the link Hyemin gave
```
(b) Review your overall results including the estimated neuronal activations from the GLm as summarized in the `afni_proc.py QC(APQC)` with a `html` format. 

---
[2] Statistical Analysis
```bash
From Class 11.24(Tue) - t-test
```
(a) Perform **one-sample t-test** for each of the four tasks

(b) Perform all the **paired t-test** for the pairs of the tasks(e.g. ad vs lh, ad vs rh ... and so on.)

(c) Perform one-way repeated measures ANOVA using the results from all the four tasks(i.e. suppose there are four factors and one group)

---
[+] Reference Links
[HTMl APQC](https://afni.nimh.nih.gov/pub/dist/doc/htmldoc/tutorials/apqc_html/apqc_ex1.html)
[AFNI Overview](https://andysbrainbook.readthedocs.io/en/latest/AFNI/AFNI_Overview.html)
