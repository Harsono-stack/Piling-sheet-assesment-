# Piling-sheet-assesment-
Asessing the corrosion on piling sheet according to NEN and estimating distance between the bumps. Two classificiation algorithm have been made:
1. Classification with four classes: Grass, Metal good, Metal bad and Rock.
2. Classification with six classes: Grass, Metal good, Metal acceptable, Metal moderate and Metal bad and Rock.

After the assesment the images that have been labeled with "Metal" will be sent through an Object detection algorithm that was made using YOLOv4. This algorithm was trained to detect: the bumps of a piling sheet and a reference object. The reference object was something that was seen on most piling sheet in which we know the actual dimension. The horizontal distance between the bumps was calculated and using the reference object we converted the pixel distance into actual distance.

The data can be downloade from [Kaggle](https://www.tutorialsandyou.com/markdown/how-to-add-links-in-markdown-12.html)
Codes and files will be uploaded later as we still need get permission on what is allowed to be made open.
--Uploaded a few things. More will come hold on
