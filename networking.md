# NAT, routes, Internet Gateway

​
Answer the following questions
​

1. What do you think the purpose of an internet gateway is? What would we not be able to do without one?
   To give the local network / vpc access to the internet and vice versa. Without one, data/apps etc cannot be accessed by inbound traffic.
   ​
2. Thinking back to a previous session, where do you think you might be using a NAT gateway right now?
   Seeting up our VPC we would have used a NAT gateway to connect the private subenst to the public subnets and the public subnets to the internet.
   ​
3. What IP addresses will be matched by the CIDR block of `0.0.0.0/0`?
    - for bonus points, explain why?
      This CIDR block represents the entire IPv4 address space from 0.0.0.0 to 255.255.255.255. The /# specifies how many bits in the subnet mask are dedicated to the private network. This means /0 no bits are reserved and all are available for the host portion.
      ​
4. In your own words, what is the difference between a NAT gateway and an Internet Gateway? When would you want one over the other?

An internet gateway allows communication between the internet and public subnets within a VPC.

A NAT (Network Address Translation) gateway allows outbound communication from a private subnet in a VPC with the internet but not inbound requests
