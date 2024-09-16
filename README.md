# CrDroid Android for sweet2 (Redmi Note 12 Pro 4G)

Follow the instruction from [crDroid official build guide](https://github.com/crdroidandroid/android/blob/14.0/README.mkdn) before initializing the crDroid repository ([1.2 of the guide](https://github.com/crdroidandroid/android/blob/14.0/README.mkdn#12-initializing-repo))

After entering the initialization command:

```shell
# Install Repo in the created directory
repo init -u https://github.com/crdroidandroid/android.git -b 14.0 --git-lfs
```

Import this repository as a local manifest with the command:

```shell
git clone https://github.com/xiaomi-sweet2/manifest -b 14.0/crdroid --depth=1 .repo/local_manifests
```

Then, follow the steps of the build instructions as before
