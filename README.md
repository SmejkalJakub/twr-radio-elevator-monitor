<a href="https://www.hardwario.com/"><img src="https://www.hardwario.com/ci/assets/hw-logo.svg" width="200" alt="HARDWARIO Logo" align="right"></a>

# Elevator monitor

[![build](https://github.com/hardwario/twr-radio-elevator-monitor/actions/workflows/main.yml/badge.svg)](https://github.com/hardwario/twr-radio-elevator-monitor/actions/workflows/main.yml)
[![Release](https://img.shields.io/github/release/bigclownprojects/bcf-radio-elevator-monitor.svg)](https://github.com/bigclownprojects/bcf-radio-elevator-monitor/releases)
[![License](https://img.shields.io/github/license/bigclownprojects/bcf-radio-elevator-monitor.svg)](https://github.com/bigclownprojects/bcf-radio-elevator-monitor/blob/master/LICENSE)
[![Twitter](https://img.shields.io/twitter/follow/hardwario_en.svg?style=social&label=Follow)](https://twitter.com/hardwario_en)

This repository contains firmware Elevator Monitor for [Core Module](https://shop.hardwario.com/core-module).

You can use it in 2 modes, that is changed by the press of the button on the Core Module. If the LED on Core Module is ON it means that it is meassuring and sending you
the data about the height of the current floor. After you have all the information about each floor, just press the Button again and the LED will be OFF, after that you will get the floor number of the elevator.

Please keep in mind that this is mostly for demonstration of how the Accelerometer and Barometer works so it might be a little bit off some times.

If you want to get more information about Core Module, firmware and how to work with it, please follow this link:

**https://developers.hardwario.com/firmware/basic-overview/**

User's application code (business logic) goes into `src/application.c`.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT/) - see the [LICENSE](LICENSE) file for details.

---

Made with &#x2764;&nbsp; by [**HARDWARIO a.s.**](https://www.hardwario.com/) in the heart of Europe.
