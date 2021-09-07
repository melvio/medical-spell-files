# Medical Spell Files
Medical spell files that are Vim-compatible.


[![melvio - medical-spell-files](https://img.shields.io/static/v1?label=melvio&message=medical-spell-files&color=blue&logo=github)](https://github.com/melvio/medical-spell-files) 
[![stars - medical-spell-files](https://img.shields.io/github/stars/melvio/medical-spell-files?style=social)](https://github.com/melvio/medical-spell-files)


### How to get a medical spell file for vim

**Step 1**:
Download a vim spell file (with the `.spl` extension). 
You must place this file in the correct location. 
On most Linux machines, this will be `${HOME}/.vim/spell`.
You can place the English medical spell file `medical.utf-8.spl` from this repository in that directory by running:

```bash
curl "https://raw.githubusercontent.com/melvio/medical-spell-files/main/spell/medical.utf-8.spl" --output "${HOME}/.vim/spell/medical.utf-8.spl"
```


**Step 2**:
Configure Vim's `spelllang` to include the medical spell file. 
You can add a line like this to your `vimrc`:
```vim
set spelllang=en_us,medical
```


**Step 3**:
Start your happy vimming. 
If you don't have spell checks enabled by default, run the following command inside `vim`:
```vim
:set spell
```



Encountered any issues? Room for improvement? 
Your feedback is welcomed over [here](https://github.com/melvio/medical-spell-files/issues).



### Metadata

| Metadata            | Values                                                                                |
| ------------------- |:------------------------------------------------------------------------------------: |
| Terms:              | 98127 (in `medical.utf-8.spl`)                                                        |
| Last Updated        | medical spell file: Tue 07 Sep 2021                                                   | 
| Contents:           | Drug names (up-to-date with FDA-approvals as of 2014-04-02, trade and generic names). |
|                     | Anatomical terms                                                                      |
|                     | Dermatological terms                                                                  |
|                     | Internal medicine terms                                                               |
|                     | Surgical terms                                                                        |
|                     | DSM-IV terms                                                                          |
|                     | ICD-9 terms                                                                           |
|                     | Many more terms added                                                                 |
| Author:             | (c) 2021- Melvin Hazeleger <https://github.com/melvio/>                               |
| Work Derived From:  | (c) 2014-2017 Aristotelis P. <https://github.com/Glutanimate>                         |
|                     | (c) 2007-2014 R. Robinson <info@e-medtools.com>                                       | 
|                     | (c) 2009-2014 Rajasekharan N.                                                         | 
| Original Sources:   | OpenMedSpel by R. Robinson of e-MedTools (Version 2.0.0, released 2014-01-21)         |
|                     | MTH-Med-Spel-Chek by Rajasekharan N. of MT-Herald (released 2014-04-02)               |
| License             | [![License](https://img.shields.io/badge/License-GPL--3.0-blue)](#LICENSE)            | 






### Special Thanks

Thanks go out to Artistotelis P. for providing the 
[initial version](https://github.com/glutanimate/wordlist-medicalterms-en) of the English medical spell file. 
Who, in turn, derived it from R. Robinson and Rajasekharan N.
Thanks to [Bram Moolenaar](https://www.moolenaar.net/) for his work on Vim, his [charity work](https://www.vim.org/), and for
[inspiring me to create this repository](https://vi.stackexchange.com/questions/34401/vim-cannot-find-medical-spell-files).

<div align="center"> 

*Nanos gigantium humeris insidentes.*

[![melvio - medical-spell-files](https://img.shields.io/static/v1?label=melvio&message=medical-spell-files&color=blue&logo=github)](https://github.com/melvio/medical-spell-files)
</div>
<div align="center"> 

[![stars - medical-spell-files](https://img.shields.io/github/stars/melvio/medical-spell-files?style=social)](https://github.com/melvio/medical-spell-files)
</div>

