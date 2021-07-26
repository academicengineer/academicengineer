- 👋 Hi, I’m @academicengineer
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
academicengineer/academicengineer is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

# optix-7.3のダウンロードとインストール

# cuda-11用のドライバのダウンロードとインストール　※ドライバはインストールしない
wget http://developer.download.nvidia.com/compute/cuda/11.0.2/local_installers/cuda_11.0.2_450.51.05_linux.runsudo
sh cuda_11.0.2_450.51.05_linux.run

# gdmの停止と再起動
systemctl stop gdm.service
ps aux | grep gdm
kill -9 PID

# K760に対応するcuda-11用のドライバのダウンロード
sh https://jp.download.nvidia.com/XFree86/Linux-x86_64/470.57.02/NVIDIA-Linux-x86_64-470.57.02.run
sh sh NVIDIA-Linux-x86_64-470.57.02.run

# cuda11の動作確認
https://note.com/altbridgetech/n/ne5a320213280

# 参考
https://www.nemotos.net/?p=3176
https://qiita.com/myoshimi/items/c507d7389f38406383be
