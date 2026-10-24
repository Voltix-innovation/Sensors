# Gas and Smoke Sensors

## 1. Introduction

Gas and smoke sensors detect specific gases, smoke particles, or changes in the surrounding air. They are used in environmental monitoring, industrial processes, air-quality measurement, and fire detection systems.

Different sensors are designed to detect different substances. A gas sensor should not be assumed to detect every type of gas.

## 2. Working Principle

Gas and smoke sensors use different physical and chemical principles.

Some gas sensors detect changes in electrical resistance when gas interacts with a sensing material. Others use electrochemical reactions, infrared absorption, or changes in optical signals.

Smoke detectors may use optical methods to detect particles in the air or other technologies designed for fire detection.

The sensor converts the detected change into an electrical signal that can be processed by a monitoring or control system.

## 3. Types of Gas and Smoke Sensors

### 3.1 Metal Oxide Semiconductor (MOS) Sensors

MOS sensors detect certain gases by measuring changes in the electrical resistance of a sensing material.

- **Examples:** MQ-series sensor modules.
- **Applications:** Educational experiments and basic gas-response monitoring.
- **Limitations:** Readings can be affected by temperature, humidity, sensor ageing, and other gases.

### 3.2 Electrochemical Gas Sensors

These sensors detect gases through chemical reactions at electrodes, producing an electrical signal related to the gas concentration.

- **Applications:** Industrial monitoring and portable gas-detection equipment.
- **Advantages:** Many designs provide good sensitivity to a target gas.
- **Limitations:** Each sensor is designed for particular gases and has a finite operating life.

### 3.3 Catalytic Gas Sensors

Catalytic sensors detect certain combustible gases through heat generated during a catalytic reaction.

- **Applications:** Detection of combustible gases in suitable industrial environments.
- **Limitations:** Performance depends on the sensor design and operating conditions.

### 3.4 Infrared Gas Sensors

Infrared gas sensors detect gases by measuring the absorption of selected infrared wavelengths.

- **Applications:** Monitoring gases such as carbon dioxide in suitable measurement systems.
- **Advantages:** Some designs offer good selectivity and long-term stability.
- **Limitations:** Performance depends on the target gas, optical design, and calibration.

### 3.5 Smoke Sensors and Detectors

Smoke detectors identify smoke using technologies such as optical light scattering or ionization.

- **Applications:** Fire-warning systems and building safety.
- **Important:** Smoke detection and gas concentration measurement are different functions. Not every gas sensor can reliably detect smoke.

## 4. Common Example: MQ-2 Sensor

The MQ-2 is a metal oxide semiconductor gas-sensing module commonly used in educational experiments. It responds to several combustible gases and smoke-related conditions.

Depending on the module, it may provide:

- **Analog output:** A varying signal related to the sensor response.
- **Digital output:** A threshold-based signal from an onboard comparator, if provided.

The MQ-2 requires appropriate warm-up and operating conditions. Its output is not automatically a calibrated gas concentration in parts per million (ppm).

It should not be used as a substitute for a certified gas detector or fire-alarm device.

## 5. Important Characteristics

- **Target gas:** The gas or gases the sensor is designed to detect.
- **Sensitivity:** The sensor's response to changes in gas concentration.
- **Measurement range:** The concentration range supported by the device.
- **Response and recovery time:** How quickly the sensor responds to gas exposure and returns toward its baseline.
- **Selectivity:** How well the sensor distinguishes its target gas from other substances.
- **Operating conditions:** Temperature, humidity, airflow, and other environmental factors.
- **Calibration requirements:** Whether calibration is required to obtain reliable measurements.

Refer to the manufacturer's datasheet for model-specific specifications.

## 6. Applications

- Industrial gas monitoring
- Air-quality monitoring
- Environmental measurement
- Educational electronics experiments
- Process monitoring
- Fire and smoke detection using appropriate detectors
- Safety systems using certified, application-appropriate equipment

## 7. Advantages and Limitations

**Advantages**

- Different technologies are available for different gases and applications.
- Sensors can support automated monitoring and warning systems.
- Many modules can interface with electronic control systems.

**Limitations**

- Cross-sensitivity can cause responses to gases other than the target gas.
- Some sensors need warm-up, calibration, or periodic replacement.
- Environmental conditions can affect readings.
- An uncalibrated sensor may not provide an accurate gas concentration.
- Low-cost educational modules are not necessarily suitable for safety-critical applications.

## 8. Safety Note

Never rely on an unverified educational sensor module to protect people from fire, toxic gases, or combustible-gas leaks. Use properly certified detectors appropriate for the hazard, and follow the manufacturer's installation and maintenance instructions.

## 9. References

- [Figaro Engineering](https://www.figaro.co.jp/en/) — gas sensor documentation
- [Winsen Electronics](https://www.winsen-sensor.com/) — gas sensor product information
- [National Fire Protection Association](https://www.nfpa.org/) — fire and life-safety resources

Always consult the official datasheet for the exact sensor model.

---

[Back to Sensor Knowledge Base](../README.md)
