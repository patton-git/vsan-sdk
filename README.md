VMware vSAN Management SDK 8.0  Python 버전에서, Ansible을 이용하기 위한 파일들을 추출해둔 저장소 입니다.


https://customerconnect.vmware.com/downloads/get-download?downloadGroup=VSAN-MGMT-SDK80
vsan-sdk-python.zip
File size: 7.84 MB
File type: zip
Release Date: 2022-10-11
Build Number: 20426518
VMware vSAN Management SDK 8.0 - Python
MD5SUM: d97a3530ae789eabab19be184ceb07f8
SHA1SUM: d03413deb1afd21c136858d8966568ac5d4b4da4
SHA256SUM: 19db4eeb7c868c111a93f57af4d7fded92bc5c9c512fb18591ab2db3d4f47f97


<pre><code>
pip install defusedxml

python3 -c 'import sys; import pprint; pprint.pprint(sys.path)' | grep site-packages

git clone https://github.com/patton-git/vsan-sdk

cp ./vsan-sdk/* ./.local/lib/python3.10/site-packages/

python3 -c 'import vsanapiutils; import vsanmgmtObjects'
</code></pre> 
