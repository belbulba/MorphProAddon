# MorphPro Blender Addon
# Get addon at **[Gumroad](https://23dstudio.gumroad.com/l/morphpro)**
This is user guide for **MorphPro Blender Addon**

<img width="1000" height="1000" alt="MorphProThumbnail" src="https://github.com/user-attachments/assets/a01f3f69-8d16-4cbf-bdac-9704afccd670" />

# Get addon at **[Gumroad](https://23dstudio.gumroad.com/l/morphpro)**

## Installing Addon
1) Go to **Edit > Preferences > Add-ons** and select drop-down arrow. There select **"Install From Disk..."** and open **.py** addon file from your device.

   <img width="202" height="76" alt="image" src="https://github.com/user-attachments/assets/40b81931-642a-42a9-b9ab-e8320ef51b84" />

2) When script is installed you can find addon in navigation bar

   <img width="350" height="606" alt="image" src="https://github.com/user-attachments/assets/e2ab50ac-442a-4efa-be0e-403e2b179395" />

## How to use

1. Select 1st group of objects and hit "Assign Hide Collection"
2. Select 2nd group of objects and hit "Assign Reveal Collection"
3. As addon created corresponding collections now create controller with "Create Morph Controller" button
4. Move controller along Y axis to create morph animation
![Gif2](https://github.com/user-attachments/assets/31eca6b0-07b9-4d23-b9a6-63f617e1a587)

### Settings

Use **"Falloff Controls"** to change how far controller can morph objects. Set this value from 0 to 10.

Use **"Additional Rotation"** to add rotation to objects while they morph. Set whis value to any number.

Use **"Jump Height"** to add objects transition while they morph. Change "Jump Axis" to choose transition direction.


![Gif3](https://github.com/user-attachments/assets/d2c95a59-ce93-4a18-9965-f4777600b2db)

Use **"Jump Along Normals"** checkbox to make objects morph in spherical shape.

![Gif4](https://github.com/user-attachments/assets/e365b036-263e-42ea-a6c0-f4d5782e5253)

Use **"Enable Noise"** to add random movement to objects animations.

![Gif5](https://github.com/user-attachments/assets/196005af-d7d3-4e06-83c4-1fdc737ee1d6)

Choose **noise pattern** in dropdown below checkbox to change noise behavior.

<img width="321" height="119" alt="image" src="https://github.com/user-attachments/assets/f5a66a9e-eec8-489e-9e74-f2b99679b2d1" />

- **"Per Object"**: objects at same location could be transformed differently.
- **"Per Location"**: object as same location will be transformed exactly same.
- **"Per Y Location"**: all objects with same Y location will be transformed exactly same.

Use **"Update Morph Drivers"** button to fix some issues when changing settings. For exmaple when moving 3D cursor in **"Jump Along Normals"** mode it will apply new 3D cursor position to objects.

<img width="336" height="81" alt="image" src="https://github.com/user-attachments/assets/7df62416-8868-4879-866a-4e2fd6982306" />

Use **"Remove Morph"** button to delete all drivers and script influence in general.

## Additional Usage

Pretty obvious, but you can simply hide any collection to create reveal animation like this

![Gif6](https://github.com/user-attachments/assets/b2d040a6-7713-4677-add3-5932d90c1011)

## 

If you have any suggestions or bug issues then you can always contact me at Gumroad.

















