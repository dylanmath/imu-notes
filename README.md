# imu-notes

When an object moves, its position changes as a function of time.  
A change in position is called a displacement.  
The position of an object is given relative to some agreed upon reference point.  
It is not enough to just specify the distance from the reference point.  We also have to specify the direction.  
Distance is a scalar quantity, it is a number given in some units.  
Position is a vector quantity.  It has a magnitude as well as a direction.  
The magnitude of a vector quantity is a number (with units) telling you how much of the quantity there is and the direction tells you which way it is pointing.  
In text, vector quantities are usually printed in boldface type or with an arrow above the symbol.  
Thus, while d = distance, d = displacement.

Scalars are quantities that are fully described by a magnitude (or numerical value) alone.
Vectors are quantities that are fully described by both a magnitude and a direction.

The speed of an object is the rate at which it covers distance.  The general formula for speed is distance divided by time.
speed = distance/time, v = d/t.

The speed of an object is a scalar quantity. It just tells us how fast the object is moving, but not in which direction it is headed.  

The vector quantity which specifies both the speed and the direction is called the velocity.  (Notation:  speed = v, velocity = v.)

Instantaneous Speed - the speed at any given instant in time.
Average Speed - the average of all instantaneous speeds; found simply by a distance/time ratio.

When the velocity of an object is changing, the object is accelerating.  
Acceleration is the rate at which the velocity is changing.  
The velocity can change because the speed is changing, or because the direction of travel is changing.  The key word is CHANGE.
Whenever your velocity is CHANGING, you are accelerating.  
You are accelerating when you CHANGE your speed, CHANGE your direction of travel, or both.
Velocity is a vector quantity that refers to "the rate at which an object changes its position.

The state of motion (i.e. the velocity) of any object is always defined with respect to a reference frame.

A quaternion is a four-element vector that can be used to encode any rotation in a 3D coordinate system.  Technically, a quaternion is composed of one real element and three complex elements, and it can be used for much more than rotations.  In this application note we'll be ignoring the theoretical details about quaternions and providing only the information that is needed to use them for representing the attitude of an orientation sensor.

Acceleromter

Positive values indicate an increase in velocity.
Negative values indicate an decrease in velocity.
Zero values indicate constant velocity (which might not be zero).

Gyroscope

Magnetometer

GPS

Pressure/Altitude
