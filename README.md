# dev-in-Ubuntu-23.0.6
Setting up your ubuntu 23 for development

So yes its a bit problematic with python but here's what I have so far:

python 3.12 comes preinstalled 
pip instal doesn't work unless you're using a venv sor rather use:
  sudo apt install python3-django
  key things to notice , sudo ,python3-, d
    python3 preferebly be explicit your main python version, if the command is not working : sudo apt install python3-pip
    then you can use python3-...
    the d, yes its usually spelt Django but it seems it is very specific about casing some might work with uppercase but so
    far lower-case for all things python terminal 

    for more information till January 2024 visit there may be newer notes:
      https://discourse.ubuntu.com/t/lunar-lobster-release-notes/31910
