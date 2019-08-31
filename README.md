# emptyJUCEProject
emptyJuceProject for vscode on linux

## clone to JUCE project folder
```
$ cd ~/JUCE/
$ git clone https://github.com/icq4ever/emptyJUCEProject
```

## add to `.bashrc` or `.zshrc`
```
alias juce="cd ~/JUCE"
alias setJUCE="cp -r ~/JUCE/emptyJUCEProject/.vscode ./"
```

## how to use it ?
- open JUCE project folder, which is generated by Projucer (don't forget to check Linux Makefile)
- `Ctrl+Shift+B" and select "Build"
