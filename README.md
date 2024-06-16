# evilginx


1.Setup domain
	config domain fake.com/custom domain

2.config IPv4
	config ipv4 127.0.0.1

3.set phishlet hostname
	phishlets hostname github github.io.fake.com
4.Enable Phishlet
	phishlets enable github 

5.Optinal(Dev mode\Local Mode)
	phishlets get-hosts github

		127.0.0.1 github.io.fake.com
		127.0.0.1 api.github.io.fake.com
		127.0.0.1 github.github.io.fake.com
		SET THIS TO /ETC/HOSTS 

6.Create Lures
	lures create github

7.List all lures
	lures

8.Get the Lures URLs
	lures get-urls 0 (id .i.e 0)
