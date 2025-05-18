# 🚗 Software Defined Vehicle (SDV) Learning Journey

Welcome to my self-guided learning journey to master **Software Defined Vehicles (SDVs)**. This repository documents my research, notes, experiments, and hands-on projects in the SDV ecosystem using C++, ROS2, VSS, and modern automotive middleware.

---

## 📌 Goals

- Understand SDV architecture and layered software stacks
- Build signal-based and service-based communication modules
- Learn AUTOSAR Adaptive, ROS2, vsomeip, and VSS
- Contribute to open-source SDV projects

---

## 📚 Learning Phases

### ✅ Phase 1: SDV Foundations
- [x] SDV architecture overview
- [x] Eclipse SDV, SOAFEE, AGL
- [x] Vehicle Signal Specification (VSS)

### ✅ Phase 2: Vehicle Signals
- [x] KUKSA.val setup & simulation
- [ ] Add custom signals using VSS schema
- [ ] MQTT signal publishing demo

### ✅ Phase 3: Middleware (C++)
- [ ] Learn vsomeip and ara::com
- [ ] Create a C++ service and client
- [ ] Explore Fast DDS with ROS2

### ✅ Phase 4: ROS2 + Autoware
- [ ] Install ROS2 Foxy / Humble
- [ ] ROS2 pub/sub with vehicle signals
- [ ] Autoware sensor node demo

### ✅ Phase 5: OS & Containers
- [ ] AGL sample app in Docker
- [ ] Create Yocto layer for demo ECU
- [ ] Understand SOAFEE orchestration

### ✅ Phase 6: Security & OTA
- [ ] Read about Uptane
- [ ] Explore secure firmware update mechanism

---

## 🔧 Projects

| Project | Folder | Description |
|--------|--------|-------------|
| Vehicle Signal Publisher | `01_vehicle_signals/kuksa_val_demo` | Publish mock signals to kuksa.val |
| SOME/IP Service | `02_middleware/vsomeip_demo` | A simple service-client example |
| ROS2 Lane Detection | `03_ros2_autoware/lane_detection_node` | Node to detect lanes using OpenCV |
| AGL Container App | `04_sdvos_containers/docker_agl_app` | Minimal AGL GUI service |

---

## 📚 Resources

- [Eclipse SDV](https://sdv.eclipse.org)
- [SOAFEE](https://soafee.io/)
- [VSS by COVESA](https://github.com/COVESA/vehicle_signal_specification)
- [KUKSA.val](https://github.com/eclipse/kuksa.val)
- [vsomeip](https://github.com/COVESA/vsomeip)
- [ROS2](https://docs.ros.org/en/foxy/index.html)
- [Autoware](https://github.com/autowarefoundation/autoware.universe)

---

## 🤝 Contributions

This is a personal learning repo, but feel free to fork it or open a PR if you want to collaborate or suggest a resource.

---

## 📜 License

MIT License
