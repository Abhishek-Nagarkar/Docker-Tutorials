# Docker Tutorials
1. Install docker desktop
2. Start docker desktop

## IMPORTANT POINTS REGARDING DOCKER
### 1. Namespaces -- Virtual environment which shares resources instead of creating virtual resources like vm's do
Limit things to what a process can see
Created with syscalls
- Unix time sharings
- Process id
- Mounts
- Network
- User id
- Inter process communication
### 2. Cgroups (created by google called as control groups) -- offer resource isolation
### 3. Chroot