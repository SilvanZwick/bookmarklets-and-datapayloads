# Windows 10 Notepad Bookmarklet

## Description
yay! :3

## How to Run

### Using JSDelivr (Recommended)
This will work for most situations. If your school has blocked `cdn.jsdelir.net`, then try another method. Otherwise, this method is **highly recommended**.
To run this bookmarklet using JSDelivr, type the following into the URL field for a bookmark:
```
javascript:fetch('https://cdn.jsdelivr.net/gh/SilvanZwick/bookmarklets-and-datapayloads@main/bmlets/fetch-and-run/win10notepad/v1/fast.js').then(response => response.text()).then(code => {eval(code);}).catch(error => {console.error('Error loading script: ', error);alert('Error loading script: ', error);});
```

### Using Statically
This might work, but you should try JSDelivr first. If your school has stopped JSDelivr from working, then try this. If your school has blocked `cdn.statically.io`, then try another method.
To run this bookmarklet using Statically, type the following into the URL field for a bookmark:
```
javascript:fetch('https://cdn.statically.io/gh/SilvanZwick/bookmarklets-and-datapayloads/main/bmlets/fetch-and-run/win10notepad/v1/fast.js').then(response => response.text()).then(code => {eval(code);}).catch(error => {console.error('Error loading script: ', error);alert('Error loading script: ', error);});
```

### Using the GitHub User Content CDN (Not recommended)
This is NOT RECOMMENDED. You should try other methods first, as this will probably be blocked. If your school has blocked JSDelivr and Statically, then try this. Otherwise, it is highly recommended to try another method.
To run this bookmarklet using the GitHub User Content CDN, type the following into the URL field for a bookmark:
```
javascript:fetch('https://raw.githubusercontent.com/SilvanZwick/bookmarklets-and-datapayloads/refs/heads/main/bmlets/fetch-and-run/win10notepad/v1/fast.js').then(response => response.text()).then(code => {eval(code);}).catch(error => {console.error('Error loading script: ', error);alert('Error loading script: ', error);});
```
