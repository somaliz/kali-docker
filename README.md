## kali-linux-full-docker-image

``` shell
alias amap='docker run -it --rm -w /data -v $(pwd):/data somaliz/kali-linux-full amap'
alias burpsuite='docker run -it --rm -e DISPLAY -v $HOME/.Xauthority:/root/.Xauthority --net=host somaliz/kali-linux-full java -jar /usr/bin/burpsuite'
alias commix='docker run -it --rm -w /data -v $(pwd):/data somaliz/kali-linux-full commix'
alias dirb='docker run -it --rm -w /data -v $(pwd):/data somaliz/kali-linux-full dirb'
alias dnschef='docker run -it --rm -w /data -v $(pwd):/data --net=host somaliz/kali-linux-full dnschef'
alias dnsenum='docker run -it --rm -w /data -v $(pwd):/data somaliz/kali-linux-full dnsenum'
alias dnsmap='docker run -it --rm -w /data -v $(pwd):/data somaliz/kali-linux-full dnsmap'
alias dnsrecon='docker run -it --rm -w /data -v $(pwd):/data somaliz/kali-linux-full dnsrecon'
alias dnswalk='docker run -it --rm somaliz/kali-linux-full dnswalk'
alias hping3='docker run -it --rm -w /data -v $(pwd):/data somaliz/kali-linux-full hping3'
alias kali-sh='docker run -it --rm --net=host --privileged -e DISPLAY -v $HOME/.Xauthority:/root/.Xauthority somaliz/kali-linux-full /bin/bash'
alias msfconsole='docker run -it --rm --net=host  -v ~/.msf4:/root/.msf4 -v /tmp/msf:/tmp/data somaliz/kali-linux-full msfconsole'
alias msfvenom='docker run -it --rm -w /data -v $(pwd):/data somaliz/kali-linux-full msfvenom'
alias ndiff='docker run -it --rm -w /data -v $(pwd):/data somaliz/kali-linux-full ndiff'
alias netdiscover='docker run -it --rm --net=host -w /data -v $(pwd):/data somaliz/kali-linux-full netdiscover'
alias nikto='docker run -it --rm --net=host -w /data -v $(pwd):/data somaliz/kali-linux-full nikto'
alias nmap='docker run --rm --net=host --privileged somaliz/kali-linux-full nmap'
alias padbuster='docker run -it --rm somaliz/kali-linux-full padbuster'
alias reaver='docker run -it --rm --net=host --privileged -w /data -v $(pwd):/data somaliz/kali-linux-full reaver'
alias responder='docker run -it --rm --net=host somaliz/kali-linux-full responder'
alias searchsploit='docker run --rm somaliz/kali-linux-full searchsploit'
alias sqlmap='docker run -it --rm --net=host -w /data -v ~/.sqlmap:/root/.sqlmap -v $(pwd):/data somaliz/kali-linux-full sqlmap'
alias socat='docker run --rm -w /data -v $(pwd):/data --net=host somaliz/kali-linux-full socat'
alias tshark='docker run --rm -w /data -v $(pwd):/data --net=host --privileged somaliz/kali-linux-full tshark'
alias volafox='docker run -it --rm -w /data -v $(pwd):/data somaliz/kali-linux-full volafox'
alias volatility='docker run -it --rm -w /data -v $(pwd):/data somaliz/kali-linux-full volatility'
alias wash='docker run -it --rm -w /data -v $(pwd):/data --net=host --privileged somaliz/kali-linux-full wash'
alias webscarab='docker run -it --rm -w /data -v $(pwd):/data -e DISPLAY -v $HOME/.Xauthority:/root/.Xauthority --net=host somaliz/kali-linux-full java -jar /usr/bin/webscarab'
alias wireshark='docker run -it --rm -w /data -v $(pwd):/data -e DISPLAY -v $HOME/.Xauthority:/root/.Xauthority --net=host --privileged somaliz/kali-linux-full wireshark'
alias wpscan='docker run -it --rm -w /data -v $(pwd):/data somaliz/kali-linux-full wpscan'
alias yersinia='docker run -it --rm -w /data -v $(pwd):/data somaliz/kali-linux-full yersinia'
alias zaproxy='docker run -it --rm -v ~/.ZAP:/root/.ZAP -e DISPLAY -v $HOME/.Xauthority:/root/.Xauthority --net=host somaliz/kali-linux-full zaproxy'
```
