---
layout: default
title: Zendesk Garden Jekyll Theme
auto_title: false
---

# Smart Home - Smart Devices Amplify Documentation

This project is broken down in the following solutions:
- Mobile Application Project
- IoT Smart Device Project
- The AWS Amplify Cloud Backend
- IoT Smart Device Provisioning Project


## Usage

The purpose of this project is to provide an overall end-to-end implementation for others to utilize and quick get through all the initial setups.


### Project Design

The project has the following design choices:
- Mobile Application for iOS and Android using flutter solution
- IoT Devices using Espressif ESP32 variant of SoC chip/modules
- IoT Devices using Espressif ESP-IDF framework
  - This is mostly build in C Language in the ESP-IDF framework
- IoT Library framework
  - FreeRTOS
    - The Common Logging Library
  - coreMQTT
  - coreMQTT-Agent
  - coreJSON
  - backoffAlgorithm
- IoT Espressif Library framework
  - joltwallet littlefs
  - Network Provisioning (formally known as WiFi Provisioning)
  - ESP Secure Certificate Manager
  - Button library
  - Led Strip library (to control all WS2812 LEDs types)
  - ESP IDF version release 6.0
- AWS Cloud Services
  - Cognito Authentication Management
  - IAM Identify Management
  - CloudWatch Logging
  - IoT Core
- AWS Amplify for the backend framework
  - AppSync API calls
  - AppSync Custom Resolvers Lambda Functions
  - Amplify controlled Dynamodb tables
- Provisioning Tool
  - Python project
  - OpenSSL for Certificate creation
  - Boto3 for AWS Services communication


## Contributing

Bug reports and pull requests are welcome [on GitHub](https://github.com/zendesk/jekyll-theme-zendesk-garden).
This project is intended to be a safe, welcoming space for collaboration, and contributors are
expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

## License

Copyright 2021 Zendesk

Licensed under the [Apache License, Version 2.0](LICENSE.txt)
