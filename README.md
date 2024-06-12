# WikiLeaker-fork
A web scraper for WikiLeaks. 🕵️🔎 🌎

This web scraper is inspired by the Datasploit module written in Python2. This script leverages Python3 and pandas, Python's data analysis toolkit.
<br><br>
<div align="center">
  <a href="https://wikileaks.org">
  <img src="https://i.kym-cdn.com/entries/icons/facebook/000/006/875/1_Kcy0ZFsH8q_K_wplIaVyLQ.jpg" alt="WikiLeaks Logo" width="65%">
  </a>
  <br><br>
  <p><i>“WikiLeaks is a giant library of the world's most persecuted documents. We give asylum to these documents, we analyze them, we promote them and we obtain more.” -  Julian Assange</i></p>
</div>
<br><br>

## Prerequisites
+ Python3
+ Python3-pip
+ libre-dev
+ git
+ python3-lxml
+ requests
+ re
+ pandas
+ bs4

### Installing Prerequisites
Make sure that Recon-ng is up to date and install the WikiLeaker module using the following commands in Recon-ng:

`marketplace install wikileaker`

## Install

To install the standalone version run the following command:

`bash setup.sh`

## Running Wikileaker.py

`python3 WikiLeaker.py <domain of your choosing>`

Voila!

# Wikileaker Recon-ng Module
+ You may run `marketplace refresh` followed by `marketplace install wikileaker`
+ If the above does not work, copy the current repository from Github and move the contents of the `recon-ng module` into your directory for recon-ng (`/~/.recon-ng/modules` in Kali).
