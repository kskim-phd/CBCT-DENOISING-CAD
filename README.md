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
src
   |-- main
   |   |-- java
   |   |   |-- com
   |   |   |   |-- foxguardsolutions
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





