# k8
Kubectl command line tool

## Prerequisites

- kubectl
- dmenu
- skaffold (Optional)

## Install
```
mkdir -p ~/.scripts \
  && cd ~/.scripts \
  && rm -f k8 \
  && wget https://raw.githubusercontent.com/ErlingRoll/k8/master/k8 \
  && sudo chmod +x k8 \
```

### Add path to bashrc

```
echo "PATH=$PATH:~/.scripts >> ~/.bashrc" && bash
```
