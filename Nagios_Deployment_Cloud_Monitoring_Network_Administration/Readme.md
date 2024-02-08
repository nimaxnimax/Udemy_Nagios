
![Alt text](image.png)

Udemy Course >> Nagios Deployment Cloud Monitoring & Network Administration

Nagios for Cloud Monitoring and Network Administration - Nagios Core Infrastructure Deployment - System Administration + Lab


**********

Tips/Tricks/Notes/Commands URL Link: 
https://github.com/nimaxnimax/Udemy_Nagios

Instructor & Courses >> 
https://www.udemy.com/user/adrian-fischer-infotech/


**********

Nagios is a popular open-source monitoring system that helps organizations track the status and health of their IT infrastructure. Here's an overview of Nagios in bullet points:

- **Purpose:**
  - Nagios is designed for monitoring the availability and performance of computers, network devices, applications, and services.

- **Key Features:**
  - **Host Monitoring:** Monitors the status of hosts (devices or servers) on a network.
  - **Service Monitoring:** Monitors specific services or applications running on hosts.
  - **Alerting:** Sends notifications when a problem or downtime is detected.
  - **Performance Graphs:** Provides graphical representations of performance data over time.
  - **Event Handling:** Allows automated responses to specific events or issues.
  - **Extensibility:** Supports plugins to extend monitoring capabilities.

- **Components:**
  - **Nagios Core:** The core monitoring engine that executes checks and processes results.
  - **Plugins:** External scripts or programs that perform the actual monitoring.
  - **NRPE (Nagios Remote Plugin Executor):** Allows Nagios to execute plugins on remote Linux/Unix machines.
  - **NSCA (Nagios Service Check Acceptor):** Facilitates the communication between Nagios and passive (externally generated) checks.

- **Configuration:**
  - Nagios configurations are defined in text files.
  - Configuration includes hosts, services, notification settings, and more.
  - Changes to configurations require restarting Nagios for them to take effect.

- **Web Interface:**
  - Nagios provides a web-based interface for monitoring and managing alerts.
  - Users can acknowledge and schedule downtime for hosts/services through the interface.

- **Alerting and Notifications:**
  - Nagios can send notifications via email, SMS, or other methods.
  - Notifications are triggered based on defined thresholds and criteria.

- **State Types:**
  - **OK:** The monitored item is functioning properly.
  - **Warning:** The item is experiencing issues but is still operational.
  - **Critical:** The item is in a state that requires immediate attention.
  - **Unknown:** The status of the item cannot be determined.

- **Community and Add-ons:**
  - Nagios has a large and active community that contributes plugins and extensions.
  - Nagios XI is a commercial version with additional features and a more user-friendly interface.

- **Use Cases:**
  - Commonly used for server and network monitoring in IT environments.
  - Suitable for both small-scale and large-scale deployments.

- **Compatibility:**
  - Supports monitoring various operating systems, including Linux, Windows, and Unix.

- **Scalability:**
  - Nagios can be scaled horizontally to handle a growing number of monitored hosts and services.

- **Documentation:**
  - Nagios has comprehensive documentation available to assist with installation, configuration, and troubleshooting.


**********

This course is ideally suited for IT professionals, system administrators, network engineers, cloud architects, and anyone responsible for managing and monitoring IT infrastructure. Here's why various professionals should consider learning Nagios for Cloud Monitoring & Network Administration:

1. **System Administrators**: System administrators are responsible for ensuring the stability, performance, and security of IT systems. Learning Nagios empowers system administrators to proactively monitor system health, identify potential issues before they escalate, and maintain optimal performance across diverse environments, whether on-premises or in the cloud.

2. **Network Engineers**: Network engineers play a crucial role in designing, implementing, and managing network infrastructure. Nagios equips network engineers with the tools to monitor network devices, track bandwidth usage, and troubleshoot connectivity issues, thereby optimizing network performance and ensuring seamless communication across the organization.

3. **Cloud Architects**: With the increasing adoption of cloud computing, cloud architects are tasked with designing and managing cloud environments efficiently. Understanding Nagios for cloud monitoring enables cloud architects to implement comprehensive monitoring solutions that provide visibility into cloud resources, ensure service availability, and optimize resource utilization, ultimately enhancing the reliability and performance of cloud deployments.

4. **DevOps Engineers**: DevOps engineers focus on streamlining the software development lifecycle through automation, collaboration, and continuous integration/continuous deployment (CI/CD) practices. Integrating Nagios into DevOps workflows enables DevOps engineers to incorporate monitoring into their automation pipelines, facilitating early detection of issues, rapid response to incidents, and continuous improvement of application performance and reliability.

5. **IT Managers and Team Leads**: IT managers and team leads are responsible for overseeing IT operations and ensuring alignment with organizational goals. Learning Nagios enables IT managers to implement robust monitoring strategies, track key performance indicators (KPIs), and make data-driven decisions to optimize resource allocation, improve service quality, and enhance the overall efficiency of IT operations.

Anyone involved in IT operations, infrastructure management, or cloud deployment can benefit from learning Nagios for Cloud Monitoring & Network Administration. By mastering Nagios, professionals can enhance their ability to monitor, manage, and optimize IT infrastructure effectively, leading to improved reliability, performance, and scalability across the organization.


**********

Nagios offers several advantages that make it a popular choice for monitoring IT infrastructure:

1. **Flexibility**: Nagios is highly customizable, allowing users to monitor a wide range of devices, applications, and services across heterogeneous environments, including on-premises, virtualized, and cloud-based infrastructures.

2. **Scalability**: Nagios is scalable, capable of monitoring small-scale deployments as well as large, distributed environments with thousands of devices and services. Its modular architecture enables users to add additional monitoring nodes and scale resources to accommodate growing monitoring requirements.

3. **Extensibility**: Nagios's plugin architecture allows users to extend its functionality by integrating with third-party tools, APIs, and scripts. This extensibility enables users to monitor virtually any aspect of their infrastructure, customize alerting mechanisms, and integrate Nagios with existing systems and processes.

4. **Alerting and Notifications**: Nagios provides robust alerting and notification capabilities, allowing users to define flexible alerting rules based on specific conditions and thresholds. Users can receive alerts via email, SMS, or other communication channels, ensuring timely notification of critical events and enabling rapid response to incidents.

5. **Centralized Monitoring**: Nagios offers centralized monitoring capabilities, enabling users to monitor and manage multiple servers, devices, and services from a single dashboard. This centralized approach facilitates efficient monitoring and troubleshooting, simplifies administration, and enhances visibility into the overall health and performance of the IT infrastructure.

6. **Historical Reporting and Trend Analysis**: Nagios provides historical reporting and trend analysis features, allowing users to track performance metrics over time, identify patterns, and forecast future resource requirements. These insights enable proactive capacity planning, performance optimization, and trend analysis for informed decision-making.

Regarding port numbers and protocols supported by Nagios, here are some key points:

- Nagios primarily uses the Simple Network Management Protocol (SNMP) for monitoring network devices such as routers, switches, and firewalls. SNMP operates over UDP (User Datagram Protocol) and typically uses port 161 for SNMP queries and port 162 for SNMP traps.

- For monitoring services and applications on remote hosts, Nagios typically uses various protocols such as ICMP (Internet Control Message Protocol) for ping checks, TCP (Transmission Control Protocol) for port checks, and HTTP/HTTPS for web server checks. The specific port numbers depend on the services being monitored. For example, port 80 for HTTP, port 443 for HTTPS, etc.

- Nagios also supports plugins and scripts for monitoring custom services and applications. These plugins can communicate using different protocols and port numbers depending on the requirements of the service being monitored.

Nagios provides flexibility in terms of protocols and port numbers, allowing users to monitor a wide range of devices, services, and applications across diverse environments.

**********

How to Install Nagios Monitoring Tool on Ubuntu 20 and 22

Nagios is a powerful free, open-source monitoring tool used for monitoring Linux and Windows servers and networks and infrastructure. With Nagios, you can monitor CPU usage, disk usage, and several services including HTTP, SSH, FTP, SMTP, and more. It has a simple and user-friendly web interface that helps you monitor all servers from the central location. It can be easily integrated with third-party applications with multiple APIs. Nagios works by continuously monitoring hosts and services that you specify and alerting you when things go bad.

This tutorial will show you how to install Nagios Core on Ubuntu 22.04 server.

Prerequisites
- A server running Ubuntu 22.04.
- A root password is configured on the server.

Install Required Dependency

Before starting, you will need to update your system package and install other required dependencies on your server:

```bash
sudo apt-get update -y
sudo apt-get install wget unzip vim curl openssl build-essential libgd-dev libssl-dev libapache2-mod-php php-gd php apache2 -y
```

Install Nagios Core from Source

By default, the latest Nagios Core version is unavailable in the 22.04 default repository. So it is recommended to compile Nagios from the source.

First, download the latest version of Nagios Core from the Git repository with the following command:

```bash
wget https://assets.nagios.com/downloads/nagioscore/releases/nagios-4.4.10.tar.gz
```

Once downloaded, extract the downloaded file with the following command:

```bash
tar -xvzf nagios-4.4.10.tar.gz
```

Next, change the directory to the extracted directory and configure the Nagios Core with the following command:

```bash
tar -xvzf nagios-4.4.10.tar.gz
```

Next, change the directory to the extracted directory and configure the Nagios Core with the following command:

```bash
cd nagios-4.4.10/
sudo ./configure --with-httpd-conf=/etc/apache2/sites-enabled
```

Next, run the following command to compile the Nagios:

```bash
sudo make all
```

Next, create the required user and group, and add Nagios user to the www-data group with the following command:

```bash
sudo make install-groups-users
sudo usermod -a -G nagios www-data
```

Next, install the Nagios Core using the following command:

```bash
sudo make install
```

Once the Nagios Core is installed, you will need to create a systemd service file to manage the Nagios service. You can create the systemd init script with the following command:

```bash
sudo make install-daemoninit
```

Next, set the proper permission on the Nagios installation directory with the following command:

```bash
sudo make install-commandmode
```

Next, create a sample Nagios configuration file with the following command:

```bash
sudo make install-config
```

Next, install the Nagios web interface with the following command:

```bash
sudo make install-webconf
sudo a2enmod rewrite cgi
```

Next, restart the Apache service to apply the changes:

```bash
sudo systemctl restart apache2
```

Next, install the theme for the Nagios web interface.

```bash
sudo make install-exfoliation
```

Create Nagios Admin User

Next, you will need to create an admin user to access the Nagios web interface. You can create it with the following command:

```bash
sudo htpasswd -c /usr/local/nagios/etc/htpasswd.users nagiosadmin
```

Install Nagios Plugins

Next, you will need to download the Nagios plugins to monitor the system services. You can download it from the Git repository with the following command:

```bash
wget https://github.com/nagios-plugins/nagios-plugins/releases/download/release-2.4.0/nagios-plugins-2.4.0.tar.gz
```

Once downloaded, extract the downloaded file with the following command:

```bash
sudo tar -xvzf nagios-plugins-2.4.0.tar.gz
```

Next, change the directory to extracted directory and configure it with the following command:

```bash
cd nagios-plugins-2.4.0
sudo ./configure --with-nagios-user=nagios --with-nagios-group=nagios
```

Next, install it with the following command:

```bash
sudo make
sudo make install
```

Next, verify the sample Nagios configuration files before starting it with the following command:

```bash
sudo /usr/local/nagios/bin/nagios -v /usr/local/nagios/etc/nagios.cfg
```

Start Nagios Service

Now, start the Nagios service and enable it to start at system reboot with the following command:

```bash
sudo systemctl start nagios
sudo systemctl enable nagios
```

You can also check the status of the Nagios service with the following command:

```bash
sudo systemctl status nagios
```

Access Nagios Web Interface

Now, open your web browser and type the URL http://your-server-ip/nagios. You will be redirected to the Nagios login screen.

Provide your Nagios admin username, password and click on the OK button. You should see the Nagios default dashboard.

Nagios and the required plugins are installed.


Configuring Nagios

To monitor servers, we have to configure Nagios by editing the file /usr/local/nagios/etc/nagios.cfg.

```bash
sudo vi /usr/local/nagios/etc/nagios.cfg
```

Uncommment the line cfg_dir=/usr/local/nagios/etc/servers and save the file.

```bash
cfg_dir=/usr/local/nagios/etc/servers
```

Create the folder to store configurations:

```bash
sudo mkdir -p /usr/local/nagios/etc/servers
sudo mkdir -p /usr/local/nagios/etc/printers
sudo mkdir -p /usr/local/nagios/etc/switches
sudo mkdir -p /usr/local/nagios/etc/routers
```

Configure the contact email address in the file /usr/local/nagios/etc/objects/contacts.cfg

```bash
sudo vi /usr/local/nagios/etc/objects/contacts.cfg
```

Restart the service:

```bash
sudo systemctl restart nagios
sudo systemctl status nagios
```


Monitoring a Server with the NPRE service

The NPRE service

(Nagios Remote Plugin Executor) is an add-on that allows you to execute Nagios commands on a remote Linux servers. It is basically used to gather “local” information (like disk usage, RAM usage, CPU usage) of a remote machine. As these information are not broadcasted on the Internet, an agent has to run on the server which reports to the Nagios server.

These steps have to be done on the remote server.

Install the software on the remote server:

```bash
sudo apt update -y
sudo apt install autoconf gcc libc6 libmcrypt-dev make libssl-dev wget bc gawk dc build-essential snmp libnet-snmp-perl gettext -y
```

Download and unpack NRPE:

```bash
wget --no-check-certificate -O nrpe.tar.gz https://github.com/NagiosEnterprises/nrpe/archive/master.tar.gz
tar xzf nrpe.tar.gz
```

Compile it with the following commands:

```bash
cd nrpe-master
sudo ./configure --enable-command-args
sudo make all
```

Create users and groups:

```bash
sudo make install-groups-users
```

Install the configuration files:

```bash
sudo make install-config
```

Install NRPE:

```bash
sudo make install
```

Install the service, so NPRE can be managed by systemd:

```bash
sudo make install-init
sudo systemctl enable nrpe.service
```

Edit the file /usr/local/nagios/etc/nrpe.cfg. Replace IP_of_your_Nagios_Server with the IP address of your Nagios host:

```bash
sudo vi /usr/local/nagios/etc/nrpe.cfg
```

```bash
allowed_hosts=127.0.0.1,IP_of_your_Nagios_Server
```

Restart the service:

```bash
sudo systemctl start nrpe.service
```

Download and install the Nagios plugins:
URL >> https://nagios-plugins.org/download/?C=M;O=D

```bash
cd ..
wget https://nagios-plugins.org/download/nagios-plugins-2.4.8.tar.gz
tar xfz nagios-plugins-2.4.8.tar.gz
cd nagios-plugins-2.4.8
sudo ./configure
sudo make all
sudo make install
```

The following steps have to be done on the Nagios server

On the Nagios server, create a configuration file in the directory /usr/local/nagios/etc/servers/ for each remote host that we want to monitor:

```bash
ls -anp /usr/local/nagios/etc/servers/ 
sudo vi /usr/local/nagios/etc/servers/remote_host.cfg
```

Replace remote_host with the name of the remote server and put the following content in the file:

```bash
# Remote Host configuration file
define host {
use linux-server
host_name remote_host
alias Remote Host
address 163.172.168.167
register 1
}
define service {
host_name remote_host
service_description PING
check_command check_ping!100.0,20%!500.0,60%
max_check_attempts 2
check_interval 2
retry_interval 2
check_period 24x7
check_freshness 1
contact_groups admins
notification_interval 2
notification_period 24x7
notifications_enabled 1
register 1
}
define service {
host_name remote_host
service_description Disk Usage
check_command check_local_disk!20%!10%!/
max_check_attempts 2
check_interval 2
retry_interval 2
check_period 24x7
check_freshness 1
contact_groups admins
notification_interval 2
notification_period 24x7
notifications_enabled 1
register 1
}
define service {
host_name remote_host
service_description SSH Service
check_command check_ssh
max_check_attempts 2
check_interval 2
retry_interval 2
check_period 24x7
check_freshness 1
contact_groups admins
notification_interval 2
notification_period 24x7
notifications_enabled 1
register 1
}
```

This file will monitor if the remote host replies on ping, the disk usage of the host and if the SSH service is up. You can find more configuration examples in the file /usr/local/nagios/etc/objects/commands.cfg. Nagios allows you to monitor a wide range of services.

More commands:

```bash
cat /usr/local/nagios/etc/objects/commands.cfg
```

Save the file and restart the application:

```bash
sudo systemctl restart nagios
sudo systemctl status nagios
```

The remote server will appear in your Nagios interface and you can see the status of the monitored services.


**********

Nagios and Docker



**********

Nagios Documents >>

URL >> https://assets.nagios.com/downloads/nagioscore/docs/nagioscore/4/en/index.html
URL >> https://support.nagios.com/kb/article/nagios-core-installing-nagios-core-from-source-96.html#Ubuntu
URL >> https://support.nagios.com/kb/article/nagios-core-performance-graphs-using-pnp4nagios-801.html#Ubuntu


**********

Tips/Tricks/Notes/Commands URL Link: 
https://github.com/nimaxnimax/Udemy_Nagios

Instructor & Courses >> 
https://www.udemy.com/user/adrian-fischer-infotech/

