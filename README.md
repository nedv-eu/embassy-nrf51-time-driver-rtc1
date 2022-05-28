# Embassy Time Driver Using RTC1 on NRF51 devices
Embassy RTC1 time driver based on driver from embassy-nrf crate adopted to work on NRF51 devices. It is basically a fork of [fdb6e66b4b7aa5a6b72ec2b926ea9e5de728c657](https://github.com/embassy-rs/embassy/commits/master/embassy-nrf/src/time_driver.rs) where atomic operations not available on Cortex-M0 were replaced by mutex guards.
