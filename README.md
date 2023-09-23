<!-- Project Title -->
<h1 align="center">Kubernetes Wordlist</h1>

<!-- Project Description -->
<p align="center">This repository contains wordlists for fuzzing kubernetes.</p>

<!-- Badges -->
<p align="center">
  <img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="License">
  <img src="https://img.shields.io/badge/Version-1.0-brightgreen.svg" alt="Version">
</p>


<!-- Installation -->
## Installation
```bash
# Install ffuf
https://github.com/ffuf/ffuf

# Download the wordlist 
https://github.com/manojdeshmukh45/kubernetes_wordlist/blob/main/kubernetes-wordlist.txt

# Fuzz using wordlist
fuzz -w kubernetes-wordlist.txt -u https://master-ip:portFUZZ -mc 200

Note: No need to add / after IP address
