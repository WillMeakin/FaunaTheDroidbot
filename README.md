Create A* search on grid (the environment)
Add obstacles to avoid
Trigger obstacles and recalculate path (what if obstacle removed?)
Interface movement with robot (omnidirectional wheels?)
Use computer vision to detect obstacles
Estimate what cells on grid are blocked by obstacle, update accordingly and repeatedly.
Track same object for two coordinates. Draw line and have intersected cells be third type of cell (non-preferable cells) that should be used only if no other path within sight or reasonable search.
Get time of both cells, and then calculate speed, and give each cell a range of time it will contain an obstacle.
Use three data points to calculate acceleration and curving
Add third dimension, look at obstacles descending, predict where they will land. (For footsteps)
Increase environment size, building to building. (Recognise doorways to break down search problem)
Use Google maps/street view to map streets. Footpaths and crossings are suitable environment cells.
Create environment grid from sensor data, for unexplored areas.
Lock destination to behind a person’s feet.
Voice commands (extend existing? Give Fauna a head to acknowledge with)

Novel Applications:
Replace guide dogs
Ferry packages around offices (hospitals? cities?)
Autonomously navigate/map minefields
Personal bag carrier

Could be solar powered
