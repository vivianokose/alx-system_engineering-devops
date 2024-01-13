# 0x10-https_ssl

This project covers securing HTTP traffic with HTTPS and SSL/TLS. The goal is to learn how to encrypt communication between clients and servers for security and privacy.

## Learning Objectives

- What is HTTPS SSL and TLS
- What are the main elements that compose HTTPS connections
- How to configure HTTPS on Nginx
- What is a certificate and private key
- What steps are needed to obtain and use a certificate signed by a Certificate Authority (self-signed, Let's Encrypt)
- How to create and use a self-signed certificate with Nginx
- How to configure OCSP stapling
- How to configure HSTS
- How to generate and use an SSL certificate with Let's Encrypt
- Difference between SSL and TLS

## Project Overview

The projects are divided into the following tasks:

- 0-https_abc - Bash script that displays "ABC" on localhost on port 4000 using HTTPS
- 1-haproxy_ssl_termination - Configures HAproxy to accept HTTPS connections and redirect to HTTP backend
- 2-passenger_apache_ssl - Configure SSL on Apache to serve Passenger application securely  
- 3-letsencrypt_nginx - Generate and configure SSL on Nginx with Let's Encrypt
- 4-client_https - Python script that fetches HTTPS URLs

## Usage

Each task provides configuration files and instructions to deploy HTTPS solutions.

## Testing

Manual testing is done by simulating client connections and validating expected encryption. Automated tests can be added in the future.
