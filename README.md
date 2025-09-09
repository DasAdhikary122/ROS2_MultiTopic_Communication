# ROS2_MultiTopic_Communication
Publisher-Subscriber project on ROS 2 Jazzy with dual topics.



📥 Setup

Download the full workspace ZIP file from this repository.

Unzip the file into your desired directory.

Open a terminal and navigate into the workspace folder.




## 🚀 How to Run

Open three separate terminals in your ROS 2 workspace.

### First Terminal – Publisher 1

```bash
source /opt/ros/jazzy/setup.bash
colcon build
source install/setup.bash
ros2 run kkr_comm pub1
```

### Second Terminal – Publisher 2

```bash
source /opt/ros/jazzy/setup.bash
colcon build
source install/setup.bash
ros2 run kkr_comm pub2
```

### Third Terminal – Subscriber

```bash
source /opt/ros/jazzy/setup.bash
colcon build
source install/setup.bash
ros2 run kkr_comm subscriber
```

---

## 📌 Features

* Dual publishers on `/kkr1` and `/kkr2`
* Single subscriber listening to both topics
* Built using Python & ROS 2 node structures

---

## 👤 Author

:- Suman Das Adhikary

📧 Contact: [sumandasadhikary457@gmail.cm](mailto:sumandasadhikary457@gmail.com)

---

## 📄 License

This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.

---

