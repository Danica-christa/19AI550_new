# Ex.No: 3  Basic movements in Unity 
### DATE:12/08/25                                                                          
### REGISTER NUMBER : 212223240022
### AIM: 
 To learn the basic movements translation,scaling and rotation of game objects through code.
### Procedure:
1. Setup the Scene
2. Open Unity and create a 3D Scene.
3. Add three objects:Cube → Rename to Object1 (for movement),Sphere → Rename to Object2 (for rotation).Capsule → Rename to Object3 (for scaling).
4. Add the Script,Create a C# Script → Name it TransformOperations.cs.
5. Write the code for translation,scaling and rotation,save and close the script
6. Save the script
7. Select any empty GameObject (or create one: GameObject → Create Empty).
8. Attach the TransformOperations script to it.
9. In the Inspector, assign Object1 → Drag the Cube,Object2 → Drag the Sphere.Object3 → Drag the Capsule.
10. Run the Scene Press Play ▶️ in Unity
11. Stop the program.
### Program 
```
using UnityEngine;
public class TransformOperations : MonoBehaviour
{
    public Transform o1;
 public Transform o2;
 public Transform o3;
 void Start()
 {
    

 }

 // Update is called once per frame
 void Update()
 {
     o1.Translate(0.2f, 0, 0);
     o2.Rotate(0.2f, 0, 0);
     o3.localScale += new Vector3(0, 0.2f, 0);
 }
}
```
### Output:

<img width="1919" height="1024" alt="Screenshot 2025-08-12 143931" src="https://github.com/user-attachments/assets/53d7172e-8d1e-4dc6-b85f-cf464d40f2cb" />

<img width="1919" height="1018" alt="Screenshot 2025-08-12 142430" src="https://github.com/user-attachments/assets/f60c79bb-2f50-486a-a9fc-0e3f38ff68b8" />

### Result:
Thus the basic movement is learned through scripting


