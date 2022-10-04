# termux-repo-fix
Remove the science-repo and game-repo to fix the issue with fail output. Close session and restart termux after update


(Pkg or apt) remove science-repo && (pkg or apt) remove game-repo && (pkg or apt) update && reboot

$apt-get update --allow-releaseinfo-change --allow-downgrades
$pkg update --allow-releaseinfo-change --fix-missing 
Than install the root-repo and install tsu if your device is rooted to install the sudo command
