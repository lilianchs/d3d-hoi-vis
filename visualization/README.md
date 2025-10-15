
## Exploring the Dataset

visualizer to explore the annotated ground-truth. A few example to visualize one video result is as follows:
```
python visualize_data.py --data_folder /data2/lilianch/D3D-HOI/d3dhoi_video_data/washingmachine/b007-0017/
                         --cad_folder /data2/lilianch/SAPIEN/process/WashingMachine
```
```
python visualize_data.py --data_folder /data2/lilianch/D3D-HOI/d3dhoi_video_data/washingmachine/b007-0017/
                         --cad_folder /data2/lilianch/SAPIEN/process/WashingMachine
```
```
python visualize_data.py --data_folder /data2/lilianch/D3D-HOI/d3dhoi_video_data/storage_prismatic/b108-0103
                         --cad_folder /data2/lilianch/SAPIEN/process/StorageFurniture
```
where the CAD files are stored at root: /data2/lilianch/SAPIEN/process/<category>
for categories: 
Dishwasher  Laptop  Microwave  Oven  Refrigerator  StorageFurniture  TrashCan  WashingMachine

and the data (intrinsics, 3d info, frames) are stored at /data2/lilianch/D3D-HOI/d3dhoi_video_data/<category>
for associated categories: 
dishwasher  laptop  microwave  oven  refrigerator  storage_prismatic  storage_revolute  trashcan  washingmachine
