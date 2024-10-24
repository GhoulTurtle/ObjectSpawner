<h1>Object Spawner</h1>
 
 ### [YouTube Demonstration](https://www.youtube.com/watch?v=KcpgkjVf-rs)

<h2>Description</h2>
Project consists of a spawner script that allows users to customize the spawner in different ways. This includes: a list of objects this spawner can spawn, if the object has physics, the amount of objects, and finally the area that the objects can spawn in. Each shape has its own ShapeObject scriptable object that defines what the shape is. These definitions including: shape, color, and size. Both scripts have custom editors to make the process of defining these parameters more design friendly. 
<br/>

<h2>Languages and Enviroments</h2>

- Unity
- C#
- Windows 10
- Visual Studio Code

<h2>Libraries</h2>

- UnityEngine
- UnityEditor
- System.Collections
- System.Collections.Generic

<h2>System Walkthrough:</h2>
<p align="center">
Create a new shape object using the create menu: <br/>
<img src="https://i.imgur.com/MaAmuA6.png" height="60%" width="60%" alt="Object Spawner Steps"/>
<br />
<br />
Fill out the shape object details: <br/>
<img src="https://i.imgur.com/B99ZFpg.png" height="60%" width="60%" alt="Object Spawner Steps"/>
<br />
<br />
Attach the ObjectSpawner script to a gameobject: <br/>
<img src="https://i.imgur.com/pyL4uv3.png" height="60%" width="60%" alt="Object Spawner Steps"/>
<br />
<br />
Populate the shape object list: <br/>
<img src="https://i.imgur.com/cf03WCk.png" height="60%" width="60%" alt="Object Spawner Steps"/>
<br />
<br />
Customize the spawner: <br/>
<img src="https://i.imgur.com/QiciTCy.png" height="60%" width="60%" alt="Object Spawner Steps"/>
<br />
<br />
The Gizmos in the scene will update according to the spawner area settings: <br/>
<img src="https://i.imgur.com/p4cF7P0.png" height="70%" width="70%" alt="Object Spawner Steps"/>
<br />
<br />
Press play to start the spawner: <br/>
<img src="https://i.imgur.com/Gq8TbdC.png" height="70%" width="70%" alt="Object Spawner Steps"/>
<br />
<br />
The console will update when the spawner has finished: <br/>
<img src="https://i.imgur.com/htIFj5U.png" height="70%" width="70%" alt="Object Spawner Steps"/>

