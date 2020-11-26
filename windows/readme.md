### windows 使用
 * 主要是结合gvp使用，如果不使用gvp也可以
   + 安装包的时候把包安装到GOPATH指定的第一个目录中，所以只要设置对GOPATH就行，不管是手动设置还是通过gvp
   
 * 结合gvp使用
   1. 进行module目录
   2. start bmn 
     + bmn就是一个git bash, 即打开一个新的bash窗口
     > 如果不使用新bash窗口，在source gvp out之后，GOPATH变量并没有还原
   3. 执行source gvp
     + 此时目录创建好了，GOPAHT也设置好了
   4. 执行gpm-git
     + 下载并安装包
     
   5. go run xxx.go
   
   6. source gvp out
   
 * 将gvp sh放到git/usr/bin目录下
   
 * 使用了gpm-git，就不需要在使用gpm了
   
   
   