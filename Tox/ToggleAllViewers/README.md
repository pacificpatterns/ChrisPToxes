# ToggleAllViewers
 
## *Turning off op viewers can significantly cut down on resourses.*


### Open this tox in any touchDesigner network to toggle viewer state of every node from off and on[^1]

[^1]: Don't forget to make the viewer active by highlighted this component and pressing 'a' on the keyboard


'Recursive' set to **off** :

	the button will toggle all viewers from on to off in the current network.

'Recursive' set to **on** :

	Make sure to choose the desired state by pressing the button that appears on the container
	Increase max depth until the ops counter goes as high as possible and stops increasing. 
	By default it is set to 25, which should be more than enough in most cases.
	When max depth is set to 0 it will only effect nodes in the same network that this OP has been loaded into.
	when max depth is increased, nodes within subnetworks will be affected according to the level of defpath
	Minimm depth works the opposite direction as max depth.

