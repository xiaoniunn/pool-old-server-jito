## Build

```sh
cargo build --release
```
## 挖矿

```sh
cargo run --package ore-cli --bin ore \
-- mine \ 
--max-adaptive-tip 50000 \ #（可选）使用自适应tip并指定最大tip，不加该参数时，使用priority_fee作为固定tip
--priority_fee 5000 \ #（可选）不使用自适应tip时作为固定tip，使用自适应tip时，会在自适应tip的基础上加上该值，但不会超过指定的最大tip
--keypair path_to_id.json \ 
--rpc https://your_rpc_url
```

## 提现

```sh
cargo run --package ore-cli --bin ore \
-- claim \ 
--max-adaptive-tip 50000 \ #（可选）使用自适应tip并指定最大tip，不加该参数时，使用priority_fee作为固定tip
--priority_fee 5000 \ #（可选）不使用自适应tip时作为固定tip，使用自适应tip时，会在自适应tip的基础上加上该值，但不会超过指定的最大tip
--keypair path_to_id.json \ 
--rpc https://your_rpc_url
```