# Dit is de editor.

## Image Sizing Markdown
Standaard markdown geeft image op 100% groten. Voorkom dit door gebruik te maken van `HTML <img src="url" widht="245">`
<img src="https://d2nycb7fhhex4i.cloudfront.net/images01/dkrimage.jpg" width=245> 

Plaats de images op CDN in dit geval amazon `https://d2nycb7fhhex4i.cloudfront.net/images01`


HTML img codeing werkt perfect


![https://d2nycb7fhhex4i.cloudfront.net/images01/dkrimage.jpg](https://d2nycb7fhhex4i.cloudfront.net/images01/dkrimage.jpg) 

Dat werkt prima.

Kramdown engine? ![MyPublicImageLocation](https://storage001.public62818.s3-eu-west-1.amazonaws.com/images01/dkrimage.jpg ){:width="25px"}

En

### Level 3

###  

_My Public S3 image location._

Using own URL can be used for certificate with https; ![MyPublicImageLocation](https://storage001.public62818.s3-eu-west-1.amazonaws.com/images01/dkrimage.jpg)

Using cloudfront url; ![cloudfront url](https://d2nycb7fhhex4i.cloudfront.net/images01/dkrimage.jpg)

and now with https access. ![MyPublicImageLocation](https://storage001.public62818.s3-eu-west-1.amazonaws.com/images01/dkrimage.jpg)

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTExMTY5MTQ4MDAsMTY2MzQ5MjA3NiwxMD
Q2NjgxNzczXX0=
-->