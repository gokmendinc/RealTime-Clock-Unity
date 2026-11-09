Unity Real-Time Clock Prefab
A lightweight, ready-to-use clock prefab for Unity that automatically syncs with system time (DateTime.Now) and features smooth, continuous rotation for hour, minute, and second hands.

Features
Real-Time Sync: Automatically pulls local system time every frame.

Smooth Sweeping Motion: Uses fractional offsets and milliseconds so all hands move continuously rather than snapping abruptly.

Plug-and-Play Prefab: Simply attach the script, assign your hand GameObjects, and place it into your scene.

Zero Dependencies: Built entirely with native C# and standard UnityEngine libraries.

Installation & Setup
Clone or download this repository into your Unity project's Assets folder.

Drag the ClockPrefab into your scene hierarchy.

Select the clock object, find the ClockController component in the Inspector, and assign your child GameObjects:

Hand Hour

Hand Min

Hand Second

Important: Ensure the pivot point (origin) of each hand model or sprite is set to its base so it rotates correctly around its axis.

License
Distributed under the MIT License. Feel free to use it in your personal and commercial Unity projects!
