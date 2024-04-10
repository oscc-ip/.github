<p align="center">
    <h2 align="center">OSCC IP: A series of Verified HDL IP with Accurate-cycle and Event-driven Model</h2>
</p>
<p align="center">
    <a href="https://github.com/oscc-ip/template/blob/main/LICENSE">
      <img src="https://img.shields.io/badge/license-MulanPSL2-brightgreen?style=flat-square">
    </a>
    <a href="https://github.com/cocotb/cocotb">
      <img src="https://img.shields.io/badge/toolchain-iverilog%20vcs%20cocotb-red?style=flat-square">
    </a>
    <a href="https://github.com/oscc-ip/template/blob/main/style.md">
      <img src="https://img.shields.io/badge/code%20style-verible-brightgreen?style=flat-square">
    </a>
    <a href="https://github.com/oscc-ip/template/blob/main/style.md">
      <img src="https://img.shields.io/badge/static%20checker-verible-red?style=flat-square">
    </a>
    <a href="https://github.com/oscc-ip/template/blob/main/CONTRIBUTING.md">
      <img src="https://img.shields.io/badge/contribution-welcome-brightgreen?style=flat-square">
    </a>
</p>


## Hi, OSCC IP Project 👋

OSCC IP Project contains a bundle of IPs which aim to improve development experience of processor and SoC design. Now it mainly focus on frontend and verification field. We hope it can be integrated by other components to build a common workflow for agile hardware development from frontend to backend one day.

## Motivation

<!-- | Type | List |
| :---: | :---: |
| System     | uart, spi-flash, amba bus, dma, trace, clint, plic, jtag, rcu, pmu, core, archinfo |
| Peripheral | timer, rtc, wdg, pwm, gpio, ps2, spi, qspi, octspi, i2c, i2s, sdio |
| Memory     | sram, sdram, psram, nand-flash, ddr1, ddr2, ddr3, chiplink |
| Graphics   | vga, hdmi, lcd, mipi-dsi, video-engine, gpu |
| Communication | usb, ethernet, pcie |
| Application | crc, aes, sha, rsa, rng, foc, cnn, isp | -->

IPs list and development state:
| IP       | MILESTONE |
| :---:    | :---:     |
| [archinfo](https://github.com/oscc-ip/archinfo) | <img src="https://img.shields.io/badge/SPEC%20complete-done-green?style=flat-square"> <img src="https://img.shields.io/badge/RTL%20frozen-done-green?style=flat-square"> <img src="https://img.shields.io/badge/SMOKE%20test-done-green?style=flat-square"> <img src="https://img.shields.io/badge/UVM%20verif-no%20start-wheat?style=flat-square"> <img src="https://img.shields.io/badge/FUNCTIONAL%20coverage-0-green?style=flat-square"> <img src="https://img.shields.io/badge/CODE%20coverage-0-green?style=flat-square"> <img src="https://img.shields.io/badge/SoC%20integ-no%20start-wheat?style=flat-square"> <img src="https://img.shields.io/badge/FPGA%20emu-no%20start-wheat?style=flat-square"> <img src="https://img.shields.io/badge/TAPEOUT%20test-no%20start-wheat?style=flat-square"> |
| [rng](https://github.com/oscc-ip/rng) | <img src="https://img.shields.io/badge/SPEC%20complete-done-green?style=flat-square"> <img src="https://img.shields.io/badge/RTL%20frozen-done-green?style=flat-square"> <img src="https://img.shields.io/badge/SMOKE%20test-done-green?style=flat-square"> <img src="https://img.shields.io/badge/UVM%20verif-no%20start-wheat?style=flat-square"> <img src="https://img.shields.io/badge/FUNCTIONAL%20coverage-0-green?style=flat-square"> <img src="https://img.shields.io/badge/CODE%20coverage-0-green?style=flat-square"> <img src="https://img.shields.io/badge/SoC%20integ-no%20start-wheat?style=flat-square"> <img src="https://img.shields.io/badge/FPGA%20emu-no%20start-wheat?style=flat-square"> <img src="https://img.shields.io/badge/TAPEOUT%20test-no%20start-wheat?style=flat-square"> |

<details>
  <summary>More Info</summary>

## Template
Refer to the [template repo](https://github.com/oscc-ip/template/blob/main). If you want to create a new ip repo, You need to:

* Use this repository template to create a new repo
* Update the content `[IP NAME]` in `header` file and remove the `header` file.

## Style
refer to the [style.md](https://github.com/oscc-ip/template/blob/main/style.md).

## Contribution
If you want to contribute to this project, be sure to review the [guidelines](https://github.com/oscc-ip/template/blob/main/CONTRIBUTING.md). This is an open project and contributions and collaborations are always welcome!! This project adheres to OSCC IP's [code_of_conduct](https://github.com/oscc-ip/template/blob/main/CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code.

we use GitHub issues for tracking requests and bugs, so please direct specific questions to [issues panel](https://github.com/oscc-ip/.github/issues).

The OSCC IP project strives to abide by generally accepted best practices in open-source software development, you can issue bugs, pull requests, new features and modification suggestions freely. Your feedbacks could help us ensure a bright future for this project. We value and treasure every issue or contribution, big or small. 😄

## License
All of the IPs codes are redistributed or released under the OSI Approved LICENSE [MulanPSL2](https://opensource.org/license/mulanpsl-2-0/).

## Acknowledgement

## Reference
    
</details>
