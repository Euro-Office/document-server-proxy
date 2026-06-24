# Euro-Office Document Server example configurations for proxy

[![Config Test](https://github.com/Euro-Office/document-server-proxy/actions/workflows/ci.yml/badge.svg)](https://github.com/Euro-Office/document-server-proxy/actions/workflows/ci.yml)
[![Build Status](https://travis-ci.org/Euro-Office/document-server-proxy.svg?branch=master)](https://travis-ci.org/Euro-Office/document-server-proxy)

This repository contains the configuration files for the web-servers to proxy traffic to the Euro-Office DocumentServer.

## Examples

### Apache

- [Minimal](apache/minimal.conf)
- [Proxy HTTPS to HTTP](apache/proxy-https-to-http.conf)
- [Proxy HTTPS to HTTPS](apache/proxy-https-to-https.conf)
- [Proxy to virtual path](apache/proxy-to-virtual-path.conf)

### HAProxy

- [Minimal](haproxy/minimal.cfg)
- [Proxy HTTPS to HTTP](haproxy/proxy-https-to-http.cfg)
- [Proxy to virtual path](haproxy/proxy-to-virtual-path.cfg)
- [Active-active](haproxy/active-active.cfg)
- [Hot standby](haproxy/hot-standby.cfg)

### HAProxy 1.4

- [Cluster](haproxy-1.4/cluster/haproxy.cfg)
- [Proxy HTTPS to HTTP](haproxy-1.4/proxy-https-to-http/haproxy.cfg)

### IIS

- [Proxy to virtual path](iis/proxy-to-virtual-path/) ([README](iis/proxy-to-virtual-path/README.md))

### Nginx

- [Minimal](nginx/minimal.conf)
- [Proxy HTTPS to HTTP](nginx/proxy-https-to-http.conf)
- [Proxy to virtual path](nginx/proxy-to-virtual-path.conf)
- [Ansible playbook (virtual path)](nginx/ansible/) ([README](nginx/ansible/README.md))
- [Notes](nginx/Readme.md)

### Nginx Proxy Manager

- [Proxy to virtual path](nginx-proxy-manager/README.md)

### Traefik v1

- [Minimal](traefik/v1/minimal.toml)
- [Proxy HTTPS to HTTP](traefik/v1/proxy-https-to-http.toml)
- [Proxy to virtual path](traefik/v1/proxy-to-virtual-path.toml)

### Traefik v2/v3

- [Proxy to virtual path](traefik/v2-v3/proxy-to-virtual-path.yml)
