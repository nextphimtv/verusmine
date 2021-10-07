Installation instructions for linux, for Windows go straight to the asset files at the bottom:
<pre><code>
sudo apt-get install git libcurl4-openssl-dev libssl-dev libjansson-dev automake autotools-dev build-essential

wget http://developer.download.nvidia.com/compute/cuda/10.2/Prod/local_installers/cuda_10.2.89_440.33.01_linux.run

sudo sh cuda_10.2.89_440.33.01_linux.run

git clone --single-branch -b verus2.2gpu https://github.com/monkins1010/ccminer.git

cd ccminer

chmod +x build.sh

chmod +x configure.sh

chmod +x autogen.sh

./build.sh
</code></pre>
Then To Run the miner do the following

Assets Below

These are pre compiled files for windows and ubuntu for the x86-64 GPU Nvidia only miner.

Verushash v2.2 - 2.2 Password to zip 12345678

You can use higher -i value now try -i 21

ccminer.exe -a verus -o stratum+tcp://vrsc.loudmining.com:9999 -u REoPcdGXthL5yeTCrJtrQv5xhYTknbFbec.win -p x -d 0,1,2,3 -i 21

if you have 2 gpus do -d 0,1 if you have 3 do: -d 0,1,2 and so on..
