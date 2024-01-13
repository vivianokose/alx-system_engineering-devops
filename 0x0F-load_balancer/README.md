# 0x0F. Load balancer

This project explores load balancing techniques to improve web application performance, reliability and scalability. The goal is to learn how load balancers distribute traffic and how to configure common load balancing tools.

## Learning Objectives

- What is a load balancer
- What are the main types of load balancers
- What are the benefits of using a load balancer
- How to configure HAProxy and Nginx as load balancers
- How DNS roundrobin works
- How to configure a load balancer with Ubuntu, Nginx and HAproxy
- How to optimize load balancing

## Project Overview

The projects are split into the following tasks:

- 0-custom_http_response-header - Nginx configuration that adds custom HTTP header 
- 1-install_load_balancer - Bash script that installs, configures and secures HAproxy on Ubuntu
- 2-puppet_custom_nginx_config - Puppet manifest that configures Nginx as a load balancer
- 3-debug_nginx_config - Debug invalid Nginx configuration
- 4-healthcheck_nginx - Configure Nginx to add an active health check URL

## Usage

Each task provides configuration files and instructions to deploy load balancing solutions.

## Testing

Manual testing is done by simulating traffic loads and validating expected behavior. Automated tests can be added in the future.
