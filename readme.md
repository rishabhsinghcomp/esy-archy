# esy-archy
This repo contains an org file which can be used to set a arch-hyprland environment based on emacs for better Desktop experience.



**Requirements**
- Basic Arch Setup [refer Pacakge section in config.org ]
- emacs-nativecomp
- Hyprland 

/If you dont want use a particular application you can remove it from config.org before saving it/

**HOW TO EXEECUTE THIS**  
  - Set Up Arch , Hyprland
  - then install emacs-nativecomp
  - put .emacs.d in .config 
  - create sym link [refer rish utilitis for this ] `
"#+begin_src emacs-lisp
(use-package org-auto-tangle
  :defer t
  :hook (org-mode . org-auto-tangle-mode)) #+end_src"

- paste this snippet in .emacs file 
- now evaluate the config.org file

Mentions
- System Crafters [https://github.com/daviwil/emacs-from-scratch]
- HYPRV2 [https://github.com/SolDoesTech/HyprV2.git]
- rish [ https://github.com/rishabhsinghcomp]
