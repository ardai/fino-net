# FINO-net

**FINO-Net: A Deep Multimodal Sensor Fusion Framework for Manipulation Failure Detection** <br>
*IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)* <br>
*Arda Inceoglu, Eren Erdal Aksoy, Abdullah Cihan Ak, Sanem Sariel* <br>
[PDF link](https://ieeexplore.ieee.org/document/9636455)

**Multimodal Detection and Classification of Robot Manipulation Failures** <br>
*IEEE Robotics and Automation Letters, Volume 9, Issue 2, pp. 1396 - 1403, 2024* <br>
*Arda Inceoglu, Eren Erdal Aksoy, Sanem Sariel* <br>
[PDF link](https://ieeexplore.ieee.org/document/10372079)

#### Video
[![FINO-Net](https://img.youtube.com/vi/G_XYHcRstYg/0.jpg)](https://www.youtube.com/watch?v=G_XYHcRstYg)


#### Citation
```
@inproceedings{inceoglu2020fino,
  title={FINO-Net: A Deep Multimodal Sensor Fusion Framework for Manipulation Failure Detection},
  author={Inceoglu, Arda and Aksoy, Eren Erdal and Ak, Abdullah Cihan and Sariel, Sanem},
  booktitle={IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)},
  year={2021},
}
```

```
@article{inceoglu2024multimodal,
  title={Multimodal Detection and Classification of Robot Manipulation Failures},
  author={Arda Inceoglu, Eren Erdal Aksoy, Sanem Sariel},
  journal={IEEE Robotics and Automation Letters (RA-L)},
  volume={9},
  issue={2},
  pages={1396-1403},
  year={2024},
  publisher={IEEE}
}
```


## FAILURE Dataset
[Download Data (~9.5GB compressed, ~20GB decompressed)](http://160.75.159.4/data/failure.zip)

[Download Annotations](https://github.com/ardai/fino-net/raw/main/annotation.zip)

Sample executions from the dataset:

<table style="width:100%">
    <tr>
        <th></th><th>Place</th><th>Pour</th><th>Put-In</th><th>Put-On</th><th>Push</th>
    </tr>
    <tr>
        <th>Success</th> 
        <td><img src="https://raw.githubusercontent.com/ardai/fino-net/main/assets/place_s.gif" width="112" height="112"/></td>
        <td><img src="https://raw.githubusercontent.com/ardai/fino-net/main/assets/pour_s.gif" width="112" height="112"/></td> 
        <td><img src="https://raw.githubusercontent.com/ardai/fino-net/main/assets/put_in_s.gif" width="112" height="112"/></td> 
        <td><img src="https://raw.githubusercontent.com/ardai/fino-net/main/assets/put_on_s.gif" width="112" height="112"/></td> 
        <td><img src="https://raw.githubusercontent.com/ardai/fino-net/main/assets/push_s.gif" width="112" height="112"/></td>
    </tr>
    <tr>
        <th>Failure</th> 
        <td><img src="https://raw.githubusercontent.com/ardai/fino-net/main/assets/place_f.gif" width="112" height="112"/></td> 
        <td><img src="https://raw.githubusercontent.com/ardai/fino-net/main/assets/pour_f.gif" width="112" height="112"/></td>
        <td><img src="https://raw.githubusercontent.com/ardai/fino-net/main/assets/put_in_f.gif" width="112" height="112"/></td> 
        <td><img src="https://raw.githubusercontent.com/ardai/fino-net/main/assets/put_on_f.gif" width="112" height="112"/></td>
        <td><img src="https://raw.githubusercontent.com/ardai/fino-net/main/assets/push_f.gif" width="112" height="112"/></td>
    </tr>
</table>
