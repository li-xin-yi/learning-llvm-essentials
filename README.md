# learning-llvm-essentials
Notes and practices in this book: https://g.co/kgs/bQ1chr

# Set up LLVM-13

```
wget -O - https://apt.llvm.org/llvm-snapshot.gpg.key | sudo apt-key add -
sudo apt-add-repository "deb http://apt.llvm.org/bionic/ llvm-toolchain-bionic-13 main"
sudo apt-get update
sudo apt-get install -y llvm-13 llvm-13-dev llvm-13-tools clang-13
```