# Infrared (IR) Sensors

## 1. Introduction

An infrared (IR) sensor is a device that detects infrared radiation or uses infrared light to identify objects, measure distances, or detect movement.

Infrared radiation is electromagnetic radiation that lies beyond the red end of the visible spectrum. IR sensors are commonly used in robotics, security systems, remote controls, and industrial automation.

## 2. Working Principle

IR sensors operate by detecting or emitting infrared radiation.

In an active IR sensing system, an infrared emitter sends IR light toward an object. A receiver detects the reflected light. The amount of received light can help the system identify an object or estimate its position.

Passive infrared (PIR) sensors work differently. They detect changes in infrared radiation from objects, especially warm bodies moving across the sensor's field of view. PIR sensors do not need to emit infrared light.

## 3. Types of IR Sensors

### 3.1 Active IR Sensors

Active IR sensors use an infrared emitter and a receiver.

- **Working principle:** The receiver detects IR light reflected from an object or interrupted by an object.
- **Applications:** Obstacle detection, object counting, and line-following robots.
- **Limitations:** Performance can depend on surface reflectivity, ambient light, and sensor alignment.

### 3.2 Passive Infrared (PIR) Sensors

PIR sensors detect changes in infrared radiation within their field of view.

- **Applications:** Motion-activated lights, security alarms, and occupancy detection.
- **Advantages:** Low power consumption and no need for an IR emitter.
- **Limitations:** They generally detect changes associated with movement rather than providing an exact distance measurement.

### 3.3 IR Temperature Sensors

These sensors estimate an object's surface temperature by detecting infrared radiation emitted by the object.

- **Applications:** Non-contact temperature measurement and equipment monitoring.
- **Limitations:** Readings can be affected by emissivity, distance, and the surrounding environment.

### 3.4 IR Break-Beam Sensors

A break-beam system places an IR emitter opposite a receiver. When an object interrupts the beam, the system detects the interruption.

- **Applications:** Object counting, entry detection, and position sensing.
- **Limitations:** Emitter and receiver alignment is important.

## 4. Important Characteristics

- **Detection range:** The distance over which the sensor can operate reliably.
- **Field of view:** The region monitored by the sensor.
- **Response time:** How quickly the sensor responds to a change.
- **Sensitivity:** The smallest relevant change the sensor can detect.
- **Ambient-light tolerance:** How well the sensor performs under different lighting conditions.
- **Operating wavelength:** The infrared wavelength used or detected by the sensor.

Exact specifications depend on the sensor model and its intended application.

## 5. Applications

- Robot obstacle detection
- Line-following robots
- Motion-activated lighting
- Security and occupancy systems
- Object counting and position detection
- Remote-control receivers
- Non-contact temperature measurement

## 6. Advantages and Limitations

**Advantages**

- Many IR sensors are compact and inexpensive.
- Some designs support non-contact detection.
- PIR sensors can operate with low power consumption.
- IR technology is useful for a wide range of sensing tasks.

**Limitations**

- Some active IR sensors are affected by ambient light and object reflectivity.
- PIR sensors may not detect stationary objects reliably.
- Smoke, dust, or other obstructions can affect certain IR sensing systems.
- IR temperature readings depend on surface properties and measurement conditions.
- Different IR sensor types are designed for different purposes and are not interchangeable.

## 7. References

- [Arduino Documentation](https://docs.arduino.cc/)
- [Analog Devices](https://www.analog.com/) — sensor and infrared measurement resources

Consult the manufacturer's datasheet for the exact sensor's operating range, output type, and electrical requirements.

---

[Back to Sensor Knowledge Base](../README.md)
