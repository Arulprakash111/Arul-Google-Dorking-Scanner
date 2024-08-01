The OSINT project, the main idea of which is to collect all the possible Google dorks search combinations and to find the information about the specific web-site: common admin panels, the widespread file types and path traversal. The 100% automated.
Usage example:
```
cd Arul-Google-Dorking-Scanner
```
```
chmod +x AGDS.sh
```
```
./AGDS.sh megacorp.one
```

or
```
bash ./AGDS.sh megacorp.one
```

with proxy

bash ./AGDS.sh megacorp.one 192.168.1.1 8080

This will work beatifully on Kali but an ultimately universal way is through Docker. Just run

docker build -t FOO .

and then run it with your argument for the URL such as this:

docker run -it --rm FOO mysite.com
