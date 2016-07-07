
# .bash_profile 

## Mac

```bash
# configure
my_proxy="http://192.168.5.4:7777"
my_android_sdk_root=$HOME/opt/android-sdk-macosx
# endconfigure

# iTerm2
export CLICOLOR=1
LSCOLORS=gxfxcxdxbxegedabagacad
export PS1='\[\033[01;32m\]\u@\h\[\033[00m\]:\[\033[01;36m\]\w\[\033[00m\]\$ '
export TERM=xterm-color
# endiTerm2

# android
export ANDROID_HOME=${my_android_sdk_root}
export PATH=$ANDROID_HOME/tools:$ANDROID_HOME/platform-tools:$PATH
# endandroid

# proxy
mySetProxy() {
  export http_proxy=${my_proxy}
  export https_proxy=${my_proxy}
}
# endproxy


```

