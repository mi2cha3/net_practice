# NetPractice

*This project has been created as part of the 42 curriculum by ktei.*

## Description

NetPractice is a comprehensive practical exercise designed to introduce the fundamentals of computer networking. This project focuses on configuring small-scale networks and understanding how devices communicate through routers and switches.

The main objectives are to:
- Learn how to configure IP addresses on network devices
- Understand TCP/IP addressing and subnet masks
- Set up routes and gateways for inter-network communication
- Connect multiple devices through routers and switches
- Solve 10 progressively complex networking problems

The project uses a web-based training interface to simulate real network configurations, allowing learners to practice network setup without requiring actual hardware.

## Instructions

### Prerequisites
- A modern web browser
- Python 3 (for running the local web server)
- Bash (for running the setup script)

### Running the Training Interface

1. Extract the project files to your desired location
2. Navigate to the project directory:
   ```bash
   cd /path/to/net_practice
   ```

3. Run the startup script:
   ```bash
   ./run.sh
   ```
   This will launch a local web server and open the training interface in your default web browser.

### Alternative Method (if run.sh doesn't work)

If the `run.sh` script fails, you can manually start the server:
```bash
python3 -m http.server 49242
```
Then open your browser and navigate to: `http://localhost:49242`

### Completing Levels

1. Enter your login in the interface to use your personal configuration
2. For each level, you'll see a network diagram with incomplete configuration
3. Modify the unshaded fields to complete the network configuration
4. Click **[Check again]** to verify your configuration
5. Once correct, click **[Next level]** to proceed

### Exporting Configurations

After completing each level, export your configuration:
1. Click **[Get my config]** button
2. Save the configuration file
3. Place it in the repository root with the appropriate name (e.g., `level1.json`, `level2.json`, etc.)

### Submission Requirements

- Complete all 10 levels
- Export the configuration file for each level
- Store all 10 configuration files at the repository root with names: `level1.json` through `level10.json`
- Include this README.md file
- Commit all files to your Git repository

## Resources

### Networking Concepts Covered

This project teaches the following fundamental networking concepts:

- **TCP/IP Addressing**: Understanding IPv4 address structure and classes
- **Subnet Masks**: How to divide networks into subnetworks for efficient routing
- **Default Gateway**: The router interface that packets use to leave a network
- **Routers**: Devices that forward packets between different networks
- **Switches**: Devices that connect multiple devices within the same network segment
- **OSI Layers**: Understanding the layered approach to network communication (particularly layers 2 and 3)
- **Routing Tables**: How devices determine where to send packets based on destination addresses
- **Network Interfaces**: Physical and logical connection points on network devices

### Additional Resources

- **RFC 791**: Internet Protocol (IP) - the foundational specification
- **RFC 792**: Internet Control Message Protocol (ICMP)
- **Cisco Networking Academy**: Comprehensive networking tutorials and documentation
- **Subnetting Guides**: Online subnet calculators and tutorials for understanding CIDR notation

### AI Usage

AI tools were used to assist with the following aspects of this project:
- Understanding complex networking concepts and providing explanations
- Calculating subnet masks and IP address ranges
- Debugging network configuration issues
