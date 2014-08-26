wercker-box-rust
================

Wercker box using the latest version of Rust.
[![wercker status](https://app.wercker.com/status/34a7dcae96d0a188cfedc819150a22ea/m "wercker status")](https://app.wercker.com/project/bykey/34a7dcae96d0a188cfedc819150a22ea)

### Usage

Create `wercker.yml` in your repository with following code:
```yaml
box: asaskevich/rust-latest
```
Box contain last nightly build of Rust. If you want to use special [testing step](https://github.com/asaskevich/step-rust-test), then add following code:
```yaml
build:
  steps:
    - asaskevich/rust-test
```
Enjoy!