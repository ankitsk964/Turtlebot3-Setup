Here's the reformatted README file with highlighted code and links:

---

## Step 1 – Download Ubuntu 22.04.4 LTS Desktop (Jammy Jellyfish)

Download from the official website:

[Ubuntu 22.04.4 LTS Desktop](https://releases.ubuntu.com/jammy/)

---

## Step 2 – Download ROS2 Humble Hawksbill

Download from the official website:

[ROS2 Humble Hawksbill Installation Guide](https://docs.ros.org/en/humble/Installation/Ubuntu-Install-Debians.html)

---

### 1. Install Dependent ROS 2 Packages

Open the terminal with `Ctrl+Alt+T` from Remote PC.

Install Gazebo 11.10.2:

```bash
sudo apt install ros-humble-gazebo-*
```

---

### 2. Install Cartographer

```bash
sudo apt install ros-humble-cartographer
```

```bash
sudo apt install ros-humble-cartographer-ros
```

---

### Install Navigation2

```bash
sudo apt install ros-humble-navigation2
```

```bash
sudo apt install ros-humble-nav2-bringup
```

---

### Install TurtleBot3 Packages

Install TurtleBot3 via Debian Packages:

```bash
source ~/.bashrc
```

```bash
sudo apt install ros-humble-dynamixel-sdk
```

```bash
sudo apt install ros-humble-turtlebot3-msgs
```

```bash
sudo apt install ros-humble-turtlebot3
```

Click [here](https://example.com) to expand more details about building TurtleBot3 package from source. *(Replace with actual link)*

---

### Environment Configuration

Set the ROS environment for PC:

```bash
echo 'export ROS_DOMAIN_ID=30 #TURTLEBOT3' >> ~/.bashrc
```

```bash
source ~/.bashrc
```

---

Feel free to replace the placeholder link with the actual URL if you have one. If you need any further adjustments, let me know!
