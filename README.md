# F1_Project


This project create to splite file to 30 chunk and encrypt it with key to make it secure
that only who have key can read it.
Then upload splite file to ipfs decentralized network.
So you and other can download it back anytime by using secure key hash that we give after
encypt and upload file.

To use this project first install ipfs https://flyingzumwalt.gitbooks.io/decentralized-web-primer/install-ipfs/lessons/download-and-install.html

And Initialize your IPFS https://flyingzumwalt.gitbooks.io/decentralized-web-primer/install-ipfs/lessons/initialize-repository.html

run command > ipfs daemon

to upload we run command > fone upload {filename}  

Ex: > fone upload -f example.txt

to download run command > fone download -f {filename} -k {key}

Ex: > fone download example.txt -k tL6j77s2fObQskeaYoNbfC_bVHCJiWI3zOqalMWXQIc=

note: To make other can download your file you should give him a example.txt-hash.txt in keys floder
if you not do that other can not find your hash to download.

