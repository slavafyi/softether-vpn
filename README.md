# SoftEther VPN Server

A simple, containerized SoftEther VPN server deployment using Docker Compose. This setup provides multiple VPN protocols including OpenVPN, L2TP/IPsec, and HTTPS tunneling.

## Quick Start

Run this single command on your Ubuntu/Debian server:

```bash
curl -s https://raw.githubusercontent.com/slavafyi/softether-vpn/refs/heads/main/install | bash
```

That's it! The script will:
1. Install Docker and Docker Compose
2. Clone this repository
3. Start the SoftEther VPN server

## Manual Installation

If you prefer to install manually:

```bash
# Clone the repository
git clone https://github.com/slavafyi/softether-vpn.git
cd softether-vpn

# Start the service
docker compose up -d
```

## Documentation

- [SoftEther VPN Documentation](https://www.softether.org/4-docs)
- [Docker Hub Image](https://hub.docker.com/r/softethervpn/vpnserver)

## Contributing

Feel free to submit issues and pull requests to improve this setup.

## License

This project is licensed under the MIT License.
