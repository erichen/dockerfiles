# dockerfiles

## ubuntumiso
This is linux os ubuntu with sshpass mudule.

build image
'''
cd ubuntu
docker build -t ubuntumiso .
'''

get image
'''
docker pull erichen88/ubuntumiso
'''

run ubuntu with sshpass
'''
docker run -it --rm erichen88/ubuntumiso /bin/bash
'''

run ubuntu with sshpass in wondows using powershell
'''
misoserver.bat
'''
