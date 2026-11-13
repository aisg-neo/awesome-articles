---
title: "Scaling out Tinder Android Payment Flow using State Machine"
link: https://medium.com/tinder/scaling-out-tinder-android-payment-flow-using-state-machine-e14ef0591b6
topics:
  - Mobile
  - Payments
year: 2020
---

Tinder rewrote its Android payment flow after large legacy classes made maintenance, debugging, and new features difficult. A state machine models loading, validation, charging, and receipt verification, including explicit failure transitions, while a coordinator delegates business logic to separate commands. The modular design makes payment behavior observable and supports more structured testing and future payment methods.
