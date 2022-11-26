# namecheap-ddns.hsh
Hush shell script to dynamically change domains IPs in namecheap.com. It only updates the namecheap's IPs when when an IP change is detected.

# Usage
- Enable Dynamic DNS in namecheap's site to generate a password.
- Put this password in a secure file in your filesystem, one per host and domain.
- Fillout the namecheap_info list with your hosts, domains and password files (Note: do not use "~" in the list of password file paths, just use the full path name).
- Use cron to periodically run the script.

# References
- https://hush-shell.github.io/
- https://gist.github.com/dalhundal/89159b3f032588586e91
- https://stackoverflow.com/questions/14928573/sed-how-to-extract-ip-address-using-sed
