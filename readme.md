# Navmesh AI Tutorial 4 - Spawning Enemies
The below video is the tutorial that **ENDS** where this project is. You can mostly follow along by checking out part [3 How to Animate NavMeshAgents](https://github.com/llamacademy/ai-series-part-4). The scene is different, but the shape of the scene does not particularly matter, we just needed more space.

[![Youtube Tutorial](./Video%20Screenshot.png)](https://www.youtube.com/watch?v=5uO0dXYbL-s&ref=github)

**IMMEDIATELY AFTER CHECKING THIS OUT** IMPORT THE [UNITY CHAN MODEL](https://assetstore.unity.com/packages/3d/characters/unity-chan-model-18705) FROM THE UNITY ASSET STORE or you will be missing the model! (it's free)

In this project we have:
1. Simple click to move.
2. An enemy that follows the player
3. NavMeshLinks to allow the player and enemy to jump from one platform to another, and on top of some walls.
4. AgentLinkMover to control how NavMeshAgents will traverse NavMeshLinks
5. Animated 3D Model based on NavMeshAgent's movement
6. Dynamically spawned enemies at random points on the NavMesh
7. 2 Enemy types, configured via a ScriptableObject, that path differently based on Agent Configuration

## Requirements
* Requires Unity 2019.4 LTS or higher. 
* Utilizes the [Navmesh Components](https://github.com/Unity-Technologies/NavMeshComponents) from Unity's Github.
* [Unity-Chan Model](https://assetstore.unity.com/packages/3d/characters/unity-chan-model-18705) from the Unity Asset Store (it's free)