> Based on the template [cortex-m-quickstart](https://github.com/rust-embedded/cortex-m-quickstart) and [The Embedded Rust Book](https://docs.rust-embedded.org/book/)
## Requirements
* MCU [STM32F407VG](https://www.st.com/en/evaluation-tools/stm32f4discovery.html)
* https://docs.rust-embedded.org/book/intro/install.html
* Linux: Use this [70-st-link.rules](70-st-link.rules)
## Build and upload Hello app to MCU
* Connect MCU to your machine over mini USB
### 1st way
* Open a 1st terminal and run `openocd`
* Open a 2nd terminal and run `cargo run --example hello`
* Switch to the 1st terminal, you should see a text "**Hello, world**"

### 2nd way
* Install [VSCode](https://code.visualstudio.com/) and [Cortex-Debug](https://marketplace.visualstudio.com/items?itemName=marus25.cortex-debug)
* VSCode: `Run -> Run Without Debugging`
* You should see a text "**Hello, world**" in terminal
* Stop debugger
