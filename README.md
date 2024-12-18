Project page of the paper: "Event-based Photometric Bundle Adjustment"

# Coming soon... EPBA: Event-based Photometric Bundle Adjustment
Official repository for [**Event-based Photometric Bundle Adjustment**](), by [Shuang Guo](https://shuang1997.github.io) and [Guillermo Gallego](https://sites.google.com/view/guillermogallego).
<h2 align="left">

[PDF]() | [Video](https://youtu.be/v4DhU-N6o6s) | [Dataset](https://github.com/tub-rip/ECRot) 
</h2>

[![Event-based Photometric Bundle Adjustment](docs/img/video_cover.jpg)](https://youtu.be/v4DhU-N6o6s)

## Citation

If you use this work in your research, please cite it as follows:

```bibtex
@Article{Guo24epba,
  author        = {Shuang Guo and Guillermo Gallego},
  title         = {Event-based Photometric Bundle Adjustment},
  journal       = {(under review)},
  year          = 2024
}
```

-------
## Setup

### High-level Input-Output

**Input**:
- Events.
- Camera calibration.
- Initial trajectory from other front-end methods.
- (Optional) Initial panoramic brightness maps.

**Output**:
- Refined rotations of the event camera.
- Refined intensity panorama.

## Usage
- [Installation](docs/installation.md)
- [Execution](docs/execution.md)
- [Parameter Guide](docs/parameters.md)

## [Event Camera Rotation Dataset (ECRot)](https://github.com/tub-rip/ECRot)

We test EPBA on the newly-released ECRot dataset, see and download it at [here](https://github.com/tub-rip/ECRot). The instructions of running EPBA on the ECRot dataset can be found [here](docs/execution.md).

## Acknowledgements

This code leverages the following repository for computing the derivative of Lie Group B-splines:
- [Basalt Headers](https://gitlab.com/VladyslavUsenko/basalt-headers)


## Additional Resources

* [CMax-SLAM](https://github.com/tub-rip/cmax_slam)
