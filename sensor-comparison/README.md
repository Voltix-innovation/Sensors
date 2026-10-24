# Sensor Comparison Guide

## 1. Introduction

Different sensors measure different physical and environmental quantities. Comparing their working principles, outputs, and applications helps users understand their differences and select an appropriate sensor for a particular purpose.

## 2. Comparison of Common Sensors

| Sensor | Quantity Measured | Typical Output | Common Applications |
|---|---|---|---|
| LM35 | Temperature | Analog voltage | Temperature monitoring |
| DS18B20 | Temperature | Digital | Embedded systems |
| DHT11 | Temperature and humidity | Digital | Basic environmental monitoring |
| DHT22 | Temperature and humidity | Digital | Environmental monitoring |
| HC-SR04 | Distance | Trigger and echo signals | Distance measurement |
| PIR sensor | Motion of warm bodies | Digital | Motion detection |
| LDR | Light intensity | Resistance change | Automatic lighting |
| MQ-2 | Response to certain gases and smoke | Analog; some modules also provide digital output | Gas/smoke experiments |
| BH1750 | Ambient light level | Digital, typically I²C | Light measurement |
| INMP441 | Sound | Digital I²S audio data | Audio acquisition |

**Note:** These are general descriptions. Actual output interfaces and capabilities depend on the exact sensor or module.

## 3. How to Select a Sensor

Before selecting a sensor, consider:

1. **Measured quantity:** What physical parameter needs to be measured?
2. **Measurement range:** What minimum and maximum values are expected?
3. **Accuracy:** How close must the measurement be to the actual value?
4. **Output type:** Is analog, digital, I²C, I²S, or another interface required?
5. **Operating conditions:** Will the sensor be exposed to heat, moisture, dust, or vibration?
6. **Power requirements:** What supply voltage and current does the sensor require?
7. **Cost and availability:** Does the sensor fit the project budget?

## 4. Important Safety Note

Educational modules such as MQ-series gas sensors should not be treated as certified life-safety devices. For safety-critical applications, use equipment approved for the intended purpose.

## 5. References

- [Arduino Documentation](https://docs.arduino.cc/)
- [Espressif Documentation](https://docs.espressif.com/)
- [Texas Instruments](https://www.ti.com/)
- [Analog Devices](https://www.analog.com/)

---

[Back to Sensor Knowledge Base](../README.md)
