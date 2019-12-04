# saccader-reproducibility
NeurIPS reproducibility challenge on google-AI's saccader paper

Narrow clone from 
# set root directory
  $PSScriptRoot
  git init
  git remote add -f origin https://github.com/google-research/google-research.git
  git config core.sparseCheckout true
  Set-Content .git\info\sparse-checkout "saccader/*" -Encoding Ascii
  git pull origin master --depth=1
