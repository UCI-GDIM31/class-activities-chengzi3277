# in-class-activities
## Devlogs
### W1
Write your W1 activity Devlog here. Hello world!
Hello world!
### W2
Create future Devlog sub-headers with the three # symbols, then write your Devlogs below them.

1. becae r g b are floats because color values are continuous (0.0 ~ 1.0) and need decimals for smooth color changes.

2. because the bounce is an int because it counts whole bounce events—something you can’t do with fractions.

3. it shows"All compiler errors have to be fixed before you can enter playmode!UnityEditor.SceneView:ShowCompileErrorNotification ()， it means there something wrong of code like missing the symbol “ ； ”

### w3

1. table 19 : The SetLightDimness method takes the player’s sanity level as a float 0 ~ 100 , and because of it doesnt need a output so it has a void return type since it directly changes the room’s light brightness.

2. Classes are like cookie cutters, and Components are the cookies made from them.
Member variables are the ingredients that define each cookie’s traits, and methods are the actions it can do.

3. 
The balls get too bright because each bounce keeps adding light intensity with no limit.


### w4

1.   table 19 
  _isGrounded is a member variable of type boolean, used to track whether the character is on the ground.And the code will call a method to check When both the player click space and the cat is "isgrounded" , the if statement will be ture. And the last code  means when the cat start jumping the 'isgrounded' will be false, it limits jump of cat.

2. tablet 19
 ball and cat need rigidbody because they need phyiscal body when the cat hit the ball. the goal don't need a phyiscal body and it will check trigger because it need to record when the ball pass through the goal. during I add the component I find that the cat is floating on the sky. and the problem of this bug is that the size of collidor is too large after i edit the size the collider the cat will not floating

### w5

 1. Why use transform.Translate() in Unity?

 We use transform.Translate() to move a GameObject. It changes the object’s position in the game, making it move smoothly each frame.

 2. 
What method(s) does this class need? Should it be something that Unity provides (like Start(), Update(), or a collision method), or one you write?
Start and update methods should be provided by Unity. The methods should include move to target (for deer it should also be provided by unity AI navi mesh), play animation and a collision method to prevent object pass through each others. 

What should the method(s) do?
The methods should direct gameObjects to do what they purpose. For example direct the deer to the right place and play correct animation for each animals.


### w6

1. table 19  (part 2)
[https://docs.google.com/document/d/13WL1faOUeHHIt5U-4Nu450rY6-oTy8zhNi828PVl7UI/edit?pli=1&tab=t.0#heading=h.jo9rncec39bd](URL)

2. to design and implement a Unity C# script that controls bat behavior. The goal is to make all bats move toward the Cat using variables and methods that the BatManager can trigger.



Member Variables

Transform _target → reference to the Cat’s position.
float _speed → how fast the bat moves (adjustable in Inspector).
bool _isChasing → determines whether the bat is currently chasing.

Methods

Start() → runs once at the beginning; for testing, it should make the bat start chasing immediately.
Update() → runs every frame; moves the bat toward the Cat if _isChasing is true.
public void StartChasing() → sets _isChasing to true.
public void StopChasing() → sets _isChasing to false.

What the Methods Should Do

In Update():







## Open-Source Assets
### W1
- Animals: https://assetstore.unity.com/packages/3d/characters/animals/animals-free-animated-low-poly-3d-models-260727 
- Low-poly environment: https://assetstore.unity.com/packages/3d/environments/landscapes/low-poly-simple-nature-pack-162153 

