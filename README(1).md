# Arul Google Dorking Scanner

The OSINT project, the main idea of which is to collect all the possible Google dorks search combinations and to find the information about the specific web-site: common admin panels, the widespread file types and path traversal. The 100% automated.

Usage example:
--------------
```
cd Arul-Google-Dorking-Scanner

```
chmod +x AGDS.sh
./FGDS.sh megacorp.one
```
or
```
bash ./AGDS.sh megacorp.one
```

with proxy

```
bash ./FGDS.sh megacorp.one 192.168.1.1 8080
```

This will work beatifully on Kali but an ultimately universal way is through Docker. Just run 

```
docker build -t FOO .
```

and then run it with your argument for the URL such as this:

```
docker run -it --rm FOO mysite.com
```

Video example:
--------------


Screenshots:
------------



An original article:
--------------------
[https://www.ivanglinkin.com/Arul-Google-Dorking-Scanner/](https://www.ivanglinkin.com/Arul-Google-Dorking-Scanner/)

IT's LICENCED BY
ARUL PRAKASH.R
