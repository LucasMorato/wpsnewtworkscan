# WP Network Scan

<img src="https://i.postimg.cc/2848fzvy/download.png" alt="wpnetworkscan">

Version 1.0

This script was developed with the intention of improving the internet in order to find vulnerabilities in an automated way and report to the respective owners the flaw to be corrected.

The script searches for wordpress sites on the internet according to the settings you establish.
This script is not for personal profit and uses Wpscan By WPScan Team. You must create an account on their website: https://wpscan.com/ to get your token.

The FREE account is limited to a few scans per day, however, you have the option to search for the best plan for you.

Use it wisely and for good.
By using this script you are agreeing that any misuse is not my responsibility.

How to use:
After downloading and saving the script on your Linux, with a text editor (like nano) edit the commented lines with #:
```
nano wpnetworkscan.py
```
```
keyword_search = "amazonas" # change here
country = "com.br" # change here
token = "F91V12GFJNFSJSFOM8LdSHtWayd8PrT6VTiH19FU8" # change here | you can get a plan here: https://wpscan.com/pricing
```

Also change the number of websites you would like to change in the argument "num-". It is important to mention as well that everytime you search for a website, the chances that Google blocks your IP emporaril increases.
```
for urls in search(keyword, num=5, stop=5, pause=4)
```

After changing the lines run with the command:
```
python3 wpnetworkscan.py
```

The script takes a while to complete depending on the number of sites that are fetched.
