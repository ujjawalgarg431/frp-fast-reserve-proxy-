# Exposing Local Apache Website to the Internet using FRP

## introduction

• FRP (Fast Reverse Proxy) is a high-performance reverse proxy that allows you to expose local servers behind NAT/firewall to the public internet.
• We host a website using Apache locally and expose it to the internet via a VPS running FRP server.
## 1.Launch EC2 Instance  

  • Go to AWS Console, then EC2, then Launch   Instance
  • Choose Ubuntu
  • Create and Use key pair
  • Use Putty
  • Allow HTTP (80), HTTPS (443), and SSH (22)
  • Launch instance
