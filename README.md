START

0. Visual C++ Redistributable for Visual Studio 2012 Update 4
https://www.microsoft.com/en-sg/download/details.aspx?id=30679
- install this thing for RTABMap to work (RTABMap is a pretty old software)

1. RTABMap
https://github.com/introlab/rtabmap/releases
download the .exe or the .zip

2. Unity 2019.4.34f1
https://unity3d.com/get-unity/download/archive
unity have become a pain the in ass, you need to 
- download unity hub
- then install Unity 2019.4.34f1
- Sign in (need an account)
- New project -> 3D

3. https://www.meshlab.net/
- download and install windows version


4. they Have a sample for .db point cloud to work with:
"Download this database: 2loops_workspace_3IT.db"

*** Convert .db to .ply without floating nan/inf error ***
Follow this page instructions for the first few steps on exporting:
https://github.com/introlab/rtabmap/wiki/Export-Raster-Layers-to-MeshLab
- follow step 1
- follow step 2
- follow step 3
- follow step 4
- follow step 5
- follow step 12
- stop
- open meshlab
- import mesh...
- select the export .ply from RTABMap, It should be able to load the mesh
- Export the mesh again as .ply file
*** Now ur .ply should be "clean up" without errors

*** set up/import into unity
1. https://www.youtube.com/watch?v=aKfPUCZYAhw

- the description have a workshop link:
https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqa2d0aDhaWUZieWZtMi0wekdjUmRKdVBucWktd3xBQ3Jtc0treGR2OXBkUWI5LVVpQ1JnSUxiWEJBUGNoNWc0RE1TNm93NUV2eU5zSW15STl6Q1VLQlh2QTEwZk5CRVpLUGhQaFl4U2VGV1czRlRhMkZhYkhyZ29DN2tFZVhyR1otbUpZbHMwN2NjVmdzLU9ORTJlNA&q=https%3A%2F%2Fwww.gardensandmachines.com%2FDownloads%2FAD41700%2FPointCloud_workshop.zip&v=aKfPUCZYAhw

You can follow the youtube instruction to import the .ply file normally

OR 

you can start the unity project with the default PCX (original file/plugin)
https://github.com/keijiro/Pcx/releases


Note:
you need to TRY IT yourself whether the PCX plugin are able to support for other unity version.
sometimes it may work, sometimes it won't. unity is shit and magical.

OR pay $100 dollar
https://assetstore.unity.com/packages/tools/utilities/point-cloud-viewer-and-tools-16019
(NOTE: have not bought this so have no idea if this works)


STOP
