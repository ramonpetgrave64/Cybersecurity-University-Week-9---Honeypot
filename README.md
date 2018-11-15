# Cybersecurity-University-Week-9-Honeypot

We create a honeypot, using  Modern Honey Network (MHN).

- I deployed the [dionaea](https://github.com/rep/dionaea) honeypot.
- Issues:
  - For the assignment's instruction said to use ```github.com/RedolentSun/mhn.git```, but that repo is not available. I used the official repo instead: 
    ```github.com/threatstream/mhn.git```
- A summary of the data collected:
  - I used nmap on my local machine to scan for open ports. The MHN detected this. The honepot's [exported data](https://raw.githubusercontent.com/ramonpetgrave64/Cybersecurity-University-Week-9-Honeypot/master/session.json) is in this repo.
  - Attack Stats
    ![stats image](https://raw.githubusercontent.com/ramonpetgrave64/Cybersecurity-University-Week-9-Honeypot/blob/master/attack%20stats.PNG?raw=true)
  - Also, to allow http in Google Cloud Compute, I had to go to the console and specificallow http for the instance, otherwise I would only be able to connect to the HoneyMap at port 3000
- Any unresolved questions raised by the data collected
