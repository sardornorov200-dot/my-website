# Personal Website — NGINX Deployment

A static personal website deployed using NGINX on an Ubuntu Linux virtual machine.

## Live Demo

- Vercel: https://bonooooo.vercel.app
- NGINX (temporary ngrok URL): https://nag-timing-swear.ngrok-free.dev

## Technologies

- HTML5
- CSS3
- Ubuntu Linux
- NGINX
- Git & GitHub
- UFW Firewall
- ngrok

## NGINX Configuration

The website is hosted from `/var/www/html` using NGINX.

Key configurations:
- HTTP server on port 80
- Document root configuration
- Static file serving
- NGINX service management
- Firewall configuration
- NGINX configuration validation using `nginx -t`

## Project Structure

- `index.html` — Main webpage
- `style.css` — Website styling
- `background.jpg` — Background image
- `favicon.png` — Website favicon
- `logo.svg` — Website logo
- `nginx/default.conf` — NGINX configuration backup

## Deployment

The website was deployed on an Ubuntu Linux VM using NGINX and exposed publicly through ngrok.

The project is also deployed on Vercel.

## Learning Outcomes

- Hosting static websites with NGINX
- Working with Linux web server configuration
- Managing services with systemd
- Understanding HTTP and HTTPS
- Configuring firewall rules with UFW
- Using Git for version control
