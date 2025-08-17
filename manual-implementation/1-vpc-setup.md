## SEttings
* Console → VPC → Create VPC → “VPC only.”
* Name: <your-name>-lab-aws-data-engg-lifecycle-1-<service>
* IPv4 CIDR: 10.2.0.0/24.
* Enable DNS hostnames + DNS support.
* Tags
    - project : <your-name>-lab-aws-data-engg-lifecycle-1
    - environment : dev
    - safe-to-destroy : yes


## Ref
- DNS
    - Domain Name System (DNS) is a standard by which names used on the internet are resolved to their corresponding IP addresses. 
    - A DNS hostname is a name that uniquely and absolutely names a computer; it's composed of a host name and a domain name. 
    - DNS servers resolve DNS hostnames to their corresponding IP addresses.
    - Public IPv4 addresses enable communication over the internet, while private IPv4 addresses enable communication within the network of the instance.
    - ref - https://docs.aws.amazon.com/vpc/latest/userguide/vpc-dns.html
    - **DNS resolution** - setting The DNS resolution attribute determines whether DNS resolution through the Amazon DNS server is supported for the VPC.
    - **DNS hostnames** - The DNS hostnames attribute determines whether instances launched in the VPC receive public DNS hostnames that correspond to their public IP addresses.



