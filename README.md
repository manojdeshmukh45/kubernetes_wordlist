# kubernetes_wordlist
This is the worslist for fuzzing kubernetes.

Download kubernetes-wordlist.txt and run a fuzzing using this wordlist.
EX. ffuf -w kubernetes-wordlist.txt -u https://<master-ip>:<ip>FUZZ -mc 200
