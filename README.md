# rctf-scenario1

The Robotics Capture the Flag (RCTF) is an online playground to challenge robot security from your browser. It is designed to be an online game, available 24/7, launchable through your browser and designed to learn robot hacking step by step.

## Play online
Go to https://rctf.aliasrobotics.com and select scenario 1.

### Run it locally
Do you prefer to experimient locally, we've dockerized it for you. Try:

```bash
git clone https://github.com/aliasrobotics/rctf-scenario1
cd rctf-scenario1
docker build -t rctf-scenario1 .
docker run -it rctf-scenario1 bash
```
