# ⭕ APCSA-1B-RoundThings ⭕

In this project you will write a Java program that calculates and displays the area and circumference of a circle and the volume and surface area of a sphere. You will be writing two classes for this program. One will use the RoundThingsDriver class and the other will use the RoundThings class.

## 🛠️ Instructions

### Class Name: RoundThings
There will not be a main method in this class. This class will just have four methods.

*Methods*

All these methods will be static. Use Math.PI for pi. The radius parameter will be a double value. 
- [ ] calcAreaCircle() - receives the radius of a circle, and returns the area 
- [ ] calcCircumCircle() - receives the radius of a circle and returns the circumference
- [ ] calcAreaSphere() - receives the radius of a Sphere and returns the area
- [ ] calcVolumeSphere() - receives the radius of a Sphere and returns the volume - watch out for integer division!

### Class Name: RoundThingsDriver
This will have a main method and will call on methods from RoundThings.

*Variables:*

- [ ] radius - input variable, a double value (to be gotten from the user using a Scanner)
- [ ] area - a double value returned from the calcAreaCircle method
- [ ] circumference - a double value returned from the calcCircumCircle method
- [ ] surfaceArea - a double value returned from the calcAreaSphere method
- [ ] volume - a double value returned from the calcVolumeSphere method


#### Processing: 
- [ ] In main, declare all variables listed above and create a Scanner object. 
- [ ] Prompt the user to enter a value for the radius and store that value into the appropriate variable. 
- [ ] Call the methods you wrote in RoundThings and store the results into the appropriate variables.
#### Method: outPut

This method will receive 4 values as parameters: a description of the type of value calculated (i.e. circumference, area, volume, surface area), one for the shape name (i.e. circle or sphere), one for the radius inputted by the user, and one for the actual value calculated. It will display (print) the information formatted nicely (see below).

```console
The area of a circle with a radius of # is #.
The volume of a sphere with a radius of # is #. 
(# will be replaced by the appropriate value)
```

In main, call the outPut method four times. The first time should be for the area of a circle. The second time should be for the circumference of a circle. The third time should be for the surface area of a sphere. The fourth time should be for the volume of a sphere. They should all use the same radius value.
