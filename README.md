# Nginx Templates

Create nginx config template from command line.

## Installation

```bash
wget https://raw.githubusercontent.com/ShinChven/nginx-templates/master/nginx-templates.sh
chmod +x ./nginx-templates.sh
```

## Usage

```bash
# Command
./nginx-templates.sh <FILENAME> <TEMPLATE> <DOMAIN> <APP_URL>
# Example
./nginx-templates.sh test.conf 80 your.domain.com http://127.0.0.1:8080
```

## Templates

- 80: create nginx config template for 80 port.
- redirect: create nginx config template for rewriting domain.
