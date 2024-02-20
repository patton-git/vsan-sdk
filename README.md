VMware vSAN Management SDK 8.0  Python 버전에서, Ansible을 이용하기 위한 파일들을 추출해둔 저장소 입니다.

https://customerconnect.vmware.com/downloads/get-download?downloadGroup=VSAN-MGMT-SDK80

<pre><code>
  pip install defusedxml
  python3 -c 'import sys; import pprint; pprint.pprint(sys.path)' | grep site-packages
  git clone https://github.com/patton-git/vsan-sdk
  cp ./vsan-sdk/* ./.local/lib/python3.10/site-packages/
  python3 -c 'import vsanapiutils; import vsanmgmtObjects'
</code></pre> 
