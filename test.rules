alert tcp any any -> any 3399 (pcre:"/login|Initial/"; flowbits:set,ids_packet; flowbits:noalert;sid: 1000002;)
alert tcp any any -> any 3399 (msg:"bot founded"; pcre:"/(([0-9]|[1-9][0-9]|1[0-9]{2}|2[0-4][0-9]|25[0-5])\.){3}([0-9]|[1-9][0-9]|1[0-9]{2}|2[0-4][0-9]|25[0-5]):[0-9]+/"; flowbits:isset,ids_packet; sid:1000001;)
