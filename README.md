# simple-icp-cli

### Pure rust version of [kiss-icp](https://github.com/PRBonn/kiss-icp)

For library please check [here](https://github.com/powei-lin/simple-icp).

Run on [LOAM-Livox](https://github.com/hku-mars/loam_livox) dataset
* CYT_02
<img src="docs/CYT_02.avif" width="800" alt="Slow down for show case.">

* HKUST_01
<img src="docs/HKUST_01.avif" width="800" alt="Slow down for show case.">

Run the cli tool (only support ros1 bag)
```sh
cargo install simple-icp-cli
cargo install rerun-cli --version 0.22.1
simple_icp {bag_path}
# example
simple_icp CYT_02.bag
```
