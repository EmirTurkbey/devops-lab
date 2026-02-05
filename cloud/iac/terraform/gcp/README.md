## Set up GCP Service & Configure Google Cloud SDK

Update packages
```bash
sudo apt-get update
```

Install curl and apt-transport-https packages
```bash
sudo apt-get install apt-transport-https ca-certificates gnupg curl
```

Import Google Cloud public key
```bash
curl https://packages.cloud.google.com/apt/doc/apt-key.gpg | sudo gpg--dearmor -o /usr/share/keyrings/cloud.google.gpg
```

