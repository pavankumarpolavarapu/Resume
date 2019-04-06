# Resume
This repository contains latex file of Pavan Kumar Polavarapu Resume. 

I am compiling this file using blang/latex using docker container. 

You can clone this repo and download the docker container as follows

```shell
git clone https://github.com/technophileshub/Resume.git
wget https://raw.githubusercontent.com/blang/latex-docker/master/latexdockercmd.sh
chmod +x latexdockercmd.sh
mkdir build
chmod 777 build
```

You can then issue following command to build the resume to build folder
```shell
./latexdockercmd.sh latexmk -pdf -outdir="./build"
```
