---
title: Component Selection Example
---                                                   

**Rotary Encoder**

1. PEC11R-4220F-N0024-ND Rotary Encoder

    ![](<img width="200" height="200" alt="image" src="https://github.com/user-attachments/assets/0c0a8527-c071-43d1-9390-95dcc93203a3" />
)

    * $1.89/each
    * [link to product](https://www.digikey.com/en/products/detail/bourns-inc/PEC11R-4220F-N0024/4699220?gclsrc=aw.ds&gad_source=4&gad_campaignid=20232005509&gclid=CjwKCAjwr8LHBhBKEiwAy47uUmV-P2ILuPxBcfFMkXV66jv7qH3sR4MutpoOQgJ1kdWp-W5v6PoJZRoC0XQQAvD_BwE)

    | Pros                                      | Cons                                                             |
    | ----------------------------------------- | ---------------------------------------------------------------- |
    | Simpler circuit design                    | No integrated push button                                        |
    | Mechanic encoding                         | Limited interaction options                                      |
    | Lower cost                                | Knob removal requires tool                                       |

2. PEC11R-4220K-S0024-ND Rotary Encoder

    ![](<img width="200" height="200" alt="image" src="https://github.com/user-attachments/assets/296f9002-2d84-463f-b8e5-bd7ece7e1abe" />
)

    * $2.20/each
    * [Link to product](https://www.digikey.com/en/products/detail/bourns-inc/PEC11R-4220K-S0024/6164059?gclsrc=aw.ds&gad_source=4&gad_campaignid=20232005509&gclid=CjwKCAjwr8LHBhBKEiwAy47uUoJJXs03gWoiEB9TnnwgNjIXGr7vssQzdQrfOzL1QPFXgUomusDsvxoCFlQQAvD_BwE)

    | Pros                                                              | Cons                |
    | ----------------------------------------------------------------- | ------------------- |
    | Built in push button                                              | More expensive      |
    | Versatile user interface                                          | More complex wiring |
    | Tool free knob installation                                       | Potential knob slippage |

**Choice:** Option 2: PEC11R-4220K-S0024-ND Rotary Encoder

**Rationale:** An integrated push button would increase functionality for our LCD interface. Having the switch built in means that we can
create a cleaner looking panel. Less space required on the PCB board and it has a simpler assembly.

**LCD Display**

1. XC1259TR-ND surface mount crystal

    ![](png)

    * $1/each
    * [link to product](http://www.digikey.com/product-detail/en/ECS-40.3-S-5PX-TR/XC1259TR-ND/827366)

    | Pros                                      | Cons                                                             |
    | ----------------------------------------- | ---------------------------------------------------------------- |
    | Inexpensive                               | Requires external components and support circuitry for interface |
    | Compatible with PSoC                      | Needs special PCB layout.                                        |
    | Meets surface mount constraint of project |

1. CTX936TR-ND surface mount oscillator

    ![](image3.png)

    * $1/each
    * [Link to product](http://www.digikey.com/product-detail/en/636L3I001M84320/CTX936TR-ND/2292940)

    | Pros                                                              | Cons                |
    | ----------------------------------------------------------------- | ------------------- |
    | Outputs a square wave                                             | More expensive      |
    | Stable over operating temperature                                 | Slow shipping speed |
    | Direct interface with PSoC (no external circuitry required) range |

**Choice:** Option 2: CTX936TR-ND surface mount oscillator

**Rationale:** A clock oscillator is easier to work with because it requires no external circuitry in order to interface with the PSoC. This is particularly important because we are not sure of the electrical characteristics of the PCB, which could affect the oscillation of a crystal. While the shipping speed is slow, according to the website if we order this week it will arrive within 3 weeks.
