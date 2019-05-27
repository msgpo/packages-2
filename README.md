Package Repository for Debian
=============================

| Codename | Architecture |
|----------|--------------|
| stretch  | armhf        |


### Add repository
```
echo "deb https://voice-engine.github.io/packages/ main" | sudo tee /etc/apt/sources.list.d/voice-engine.list
```

### Add public GPG key
```
apt-key adv --keyserver keyserver.ubuntu.com --recv-keys 63B5BCC3
```
or
```
curl https://voice-engine.github.io/packages/public.key | sudo apt-key add -
```
