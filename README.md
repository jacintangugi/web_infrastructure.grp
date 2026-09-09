
# Web Infrastructure - Client & Server on One Linux Machine

**Module:** Web Infrastructure  
**Group:** Web Infrastructure Group  
**Team Members:** JACINTA WACUKA, GRACE UMWIZA, NWANDO UKOH, ABDULJABAR  
**Submission Date:** 06th September 2026

---

## Overview

This repository contains our technical report and supporting files for the **Web Infrastructure Assessment**.

Using **Parrot Security OS 7.3**, we configured and tested SSH, NGINX, HTTP, Telnet, a public REST API, and troubleshooting procedures on a single Linux machine.

The project demonstrates that **client and server are roles that can operate on the same machine** using `127.0.0.1`.

---

## Environment

| Item | Value |
|---|---|
| OS | Parrot Security OS 7.3 |
| Web Server | NGINX |
| SSH | OpenSSH |
| Test Host | 127.0.0.1 |
| HTTP Port | 80 |
| SSH Port | 22 |
| Tools | SSH, SCP, SFTP, cURL, Telnet |
| API | JSONPlaceholder |

---

## What's Covered

### 1. SSH

- Installed and verified OpenSSH.
- Tested password and public-key authentication.
- Generated an SSH key pair.
- Demonstrated SCP and SFTP file transfer.

### 2. NGINX & HTTP

- Installed and configured NGINX.
- Hosted a custom website.
- Created a custom 404 page.
- Tested GET, HEAD, POST, PUT and DELETE.
- Tested HTTP status codes including 200, 201, 204, 403, 404 and 405.
- Added and verified a custom HTTP response header.

### 3. Telnet & Raw HTTP

- Tested SSH on port 22 and NGINX on port 80.
- Stopped and restarted NGINX to test service availability.
- Sent a raw HTTP request using Telnet.
- Inspected the HTTP response, headers and body.

### 4. Public API Testing

- Used the JSONPlaceholder public REST API.
- Tested GET and POST requests.
- Tested query parameters.
- Deliberately triggered a 404 error and corrected the request.

### 5. Troubleshooting

- Deliberately introduced a website permissions error.
- Used NGINX logs and service checks to investigate the problem.
- Identified the cause and restored the correct permissions.
- Verified recovery using cURL and a successful HTTP response.

---

## Security

- Used SSH public-key authentication.
- Protected private SSH keys and passwords.
- No sensitive credentials are included in the repository.
- Only public SSH keys may be included where required.

---

## Testing & Evidence

The project is supported by screenshots and terminal evidence covering:

- Linux and SSH configuration
- NGINX and website hosting
- HTTP testing
- Telnet and raw HTTP
- API requests
- Troubleshooting and recovery

---

## Team Collaboration

GitHub was used for version control, file sharing, documentation and collaboration.

---

## Contributors

- **JACINTA WACUKA**
- **GRACE UMWIZA**
- **NWANDO UKOH**
- **ABDULJABAR**

---

## Assessment

**Course:** Web Infrastructure Assessment  
**Year:** 2026  
**Project:** Client & Server on One Linux Machine

## Repository Link

https://github.com/jacintangugi/web_infrastructure.grp.git

