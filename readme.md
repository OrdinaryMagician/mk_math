Remember to change the class prefix if you use them in your project.

The quaternion class doesn't offer as much functionality as its equivalent in
[Gutamatics](https://gitlab.com/Gutawer/gzdoom-gutamatics/), but it should
provide what's "essential" for 6DOF rotation and the like.

The relative axes returned by CoordUtil.GetAxes use left-hand coordinates by
default (i.e.: positive Y means "to the right"), there's an optional parameter
to use right-handed Y if you want it.
