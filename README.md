# Website IP Finder

### Find the IP address of any website...
WIF ( Website IP Finder ) is a script that allows you to quickly track the IP addresses of websites.

## Requirements
```
Python 3
pip install reportlab
```
## Clone the repository
```
$ git clone https://github.com/RamosTechLinux/WebSite-IP-Finder.git
```

## Usage
```
usage: FinderIP.py [-h] [-d] [-s] [--pdf] [--version]

Find the IP address of any website

options:
  -h, --help      show this help message and exit
  -d , --domain   Domain to track
  -s, --save      Save results in a file
  --pdf           Generate a PDF report
  --version       Current version

```
## Example
```
$ FinderIP.py -d www.google.com

                ______
             .-'      `-.
           .'            `.
          /                \              [ WebSite IP Finder ] Versão 1.0
         ;                 ;`             
         |          /      |;             Código Feito Por ➜ {ylw}RamosTech
         ;         / / /   ;|             Twitter  ➜ @gabriiellramoss
         '\       / / /   / ;             Instagram   ➜ @gabriiell.ramos
          \`.    / /    .' /              GitHub   ➜ @RamosTechLinux
           `.`-._____.-' .'               
             / /`_____.-'
            / / /
           / / /
          / / /
         / / /
        / / /
       / / /
      / / /
     / / /
    / / /
    \/_/

            Domain : www.google.com                                                                                                                                 
            IP : 142.251.132.36
            
```
You can also save the results in a text file with the argument ```-s``` or ```--save```.  If you want generate a PDF report with the results, you can use ```--pdf```

The file and PDF report is saved in the same directory as the script and has the following format :
> Domain : IP
