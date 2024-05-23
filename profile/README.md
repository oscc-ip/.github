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

* SPC: SPEC complete
* RTF: RTL frozen
* SMT: SMOKE test
* UVV: UVM verif
* FUC: FUNCTION coverage
* COC: CODE coverage
* SOI: SoC integ
* FPE: FPGA emu
* TPT: TAPEOUT test

| IP       | MILESTONE |
| :---:    | :---     |
| [archinfo](https://github.com/oscc-ip/archinfo) | <img src="https://img.shields.io/badge/SPC-done-green?style=flat-square"> <img src="https://img.shields.io/badge/RTF-done-green?style=flat-square"> <img src="https://img.shields.io/badge/SMT-done-green?style=flat-square"> <img src="https://img.shields.io/badge/UVV-no%20start-wheat?style=flat-square"> <img src="https://img.shields.io/badge/FUC-0-green?style=flat-square"> <img src="https://img.shields.io/badge/COC-0-green?style=flat-square"> <img src="https://img.shields.io/badge/SOI-done-green?style=flat-square"> <img src="https://img.shields.io/badge/FPE-no%20start-wheat?style=flat-square"> <img src="https://img.shields.io/badge/TPT-no%20start-wheat?style=flat-square"> |
| [rng](https://github.com/oscc-ip/rng) | <img src="https://img.shields.io/badge/SPC-done-green?style=flat-square"> <img src="https://img.shields.io/badge/RTF-done-green?style=flat-square"> <img src="https://img.shields.io/badge/SMT-done-green?style=flat-square"> <img src="https://img.shields.io/badge/UVV-no%20start-wheat?style=flat-square"> <img src="https://img.shields.io/badge/FUC-0-green?style=flat-square"> <img src="https://img.shields.io/badge/COC-0-green?style=flat-square"> <img src="https://img.shields.io/badge/SOI-done-green?style=flat-square"> <img src="https://img.shields.io/badge/FPE-no%20start-wheat?style=flat-square"> <img src="https://img.shields.io/badge/TPT-no%20start-wheat?style=flat-square"> |
| [sram](https://github.com/oscc-ip/sram) | <img src="https://img.shields.io/badge/SPC-done-green?style=flat-square"> <img src="https://img.shields.io/badge/RTF-done-green?style=flat-square"> <img src="https://img.shields.io/badge/SMT-done-green?style=flat-square"> <img src="https://img.shields.io/badge/UVV-no%20start-wheat?style=flat-square"> <img src="https://img.shields.io/badge/FUC-0-green?style=flat-square"> <img src="https://img.shields.io/badge/COC-0-green?style=flat-square"> <img src="https://img.shields.io/badge/SOI-done-green?style=flat-square"> <img src="https://img.shields.io/badge/FPE-no%20start-wheat?style=flat-square"> <img src="https://img.shields.io/badge/TPT-no%20start-wheat?style=flat-square"> |
| [ps2](https://github.com/oscc-ip/ps2) | <img src="https://img.shields.io/badge/SPC-done-green?style=flat-square"> <img src="https://img.shields.io/badge/RTF-done-green?style=flat-square"> <img src="https://img.shields.io/badge/SMT-done-green?style=flat-square"> <img src="https://img.shields.io/badge/UVV-no%20start-wheat?style=flat-square"> <img src="https://img.shields.io/badge/FUC-0-green?style=flat-square"> <img src="https://img.shields.io/badge/COC-0-green?style=flat-square"> <img src="https://img.shields.io/badge/SOI-done-green?style=flat-square"> <img src="https://img.shields.io/badge/FPE-no%20start-wheat?style=flat-square"> <img src="https://img.shields.io/badge/TPT-no%20start-wheat?style=flat-square"> |
| [gpio](https://github.com/oscc-ip/gpio) | <img src="https://img.shields.io/badge/SPC-done-green?style=flat-square"> <img src="https://img.shields.io/badge/RTF-done-green?style=flat-square"> <img src="https://img.shields.io/badge/SMT-done-green?style=flat-square"> <img src="https://img.shields.io/badge/UVV-no%20start-wheat?style=flat-square"> <img src="https://img.shields.io/badge/FUC-0-green?style=flat-square"> <img src="https://img.shields.io/badge/COC-0-green?style=flat-square"> <img src="https://img.shields.io/badge/SOI-done-green?style=flat-square"> <img src="https://img.shields.io/badge/FPE-no%20start-wheat?style=flat-square"> <img src="https://img.shields.io/badge/TPT-no%20start-wheat?style=flat-square"> |
| [clint](https://github.com/oscc-ip/clint) | <img src="https://img.shields.io/badge/SPC-done-green?style=flat-square"> <img src="https://img.shields.io/badge/RTF-done-green?style=flat-square"> <img src="https://img.shields.io/badge/SMT-done-green?style=flat-square"> <img src="https://img.shields.io/badge/UVV-no%20start-wheat?style=flat-square"> <img src="https://img.shields.io/badge/FUC-0-green?style=flat-square"> <img src="https://img.shields.io/badge/COC-0-green?style=flat-square"> <img src="https://img.shields.io/badge/SOI-done-green?style=flat-square"> <img src="https://img.shields.io/badge/FPE-no%20start-wheat?style=flat-square"> <img src="https://img.shields.io/badge/TPT-no%20start-wheat?style=flat-square"> |
| [pwm](https://github.com/oscc-ip/pwm) | <img src="https://img.shields.io/badge/SPC-done-green?style=flat-square"> <img src="https://img.shields.io/badge/RTF-done-green?style=flat-square"> <img src="https://img.shields.io/badge/SMT-done-green?style=flat-square"> <img src="https://img.shields.io/badge/UVV-no%20start-wheat?style=flat-square"> <img src="https://img.shields.io/badge/FUC-0-green?style=flat-square"> <img src="https://img.shields.io/badge/COC-0-green?style=flat-square"> <img src="https://img.shields.io/badge/SOI-done-green?style=flat-square"> <img src="https://img.shields.io/badge/FPE-no%20start-wheat?style=flat-square"> <img src="https://img.shields.io/badge/TPT-no%20start-wheat?style=flat-square"> |
| [timer](https://github.com/oscc-ip/timer) | <img src="https://img.shields.io/badge/SPC-done-green?style=flat-square"> <img src="https://img.shields.io/badge/RTF-done-green?style=flat-square"> <img src="https://img.shields.io/badge/SMT-done-green?style=flat-square"> <img src="https://img.shields.io/badge/UVV-no%20start-wheat?style=flat-square"> <img src="https://img.shields.io/badge/FUC-0-green?style=flat-square"> <img src="https://img.shields.io/badge/COC-0-green?style=flat-square"> <img src="https://img.shields.io/badge/SOI-done-green?style=flat-square"> <img src="https://img.shields.io/badge/FPE-no%20start-wheat?style=flat-square"> <img src="https://img.shields.io/badge/TPT-no%20start-wheat?style=flat-square"> |
| [wdg](https://github.com/oscc-ip/wdg) | <img src="https://img.shields.io/badge/SPC-done-green?style=flat-square"> <img src="https://img.shields.io/badge/RTF-done-green?style=flat-square"> <img src="https://img.shields.io/badge/SMT-done-green?style=flat-square"> <img src="https://img.shields.io/badge/UVV-no%20start-wheat?style=flat-square"> <img src="https://img.shields.io/badge/FUC-0-green?style=flat-square"> <img src="https://img.shields.io/badge/COC-0-green?style=flat-square"> <img src="https://img.shields.io/badge/SOI-done-green?style=flat-square"> <img src="https://img.shields.io/badge/FPE-no%20start-wheat?style=flat-square"> <img src="https://img.shields.io/badge/TPT-no%20start-wheat?style=flat-square"> |
| [rtc](https://github.com/oscc-ip/rtc) | <img src="https://img.shields.io/badge/SPC-done-green?style=flat-square"> <img src="https://img.shields.io/badge/RTF-done-green?style=flat-square"> <img src="https://img.shields.io/badge/SMT-done-green?style=flat-square"> <img src="https://img.shields.io/badge/UVV-no%20start-wheat?style=flat-square"> <img src="https://img.shields.io/badge/FUC-0-green?style=flat-square"> <img src="https://img.shields.io/badge/COC-0-green?style=flat-square"> <img src="https://img.shields.io/badge/SOI-done-green?style=flat-square"> <img src="https://img.shields.io/badge/FPE-no%20start-wheat?style=flat-square"> <img src="https://img.shields.io/badge/TPT-no%20start-wheat?style=flat-square"> |
| [uart](https://github.com/oscc-ip/uart) | <img src="https://img.shields.io/badge/SPC-done-green?style=flat-square"> <img src="https://img.shields.io/badge/RTF-done-green?style=flat-square"> <img src="https://img.shields.io/badge/SMT-done-green?style=flat-square"> <img src="https://img.shields.io/badge/UVV-no%20start-wheat?style=flat-square"> <img src="https://img.shields.io/badge/FUC-0-green?style=flat-square"> <img src="https://img.shields.io/badge/COC-0-green?style=flat-square"> <img src="https://img.shields.io/badge/SOI-done-green?style=flat-square"> <img src="https://img.shields.io/badge/FPE-no%20start-wheat?style=flat-square"> <img src="https://img.shields.io/badge/TPT-no%20start-wheat?style=flat-square">
| [i2c](https://github.com/oscc-ip/i2c) | <img src="https://img.shields.io/badge/SPC-done-green?style=flat-square"> <img src="https://img.shields.io/badge/RTF-done-green?style=flat-square"> <img src="https://img.shields.io/badge/SMT-done-green?style=flat-square"> <img src="https://img.shields.io/badge/UVV-no%20start-wheat?style=flat-square"> <img src="https://img.shields.io/badge/FUC-0-green?style=flat-square"> <img src="https://img.shields.io/badge/COC-0-green?style=flat-square"> <img src="https://img.shields.io/badge/SOI-done-green?style=flat-square"> <img src="https://img.shields.io/badge/FPE-no%20start-wheat?style=flat-square"> <img src="https://img.shields.io/badge/TPT-no%20start-wheat?style=flat-square"> |
| [spi](https://github.com/oscc-ip/spi) | <img src="https://img.shields.io/badge/SPC-done-green?style=flat-square"> <img src="https://img.shields.io/badge/RTF-done-green?style=flat-square"> <img src="https://img.shields.io/badge/SMT-done-green?style=flat-square"> <img src="https://img.shields.io/badge/UVV-no%20start-wheat?style=flat-square"> <img src="https://img.shields.io/badge/FUC-0-green?style=flat-square"> <img src="https://img.shields.io/badge/COC-0-green?style=flat-square"> <img src="https://img.shields.io/badge/SOI-done-green?style=flat-square"> <img src="https://img.shields.io/badge/FPE-no%20start-wheat?style=flat-square"> <img src="https://img.shields.io/badge/TPT-no%20start-wheat?style=flat-square"> |
| [vga](https://github.com/oscc-ip/vga) | <img src="https://img.shields.io/badge/SPC-done-green?style=flat-square"> <img src="https://img.shields.io/badge/RTF-done-green?style=flat-square"> <img src="https://img.shields.io/badge/SMT-done-green?style=flat-square"> <img src="https://img.shields.io/badge/UVV-no%20start-wheat?style=flat-square"> <img src="https://img.shields.io/badge/FUC-0-green?style=flat-square"> <img src="https://img.shields.io/badge/COC-0-green?style=flat-square"> <img src="https://img.shields.io/badge/SOI-done-green?style=flat-square"> <img src="https://img.shields.io/badge/FPE-no%20start-wheat?style=flat-square"> <img src="https://img.shields.io/badge/TPT-no%20start-wheat?style=flat-square"> |
| [plic](https://github.com/oscc-ip/plic) | <img src="https://img.shields.io/badge/SPC-done-green?style=flat-square"> <img src="https://img.shields.io/badge/RTF-done-green?style=flat-square"> <img src="https://img.shields.io/badge/SMT-done-green?style=flat-square"> <img src="https://img.shields.io/badge/UVV-no%20start-wheat?style=flat-square"> <img src="https://img.shields.io/badge/FUC-0-green?style=flat-square"> <img src="https://img.shields.io/badge/COC-0-green?style=flat-square"> <img src="https://img.shields.io/badge/SOI-done-green?style=flat-square"> <img src="https://img.shields.io/badge/FPE-no%20start-wheat?style=flat-square"> <img src="https://img.shields.io/badge/TPT-no%20start-wheat?style=flat-square"> |
| [i2s](https://github.com/oscc-ip/i2s) | <img src="https://img.shields.io/badge/SPC-done-green?style=flat-square"> <img src="https://img.shields.io/badge/RTF-no%20start-wheat?style=flat-square"> <img src="https://img.shields.io/badge/SMT-no%20start-wheat?style=flat-square"> <img src="https://img.shields.io/badge/UVV-no%20start-wheat?style=flat-square"> <img src="https://img.shields.io/badge/FUC-0-green?style=flat-square"> <img src="https://img.shields.io/badge/COC-0-green?style=flat-square"> <img src="https://img.shields.io/badge/SOI-no%20start-wheat?style=flat-square"> <img src="https://img.shields.io/badge/FPE-no%20start-wheat?style=flat-square"> <img src="https://img.shields.io/badge/TPT-no%20start-wheat?style=flat-square"> |
| [sdram](https://github.com/oscc-ip/sdram) | <img src="https://img.shields.io/badge/SPC-done-green?style=flat-square"> <img src="https://img.shields.io/badge/RTF-no%20start-wheat?style=flat-square"> <img src="https://img.shields.io/badge/SMT-no%20start-wheat?style=flat-square"> <img src="https://img.shields.io/badge/UVV-no%20start-wheat?style=flat-square"> <img src="https://img.shields.io/badge/FUC-0-green?style=flat-square"> <img src="https://img.shields.io/badge/COC-0-green?style=flat-square"> <img src="https://img.shields.io/badge/SOI-no%20start-wheat?style=flat-square"> <img src="https://img.shields.io/badge/FPE-no%20start-wheat?style=flat-square"> <img src="https://img.shields.io/badge/TPT-no%20start-wheat?style=flat-square"> |

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
