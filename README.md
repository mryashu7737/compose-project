# YASH SHARMA DOCKER_COMPOSE_ JOOMLA_PROJECT

## Project Overview

This project provides a Docker Compose configuration to set up a Joomla! content management system (CMS) environment quickly. A platform for creating websites and online apps, Joomla! is open-source and free.

## Features

- *Fast Deployment*: Quick setup is made possible by using Docker Compose to orchestrate Joomla! and its necessary services.
- *Scalability*: Docker's features make it simple to scale services as needed.
- *Isolation*: Makes sure Joomla! is isolated from other apps and operates in a containerised environment.


## Tech Stack

- *Joomla!*: The main application for content management.
- *MySQL*: The relational database used to store Joomla! content and configurations.
- *Docker*: Container platform to package and run applications.
- *Docker Compose*: Tool for defining and running multi-container Docker applications.

<div style="text-align: center;> 
   
## Snapshot of Executing :

### 1. Run docker-compose up on the system.
---

<img src="/SnapShots/Start_Docker-App.png">

### 2. Internally execute the process of creating Joomla and MySQL server on the system.
---
<img src="/SnapShots/DockerApp-processing.png">

### 3. Verify the running containers on the system.
---

<img src="/SnapShots/Inspect_IP_Of_Container.png">


### 4. Screenshot of the Joomla! sample site homepage.
---

<img src="/SnapShots/Check_MSQ_DB_Details.png">


### 5. Configure Joomla on the system (first page setup).
---

<img src="/SnapShots/Config_Joomla_webPage.png">

### 6. Connect an external device to the Linux system, then check the docker-compose.yaml file on the external device.
---

<img src="/SnapShots/docker-compose code.jpg">



###: 7. Check the Docker version and start Docker Compose.
---

<img src="/SnapShots/Execute_docker-compose.jpg">

### 8. Install Joomla and MySQL on the external device.
---

<img src="/SnapShots/Process_Executing_docker-compose.jpg">

### 9. Access Joomla via the IP address on the external device.
---

<img src="/SnapShots/Searching_On_Device_By_IP.jpg">

### 10. Confirm successful Joomla installation on the external device.
---

<img src="/SnapShots/JOOMLA_web_Page.jpeg">

### 11. Fill in the configuration page and enter the required details in the Joomla database on the external device.
---

<img src="/SnapShots/Seting_DB_via_JOOMLA.jpeg">

### 12. Review the Joomla configuration overview on the external device.
---

<img src="/SnapShots/JOOMLA_OverView.jpeg">

###: 13. Complete the Joomla installation on the external device.
---

<img src="/SnapShots/Installing_JOOMPLA_API.jpeg">

### 14. Access the Joomla login page.
---

<img src="/SnapShots/JOOMLA_LOGIN.jpeg">


### 15. Navigate to the Joomla control panel dashboard on the external device.
---

<center><img src="/SnapShots/Access_JOOMLA.jpeg" height=40% width=30% ></center>


###: 16. Verify the database and schema on the system.
---

<img src="/SnapShots/MySQL_DB_Run_Inside_D_Container.png">

### 17. Check database details, including table creation status.

---

<img src="/SnapShots/Check_Docker_Images.png" >




</div>

## Installation

1. Clone the repository:
   ```bash
   https://github.com/mryashu7737/compose-project
