# GameJamTextureScaler
Simple Unity3D script to instantiate and edit the tiling of materials in Edit Mode.

-------------

To use:
1. Clone the repo and drag the TextureScaler.cs script into your Unity project files. 

2. Attach TextureScaler to any GameObject with a MeshRenderer.

3. Drag a new material in and press the "Refresh Material" button in the Inspector, which saves and sets an instance of the current shared material (typically only done when the game is played) allowing it to be altered by the script.

4. If no sharedmaterial is found the material in the "Default Material" field is used.

--------------

Fields:
Auto Adjust Tiling X and Auto Adjust Tiling Y booleans can be toggled off to ignore tiling in the specified axis.
Auto Tiling Scale Factor multiplies the tiling in the x and y. 
Manual Tiling adds to the x and y tiling.
Manual Offset sets the material's UV in the x and y.

--------------

Notes:
- If instantiating from a prefab results in a missing material, it can likely be fixed by setting the default material field.
- I know the AutoTilingScaleFactor and ManualTiling are basically the same thing.
- The current version of the script does not rotate as it wasn't needed for the game jam it was written for. It can totally be added along with other great texture features to make your designer's life even easier.
- Made for the 2018 UCF vs. USF Summer Game Jam, hosted by the Game Dev Knights. Used in the game "Clothes Combat". 
- Free to use under the MIT License.

