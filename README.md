# My PHP Dirb
PHP tool to brute force subdirectories  
Note that this is an automated tool, manual check is still required.  

```
Usage: php myphp-dirb.php [OPTIONS] -t <target> -w <wordlist>

Options:
	-b	do not display banner
	-c	enable colored output
	-h	print this help
	-d	http code to display separated by comma (default=all)
	-f	display full url
	-i	http code to NOT display separated by comma (default=none)
	-q	do not display HTTP code and length
	-r	follow redirection
	-t	set threads (default=5)
	-u	set url (required)
	-w	set wordlist (required)

Examples:
	php myphp-dirb.php -u http://www.example.com -w /home/mywordlist.txt
```

I don't believe in license.  
You can do want you want with this program.  
