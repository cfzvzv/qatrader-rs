# qatrader-rs

rust version for qatrader, for a high performance with limited resources




```toml
mongodb = "0.3.11" # mongodb
amiquip = "0.3"
futures = "^0.1"
log = "^0.4"
chrono = { version = "0.4", features = ["serde"] } # datetime
env_logger = "^0.7" 
serde_json = "1.0"
serde_derive = "1.0"
serde = { version = "1.0", features = ["derive"] } # 序列化
rayon = "1.1" # 多线程
ndarray = "0.13.0" # ndarray
wsq = '0.9.1'
crossbeam = "0.7"
crossbeam-channel = "0.4"
crossbeam-utils = "0.7"
```


如果需要编译:


```
rustup install nightly
cargo +nightly build

```