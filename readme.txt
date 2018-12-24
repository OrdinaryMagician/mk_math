Remember to prefix the classes if you use them in your project.

CoordUtil depends on Matrix4, so include them together.

Including the license file is optional, but recommended.

The matrix and quaternion classes don't offer as much functionality as their
equivalents in Gutamatics, but they should provide what's "essential" for most
basic tasks.

The relative axes returned by Matrix4.GetAxes use left-hand coordinates.
That is, positive Y means "to the right".
