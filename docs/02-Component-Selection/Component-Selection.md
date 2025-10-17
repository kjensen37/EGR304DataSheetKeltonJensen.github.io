---
title: Component Selection Example
---                                                   

**Rotary Encoder**

1. PEC11R-4220F-N0024-ND Rotary Encoder

    <img width="200" height="200" alt="image" src="https://github.com/user-attachments/assets/0c0a8527-c071-43d1-9390-95dcc93203a3" />

    * $1.89/each
    * [link to product](https://www.digikey.com/en/products/detail/bourns-inc/PEC11R-4220F-N0024/4699220?gclsrc=aw.ds&gad_source=4&gad_campaignid=20232005509&gclid=CjwKCAjwr8LHBhBKEiwAy47uUmV-P2ILuPxBcfFMkXV66jv7qH3sR4MutpoOQgJ1kdWp-W5v6PoJZRoC0XQQAvD_BwE)

    | Pros                                      | Cons                                                             |
    | ----------------------------------------- | ---------------------------------------------------------------- |
    | Simpler circuit design                    | No integrated push button                                        |
    | Mechanic encoding                         | Limited interaction options                                      |
    | Lower cost                                | Knob removal requires tool                                       |

2. PEC11R-4220K-S0024-ND Rotary Encoder

    <img width="200" height="200" alt="image" src="https://github.com/user-attachments/assets/296f9002-2d84-463f-b8e5-bd7ece7e1abe" />

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

1. 1548-NHD-0216K1Z-NSW-BBW-L-ND LCD display

    <img width="200" height="200" alt="image" src="https://github.com/user-attachments/assets/3143f729-8799-4647-9ae0-e45638180b8c" />


    * $7.92/each
    * [link to product](https://www.digikey.com/en/products/detail/newhaven-display-intl/NHD-0216K1Z-NSW-BBW-L/1701179)

    | Pros                                      | Cons                                                             |
    | ----------------------------------------- | ---------------------------------------------------------------- |
    | Standard 5V operation                     | Requires backlight for visibility                                |
    | High contrast blue backlight aesthetic    | Higher power consumption                                         |
    | Manual contrast control via potentiometer | Limited viewing angles                                           |

2. NHD-0216HZ-FSW-FBW-33V3C-ND LCD display

    <img width="200" height="200" alt="image" src="https://github.com/user-attachments/assets/af4f548f-ad76-4bb9-ae8b-6c61d6eb827a" />


    * $9.37/each
    * [Link to product](https://www.digikey.com/en/products/detail/newhaven-display-intl/NHD-0216HZ-FSW-FBW-33V3C/2773591)

    | Pros                                                              | Cons                |
    | ----------------------------------------------------------------- | ------------------- |
    | Modern 3.3V logic compatibility                                   | Lower contrast appearance                    |
    | Transflective display technology                                  | No manual contrast adjustment                |
    | Superior viewing angles                                           | Lower backlight current but separate voltage |

**Choice:** Option 1: 1548-NHD-0216K1Z-NSW-BBW-L-ND LCD display

**Rationale:** High contrast adjustable blue blacklight aesthetic is easier for users to see their information being displayed in all lighting.
Less complex power supply setup, no need for extra regulator. Can run write-only mode to avoid bi-directional shifitng.
