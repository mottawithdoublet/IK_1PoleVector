# IK_1PoleVector
Creates a 1 Pole Vector IK system for a double articulated limb, usually for creatures.
1) Select joints from bottom to top of the limb (4 joints, from end of limb without hands all the way to shoulder)
2) Creates necessary IK systems, constraints, controls and attributes in for Shoulder Sytem Ratio and Knee Bend Ratio. 
3) Ends up with "foot_Ctrl_Old" (import in use with the SDK_FootRig Script and LinkIK_1PoleVector Script)
4) If SDK_FootRig was used, then use LinkIK_1PoleVector next to tie the FootSystem and IK together.
5) Note:(Wouldn't it be nice for it to all be one button? But that way it works with the IK_2PoleVectorscript without so much brain energy.)
