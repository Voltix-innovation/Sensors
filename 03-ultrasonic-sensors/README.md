# Ultrasonic Sensors

## 1. Introduction

An ultrasonic sensor uses high-frequency sound waves to detect objects or measure distance. These sound waves have frequencies above the typical range of human hearing, which is approximately 20 kHz.

Ultrasonic sensors are widely used in robotics, industrial automation, vehicle parking systems, and object detection.

## 2. Working Principle

Many ultrasonic distance sensors operate using the time-of-flight principle.

1. The sensor emits an ultrasonic pulse.
2. The sound wave travels through the air and reaches an object.
3. Part of the sound wave reflects back as an echo.
4. The sensor measures the time taken for the echo to return.
5. The distance is calculated using the speed of sound and the measured time.

## 3. Distance Calculation

For a typical pulse-and-echo sensor:

**Distance = (Speed of Sound × Echo Time) / 2**

The division by 2 is necessary because the sound travels to the object and then returns to the sensor.

For example, if the echo takes approximately 5.8 milliseconds to return and the speed of sound is assumed to be 343 metres per second:

Distance = (343 × 0.0058) / 2

Distance ≈ 0.995 metres

This is an illustrative calculation. The speed of sound varies with environmental conditions, especially temperature.

## 4. Types of Ultrasonic Sensors

### 4.1 Ultrasonic Distance Sensors

These sensors measure the distance between the sensor and a reflecting object.

- **Example:** HC-SR04
- **Applications:** Robotics, obstacle detection, and educational experiments.

### 4.2 Industrial Ultrasonic Sensors

Industrial ultrasonic sensors detect objects or measure distances in manufacturing and automation systems.

- **Applications:** Level measurement, object detection, and production-line monitoring.
- **Features:** Some models provide analog, digital, or industrial communication outputs.

### 4.3 Ultrasonic Level Sensors

These sensors estimate the level of a liquid or solid material by measuring the distance to its surface.

- **Applications:** Tanks, storage containers, and industrial process monitoring.

## 5. Important Characteristics

- **Measurement range:** The distance range supported by the sensor.
- **Resolution:** The smallest distance change the sensor can represent.
- **Accuracy:** How close the measured distance is to the actual distance.
- **Beam angle:** The region in which the sensor can detect reflected sound.
- **Response time:** How quickly the sensor produces a new measurement.
- **Operating environment:** Conditions such as temperature, humidity, dust, and airflow that may affect performance.

Refer to the manufacturer's datasheet for model-specific specifications.

## 6. Common Example: HC-SR04

The HC-SR04 is a commonly used ultrasonic distance-measurement module.

It typically has four pins:

- **VCC:** Power supply
- **TRIG:** Trigger input
- **ECHO:** Echo output
- **GND:** Ground

The exact electrical requirements should be checked for the specific module. In particular, verify the echo-output voltage before connecting it to a microcontroller that is not 5 V tolerant.

## 7. Applications

- Robot obstacle detection
- Vehicle parking assistance
- Liquid-level measurement
- Industrial object detection
- Distance measurement experiments
- Automated equipment monitoring

## 8. Advantages and Limitations

**Advantages**

- Measures distance without physical contact.
- Can detect many objects regardless of their visible colour.
- Useful for simple distance-measurement applications.

**Limitations**

- Soft materials may absorb sound and reduce echo strength.
- Angled or irregular surfaces may reflect sound away from the sensor.
- Temperature and environmental conditions can affect measurements.
- Very small objects and objects outside the detection beam may be difficult to detect.
- Ultrasonic sensors are not suitable for every material or measurement environment.

## 9. References

- [Arduino Documentation](https://docs.arduino.cc/)
- [Texas Instruments](https://www.ti.com/) — ultrasonic sensing and technical resources

For exact measurement range, timing, and electrical specifications, consult the datasheet for the specific sensor model.

---

[Back to Sensor Knowledge Base](../README.md)
