### [How does a DNS request work?](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/What_is_a_domain_name#how_does_a_dns_request_work "Permalink to How does a DNS request work?")

As we already saw, when you want to display a webpage in your browser it's easier to type a domain name than an IP address. Let's take a look at the process:

1.  Type `mozilla.org` in your browser's location bar.
2.  Your browser asks your computer if it already recognizes the IP address identified by this domain name (using a local DNS cache). If it does, the name is translated to the IP address and the browser negotiates contents with the [[diff between webpage, webserver and search engine#web server|WebServer]] . End of story.
3.  If your computer does not know which IP is behind the `mozilla.org` name, it goes on to ask a DNS server, whose job is precisely to tell your computer which IP address matches each registered domain name.
4.  Now that the computer knows the requested IP address, your browser can negotiate contents with the web server.

![Explanation of the steps needed to obtain the result to a DNS request](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/What_is_a_domain_name/2014-10-dns-request2.png)