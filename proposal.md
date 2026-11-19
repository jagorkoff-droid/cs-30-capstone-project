# Description
3D online first-person shooter game, 2 teams in a bomb planters vs bomb defenders scenario.


## Needs to have:
- WASD movement in a 3D space, SPACEBAR to jump
- Left shift to sprint, increasing movement speed
- Left ctrl to crouch, decreasing movement speed and height
- Corresponding animations for each action that other players are able to see
- Multiple weapons, cycled through using the mouse scroll wheel, or the number keys on the keyboard
- Recoil and spray patterns, recoil is variable for each gun
- A purchasing menu with a credit system that allows you to buy different weapons
- Hitboxes that apply different damage and also different damage depending on the gun used

## Nice to have
- Rendering using p5.js WEBGL
- Use Cannon-es or Rapier for 3d collision physics
- Create a node.js backend server using Websockets or WebRTC, this server must run a “headless” version of the physics engine to verify player positions and confirm hits
- Use Electron or Tauri to package the HTML/p5.js code into a standalone .exe or .app
- Must integrate Steamworks.js library inside Electron app to use Steam features