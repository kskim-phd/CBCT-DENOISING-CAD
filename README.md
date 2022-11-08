# CBCT-Denoising-CAD
We release OMU-Denoising-CAD train/test code.

Contributors: Kyung-su Kim , Chae-yeon Lim

Detailed instructions for train/testing the image are as follows.

---

# Implementation
OMU-Denoising-CAD implementation based on pytorch

Internal CBCT dataset : https://drive.google.com/file/d/1oW35VoVKf7W1NBstty1rghGxHWXEgSg2/view?usp=share_link

External CBCT dataset : https://drive.google.com/file/d/1sxct8LRip1mV6k7Lm6hynQcFx4ZDmujN/view?usp=share_link

---

# Environments

The setting of the virtual environment we used is described as osj_env.yaml.
```python
conda env create --file osj_env.yaml
```

---

# Pre-trained weights

Denoising weight: https://drive.google.com/file/d/16xECqeDaei64KiWiIBoaJmjteeZUULak/view?usp=share_link

ResNet weight: https://drive.google.com/file/d/1rbhoJPHuITF8dbW2_t8jCbDvb3SOzwER/view?usp=share_link

```
Classification_OMU
   |-- 1_Codes_pre
   |-- 2_Codes_3D
   |   |-- 3D_logs
   |   |-- 3D_weights
   |   |-- cam
   |   |-- eval
   |   |-- models
   |   |   |-- r3d18_K_200ep.pth `#f03c15`
   |   |   |-- r3d34_K_200ep.pth `#f03c15`
   |   |   |-- r3d50_K_200ep.pth `#f03c15`
   |-- 3_Codes_external
   |   |-- cam
   |   |-- eval
   |   |-- key_logs
   |   |-- models
   |   |   |-- r3d18_K_200ep.pth
   |   |   |-- r3d34_K_200ep.pth
   |   |   |-- r3d50_K_200ep.pth
   |   |   |   |   |-- jonavon
   |   |   |   |   |   |-- AbstractFile.java
   |   |   |   |   |   |-- roman
   |   |   |   |   |   |   |-- Main.java
   |   |   |   |   |   |   |-- Numeral.java
   |   |   |   |   |   |   |-- RomanNumberInputFile.java
   |   |   |   |   |   |   |-- RomanNumeralToDecimalEvaluator.java
   |-- test
   |   |-- java
   |   |   |-- com
   |   |   |   |-- foxguardsolutions
   |   |   |   |   |-- jonavon
   |   |   |   |   |   |-- roman
   |   |   |   |   |   |   |-- InterpretSteps.java
   |   |   |   |   |   |   |-- RunCukesTest.java
   |   |-- resources
   |   |   |-- com
   |   |   |   |-- foxguardsolutions
   |   |   |   |   |-- jonavon
   |   |   |   |   |   |-- roman
   |   |   |   |   |   |   |-- Interpret.feature
   |   |   |-- sample-input.txt
   ```





